# Web3 projects
Below is a list of my Web3 projects, demonstrating how decentralized technologies, smart contracts, and integrations with leading DeFi protocols can work together. Each project includes source code, an overview, and details about the tech stack—showing how to build secure, transparent, and scalable decentralized applications with modern Web3 development tools.

## AMM DEX (Automated Market Maker Decentralized Exchange)
The AMM DEX is a Uniswap V3-inspired decentralized exchange platform that enables efficient token swapping and concentrated liquidity provision. The platform features advanced AMM functionality with concentrated liquidity within custom price ranges, customizable fee tiers, NFT position tracking, ERC-4626 tokenized vaults for flexible liquidity provision, and a DAO-based governance system for protocol parameters and upgrades. The protocol utilizes upgradeable smart contracts to enable future improvements while maintaining security through timelock and multi-signature requirements.

**Technologies:** Solidity, OpenZeppelin, Hardhat, JavaScript, Chai, Mocha

#### Source code:
https://github.com/v7m/amm-dex (Hardhat)

## Decentralized Exchange DAO
The Decentralized Exchange DAO is a decentralized finance platform that supports a range of services including ETH staking for governance tokens (ERC20), token swapping via Uniswap, interactions with Aave Protocol, liquidity provision with NFT (ERC721) rewards. The project focused on ETH, DAI, USDT and features user-centric options like deposits, withdrawals, and emphasizes decentralized governance through DAO, allowing token holders to participate in decision-making.

**Technologies:** Solidity, OpenZeppelin, Aave and Uniswap integration, Hardhat, JavaScript, Ethers.js, Chai, Mocha

#### Source code:
https://github.com/v7m/defi-exchange-dao-hardhat (Hardhat)


## NFT Marketplace
The NFT Marketplace decentralized applications (DApp) offers compatibility with multiple Web3 wallets and supports trading of diverse NFT types (ERC721), including Basic (IPFS hosted) and Dynamic SVG (on-chain storage). It enables users to buy, sell, mint, and manage NFTs with ease, offering complete control over pricing, listings, and earnings.

**Technologies:** Solidity, OpenZeppelin, Chainlink VRF, Hardhat, JavaScript, Ethers.js, Next.js, Moralis, The Graph, IPFS, Chai, Mocha

#### Source code:
https://github.com/v7m/nft-marketplace-hardhat (Hardhat) \
https://github.com/v7m/nft-marketplace-nextjs (Next.js) \
https://github.com/v7m/nft-marketplace-graph (The Graph)


## Decentralized Lottery
Smart contract-based decentralized lottery offers features like dynamic player participation, automated winner calculation, and direct control over lottery states, enhancing the transparency and fairness of endless online lotteries. This project leverages Chainlink's Automation along with Chainlink's VRF (Verifiable Random Function) for secure, random winner selection in a decentralized lottery system.

**Technologies:** Solidity, Chainlink VRF, Chainlink Automation, Hardhat, JavaScript, Ethers.js, Next.js, Moralis, IPFS, Chai, Mocha

#### Source code:
https://github.com/v7m/decentralized-lottery-hardhat (Hardhat) \
https://github.com/v7m/decentralized-lottery-nextjs (Next.js)
