---
layout: cv
title: Rohit Narurkar
---
# Rohit Narurkar
Software Engineer, Ethereum Enthusiast, Musician

<div id="webaddress">
<a href="rohit.narurkar@protonmail.com">rohit.narurkar@protonmail.com</a>
| <a href="http://github.com/roynalnaruto">Github profile</a>
</div>


## Currently

Exploring Zero Knowledge Proofs. Here is a [summary of my journey](https://gist.github.com/roynalnaruto/2ce81b2255823526a6b3f779def7c4e2) so far.


### Experienced in

Smart contract development (Solidity), Backend development (Elixir, Node JS)


### Other Interests Include

Chess, Poker, Playing Music, Football


## Education

`2010-2015`
__Indian Institute of Technology, Kharagpur__

- BTech. Honours & MTech. Mechanical Engineering
  - *Thesis*
  - I worked with Prof. Manab Kumar Das on studying and simulating high Reynolds number flows
  - by computing on Nvidia GPUs. We implemented the Lattice Boltzmann Methods for simulating
  - three dimensional fluid flow for a Reynolds number as high as 10,000. Using CUDA,
  - we achieved tremendous computational enhancement, which could help us solve this problem.
  - Some of my work has been [documented on my blog](https://rohitnarurkar.wordpress.com/category/gpu-gpgpu/).

`May-July, 2014`
__College of Computing, Georgia Institute of Technology__

- Research Assistant under Prof. Edmond Chow
  - *Thesis*
  - I started working on General Purpose Computing on GPUs (GPGPU). I mainly focused on
  - solving fluid dynamics and numerical algebra problems using Nvidia’s CUDA platform for GPGPU.
  - I worked with Prof. Edmond Chow at Georgia Tech’s College of Computing on
  - simulating variable-sized particle system using Brownian Dynamics.
  - The breakthroughs were:
    - (1) Existing related work was limited to assumption of constant sized particles
    - (2) Achieving computational speed up by using the Parallel Fast Multipole Methods


## Personal Projects

`2020`
__ZeKstament__, [repository](https://github.com/roynalnaruto/ZeKstament)

- a ÐApp powered by [AZTEC Protocol](https://www.aztecprotocol.com/), that lets users create a zero knowledge testament for their Crypto Assets
- Asset distribution is stored in the form of confidential AZTEC UTXO notes, unlocked after a year of inactivity

`2018`
__b.lock Password Manager__, [repository](https://github.com/BlockProject/b-lock)

- b.lock is a [Chrome extension](https://chrome.google.com/webstore/detail/block-password-manager/hjbpkcanpblbdfeoogkbpkbjmacakmjn) that helps users manage passwords and secret notes in a secure and trustless way
- Data is encrypted and stored on a public blockchain


## Work Experience

`June 2019-Jan 2020`
__Tech Lead, Digix__, Singapore

- *Electron Marketplace*
- [Electron](https://digix.global) is Digix's marketplace for [DGX](https://digix.global/#/ecosystem), the gold-backed token.
- I worked on architecting and building a complete revamp of Digix's legacy marketplace.
- Electron consists of
  - A set of modular smart contracts implementing the Provenance Protocol, deployed to Ethereum.
  - A total of 5 elixir servers working together through a message queue to:
    - (1) Handle user authentication and price signing
    - (2) Serve pricefeeds
    - (3) Cache and serve gold assets metadata
    - (4) Watch and process latest Ethereum blocks
    - (5) Secure authority keys, to sign and broadcast authorised transactions
- Electron has been deployed on the Mainnet, and has been live since February 2020.
- _Electron repositories are private_

`Feb 2018-May 2019`
__Software Engineer, Digix__, Singapore

- *DigixDAO*
- [DigixDAO](https://community.digix.global/#/) is Digix's DAO that funds projects building integrations with DGX token.
- I worked in a team of two, to design, architect and build the [smart contract logic for DigixDAO](https://github.com/DigixGlobal/dao-contracts).
- A detailed technical model of [DigixDAO was documented](https://github.com/DigixGlobal/dao-contracts/blob/master/doc/DigixDAO_Governance_Model.pdf) as we progressed.
- The security audit of the smart contracts is published [here](https://github.com/DigixGlobal/dao-contracts/blob/master/doc/chainsecurity_digix.pdf)
- DigixDAO contracts implement
  - (1) [State transition](https://github.com/DigixGlobal/dao-contracts/blob/master/doc/digixdao-proposal-state-diagram.jpg) for Proposals
  - (2) Stake locking mechanism
  - (3) User reputation
  - (4) Voting mechanism
  - (5) Reward distribution, as briefly described [here](https://github.com/DigixGlobal/dao-contracts#smart-contract-architecture)
- DigixDAO has two servers responsible for improving user experience
  - (1) [Info Server](https://github.com/DigixGlobal/info-server), Node JS server responsible for watching latest blocks and creating an off-chain replica of on-chain data
  - (2) [DAO Server](https://github.com/DigixGlobal/dao-server), Ruby on Rails server responsible for storing off-chain user data and supporting authentication

- *Legacy Marketplace*
- I worked on testing the smart contracts for the legacy marketplace.
- I also worked on
  - Testing testnet deployment scripts
  - Maintenance of system after it was live

`Oct 2015-Jan 2018`
__Software Engineer, Works Applications__, Singapore

- *Mail Team*
- I worked on data modelling for Cassandra DB, Elasticsearch and full stack
- development using Spring Java and Javascript.
- My major contributions were:
  - Designing the front-end for the hybrid mobile application
  - Developing backend support for _mailing lists_
  - Developing backend support for _contacts_
- *PaaS Team*
  - I worked on setting up the OpenStack cluster and migrating most of our middleware
  - from AWS to OpenStack using Ansible scripts. As we moved towards Microservice Architecture
  - I worked on deploying services as Docker containers on the Kubernetes cluster.
  - The design of our PaaS system was still in progress when I left.


<!-- ### Footer

Last updated: March 2020 -->
