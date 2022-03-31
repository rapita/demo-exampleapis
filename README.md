# Demo Example APIs

This repository contains the interface definitions for generating servers and clients in different languages.

Inspired by [googleapis](https://github.com/googleapis/googleapis).

### Protobuf highlight

Install packages for highlight:
```shell
go install \
    github.com/grpc-ecosystem/grpc-gateway/v2/protoc-gen-grpc-gateway \
    github.com/grpc-ecosystem/grpc-gateway/v2/protoc-gen-openapiv2 \
    google.golang.org/protobuf/cmd/protoc-gen-go \
    google.golang.org/grpc/cmd/protoc-gen-go-grpc
```

Setup IDE (GoLand):

1. Go to File -> Settings -> Languages & Frameworks -> Protocol Buffers
2. Disable `Configure Automaticaly`
3. Setup:

| Location | Prefix   |
|--------|--------- |
| `auto generated value` | |
| `${HOME}/go/pkg/mod/github.com/grpc-ecosystem/grpc-gateway/v2@v2.7.3/protoc-gen-openapiv2/options` | `protoc-gen-openapiv2/options` |
| `${HOME}/go/pkg/mod/github.com/grpc-ecosystem/grpc-gateway@v1.16.0/third_party/googleapis/google/api` | `google/api` |

`${HOME}` - is your real path