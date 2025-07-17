# ⚙️ Configuration Guide

This guide explains how to configure the Spring PetClinic application for different environments.

## 🔧 Application Properties

Located in `src/main/resources/application.properties`:
```properties
server.port=8080
spring.datasource.url=jdbc:h2:mem:petclinic
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=
spring.jpa.hibernate.ddl-auto=none
