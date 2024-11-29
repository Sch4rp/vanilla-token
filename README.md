# VanillaToken

A basic ERC-20 compliant token implementation on the Ethereum blockchain.

## Features

- Standard ERC-20 functionality
- Mintable tokens (owner only)
- Burnable tokens
- Owner management
- 18 decimal precision

## Contract Details

- Name: Vanilla Token
- Symbol: VNLA
- Decimals: 18
- Initial Supply:  100000 VNLA

## Functions

### Core ERC-20 Functions

- `transfer(address, uint256)`: Transfer tokens to another address
- `approve(address, uint256)`: Approve address to spend tokens
- `transferFrom(address, address, uint256)`: Transfer tokens on behalf of another address

### Additional Functions

- `mint(address, uint256)`: Create new tokens (owner only)
- `burn(uint256)`: Burn tokens from caller's balance

## Requirements

- Solidity 0.8.26

## License

This project is licensed under GNU General Public License v3.0. Free to use, distribute, and modify. This contract was developed for educational purposes.
