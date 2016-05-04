# SpringBootDocker
A Spring Boot web application on top of Docker

@Author
Yoaz Menda

Usage:
(1) ./gradlew buildDocker

(2) docker run -i -t -p 8080:8080 IMAGE_YOU_JUST_CREATED

(3) DOCKER_VM_IP:8080 (usualy 192.168.99.100:8080)

You should see a 'hello docker world' message.
