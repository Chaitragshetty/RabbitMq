FROM openjdk:11-jdk-stretch
WORKDIR /i2ps
ADD /target/rabbitmq-listener-0.0.1-SNAPSHOT.jar /i2ps/rabbitmq-listener-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "rabbitmq-listener-0.0.1-SNAPSHOT.jar"]