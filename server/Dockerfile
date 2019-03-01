FROM mhart/alpine-node

WORKDIR /server

EXPOSE 3100

ADD . /server

RUN yarn

RUN yarn global add ts-node

RUN yarn build

CMD yarn start