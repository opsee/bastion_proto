# bastion_proto

In order to use this in another project, first add the submodule as a dependency:

`git submodule add git@github.com:opsee/bastion_proto.git`

## Mac instructions

In order to compile and use protobuf/grpc on a Mac, you first need homebrew. Assuming that:

```
brew tap homebrew/dupes
brew tap grpc/grpc
brew install grpc/grpc/grpc
```

## Install go-grpc, proto3, and protoc
go get -u github.com/golang/protobuf/{proto,protoc-gen-go}
go get google.golang.org/grpc
