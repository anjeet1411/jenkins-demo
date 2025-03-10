FROM eclipse-temurin:19
LABEL maintainer="anjeet@wipro.com"
WORKDIR /app
COPY target/springboot-mysql-docker.jar /app/springboot-docker-demo.jar
ENTRYPOINT ["java","-jar","springboot-docker-demo.jar"]