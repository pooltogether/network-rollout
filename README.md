# PrizePool V4 Network Rollout

PoolTogether V4 Network Rollout guide for deplying to new blockchains.

## 🏗️ Steps: Create PrizePool

Each sequence includes the following steps:

- **Deployment:** Deploy PrizePool smart contracts on blockchain.
- **Auto-Tasks:** Create LockAndPush & PrizeFlush Modules
- **Subgraphs:** Create Ticket Subgraph
- **API:** Configure Cron Jobs to Fetch Subgraph Data
- **Application:** Add new blockchain smart contracts to Production App

## 🚛 Stages: Setup, Tooling and Launch

The steps are grouped into 3 stages: **setup, tooling and launch.**

### Stage 1: Setup

The first stage is deploying the PrizePool smart contracts and configuring the OpenZeppeling Defender Auto-Tasks.
- Deployment
- Auto-Tasks

### Stage 2: Tooling

The second stage is setting up the caching and data availability services: subgraphs and flat-file prize database.
- Subgraphs
- API

### Stage 3: Launch

The third and final stage of a sequence is adding the new PrizePool to the Application frontend and completing Quality Assurance, before publishing to the production website.
- Application
- Quality Assurance

## ⛓️ Sequencing: Testnet and Mainnet

The rollout of a new PoolTogether PrizePool on a new blockchain is divided into two sequences: testnet and mainnet.

**Testnet Sequence:** Deployment on a live testnet envrionment i.e. Rinkeby, Kovan, Mumbai, etc...

**Mainnet Sequence:** Deployment on a live production envrionment i.e. Ethereum, Polygon, Optimism, etc...
