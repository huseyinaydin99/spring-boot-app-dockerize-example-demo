### spring-boot-dockerize
Spring Boot Uygulaması Nasıl Dockerize Edilir?

### Docker İmajını İnşa Et
$ docker build -t spring-boot-docker.jar .

### Docker Imajını Kontrol Et
$ docker image ls

### Docker Imajını Çalıştır
$ docker run -p 9090:8080 spring-boot-docker.jar

Run komutunda 9090:9090 iç:dış port numaraları belirttik.
