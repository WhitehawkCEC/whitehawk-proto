# API Kilo

## Authentication

Use metadata key `api-key`.

### Authentication Example (Typescript)

```ts
import { Service } from '@buf/whitehawkcec_whitehawk-api-kilo.connectrpc_es/whitehawk/api/kilo/resources/accounts/v1/service_connect'
import { createPromiseClient } from '@connectrpc/connect'
import { createGrpcTransport } from '@connectrpc/connect-node'

const METADATA_KEY = 'api-key'
const apiKeyValue = 'whk_...'

const transport = createGrpcTransport({
  baseUrl: 'https://api-kilo.whitehawk.com',
  httpVersion: '2',
  interceptors: [
    (next) => async (request) => {
      request.header.set(METADATA_KEY, apiKeyValue)

      return next(request)
    },
  ],
})

const client = createPromiseClient(Service, transport)

client.list({})
```

## Design

This API follows a resource-oriented design.

Collection resources use these standard operations:

- Create
- Read
- Update
- Delete
- List

Singleton resources use these standard operations:

- Get
- Set

This is similar to the [Google recommendation](https://cloud.google.com/apis/design/resources).
