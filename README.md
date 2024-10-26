# 🚀 Smart Contract Deployment Automation with Hardhat 
### Example: MultiSig Wallet with Uniswap Support

This repository provides an automated script for deploying **any Solidity smart contract** using Hardhat. It simplifies the entire process from dependency installation to deployment. You can deploy contracts to Ethereum/Polygon networks with ease. As an example, this project includes a **MultiSig Wallet** contract, which supports ERC20, ERC721, ERC1155 token transfers and Uniswap V3 MATIC-to-WETH swaps.

---

## 🌟 Key Features
- **Deploy Any Solidity Contract**: The script supports deploying any Solidity smart contract, with automatic dependency management.
- **MultiSig Wallet Example**: Includes a MultiSig wallet that requires multiple confirmations for transactions and Uniswap V3 integration.
- **Automatic Dependency Installation**: The script automatically detects and installs imported dependencies from the Solidity contract (e.g., `@openzeppelin`, `@uniswap`).
- **Hardhat Integration**: Automatically installs and configures Hardhat for deployment.
- **Custom Network Support**: Easily configure and deploy to any Ethereum or Polygon network by providing network URL and wallet private key.

---

## ⚙️ Prerequisites

Make sure you have the following installed:
- [Node.js](https://nodejs.org/) (with npm)
- An Ethereum or Polygon node provider (e.g., [Infura](https://infura.io/) or [Alchemy](https://www.alchemy.com/))
- A funded Ethereum or Polygon wallet for contract deployment.

---

## 📦 Installation

### Clone the repository
```bash
git clone https://github.com/yourusername/smart-contract-deployment-automation.git
cd smart-contract-deployment-automation
node deploy_script.js <contract_file_path>
