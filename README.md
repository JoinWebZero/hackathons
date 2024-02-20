# The Polkadot Hakcer Resource Guide

Welcome to a curated collection of resources for builders working on bounties specific to building on the core Polkadot tech stack and protocol! 

## ✨ Appchain development with the Polkadot SDK ✨ 

Planning on hacking on your own appchain idea using the Polkadot SDK? Start by [setting up your development environment](https://docs.substrate.io/install/) for Rust and Substrate. Then, dive into [this hands-on guide](https://paritytech.github.io/polkadot-sdk/master/polkadot_sdk_docs/guides/your_first_pallet/index.html) to learn about building your first FRAME pallet. 🚀

### 🖼️ Appchain templates

Here are some appchain templates for you to use depending on your needs:

- [Basic Substrate Node Template](https://github.com/substrate-developer-hub/substrate-node-template): a basic Substrate node, with minimal functionality and a template pallet perfect to start hacking with
- [Extended Parachain Template](https://github.com/paritytech/extended-parachain-template): a parachain template that comes with pre-configured functionality with basic governance and asset management pallets.
- [Frontier Parachain Template](https://github.com/paritytech/frontier-parachain-template): a parachain template for launching EVM-compatible parachains.

> *⚠️ **Note**: always check which version of Polkadot your project's Cargo files are using and keep consistent with them across your repo. Note that standalone node template uses `branch = "polkadot-v1.0.0"` on master, tagged to the `git = "https://github.com/paritytech/substrate.git"`. For the other templates, stick to specific release tags from the [Polkadot SDK repository](https://github.com/paritytech/polkadot-sdk/releases).*

### 🏆 Other notable resources for appchain developers

- [Trappist](https://github.com/paritytech/trappist): a web3 developer playground for experimenting with cross-chain applications and services built on the technologies spearheaded by the Polkadot Network.
- [Frontier](https://polkadot-evm.github.io/frontier/): a suite that provides an Ethereum compatibility layer for Substrate based chains.
- [XCM docs](https://paritytech.github.io/xcm-docs/): XCM is a language for communicating intentions between consensus systems.

### 🛠️ Relevant tools for appchain development

A list of existing tools specific to hacking with Substrate appchains:

- [Subalfred](https://github.com/hack-ink/subalfred): a CLI tool providing a bunch of useful things when hacking with Substrate chains.
- [Sidecar](https://github.com/paritytech/substrate-api-sidecar): a REST service that makes it easy to interact with blockchain nodes built using Substrate.

**🧪 Testing**

These may be a little advanced in the context of a hackathon and especially if you're new to Polkadot, but here nonetheless for you to check out!

- [Chopsticks](https://github.com/AcalaNetwork/chopsticks): create parallel reality of your Substrate network.
- [Zombienet](https://paritytech.github.io/zombienet/): a testing framework for Substrate based blockchains, providing a simple CLI tool that allows users to spawn and test ephemeral networks
- [SubWasm](https://github.com/chevdor/subwasm): a CLI utility to look inside a Substrate WASM Runtime, useful to inspect and compare the metadata of Substrate based runtimes such as Polkadot or Kusama.

_Have gander in the [Awesome Substrate repo](https://github.com/substrate-developer-hub/awesome-substrate) to see other tools and libraries that the developer community has built.♥️_

## 💻 UI and app development: interacting with Polkadot 

Below you'll find a list of templates, libraries and tools to help you get started with creating user-facing applications for Polkadot.

_👉 Want to jump into some hands-on learning material? Head to the [Polkadot JS API recipes](https://polkadotjs-developer-hub.gitbook.io/polkadotjs-recipies/)._

### 🪟 Templates

- [Polkadot React Template](https://github.com/shawntabrizi/polkadot-react-template): a minimal React JS template for Polkadot SDK chains.

### 🍦 Javascript libraries

- [Polkadot JS API](https://polkadot.js.org/docs/api/): the Javascript library for interacting with Substrate blockchains
- [Polkadot UI](https://github.com/polkadot-ui): helpful components for building Polkadot UIs, hooks, recipes, network information in a puzzle-fit manner (see [Polkadot Cloud](https://polkadot.cloud/) documentation)
- [Substrate Connect](https://github.com/paritytech/substrate-connect): run Wasm Light Clients for any Substrate based chain directly in your browser

### 🦀 Rust libraries

- [Subxt](https://docs.rs/subxt/latest/subxt/): a library for interacting with Substrate based nodes in pure Rust
- [Subxt Yew UI integration](https://github.com/paritytech/subxt/tree/master/examples/wasm-example): an example of building a UI entirely in Rust 

### 📱 Mobile development

- [substrate-sdk-ios](https://github.com/novasamatech/substrate-sdk-ios): native iOS SDK for developing client apps for Substrate-based networks
- [substrate-sdk-android](https://github.com/novasamatech/substrate-sdk-android): native Android SDK for developing client apps for Substrate-based networks

### 🏆 Other notable tools for application developers

- [Polkadot JS Apps UI](https://polkadot.js.org/apps/#/explorer): the all-in-one developer console for interacting with Polkadot including test networks
- [Metadata explorer](https://wiki.polkadot.network/docs/metadata): visualize the metadata of various parachains
- [Siws](https://siws.xyz/): an authentication standard for signing-in with a Substrate account.


## ➕ Additional resources ➕

_Have a look at the Polkadot Wiki for a complete list of tools in the Polkadot ecosystem [here](https://wiki.polkadot.network/docs/build-tools-index)._ Here's a list of additional useful resources:

## 🔎 Explorers

- [Subscan](https://polkadot.subscan.io/): an aggregate Web3 explorer for the Polkadot ecosystem
- [Polkassembly](https://polkadot.polkassembly.io/): an explorer to discover and participate in all things on-chain governance on the Polkadot network

## ✒️ Contract development
- [ink!](https://use.ink/): a programming language for Substrate native smart contracts.
- [Contracts UI](https://contracts-ui.substrate.io/?rpc=wss://rococo-contracts-rpc.polkadot.io): a simple UI for deploying contracts to various appchains that contain the contracts pallet. 

## 🛜 Testnets 

[Rococo](https://substrate.io/developers/rococo-network/) is a Polkadot-like test network maintained by Parity Technologies that contains a number of ecosystem parachains connected to it as well as [core system chains](https://wiki.polkadot.network/docs/learn-system-chains).

You might want to test out interacting with one of the system chains, like the AssetHub, BridgeHub, Coretime or People chains. Or deploy ink! contracts to the dedicated Contracts chain.

- Use the Rococo faucet to receive ROCs on the chain you want to use: https://paritytech.github.io/polkadot-testnet-faucet/
- Head to the Rococo developer console to explore the chains connected to it: https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Frococo-rpc.polkadot.io#/explorer


_Looking for a resource that's not here? Submit an issue to this repo and we'll make sure to address it._