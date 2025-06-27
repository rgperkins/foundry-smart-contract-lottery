# Proveably random raffle contracts

## What do we want it to do?

1. Users can enter by paying for a ticket
   1. The ticket fees are going to go to the winner during the draw
2. After X period of time, the lottery will automatically draw a winner
   1. This will be done programmatically
3. Using Chainlink VRF & Chainlink Automation
   1. Chainlink VRF -> Randomness
   2. Chainlink Automation -> Time based triggers

## Tests!

1. Write deploy scripts
   1. Note, these will not work on zkSync
2. Write tests
   1. Local chain
   2. Forked testnet
   3. Forked mainnet
