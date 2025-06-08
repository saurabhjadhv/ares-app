FROM node

ADD . /app

WORKDIR /app

RUN npm install

RUN npm install express

ENTRYPOINT [ "npm" ]

CMD [ "start" ]