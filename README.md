# 🔄 UPDATE Plume Swap Bot season 2
A lightweight Node.js bot that automatically swaps between PLUME and pUSD on the Plume chain. Ideal for automation and airdrop farming—especially for Plume Airdrop Season 2.

<img width="1205" height="540" alt="image" src="https://github.com/user-attachments/assets/3aa61fe0-54a6-4d67-8284-18f3613e37ec" />

## 🚀 New Features
- Randomized daily swaps across 3 DEXs: Ambient, Rooster, and iZUMi.
  
- Auto-stakes to the Plume Portal daily with a random amount between 0.1 and 0.3 PLUME.
  
- Swap amounts and delays are randomized and fully configurable via the .env file.

- Designed to maximize points for Plume Airdrop Season 2.

## 📦 Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/Kurisaitou/auto-swap-plume-season-2-in-4-DAPPs.git
```
```bash
cd auto-swap-plume-season-2-in-4-DAPPs
```
```bash
npm install
```

# ⚙️ Environment Setup
Create a .env file in the project root:
```bash
nano .env
```
Fill in your wallet details and configure your preferred settings:
```bash
PLUME_RPC=https://rpc.plume.org

PRIVATE_KEY_1=your_private_key
WALLET_ADDRESS_1=your_address

# you can change
MIN_PLUME=10
MAX_PLUME=30

# you can change
MIN_TX=10
MAX_TX=30

# you can change
MIN_DELAY=60
MAX_DELAY=120
```

## ▶️ Running the Bot
To start the bot:
```bash
node index.js
```
What the bot does:

- Randomly selects between Ambient, Rooster, and iZUMi DEXs for daily swaps.

- Executes a random number of swap transactions with randomized token amounts and delays.

- Automatically stakes a random amount (0.1 – 0.3 PLUME) daily to the Plume Portal to earn airdrop points.

## 🎯 Goal
Maximize your engagement with the Plume ecosystem and boost your chances of earning more rewards from Plume Airdrop Season 2 — automatically.

## 🔖 Tags
#plume #airdrop #swap #bot #crypto #web3 #automation #trading #pUSD #dex #stake 
