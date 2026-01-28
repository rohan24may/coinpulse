# 🚀 CoinPulse  
CoinPulse is a modern **crypto tracking dashboard** built with **Next.js App Router**, **TypeScript**, and the **CoinGecko API**.  
It provides real-time crypto prices, interactive candlestick charts, trending coins, and detailed coin analytics in a clean, production-ready UI.

![CoinPulse Banner](./public/logo.svg)

---


## ✨ Features
- 📊 **Live Crypto Prices** – Track Bitcoin and other popular coins.
- 📈 **Candlestick Charts (OHLC)** – Visualize price movements clearly.
- 🔥 **Trending Coins** – Discover trending assets in real time.
- 🔍 **Dynamic Coin Pages** – Detailed views with `/coins/[id]` routing.
- ⚡ **Server Components & Actions** – Optimized performance with Next.js.
- 🛡️ **Graceful Error Handling** – Handles unsupported coins & API failures.
- 🎨 **Clean Responsive UI** – Works seamlessly across devices.

---

## ⚡️ Glimpse
![CoinPulse Charts](./public/chart.png)
![CoinPulse Coins](./public/coins.png)

---

## 🧑‍💻 Tech Stack
- **Next.js (App Router)** – Fullstack React framework  
- **TypeScript** – Type-safe development  
- **Tailwind CSS** – Modern utility-first styling  
- **CoinGecko API** – Crypto market data  
- **Lightweight Charts** – Candlestick chart rendering  
- **Lucide Icons** – Clean, consistent icons  

---

## 💻 Workflow
![CoinPulse Workflow](./public/features.png)

---

## 🚀 Getting Started  

Before running CoinPulse, make sure you have the following installed:

### ✅ Node.js & npm
- Download from [nodejs.org](https://nodejs.org/)
- Verify installation:
```bash
node -v
npm -v
📦 Installation
# Clone the repository
git clone https://github.com/rohan24may/coinpulse.git
cd coinpulse

# Install dependencies
npm install
⚙️ Environment Setup
Create a .env.local file in the root directory:

COINGECKO_BASE_URL=https://api.coingecko.com/api/v3
Uses the free CoinGecko API (no API key required).

▶️ Run the App
npm run dev
Open in browser:

http://localhost:3000
📁 Project Structure
coinpulse/
├── app/                 # Next.js App Router pages
│   └── coins/[id]/      # Dynamic coin pages
├── components/          # UI & chart components
├── lib/                 # API actions & utilities
├── hooks/               # Custom hooks
├── public/              # Static assets
└── README.md
⚠️ Notes
Uses CoinGecko free tier (rate-limited)

Charts show historical OHLC data, not live streaming

Some trending items may be NFTs and are handled safely

📞 Contact
Author: Rohan
GitHub: @rohan24may

⭐ If you like this project, consider starring the repo!


---

If you want next, I can:
- adjust wording for **recruiters**
- add **badges** (Next.js, TypeScript, Vercel)
- simplify it to **one-scroll README**

Just tell me 😄
