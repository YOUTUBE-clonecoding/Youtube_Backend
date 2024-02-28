# FROM java:17
# ARG JAR_FILE=build/libs/*.jar
# COPY ${JAR_FILE} studymate.jar
# ENTRYPOINT ["java","-jar","/studymate.jar"]

FROM openjdk:17
COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
RUN javac ./src/main/java/backend/backend/BackendApplication.java