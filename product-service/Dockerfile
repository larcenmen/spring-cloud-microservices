FROM maven:3.3.9-jdk-8-alpine
MAINTAINER ziedyazidi
RUN apk --no-cache add netcat-openbsd
COPY target/product-service-0.0.1-SNAPSHOT.jar /opt/lib/
ADD wait-for-it.sh /wait-for-it.sh
RUN chmod 755 /wait-for-it.sh
EXPOSE 9999