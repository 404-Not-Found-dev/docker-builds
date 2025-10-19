FROM alpine:latest

RUN apk add --no-cache bind-tools curl iputils && \
    rm -rf /var/cache/apk/* /tmp/* /var/tmp/*

CMD ["/bin/sh"]
