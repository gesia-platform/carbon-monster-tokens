# Voucher1155Nft Smart Contract

## 📖 Overview

The Voucher1155Nft Smart Contract is a versatile blockchain-based platform for issuing and managing voucher NFTs (Non-Fungible Tokens). Deployed on the Gesia network, this contract allows for the creation, sale, and transfer of voucher NFTs in a secure and decentralized manner. It integrates with OpenZeppelin libraries and other external interfaces for enhanced functionality.

## ✨ Features

Minting and Managing Voucher NFTs (Owner Only): Enables the contract owner to mint new voucher NFTs and manage their properties.

Transfer By Signature (Owner Only): Facilitates secure transfers of NFTs via digital signatures, ensuring authenticated transactions.

Voucher NFT Pricing and Metadata Management: Allows for setting and updating the prices and metadata of voucher NFTs.

```
Core Functions:
- mintByOperator()
- mintBySignature()
- transferBySignature()
- getCarbonPrice()
```

## 🚀 Smart Contract Deployment Information

The Voucher1155Nft Contract has been deployed on the Gesia network. Below are the deployment details:

Contract Address: [0x25F9f93Eb7c6Cc878b93E7a8a4cE95100bA01DE0](https://explorer.gesia.io/address/0x25F9f93Eb7c6Cc878b93E7a8a4cE95100bA01DE0)

Transaction Hash: [0x256d1997037210647073c995441279719fb8e8249412b1ae7207c246bb045687](https://explorer.gesia.io/tx/0x256d1997037210647073c995441279719fb8e8249412b1ae7207c246bb045687)

You can verify the deployment by checking the contract address and transaction hash on [Gesiascan](https://explorer.gesia.io/).

## 📝 How It Works?

Minting NFTs: The contract owner can mint new NFTs, specifying their attributes and metadata.

Transferring NFTs: Secure transfer of NFTs between addresses using digital signatures.

Setting Prices: The contract allows for setting and updating the carbon price of each NFT.

## 🛠️ Integrations

OpenZeppelin Libraries: SafeMath, Counters, ERC1155, ReentrancyGuard, etc.

IPrice Interface: For managing NFT pricing.

IFeeManager Interface: For handling fee calculations.

# Carbon1155Nft Smart Contract

## 📖 Overview

The Carbon1155Nft Smart Contract is a blockchain-based platform designed for managing and trading carbon credit tokens in the form of ERC1155 NFTs. This contract, deployed on the Gesia network, allows users to mint, transfer, and manage carbon credits securely and efficiently. It leverages OpenZeppelin libraries and integrates with various interfaces such as IOperator, IFeeManager, and IPrice for enhanced functionality.

## ✨ Features

Minting Carbon Credits (Operators Only): Operators can mint new carbon credit tokens, specifying the amount and metadata, while ensuring compliance with environmental standards.

Secure Transfer Mechanisms: Includes features for transferring tokens with signature verification, ensuring secure and authenticated transactions.

Carbon Pricing and Weight Management: Allows operators to set and update carbon prices and weights for each token.

```
Core Functions:
- mint()
- transferWithSignature()
- transferWithGift()
- getCarbonPrice()
- tokenWeight()
```

## 🚀 Smart Contract Deployment Information

The Carbon1155Nft contract has been deployed on the Gesia network. Below are the deployment details:

Contract Address: [0xE66e31924F5e2Af659fCdDBfB390F70F5773bc81](https://explorer.gesia.io/address/0xE66e31924F5e2Af659fCdDBfB390F70F5773bc81)

Transaction Hash: [0x93c9443c5e9b14d7e27e67ab944ee0da749f465f991165e3cc4d8f5fbf81b96a](https://explorer.gesia.io/tx/0x93c9443c5e9b14d7e27e67ab944ee0da749f465f991165e3cc4d8f5fbf81b96a)

You can verify the deployment by checking the contract address and transaction hash on [Gesiascan](https://explorer.gesia.io/).

## 📝 How It Works?

Minting Carbon Credits: Operators mint new tokens by specifying the carbon amount, price, and metadata.

Transferring Tokens: Secure transfer of tokens is facilitated either by operator intervention or by using digital signatures for authenticated transactions.

Managing Carbon Prices and Weights: Operators can update the pricing and weight of each carbon credit token to reflect current market values and environmental impact.

## 🛠️ Integrations

OpenZeppelin Libraries: SafeMath, Counters, ERC1155, ReentrancyGuard, etc.

IPrice Interface: For managing token pricing.

IFeeManager Interface: For handling transaction fees.

## 📄 License

This project is unlicensed and is available for use and modification without restrictions.
