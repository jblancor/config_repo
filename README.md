# Configuration repository for Spring Boot's microservices

Execute all projects with: gradle bootRun.

Set config-server configuration. Edit application.yml or use env variables for github repository.


Test:
- http://localhost:8761/eureka/apps
- http://localhost:8080/greeting?name=Joe
- http://localhost:8090/middle/greeting?name=Joe
