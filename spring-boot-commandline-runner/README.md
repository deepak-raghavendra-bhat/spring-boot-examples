# REST Service Demo with Spring Boot

This example demonstrates how you can implement REST service in Spring Boot.

### Technical Details
In this project, we are going to use below set of versions for demonstrations.

    Spring Boot - 2.7.4
    Spring - 5.3.23
    Lombok - 1.18.24

### Building

The example can be built with

    mvn clean install

### Running the example in your local

    spring-boot:run -Dspring-boot.run.arguments=--priceOne.pound=5
    
    Windows user -> mvn spring-boot:run -D"spring-boot.run.arguments=--priceOne.pound=5"

### Test it using Program Arguments in Run Configurations
-DpriceOne.pound=5
