FROM openjdk:8-alpine
RUN mkdir -p /opt/todoserviceregistry
WORKDIR /opt/todoserviceregistry
COPY target/todoserviceregistry-0.0.1-SNAPSHOT.jar /opt/todoserviceregistry
CMD ["java", "-Dspring.profiles.active=k8s", "-jar", "todoserviceregistry-0.0.1-SNAPSHOT.jar"]