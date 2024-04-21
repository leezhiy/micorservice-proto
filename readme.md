# Microservice-proto

This repo contains Protobuf definitions for all the microservices organised in folders.

The pipeline will generate libraries in format `ca101-proto-{lang}`.

### Folder structure

```
microservice-proto:
|____proto // 服务API定义
| |____helloworld
| | |____server
| | | |____v1
| | | | |____demo.proto
|____annotations // 注解定义options
|____third_party // 第三方引用
```

## License

Kratos is MIT licensed. See the [LICENSE](./LICENSE) file for details.
