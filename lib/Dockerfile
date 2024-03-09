FROM quay.io/sampandey001/secktor
RUN https://github.com/MalakHaroon/Itx_Hayat_Bot /root/Itx_Hayat_bot
WORKDIR /root/Itx_Hayat_bot/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
