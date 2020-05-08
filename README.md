# awesome-ligo [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome [Ligo](https://ligolang.org/) resources, libraries, tools and more.


### Contents
- [Resources](#resources)
    - [Official](#official)
    - [Tutorials](#tutorials)
    - [Cheatsheet](#cheatsheet)
    - [Security](#security)
    - [Examples](#examples)
    - [Books](#books)
    - [Practice](#practice)
- [Libraries](#libraries)
- [Tools](#tools)
    - [General](#general)
    - [Audit](#audit)
    - [DevOps](#devops)
    - [JavaScript](#javascript)
    - [TypeScript](#typescript)
    - [Utility](#utility)
    - [Webpack](#webpack)
- [Editor Plugins](#editor-plugins)
    - [Visual Studio Code](#visual-studio-code)


## Resources
#### Official
- [Docs](https://ligolang.org/docs/intro/introduction) - Official documentation.
- [Tezos Agora Forum](https://forum.tezosagora.org/tag/ligo) - The Ligo posts in the Tezos Agora Forum
- [Tezos Stackexchange](https://tezos.stackexchange.com/questions/tagged/ligo) - Tezos's Stackexchange board with Ligo posts tagged.
- [Telegram](https://tezos.stackexchange.com/questions/tagged/ligo) - Telegram group.
- [Discord](https://discord.com/invite/9rhYaEt) - Discord group.
- [Ligo Gitlab Repo](https://gitlab.com/ligolang/ligo) - Source code.

#### Tutorials
- [Taco shop smart contract](https://ligolang.org/docs/tutorials/get-started/tezos-taco-shop-smart-contract/) - Taco shop smart contract

#### Cheatsheet
- [Cheat sheet](https://ligolang.org/docs/api/cheat-sheet) - A ligo cheat sheet

#### Security
- [Awesome Ethereum Security](https://github.com/crytic/awesome-ethereum-security) - Curated list of awesome Ethereum security references, guidance, tools, and more.
- [Capture the Ether](https://capturetheether.com/) - Game in which you hack Ethereum smart contracts to learn about security.
- [Ethereum Smart Contract Security Best Practices](https://consensys.github.io/smart-contract-best-practices/) - General security philosophy, known attacks, and sample code.
- [Not So Smart Contracts](https://github.com/crytic/not-so-smart-contracts) - Examples of common vulnerabilities, including code from real smart contracts.

#### Examples
- [Protofire smart contracts](https://github.com/protofire/tezos-contracts-examples) - This is a recopilation for smart contract development in Tezos.


#### Books
- [Blockchain in Action](https://www.manning.com/books/blockchain-in-action) - Book that teaches the essential principles of blockchain and how to create your own decentralized apps.
- [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook) - Mastering Ethereum is a book for developers, offering a guide to the operation and use of the Ethereum, Ethereum Classic, RootStock (RSK) and other compatible EVM-based open blockchains.
- [Permissioned Blockchains in Action](https://www.manning.com/books/permissioned-blockchains-in-action) - A guide to creating innovative applications using blockchain technology.


#### Practice
- [ChainShot](https://www.chainshot.com/) - Hands-on learning with challenging coding tutorials.
- [Eth Hole](https://ethhole.com/challenge) - Practice challenges for building portfolio, added to weekly.


## Libraries
- [Truffle](https://www.trufflesuite.com/docs/tezos/truffle/quickstart) - Development environment, testing framework and asset pipeline for Tezos.

## Tools
#### General
- [Ligo Ide](https://ide.ligolang.org/) - Online realtime compiler and runtime.
- [Faucet](https://faucet.tzalpha.net/) - A Tezos faucet for the Carthagenet network

#### Audit
- [Echidna](https://github.com/crytic/echidna) - Define properties for your smart contract then use fuzzing to catch security bugs.
- [Manticore](https://github.com/trailofbits/manticore) - Detects many common bug types, and can prove correctness properties with symbolic execution.
- [Mythril](https://github.com/ConsenSys/mythril) - Security analysis tool for smart contracts.
- [SmartCheck](https://tool.smartdec.net) - Online tool for checking smart contracts for vulnerabilities and bad practices.
- [Securify](https://securify.chainsecurity.com/) - Online tool for analyzing smart contracts for vulnerabilities and insecure coding.
- [Slither](https://github.com/crytic/slither) - Static analyzer with support for many common bug types, including visualization tools for security-relevant information.
- [MythX](https://mythx.io/) - Detection for security vulnerabilities in Ethereum smart contracts throughout the development life cycle


#### DevOps
- [Embark](https://github.com/embark-framework/embark) - Framework that allows you to easily develop and deploy DApps.
- [Moesif](https://www.moesif.com/docs/platform/ethereum-web3/) - Service that provides Ethereum smart contract analytics and anomaly detection for DApps and DAPIs.

#### JavaScript
- [solc-js](https://github.com/ethereum/solc-js) - JavaScript bindings for the Solidity compiler.
- [solidity-parser](https://github.com/federicobond/solidity-parser-antlr) - Solidity parser built in JavaScript.
- [sulk](https://github.com/lukehedger/sulk) - Configurable contract compilation.

#### TypeScript
- [Soltsice](https://github.com/Soltsice/Soltsice) - Generates strongly-typed TypeScript classes for contracts from Truffle artifacts with a single command.
- [TypeChain](https://github.com/ethereum-ts/TypeChain) - TypeScript bindings for Ethereum smart contracts.

#### Utility
- [solhint](https://github.com/protofire/solhint) - Solidity linter that provides security, style guide and best practice rules for smart contract validation.
- [Ethlint](https://github.com/duaraghav8/Ethlint) - Linter to identify and fix style & security issues in Solidity smart contracts.
- [sol-profiler](https://github.com/Aniket-Engg/sol-profiler) - CLI tool to list & store solidity smart contract methods attributes.
- [sol-tester](https://github.com/androlo/sol-tester) - Utilities for building, linking and testing contracts using go-ethereum and the simulated chain.
- [sol-verifier](https://github.com/Aniket-Engg/sol-verifier) - Verify solidity smart contracts on Etherscan.
- [solidity-coverage](https://github.com/sc-forks/solidity-coverage) - Code coverage tool.
- [truffle-plugin-verify](https://github.com/rkalis/truffle-plugin-verify) - Truffle plugin to verify smart contracts on Etherscan from the Truffle command line.
- [Tenderly CLI](https://github.com/Tenderly/tenderly-cli) - Speed up your development with error stack traces.

#### Webpack
- [solidity-loader](https://github.com/jeffscottward/solidity-loader) - Webpack loader.

## Editor Plugins
#### Visual Studio Code
- [Ligo Tools](https://marketplace.visualstudio.com/items?itemName=Ligo.ligo-tools) - A webview for LIGO related tasks like compile and dryrun.
- [ReasonLigo](https://marketplace.visualstudio.com/items?itemName=JamesBachini.reasonligo-vscode) - A syntax highlighter for ReasonLigo for developing smartcontracts with Tezos
- [PascalLigo](https://marketplace.visualstudio.com/items?itemName=LigoLang.pascaligo-vscode) - Pascaligo vscode includes syntax highlighting, and a language server for pascaligo a ligolang syntax.


---
