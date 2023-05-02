---
sidebar_position: 5.1
slug: /treasury_of_shimmer/hack_the_eggs
title: Hack the EGGS
---

# Hack the EGGS

Welcome to the "Treasury of Shimmer" Event and the exciting "Hack the EGGS" challenge! This challenge allows you to play a game against the IOTABOT and win valuable rewards. This document provides a brief overview of the game contract and instructions on how to join the challenge.


```
EGGS address: 0xdFCF738225F6508F7A664c3c7D236432501e16d4

Test IOTABOTS address: 0xb5A53615170e4684E488C9E1c641aB9dDC307489

Game Address: 0x3CE8aB86dED969004102caB650060373e04A0448
```

Best of luck in your games against the IOTABOT, and enjoy the "Hack the EGGS" challenge!


## How the Game Contract Works

The game is based on the classic Rock, Paper, Scissors game, where:

- 0 represents Rock
- 1 represents Paper
- 2 represents Scissors

The game contract uses a pseudo-random function to determine the IOTABOT's move. Players can participate by calling the `createSingleGame` function with their chosen move and the required game fee.

The game rules are as follows:

- Rock beats Scissors
- Paper beats Rock
- Scissors beat Paper

If the player wins, they receive 10 EasterEggs tokens. In case of a draw or a loss, the player receives nothing.

## How to Play

Here is a step by step guide, how to get some EGGS:

### 1. Get an Test OG IOTABOTS

- Install MetaMask, copy your paste it to me.
- Add custom network -> [ShimmerEVM Testnet Quickstart Guide](https://wiki.iota.org/shimmer/smart-contracts/guide/evm/quickstart/)
- Go to https://games.iotabots.io/games and click on "connect to metamask"
- Your bot should be visable now - if you already have one.
- If you dont have a bot - ask around or find one on some Test NFT Marketplaces. Keep in mind - every trade or movement of an IOTABOT in the Testnet does not affect the mainnet!

### 2. Get some EGGS

- Play the game to win some EGGS.
- You need Shimmer Test Tokens -> https://evm-toolkit.evm.testnet.shimmer.network/
- Add the EGGS Token to your MetaMask
- Understand what happens
- Watch TX on Explorer: https://explorer.evm.testnet.shimmer.network/

### 3. Hack the Eggs

- Get 1.000.000 EGGS
- Win 100 times in a row
- Can u get EGGS without an IOTABOT?

## How to Join the Challenge

To join the "Hack the EGGS" challenge, follow these steps:

1.  Make sure you have a compatible Ethereum wallet with enough Ether to cover the game fee and gas fees.
2.  Connect your wallet to a user interface that supports interactions with smart contracts, such as Remix or a custom Dapp.
3.  Ensure that you have the appropriate CryptoHeros tokens in your wallet to participate in the game.
4.  Interact with the Game contract using its deployed address, and call the `createSingleGame` function with the following parameters:
    - `_tokenId`: The ID of the CryptoHeros token you wish to use for the game.
    - `_bet`: Your move in the game, represented by an integer (0, 1, or 2).
5.  Pay the required game fee (1 ether) to participate in the game.
6.  Wait for the game to conclude, and check the emitted `gamePlayed` event to determine the winner and the moves played.

Advanced Participation: Using Scripts or Smart Contracts
--------------------------------------------------------

For more experienced users, you can interact with the "Hack the EGGS" challenge using custom scripts or even another smart contract. This approach allows you to automate game participation and potentially implement your strategies for winning against the IOTABOT.

### Using Custom Scripts

To use a custom script to interact with the Game contract, follow these steps:

1.  Choose a programming language and Ethereum library that supports interacting with smart contracts, such as Web3.js (JavaScript), ethers.js (JavaScript), or Web3.py (Python).
2.  Initialize the library with your Ethereum wallet and the deployed address of the Game contract.
3.  Write a script that calls the `createSingleGame` function, passing the appropriate parameters (`_tokenId` and `_bet`), and sends the required game fee.
4.  Optionally, you can implement a strategy for choosing your moves, either based on historical data, patterns, or any other approach you find interesting.
5.  Run the script and monitor the emitted `gamePlayed` events to determine the outcomes of your games.

### Using Another Smart Contract

To interact with the Game contract using another smart contract, follow these steps:

1.  Create a new smart contract in Solidity or another supported Ethereum programming language.
2.  Import the Game contract's interface to your new smart contract, ensuring that the functions and events are correctly defined.
3.  Implement a function within your new smart contract that calls the `createSingleGame` function of the Game contract, passing the appropriate parameters (`_tokenId` and `_bet`), and sends the required game fee.
4.  Optionally, you can implement a strategy for choosing your moves or even allow other users to participate in the "Hack the EGGS" challenge through your smart contract.
5.  Deploy your new smart contract to the Ethereum network.
6.  Interact with your smart contract by calling the function that initiates participation in the "Hack the EGGS" challenge.
7.  Monitor the emitted `gamePlayed` events to determine the outcomes of your games.

By using custom scripts or another smart contract, you can enhance your experience in the "Hack the EGGS" challenge and potentially increase your chances of winning against the IOTABOT. Good luck and have fun exploring new ways to play the game!


