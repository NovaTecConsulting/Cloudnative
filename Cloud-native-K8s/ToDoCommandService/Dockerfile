FROM openjdk:8-alpine
RUN mkdir -p /opt/ToDoCommandService
WORKDIR /opt/ToDoCommandService
COPY target/ToDoCommandService-0.0.1-SNAPSHOT.jar /opt/ToDoCommandService
CMD ["java", "-Dspring.profiles.active=k8s", "-jar", "ToDoCommandService-0.0.1-SNAPSHOT.jar"]