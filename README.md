# 🇺🇸 Old Glory Token DApp

**Autonomous Treasury Protocol on PulseChain**

A patriotic, sovereign DeFi interface for the Old Glory Token (OGT+) - featuring immutable smart contracts, autonomous CST yield distribution, and zero governance dependencies.

![Old Glory Token](assets/OG_ELITE.png)

## 🎯 Features

- **Real-time Token Stats** - Supply, burns, deflation metrics, and treasury balance
- **CST Yield Claiming** - Pull-based reward system with countdown timers
- **LP Bonus Tracking** - 2x share multiplier for liquidity providers
- **Autonomous Operation** - No admin keys, no governance, pure self-sovereignty
- **PulseChain Native** - Built specifically for the PulseChain ecosystem

## 🚀 Live Demo

Visit: [https://oldglorytoken.com](https://oldglorytoken.com)

## 📋 Contract Addresses

- **OGT+ Token**: [`0x63aa45017513B9D5bD7252F0C4752f23f77f7043`](https://scan.pulsechain.com/address/0x63aa45017513B9D5bD7252F0C4752f23f77f7043)
- **LP Pair (OGT+/WPLS)**: [`0x09Df81e6CD69F75c769402fa115c529BDc035507`](https://scan.pulsechain.com/address/0x09Df81e6CD69F75c769402fa115c529BDc035507)
- **CST Reward Token**: [`0x600136dA8cc6D1Ea07449514604dc4ab7098dB82`](https://scan.pulsechain.com/address/0x600136dA8cc6D1Ea07449514604dc4ab7098dB82)

## 🛠️ Technology Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (no framework dependencies)
- **Web3 Integration**: ethers.js v5.7.2
- **Blockchain**: PulseChain (Chain ID: 369)
- **Design**: Patriotic theme with metallic accents and animated effects

## 📦 Installation & Deployment

### Option 1: Direct Deployment

1. Clone this repository:
```bash
git clone https://github.com/YOUR_USERNAME/old-glory-token-dapp.git
cd old-glory-token-dapp
```

2. Add the logo image to `/assets/OG_ELITE.png`

3. Deploy to any static hosting:
   - **GitHub Pages**: Enable in repo settings
   - **Netlify**: Drag and drop the folder
   - **Vercel**: Import from GitHub
   - **Traditional hosting**: Upload via FTP/cPanel

### Option 2: Run Locally

Simply open `index.html` in your browser. That's it!

```bash
# Or use a local server
python -m http.server 8000
# Then visit http://localhost:8000
```

## 🎨 Customization

All styling is contained within `index.html` using CSS variables:

```css
:root {
    --navy: #0a1628;
    --red: #c41e3a;
    --white: #ffffff;
    --blue: #002868;
    --silver: #c0c0c0;
    --gold: #d4af37;
}
```

## 🔐 Security

- **No backend required** - Pure client-side application
- **Read-only operations** - Only writes are user-initiated claims
- **MetaMask integration** - Users maintain custody of their keys
- **Immutable contracts** - No admin functions or upgradability

## 📊 Key Metrics Displayed

### Global Stats
- Total Supply
- Total Burned (to address `0x369`)
- Deflation Rate
- Total Shareholders
- CST Distributed
- Treasury Balance

### User Dashboard
- OGT+ Balance
- LP Token Balance
- Share Count
- Unpaid CST Yield
- Next Claim Countdown

## 🎯 How It Works

1. **Connect Wallet** - MetaMask or Web3 wallet on PulseChain
2. **View Stats** - Real-time protocol metrics
3. **Claim Rewards** - Pull-based CST distribution (1 hour cooldown)
4. **LP Bonus** - Liquidity providers receive 2x share weight

## 🏗️ Protocol Architecture

Old Glory Token implements:
- **Autonomous Treasury**: Self-executing buy-and-burn mechanism
- **Pull-Based Rewards**: Gas-efficient claiming (90k gas vs 390k auto-payout)
- **LP Incentivization**: 2x share multiplier for liquidity providers
- **Immutable Design**: No governance tokens, no admin keys

## 📝 License

MIT License - Feel free to fork and modify

## 🤝 Contributing

Contributions welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request

## 🔗 Links

- **Website**: [oldglorytoken.com](https://oldglorytoken.com)
- **Contract**: [PulseScan](https://scan.pulsechain.com/address/0x63aa45017513B9D5bD7252F0C4752f23f77f7043)
- **Developer**: ELITE TEAM6

## ⚠️ Disclaimer

This DApp is provided as-is. Always DYOR (Do Your Own Research) before interacting with any smart contracts. The protocol operates autonomously without any central control or guarantees.

---

**Built with 🇺🇸 for the PulseChain community**

*Autonomous • Immutable • Sovereign*
