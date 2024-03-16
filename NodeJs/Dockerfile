FROM ubuntu:latest

ENV TZ=Asia/Kolkata
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

RUN apt update && apt upgrade -y

RUN apt install curl git -y

RUN curl -fsSL https://deb.nodesource.com/setup_lts.x | bash -

RUN apt install nodejs -y

RUN npm i -g npm

RUN npm i -g yarn

RUN npm i -g pnpm
