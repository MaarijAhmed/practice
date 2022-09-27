# Sample Solidity Project
This is the sample solidity project that can be used as an example of a proper environment setup.

# Project Status
The project is in progress. More info, documents, tests, and code will be added. Docs Proofread is required.

# Specs

Are found in the [Requirements.pdf](./docs/Requirements.pdf) file

# Getting Started
Recommended Node version is 16.0.0 and above.

```bash
$ npx yarn
$ npx hardhat node
$ npx hardhat test
```

# Project Structure
This a hardhat javascript project.

## Tests

Tests are found in the `./test/` folder. `./sample-test.js` contains various test helpers.

## Contracts

Solidity smart contracts are found in `./contracts/`.
`./contracts` folder contains contracts 

## Deploy
Deploy script can be found in the `scripts/sample-scripts.js` folder.

To add the private key of a deployer account, assign the following variable in``hardhat-config.js`
```
account : ["PRIVATE KEY "]
```

# Deploy Contract

```bash
$ npx hardhat run scripts/sample-script.js --network bsc
```
