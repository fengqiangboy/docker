FROM node:8-alpine

RUN mkdir /usr/app \
&& cd /usr/app \
&& mkdir /usr/work

WORKDIR /usr/app

ADD ./build.sh /usr/work/build.sh

CMD [ "sh" , "/usr/work/build.sh"]
