# Agentic Ethereum Hackathon India

# 🛠 Project Title - RunaX

Welcome to our submission for the *Agentic Ethereum Hackathon* by Reskilll & Geodework! This repository includes our project code, documentation, and related assets.

---

## 📌 Problem Statement

We addressed the challenge: *“Web3 remains inaccessible to everyday users due to fragmented chains, complex wallet management, and unpredictable gas fees.”*  
We tackled the challenge of cross-chain fragmentation and complicated Web3 user experiences.
Today, managing multiple wallets, keeping track of gas fees, and navigating different blockchain networks is frustrating—even for experienced users. It’s a huge barrier for anyone new to crypto or trying to use it practically..

---

## 💡 Our Solution

*Project Name:* [RunaX: Cross‑Chain Smart Wallet with BharatStack & Agentic Integration]  
RunaX makes using crypto as easy as sending UPI. We built a smart wallet that works across multiple blockchains, pays gas fees on your behalf, and lets users do everything from simple transfers to complex transactions—without needing to understand what's happening under the hood.

It’s designed for everyday users, not just developers or DeFi pros. By integrating BharatStack elements like Aadhaar, DigiLocker, and UPI (mocked), we show how Web3 can feel familiar and useful in an Indian context. We also added an AI agent to help users interact naturally..

---

## 🧱 Tech Stack

- 🖥 Frontend:Next.js, React, Tailwind CSS
- ⚙ Backend: Python (Flask/FastAPI) for AI‑agent server
- 🧠 AI: LangChain (Python)
- 🔗 Blockchain:Solidity & Hardhat on EVM chains (Sepolia & Mumbai), Account Abstraction via Thirdweb, Connext for cross‑chain
- 🔍 DB/Storage: Firebase (Auth & Firestore)
- 🚀 Hosting: Local Host ( as of now )
---

## 📽 Demo

- 🎥 *Video Link*: [YouTube/Drive Link]  
- 🖥 *Live App (if available)*: [URL]

---

## 📂 Repository Structure

```bash
```
```
RUNAXAGENT/
├── agent/
│   ├── venv/
│   │   ├── Include/
│   │   ├── Lib/
│   │   ├── pyvenv.cfg
│   │   └── Scripts/
│   ├── app.py # AI agent application powered by LangChain
│   └── requirements.txt
├── contracts/
│   ├── cache/
│   ├── contracts/
│   │   ├── RunaXAccount.sol # RunaX custom smart account contract
│   │   └── RunaXAccountFactory.sol # Factory contract for RunaX accounts
├── ignition/
│   └── modules/
│       ├── Lock.js # Example Lock contract deployment module
│       └── RunaXAccountSystemModule.js # RunaX account system deployment module
├── node_modules/
├── script/
│   └── deploy.js # Deployment script for smart contracts
├── test/
│   └── Lock.js # Test file for the Lock contract
├── .gitignore
├── hardhat.config.js # Hardhat configuration file
├── package-lock.json
├── package.json
├── lock.sol # Example Solidity contract
├── RunaXAccount.sol # RunaXAccount smart contract (likely reference or duplicate)
├── RunaXAccountFactory.sol # RunaXAccountFactory smart contract (likely reference or duplicate)
├── README.md # Project README file
├── frontend/
│   ├── .env.local
│   ├── .gitignore
│   ├── .next/
│   ├── .modules.yaml
│   ├── eslint.config.mjs
│   ├── next-env.d.ts
│   ├── next.config.ts
│   ├── node_modules/
│   ├── package.json
│   ├── postcss.config.mjs
│   ├── public/
│   ├── src/
│   │   ├── app/
│   │   │   ├── favicon.ico
│   │   │   ├── globals.css
│   │   │   ├── layout.tsx # Root layout component for Next.js app
│   │   │   └── page.tsx # Main page component
│   │   └── lib/
│   │       ├── firebase.ts # Firebase integration utilities
│   │       └── thirdweb.ts # Thirdweb SDK integration utilities
│   └── tsconfig.json
├── node_modules
├── .env
├── .gitignore
├── package.json
├── pnpm-lock.yaml
├── pnpm-workspace.yaml
└── README.md
```

