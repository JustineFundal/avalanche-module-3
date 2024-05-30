# avalanche-module-3
Token Smart Contract
This repository contains an ERC-20 token contract with custom minting, burning, and owner-specific restrictions.

Contract Details

License
SPDX License Identifier: MIT

Solidity Version
Version: ^0.8.25

Imports
OpenZeppelin ERC-20: @openzeppelin/contracts/token/ERC20/ERC20.sol

Key Features
Minting: Only the owner can mint new tokens.
Burning: Owner can burn tokens but must retain a minimum balance.
Transfers: Standard ERC-20 token transfers.
Configuration: Owner can set the minimum burn balance.

Usage
Deploy: Deploy with the owner's address.
Mint: Owner mints tokens to their address.
Burn: Owner burns tokens ensuring a minimum balance.
Transfer: Use the standard ERC-20 transfer function.
Configure: Owner can set the minimum owner burn balance.

License
MIT License

authors 
creator: Justine Felix V. Fundal
email: 8213339@ntc.edu.ph
contact: 09176510079
