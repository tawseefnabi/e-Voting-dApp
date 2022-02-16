# e-Voting-dApp
a simple application, in which we will be holding an election between the candidates. Users will be able to vote for their chosen candidate. So, to vote easily and efficiently using the browser, we also need a client-side application to interact with the blockchain

## Prerequisites

- [Truffle-suite](https://trufflesuite.com/)
- [Datahub](https://datahub-beta.figment.io/signup)
- [Avalanche's architecture.](https://docs.avax.network/learn/platform-overview/)

## Requirements
- NodeJS v8.9.4 or later.
- Truffle, which you can install with npm install -g truffle
- Metamask extension added to the browser, which you can add from here
- Express.js, dotenv and @truffle/hdwallet-provider (instructions to install these are below)
- You will also need to have performed a cross-chain swap via the [Transfer AVAX Between X-Chain and C-Chain](https://docs.avax.network/build/tutorials/platform/transfer-avax-between-x-chain-and-c-chain/) tutorial to get funds to your C-Chain address on the Fuji testnet.

## Project-setup

```sh
npm init
```

install dependencies

```sh
npm install express dotenv @truffle/hdwallet-provider --save

```
Then create a boilerplate truffle project:
```sh
truffle init
```

This will setup our initial project structure. Smart contracts will be stored in the `contracts` folder, deployment functions for migrating smart contracts to the network will be stored in the `migrations` folder. And `build/contracts` folder would contain information about the deployed contract, ABI etc.
