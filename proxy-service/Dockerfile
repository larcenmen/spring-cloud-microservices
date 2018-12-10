FROM maven:3.3.9-jdk-8-alpine
MAINTAINER javaonfly
RUN apk --no-cache add netcat-openbsd
COPY target/proxy-service-0.0.1-SNAPSHOT.jar /opt/lib/
ADD wait-for-it.sh /wait-for-it.sh
RUN chmod 755 /wait-for-it.sh
EXPOSE 9999