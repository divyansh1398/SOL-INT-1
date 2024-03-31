# Sol-Advance-1

The following is a Rust program designed to perform addition or subtraction operations on two given numbers based on user instructions.

## Description

This is a smart contract implemented in Rust, a programming language specifically used for developing smart contracts on the Solana blockchain. This contract operates by accepting user inputs and performing addition or subtraction on the provided numbers. A client program is provided for testing and interacting with the smart contract.

## Getting Started

### Executing program

To run the program, please follow these steps:

**Build**

`cargo build-bpf --manifest-path=./Cargo.toml --bpf-out-dir=dist/program`

**Deploy**

`solana program deploy dist/program/solana_calculator.so`

Program Id: 2RuyRo3L4g3ASzEXSPyMn3HPJ1pic9U96VezjjgLDuXL

Once you have completed the above steps, navigate to the "scripts" folder and run `npm install` to install the necessary dependencies.

After completing the installation, you can interact with the contract using the following commands:

**Add two numbers**

`npm run start -- add <NUM1> <NUM2>`

**Subtract two numbers**

`npm run start -- sub <NUM1> <NUM2>`
