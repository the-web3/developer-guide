# Project-x developer guide

This guide is used to guide developers who are new to saourlabs, so that developers can participate in the development of corresponding projects according to their own interests. It mainly includes project introduction and how to participate in project development.


## 1. saourlabs Project introduce
### 1.1 Projects under development
- [wallet-chain-node](https://github.com/savour-labs/wallet-chain-node): A node RPC service that connects to each public chain, and a unified set of wallet interface services, currently supported More than 40 mainstream chains including BTC, ETH, ADA, Arbi, OP, Scroll, Zksync, Tron, Tezos, Oasis, Cosmos, etc.
- [key-locker](https://github.com/savour-labs/key-locker): An on-chain key management tool that can be used for decentralized key management of social recovery wallets and MPC wallets.
- [skyeye](https://github.com/savour-labs/skyeye): Digital currency market aggregator, currently supports all mainstream centralized exchanges, and decentralized exchanges are also being supported.
- [fieryeyes](https://github.com/savour-labs/fieryeyes): NFT aggregator project, development has been temporarily suspended
- [hailstone](https://github.com/savour-labs/hailstone): Business mid-end project, docking various back-end rpc services, such as [wallet-chain-node](https://github.com/savour -labs/wallet-chain-node), [skyeye](https://github.com/savour-labs/skyeye) and other projects
- [protect-x-contracts](https://github.com/savour-labs/protect-x-contracts): Economic model of layer3 privacy social protocol chain, reverse re-pledge protocol contract
- [wallet-sdk](https://github.com/savour-labs/wallet-sdk): HD wallet SDK, mnemonic phrase generation, offline mnemonic phrase export private key generation address, transaction offline signature, currently supports BTC, There are more than 40 mainstream chains such as ETH, ADA, Arbi, OP, Scroll, Zksync, Tron, Tezos, Oasis, and Cosmos.
- [shadow-x-app](https://github.com/savour-labs/parapack): A private social wallet developed by RN. It has been connected to 7 mainstream chains and integrated with DAPP browser, flash exchange and market prices. and other functions.
- [bitcoin-sdk-lite](https://github.com/savour-labs/bitcoin-sdk-lite): Lightweight BTC wallet SDK
- [savour-treasure](https://github.com/savour-labs/savour-treasure): save community task management plus treasury contract
- [savour-proto](https://github.com/savour-labs/savour-proto): protobuf interface definition for all projects
- [savour-secret](https://github.com/savour-labs/savour-secret): Threshold shared secret algorithm library implemented by nodeJS
- [universe-uni](https://github.com/savour-labs/universe-uni): A privacy social wallet developed by uni-app. Development has been suspended for now.
- [savour-prototype](https://github.com/savour-labs/savour-prototype): Product prototype design draft
- [savnode](https://github.com/savour-labs/savnode): layer3 Mpc node, development is currently suspended and will be restarted after the development of layer3 privacy social protocol
- [distribute](https://github.com/savour-labs/distribute): Distribution platform for IOS app release (the one with enterprise signature mode, which cannot be put on the app store. This distribution can be used after enterprise signature or super signature is completed) platform).
- [savour-offical](https://github.com/savour-labs/savour-offical): savourlabs official website, currently suspended.
- [shadow-x](https://github.com/savour-labs/shadow-x): layer3 privacy social protocol project, which will be renamed protect-x in the future.
- [protect-x-sdk](https://github.com/savour-labs/protect-x-sdk): The developed layer3 privacy social protocol sdk will be launched soon for third-party access.

### 1.2. Projects planned to be developed
- [protect-x-services](https://github.com/savour-labs/protect-x-services) layer3 pledge contract off-chain service project. In order to attract more developers to join, this project is developed using rust
- [ethereum-event-watcher](https://github.com/savour-labs/ethereum-event-watcher) The contract event indexing infrastructure of the EVM chain is provided for use by protect-x-services in order to attract more developers If you want to join, this project is developed using rust

## 2. develop guide

There will be a corresponding issure under each project. If the issure is marked as a task, it is a task that needs to be developed. There will also be a development bounty under the corresponding task. After the task development is completed, a PR will be submitted. If there are problems with the PR, there will be comments for improvement. , developers need to make fixes based on improvement comments. If the PR is merged, it means that the task has been completed, and the developer will receive the bounty for the corresponding task.

## 3. How to contribute
### 3.1.Developer in organization

- Step 1: Clone the code and switch to the develop branch
- Step 2: Cut the development branch based on the develop branch
- Step 3: Develop the task according to the task spec
- Step 4: Submit the code to the development branch and submit a PR
- Step 5: Savorlabs technical director reviews the code. If there are problems with the PR, make improvements based on the comments.
- Step 6: Merge PR and issue task rewards
  
### 3.2.Developers outside the organization
- The first step: fork the code to your own github
- Step 2: Branch development based on your own repo on github
- Step 3: Develop the task according to the task spec
- Step 4: Submit the code to your own github repo and submit PR to the savorlabs project
- Step 5: Savorlabs technical director reviews the code. If there are problems with the PR, make improvements based on the comments.
- Step 6: Merge PR and issue task rewards
