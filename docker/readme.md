# Docker

### Docker hub account (https://hub.docker.com/)
username: wperng   
password: .....67 (all lower)   

### Bookmark
Name | URL
--- | ---
Basic Srping Boot Example | https://stackify.com/guide-docker-java/
Basic Srping Boot Example | https://spring.io/guides/gs/spring-boot-docker/
How to build a docker image | https://www.mirantis.com/blog/how-do-i-create-a-new-docker-image-for-my-application/
How to List / Start / Stop / Delete docker Containers | https://www.thegeekdiary.com/how-to-list-start-stop-delete-docker-containers/
How To Remove Docker Images, Containers, and Volumes | https://www.digitalocean.com/community/tutorials/how-to-remove-docker-images-containers-and-volumes

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
   
