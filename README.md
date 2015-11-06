# boot-shutdown

Example showing Spring Boot shutdown issue.

Build:

    ./mvnw clean package

Run:

    java -jar target/demo-0.0.1-SNAPSHOT.jar --endpoints.shutdown.enabled=true

Stop:

    curl -X POST localhost:8080/shutdown {"message":"Bye"}