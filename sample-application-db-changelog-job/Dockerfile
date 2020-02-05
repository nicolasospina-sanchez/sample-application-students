# Run
FROM openjdk:11-jre-slim

COPY target/*-exec.jar /opt/myapp/dbapp.jar

ENTRYPOINT ["java", "-jar", "/opt/myapp/dbapp.jar"]

