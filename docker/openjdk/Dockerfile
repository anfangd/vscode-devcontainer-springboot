# [Choice] Alpine version: 3.12, 3.11, 3.10
ARG JDK_VERSION="15"
ARG ALPIN_VERSION="3.12"
#FROM mcr.microsoft.com/vscode/devcontainers/base:0-alpine-${VARIANT}
FROM openjdk:${JDK_VERSION}-jdk-alpine${ALPIN_VERSION}

# ** [Optional] Uncomment this section to install additional packages. **
# RUN apk update \
#     && apk add --no-cache <your-package-list-here>
RUN apk update \
    && apk add git curl maven make
