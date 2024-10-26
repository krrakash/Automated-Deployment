# 🚀 Smart Contract Deployment Automation

This repository provides an automated script for deploying **any Solidity smart contract** using Hardhat. It simplifies the entire process from dependency installation to deployment. You can deploy contracts to any EVM-based blockchain networks with ease. As an example, this project includes a **MultiSig Wallet** contract, which supports ERC20, ERC721, ERC1155 token transfers and Uniswap V3 MATIC-to-WETH swaps.

> **Note:** Currently, this script is tested for **single contract deployments**, but in future iterations, we plan to support deploying **multiple interlinked contracts**.

---

## 🌟 Key Features
- **Deploy Any Solidity Contract**: The script supports deploying any Solidity smart contract, with automatic dependency management.
- **Automatic Dependency Installation**: The script automatically detects and installs imported dependencies from the Solidity contract (e.g., `@openzeppelin`, `@uniswap`).
- **Hardhat Integration**: Automatically installs and configures Hardhat for deployment.
- **Custom Network Support**: Easily configure and deploy to any Ethereum or Polygon network by providing network URL and wallet private key.
- **MultiSig Wallet Example**: Includes a MultiSig wallet that requires multiple confirmations for transactions and Uniswap V3 integration.

---

## 🛠️ Planned Features (Future Development)
In future iterations, this project will evolve to include:
- **Automated Solidity Contract Generation**: Users will be able to provide a simple **text description**, and the system will automatically generate the corresponding Solidity smart contract, including importing the necessary libraries.
- **Multiple Contract Deployments**: In addition to single contract deployment, support for **multiple interlinked contracts** will be added, allowing more complex use cases.

---

## ⚙️ Prerequisites

Make sure you have the following installed:
- [Node.js](https://nodejs.org/) (with npm)
- Any EVM node provider (e.g., [Infura](https://infura.io/) or [Alchemy](https://www.alchemy.com/))
- A funded EVM wallet for contract deployment.

---

## 📦 Installation

### Clone the repository
#### Example: MultiSig Wallet with Uniswap Support
Add the required contracts you want to deploy.
```bash
git clone https://github.com/yourusername/smart-contract-deployment-automation.git
cd smart-contract-deployment-automation
node deploy_wrapper.js <contract_path>
