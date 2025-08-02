# Capture The Crux
Capture The Crux is a strategy-based board game where two players, each controlling a team of five unique adventurers, compete to conquer the enemy’s base. This game combines tactical decision-making and adventurous gameplay.


## Demo-Video

## Key Features
* ####  2-Player Gameplay
* ####  Unique Adventurer Roles and Abilities of Pieces
* ####  MONAD Blockchain integration
     ##### 1.Character Skins Purchase: Users can buy character skins using MONAD.
     ##### 2.Exclusive Collab Skins: Special MONAD collaboration skins are available for purchase.
     ##### 3.Reward System: Players earn WIN tokens upon victory.

## Objective
The goal is to strategically maneuver your pieces and place one on your opponent's base to win the game.

## Game Rule
1. Each player starts with five pieces, each having unique abilities.
2. Players take turns moving one piece at a time on the board.
3. A piece must reach the opponent's base to win the game.
4. All pieces are unique, having their own attack power, health, move range, and 
   special abilities.
   

## Technologies Used
* ####  Frontend: Vite ( React ), Tailwind CSS
* ####  Backend: Node.js, Express.js, Socket.io
* ####  Blockchain: Foundry ( Contract deployed on MONAD Testnet )
* ####  Smart contract Connection: Ethers.js

## Installation & Setup

### Prerequisites
- Node.js
- npm or yarn
- Metamask or other Web3 wallet configured for MONAD Chain

### Client Setup
```bash
cd client
npm i
npm run dev
```

### Server Setup
```bash
cd server
node server.js
```

### MONAD Chain Configuration for Metamask
- **Network Name**: MONAD Testnet
- **RPC URL**: https://testnet-rpc.monad.xyz
- **Chain ID**: 10143
- **Currency Symbol**: MON
- **Block Explorer URL**: https://testnet.monadexplorer.com


## Important Points
1. You do not need to connect a wallet to play but connecting wallet allows you to select the skins. If both players have their wallet connected, they can agree to register the winner.
2. Zoom in/out if unable to see all pieces and map according to your comfort.
3. Read the How-to-play on Home page to know about the instructions.
4. For the online site, it may happen that the server does not respond due to being inactive after a period of inactivity as it was hosted on a free tier.

## Creating and Joining Room
A player can create room and get the room code which can then be shared with the other player, and both can jump into a game.


## Connect Wallet and Skins
A player can choose to connect their wallet. The code is set up to connect to MONAD Testnet since the contract was deployed on that. Although it is also set to ask permission to add the testnet if not present in user's metamask, if facing issue, make sure to add and switch to MONAD testnet before connecting wallet. Else if connected wallet but not on MONAD Testnet, you will be able to see current skins and the ones for collab but will be unable to buy the skins through smart contract.

### Current Skins
Shows the current equipped skins of the player. Go to lobby, reload page, and come back if you want to change to default skins after changing the skins.


### Available Skins 
Shows the current available skins you can buy and apply.


### MONAD Collab Skins
Shows the skins that are provided through some web3 collaboration. Right now there is a volcano map which you can buy and upon selecting that you can change your lobby and arena background.


## Registering the Winner
If both players have their wallet connected, then after one player wins, players can choose to agree and register the winning of the winner on blockchain. The option is provided on the same screen which shows who won after the game ends.

## GMONAD Tokens as Reward
The person who wins gets 100 GMONAD tokens as reward which he can see in his wallet upon successfully importing the GMONAD token address.

# The Contract

MONAD's Battle Arena Contract Address - 0x8bD9acAA603f038170a63bAAAd076448Abe866A2

GMONAD Token Address - 0x44A8d4f0ea6b36FF20C3A98D315b6aFb59C34294

Block Explorer Link - https://testnet.monadexplorer.com/address/0x8bD9acAA603f038170a63bAAAd076448Abe866A2









