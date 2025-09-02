# FomoRush

A decentralized social experiment and game on the TON blockchain, combining game theory, strategy, and community engagement.

## 🎮 Overview

FomoRush is a blockchain-based game where participants collectively influence the duration of a round and compete for a growing prize pool. The game features:

- **FRSH Token**: Native utility token with 50M total supply
- **Staking System**: 9-day staking cycles with TON rewards
- **Referral Program**: Growth incentives and community building
- **Smart Contracts**: Fully decentralized on TON blockchain

## 🏗️ Architecture

### Smart Contracts

- **MainGame**: Core game logic and round management
- **UserGameWallet**: Individual player wallets and key tracking
- **JettonMinterICO**: FRSH token issuance and ICO management
- **JettonWallet**: FRSH token transfers and balances
- **StakeBank**: Staking mechanism and reward distribution

### Key Features

- **Keys Activation**: Primary game action with 30-second timer extension
- **Dividend System**: 43% of activations distributed to key holders
- **Prize Pool**: 37% of activations for round winners
- **Jackpot**: 0.3314% chance per qualifying activation

### Distribution
    - 43% — dividends to key holders
    - 37% — prize pool (pot)
    - 10% — referral program, in case no referrer comes to jackpot
    - 6% — staking pool
    - 2% — community
    - 1% — next round’s pot
    - 1% — jackpot

### 📁 Project Structure

```
├── audit/             # Security audit reports
│   ├── STAKE_AUDIT_REPORT.pdf
│   └── TOKENS_AUDIT_REPORT.pdf
├── contracts/         # FunC smart contracts
│   ├── stake/         # Staking contracts
│   └── tokens/        # Token contracts
```

## 🔧 Configuration

### Contract Parameters

- **Total Supply**: 50,000,000 FRSH
- **ICO Stages**: 5 stages with increasing prices
- **Staking Period**: 9 days
- **Key Price**: Dynamic bonding curve

## 📊 Tokenomics

- **Token Name**: FRSH (FomoRush)
- **Total Supply**: 50,000,000 FRSH
- **Price Range**: 0.005 TON to 0.05 TON
- **Distribution**: 100% to investors (no team allocation)

## 🔒 Security

- **AI Audited**: All contracts undergo security audits
- **Open Source**: Transparent and verifiable code
- **Decentralized**: No centralized control points
- **Access Control**: Proper authorization mechanisms

## 📚 Documentation

- [Whitepaper](https://fomorush.io/whitepaper.pdf) - Complete project documentation
- [Tokenomics](https://fomorush.io/tokenomics.pdf) - Detailed token economics

## 🔗 Links

- **Website**: [fomorush.io](https://fomorush.io)
- **Telegram**: [@FomoRushOfficial](https://t.me/FomoRushOfficial)

---

**Invest Responsibly**: FomoRush is a decentralized game on the TON blockchain involving token purchases (FRSH) and gameplay with financial risks. Participation, including buying FRSH tokens, activating keys or staking, is speculative and volatile. You may lose your investment. Past performance is not indicative of future results. Conduct your own research and consult financial advisors before participating. FomoRush is not financial advice. Only risk what you can afford to lose.
