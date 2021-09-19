FROM node:10

WORKDIR /app

RUN apt-get update && \
    apt-get install -y git && \
    apt-get upgrade -y && \
    git clone https://github.com/rearc/quest .
    
RUN npm install

EXPOSE 3000

ENTRYPOINT npm run start

