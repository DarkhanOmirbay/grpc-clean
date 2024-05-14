# GOLANG GRPC MICROSERVICE PRACTICE
# 1.create proto file
# 2.compile proto file
    2.1 download protoc compiler and add in path(env var):https://github.com/protocolbuffers/protobuf/releases
    2.2 protocol buf plugin:go install google.golang.org/protobuf/cmd/protoc-gen-go@v1.27
    2.3 grpc plugin:go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@v1.1
    2.4 command for generating : protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative proto/*.proto
# 3.create user model
use gorm(Golang ORM):go get -u gorm.io/gorm
# 4.create intefaces.go (methods) ...
# 5.create gorm.go ...
