FROM openjdk:8-alpine
RUN mkdir -p /opt/ToDoQueryService
WORKDIR /opt/ToDoQueryService
COPY target/ToDoQueryService-0.0.1-SNAPSHOT.jar /opt/ToDoQueryService
CMD ["java", "-Dspring.profiles.active=k8s", "-jar", "ToDoQueryService-0.0.1-SNAPSHOT.jar"]