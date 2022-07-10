FROM adoptopenjdk/openjdk11:alpine-jre
COPY build/libs/dockerApp-1.jar dockerApp-1.jar
WORKDIR /
ENTRYPOINT ["java", "-jar", "dockerApp-1.jar"]
EXPOSE 9000