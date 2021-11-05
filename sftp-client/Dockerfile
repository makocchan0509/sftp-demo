FROM alpine:latest
RUN apk update
RUN apk add --update --no-cache openssh curl bash python
RUN curl -sSL https://sdk.cloud.google.com | bash
ENV PATH $PATH:/root/google-cloud-sdk/bin
