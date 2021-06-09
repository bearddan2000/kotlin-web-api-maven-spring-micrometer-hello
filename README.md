# kotlin-web-api-maven-spring-micrometer-hello

## Description
Another way to serve web content.
Uses micrometer to expose endpoints
through springframework actuator.

## Tech stack
- kotlin
- maven

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- Available http://localhost/actuator

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://github.com/monodot/spring-boot-with-metrics/blob/main/pom.xml
