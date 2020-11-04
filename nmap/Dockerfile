FROM alpine:latest
LABEL maintainer="info@practical-devsecops.com"

RUN apk -U upgrade \
    && apk add --no-cache \
        nmap \
        nmap-scripts \
    && rm -rf /var/cache/apk/*

ENTRYPOINT ["nmap"]
CMD ["-h"]