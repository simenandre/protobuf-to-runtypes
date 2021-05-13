# Generate Runtypes from Protobuf

[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![NPM version](https://img.shields.io/npm/v/protobuf-to-runtypes.svg)](https://www.npmjs.com/package/protobuf-to-runtypes)
[![codecov](https://codecov.io/gh/cobraz/protobuf-to-runtypes/branch/main/graph/badge.svg)](https://codecov.io/gh/cobraz/protobuf-to-runtypes)

</div>

This CLI and library aim to provide an easy way to convert Protobuf to Runtypes.

We are thankful for all help with adding new functionality, fixing issues, or
improve the package. Feel free to open issues and pull requests ❤️

## Quickstart

```shell
▶ npx protobuf-to-runtypes -i protobuf.proto -o protobuf.ts
```

or

```shell
▶ cat https://some-url.com/my-api.proto | npx protobuf-to-runtypes -o protobuf.ts
```

## Documentation

Apart from this README, you can find details and examples of using the SDK in
the following places:

- [API Documentation][docs]

## Example

```typescript
import { parseToGenerator } from 'protobuf-to-runtypes';
import { generateRuntypes } from 'generate-runtypes';

const protobuf = await readFile('my-protobuf.proto');
const toGenerator = await parseToGenerator(protobuf);
const sourceCode = await generateRuntypes(toGenerator);
```

[runtypes]: https://github.com/pelotom/runtypes
[docs]: ./docs
