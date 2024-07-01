# SimpleVoting Smart Contract 🗳️

## Project Title
SimpleVoting Smart Contract

## Simple Overview
A basic Ethereum smart contract that implements a simple voting system with proposal creation, voting, and finalization functionalities.

## Description
The SimpleVoting smart contract manages a straightforward voting system on the Ethereum blockchain. Users can create proposals, vote on proposals, finalize them, and cancel if necessary. Events are emitted to log these actions for transparency and tracking.

## Getting Started

### Installing
You can copy the contract code from the `SimpleVoting.sol` file in this repository.

### Executing program

#### Set Up Your Development Environment:
- Use Remix IDE or any other Solidity development environment.

#### Compile the Contract:
- Paste the copied code into your Solidity file in Remix IDE.
- Click on the "Solidity Compiler" tab and compile the contract.

#### Deploy the Contract:
- Go to the "Deploy & Run Transactions" tab in Remix IDE.
- Select the desired environment (e.g., JavaScript VM, Injected Web3 for MetaMask).
- Click "Deploy" to deploy the contract.

### Step-by-step Usage

#### Create a Proposal:
```solidity
simpleVotingInstance.createProposal("My Proposal");
```
This command creates a new proposal with the description "My Proposal".

#### Vote on a Proposal:
```solidity
simpleVotingInstance.vote(1, true);
```
This command votes "yes" on proposal with ID 1.

#### Finalize a Proposal:
```solidity
simpleVotingInstance.finalizeProposal(1);
```
This command finalizes proposal with ID 1.

#### Get Proposal Result:
```solidity
simpleVotingInstance.getResult(1);
```
This command returns the result of proposal with ID 1.

#### Cancel a Proposal:
```solidity
simpleVotingInstance.cancelProposal(1);
```
This command cancels proposal with ID 1.

### Help
For common problems or issues, ensure:
- You have sufficient balance for voting and finalizing functions.
- The proposal IDs used in functions are correct and valid.
- Verify your Solidity version and compatibility with the compiler settings if deployment fails.

## Authors
Anshu Kumar - [@AnshuKumar](https://github.com/Ansh-Ks18)

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

For more information, please refer to the [Solidity Documentation](https://docs.soliditylang.org/).

---
