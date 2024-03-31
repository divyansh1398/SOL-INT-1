# Sol-Advance-1

This Rust program is created to execute addition or subtraction operations on two provided numbers depending on user input instructions.

## Description

This smart contract, coded in Rust, is tailored for the Solana blockchain, serving to accept user inputs and execute addition or subtraction operations on the given numbers. A client program is also included for testing and interacting with the smart contract.

note: target folder is not uploaded as it coontains too many files so please refer to the original folder in the assignment page.

## Getting Started

### Executing program

To execute the program, kindly adhere to the following instructions:

**Build**

Execute the command:
```
cargo build-bpf --manifest-path=./Cargo.toml --bpf-out-dir=dist/program
```

**Deploy**

Deploy the program using the command:
```
solana program deploy dist/program/solana_calculator.so
```

Program Id: 2RuyRo3L4g3ASzEXSPyMn3HPJ1pic9U96VezjjgLDuXL

After completing the aforementioned steps, proceed to the "scripts" directory and execute `npm install` to install the required dependencies.

Upon finishing the installation, you can engage with the contract using the provided commands:

**Add two numbers**

`npm run start -- add <NUM1> <NUM2>`

**Subtract two numbers**

`npm run start -- sub <NUM1> <NUM2>`
