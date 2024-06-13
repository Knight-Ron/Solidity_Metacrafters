# Solidity_Metacrafters
# Remix Default Workspace for MyToken Contract

## Introduction

The Remix default workspace is available when:
- Remix loads for the very first time.
- A new workspace is created with the 'Default' template.
- There are no files existing in the File Explorer.

## Workspace Structure

This workspace contains three main directories:

1. **contracts**: Holds the MyToken contract.
2. **scripts**: Contains TypeScript files to deploy the MyToken contract using `web3.js` and `ethers.js` libraries.
3. **tests**: Contains Solidity and JavaScript test files for the MyToken contract.

## Contracts Directory

### MyToken.sol

The `MyToken.sol` contract allows minting and burning of tokens. It includes:
- **Token_Name**: The name of the token ("NiceToken").
- **Token_Abbrv**: The abbreviation of the token ("NT").
- **Total_Supply**: The total number of tokens in circulation.
- **Balance**: A mapping to keep track of token balances for each address.

## Scripts Directory

The `scripts` folder has TypeScript files to help deploy the MyToken contract using `web3.js` and `ethers.js` libraries.

### Deployment Instructions

To deploy the MyToken contract:
1. Update the contract's name from 'Storage' to 'MyToken'.
2. Provide any necessary constructor arguments in the deployment files.

## Tests Directory

The `tests` folder contains unit tests for the MyToken contract using Mocha-Chai.

### Test Files

The test files verify the minting and burning functions of the MyToken contract.

Running Scripts

To run a script:
1. Right-click on the file name in the File Explorer and click 'Run'.
2. Ensure the Solidity file has already been compiled.
3. The output from the script will appear in the Remix terminal.

**Note: Require/import is supported in a limited manner for Remix supported modules. Supported modules include ethers, web3, swarmgw, chai, multihashes, remix, and hardhat (only for hardhat.ethers object/plugin). Unsupported modules will throw an error indicating that the module is not supported by Remix IDE.
