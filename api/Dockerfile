FROM node:13.12.0-alpine3.10

ENV PORT 8090

WORKDIR /srv/app/

RUN apk update && apk add git && apk add curl

RUN curl -o- -L https://yarnpkg.com/install.sh | sh

RUN git clone 

RUN yarn

EXPOSE ${PORT}

CMD ["yarn", "start"]