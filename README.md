# Proveably Random Raffle Contracts

## About

This code is to create a proveably random smart contract lottery.

## What we want it to do?

1. Users can enter by paying for a ticket
   1. The ticket fees are going to go to the winner during the draw
2. After period X of time, the lottery will automatically draw a winner
   1. And this will be done programmatically
3. Using Chainlink VRF & Chainlink Automation
   1. Chainlink VRF -> Randomness
   2. Chainlink Automation -> Time based trigger

## Tests

1. Write some deploy scripts
2. Write our tests
   1. Work on a local chain
   2. Forked Testnet
   3. Forked Mainnet

## Layout of Contract

1. version
2. imports
3. errors
4. interfaces, libraries, contracts
5. Type declarations
6. State variables
7. Events
8. Modifiers
9. Functions

## Layout of Functions

1. constructor
2. receive function (if exists)
3. fallback function (if exists)
4. external
5. public
6. internal
7. private
8. view & pure functions
