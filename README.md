# configuration-service #
##configuration-service for osi-tech portal##

Please add below configurations in your domain service's bootstrap.yml

```yml
spring
  cloud:
     config:
       #uri: http://localhost:8888
       discovery:
         enabled: true
         service-id: configuration-service
       username: root
       password: s3cr3t```
       
       
*** Run application in your local ***

check-out from git

`git clone https://github.com/ositechportal/configuration-service.git`

go inside configuration-service folder and run below commands:

	Markup :  `gradlew bootRun` for windows
	Markup :  `./gradlew bootRun` for Mac
