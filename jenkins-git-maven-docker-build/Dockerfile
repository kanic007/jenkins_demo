FROM java:8
ARG JAR_FILE=target/teacher-service.jar
COPY ${JAR_FILE} app.jar
EXPOSE 9090
ENTRYPOINT ["java","-jar","app.jar"]