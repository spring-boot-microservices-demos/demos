# SPRING-BOOT-MICROSERVICES-DEMOS
*A video blog series for creating Microservices from Scratch using SpringBoot Framework and use AWS for operations*
## Demo Layout
- **Demo 1**: Setup
  - multi-module spring-boot project within eclipse using STS (Spring Starter Project)
  - use Gradle as build tool
  - use Java 1.8
  - **domain** : restaurant
  - start the *RAW* SpringBoot Application
    - within Eclipse
    - command line
  - multi-module project structure
    - restaurant-service (root / shell project with no implementation)
      - app (springboot, config etc)
      - domain (rest-endpoints, service-layer, DAO Layer)
