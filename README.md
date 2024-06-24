# docker-registry-mirror

This is a simple Docker registry mirror. Due to the fact that Docker Registry mirror service provided by Chinese cloud service providers is only open to intranet, a proxy service is needed for access. This service is a simple proxy service that forwards requests to the specified Docker Registry.

### Usage
```
Docker Registry Proxy 
  -address string
        Serve Address (default "localhost:8989")
  -help
        Show help
  -registry string
        Docker Registry Host (default "registry-1.docker.io")
```

### Example
```bash
./docker-registry-mirror -registry mirror.ccs.tencentyun.com
```

### License

**docker-registry-mirror** is released under the MIT license. See [LICENSE](LICENSE) for details.