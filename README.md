![AvaXGod](https://github.com/user-attachments/assets/cb2c9fbc-882f-4ea4-ad49-7c537f5124e2)


### Project Name: **Avax God on Intersect**

### Description:
The Avax God on Intersect NFT Card Game is a blockchain-based strategy card game where players use NFTs as cards to engage in strategic battles. The game is hosted on the **Avalanche's Intersect Testnet** with **Pearl** as the native token. Each player's move, whether attacking or defending, requires signing a transaction via their connected crypto wallet (Metamask or Core Wallet), ensuring decentralized and transparent gameplay. Players must balance attack, defense, and mana usage to outsmart their opponent and win.

### Features:
- **NFT Cards**: Each player owns unique NFT cards with different attack and defense stats.
- **Strategic Gameplay**: Players can attack or defend, with the game's rules ensuring strategic thinking is rewarded.
- **On-Chain Moves**: Every move is recorded on the Avalanche Intersect blockchain, with transactions signed via the player's wallet.
- **Mana System**: Each action (attack or defense) requires a mana cost, and defending regenerates mana.
- **Native Token**: The game uses **Pearl**, the native token of the Intersect Testnet, for all in-game transactions.
  
### Game Rules:
1. **Card Cancellation**: Cards with the same attack and defense points will cancel each other out.
2. **Attack Impact**: If a player attacks and the opponent does not defend, the attack points will directly reduce the opponent's health.
3. **Defense Calculation**: If the opponent defends, their defense is subtracted from the attack points.
4. **Mana Refill on Defense**: Defending regenerates 3 mana points.
5. **Mana Spend on Attack**: Attacking costs 3 mana points.

### Requirements:
- **Metamask or Core Wallet**: Install one of these crypto wallets and connect to the Avalanche Intersect Testnet.
- **Pearl Token**: Ensure you have some **Pearl** tokens for in-game interactions.

### Steps to Connect to Avalanche Intersect Testnet:
1. Open Metamask and click the network dropdown in the top-right corner.
2. Select "Add Network" and fill in the following:
   - **Network Name**: Intersect Testnet
   - **RPC URL**: `https://subnets.avax.network/pearl/testnet/rpc`
   - **ChainID**: `1612`
   - **Symbol**: `Pearl (Test)`
   - **Decimals**: `18`
   - **Explorer URL**: `https://subnets-test.avax.network/intersect`
3. Click "Save."

### How to Play:
- Each player begins with a set of NFT cards and a limited amount of mana.
- Players can attack or defend during their turn, with each action requiring them to sign a transaction through their connected wallet.
- The game ends when one player's health reaches zero, based on their strategic use of attack and defense cards.

### Technologies Used:
- **Avalanche Intersect Testnet**: Blockchain network where all interactions are executed.
- **Solidity**: Smart contracts for handling in-game transactions and moves.
- **React.js**: Frontend framework for the game interface.
- **Metamask/Core Wallet**: Wallet integration for signing transactions and interacting with the blockchain.
