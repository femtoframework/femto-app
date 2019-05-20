FROM openjdk:8-jdk-alpine

WORKDIR /app

EXPOSE 9169
COPY target/${artifactId}-executable.jar /app/

ENTRYPOINT exec java $JAVA_OPTS -jar ./${artifactId}-executable.jar
