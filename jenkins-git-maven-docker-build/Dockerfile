FROM java:8
ARG JAR_FILE=jenkins-git-maven-docker-build/target/teacher-service.jar
COPY ${JAR_FILE} app.jar

ENTRYPOINT ["java","-jar","app.jar"]
