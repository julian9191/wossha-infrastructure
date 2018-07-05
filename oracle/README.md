# ORACLEE 12 in docker
[imagen de docker usada (sath89/oracle-12c)](https://hub.docker.com/r/sath89/oracle-12c/)


Bajar la imagen:
# docker pull sath89/oracle-12c
```

crear contenedor
# docker run -d -p 8080:8080 -p 1521:1521 sath89/oracle-12c
```


hostname: localhost
port: 1521
sid: xe
service name: xe
username: system
password: oracle