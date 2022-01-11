FROM openjdk:8-jdk-alpine
VOLUME /tmp
EXPOSE 80
ADD spring-boot-web-application-example-0.0.1-SNAPSHOT.war app.war
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /app.war" ]
