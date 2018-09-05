# Spring Boot Flyway Example with custom configurations


## Requirements

1. Java - 1.8.x

2. Maven - 3.x.x

3. MySQL - 5.x.x

## Steps to setup

**1. Clone the application**

```bash
git clone https://github.com/aaffio/spring-data-fundamentals.git
```

**2. Create Mysql database**
```bash
create database greeting
```

**3. Change mysql username and password as per your installation**

+ open `src/main/resources/config/application.properties`
+ open `src/main/resources/config/application-mysql.properties`

+ change `spring.datasource.username` and `spring.datasource.password` as per your mysql installation

**4. Build and run the app using maven**

```bash
cd spring-data-fundameltals
mvn clean package
java -jar target/*.jar
```

You can also run the app without packaging it using -

```bash
mvn spring-boot:run
```