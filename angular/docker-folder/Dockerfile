FROM alpine:3.8

RUN apk add --update nodejs nodejs-npm
RUN apk add git
RUN apk add curl

RUN git config --global user.email "farshad.ahmadi.gh@gmail.com"
RUN git config --global user.name "farshad"
RUN npm install -g @angular/cli

WORKDIR /home/application

CMD ng serve --host 0.0.0.0