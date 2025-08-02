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
# HOW TO PLAY

Capture the crux is a two-player strategy board game. 2 players compete against each other using 5 pieces, each having different stats and abilities, to capture the opponent's base.

## Rooms
One player creates a room and shares the room code with the other player. Once both players join, the game starts.

## Game Overview
Pieces and Their Special Abilities
Scout: Can move 3 steps and has low health (HP: 15) and attack power (ATK: 10).
Special ability: Pathfinder (isn't blocked by pieces/goes through pieces).
Knight: Moves 2 steps with decent health (HP: 25) and attack power (ATK: 15).
Special ability: Aggressor (+5 damage when it initiates an attack).
Tank: Moves 1 step but has high health (HP: 40).
Special ability: Fortified (reduced damage taken when on its base).
Mage: Moves 2 steps with moderate health (HP: 20) and attack power (ATK: 15).
Special ability: Ranged (can attack from a distance of 2 steps).
Healer: Moves 2 steps with moderate health (HP: 30) and low attack power (ATK: 5).
Special ability: Medic (can heal one of the deployed allies by 15 HP when deployed).

## Pieces' Deployment and Points
To deploy a piece, select a card. The card will glow red to indicate that its selected. Pieces can only be placed at one of the 2 deployable points of your side ( Be sure to not let them get captured).

For the player who created the room (Player 1), their side is green one. For the player who joined the room through code (Player 2), their side is the blue one.

For both players, the darker 2 Points are the deployable points, while the lighter one is the base. Place any of your piece on opponent's base to win the game.

## Moving a Piece
To move a piece, click on the piece on the board. It will glow purple and the valid points it can move to will glow red.

Click on any red point to move your piece to that point.

## Combat Mechanics
When you have a piece in range ( 2 for Mage, Adjacent for others ) of an opponent's piece and its your turn, you can click on the card of the piece. The opponent pieces that can be attacked will have their card glow blue. Click on the card to attack the piece. Your turn ends.

When you attack an opponent's piece, the attacked piece's HP is reduced by the ATK of the attacking piece. The attacking piece's HP is reduced by the attacked piece's ATK. Meaning both pieces attack each other.

If any piece has its Hp down to 0, it goes into Recovery (indicated by a black background). In order for the piece to get back into the game, another piece will have to go into Recovery essentially exchanging the pieces.

## Combat Mechanics
Some important points
Zoom in or out if you are unable to view the full board along with the 5 piece cards.

Reloading the tab will mean disconnecting the game. However, you can always create a new room.


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









