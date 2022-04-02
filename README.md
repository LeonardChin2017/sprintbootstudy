# sprint-boot-study
My study material for spring boot framework.
https://www.youtube.com/watch?v=9SGDpanrc8U&t=1472s

## Overview
Spring boot is an amazing framework for building application using Java / Kotlin. 

Spring boot provides following features:
- microservices
- connecting to DB
- security
- production ready
- configuration
- logging
- metrics (measure how ur application behave in production)
- and more

## Project Overview
Spring boot initializr: https://start.spring.io/

!! Choose based on your own Java version, my Jave version is 11.
![image](https://user-images.githubusercontent.com/25117204/161364777-7498231a-7e97-423c-888d-3b0d44698465.png)

My configuration:
https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.6.6&packaging=jar&jvmVersion=11&groupId=com.example&artifactId=demo&name=demo&description=Demo%20project%20for%20Spring%20Boot&packageName=com.example.demo&dependencies=web,data-jpa,postgresql

Download the demo file and open it using your favourite IDE.
![image](https://user-images.githubusercontent.com/25117204/161364935-bbab51be-122a-43a7-bed2-40ff5b1ac25e.png)

If you run the project, it will fail to connect to the DB.
![image](https://user-images.githubusercontent.com/25117204/161365067-c4b3c962-c351-4875-9696-9be46e5272b2.png)

Comment and reload (maven -> reload project) this in poml
![image](https://user-images.githubusercontent.com/25117204/161365073-d686c583-3bb9-4ab3-be97-4f4da7b10c04.png)

##Write Simple RESTful API

![image](https://user-images.githubusercontent.com/25117204/161365193-f46e2297-8592-4d80-90f9-ef20734d9c05.png)
![image](https://user-images.githubusercontent.com/25117204/161365199-6549d88e-bc7a-43cd-886d-5629082cf667.png)

![image](https://user-images.githubusercontent.com/25117204/161365256-c90fd126-615f-4f47-978b-716010c15c4d.png)
![image](https://user-images.githubusercontent.com/25117204/161365263-f9b79326-5e87-46ad-aa9e-6f24bbf7f75a.png)

Simple RESTful API from custom student class
![image](https://user-images.githubusercontent.com/25117204/161365540-bfbbcc0a-e71b-4196-b5f5-76887d12a6e5.png)

In IntelliJ, you can use Alt + Insert to create constructor, getting, and setter. 
![image](https://user-images.githubusercontent.com/25117204/161365566-8cc8a1fc-0345-4280-bcc0-a904573cca73.png)

![image](https://user-images.githubusercontent.com/25117204/161365676-aae6c4b6-fb13-45f0-a685-705a40273494.png)
![image](https://user-images.githubusercontent.com/25117204/161365685-32ca3879-e040-4ed4-8ac4-d3762591030c.png)

Move all the code to service layer.
"service" annotation is required.
![image](https://user-images.githubusercontent.com/25117204/161366573-fe5938a3-d542-4fcb-84e5-385ffedc65cf.png)


