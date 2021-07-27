FROM fusuf/whatsasena:latest

RUN git clone https://github.com/tompusa/TestBot /root/TestBot
WORKDIR /root/TestBot/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
