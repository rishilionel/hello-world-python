# python-app-docker-demo

1) Install docker

2) Build the dockerfile by using Dockerfile
```
docker build -t pythonapp -f Dockerfile .
```

3) Run the docker image mapping any port . example: 8080
```
docker run -p 8080:8080 -itd pythonapp 
```

4) Test your application
```
$ curl http://localhost:8080
Hello World
```
