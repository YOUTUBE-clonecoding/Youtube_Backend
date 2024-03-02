# FROM java:17
# ARG JAR_FILE=build/libs/*.jar
# COPY ${JAR_FILE} studymate.jar
# ENTRYPOINT ["java","-jar","/studymate.jar"]

# FROM openjdk:17
# COPY . /usr/src/myapp
# WORKDIR /usr/src/myapp
# RUN ./gradlew build
# ENTRYPOINT ["java","-jar","build/libs/backend-0.0.1-SNAPSHOT.jar"]
# RUN javac ./src/main/java/backend/backend/BackendApplication.java

FROM openjdk:17-jdk
ARG JAR_FILE=build/libs/*.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]