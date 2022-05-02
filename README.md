
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
* [EIP2535 Blog](https://eip2535diamonds.substack.com/) - Technical articles about diamonds.
* [EIP2535 Discord Server](https://discord.gg/kQewPw2) - Discord server for discussing EIP2535 Diamonds and related things.
* [Diamond reference implementation comparisons](https://github.com/mudgen/diamond) - Compares Diamond reference implementations.
* [diamond-1-hardhat](https://github.com/mudgen/diamond-1-hardhat) - Simple Diamond reference implementation.
* [diamond-2-hardhat](https://github.com/mudgen/diamond-2-hardhat) - Gas-optimized Diamond reference implementation.
* [diamond-3-hardhat](https://github.com/mudgen/diamond-3-hardhat) - Simple loupe (introspecting functions) Diamond reference implementation.

# Articles

### Diamonds

* [Introduction to EIP-2535 Diamonds](https://eip2535diamonds.substack.com/p/introduction-to-the-diamond-standard?s=w) - Explains the problem diamonds were initially developed to solve, how they work, how to organize them, and how to deploy and upgrade them.
* [EIP-2535: A standard for organizing and upgrading a modular smart contract system.](https://soliditydeveloper.com/eip-2535) - Describes what diamonds are, how they work and how to use them.
* [Diamond Loupe Functions](https://dev.to/mudgen/why-loupe-functions-for-diamonds-1kc3) - Explains the need and use of loupe functions (diamond introspecting functions).
* [How to Share Functions Between Facets of a Diamond](https://eip2535diamonds.substack.com/p/how-to-share-functions-between-facets?s=w) - Shows ways to share functionality between facets of a diamond.
* [A Beginner’s Guide to The Diamond Standard Proxy](https://blessingemah.medium.com/a-beginners-guide-to-the-diamond-standard-proxy-b57076365403)

### Diamond Storage

* [How Diamond Storage Works](https://dev.to/mudgen/how-diamond-storage-works-90e) - Explains diamond storage and shows an example.
* [New Storage Layout For Proxy Contracts and Diamonds](https://medium.com/1milliondevs/new-storage-layout-for-proxy-contracts-and-diamonds-98d01d0eadb) - First written article that describes diamond storage.
* [AppStorage Pattern for State Variables in Solidity](https://eip2535diamonds.substack.com/p/appstorage-pattern-for-state-variables?s=w) - Describes and shows AppStorage.

### Diamond Upgrades

* [Diamond Upgrades](https://eip2535diamonds.substack.com/p/diamond-upgrades?s=w) - How to perform diamond upgrades.
* [Example of Adding New State Variables in Diamond Upgrade](https://eip2535diamonds.substack.com/p/example-of-a-diamond-upgrade?s=w) - Shows how to add new state variables to a diamond.

### Diamonds in Projects

* [Dark Forest & the Diamond Standard](https://blog.zkga.me/dark-forest-and-the-diamond-standard) - Dark Forest project moves to and dicusses diamonds.
* [The Diamond Standard: A new paradigm for upgradeability](https://medium.com/derivadex/the-diamond-standard-a-new-paradigm-for-upgradeability-569121a08954) - DerivaDEX on diamonds.
* [We like the (EIP-2535) Diamonds](https://blog.premia.finance/we-like-the-eip-2535-diamonds-90184b2e6741) - Premia Finance talks about their use of diamonds.
* [Why Gotchivault is upgrading to the Diamond standard](https://medium.com/@bearded.eth/diamonds-are-a-proxys-best-friends-c302cca82203) - How to upgrade an existing proxy contract to EIP2535 Diamonds.

# Libraries

* [SolidState Solidity](https://github.com/solidstate-network/solidstate-solidity) - Upgradeable-first Solidity smart contract development library that supports diamonds.
* [ERC20 Facet](https://github.com/danfinlay/erc20-diamond-facet) - A facet that adds ERC-20 token functionality to the host contract.

# Tools

* [Louper - The Ethereum Diamond Inspector](https://louper.dev/) - User interface for diamonds.
* [hardhat-diamond-abi](https://github.com/projectsophon/hardhat-diamond-abi) - Hardhat plugin to combine multiple ABIs into a Diamond ABI artifact. 
* [hardhat-deploy](https://github.com/wighawag/hardhat-deploy#builtin-in-support-for-diamonds-eip2535) - Hardhat plugin that supports deploying, upgrading and managing diamonds.

# Audits

### Omniscia

*  [Smart Contract Audit](https://omniscia.io/alliance-block-multitoken-bridge/) - Omniscia published a smart contract audit of the diamond implementing AllianceBlock’s token bridge, which uses the [diamond-3](https://github.com/mudgen/diamond-3-hardhat) implementation.

*  [Smart Contract Audit](https://omniscia.io/seen-haus-nft-auction-sales/) - Omniscia published a smart contract audit of the [Seen.Haus Marketplace Diamond](https://github.com/seen-haus/seen-contracts), which uses the [diamond-3](https://github.com/mudgen/diamond-3-hardhat) implementation, modified for role-based access rather than single-owner.

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

# Projects using Diamonds

1. DerivaDEX
1. BarnBridge
1. Aavegotchi
1. PieDAO
2. Boson Protocol
3. hardhat-deploy
4. Nifty Cannon
5. AllianceBlock
6. Louper
7. solidstate-solidity
8. Nayms
9. Diamond Setter
10. Sherlock
11. Premia Finance
12. Love Boat Exchange
13. Nocturnal Finance 
15. Quotient.fi
16. scaffold-eth
17. diamond-starter-kit
18. scaffold-eth-diamond-standard
19. Sanshu Inu
20. Gelato Network
21. Teller Finance
22. seen.haus
23. thx.network
24. Token Gallery
25. Cyber
26. Beanstalk Protocol
27. kanaloa.network
28. PoolSharks
29. Bitpixel
30. neodymium-contracts
31. INU Token
32. Sigmadex
33. TuffToken
34. hardhat-diamond-abi
35. EnterDAO
36. Gemcutter
37. GNUS.AI
38. Dark Forest
39. Moonstream DAO
40. Chain of Empires
41. LI.FI
42. cryptopoopz.com
43. Copium Wars
