# registry

to create registry, we have add below dependency
- spring-cloud-starter-netflix-eureka-server
    
    we have to give below properties in yml
    
    eureka:
   client:
      register-with-eureka: false
      fetch-registry: false
   instance:
      hostname:localhost
      
Have to give below annotation to maker it as a registry

@EnableEurekaServer
