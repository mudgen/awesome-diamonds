
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

# Websites

* [info.diamonds](https://www.info.diamonds/)

# Articles

### Diamonds

* [Introduction to EIP-2535 Diamonds](https://eip2535diamonds.substack.com/p/introduction-to-the-diamond-standard?s=w) - Explains the problem diamonds were initially developed to solve, how they work, how to organize them, and how to deploy and upgrade them.
* [Compliance with EIP-2535 Diamonds Standard](https://eip2535diamonds.substack.com/p/compliance-with-eip-2535-diamonds) - How implementations can comply with the standard.
* [EIP-2535: A Technical Overview of the Diamond Smart Contract Standard](https://hackmd.io/@Jesserc/HkZXGpC6j) - Overview and tutorial.
* [EIP-2535: A standard for organizing and upgrading a modular smart contract system.](https://soliditydeveloper.com/eip-2535) - Describes what diamonds are, how they work and how to use them.
* [Diamond Loupe Functions](https://dev.to/mudgen/why-loupe-functions-for-diamonds-1kc3) - Explains the need and use of loupe functions (diamond introspecting functions).
* [How to Share Functions Between Facets of a Diamond](https://eip2535diamonds.substack.com/p/how-to-share-functions-between-facets?s=w) - Shows ways to share functionality between facets of a diamond.
* [A Beginner’s Guide to The Diamond Standard Proxy](https://blessingemah.medium.com/a-beginners-guide-to-the-diamond-standard-proxy-b57076365403) - Explains EIP-2535 Diamonds.
* [Idiots Guide to Using an EIP-2535 Diamond Proxy](https://andrewedwards.substack.com/p/coming-soon)
* [EIP 2535: Diamond standard explained — Part 1: Why diamonds?](https://bitsbyblocks.com/eip-2535-diamond-standard-explained-part-1-why-diamonds/)
* [EIP 2535: Diamond standard explained – Part 2: What are diamonds and how they work](https://bitsbyblocks.com/eip-2535-diamond-standard-explained-part-2-what-are-diamonds-and-how-they-work/)
* [EIP 2535: Diamond standard explained – Part 3: Understanding storage patterns in diamonds](https://bitsbyblocks.com/eip-2535-diamond-standard-explained-part-3-understanding-storage-patterns-in-diamonds/)
* [The Diamond Standard (EIP-2535) Explained: Part 1](https://www.quicknode.com/guides/smart-contract-development/the-diamond-standard-eip-2535-explained-part-1)
* [ The Diamond Standard (EIP-2535) Explained: Part 2](https://www.quicknode.com/guides/smart-contract-development/the-diamond-standard-eip-2535-explained-part-2)
* [A better way to initialize upgradeable contracts](https://medium.com/@gweiworld/a-new-better-way-to-initialize-upgradeable-contracts-39080d72f066) - Shows how to execute initialization functions during diamond upgrades.
* [An Introduction to ERC2535 Diamonds Development And Why Solidity Devs Should Adopt It](https://proggr.hashnode.dev/ooo-shiny-an-introduction-to-erc2535-diamonds-development-and-why-solidity-devs-should-adopt-it)
* [Transforming web3 through a Diamond Management System](https://medium.com/@alexeluca.spataru/transforming-web3-through-a-diamond-management-system-d2efa560ea7f)
* [Achieving Universal and Reusable Smart Contracts via ERC2535 Diamond Proxy Standard](https://medium.com/@alexeluca.spataru/achieving-universal-and-reusable-smart-contracts-via-erc2535-diamond-proxy-standard-ba4c9f5ac5bc)
* [A guide to building and deploying upgradeable contracts on CELO with Diamond standard](https://docs.celo.org/blog/tutorials/a-guide-to-building-and-deploying-upgradeable-contracts-on-celo-with-diamond-standard)

### Diamond Storage

* [How Diamond Storage Works](https://dev.to/mudgen/how-diamond-storage-works-90e) - Explains diamond storage and shows an example.
* [New Storage Layout For Proxy Contracts and Diamonds](https://medium.com/1milliondevs/new-storage-layout-for-proxy-contracts-and-diamonds-98d01d0eadb) - First written article that describes diamond storage.
* [AppStorage Pattern for State Variables in Solidity](https://eip2535diamonds.substack.com/p/appstorage-pattern-for-state-variables?s=w) - Describes and shows AppStorage.
* [Rules for Upgrading Diamond Storage](https://eip2535diamonds.substack.com/p/diamond-upgrades) - Best documentation about upgrading Diamond Storage.
* [Migrating the EIP-2535 Diamond Storage layout](https://medium.com/@0xFluffyBeard/migrating-the-eip-2535-diamond-storage-layout-cb28b9c47e71) - Shows Diamond Storage and how to migrate data to new Diamond Storage in upgrades.

### Diamond Upgrades

* [Diamond Upgrades](https://eip2535diamonds.substack.com/p/diamond-upgrades?s=w) - How to perform diamond upgrades.
* [Example of Adding New State Variables in Diamond Upgrade](https://eip2535diamonds.substack.com/p/example-of-a-diamond-upgrade?s=w) - Shows how to add new state variables to a diamond.
* [A better way to initialize upgradeable contracts](https://medium.com/@gweiworld/a-new-better-way-to-initialize-upgradeable-contracts-39080d72f066) - Shows how to execute initialization functions during diamond upgrades.
* [Upgradeable Smart Contracts and Initialization](https://medium.com/@gweiworld/upgradeable-smart-contracts-and-initialization-6374fd3df267) - Compares methods of initializing upgrades.

### Diamonds in Projects
* [🌱 Beanstalk 🤝 EIP-2535 💎](https://bean.money/blog/beanstalk-eip-2535) - Lays out benefits of EIP-2535 with examples from their project.
* [Smart Contracts as Apps](https://0xhabitat.substack.com/p/33) - EIP-2535 Diamonds and the feasibility of a DAO Operating System
* [Dark Forest & the Diamond Standard](https://blog.zkga.me/dark-forest-and-the-diamond-standard) - Dark Forest project moves to and dicusses diamonds.
* [The Diamond Standard: A new paradigm for upgradeability](https://medium.com/derivadex/the-diamond-standard-a-new-paradigm-for-upgradeability-569121a08954) - DerivaDEX on diamonds.
* [We like the (EIP-2535) Diamonds](https://blog.premia.finance/we-like-the-eip-2535-diamonds-90184b2e6741) - Premia Finance talks about their use of diamonds.
* [Why Gotchivault is upgrading to the Diamond standard](https://medium.com/@bearded.eth/diamonds-are-a-proxys-best-friends-c302cca82203) - How to upgrade an existing proxy contract to EIP2535 Diamonds.
* [Handling multiple tokens, with a modern solidity architecture via Diamonds & ERC1155](https://dev.to/nohehf/handling-multiple-tokens-with-a-modern-solidity-architecture-via-diamonds-erc1155-1h7e)
* [Smart contract packages — upgradeability for normal people](https://medium.com/@tjvs/smart-contract-packages-upgradeability-for-normal-people-8646e817e196)

#### Diamond Project Documentation
* [Aavegotchi Smart Contract Documentation](https://docs.aavegotchi.com/)
* [LIFI Overview](https://docs.li.fi/smart-contracts/overview)
* [Geo Web Documentation](https://docs.geoweb.network/developers/core-contracts)

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
* [diamond-hardhat](https://github.com/proggR/diamond-hardhat) - Extension that adds deeper Hardhat integrations for faster/more maintainable ERC2535 Diamond contract development.
* [OpenZeppelin Diamonds](https://github.com/GeniusVentures/openzeppelin-contracts-diamond) - OpenZeppelin contracts transpiled to use Diamonds & Facets

# Tools

* [Louper - The Ethereum Diamond Inspector](https://louper.dev/) - User interface for diamonds.
* [Governance Diamonds](https://www.dmath.is/governance-diamonds/) - User interface for exploring diamonds.
* [hardhat-diamond-abi](https://github.com/projectsophon/hardhat-diamond-abi) - Hardhat plugin to combine multiple ABIs into a Diamond ABI artifact.
* [hardhat-deploy](https://github.com/wighawag/hardhat-deploy#builtin-in-support-for-diamonds-eip2535) - Hardhat plugin that supports deploying, upgrading and managing diamonds.
* [Inspector Facet](https://github.com/bugout-dev/inspector-facet) - Inspection utility for EIP2535 Diamond proxies. Written in Python.
* [Zem](https://github.com/anders-torbjornsen/zem) - Hardhat deployment management system that supports deploying, upgrading and managing diamonds.
* [diamond-foundry][https://github.com/Forgenie/diamond-foundry] - A modern framework for creating EIP2535 Diamonds
* [Foundry-Hardhat-Diamonds](https://github.com/Timidan/Foundry-Hardhat-Diamonds) - Mimimal template for Diamonds
* [foundry-diamond-deploy](https://github.com/xenoliss/foundry-diamond-deploy) - Minimal example of a Diamond deployment script using foundry.
* [Diamond-Foundry](https://github.com/FydeTreasury/Diamond-Foundry) - Foundry version of Diamond Pattern (EIP-2535) reference implementation.
* [0xpm](https://0xpm.app/) - Diamond-based smart contract package manager.
* [diamond-etherscan](https://github.com/zdenham/diamond-etherscan) - Make your EIP-2535 Diamond etherscan compatible.
* [Diamantair](https://diamantaire.xyz/) -  Deploying new diamonds from a template.
* [diamond-diff](https://www.npmjs.com/package/diamond-diff) - Tool that helps retrieve the necessary `diamondCut` by checking against a Diamond model.
* [Ethereum Package Manager](https://epm.wtf) - GUI to deploy and upgrade Diamond proxies and facets. Granular facet control with ability to toggle facet functions on/off.
* [OpenZeppelin Transpiler for Diamonds](https://github.com/GeniusVentures/openzeppelin-transpiler) - Updated OpenZeppelin Transpiler supporting Diamond patter with significant speed improvements
* [How to use TypeScript with EIP-2535: Diamonds](https://dev.to/erhant/how-to-use-typescript-with-eip-2535-diamonds-3gl6)

# Security Audits

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
2. BarnBridge
3. Aavegotchi
4. [ERC721A-Upgradeable](https://github.com/chiru-labs/ERC721A-Upgradeable)
5. PieDAO
6. Boson Protocol
7. hardhat-deploy
8. Nifty Cannon
9. AllianceBlock
10. Louper
11. solidstate-solidity
12. Nayms
13. Diamond Setter
14. Sherlock
15. Premia Finance
16. Nocturnal Finance
17. scaffold-eth
18. diamond-starter-kit
19. scaffold-eth-diamond-standard
20. Sanshu Inu
21. Gelato Network
22. Teller Finance
23. seen.haus
24. thx.network
25. Token Gallery
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
37. [GNUS.AI](https://www.gnus.ai)
38. Dark Forest
39. Moonstream DAO
40. Chain of Empires
41. LI.FI
42. cryptopoopz.com
43. [Copium Wars](https://copiumwars.xyz/)
44. Typenauts
46. connext.network
47. [The Saudis](https://www.thesaudisnft.com/)
48. [Spring Game](https://spring.game/)
49. [oncyber](https://oncyber.io/)
50. [Avathereum](https://avathereum.com/)
51. [Cartesi](https://cartesi.io/)
52. [Energy Web](https://www.energyweb.org)
53. [Shattered Eon](https://shatteredeon.io/)
54. Zem
55. [SolarProtocol](https://www.solarprotocol.io/)
56. [VOID.MONEY](https://void.money/)
58. [Simple DeFi](https://www.simpledefi.io/)
59. [CroSwap](https://www.croswap.com/)
60. [Lightm](https://lightm.xyz)
61. [PartyFinance](https://party.finance/)
62. [1o1.art](https://1o1.art/)
63. [withmantra.com](https://withmantra.com)
64. [Nobility Token](https://nobilitytoken.com)
65. [meTokens](https://meTokens.com)
66. [Fyde Treasury Protocol](https://www.fyde.fi)
67. [VaporFi](https://vapornodes.finance/)
68. [MetaMask Grants DAO](https://metamaskgrants.org/)
69. [zkSync](https://zksync.io/)
70. [Crypto Unicorns](https://www.cryptounicorns.fun/)
71. [Forward Protocol](https://forwardprotocol.io/)
1. [Ubiquity Dollar](https://github.com/ubiquity/ubiquity-dollar)
1. [Geo Web](https://www.geoweb.network/)
1. [Nexera ID](https://blog.allianceblock.io/nexera-nexera-id-deep-dive-ea58350686f3)
1.  [CronosNode NFTs](https://cronosnode.com/)
1. [Tombala Games](https://tombala.games/)
1. [Perp88](https://medium.com/perp88/perp88-has-adopted-the-diamond-standard-eip-2535-fcc60f49ece1)
1. [Helix2](https://ethresear.ch/t/helix2-name-link-service/14823)
1. [Pendle](https://www.pendle.finance/)
1. [Worker Node Toolkit](https://medium.com/energy-web-insights/proof-of-good-work-energy-web-releases-worker-node-toolkit-to-the-public-e67a9d8a2973)
1. [NiftyKit](https://niftykit.com/)
2. [Babylon](https://babylon.game/)
1. [Autify Network](https://autifynetwork.com/)
