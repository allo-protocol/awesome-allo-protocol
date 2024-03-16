# Awesome Allo [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[ <img src="./static/lockup.svg" alt="Logo" width="350" height="100" align="right"> ](https://allo.gitcoin.co/?utm_source=awesome-allo&utm_medium=referral&utm_content=Allo)

> A curated list of awesome things built on Gitcoin&#39;s Allo Protocol.

Live on Mainnet

Allo is an open-source protocol that enables groups to efficiently and transparently allocate capital onchain.

## Contents

- [Official Docs and Quickstart](#official-docs-and-quickstarts)
  - [Updates](#updates)
  - [Official Documentation](#official-documentation)
  - [Learning Resources](#learning-resources)
- [Allocation Strategies](#allocation-strategies)
  - [Official Strategies](#official-strategies)
  - [Base Strategies](#base-strategies)
  - [Proof of Concept Strategies](#proof-of-concept-strategies)
  - [Community Strategies](#community-strategies)
- [Project Showcase](#project-showcase)

## Official Docs and Quickstarts

These resources are built and maintained by the Allo team

- [Allo Documentation](https://docs.allo.gitcoin.co/)
- [Allocation Strategy Starter Kit](https://github.com/allo-protocol/strategy-starter)
- [Allocation Strategy Spec Template](https://github.com/allo-protocol/allo-v2/blob/main/contracts/strategies/SpecTemplate.md)
- Allocation dApp starter kit (Coming Soon)
- [Allo contracts](https://github.com/allo-protocol/allo-v2/tree/main/contracts)
- [Allo v2 SDK](https://github.com/allo-protocol/allo-v2-sdk)
- [Subgraphs](https://github.com/allo-protocol/allo-v2-graph)
- [Inspiration for Builders](https://gitcoin.notion.site/Inspiration-for-builders-dc30da5f05964bdb948b22aba324d4a2)

### Updates

Stay up to date with the latest information on Allo Protocol.

- [ Official Website ](https://allo.gitcoin.co/?utm_source=awesome-allo&utm_medium=referral&utm_content=Allo)
- [ Twitter Account ](https://twitter.com/alloprotocol)
- [ Official Blog ](https://docs.allo.gitcoin.co/blog)
- [GitHub Discussion](https://github.com/orgs/allo-protocol/discussions)

### Official Documentation

These are the best places to get started with Allo Protocol.

- [Official Documentation](https://docs.allo.gitcoin.co/)
- [Conceptual Overview](https://docs.allo.gitcoin.co/overview)
- [Allo: Overview](https://docs.allo.gitcoin.co/allo)
- [Guide: Flow of Funds](https://docs.allo.gitcoin.co/allo/flow-of-funds)
- [Guide: Building on Allo](https://docs.allo.gitcoin.co/allo/building-on-allo)
- [Allocation Strategies: Overview](https://docs.allo.gitcoin.co/strategies)
- [Project Registry: Overview](https://docs.allo.gitcoin.co/project-registry)
- [Guide: Integrating with the Project Registry](https://docs.allo.gitcoin.co/project-registry/integrating-with-the-project-registry)

### Learning Resources

Resources provided by the Allo Protocol team to help you get up to speed.

- [Workshop: Allo v2 SDK](https://github.com/allo-protocol/allo-sdk-workshop-1)

## Allocation Strategies

Allocation strategies are an important part of Allo, as they govern how a pool
of capital is distributed. We highly recommend using the [allocation strategy
spec
template](https://github.com/allo-protocol/allo-v2/blob/main/contracts/strategies/SpecTemplate.md)
to document and write your own strategies.

This is a curated list of allocation strategy contracts. Note that some of these
have been audited, but many of them haven't. Use at your own risk. 

### Official Strategies

- [Donation Voting (Quadratic Funding) with Merkle Distribution and Direct
    Transfer](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/donation-voting-merkle-distribution-direct-transfer)
- [Donation Voting (Quadratic Funding) with Merkle Distribution and a Vault](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/donation-voting-merkle-distribution-vault)
- [Simple Quadratic Voting Strategy](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/qv-simple)
- [Simple RFP Strategy](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/rfp-simple)
- [Committee RFP Strategy](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/rfp-committee)

### Base Strategies

Base strategies provide the basic functionality for a type of allocation
mechanism and are meant to be built on and customized.

- [Base Allocation Strategy](https://github.com/allo-protocol/allo-v2/blob/main/contracts/strategies/BaseStrategy.sol)
- [Donation Voting (Quadratic Funding) Base Strategy](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/donation-voting-merkle-base)
- [Base Quadratic Voting Strategy](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/qv-base)

### Proof of Concept Strategies

The strategies serve as a proof of concept. They have not been audited.

- [Simple Direct Grants Strategy](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/_poc/direct-grants-simple)
- [Donation Voting (Quadratic Funding) with a custom registry](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/_poc/donation-voting-custom-registry)
- [Simple Donation Voting (Quadratic Funding) Strategy](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/_poc/donation-voting)
- [Committee RFP with grant distribution through Hedgey](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/_poc/hedgey)
- [Microgrants / Small Grants strategy](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/_poc/micro-grants)
- [Proportional Payout Strategy](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/_poc/proportional-payout)
- [Quadratic Voting with a governance token](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/_poc/qv-governance)
- [Hackathon QV Strategy](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/_poc/qv-hackathon)
- [Quadratic Voting with Tiered NFTs](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/_poc/qv-nft-tiered)
- [Wrapped Voting](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/_poc/wrapped-voting-nftmint)

### Community Strategies

- [Impact Stream's Quadratic Voting Strategy](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/_poc/qv-impact-stream)
- [Sablier Distribution Strategy](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/_poc/sablier-v2)
- [Committee RFP with grant distribution through Hedgey](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/_poc/hedgey)
- [Streaming Quadratic Funding](https://github.com/allo-protocol/allo-v2/tree/main/contracts/strategies/_poc/sqf-superfluid)

## Project Showcase

A showcase of some of the awesome dApps people have built on Allo.

- AlloScan: [Repo](https://github.com/allo-protocol/allo-scan)
- SeaGrants: [Website](https://www.seagrants.xyz/) | [Repo](https://github.com/allo-protocol/SeaGrants)
- Build3r: [Website](https://build3r.on.fleek.co/) | [Repo](https://github.com/chrisarevalo11/Build3r)
- Spray: [Website](https://www.spray.cash/) | [Repo](https://github.com/WuBruno/spray.cash)
- DAO Driven Crowdfunding Platform: [Website](https://alexandr-masl.github.io/frontend-gitcoin-alloV2-hackathon/) | [Repo](https://github.com/alexandr-masl/web3-crowdfunding-on-allo-V2)
- Alloliance: [Website](https://alloliance.vercel.app/) | [Repo](https://github.com/Alloliance)
- SolidGrant: [Website](https://solidgrant.click/home) | [Repo](https://github.com/web3senior/solidgrant)
- Conviction Voting App: [Website](https://gardens-v2.vercel.app/gardens) | [Repo](https://github.com/1Hive/gardens-v2)
- Grant Ships: [Website](https://grantships.fun) | [Repo](https://github.com/DAOmasons/allo-v2/tree/grantShips)
- PledgePost: [Website](https://v2-interface-sigma.vercel.app/) | [Repo](https://github.com/PledgePost/v2Interface)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
