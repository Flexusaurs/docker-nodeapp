FROM node:18

WORKDIR /anewproj/test-application

COPY  package*.json ./

RUN yarn

COPY . .
ENTRYPOINT [ "./index.js" ]
CMD ["node", "index.js"]