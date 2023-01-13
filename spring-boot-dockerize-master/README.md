# spring-boot-dockerize (Spring Boot Uygulamasını Docker'ize Etmek)
How to Dockerize Spring Boot Application 
Spring Boot Uygulaması Nasıl Dockerize Edilir?

# Build Docker Image / Docker İmajını İnşa Etme.!
$ docker build -t spring-boot-docker.jar .

# Check Docker Image / Docker Imajını Kontrol Etme / Listeleme.!
$ docker image ls

# Run Docker Image / Docker Imajını Çalıştırma
$ docker run -p 9090:8080 spring-boot-docker.jar

In the run command, we have specified that the port 8080 on the container should be mapped to the port 9090 on the Host OS.

Run komutunda 9090:9090 iç:dış port numaraları belirttik.!
