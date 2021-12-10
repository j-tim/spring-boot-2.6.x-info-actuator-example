# Spring Boot 2.6.x Actuator info endpoint

Example project Spring Boot 2.6 to play around with the actuator info contributor.
See blogpost: 

Build the project:

```
./mvnw clean package
```

Start the example:

```
./mvnw spring-boot:run
```

Check the [/info](http://localhost:8080/actuator/info) actuator endpoint:

```
curl http://localhost:8080/actuator/info | jq
```

From the Spring Boot 2.6 [release notes](https://github.com/spring-projects/spring-boot/wiki/Spring-Boot-2.6-Release-Notes#actuator-env-infocontributor-disabled-by-default)

> Actuator Env InfoContributor Disabled by Default
The env info contributor is now disabled by default. To enable it, set management.info.env.enabled to true.

## Spring Boot 2.5.x example

See branch: `spring-boot.2.5.x`