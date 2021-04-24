---
layout: cv
title: Rohit Narurkar
---
# Rohit Narurkar
Software Engineer, Musician

<div id="webaddress">
<a href="rohit.narurkar@protonmail.com">rohit.narurkar@protonmail.com</a>
| <a href="http://github.com/roynalnaruto">Github profile</a>
</div>


### Experience

Rust, Golang, Solidity, Elixir, Docker, K8s


### Other Interests Include

Chess, Poker, Music, Football


## Personal Projects
`2021`
__Eth Keystore__ [repository](https://github.com/roynalnaruto/eth-keystore-rs)

- Authored the [eth-keystore](https://github.com/roynalnaruto/eth-keystore-rs) crate used by [ethers-rs](https://github.com/gakonst/ethers-rs) for supporting Web3 encrypted JSON keystores.

`2020`
__Moebius__ [repository](https://github.com/roynalnaruto/moebius)

- Moebius is a cross-chain oracle that bridges on-chain Ethereum data to Solana.
- [Won 3rd place](https://medium.com/solana-labs/announcing-the-winners-of-solanas-inaugural-hackathon-66a280b33e6) in Solana's Hackathon

`2020`
__Monkey__ [repository](https://github.com/roynalnaruto/monkey)

- Monkey is a toy blockchain powered by [libp2p](https://github.com/libp2p/rust-libp2p)
- Using the [Monkey CLI](https://raw.githubusercontent.com/roynalnaruto/monkey/master/img/demo.gif), peers can fight to create blocks in the Monkey blockchain
- Monkey's Proof of Work is proposing a wordset not used previously in the chain

`2020`
__Zero Knowledge Range Proofs__ [repository](https://github.com/roynalnaruto/range_proof)

- Pure Rust implementation of the ZK Range Proofs protocol described [here](https://hackmd.io/@dabo/B1U4kx8XI)
- Prover can prove to Verifier that a number of their choice lies in a range [0, 2^n)
- Protocol depends on a Polynomial Commitment Scheme

`2020`
__RsTx__, [repository](https://github.com/roynalnaruto/rs_tx_client)

- Rust client to implement Stealth Addresses for Ethereum.
- The implementation is based on [ECDH protocol](https://en.bitcoin.it/wiki/ECDH_address)
- [Smart contract](https://github.com/roynalnaruto/rs_tx_contracts) on Ethereum is used to persist and communicate the nonce point
- [Subgraph](https://github.com/roynalnaruto/rs_tx_subgraph), powered by [The Graph](https://thegraph.com/) is used to query Ethereum blockchain

`2020`
__Guess My Word__ (In Progress), [repository](https://github.com/roynalnaruto/guessmyword)

- A Proof of Concept project for playing the [Guess My Word](https://hryanjones.com/guess-my-word/) game
- Operator provides a zkSNARK proof for the verdict
- Game player can verify the soundness of provided verdict

`2020`
__ZeKstament__, [repository](https://github.com/roynalnaruto/ZeKstament)

- a ÐApp powered by [AZTEC Protocol](https://www.aztecprotocol.com/), that lets users create a zero knowledge testament for their Crypto Assets
- Asset distribution is stored in the form of confidential AZTEC UTXO notes, unlocked after a year of inactivity

`2018`
__b.lock Password Manager__, [repository](https://github.com/BlockProject/b-lock)

- b.lock is a [Chrome extension](https://chrome.google.com/webstore/detail/block-password-manager/hjbpkcanpblbdfeoogkbpkbjmacakmjn) that helps users manage passwords and secret notes in a secure and trustless way
- Data is encrypted and stored on a public blockchain

## Work Experience

`May 2020-Present`
__Backend Engineer, [Ren](https://renproject.io/)__, Remote

- *[Multichain](https://github.com/renproject/multichain)*
  - Build and maintain Ren's [Multichain](https://github.com/renproject/multichain) project aimed at supporting various blockchains by implementing a Multichain interface
  - This allows RenVM to interact with several chains using this unified interface
  - Built support for [Solana](https://github.com/renproject/multichain/pull/67), [Substrate](https://github.com/renproject/multichain/pull/54), [Cosmos](https://github.com/renproject/multichain/pull/22), [Filecoin](https://github.com/renproject/multichain/pull/24) and various [UTXO chains](https://github.com/renproject/multichain/tree/master/chain/bitcoin)
  - Built a robust [test suite](https://github.com/renproject/multichain/blob/master/multichain_test.go) for [Multichain CI](https://github.com/renproject/multichain/actions)

- *[Ren Gateway](https://github.com/renproject/ren-solana/wiki), Solana*
  - Build and maintain Ren's [Gateway](https://github.com/renproject/ren-solana) program for Solana
  - The gateway logic heavily relies on program-derived addresses and cross-program invocations

- *[MPC](https://github.com/renproject/mpc)*
  - Contributed to Ren's [Multi-Party Computation](https://github.com/renproject/mpc) implementation
  - Key contributions include [Biased Random Number Generation](https://github.com/renproject/mpc/pull/12), [Random Number Generation](https://github.com/renproject/mpc/pull/9) and [Random Zero Generation](https://github.com/renproject/mpc/pull/13)

- *Ren DevOps* (Private Repository)
  - Build and Maintain Ren's DevOps infrastructure powered by Kubernetes.

- *Ren Darknode* (Private Repository)
  - Contributed to Ren's Darknode project that powers RenVM.

- *[Hyperdrive](https://github.com/renproject/hyperdrive/tree/release/0.4.0)*
  - Implemented a [test suite](https://github.com/renproject/hyperdrive/pull/84) for Ren's [Hyperdrive](https://github.com/renproject/hyperdrive/tree/release/0.4.0) consensus engine.
  - Hyperdrive is a Tendermint-flavored consensus algorithm used by the Darknodes to propose and commit to data in RenVM.

`June 2020-Present`
__Contributor, [ethers-rs](https://github.com/gakonst/ethers-rs)__

Key contributions:
- (1) Multicall functionality for batching calls [PR](https://github.com/gakonst/ethers-rs/pull/43)
- (2) Gas Oracles as Middleware [PR](https://github.com/gakonst/ethers-rs/pull/56)
- (3) Support for Web3 JSON keystore [PR](https://github.com/gakonst/ethers-rs/pull/138)
- (4) DS Proxy support as Middleware for proxy transactions [PR](https://github.com/gakonst/ethers-rs/pull/165)
- (5) Support for BIP-39 mnemonic phrase wallets [PR](https://github.com/gakonst/ethers-rs/pull/256)

`June 2019-Jan 2020`
__Tech Lead, [Digix](https://digix.global/#/)__, Singapore

- *Electron Marketplace* (Private Repository)
- [Electron](https://digix.global) is Digix's marketplace for [DGX](https://digix.global/#/ecosystem), the gold-backed token.
- Worked on architecting and building a complete revamp of Digix's legacy marketplace.
- Electron consists of
  - Modular smart contracts implementing Digix's Provenance Protocol
  - Elixir servers connected via a message queue to:
    - (1) Handle user authentication and price signing
    - (2) Serve pricefeeds
    - (3) Cache and serve asset metadata
    - (4) Watch and process latest Ethereum blocks
    - (5) Secure authority keys to sign and broadcast authorised transactions
- Electron has been deployed on the Mainnet and has been live since February 2020

`Feb 2018-May 2019`
__Software Engineer, [Digix](https://digix.global/#/)__, Singapore

- *DigixDAO*
- [DigixDAO](https://community.digix.global/#/) is Digix's DAO that funds projects building integrations with DGX token
- Worked in a team of two, to design, [architect](https://github.com/DigixGlobal/dao-contracts/blob/master/doc/DigixDAO_Governance_Model.pdf) and build the [smart contract logic for DigixDAO](https://github.com/DigixGlobal/dao-contracts)
- The security audit of the smart contracts is published [here](https://github.com/DigixGlobal/dao-contracts/blob/master/doc/chainsecurity_digix.pdf)
- DigixDAO contracts implement
  - (1) [State transition](https://github.com/DigixGlobal/dao-contracts/blob/master/doc/digixdao-proposal-state-diagram.jpg) for Proposals
  - (2) Stake locking mechanism
  - (3) User reputation
  - (4) Voting mechanism
  - (5) Reward distribution, as briefly described [here](https://github.com/DigixGlobal/dao-contracts#smart-contract-architecture)
- DigixDAO has two off-chain servers to improve user experience
  - (1) [Info Server](https://github.com/DigixGlobal/info-server), Node JS server responsible for watching latest blocks and creating an off-chain replica of on-chain data
  - (2) [DAO Server](https://github.com/DigixGlobal/dao-server), Ruby on Rails server responsible for storing off-chain user data and supporting authentication

`Oct 2015-Jan 2018`
__Software Engineer, [Works Applications](https://www.worksap.sg/)__, Singapore


## Education

`2010-2015`
__Indian Institute of Technology, Kharagpur__

- BTech. Honours & MTech. Mechanical Engineering
  - Worked with Prof. Manab Kumar Das on studying and simulating high Reynolds number flows
  - by computing on Nvidia GPUs. We implemented the Lattice Boltzmann Methods for simulating
  - three dimensional fluid flow for a Reynolds number as high as 10,000. Using CUDA,
  - we achieved tremendous computational speed-up that helped us solve this problem.
  - Some of the work has been [documented](https://rohitnarurkar.wordpress.com/category/gpu-gpgpu/) on my blog.

`May-July, 2014`
__College of Computing, Georgia Institute of Technology__

- Research Assistant under Prof. Edmond Chow
  - I was working on General Purpose Computing on GPUs (GPGPU). I primarily focused on
  - solving fluid dynamics and numerical methods using Nvidia’s CUDA platform for GPGPU.
  - I worked with Prof. Edmond Chow at Georgia Tech’s College of Computing on
  - simulating variable-sized particle system using Brownian Dynamics.
  - The breakthroughs were:
    - (1) Existing related work was limited to assumption of constant sized particles
    - (2) Achieving computational speed up by using the Parallel Fast Multipole Methods

<!-- ### Footer

Last updated: April 2021 -->
