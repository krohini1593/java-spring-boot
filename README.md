# Spring boot web application

Starter template for RESTful web app with Spring Boot and Gradle


## Dependencies
* Java 17
* Gradle 8.4

On macOS 14.2.1

## Build and run
The below command builds and runs the application starting a server reachable at `localhost:8080`.
From project root, run:
```shell
gradle bootRun
```

## Create executable jar
From project root, run:
```shell
gradle bootJar
```

This creates a jar in the directory `/build/libs`
Execute the jar using `java -jar`
```shell
java -jar <path/to/jar>
```

