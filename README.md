# Crowdfunding-Based-blockchain-Project


## Getting Started

To use this smart contract, you will need a platform that supports smart contract deployment and execution, such as Ethereum. You will also need a tool such as Remix or Truffle to deploy and test the contract.

## Features
- Secure and transparent fundraising: All transactions and donations are recorded on the Ethereum blockchain, ensuring that the funds are secure and transparent.
- Refund mechanism: In case the campaign does not reach its funding goal, the smart contract will automatically return the donated funds to their respective contributors.
- Efficient and cost-effective: The smart contract eliminates the need for intermediaries, reducing transaction fees and speeding up the fundraising process.

## Contract Methods
### `contribute`
This method allows all the participants to contribute to the Fund.
### `contractBalance`
This method fetche's the balance of the contract.
### `reFund`
This method is used to get the refund if the contract has not reached the target before the deadline.
### `createProposal`
This will be used by the manager to create proposals for investing/donating the Fund.
### `voteForProposal`
This will give the power to the user to vote for any proposal and proposals who win more than 50% vote can only be executed.
### `makePayment`
This will give the payment to the recpient for the proposal.
