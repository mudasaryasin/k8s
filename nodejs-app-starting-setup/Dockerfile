FROM node

WORKDIR /app
COPY . /app
#COPY . . same as above command 

RUN nmp install

EXPOSE 80
CMD node server.js
#RUN node server.js, it will run the server in image that is not required. so we will use CMD, it will execute when image will run. 
#https://www.udemy.com/course/docker-kubernetes-the-practical-guide/learn/lecture/22166778#overview
