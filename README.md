# Smart Contract Hacking Exercises

# Introduction

Welcome to my Smart Contract Hacking Exercises repository! This project consists of a series of exercises designed to enhance my understanding of smart contract vulnerabilities and security exploits. By working through these exercises, I aim to identify, analyze, and exploit weaknesses in Solidity smart contracts.

# Why?

The purpose of this repository is to provide hands-on experience in smart contract security by simulating real-world vulnerabilities. This will help me:

Improve my Solidity security skills.

Understand common smart contract vulnerabilities.

Learn how to mitigate risks and secure smart contracts effectively.

Gain experience using Hardhat for testing and debugging.

# Structure

This repository is structured as a Hardhat project with the following main folders:

./instructions - Contains all the instructions for each exercise.

./contracts - Includes the Solidity smart contracts used in the exercises.

./test - Holds the test files to execute and validate the exercises.

# Quick Start Guide

Setup & Installation

Dependencies

From the root folder, install all required dependencies:

npm install

RPC Node - For Mainnet Forks

I signed up for Infura (or any other Ethereum node provider).

Obtained an Ethereum Mainnet URL.

Copied the .env-example file and renamed it to .env.

Set my Infura URL for:

MAINNET - Ethereum Mainnet

Running Exercises

To execute and test an exercise, I use the following command:

npm run [exercise-name]

I can find the list of available exercises in the package.json file.

Example:

If working on the reentrancy-2 exercise:

Create any necessary contracts under ./contracts/reentrancy-2/

Modify the test file ./test/reentrancy-2/tests.js as needed.

Run the exercise:

npm run reentrancy-2

This will validate whether I have completed the exercise successfully.

# Guidelines

Unless explicitly mentioned in an exercise, I do not modify the EVM state using Hardhat functionalities (e.g., balance manipulation, block time changes, etc.).

I do not alter the before and after sections in test files.

Useful Hardhat Commands

npx hardhat help             # List available Hardhat commands
npx hardhat test             # Run all tests
REPORT_GAS=true npx hardhat test  # Run tests with gas reporting
npx hardhat node             # Start a local Hardhat node
npx hardhat run scripts/deploy.js  # Deploy contracts using a script

Resources

# Solidity Documentation: Solidity Docs

# Hardhat Documentation: Hardhat Docs

#Ethereum Security Best Practices: Consensys Security Guide

License

This project is licensed under the MIT License.

