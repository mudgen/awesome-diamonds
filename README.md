
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
* [A Beginner’s Guide to The Diamond Standard Proxy](https://blessingemah.medium.com/a-beginners-guide-to-the-diamond-standard-proxy-b57076365403) - Explains EIP-2535 Diamonds.
* [Idiots Guide to Using an EIP-2535 Diamond Proxy](https://andrewedwards.substack.com/p/coming-soon)
* [EIP 2535: Diamond standard explained — Part 1: Why diamonds?](https://bitsbyblocks.com/eip-2535-diamond-standard-explained-part-1-why-diamonds/)
* [EIP 2535: Diamond standard explained – Part 2: What are diamonds and how they work](https://bitsbyblocks.com/eip-2535-diamond-standard-explained-part-2-what-are-diamonds-and-how-they-work/)
* [EIP 2535: Diamond standard explained – Part 3: Understanding storage patterns in diamonds](https://bitsbyblocks.com/eip-2535-diamond-standard-explained-part-3-understanding-storage-patterns-in-diamonds/)

### Diamond Storage

* [How Diamond Storage Works](https://dev.to/mudgen/how-diamond-storage-works-90e) - Explains diamond storage and shows an example.
* [New Storage Layout For Proxy Contracts and Diamonds](https://medium.com/1milliondevs/new-storage-layout-for-proxy-contracts-and-diamonds-98d01d0eadb) - First written article that describes diamond storage.
* [AppStorage Pattern for State Variables in Solidity](https://eip2535diamonds.substack.com/p/appstorage-pattern-for-state-variables?s=w) - Describes and shows AppStorage.

### Diamond Upgrades

* [Diamond Upgrades](https://eip2535diamonds.substack.com/p/diamond-upgrades?s=w) - How to perform diamond upgrades.
* [Example of Adding New State Variables in Diamond Upgrade](https://eip2535diamonds.substack.com/p/example-of-a-diamond-upgrade?s=w) - Shows how to add new state variables to a diamond.

### Diamonds in Projects

* [Smart Contracts as Apps](https://0xhabitat.substack.com/p/smart-contracts-as-apps?s=r) - EIP-2535 Diamonds and the feasibility of a DAO Operating System
* [Dark Forest & the Diamond Standard](https://blog.zkga.me/dark-forest-and-the-diamond-standard) - Dark Forest project moves to and dicusses diamonds.
* [The Diamond Standard: A new paradigm for upgradeability](https://medium.com/derivadex/the-diamond-standard-a-new-paradigm-for-upgradeability-569121a08954) - DerivaDEX on diamonds.
* [We like the (EIP-2535) Diamonds](https://blog.premia.finance/we-like-the-eip-2535-diamonds-90184b2e6741) - Premia Finance talks about their use of diamonds.
* [Why Gotchivault is upgrading to the Diamond standard](https://medium.com/@bearded.eth/diamonds-are-a-proxys-best-friends-c302cca82203) - How to upgrade an existing proxy contract to EIP2535 Diamonds.
* [Handling multiple tokens, with a modern solidity architecture via Diamonds & ERC1155](https://dev.to/nohehf/handling-multiple-tokens-with-a-modern-solidity-architecture-via-diamonds-erc1155-1h7e)
* [Smart contract packages — upgradeability for normal people](https://medium.com/@tjvs/smart-contract-packages-upgradeability-for-normal-people-8646e817e196)

# Videos

* [Ethereum Diamonds - EIP-2535 Multi Facet Proxy](https://youtu.be/yKLDBsYPyE8)
* [How to Organize a Diamond with Facets](https://youtu.be/qHMdqHJMXww)
* [Create Diamond Contracts In Your Browser Using Remix And Louper](https://youtu.be/8p4NhC9sLDA)
* [Share Functions And Storage With Diamond Contracts | Louper/Remix](https://youtu.be/6a379dRTcXU)


# Libraries

* [SolidState Solidity](https://github.com/solidstate-network/solidstate-solidity) - Upgradeable-first Solidity smart contract development library that supports diamonds.
* [ERC20 Facet](https://github.com/danfinlay/erc20-diamond-facet) - A facet that adds ERC-20 token functionality to the host contract.
* [ERC721A-Upgradeable](https://github.com/chiru-labs/ERC721A-Upgradeable) - Gas efficient ERC721 implementation.
* [ERC1155-DiamondStorage](https://github.com/rachit2501/ERC1155-Diamond) - ERC1155 Implementation

# Tools

* [Louper - The Ethereum Diamond Inspector](https://louper.dev/) - User interface for diamonds.
* [hardhat-diamond-abi](https://github.com/projectsophon/hardhat-diamond-abi) - Hardhat plugin to combine multiple ABIs into a Diamond ABI artifact.
* [hardhat-deploy](https://github.com/wighawag/hardhat-deploy#builtin-in-support-for-diamonds-eip2535) - Hardhat plugin that supports deploying, upgrading and managing diamonds.
* [Inspector Facet](https://github.com/bugout-dev/inspector-facet) - Inspection utility for EIP2535 Diamond proxies. Written in Python.
* [Zem](https://github.com/anders-torbjornsen/zem) - Hardhat deployment management system that supports deploying, upgrading and managing diamonds.
* [Foundry-Hardhat-Diamonds](https://github.com/Timidan/Foundry-Hardhat-Diamonds) - Mimimal template for Diamonds
* [0xpm](https://0xpm.app/) - Diamond-based smart contract package manager.
* [diamond-etherscan](https://github.com/zdenham/diamond-etherscan) - Make your EIP-2535 Diamond etherscan compatible.


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
2. [ERC721A-Upgradeable](https://github.com/chiru-labs/ERC721A-Upgradeable)
3. PieDAO
4. Boson Protocol
5. hardhat-deploy
6. Nifty Cannon
7. AllianceBlock
8. Louper
9. solidstate-solidity
10. Nayms
11. Diamond Setter
12. Sherlock
13. Premia Finance
15. Nocturnal Finance 
17. scaffold-eth
18. diamond-starter-kit
19. scaffold-eth-diamond-standard
20. Sanshu Inu
21. Gelato Network
22. Teller Finance
23. seen.haus
24. thx.network
25. Token Gallery
27. Beanstalk Protocol
28. kanaloa.network
29. PoolSharks
30. Bitpixel
31. neodymium-contracts
32. INU Token
33. Sigmadex
34. TuffToken
35. hardhat-diamond-abi
36. EnterDAO
37. Gemcutter
38. GNUS.AI
39. Dark Forest
40. Moonstream DAO
41. Chain of Empires
42. LI.FI
43. cryptopoopz.com
44. Copium Wars
45. Typenauts
46. Boson Protocol
47. connext.network
1. [The Saudis](https://www.thesaudisnft.com/)
1. [Spring Game](https://spring.game/)
1. [oncyber](https://oncyber.io/)
1. [Avathereum](https://avathereum.com/)
1. [Cartesi](https://cartesi.io/)
1. [Energy Web](https://www.energyweb.org)
1. [Shattered Eon](https://shatteredeon.io/)
2. Zem
