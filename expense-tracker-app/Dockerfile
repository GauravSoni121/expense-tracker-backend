FROM eclipse-temurin:17-jdk
WORKDIR /app
COPY target/expense-tracker-app-0.0.1-SNAPSHOT.jar /app/expense-tracker-app-0.0.1-SNAPSHOT.jar
EXPOSE 9090
ENTRYPOINT ["java","-jar","expense-tracker-app-0.0.1-SNAPSHOT.jar"]
