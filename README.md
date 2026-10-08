An AI-powered payment assistant built on the Stellar Network that simplifies cross-border transactions using natural language.

# StellarFlow

AI-powered cross-border payment platform using Stellar Network

StellarFlow allows users to send digital payments across borders using AI commands and Stellar blockchain transactions. The platform simplifies blockchain payments for anyone, even without prior crypto knowledge.

---

## 🚀 Features

- Conversational AI interface to initiate payments  
- Stellar testnet/mainnet integration for real transactions  
- Real-time transaction confirmations  
- Clean, responsive frontend interface (built with Lovable AI prototype)  

---

## 💻 How It Works

1. User enters payment command in the web interface  
2. AI processes the request and generates Stellar transaction  
3. Transaction is submitted to Stellar testnet/mainnet  
4. Confirmation and transaction hash displayed to user  

> Example: “Send $50 USDT to wallet XYZ”

---

## 🔗 Stellar Testnet Interaction

This project integrates with Stellar blockchain using a Lovable AI-powered prototype.

- Network: Testnet  
- Example Transaction Hash: <PASTE_HASH_HERE>  

> You can verify it on [Stellar Laboratory](https://laboratory.stellar.org/)

---


> The video shows the AI interface, sending a transaction, and proof of Stellar integration.

---


> Replace with your actual website screenshots

---


## 🧠 Development Note

- The frontend UI and AI integration were prototyped using Lovable AI  
- Core logic, Stellar transaction integration, and project idea are implemented and validated by me  
- .gitignore

### Required Build Environment Variables

The production build requires the following environment variables. The build will fail fast if either is missing:

- `VITE_SUPABASE_URL` — the Supabase project URL
- `VITE_SUPABASE_PUBLISHABLE_KEY` — the Supabase publishable (anon) key

For local development, add them to a `.env` file at the repository root. In CI, supply them via repository secrets (see `.github/workflows/ci.yml`).
