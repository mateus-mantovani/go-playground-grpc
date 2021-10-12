This is just a GO playground. Inside this project there is a stream request, take a look.

To compile the *.proto files use the following command:
protoc --proto_path=proto proto/*.proto --go_out=pb --go-grpc_out=pb

To run the server:
go run cmd/server/server.go

To run the client:
go run cmd/client/client.g
