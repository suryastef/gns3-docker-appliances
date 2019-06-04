FROM alpine:latest
MAINTAINER developers@gns3.net

ENV TZ=Asia/Jakarta

RUN apk add --update --no-cache dnsmasq tzdata

COPY boot.sh .

CMD /bin/sh boot.sh
