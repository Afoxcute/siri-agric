# EcoCollect

## Project Description

EcoCollect is a decentralized application designed to incentivize individuals and organizations to collect and recycle plastic waste. By rewarding users with tokens for their recycling efforts, EcoCollect aims to promote environmental stewardship and innovation in waste management. The application consists of two main smart contracts: **Recylox** and **Recycle**, which facilitate the locking of rewards and the recycling process, respectively.

## Functionality

- **Recylox**: This contract manages the rewards system, allowing users to lock tokens as incentives for recycling efforts.
- **Recycle**: This contract handles the recycling process, ensuring that collected plastics are processed efficiently and transparently.

## Usage

1. **Collect Plastics**: Users can collect waste plastics in their local communities.
2. **Lock Rewards**: Once collected, users can lock their rewards in the Recylox contract to receive tokens.
3. **Recycle**: The Recycle contract processes the collected plastics and ensures proper recycling practices are followed.

## Installation

To set up the EcoCollect project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git https://github.com/Lukman-01/EcoCollect.git
   cd EcoCollect/Blockend
   ```

2. **Install Dependencies**:
   Make sure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed. Then run:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and add your wallet key and Blockscout API key:
   ```plaintext
   WALLET_KEY=<your-wallet-key>
   BLOCKSCOUT_KEY=<your-blockscout-api-key>
   ```

## Compile

To compile the smart contracts, run:
```bash
npx hardhat compile
```

## Deploy

To deploy the contracts on the Base Sepolia testnet, execute:
```bash
npx hardhat ignition deploy ./ignition/modules/deploy.ts --network base-sepolia
```

## Verify Contracts

After deployment, verify your contracts on the Base Sepolia block explorer with:
```bash
npx hardhat verify --network base-sepolia <deployed address>
```

### Deployed Addresses

Deployed Addresses

**Recylox** - 0xacFfd04f690a7D718A23C07276c2bFCcF2Ee7E7A
**Recycle** - 0xD0BFe7253aB8EdCe6Fb46Eba473e13Ee9336aE82

- **Recylox**: [0xacFfd04f690a7D718A23C07276c2bFCcF2Ee7E7A](https://base-sepolia.blockscout.com/address/0x7042153d890F545E1fACaea4363DA2A861e546fC#code)
- **Recycle**: [0xD0BFe7253aB8EdCe6Fb46Eba473e13Ee9336aE82](https://base-sepolia.blockscout.com/address/0xD0BFe7253aB8EdCe6Fb46Eba473e13Ee9336aE82#code)

Successfully verified contracts:
- [Recylox](https://base-sepolia.blockscout.com/address/0xacFfd04f690a7D718A23C07276c2bFCcF2Ee7E7A#code)
- [Recycle](https://base-sepolia.blockscout.com/address/0xD0BFe7253aB8EdCe6Fb46Eba473e13Ee9336aE82#code)
