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
- [Contracts UI](https://ui.use.ink/?rpc=wss://rpc2.paseo.popnetwork.xyz): a simple UI for deploying contracts to various appchains that contain the contracts pallet. 
- [Create dApp](https://www.npmjs.com/package/create-polkadot-dapp): bootstamp you project in just one command: `npx create-polkadot-dapp@latest`

_Or dive into building with the Polkadot SDK:_

Planning on hacking on your own appchain idea using the Polkadot SDK? Start by [setting up your development environment](https://docs.substrate.io/install/) for Rust and Substrate. Then, dive into [this hands-on guide](https://paritytech.github.io/polkadot-sdk/master/polkadot_sdk_docs/guides/your_first_pallet/index.html) to learn about building your first FRAME pallet. 🚀

Here are some appchain templates for you to start hacking on an appchain idea:

- [Generic Runtime Template](https://github.com/OpenZeppelin/polkadot-runtime-templates/tree/main/generic-template): This template by OpenZeppelin has all the basic features you expect to find on a typical L1 blockchain or parachain. Basic, yet preserving the most important pallets that are used in the Polkadot ecosystem today and a safe runtime base configuration. Head to [their docs](https://docs.openzeppelin.com/substrate-runtimes/1.0.0/) for a quickstart guide!
- [EVM Parachain Template](https://github.com/OpenZeppelin/polkadot-runtime-templates/tree/main/evm-template): a parachain template by OpenZeppelin for launching EVM-compatible parachains.
- [Minimal, Solochain and Parachain Templates](https://github.com/paritytech/polkadot-sdk/tree/master/templates): Default templates available on Polkadot SDK

Also, check out [Tanssi network](https://www.tanssi.network/) and [onpop.io](https://onpop.io/) which provide intuitive tooling that enables deployment of appchains. 

**💻 UI and app development for interacting with Polkadot and its connected chains**

A list of templates, libraries and tools to help you get started with creating user-facing applications for Polkadot. _👉 Want to jump into some hands-on learning material? Head to the [Polkadot JS API recipes](https://polkadotjs-developer-hub.gitbook.io/polkadotjs-recipies/)._

**🍦 Frontend libraries**

- [Polkadot API](https://papi.how/): Typescript API to interact with Polkadot chains
- [Polkadot UI](https://www.polkadot-ui.xyz): helpful components for building Polkadot UIs, hooks, recipes, network information in a puzzle-fit manner
- [Polkadot JS API](https://polkadot.js.org/docs/api/): the Javascript library for interacting with blockchains built with Polkadot SDK
- [Polkadot React Template](https://github.com/shawntabrizi/polkadot-react-template): a minimal React JS template for Polkadot SDK chains
- [Reactive DOT](https://reactivedot.dev/): A reactive library for building Substrate front-ends

**🦀 Rust libraries**

- [Subxt](https://docs.rs/subxt/latest/subxt/): a library for interacting with Substrate based nodes in pure Rust
- [Subxt Yew UI integration](https://github.com/paritytech/subxt/tree/master/examples/wasm-example): an example of building a UI entirely in Rust 

**📱 Mobile development**

- [substrate-sdk-ios](https://github.com/novasamatech/substrate-sdk-ios): native iOS SDK for developing client apps for Substrate-based networks
- [substrate-sdk-android](https://github.com/novasamatech/substrate-sdk-android): native Android SDK for developing client apps for Substrate-based networks

**🏆 Other notable tools for application developers**

- [Polkadot JS Apps UI](https://polkadot.js.org/apps/#/explorer): the all-in-one developer console for interacting with Polkadot including test networks
- [Polkadot Developer Console](https://console.polkadot.cloud/): Still in alpha phase, but under active development.
- [Metadata explorer](https://wiki.polkadot.network/docs/metadata): visualize the metadata of various parachains
- [Siws](https://siws.xyz/): an authentication standard for signing-in with a Substrate account with Talisman.


## ➕ Additional resources ➕

_Have a look at the Polkadot Wiki for a complete list of tools in the Polkadot ecosystem [here](https://wiki.polkadot.network/docs/build-tools-index)._ Here's a list of additional useful resources:

- [DotCodeSchool](https://dotcodeschool.com/courses): short courses on blockchain development
- [Polkadot Open Source Stack](https://wiki.polkadot.network/docs/build-open-source): A collection of Open GitHub repositories fuunded by Web3 Foundation grants and Polkadot Treasury.

## 🛜 Testnets 

[Paseo](https://github.com/paseo-network) is a Polkadot-like test network maintained by the Polkadot community that contains a number of ecosystem parachains connected to it as well as [core system chains](https://wiki.polkadot.network/docs/learn-system-chains).

You might want to test out interacting with one of the system chains, like the AssetHub, BridgeHub, Coretime or People chains. Or deploy ink! contracts to the dedicated Contracts chain.

- Use the Polkadot faucet to receive PAS or any token of the test chains you like to experiment with: https://faucet.polkadot.io/
- Head to the Rococo developer console to explore the chains connected to it: https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Fpaseo.rpc.amforc.com#/explorer
