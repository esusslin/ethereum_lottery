# ethereum_lottery
A simple decentralized lottery application on the Ethereum network via Solidity and Web3 and built with a React frontend.

### Summary

This application enables a manager to host a lottery held on the Ethereum network.  Peasants can all submit their own lottery contracts, which are sent to the ethereum network, and the manager can initiate the random selection of a winner.  When one of the peasants wins, the lottery sum is distributed to their own account.

## Lottery Contract

#### Variables
⋅⋅* manager: id of the boss
⋅⋅* players: ids of the pesants

#### Functions
⋅⋅* enter: submits a player into the lottery
⋅⋅* pickWinner: randomly picks the winner and distrubutes winnings
