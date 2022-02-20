# paper-wallet

This repository contains a simple single page app for generating a paper wallet. The paper wallet can be used to store Bitcoin Cash (BCH) or SLP tokens. They can later be retrieved from the paper wallet with [wallet.FullStack.cash](https://wallet.fullstack.cash).

The latest version of this app is uploaded to Filecoin and accessible via [paperwallet.FullStack.cash](https://paperwallet.fullstack.cash).

This repository has a few files that do different jobs:

- [paper-wallet/index.html](./paper-wallet/index.html) is a web app that generates a paper wallet. This is the file that is uploaded to Filecoin.
- [publish.js](./publish.js) is a script for uploading the paper wallet app to the Filecoin blockchain.
- [redirect/index.html](./redirect/index.html) is the web page loaded at [paperwallet.fullstack.cash](https://paperwallet.fullstack.cash). It finds the latest IPFS hash on the BCH blockchain, the retrieves the content from the Filecoin blockchain.

## License

[MIT](LICENSE.md)
