FROM alpine:3.17

RUN apk update && \
    apk upgrade && \
    apk --no-cache add curl bash && \
    rm -rf /var/cache/apt/*

RUN curl -L https://github.com/hasura/graphql-engine/raw/stable/cli/get.sh | bash
