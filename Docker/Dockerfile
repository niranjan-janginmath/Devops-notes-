QUESTION 1
Build a custom docker image using Ubuntu as a base docker image and run the nginx application. - this docker image should be built using a Dockerfile. Once the docker image is build, start the docker
image using the host network and make it accessible on Public IP

FROM ubuntu:18.04

RUN apt-get update
RUN apt-get install -y nginx 
RUN mkdir /tmp/docker
RUN touch /tmp/docker/test.txt

EXPOSE 80
CMD /usr/sbin/nginx -g "daemon off;"




QUESTION 2


