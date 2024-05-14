# WebSocket echo server/client

After connection to WS port, server give 5 time chance to client write data in console. If data not writing - server close to connection

- `cmd go run websocket.go`
- `cmd cd client`
- `cmd go run client.go localhost:1234 ws`
