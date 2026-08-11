# Jenkins Tomcat App

A simple Java web application built with Maven and deployable as a WAR file to Apache Tomcat.

## Build

```bash
mvn clean package
```

## Deploy

1. Copy `target/jenkins-tomcat-app.war` to your Tomcat `webapps` folder.
2. Start Tomcat.
3. Open `http://localhost:8080/jenkins-tomcat-app/`.
4. Open `http://localhost:8080/jenkins-tomcat-app/hello`.
