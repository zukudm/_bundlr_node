FROM node:14-alpine

ARG FILE_NAME

RUN apk add --no-cache git

RUN npm install -g arweave-deploy

RUN touch $FILE_NAME

CMD ["sh"]

