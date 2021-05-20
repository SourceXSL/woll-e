FROM fusuf/whatsasena:latest

RUN git clone https://github.com/SourceXSL/woll-e /root/woll-e
WORKDIR /root/woll-e/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
