FROM alpine

RUN apk add nginx && \
    mkdir /www
    
#COPY nginx.conf /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY index.html /www/

CMD ["nginx", "-g", "daemon off;" ]
