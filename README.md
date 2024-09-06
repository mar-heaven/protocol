# protocol

```azure
protoc --version
# libprotoc 26.0 (这个其实就是5.26.0)
```
```shell
go get -u google.golang.org/grpc
go get -u github.com/golang/protobuf/{proto,protoc-gen-go}

go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@v1.5.1
go install google.golang.org/protobuf/cmd/protoc-gen-go@v1.34.2


# protoc
# https://github.com/protocolbuffers/protobuf/releases?page=2
wget https://github.com/protocolbuffers/protobuf/releases/download/v26.0/protoc-26.0-linux-x86_64.zip
```