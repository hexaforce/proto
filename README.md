
```bash 
python -m grpc_tools.protoc -I./protos \
 --python_out=python \
 --pyi_out=python \
 --grpc_python_out=python \
 ./protos/addressbook.proto
```

```bash
protoc \
 --go_out=. \
 --go-grpc_out=. \
 ./protos/addressbook.proto
```

```bash
protoc \
 --java_out=java \
 ./protos/addressbook.proto
 ```
