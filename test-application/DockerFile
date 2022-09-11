FROM node:16

WORKDIR /anewproj/test-application

COPY  package*.json ./

RUN npm install

COPY . .
ENTRYPOINT [ "./index.js" ]
CMD ["node", "index.js"]
