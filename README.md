# Web3 Development Portfolio
Below is a list of Web3 projects, demonstrating how decentralized technologies, smart contracts, and integrations with leading DeFi protocols can work together across different blockchain networks and programming languages. Each project includes source code, an overview, and details about the tech stack — showing how to build secure, transparent, and scalable decentralized applications with modern Web3 development tools and showcasing experience with various blockchain ecosystems.

</br>

## Production Projects

### 1. Alfa APY (Yield Optimization Protocol) – `ICP`
- https://github.com/alfa-codes/alfa-apy-icp-canisters (Backend - Rust)
- https://github.com/alfa-codes/alfa-apy-frontend (Frontend - TypeScript/React)

**Technologies:** Rust, Internet Computer Protocol (ICP), ICRC-1/ICRC-2, TypeScript, React

**Description:** The AlfaAPY is the first yield optimization DeFi protocol built on the Internet Computer Protocol (ICP). The protocol automatically maximizes returns for users by finding the highest-yielding liquidity pools and dynamically reallocating assets to optimize yield. Users can invest in various strategies including conservative, stable, and aggressive approaches, with automatic rebalancing calculated through multiple factors and parameters including market conditions, risk tolerance, and yield opportunities. The protocol consists of multiple canisters and integrates with various DeFi providers like KongSwap, ICPSwap, and others, automatically rebalancing funds when higher-yielding opportunities are detected. The project is actively developed and has attracted multiple grants for continued innovation and expansion to support multiple blockchain networks.

</br>

## Research and Personal Projects

### 2. AMM DEX (Automated Market Maker Decentralized Exchange) – `Ethereum`
- https://github.com/v7m/amm-dex (Smart Contracts - Solidity/Hardhat)

**Technologies:** Solidity, OpenZeppelin, Hardhat, JavaScript

**Description:** The AMM DEX is a Uniswap V3-inspired decentralized exchange platform that enables efficient token swapping and concentrated liquidity provision. The platform features advanced AMM functionality with concentrated liquidity within custom price ranges, customizable fee tiers, NFT position tracking, ERC-4626 tokenized vaults for flexible liquidity provision, and a DAO-based governance system for protocol parameters and upgrades. The protocol utilizes upgradeable smart contracts to enable future improvements while maintaining security through timelock and multi-signature requirements.


### 3. Decentralized Exchange DAO (DAO-controlled vault) – `Ethereum`
- https://github.com/v7m/defi-exchange-dao-hardhat (Smart Contracts - Solidity/Hardhat)

**Technologies:** Solidity, OpenZeppelin, 3rd party integration (Aave, Uniswap), Hardhat, JavaScript, Ethers.js

**Description:** The Decentralized Exchange DAO is a decentralized finance platform that supports a range of services including ETH staking for governance tokens (ERC20), token swapping via Uniswap, interactions with Aave Protocol, liquidity provision with NFT (ERC721) rewards. The project focused on ETH, DAI, USDT and features user-centric options like deposits, withdrawals, and emphasizes decentralized governance through DAO, allowing token holders to participate in decision-making.


### 4. NFT Marketplace (ERC721 Trading Platform) – `Ethereum`
- https://github.com/v7m/nft-marketplace-hardhat (Smart Contracts - Solidity/Hardhat)
- https://github.com/v7m/nft-marketplace-nextjs (Frontend - JavaScript/Next.js)
- https://github.com/v7m/nft-marketplace-graph (Subgraph - JavaScript/The Graph)

**Technologies:** Solidity, OpenZeppelin, Chainlink VRF, Hardhat, JavaScript, Ethers.js, Next.js, Moralis, The Graph, IPFS

**Description:** The NFT Marketplace decentralized applications (DApp) offers compatibility with multiple Web3 wallets and supports trading of diverse NFT types (ERC721), including Basic (IPFS hosted) and Dynamic SVG (on-chain storage). It enables users to buy, sell, mint, and manage NFTs with ease, offering complete control over pricing, listings, and earnings.


### 5. Decentralized Lottery (Chainlink VRF-based) – `Ethereum`
- https://github.com/v7m/decentralized-lottery-hardhat (Smart Contracts - Solidity/Hardhat)
- https://github.com/v7m/decentralized-lottery-nextjs (Frontend - JavaScript/Next.js)

**Technologies:** Solidity, Chainlink VRF, Chainlink Automation, Hardhat, JavaScript, Ethers.js, Next.js, Moralis, IPFS

**Description:** Smart contract-based decentralized lottery offers features like dynamic player participation, automated winner calculation, and direct control over lottery states, enhancing the transparency and fairness of endless online lotteries. This project leverages Chainlink's Automation along with Chainlink's VRF (Verifiable Random Function) for secure, random winner selection in a decentralized lottery system.
