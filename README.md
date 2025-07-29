# Mirlo API Client

A simple wrapper around our API and fetch stuff.

```
npm install @mirlo/mirlo-api-client
```

And then:

```typescript
import APIInstance from "@mirlo/mirlo-api-client";

const api = APIInstance("http://localhost:3000", "");

export default api;
```

## To update.

1. Bump the version number in package.json
2. `npm publish`
