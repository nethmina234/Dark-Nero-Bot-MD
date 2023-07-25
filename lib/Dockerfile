FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/Kaveeshasithum/Dark-Nero-Bot-MD /root/Kaveeshasithum
WORKDIR /root/Kaveeshasithum/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]

