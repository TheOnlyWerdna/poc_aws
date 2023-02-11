FROM maven:3.8-openjdk-18-slim
WORKDIR /usr/src/spti-springboot
COPY . .
RUN mvn clean install -DskipTests
CMD mvn spring-boot:run