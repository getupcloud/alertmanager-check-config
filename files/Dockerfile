FROM alpine

RUN mkdir -p /config

WORKDIR /config

COPY run.sh /config/

RUN apk add nmap-ncat bash --no-cache && \
    chmod +x run.sh

USER 1001

CMD ["./run.sh"]


