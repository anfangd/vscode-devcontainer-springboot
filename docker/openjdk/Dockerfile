ARG JDK_VERSION="15"
ARG ALPIN_VERSION="3.12"

FROM openjdk:${JDK_VERSION}-jdk-alpine${ALPIN_VERSION}

RUN apk update \
    && apk add git curl maven mysql-client
