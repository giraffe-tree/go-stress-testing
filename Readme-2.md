# README 2

## 参数

```
./main -c 10000 -n 40 -u ws://localhost:8010/websocket/handshake/
```

## 编译

```
SET CGO_ENABLED=0
SET GOOS=linux
SET GOARCH=amd64
go build main.go
```

