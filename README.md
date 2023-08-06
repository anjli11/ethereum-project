# ethereum-project

# MyToken - ERC20-like Token Contract

## Description
This is a simple ERC20-like token contract called "HAND" with the abbreviation "HD". It allows users to mint and burn tokens, and it keeps track of the total supply and individual balances.

## Public Variables
- Token Name: HAND
- Token Abbreviation: HD
- Total Supply: 0 (initial value)

## Mint Function
Function Name: mint
Parameters: `_address` (address to mint tokens for), `_value` (amount of tokens to mint)
Description: This function increases the total supply by `_value` and increases the balance of the specified `_address` by that amount.

## Burn Function
Function Name: burn
Parameters: `_address` (address to burn tokens from), `_value` (amount of tokens to burn)
Description: This function reduces the total supply by `_value` and deducts that amount from the balance of the specified `_address`. It includes a check to ensure that the balance of the `_address` is greater than or equal to the amount to be burned.

## License
SPDX-License-Identifier: MIT
