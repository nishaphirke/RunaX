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
│   ├── venv/
│   │   ├── Include/
│   │   ├── Lib/
|   |   ├── pyvenv.cfg
│   │   └── Scripts/
│   ├── app.py # langchain  
│   └── requirements.txt
├── contracts/
│   ├── cache/
│   ├── contracts/
│   │   ├── RunaXAccount.sol #
│   │   └── RunaXAccountFactory.sol
├   |── ignition/
│   |     └── modules/
│   |          ├── Lock.js
│   |          └── RunaXAccountSystemModule.js
├   |── node_modules/
|   ├── script/
│   |     └── deploy.js
|   ├── test/
│   |      └── Lock.js
|   ├──.gitignore
|   ├──hardhat.config.js
|   ├──package-lock.json
|   ├──package.json
|   ├──lock.sol
|   ├──RunaXAcoount.sol
|   ├──RunaXAccountFactory.sol
|   ├──README.md
├── frontend/
│   ├── .env.local
│   ├── .gitignore
│   ├── .next/
│   ├── .modules.yaml
│   ├── eslint.config.mjs
│   ├── next-env.d.ts
│   ├── next.config.ts
│   ├── node_modules/
│   ├── package.json
│   ├── postcss.config.mjs
│   ├── public/
│   ├── src/
│   │   ├── app/
│   │   │   ├── favicon.ico
│   │   │   ├── globals.css
│   │   │   ├── layout.tsx
│   │   │   └── page.tsx
│   │   └── lib/
│   │       ├── firebase.ts
│   │       └── thirdweb.ts
│   └── tsconfig.json
├── node_modules
├── .env
├── .gitignore
├── package.json
├── pnpm-lock.yaml
├── pnpm-workspace.yaml
└── README.md
```

