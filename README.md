# Simple NFT for Base Network (Remix)

This repository contains a minimal NFT (ERC721-like) smart contract deployable on the Base network via Remix IDE.

## Steps to Deploy

1. Open Remix IDE: [https://remix.ethereum.org](https://remix.ethereum.org)
2. Create a new file `MyNFT.sol` and paste the contract code from `contracts/MyNFT.sol`.
3. Compile the contract using Solidity compiler ^0.8.30.
4. Connect MetaMask to the **Base network** (mainnet or testnet).
5. Deploy the contract.
6. Use the following functions to interact:
   - `mint(to, "ipfs://...")` → mint new NFTs.
   - `balanceOf(address)` → check wallet balance.
   - `ownerOf(tokenId)` → get owner of specific token.
   - `transferFrom(from, to, tokenId)` → transfer NFT to another address.

## Example Token URI
Use IPFS or HTTP links, for example:
ipfs://ILoveYouMoreThanAnything/myimage.png
