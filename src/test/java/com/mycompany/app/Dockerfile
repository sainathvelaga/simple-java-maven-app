   FROM openjdk:11-jdk
   WORKDIR /app
   COPY . /app
   RUN ./gradlew build
   CMD ["java", "-jar", "build/libs/your-app.jar"]
