# ts-grpc

## install
```
# mkdir proto scripts src
# touch proto/songs.proto scripts/build-protos.sh
# yarn init 
# yarn add grpc grpc-tools grpc_tools_node_protoc_ts
```
注意⚠️
- 安装grpc-tools会报错，下载https://node-precompiled-binaries.grpc.io/grpc-tools/v1.8.1/darwin-x64.tar.gz,解压拷贝bin文件夹所有文件到项目的node_modules/grpc-tools/bin/下


## make code 
```
# bash ./scripts/build-protos.sh ./proto/songs.proto ./src/proto
```