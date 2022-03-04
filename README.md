## Wallet API

You can import the `Wallet` class like this

Node.js / ES5:

```js
const { Wallet } = require('ethereumjs-wallet').default
```

ESM / TypeScript:

```js
import Wallet from 'ethereumjs-wallet'
```

## Thirdparty API

Importing various third party wallets is possible through the `thirdparty` submodule:

Node.js / ES5:

```js
const { thirdparty } = require('ethereumjs-wallet')
```

ESM / TypeScript:

```js
import { thirdparty } from 'ethereumjs-wallet'
```

Please go to [./docs/README.md](./docs/README.md) for more info.

## HD Wallet API

To use BIP32 HD wallets, first include the `hdkey` submodule:

Node.js / ES5:

```js
const { hdkey } = require('ethereumjs-wallet')
```

ESM / TypeScript:

```js
import { hdkey } from 'ethereumjs-wallet'
```

