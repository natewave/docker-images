FROM openjdk:11-alpine

RUN apt-get install -y curl \
  && curl -sL https://deb.nodesource.com/setup_8.x | bash - \
  && apt-get install -y nodejs \
  && curl -L https://www.npmjs.com/install.sh | sh
RUN apt-get install -y openssh-client
RUN npm install -g gulp-cli shadow-cljs
