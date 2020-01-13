# Docker

### Docker hub account (https://hub.docker.com/)
username: wperng   
password: abc1234567   

### Bookmark
Name | URL
--- | ---
Basic Srping Boot Example | https://stackify.com/guide-docker-java/
Basic Srping Boot Example | https://spring.io/guides/gs/spring-boot-docker/

### 
1. Download docker desktop 
2. start it
3. run "docker pull adoptopenjdk/openjdk8" to get jdk8
   - "docker info"  can see what library do we have
4. run "docker build ." to create docker image   
   (example) run "docker build -t springio/gs-spring-boot-docker ."   
   - if any file you don't want it go to image, put it in ".dockerignore" file  
   - "docker image ls"
   - "docker container ls --all"
   - remove image "docker rmi xxx"   
5. run "docker run -p \<external port\>:\<internal port\> -t \<repository\>"    
   (example) run "docker run -p 9090:8080 -t springio/gs-spring-boot-docker" 
   
