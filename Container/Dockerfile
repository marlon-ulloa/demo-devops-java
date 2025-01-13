FROM amazoncorretto:17-alpine-jdk

WORKDIR /app

COPY target/demo*.jar demo.jar

EXPOSE 8000

ENTRYPOINT ["java", "-jar", "demo.jar"]
