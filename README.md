# Precursor Chemical Tracking Using Blockchain
- **Requirements**:
  - Modern browser (Chrome, Brave, etc.).
  - MetaMask extension on Sepolia testnet.
  - Sepolia test ETH (via faucet).

## Running Locally

1. write code
2. **Install**: `cd Precursor-Chemical-Tracking/front-end && npm install`
3. **Run**: `npm start`
4. **Requirements**:
   - Node.js
   - Git
   - MetaMask on Sepolia with test ETH

## Overview

The **Precursor Chemical Tracking Using Blockchain** project aims to revolutionize the traditional tracking process by leveraging blockchain technology. This decentralized solution ensures transparency, immutability, and security in property transactions, addressing issues like inefficiency, fraud, and ownership disputes.

## Features

- **Decentralized Records**: Transactions and ownership details are stored securely on a blockchain, ensuring transparency and reducing the risk of tampering.
- **Smart Contracts**: Automates and verifies chemical transfers, reducing the need for intermediaries.
- **Immutable Ledger**: Ensures all transaction records are tamper-proof.
- **User-Friendly Interface**: Simplifies interaction for chemical owners, buyers, and government officials.
- **Enhanced Security**: Data encryption and blockchain technology ensure secure transactions.

## Benefits

- Eliminates fraudulent activities in chemical registration.
- Reduces delays and paperwork in transactions.
- Provides a transparent and easily accessible history of precursor chemical ownership.
- Enhances trust among stakeholders by using a decentralized ledger.

## Technologies Used

- Blockchain: **Ethereum**
- Front-end: **React.js, Bootstrap, CSS**
- Back-end: **Solidity, Node.js, Web3.js**
- Framework: **Truffle, Ganache, Alchemy (for API)**
- Wallet: **Metamask**

## Project Structure

```
Precursor-Chemical-Tracking/
├── contracts/
│   └── Precursor.sol
├── front-end/
│   ├── src/
│   │   ├── components/
│   │   │   ├── AboutPage.js
│   │   │   ├── AdminPanel.js
│   │   │   ├── ContactPage.js
│   │   │   ├── FeaturesPage.js
│   │   │   ├── Footer.js
│   │   │   ├── LandingPage.js
│   │   │   ├── ManageLandPage.js
│   │   │   ├── Navbar.js
│   │   │   └── WalletContext.js
│   │   ├── contracts/
│   │   ├── App.js
│   │   ├── index.js
│   │   └── styles.css
│   └── package.json
├── migrations/
│   └── 2_deploy_contract.js
├── package.json
└── truffle-config.js
```

## Future Enhancements

- Large-scale implementation for testing with real-world data.
- Support for additional blockchain platforms.
- Mobile application for easier access.


