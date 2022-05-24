[Avalanche](https://www.avax.network/) is an open-source, proof-of-stake blockchain with smart contract functionality that uses the Snow family of consensus protocols. Avalanche features [3 built-in blockchains](https://docs.avax.network/overview/getting-started/avalanche-platform) that are validated and secured by the Primary Network:
* [Exchange Chain (X-Chain)](https://docs.avax.network/overview/getting-started/avalanche-platform/#exchange-chain-x-chain) - Acts as a decentralized platform for creating and trading digital smart assets like AVAX. These assets are a representation of a real-world resource with a set of rules that govern its behavior. The X-Chain is an instance of the Avalanche Virtual Machine (AVM). 
* [Platform Chain (P-Chain)](https://docs.avax.network/overview/getting-started/avalanche-platform/#platform-chain-p-chain) - Metadata blockchain on Avalanche that coordinates validators, keeps track of active subnets, and enables the creation of new subnets. The P-Chain implements the [Snowman consensus protocol](https://docs.avax.network/#snowman-consensus-protocol).
* [Contract Chain (C-Chain)](https://docs.avax.network/overview/getting-started/avalanche-platform/#contract-chain-c-chain) - Allows for the creation smart contracts using the [C-Chain’s API](https://docs.avax.network/apis/avalanchego/apis/c-chain).

Avalanche is one of a number of new Layer 1 blockchains that are competing to draw Ethereum developers. To make a simpler onboarding experience for Ethereum developers, Avalanche's smart contracts can be written in Solidity. Avalanche's consensus mechanism aims to enable developing applications that are faster, cheaper, and more energy efficient than competing chains.

## Setup

Rename `.env.sample` to `.env` and include your environment variables.

```bash
mv .env.sample .env
```

Install dependencies.

```bash
yarn
```

Start development server.

```bash
yarn dev
```