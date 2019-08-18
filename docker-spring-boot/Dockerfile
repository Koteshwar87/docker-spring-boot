FROM openjdk:8
ADD docker-spring-boot/target/docker-spring-boot.jar docker-spring-boot.jar
EXPOSE 8585
ENTRYPOINT ["java", "-jar", "docker-spring-boot.jar"]