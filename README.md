# [@brtmvdl/logger](https://www.npmjs.com/package/@brtmvdl/logger)

Easy Logger Node.js library

[![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/brtmvdl/logger/npm-publish.yml?label=NPM%20package&link=https%3A%2F%2Fgithub.com%2Fbrtmvdl%2Flogger%2Factions%2Fworkflows%2Fnpm-publish.yml)](https://github.com/brtmvdl/logger/actions/workflows/npm-publish.yml) [![github/license](https://img.shields.io/github/license/brtmvdl/logger)](https://img.shields.io/github/license/brtmvdl/logger) [![github/stars](https://img.shields.io/github/stars/brtmvdl/logger?style=social)](https://img.shields.io/github/stars/brtmvdl/logger?style=social)

## social & donate

[Donate](https://link.mercadopago.com.br/brtmvdl) - [Telegram](https://t.me/+KRmg5MlqgMk0MTg5) - [Discord](https://discord.gg/CPRyzsjj)

## how to install

```bash
# bash

npm i @brtmvdl/logger
```

## how to use

```js
// index.js

const { Logger } = require('@brtmvdl/logger')

const logger = new Logger('application')

logger.log('key', 'value1', 'value2', 'value3')
```

```sh
# bash

node index.js
```

## license

[MIT](./LICENSE)
