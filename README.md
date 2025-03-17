# NFT Art Marketplace

## Project Title
NFT Art Marketplace

## Project Description 
Create a platform to buy, sell, and auction digital art as NFTs.

## Features
- **Decentralized Marketplace:** Buy, sell, and auction NFTs in a secure and transparent manner.
- **Smart Contract Automation:** Ensures trustless and tamper-proof transactions.
- **Blockchain Security:** Immutable records of ownership and transactions.
- **User-Friendly Interface:** Simplified interaction for artists and buyers.

## Smart Contract
The smart contract is developed using Solidity and provides functionalities to retrieve the project title and description.

### Smart Contract Code
```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.9;

contract NFTArtMarketplace {
    string public projectTitle = "NFT Art Marketplace";
    string public projectDescription = "Create a platform to buy, sell, and auction digital art as NFTs.";

    function getProjectTitle() public view returns (string memory) {
        return projectTitle;
    }

    function getProjectDescription() public view returns (string memory) {
        return projectDescription;
    }
}
```

## How to Use
1. Deploy the smart contract on an Ethereum-compatible blockchain.
2. Interact with `getProjectTitle` and `getProjectDescription` functions to retrieve information.
3. Extend the contract with additional functionalities like NFT minting and trading.

## Future Enhancements
- Integration of NFT minting and transfer capabilities.
- Implementation of royalty distribution for artists.
- Multi-chain compatibility for broader adoption.

This smart contract is the foundation for a fully decentralized NFT Art Marketplace. 🚀

Contract Address:0xc7C69F02dac51eC89Ecda7a766eb6A6f56232cD


