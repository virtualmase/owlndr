[README.md](https://github.com/user-attachments/files/27914682/README.md)
<div align="center">

```
 ██████╗ ██╗    ██╗██╗     ███╗   ██╗██████╗ ██████╗
██╔═══██╗██║    ██║██║     ████╗  ██║██╔══██╗██╔══██╗
██║   ██║██║ █╗ ██║██║     ██╔██╗ ██║██║  ██║██████╔╝
██║   ██║██║███╗██║██║     ██║╚██╗██║██║  ██║██╔══██╗
╚██████╔╝╚███╔███╔╝███████╗██║ ╚████║██████╔╝██║  ██║
 ╚═════╝  ╚══╝╚══╝ ╚══════╝╚═╝  ╚═══╝╚═════╝ ╚═╝  ╚═╝
```

**Trade AI Agents. Own the Night.**

The official mobile companion for [CreatorBid](https://creatorbid.com) — the premier AI Agent trading protocol on Base.

[![Live on Base](https://img.shields.io/badge/Network-Base%20L2-0052FF?style=flat-square&logo=coinbase&logoColor=white)](https://base.org)
[![Token](https://img.shields.io/badge/Token-BID-7c3aed?style=flat-square)](https://aerodrome.finance)
[![DEX](https://img.shields.io/badge/DEX-Aerodrome-e40421?style=flat-square)](https://aerodrome.finance)
[![Status](https://img.shields.io/badge/Status-LIVE-10b981?style=flat-square)]()
[![Built with Expo](https://img.shields.io/badge/Built%20with-Expo-000020?style=flat-square&logo=expo&logoColor=white)](https://expo.dev)

</div>

---

## 🦉 What is OWLNDR?

OWLNDR is the ultimate mobile command center for the CreatorBid ecosystem on Base. Built for degens who move fast — no more clunky browser tabs, no more missed bids, no more checking leaderboards on desktop.

Real-time leaderboards. One-tap bids. Your full portfolio in your pocket.

> *"Finally. A proper mobile app for Agent trading."*

---

## ✨ Features

### 📊 Live Leaderboard + Podium
Real-time rankings with live on-chain winnings, percentage returns, and fill counts. Know who's winning before anyone else does. Data sourced directly from Base — no fake numbers, no paper trades.

### 🔍 Explore & Filter by Archetype
Search thousands of live AI agents with powerful archetype filters:

| Archetype | Strategy |
|-----------|----------|
| 🦈 **Whale** | High-volume, deep-pocket accumulation |
| 🎯 **Sniper** | Precision entry, rapid exit |
| 📈 **Trendfollower** | Rides momentum signals |
| 🚀 **FomoBuyer** | Chases the breakout move |
| 🐋 **Whale Momentum** | Follows big money flows |
| ⚙️ **Custom** | User-defined strategy rules |

### ⚡ One-Tap Bidding
Instant bidding directly from your connected wallet. Deep-linked to Aerodrome liquidity for BID/USDC pairs on Base.

### 💼 Portfolio Tracking
Total value, 24h P&L, and asset breakdown across USDC, BID, and ETH — always live, always accurate.

### ⭐ Watchlist
Star any agent to track it. Get push notifications on big moves. Never miss a position again.

### 🔗 Native Wallet Integration
Connect and trade in seconds with full Base network support:
- **Brave Wallet** — Native Base chain support
- **Coinbase Wallet** — Native Base chain by Coinbase
- **WalletConnect** — MetaMask, Rainbow & more

### 🎨 Arcturian Design
Dark, premium UI system with haptic feedback, smooth Reanimated animations, and a purple/cyan aesthetic built for the night shift.

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | [Expo](https://expo.dev) + React Native |
| Styling | [NativeWind](https://nativewind.dev) (Tailwind for RN) |
| Animations | [React Native Reanimated](https://docs.swmansion.com/react-native-reanimated/) |
| Data Fetching | [TanStack Query](https://tanstack.com/query) |
| Navigation | [Expo Router](https://expo.github.io/router/) |
| Wallet | WalletConnect v2 / Coinbase Wallet SDK / Brave |
| Chain | [Base](https://base.org) (Chain ID: 8453 · L2 on Ethereum) |
| DEX | [Aerodrome Finance](https://aerodrome.finance) |
| Protocol | [CreatorBid](https://creatorbid.com) AI Agent trading |

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- iOS Simulator / Android Emulator or physical device with Expo Go

### Installation

```bash
# Clone the repository
git clone https://github.com/your-org/owlndr.git
cd owlndr

# Install dependencies
npm install

# Start the development server
npx expo start
```

### Running on Device

```bash
# iOS
npx expo run:ios

# Android
npx expo run:android

# Expo Go (scan QR)
npx expo start
```

### Environment Variables

Create a `.env.local` file in the root:

```env
EXPO_PUBLIC_BASE_RPC_URL=https://mainnet.base.org
EXPO_PUBLIC_CREATORBID_API=https://api.creatorbid.com
EXPO_PUBLIC_WALLETCONNECT_PROJECT_ID=your_project_id
EXPO_PUBLIC_CHAIN_ID=8453
```

---

## 📁 Project Structure

```
owlndr/
├── app/                    # Expo Router screens
│   ├── (tabs)/
│   │   ├── index.tsx       # Home / Leaderboard
│   │   ├── explore.tsx     # Agent explorer + filters
│   │   ├── wallet.tsx      # Wallet connect + portfolio
│   │   └── profile.tsx     # User profile + watchlist
│   └── agent/[id].tsx      # Agent detail page
├── components/
│   ├── ui/                 # Reusable UI components
│   ├── leaderboard/        # Podium, entry cards
│   ├── agent/              # Agent cards, charts
│   └── wallet/             # Wallet connect modals
├── hooks/                  # Custom React hooks
├── lib/
│   ├── api/                # CreatorBid API client
│   ├── chain/              # Base chain config + wagmi
│   └── utils/              # Helpers, formatters
├── constants/
│   ├── theme.ts            # Arcturian color system
│   └── archetypes.ts       # Agent archetype config
└── assets/                 # Images, fonts, icons
```

---

## 🌐 Network & Chain Info

OWLNDR operates exclusively on **Base** (Coinbase L2):

```
Network Name:  Base
Chain ID:      8453
RPC URL:       https://mainnet.base.org
Block Explorer: https://basescan.org
Native Token:  ETH
```

Your wallet must be connected to the Base network to trade agent keys.

---

## 🤝 Partners & Ecosystem

- **[CreatorBid](https://creatorbid.com)** — The AI Agent trading protocol OWLNDR is built for
- **[Aerodrome Finance](https://aerodrome.finance)** — Primary DEX for BID/USDC liquidity on Base
- **[Base](https://base.org)** — Coinbase L2, home chain for OWLNDR
- **[Coinbase Wallet](https://www.coinbase.com/wallet)** — Native wallet integration

---

## 📈 Live Stats

| Metric | Value |
|--------|-------|
| Token | BID |
| Price | $0.009343 |
| Market Cap | $3.60M |
| 24h Change | +12.00% |
| Liquidity | $153.4K |
| DEX | Aerodrome |

*Stats update in real time inside the app.*

---

## 🗺 Roadmap

- [x] Live leaderboard with real-time on-chain data
- [x] Agent explorer with archetype filters
- [x] Wallet connect (Brave, Coinbase, WalletConnect)
- [x] Portfolio tracking (USDC, BID, ETH)
- [x] Watchlist with star/unstar
- [ ] In-app trading (direct bid execution)
- [ ] Agent detail pages with performance charts
- [ ] Push notifications for watchlist alerts
- [ ] Aerodrome swap widget integration
- [ ] Agent of the Day daily feature
- [ ] Social sharing (screenshot your wins)

---

## 🏗 Contributing

Contributions are welcome. Please open an issue first to discuss what you'd like to change.

```bash
# Create a feature branch
git checkout -b feature/your-feature-name

# Commit your changes
git commit -m "feat: add your feature"

# Push and open a PR
git push origin feature/your-feature-name
```

Please follow the existing code style and include tests where applicable.

---

## 📜 License

MIT License — see [LICENSE](./LICENSE) for details.

---

## 🔗 Links

| Resource | URL |
|----------|-----|
| 🌐 Website | [owlndr.xyz](https://owlndr.xyz) |
| 🐦 Twitter / X | [@owlndr](https://x.com/owlndr) |
| 🟣 Farcaster | [/owlndr](https://warpcast.com/owlndr) |
| 💬 Telegram | [t.me/owlndr](https://t.me/owlndr) |
| 📱 App Store | *Coming soon* |
| 🤖 Google Play | *Coming soon* |
| 🏗 CreatorBid | [creatorbid.com](https://creatorbid.com) |
| 🔵 Base Network | [base.org](https://base.org) |

---

<div align="center">

Built on Base · Powered by CreatorBid · Fueled by the night 🦉

**#OWLNDR · #CreatorBid · #AIAgents · #Base**

</div>
