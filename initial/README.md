# Spring Security

From this tutorial https://spring.io/guides/gs/securing-web/#initial

## Running the app
`./mvnw spring-boot:run`

or build the JAR file with `./mvnw clean package` and then run the JAR file, as follows:

`java -jar target/gs-securing-web-0.1.0.jar`

Access the app on http://localhost:8080

## Users
With spring security added to the pom, authentication is mandatory and you will need to log in.

If no users defined yet, then the default user is `user` and the password is regenerated on start up and can be seen in the logs e.g.
`Using generated security password: 99d686c9-36b8-4e92-90fd-9fbdafbf9e02`





