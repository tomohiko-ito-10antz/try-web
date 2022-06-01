FROM node:16-bullseye-slim

ENV DEBIAN_FRONTEND=noninteractive

RUN apt update -y && apt install -y npm git curl \
    && npx -y n 16.15.0 \
    && npm install -g npm@8.11.0
WORKDIR /try-web
#ENV PATH=/try-web/node_modules;$PATH