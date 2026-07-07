FROM openjdk:17
WORKDIR /app
COPY target/expense-tracker-app-0.0.1-SNAPSHOT.jar /app/expense-tracker-app-0.0.1-SNAPSHOT.jar
EXPOSE 9090
ENTRYPOINT ["java","-jar","expense-tracker-app-0.0.1-SNAPSHOT.jar"]
