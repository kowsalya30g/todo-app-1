FROM maven:3.5-jdk-8
COPY artifacts/todo-app/TodoDemo-0.0.1-SNAPSHOT.war app.war
ENTRYPOINT [ "java","-jar","app.war" ]