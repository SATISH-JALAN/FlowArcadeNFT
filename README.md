# 🎮 FlowArcade – Play. Evolve. Dominate.

**FlowArcade** is a Web3 gaming platform built on **Flow EVM Testnet**, where players mint their own **Dynamic NFT Avatars** that evolve as they play. Each game session earns XP (Experience Points), powering NFT evolution through levels, badges, and rarity tiers.

---

## 🚀 Vision

To redefine Web3 gaming by allowing players to **own their progress**. Your avatar isn't just a profile picture – it's a living identity that grows with every win, achievement, and challenge.

---

## 🪙 Contract Details

* **Blockchain:** Flow EVM Testnet
* **Standard:** ERC-721 (Dynamic NFT)
* **Contract Address:** `0x839595349fc4b54Dbed8dB3c96F26dB6267e6Bc5`

---

## 🧠 Core Features

✅ **Dynamic NFTs** – Avatars evolve via XP and levels
✅ **XP System** – In-game performance directly updates on-chain stats
✅ **Game Authority Control** – Only backend/game can award XP
✅ **Upgradeable Metadata** – NFT visual changes through tokenURI updates
✅ **Flow Friendly** – Low-fee gaming on Flow EVM

---

## 🏗 Tech Stack

| Layer          | Tools                                   |
| -------------- | --------------------------------------- |
| Smart Contract | Solidity, OpenZeppelin                  |
| Blockchain     | Flow EVM Testnet (Chain ID 545)         |
| Frontend       | React + FCL (Flow Client Library)       |
| Backend        | Node.js (Game Authority for XP updates) |

---

## 🔗 Flow EVM Testnet Setup

RPC: `https://testnet.evm.nodes.onflow.org`
Chain ID: `545`
Explorer: [https://evm-testnet.flowscan.io/](https://evm-testnet.flowscan.io/)

---

## 📜 Smart Contract Overview

This contract enables:

* `mint()` – Players mint their Starter NFT Avatar
* `awardXP(tokenId, amount)` – Game backend updates XP
* `getTokenStats(tokenId)` – View XP & Level
* Level thresholds are configurable by owner

---

## 🎯 Gameplay Loop (Concept)

1️⃣ **Connect Wallet** (Flow EVM)
2️⃣ **Mint Your Avatar** (Level 0 Rookie)
3️⃣ **Play Mini-Games** (Arcade Challenges)
4️⃣ **Earn XP + Level Up** (Avatar Evolves)
5️⃣ **Show Off / Trade / Compete**

---

## 🗺 Future Roadmap

* 🏆 Leaderboards & PvP Rankings
* 🎨 On-chain SVG / Animated Visual NFTs
* 🛒 NFT Marketplace for Skins & Powers
* 🎭 Seasonal Events & Exclusive Badges

---

## 🧪 Local Development (Hardhat)

```bash
npm install
npx hardhat compile
npx hardhat run --network flowTestnet scripts/deploy.js
```

Add this to `hardhat.config.js`:

```js
networks: {
  flowTestnet: {
    url: "https://testnet.evm.nodes.onflow.org",
    chainId: 545,
    accounts: ["YOUR_PRIVATE_KEY"]
  }
}
```

---

## 🤝 Contributing

Pull requests are welcome! If you’ve got ideas for mini-games, NFT art, or XP mechanics – join the mission.

---

## ✨ Credits

Built for the new era of Web3 Gaming on **Flow**.
**Own Your Progress. Evolve Your Identity.**

👇 *Stay tuned for the Arcade frontend & game integrations.*
<img width="1906" height="957" alt="image" src="https://github.com/user-attachments/assets/a41df1f7-cc89-4f8b-8ef4-508ee6e8773c" />
