.PHONY: build-proto
build-proto:
	@protoc -I=./protoc/include:. --go_out=. --go-grpc_out=. *.proto
