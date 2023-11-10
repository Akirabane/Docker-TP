# Utilisation d'une image de base contenant Java
FROM openjdk:17:11-alpine

WORKDIR ./back

COPY target/spring-boot-data-jpa-0.0.1-SNAPSHOT.jar .

EXPOSE 8080

CMD ["java", "-jar", "spring-boot-data-jpa-0.0.1-SNAPSHOT.jar"]
