# Course: Blockchain basics

- Course repository: 
https://github.com/Cyfrin/foundry-full-course-f23.git

- Terms: 
    - SCs: Smart Contracts
    - L2s: Layer Twos    

## What is a blockchain?
A blockchain is network infrastructure powered by cryptography and decentralization.

## The purpose of smart contracts
A smart contract is a decentralized agreement composed by a set of instructions executed in a decentralized and autonomous way without the need for a centralized or third party intermediary. They can be thought as traditional agreements, except that smart contracts are written in code and emboddied in decentralized platforms depending on the purpose. Smart contracts allow removing centralized forces and counterparty risk.

### Oracles
Smart contracts have the **oracle issue**:
- The oracle issue consists in the Blockchains impossibility to interact with data from the real world since these blockchains are deterministic systems and they are deterministic on purpose. 
- So these blockchains need to get data from the real world, and **Oracles** are in charge of this task. Oracles are any device that delivers data to these decentralized blockchains or runs external computation.
- To make a blockchain **really decentralized**, *it can't work with a single Oracle* or resource that runs these external computations. It has to work with a **decentralized oracle network**.
- By *combining this on-chain decentralized logic and this off-chain (Oracles) decentralized* data/computation the **Hybrid smart contracts** rise, with which some projects interact at some way (either by being Hybrid by its native structure or by interactions). 
- An example of hybrid smart contracts protocol is Chainlink (LINK) since it is a modular decentralized oracle network that can both bring external data and external computation into smart contracts to make sure they're decentralized end-to-end while providing the feature richness that smart contracts need. **Smart contracts and Hybrid Smart contracts terminology will be used interchangeably **

### Chainlink
Chainlink is blockchain agnostic, so it will have part of the focus on this notes. It works on almost any blockchain such as Polygon, Avalanche, Ethereum, Solana, etc.

### Layers 2 (L2s)
L2s are intented to solving the scalability issue that some blockchains has to pass by to become bigger.
- There are two types of L2s at the moment: 
    - Optimistic rollups: Optimism and Arbitrum
    - Zero knowledge rollups: ZK sync or Polygon ZK EVM

### Decentralized Applications (DApps)
A DApp is a combination of many SCs 

### Web3
Web3 is the idea that blockchains and smart contracts are the next iteration of the web:
- It is said the web3 is the permissionless web, with dynamic content. Where decentralized censorship, resistant networks run agreements and code. It generally is accompanies by the idea of the user owned ecosystems, where the protocols users that interact with them also own a portion of, instead of solely being the product/consumers. 

### Purpose of smart contracts 
Smart contracts create **Trust minimized agreements**, which give rise to *unbreakable promises (and agreements)* 

<!-- ## Current smart contract landscape

## Setting up the first wallet

## Introduction to gas

## How do blockchains work

## Signing transactions

## Gas in depth

## Blockchain overview -->



