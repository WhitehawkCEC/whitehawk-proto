# whitehawk-proto

API defined via:

- [Protocol Buffers](https://developers.google.com/protocol-buffers)
- [gRPC](https://grpc.io/)

## Trigger Release

```bash
yarn run release
git push --tags
```

## Building (manual)

### Generate source code

```bash
buf generate
```

### Build language-specific artifacts

```bash
.ci/all-ci build $(git describe)
```

### Publish language-specific artifacts

```bash
.ci/all-ci publish
```

## Learning Resources

- [Buf](https://docs.buf.build/introduction)
