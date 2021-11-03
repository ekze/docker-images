FROM postgres:14.0-alpine

# Setup timezone to Europe/Moscow
RUN apk add tzdata && \
    cp /usr/share/zoneinfo/Europe/Moscow /etc/localtime && \
    echo "Europe/Moscow" >  /etc/timezone && \
    apk del tzdata
