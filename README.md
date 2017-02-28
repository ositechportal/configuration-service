# configuration-service
configuration-service for osi-tech portal

Please add below configurations in your domain service's bootstrap.yml
spring
  cloud:
     config:
       #uri: http://localhost:8081
       discovery:
         enabled: true
         service-id: configuration-service
       username: root
       password: s3cr3t
