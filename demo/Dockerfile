# Version: 0.0.1
FROM ubuntu
MAINTAINER colddew "88028842@qq.com"
ENV REFRESH_DATE 2018-05-22
WORKDIR /tmp/docker/webserver
RUN apt-get update && apt-get install -y nginx
RUN echo 'hello world' > /usr/share/nginx/html/index.html
EXPOSE 80
# docker run -it colddew/ubuntu -g "daemon off;"
ENTRYPOINT ["/usr/sbin/nginx"]
CMD ["-h"]
