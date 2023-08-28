# Custom Token Contract

This Solidity program implements a custom token contract with minting and burning functionality. It allows you to create and manage your own token on the Ethereum blockchain.

## Description

This contract is designed to create and manage custom tokens on the Ethereum blockchain. It provides functions to mint (create) and burn (destroy) tokens. The contract keeps track of token balances for each address and maintains the total supply of tokens.

## Getting Started

### Prerequisites

To interact with this contract, you'll need an Ethereum wallet or a development environment such as Remix.

### Deployment

1. Deploy the Contract:
   - Open Remix (https://remix.ethereum.org/).
   - Create a new Solidity file (e.g., `MyToken.sol`) and paste the contract code into it.
   - Make sure the Solidity compiler version is set to 0.8.0.
   - Compile the contract.
   - Deploy the contract using an Ethereum wallet or Remix's Deploy & Run Transactions tab.

2. Interact with the Contract:
   - Once the contract is deployed, you can interact with it using the provided functions.

## Token Contract Functions

### `mintTokens(address recipient, uint256 value)`

Mints (creates) `value` tokens and adds them to the `recipient`'s balance. Only the contract owner can call this function.

### `burnTokens(address account, uint256 value)`

Burns (destroys) `value` tokens from the `account`'s balance. Only the contract owner can call this function.

## Contract Owner

The contract owner has special privileges and can mint and burn tokens. The owner's address is set during contract deployment.

## Example Workflow

1. Deploy the contract to the Ethereum blockchain.
2. The contract owner can use the `mintTokens` function to create new tokens for specific addresses.
3. The contract owner can use the `burnTokens` function to destroy tokens from an address's balance.

## Authors

Ariyan Paul

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
