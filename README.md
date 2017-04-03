## Upgrade Xampp version, with php 7.1 and composer 1.4

##1. Build from Dockerfile

```
docker build -t nghiatrx/docker-xampp .
```

##2. Running the image

```
docker run --name docker-xampp -p <your_sql_port>:22 -p <your_http_port>:80 -d -v <your_www_dir>:/www nghiatrx/docker-xampp
```

This project has been forked from tomsik68/docker-xampp, please read the instruction at https://github.com/tomsik68/docker-xampp/blob/master/README.md
