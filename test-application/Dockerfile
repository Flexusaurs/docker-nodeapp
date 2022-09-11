FROM node:18

WORKDIR /anewproj/test-application

COPY  package*.json ./

RUN npm ci

COPY . .
ENTRYPOINT [ "./index.js" ]
CMD ["node", "index.js"]
