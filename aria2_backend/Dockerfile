FROM alpine
RUN apk add --update aria2
RUN mkdir /etc/aria2
RUN mkdir /downloads
RUN touch /etc/aria2/aria2.session
RUN chmod 777 /etc/aria2/aria2.session
COPY aria2.conf /etc/aria2/aria2.conf

CMD ["aria2c", "--conf-path=/etc/aria2/aria2.conf"]

EXPOSE 6800
