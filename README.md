# proto
```bash
$ protoc -I proto proto/sso/sso.proto --go_out=./gen/go/ --go_opt=paths=source_relative --go-grpc_out=./gen/go/ --go-grpc_opt=paths=source_relative
```

Для того чтобы подтягивать конкретные версии protobuf-a НиД: `$ git tag v.0.0.1`
