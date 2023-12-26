# grpc-example

## Use proto to generate new files
protoc -I . --go-grpc_out=./ --go_out=./ hello.proto

## Run under the folder