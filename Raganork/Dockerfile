FROM souravkl11/kellymowl:test

RUN git clone https://github.com/souravkl11/Raganork/ /skl/KELLYMOWLV2
WORKDIR /skl/raganork 
ENV TZ = Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "kelly.js"]
