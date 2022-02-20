FROM fusuf/whatsasena:latest

RUN git clone https://github.com/abu146/RANGNORK /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Ajx-Abu/media

CMD ["node", "bot.js"]
