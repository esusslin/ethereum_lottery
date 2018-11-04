# ethereum_lottery

A simple decentralized lottery application on the Ethereum network via Solidity and Web3 and built with a React frontend.

### Summary

This application enables a manager to host a lottery held on the Ethereum network. Peasants can all submit their own lottery contracts, which are sent to the ethereum network, and the manager can initiate the random selection of a winner. When one of the peasants wins, the lottery sum is distributed to their own account.

### Technical Drill-Down

This simple application utilizes the [Metamask](https://metamask.io/) chrome extention to enable multiple mock users to enter into the lottery by submitting at least .01 Ether into the pool. This application is centered around a Lottery contract written in Solidity and a simple React user interface.

### Installation Instructions

1. Download [Metamask](https://metamask.io/)

2. cd lottery-react & npm install

3. npm start

### Lottery Contract

#### Variables

- **_manager_** - address of the boss
- **_players_** - addresses of the pesants

#### Functions

- **_enter_** - submits a player into the lottery
- **_pickWinner_** - randomly picks the winner and distrubutes winnings

[Remix](https://remix.ethereum.org/) - great workbench for creating solidity contracts - deploys to local mock networks.

[Rinkeby-faucet](rinkeby-faucet.com) - socialist / communist source for free Ether (for testing only)

[Ether Converter](https://etherconverter.online/) - converts Wei / Finney / Ether / etc

[Mnemonic Code Converter](https://iancoleman.io/bip39/) - full status of all accounts linked to a single mnemonic code

[Infura.io](https://infura.io/) - Rinkeby provider API

[Rinkeby.Etherscan](https://rinkeby.etherscan.io/) - Rinkeby tool to examine contracts on Rinkeby network

### Suite Links

[Tool Stack Resources](https://hackernoon.com/ethereum-development-walkthrough-part-2-truffle-ganache-geth-and-mist-8d6320e12269)
