# NFT-Deposite

## Project Overview
This guide provides detailed instructions on deploying an NFT collection on the Ethereum blockchain, mapping the collection to the Polygon network, and transferring assets via the Polygon Bridge. Additionally, we will utilize an image generation tool like DALLE 2 or Midjourney to create images for the NFTs.

## Tools Used
- Hardhat
- Foundry (optional)
- IPFS for storing items
- Pinata.cloud for IPFS pinning

## Project Rubric
To successfully complete the Final Challenge, your project should meet the following criteria:

1. Generate a 5-item collection using DALLE 2 or Midjourney.
2. Store items on IPFS using pinata.cloud.
3. Deploy an ERC721 or ERC1155 contract to the Goerli Ethereum Testnet.
4. Implement a promptDescription function on the contract that returns the prompt used to generate the images.
5. Map the NFT Collection using the Polygon network token mapper (optional but recommended for visualization).
6. Write a Hardhat script to batch mint all NFTs (Hint: ERC721A is optimal here).
7. Write a Hardhat script to batch transfer all NFTs from Ethereum to Polygon Mumbai using the FxPortal Bridge.
8. Approve the NFTs to be transferred.
9. Deposit the NFTs to the Bridge.
10. Test balanceOf on the Mumbai test net.
11. Write a README file.

## Step-by-Step Deployment Guide

### 1. Generate NFT Collection
Use DALLE 2 or Midjourney to generate a 5-item NFT collection.

### 2. Store Items on IPFS
Upload the generated NFT images to IPFS using pinata.cloud.

### 3. Deploy Contract to Goerli Testnet
Deploy an ERC721 or ERC1155 contract to the Goerli Ethereum Testnet. Ensure that the contract includes a promptDescription function to return the prompt used for image generation.

### 4. Map NFT Collection to Polygon
Map the NFT Collection using the Polygon network token mapper.

### 5. Write Hardhat Scripts
- Write a Hardhat script to batch mint all NFTs. Consider using ERC721A for optimal efficiency.
- Write a Hardhat script to batch transfer all NFTs from Ethereum to Polygon Mumbai using the FxPortal Bridge.

### 6. Approve and Deposit NFTs
- Approve the NFTs to be transferred.
- Deposit the NFTs to the Bridge.

### 7. Test BalanceOf on Mumbai Testnet
Ensure that balanceOf functions correctly on the Mumbai test net.
