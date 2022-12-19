# Docker grpc chat app

### To run the project follow the command below
```
$ docker build --tag=docker_grpc_chat .
$ docker run -it -p 8080:8080 docker_grpc_chat
```
### To chat through the command line follow the command below
```
$ cd client
$ go run main.go -N Ronaldo
$ go run main.go -N Neymer
```
