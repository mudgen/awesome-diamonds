
  <h1 align="center">Awesome Diamonds</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="http://makeapullrequest.com">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>    
  </p>
  
  <p align="center">A curated list of awesome EIP2535 Diamonds resources, libraries, tools and more.</p>
  <p align="center">Please check the <a href="CONTRIBUTING.md">contribution guidelines</a> for information on formatting and writing pull requests.</p>
  

# Official

* [EIP2535 Diamonds](https://eips.ethereum.org/EIPS/eip-2535) - Standard.
* [EIP2535 Diamonds discussion thread](https://github.com/ethereum/EIPs/issues/2535) - Github issue created to discuss Diamonds.
* [Twitter @eip2535](https://twitter.com/eip2535) - Twitter handle.
* [EIP2535 Discord Server](https://discord.gg/kQewPw2) - Discord server for discussing EIP2535 Diamonds and related things.
* [Diamond reference implementation comparisons](https://github.com/mudgen/diamond) - Compares Diamond reference implementations.
* [diamond-1-hardhat](https://github.com/mudgen/diamond-1-hardhat) - Simple Diamond reference implementation.
* [diamond-2-hardhat](https://github.com/mudgen/diamond-2-hardhat) - Gas-optimized Diamond reference implementation.
* [diamond-3-hardhat](https://github.com/mudgen/diamond-3-hardhat) - Simple loupe (introspecting functions) Diamond reference implementation.

# Articles

## Diamonds

* [Introduction to EIP-2535 Diamonds](https://eip2535diamonds.substack.com/p/introduction-to-the-diamond-standard?s=w) - Explains the problem diamonds were initially developed to solve, how they work, how to organize them, and how to deploy and upgrade them.

## Diamond Storage

* [How Diamond Storage Works](https://dev.to/mudgen/how-diamond-storage-works-90e) - Explains diamond storage and shows an example.
* [New Storage Layout For Proxy Contracts and Diamonds](https://medium.com/1milliondevs/new-storage-layout-for-proxy-contracts-and-diamonds-98d01d0eadb) - First written article that describes diamond storage.

## Diamonds Used in Projects

* [Dark Forest & the Diamond Standard](https://blog.zkga.me/dark-forest-and-the-diamond-standard) - Dark Forest project moves to and dicusses diamonds.
* [The Diamond Standard: A new paradigm for upgradeability] - DerivaDEX on diamonds.

# Libraries

* [SolidState Solidity](https://github.com/solidstate-network/solidstate-solidity) - Upgradeable-first Solidity smart contract development library that supports diamonds.

# Tools

* [Louper - The Ethereum Diamond Inspector](https://louper.dev/) - User interface for diamonds.
* [hardhat-diamond-abi](https://github.com/projectsophon/hardhat-diamond-abi) - Hardhat plugin to combine multiple ABIs into a Diamond ABI artifact. 
* [hardhat-deploy](https://github.com/wighawag/hardhat-deploy#builtin-in-support-for-diamonds-eip2535) - Hardhat plugin that supports deploying, upgrading and managing diamonds.

# Audits

### Omniscia

*  [Smart Contract Audit](https://omniscia.io/alliance-block-multitoken-bridge/) - Omniscia published a smart contract audit of the diamond implementing AllianceBlock’s token bridge, which uses the [diamond-3](https://github.com/mudgen/diamond-3-hardhat) implementation.

### Certik

* [Smart Contract Audit](https://www.certik.org/projects/aavegotchi) - Certik published a smart contract audit of Aavegotchi’s core diamond which use the  [diamond-3](https://github.com/mudgen/diamond-3-hardhat) implementation.
* [Smart Contract Audit](https://raw.githubusercontent.com/DOTCPro/Audit/main/DOTC-Security-Rep.pdf) - Certik published a smart contract audit of DOTC’s diamond. 

### Quantstamp

* [Smart Contract Audit](https://certificate.quantstamp.com/full/aavegotchi-ghst-staking) - Quantstamp published a smart contract audit of Aavegotchi’s staking diamond which used the [diamond-2](https://github.com/mudgen/diamond-2-hardhat) implementation.

* [Smart Contract Audit](https://raw.githubusercontent.com/BarnBridge/BarnBridge-PM/master/audits/BarnBridge%20DAO%20audit%20by%20Quanstamp.pdf) - Quantstamp published a smart contract audit of BarnBridge’s [Barn diamond](https://github.com/BarnBridge/BarnBridge-Barn), which uses BarnBridge’s own implementation of EIP-2535 Diamonds based on diamond-1. 

* [Smart Contract Audit](https://certificate.quantstamp.com/full/deriva-dex) - Quantstamp published a smart contract audit of DerivaDEX’s [governance diamond](https://gitlab.com/derivadex/dips/-/tree/master/packages/protocol/contracts), which uses the [diamond-3](https://github.com/mudgen/diamond-3-hardhat) implementation. 

### MixBytes

* [Smart Contract Audit](https://github.com/pie-dao/audits/blob/main/Mixbytes%20-%20ExperiPie_Smart_Contrac%202020-12-11.pdf) - MixBytes published a smart contract audit of PieDAO’s [ExperiPie diamond](https://github.com/pie-dao/initialisable-diamond), which uses the diamond-2 implementation.

### Haechi Audit

* [Smart Contract Audit](https://github.com/BarnBridge/BarnBridge-Barn) - Haechi Audit published a smart contract audit of BarnBridge’s Barn diamond, which uses BarnBridge’s own implementation of EIP-2535 Diamonds based on diamond-1. 




