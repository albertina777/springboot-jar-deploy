FROM registry.access.redhat.com/ubi9/openjdk-17:1.17-1.1705573248

WORKDIR /app
COPY --chown=185 target/demo-0.0.1-SNAPSHOT.jar /app

EXPOSE 8080
USER 185

ENTRYPOINT [ "java", "-jar", "/app/demo-0.0.1-SNAPSHOT.jar" ]