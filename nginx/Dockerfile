FROM alpine:latest
RUN apk add --update nginx openrc
COPY nginx.conf /etc/nginx/nginx.conf

CMD echo "Nginx is up and running - http://localhost:1234" && nginx
