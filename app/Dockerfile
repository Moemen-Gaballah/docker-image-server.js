FROM node:13-alpine

ENV MONGO_DB_USERNAME=admin \
	MONGO_DB_PWD=password

#RUN mkdir -p /home/app

#COPY ./app /home/app

COPY ./app .

RUN npm install

#RUN ls home/app

#RUN cd home/app 

#RUN ls home/app

CMD ["node", "server.js"]