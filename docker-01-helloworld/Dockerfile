FROM openjdk:8-jre-alpine

RUN mkdir -p /opt/my-java-app

COPY HelloWorld.class /opt/my-java-app

WORKDIR /opt/my-java-app

RUN pwd;ls -al

CMD ["java", "-cp", ".", "HelloWorld"]
