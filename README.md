# whitehawk-proto

API defined via:

- [Protocol Buffers](https://developers.google.com/protocol-buffers)
- [gRPC](https://grpc.io/)

## Trigger Release

```bash
pnpm run release
git push --tags
```

This will cause the [build.yml](./.github/workflows/build.yml) to be executed.

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

### Git

- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/#summary)

### Buf

- [Buf](https://docs.buf.build/introduction)
