FROM node:16-alpine3.14

WORKDIR /app

RUN apk update && \
    npm install -g npm && \
    npm install -g @vue/cli

EXPOSE 8080
ENV HOST 0.0.0.0