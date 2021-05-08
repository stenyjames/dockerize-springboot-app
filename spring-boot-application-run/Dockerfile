FROM openjdk:11-jdk

#RUN mkdir /usr/src

COPY ./target/spring-boot-application-run-0.0.1-SNAPSHOT.jar /usr/src

WORKDIR /usr/src

ENTRYPOINT ["java","-jar", "spring-boot-application-run-0.0.1-SNAPSHOT.jar"]

