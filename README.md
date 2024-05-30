# The Polkadot Hacker Resource Guide

Welcome to a curated collection of resources to guide you through building in the [Polkadot Ecosystem](https://polkadot.network/).

## Overview

- [Polkadot wallets](https://github.com/haquefardeen/awesome-dot?tab=readme-ov-file#wallets): a list of Polkadot compatible wallets you may want to use in your solutions.
- [Polkadot block explorers](https://github.com/haquefardeen/awesome-dot?tab=readme-ov-file#block-explorers): Subscan and Statescan are your go-to block explorers for querying Polkadot and all its connected chains.

## Popular consumer and community apps built for Polkadot

- [All things governance](https://github.com/haquefardeen/awesome-dot?tab=readme-ov-file#governance): explorers, dashboards and tools for interacting with OpenGov.
- [Bridging solutions](https://github.com/haquefardeen/awesome-dot?tab=readme-ov-file#bridges): get familiar with the bridging solutions out there!
- [Community projects](https://github.com/haquefardeen/awesome-dot?tab=readme-ov-file#community-projects): check out some popular community projects you may want to take inspiration from.
- [Popular dApps on Polkadot](https://github.com/haquefardeen/awesome-dot?tab=readme-ov-file#dapps): a list of dApps in production powered by Polkadot.

_Curious about working full-time in the Polkadot ecosystem? Visit the [Polkadot ecosystem job board](https://polkadot.getro.com/jobs)._

## Developer resources

**🦀 Appchain development** 

_Get started with contract development:_

- [ink!](https://use.ink/): a programming language for Substrate native smart contracts.
- [Contracts UI](https://contracts-ui.substrate.io/?rpc=wss://rococo-contracts-rpc.polkadot.io): a simple UI for deploying contracts to various appchains that contain the contracts pallet. 

_Or dive into building with the Polkadot SDK:_

Planning on hacking on your own appchain idea using the Polkadot SDK? Start by [setting up your development environment](https://docs.substrate.io/install/) for Rust and Substrate. Then, dive into [this hands-on guide](https://paritytech.github.io/polkadot-sdk/master/polkadot_sdk_docs/guides/your_first_pallet/index.html) to learn about building your first FRAME pallet. 🚀

Here are some appchain templates by Open Zeppelin for you to start hacking on an appchain idea:

- [Generic Substrate Node Template](https://github.com/OpenZeppelin/polkadot-runtime-templates/tree/main/generic-template): This template has all the basic features you expect to find on a typical L1 blockchain or parachain. Basic, yet preserving the most important pallets that are used in the Polkadot ecosystem today and a safe runtime base configuration. Head to [their docs](https://docs.openzeppelin.com/substrate-runtimes/1.0.0/) for a quickstart guide!
- [EVM Parachain Template]([https://github.com/paritytech/frontier-parachain-template](https://github.com/OpenZeppelin/polkadot-evm-runtime-template)): a parachain template by Open Zeppelin for launching EVM-compatible parachains.

**💻 UI and app development for interacting with Polkadot and its connected chains**

A list of templates, libraries and tools to help you get started with creating user-facing applications for Polkadot. _👉 Want to jump into some hands-on learning material? Head to the [Polkadot JS API recipes](https://polkadotjs-developer-hub.gitbook.io/polkadotjs-recipies/)._

**🍦 Javascript libraries**

- [Polkadot JS API](https://polkadot.js.org/docs/api/): the Javascript library for interacting with Substrate blockchains
- [Polkadot UI](http://www.polkadot-ui.xyz): helpful components for building Polkadot UIs, hooks, recipes, network information in a puzzle-fit manner
- [Substrate Connect](https://github.com/paritytech/substrate-connect): run Wasm Light Clients for any Substrate based chain directly in your browser
- [Polkadot React Template](https://github.com/shawntabrizi/polkadot-react-template): a minimal React JS template for Polkadot SDK chains.

**🦀 Rust libraries**

- [Subxt](https://docs.rs/subxt/latest/subxt/): a library for interacting with Substrate based nodes in pure Rust
- [Subxt Yew UI integration](https://github.com/paritytech/subxt/tree/master/examples/wasm-example): an example of building a UI entirely in Rust 

**📱 Mobile development**

- [substrate-sdk-ios](https://github.com/novasamatech/substrate-sdk-ios): native iOS SDK for developing client apps for Substrate-based networks
- [substrate-sdk-android](https://github.com/novasamatech/substrate-sdk-android): native Android SDK for developing client apps for Substrate-based networks

**🏆 Other notable tools for application developers**

- [Polkadot JS Apps UI](https://polkadot.js.org/apps/#/explorer): the all-in-one developer console for interacting with Polkadot including test networks
- [Metadata explorer](https://wiki.polkadot.network/docs/metadata): visualize the metadata of various parachains
- [Siws](https://siws.xyz/): an authentication standard for signing-in with a Substrate account with Talisman.


## ➕ Additional resources ➕

_Have a look at the Polkadot Wiki for a complete list of tools in the Polkadot ecosystem [here](https://wiki.polkadot.network/docs/build-tools-index)._ Here's a list of additional useful resources:


## 🛜 Testnets 

[Rococo](https://substrate.io/developers/rococo-network/) is a Polkadot-like test network maintained by Parity Technologies that contains a number of ecosystem parachains connected to it as well as [core system chains](https://wiki.polkadot.network/docs/learn-system-chains).

You might want to test out interacting with one of the system chains, like the AssetHub, BridgeHub, Coretime or People chains. Or deploy ink! contracts to the dedicated Contracts chain.

- Use the Rococo faucet to receive ROCs on the chain you want to use: https://paritytech.github.io/polkadot-testnet-faucet/
- Head to the Rococo developer console to explore the chains connected to it: https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Frococo-rpc.polkadot.io#/explorer
