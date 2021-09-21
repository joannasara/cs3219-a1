# Docker Nginx Reverse Proxy

Build image tagged as `myproxy` from the Dockerfile:
```
docker build -t myproxy .
```
</br>

Create and start container using:   
```
docker-compose up -d
```
or alternatively, you can scale the app using more containers:   
```
docker-compose  up -d --scale myapp=<number-of-containers>
```
</br>   

Check the result at `http://localhost:80`
