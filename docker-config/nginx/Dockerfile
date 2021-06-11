FROM alpine:3.6

RUN apk update && \
    apk add --no-cache nginx


# CMD nginx -g 'pid /tmp/nginx.pid;'
RUN mkdir -p /run/nginx
# RUN apk add openssl
# ADD ssl /etc/nginx/ssl

CMD nginx -g "daemon off;"

