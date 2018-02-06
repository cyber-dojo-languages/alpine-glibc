FROM  alpine:latest
LABEL maintainer=jon@jaggersoft.com

ADD install.sh /

RUN /install.sh \
  && rm -f /install.sh

ENV LANG=C.UTF-8

RUN cat /etc/issue | grep 3.7
