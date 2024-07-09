# Cross-Chain-Smart-Contract

This project demonstrates how to implement and configure Cross-Chain Smart Contracts that will transfer the IBC Packets.

## Project layout

In order to test out the Cross Chain protocol with smart contracts, we need two chains running. We will call them `local chain` and
`remote chain`. Each of these chains will host a contract that is designed specifically for it.

### Workflow

Follow these steps to run the end-to-end IBC smart contract example.

* 1. Start the local chain
* 2. Store and initialize
* 3. Start the remote chain
* 4. Store and initialize

### Using prepared contracts

Each local and remote directory contains smart contracts that are prepared and optimized before.
The binary is executable, so you can just copy and past the contract in your chain.
