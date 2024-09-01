# FavourToken Contract

## Summary
FavourToken is an ERC20 token contract implemented in Solidity. It provides basic functionalities such as transferring tokens, burning tokens, and minting new tokens. This contract is designed to offer a simple yet functional token implementation on the Ethereum blockchain.

## Description
FavourToken is a straightforward ERC20 token contract written in Solidity. The contract allows users to transfer tokens, burn their tokens to reduce the overall supply, and mint new tokens (accessible only to the contract owner). This contract serves as a fundamental example for those looking to understand ERC20 token contracts, and it can be extended or used as a foundation for more advanced token projects.

## Getting Started

### Deployment

To deploy the FredToken contract, follow these steps:

1. Deploy the contract with the desired name and symbol.
2. The contract owner can mint new tokens as needed.
3. Users can transfer tokens or burn their own tokens.

### Interacting with the Contract

To interact with the FredToken contract, you can use any Ethereum development environment like [Remix](https://remix.ethereum.org/) or Hardhat.

**Transfer Tokens:**  
Users can transfer tokens to other addresses using the `transfer` function:
```javascript
transfer(address to, uint256 amount)
```
**Burn Tokens:**

Users can burn their tokens to reduce the total supply using the `burn` function:
```javascript
burn(uint256 amount)
```
**Mint Tokens:**

The contract owner can mint new tokens using the `mint` function:
```javascript
mint(address to, uint256 amount)
```
**Author**

Favour Sabo

**License**

This project is licensed under the MIT License - see the LICENSE.md file for details.
