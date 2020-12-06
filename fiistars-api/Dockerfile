FROM java:8-jre
MAINTAINER ITBro Team <itbro.team@gmail.com>

ADD ./target/fiistars-api-1.0-SNAPSHOT.jar /api/
CMD ["java", "-Xmx1024m", "-jar", "/api/fiistars-api-1.0-SNAPSHOT.jar"]

EXPOSE 8081