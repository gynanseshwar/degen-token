# DegenToken

DegenToken is an ERC-20 token contract written in Solidity that includes additional functionalities for minting, transferring, burning tokens, and managing equipment redemptions.

## Overview

This token contract includes the following features:

- **Minting:** The contract owner can mint new tokens and distribute them to specific addresses.

- **Transferring:** Token holders can transfer their tokens to other addresses.

- **Burning:** Token holders can burn their tokens, reducing the total supply.

- **Equipment Management:** The contract owner can set equipment costs and totals, redeem equipment, and remove equipment from the system.

## Equipment Management

The contract allows the owner to manage various types of equipment, each defined by a unique name. Each equipment type has an associated cost and a total supply. Users can redeem equipment by burning the required amount of tokens.

## Usage

### Deployment

1. Deploy the contract to the Ethereum blockchain.
2. The contract owner initially receives the "DEGEN" tokens.

### Minting Tokens

- Use the `mintTokens` function to mint tokens and distribute them to a specified address.

### Transferring Tokens

- Use the `transferTokens` function to transfer tokens from one address to another.

### Burning Tokens

- Use the `burnTokens` function to burn a specific amount of tokens, reducing the total supply.

### Equipment Management

- Use the `setEquipmentCostsAndTotals` function to set the cost and total supply of a specific type of equipment.

- Use the `redeemEquipment` function to redeem a specific type of equipment by burning the required amount of tokens.

- Use the `removeEquipment` function to remove a specific type of equipment from the system.

## Example

Here's a simple example of using the contract in a JavaScript environment:

```javascript
// Deploy the contract and get the contract instance

// Mint tokens to a specific address

// Transfer tokens to another address

// Burn a specific amount of tokens

// Set equipment costs and totals

// Redeem equipment by burning tokens

// Remove equipment from the system

```
##  Author

Gynaneshwar

dino8oss55@gmail.com
