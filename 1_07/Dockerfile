#Create a Dockerfile for a new image that starts from ubuntu:24.04 and add instructions to install curl into that image. 
#Then add instructions to copy the script file into that image and finally set it to run on container start using CMD.

FROM ubuntu:24.04

WORKDIR /usr/src/app

RUN apt-get update

RUN apt-get install -y curl

COPY script.sh .

CMD ["./script.sh"]