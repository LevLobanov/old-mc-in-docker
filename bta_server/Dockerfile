FROM eclipse-temurin:8-jre-alpine

WORKDIR /app

COPY ./bta-server.jar /app/server.jar

RUN echo "eula=true" > eula.txt

EXPOSE 25565

CMD ["java", "-jar", "server.jar", "nogui"]