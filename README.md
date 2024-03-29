# Solidity Lottery Contract

This Solidity smart contract implements a lottery system where participants contribute 1 ether each to enter. The contract is managed by a designated address. Participants' addresses are stored, and a winner is randomly selected from the pool of participants when triggered by the manager. The selected winner receives the entire balance of the contract.

## Features

- **Participant Entry:** Users can participate in the lottery by sending 1 ether to the contract.
- **Manager Control:** The contract is managed by a designated address, ensuring fairness and security.
- **Random Selection:** Winner selection is based on a random algorithm using block data and participant count.
- **Winner Payout:** The selected winner receives the entire balance of the contract.
- **Safety Checks:** The contract includes safety checks to ensure minimum participants before selecting a winner.

## Getting Started

To deploy and interact with the contract, follow these steps:

1. Deploy the contract on a supported Ethereum network using a compatible wallet or development environment.
2. Interact with the deployed contract using a wallet or a web3-enabled application.

## Usage

Below are the main functions available in the contract:

- **receive():** Participate in the lottery by sending 1 ether to the contract.
- **getBalance():** View the current balance of the contract.
- **random():** Generate a random number for winner selection.
- **selectWinner():** Manager selects a winner randomly and transfers the balance to the winner.

## Example

```solidity
// SPDX-License-Identifier: MIT
pragma solidity >=0.5.0 <0.9.0;

contract Lottery {
    // Contract variables and functions...
}

##   Contributors
- [Suhas H S](https://github.com/Suhas-30)
