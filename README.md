Proto, составленный для **[url_shortner](https://github.com/notblinkyet/url_shortner)**  

Для генерации кода:
```bash
export GOPATH=$HOME/go
export PATH=$PATH:$GOPATH/bin
go install google.golang.org/protobuf/cmd/protoc-gen-go@latest
go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@latest
task generate
```

Для удаления сгенерированного кода:
```bash
task clear
```