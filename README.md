# whitehawk-proto

API defined via:

- [Protocol Buffers](https://developers.google.com/protocol-buffers)
- [gRPC](https://grpc.io/)

## Building

### Generate source code

```bash
buf generate
```

### Build language-specific artifacts

```bash
.ci/all-ci build
```

### Publish language-specific artifacts

```bash
.ci/all-ci publish
```

## Learning Resources

- [Buf](https://docs.buf.build/introduction)
