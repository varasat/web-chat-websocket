# web-chat-websocket
This is a Simple example of a chat system using websockets in Go

## How to setup
- Sync all the dependencies
- run `go build main.go`
- go to http://localhost:5000/ 
- start sending messages

## Dockerize
- build the docker container `docker build -t websocketschat .`
- run it `docker run -p 5000:5000 websocketschat`
