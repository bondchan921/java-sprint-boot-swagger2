# Swagger + Swagger UI + SpringBoot example

It's hard to find a least code for the combination, I copy the code from somewhere and cut the complex.
This is a simple example to demonstrate Swagger with Spring Boot.
For more information on SpringFox, pleas visit [http://springfox.io](http://springfox.io)

## Building

This project requires Java 7 or greater.

To build:

```
mvn clean package
```

This produces an exectuable jar in the `target` folder.

To run:

```
java -jar target/java-sprint-boot-swagger2-1.0.0-SNAPSHOT.jar
```

To access Swagger UI:

```
http://localhost:8080/v2/swagger-ui.html
```