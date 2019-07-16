# spring-cloud-consul

spring-cloud-consul-example is an example for microservices system.

It's contain 
**configuration management, service discovery, circuit breakers, intelligent routing, distributed tracing, application monitor**.

## Getting Started
```shell
./gradlew clean build -x test
./buildDockerImage.sh
docker-compose up -d
```
if you want to start more serve, you should use 
```shell
docker-compose scale service-a=2 service-b=3  
```

## Technology List
* Spring Cloud Consul
* Spring Cloud Sleuth
* Spring Cloud Config
* Spring Boot Admin
* Spring Boot
* ZipKin
* Docker
* Swagger

## Architecture Overview
[](url "title")
<img src="https://raw.githubusercontent.com/yidongnan/spring-cloud-consul-example/master/screenshots/Architecture.png">

## Screenshots
### Api Route(Zuul)
[](url "title")
<img src="https://raw.githubusercontent.com/yidongnan/spring-cloud-consul-example/master/screenshots/Selection_001.png">

### Consul DashBoard
[](url "title")
<img src="https://raw.githubusercontent.com/yidongnan/spring-cloud-consul-example/master/screenshots/Selection_002.png">

### Consul Key/Value DashBoard
[](url "title")
<img src="https://raw.githubusercontent.com/yidongnan/spring-cloud-consul-example/master/screenshots/Selection_003.png">

### ZipKin DashBoard
[](url "title")
<img src="https://raw.githubusercontent.com/yidongnan/spring-cloud-consul-example/master/screenshots/Selection_004.png">

### ZipKin Trace Detail
[](url "title")
<img src="https://raw.githubusercontent.com/yidongnan/spring-cloud-consul-example/master/screenshots/Selection_005.png">

### ZipKin Dependencies Overview
[](url "title")
<img src="https://raw.githubusercontent.com/yidongnan/spring-cloud-consul-example/master/screenshots/Selection_006.png">

### Spring Boot Admin DashBoard
[](url "title")
<img src="https://raw.githubusercontent.com/yidongnan/spring-cloud-consul-example/master/screenshots/Selection_007.png">

### Spring Boot Admin Detail
[](url "title")
<img src="https://raw.githubusercontent.com/yidongnan/spring-cloud-consul-example/master/screenshots/Selection_008.png">

### Spring Boot Admin Environment
[](url "title")
<img src="https://raw.githubusercontent.com/yidongnan/spring-cloud-consul-example/master/screenshots/Selection_009.png">

### Spring Boot Admin Thread Dump
[](url "title")
<img src="https://raw.githubusercontent.com/yidongnan/spring-cloud-consul-example/master/screenshots/Selection_010.png">

### Spring Boot Admin Trace
[](url "title")
<img src="https://raw.githubusercontent.com/yidongnan/spring-cloud-consul-example/master/screenshots/Selection_011.png">

### Hystrix Dashboard
[](url "title")
<img src="https://raw.githubusercontent.com/yidongnan/spring-cloud-consul-example/master/screenshots/Selection_012.png">

### Hystrix Dashboard Detail
[](url "title")
<img src="https://raw.githubusercontent.com/yidongnan/spring-cloud-consul-example/master/screenshots/Selection_013.png">
