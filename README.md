```golang
go get -u github.com/timoxren/protoc-gen-openapi
```
Example:
```bigquery
protoc --proto_path=.  --proto_path=./third_party --openapi_out=paths=source_relative:. test.proto
```