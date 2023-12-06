# FashionToken Smart Contract

## Overview

The FashionToken smart contract is an Ethereum ERC20 token that allows users to engage in fashion-related transactions and redemptions. It facilitates the creation, transfer, and burning of tokens, allowing users to exchange tokens for various fashion items based on predefined rates.

## Features

### ERC20 Compliance

FashionToken is built on the ERC20 standard, ensuring compatibility with wallets, exchanges, and other platforms that support ERC20 tokens.

### Token Minting and Burning

The contract owner can mint new tokens and burn existing tokens using designated functions, managing the token supply as needed.

### Fashion Redemption

Users can redeem their tokens for fashion items such as shirts, pants, shoes, and blazers. Each item has a predefined token value, and users can exchange their tokens for these items by using the `redeemForFashion` function.

### Customization

The contract owner has the authority to set or modify prices for individual fashion items using the `setItemPrices` function, providing flexibility in adjusting token values for different fashion products.

## Contract Functions

- `setPrices`: Initializes the predefined token values for each fashion item.
- `setItemPrices`: Allows the contract owner to set or modify the token values for specific fashion items.
- `mintTokens`: Enables the contract owner to mint new tokens and allocate them to a designated beneficiary.
- `transferTokens`: Allows users to transfer tokens to another address.
- `burnTokens`: Enables users to burn a specific amount of their tokens, reducing the total supply.
- `redeemForFashion`: Allows users to exchange their tokens for fashion items based on their token value.
- `getBalance`: Retrieves the token balance of the caller.
- `getRecentlyRedeemedClothing`: Retrieves the type of clothing recently redeemed by a user.

## Getting Started

To deploy the FashionToken contract, follow these steps:

1. Compile the Solidity code using a compatible compiler version (e.g., Solidity 0.8.0).
2. Deploy the compiled contract to an Avalanche Fuji Testnet network  Remix
3. Interact with the deployed contract using metamask

## Author

Faizan kkhan

rehan786khan2011@gmail.com


