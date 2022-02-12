FROM fusuf/whatsasena:latest

RUN git clone https://github.com/WVFX1029/Slayer-USERBOT /skl/Raganork
WORKDIR /skl/Raganork
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "index.js"]
