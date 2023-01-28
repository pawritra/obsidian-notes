# 1) Installing the Dependencies
We need to add Spring Boot Data JPA ( Mandatory )
We need to add another depenency and that will depend upon the database we are going to use ( MariaDB, MYSQL, PostgreSQL and so on )

```xml
	<dependency>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-starter-data-jpa</artifactId>
	</dependency>
	<dependency>
		<groupId>org.mariadb.jdbc</groupId>
		<artifactId>mariadb-java-client</artifactId>
		<scope>runtime</scope>
	</dependency>
```

# 2) Configuring Database connection
Once installing the dependencies is done we need to add database configuration so that spring and connect to the database.

```java
// application.properties

spring.datasource.url=
spring.datasource.username=
spring.datasource.password=
	
// I have added MariaDB driver as I was using that one. This will change depending upon the database you are using. 
spring.datasource.driver-class-name=org.mariadb.jdbc.Driver
```


# 3) Creating the Entity Models
Models are basic data classes with some specific annotations which provides Spring information to create tables on the database accordingly.