FROM ruby:3.2.2-alpine

# Install build tools to allow native gem extensions to build:
RUN apk add --no-cache --update build-base \
    linux-headers \
    git \
    postgresql-dev \
    nodejs \
    npm \
    tzdata \
    tar \
    gzip \
    ca-certificates \
    gcompat
RUN npm install -g yarn
