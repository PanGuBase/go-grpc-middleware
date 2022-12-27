```
# option 可以对其进行拦截
https://colobu.com/2015/01/07/Protobuf-language-guide/

protoc --go_out=. --go_opt=paths=source_relative \
    --go-grpc_out=. --go-grpc_opt=paths=source_relative \
    proto/hello.proto
    
https://phenix3443.github.io/notebook/protobuf/proto2-language-guide.html
```