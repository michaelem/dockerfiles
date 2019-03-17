FROM ruby:alpine

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
                                ca-certificates
RUN npm install -g yarn
