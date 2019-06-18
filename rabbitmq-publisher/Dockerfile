FROM openjdk:11-jdk-stretch
WORKDIR /i2ps
ADD /target/rabbitmq-publisher-0.0.1-SNAPSHOT.jar /i2ps/rabbitmq-publisher-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "rabbitmq-publisher-0.0.1-SNAPSHOT.jar"]



