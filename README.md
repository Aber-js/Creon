# 🧩 Creon – Web3 Creator Economy Platform

Creon is a mobile-first Web3 platform for creators to monetize their work, receive crypto tips, and access grant opportunities — starting with NFT profiles and wallet integration.

 ✅ Current Features 

| Feature                     | Status   | Description |
|-----------------------------|----------|-------------|
| 🔐 Wallet Auth              | ✅ Built | MetaMask (Ethereum) + Phantom (Solana) connection |
| 👤 User Profiles            | ✅ Built | Wallet-linked profiles with bio and avatar |
| 🎨 NFT Showcase (Mocked)    | ✅ Built | Display wallet NFTs (basic metadata via mocks) |
| 💰 Tipping System.          | ✅ Built | Send peer-to-peer crypto tips (test wallets) |


 Planned Features (In Development / Roadmap)

| Feature                     | Status | Description |
|-----------------------------|--------|-------------|
| 🏆 Grant Discovery          | 🔜     | Browse & apply for creator grants (e.g., Superteam) |
| 🔒 Token-Gated Content      | 🔜     | Unlock premium assets via NFTs/tokens |
| 📊 Earnings Dashboard       | 🔜     | Analytics for views, earnings, tips |
| 🧾 Multi-chain Auth (ACC)   | 🔜     | Adobe Certified Creator verification system |
| 🔍Provenance + Arweave/IPFS | 🔜     | Timestamped metadata for uploaded designs |


🔧 Architecture Overview

 Frontend
- React 18 + Vite
- Tailwind CSS + shadcn/ui
- Wouter (routing), TanStack Query (data)

 Backend
- Node.js + Express
- TypeScript (ESModules)
- REST API w/ error middleware

 Database
- Drizzle ORM + PostgreSQL (Neon)
- Mocked storage for early testing

---

## 💻 Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# For production build
npm run build
# Creon
