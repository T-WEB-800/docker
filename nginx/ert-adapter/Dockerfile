FROM alpine:3.19

RUN apk add --update --no-cache nginx

COPY nginx.conf /etc/nginx/nginx.conf
COPY ./ert-adapter/ert-adapter.conf /etc/nginx/conf.d/

RUN adduser -D -g '' -G www-data www-data

CMD nginx