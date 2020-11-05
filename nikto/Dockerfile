FROM alpine:latest
LABEL maintainer="info@practical-devsecops.com"

RUN apk -U upgrade \
    && apk add --no-cache \
        nikto \
        openssl \
        perl-net-ssleay \
    && rm -rf /var/cache/apk/*

ENTRYPOINT ["nikto.pl"]
CMD ["-h"]