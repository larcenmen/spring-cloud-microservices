FROM maven:3.3.9-jdk-8-alpine
MAINTAINER ziedyazidi
COPY target/config-service-0.0.1-SNAPSHOT.jar /opt/lib/
ENTRYPOINT ["/usr/bin/java"]
CMD ["-jar", "/opt/lib/config-service-0.0.1-SNAPSHOT.jar"]
EXPOSE 8888