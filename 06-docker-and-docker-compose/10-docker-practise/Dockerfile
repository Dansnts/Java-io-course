# Base image
FROM eclipse-temurin:21-jre

WORKDIR /app

COPY ./java-ios-1.0-SNAPSHOT.jar app.jar
COPY ./test.txt test.txt

ENTRYPOINT [ "java","-jar","app.jar" ]

CMD [ "-h" ]


