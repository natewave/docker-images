FROM openjdk:11.0-jdk-slim

RUN apt-get update
RUN apt-get install -y openssh-client
RUN apt-get install -y curl \
  && curl -sL https://deb.nodesource.com/setup_8.x | bash - \
  && apt-get install -y nodejs \
  && curl -L https://www.npmjs.com/install.sh | sh
RUN npm install -g gulp-cli shadow-cljs
