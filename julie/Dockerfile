FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/FAYASSER-V3/KELLYMOWL-V3 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/FAYASSER-V3/Nandhuttynew
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
