# DESCRIPTION

This application contains
Non-blocking websocket server that broadcasts received messages to all connected clients
Web page on browser as client

## HOW 2RUN
1. `go get github.com/gorilla/websocket`
2. `go run *.go`
3. Open in browser `http://localhost:8080/`

## TODO
1. Implement JSON RPC2 and method send message to ownsefl from this link https://github.com/rabdavinci/ws-jsonrpc
2. Add tests
3. Dockerize

