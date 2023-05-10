FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
COPY target/*.jar ims.jar
ENTRYPOINT ["java", "-jar", "/ims.jar"]
EXPOSE 8080