# blockasikasik4

# AI Model Marketplace

Welcome to the AI Model Marketplace! This project is a decentralized application (dApp) that allows users to list, buy, and sell AI models using blockchain technology.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Smart Contracts](#smart-contracts)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Overview

The AI Model Marketplace is built using Ethereum smart contracts and interacts with the blockchain through a web interface. Users can connect their MetaMask wallets, check their token balances, list AI models for sale, and purchase available models using AI-Tokens.

## Features

- Connect to MetaMask wallet
- Display token balance
- List new AI models for sale
- Purchase AI models with AI-Tokens
- Secure and transparent transactions on the Ethereum blockchain

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/ai-model-marketplace.git
    cd ai-model-marketplace
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Compile the smart contracts:**
    ```bash
    npx hardhat compile
    ```

4. **Deploy the smart contracts:**
    ```bash
    npx hardhat run scripts/deploy.js --network <network-name>
    ```

5. **Start the development server:**
    ```bash
    npm start
    ```

## Usage

1. **Connect MetaMask:**
    - Open the application in your browser.
    - Click on the "Connect Wallet" button to connect your MetaMask wallet.

2. **Display Token Balance:**
    - Your token balance will be displayed once the wallet is connected.
    - Click on the "Refresh Balance" button to update your balance.

3. **List a New AI Model:**
    - Fill in the model name, description, and price in AI-Tokens.
    - Click on the "List Model" button to list your AI model for sale.

4. **Purchase an AI Model:**
    - Browse the available models in the "Available Models" section.
    - Click on the "Buy" button to purchase a model using AI-Tokens.

## Smart Contracts

The project includes two main smart contracts:

1. **AITU_SE2315_Token.sol:** An ERC20 token contract used for AI-Tokens.
2. **AIModelMarketplace.sol:** A marketplace contract for listing and purchasing AI models.

The smart contracts are located in the `contracts` directory.

## Testing

To run the tests for the smart contracts, use the following command:

```bash
npx hardhat test
