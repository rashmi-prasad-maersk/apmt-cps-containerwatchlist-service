# apmt-cps-containerwatchlist-service

Prerequisites
Java SDK 17
Apache-maven-3.8.4
Spring boot version 3.0.1
Graalvm for AOT
Build application:
Build: mvn clean install Build without running integration test: mvn clean install -DskipIntegrationTests Build without running unit test: mvn clean install -DskipUnitTests

Starting application:
To start server locally for manual testing/debugging: mvn spring-boot:run
Running Integration tests:
mvn install failsafe:integration-test

Usage
Install dependencies: mvn clean install

Local profile: mvn spring-boot:run -Dspring-boot.run.jvmArguments=-Dspring.profiles.active=local

Dev profile: mvn spring-boot:run -Dspring-boot.run.jvmArguments=-Dspring.profiles.active=dev
