FROM  alpine:latest
LABEL maintainer=jon@jaggersoft.com

ENV LANG=C.UTF-8

ADD install.sh /

RUN /install.sh \
  && rm -f /install.sh
