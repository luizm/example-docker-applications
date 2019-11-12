FROM node:latest
LABEL maintainer="Luiz Muller <luizmuller.it@gmail.com>" \
    description="Docker image used by web application"
COPY . /app
WORKDIR /app
RUN npm install && \
    rm -f .npmrc
CMD [ "npm", "start" ]
