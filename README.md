# Ethereum Dapp for Tracking Items through Supply Chain

[![Truffle](https://img.shields.io/badge/truffle-v5.3.6-green.svg)](https://github.com/trufflesuite/truffle)
[![node](https://img.shields.io/badge/node-v12.18.3-green.svg)](https://nodejs.org/en/)

## Requirement 1: Project write-up - UML
UMD documents are available at UML folder

## Requirement 2: Project write-up - Libraries
- `truffle-assertions` - truffle helper lib to test contract events.
- `@truffle/hdwallet-provider` - HD Wallet-enabled Web3 provider.
  
## Rinkeby contract info
Address - `0x6742954B78559c25fA6813EBD0407f11E836F623`
Hash - `0x194749a4aca81350b62d6bb0c8165c4346f41da22f3dc59389b67af99b16379d`

## Getting Started
Install dependencies
```
yarn
```

Launch Ganache:
Please make sure you've already installed ganache-cli, Truffle and enabled MetaMask extension in your browser.

```
ganache-cli -m "spirit supply whale amount human item harsh scare congress discover talent hamster"
```

Your terminal should look something like this:

In a separate terminal window, Compile smart contracts:

```
truffle compile
```

Your terminal should look something like this:

This will create the smart contract artifacts in folder ```build\contracts```.

Migrate smart contracts to the locally running blockchain, ganache-cli:

```
truffle migrate
```

Test smart contracts:

```
truffle test
```

In a separate terminal window, launch the DApp:

```
npm run dev
```