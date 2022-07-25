# MUD Wallet MUD 公链开源钱包
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

> MUD 公链开源钱包


## Building browser extension locally
This repo uses git-secret to encrypt the endpoints and the api keys. **So, you can't build this without creating your own config file.** You should create your own `config.var.ts`, `config.ui.var.ts` files inside the `packages/extension/src` folder. Refer to the `config.var.example.ts`, ``config.ui.var.example.ts`` sample files to create your own configuration.

This repo requires `protoc` to be installed. Check [Install protobuf](https://grpc.io/docs/protoc-installation/) for details.  

Clone this repo and run:
```sh
yarn bootstrap
yarn build
```

Browser extension's build output is placed in `packages/extension/prod`, and you can check out [this page](https://developer.chrome.com/extensions/getstarted) for installing the developing version.


## License
### Browser Extension 
Apache 2.0

