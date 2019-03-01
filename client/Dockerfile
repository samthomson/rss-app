FROM mhart/alpine-node

WORKDIR /client

EXPOSE 3000

ADD . /client

RUN yarn

RUN yarn run build

CMD yarn run start