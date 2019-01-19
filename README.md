Maven
- mvn -N io.takari:maven:wrapper

This command creates mvnw and mvnw.cmd files for linux and windows operating systems.
These mvnw files can be used as maven wrappers, so that the project can use maven even without installing maven on the box, and we can also specify what version of maven we would want to use.

mvnw can exactly be used as mvn 

Example :

- ./mvnw clean install
- ./mvnw spring-boot:run