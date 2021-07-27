FROM fusuf/whatsasena:latest

RUN git clone https://github.com/tompusa/test-bot /root/test-bot
WORKDIR /root/test-bot/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
