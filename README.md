# Retrospection

For the puzzle #7 and #8, I need the help of https://hackernoon.com/evm-puzzles-learn-ethereum-by-solving-interactive-puzzles .  I don't really understand how the opcode CREATE works. I will  deep further to notice how the bytecode executed during the deployment can return the value of the newly created contract's bytecode. There is certainly something with the constructor.

# Branch more-evm-puzzle

# EVM puzzles

A collection of EVM puzzles. Each puzzle consists on sending a successful transaction to a contract. The bytecode of the contract is provided, and you need to fill the transaction data that won't revert the execution.

## How to play

Clone this repository and install its dependencies (`npm install` or `yarn`). Then run:

```
npx hardhat play
```

And the game will start.

In some puzzles you only need to provide the value that will be sent to the contract, in others the calldata, and in others both values.

You can use [`evm.codes`](https://www.evm.codes/)'s reference and playground to work through this.
