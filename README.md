# Insurance Core

Insurance Core is the reference implementation of the **Insurance (SEC)** blockchain.

Insurance is a decentralized cryptocurrency focused on fast, secure and energy-efficient digital payments. Built on a hybrid **Proof of Work (PoW)** and **Proof of Stake (PoS)** consensus model with **Masternode** support, the project was designed to provide a scalable blockchain network while significantly reducing the energy consumption associated with traditional Proof of Work cryptocurrencies.

The network also includes **SwiftTX** instant transactions, decentralized governance and a distributed masternode infrastructure.

---

# 🖥 Desktop Wallet

The screenshots below show the official Insurance Core desktop wallet.

### Wallet Overview

<img width="1366" height="768" alt="wallet Sec 24-06" src="https://github.com/user-attachments/assets/c7a73bf6-87ca-4dc3-bbb5-3963673e8f68" />

### Deposit / Withdraw Integration

<img width="1362" height="667" alt="image" src="https://github.com/user-attachments/assets/175e3b4d-c6ea-436b-84d6-3c425e29d097" />

---

# 🚀 Features

- Hybrid Proof of Work / Proof of Stake consensus
- Masternode network
- SwiftTX instant transactions
- Desktop Wallet (Qt)
- Wallet encryption
- Blockchain synchronization
- Peer-to-peer network
- JSON-RPC interface
- Staking support
- Coin Control
- Transaction history
- Address book
- Wallet backup and recovery

---

# 📊 Coin Specifications

| Parameter | Value |
|-----------|-------|
| Coin Name | Insurance |
| Ticker | SEC |
| Algorithm | Quark |
| Consensus | PoS + Masternodes |
| Block Time | 90 Seconds |
| Max Supply | 7,000,000 SEC |
| Premine | 105,000 SEC (1.5%) |
| Masternode Collateral | 1,000 SEC |
| Masternode Reward | 90% |
| Proof of Stake Reward | 10% |
| Blocks per Day | 960 |
| Maturity | 24 Hours |

---

# 💰 Reward Distribution

| Block Height | Reward | Masternode | PoS |
|--------------|---------|------------|-----|
| 2 → ∞ | 1 SEC | 90% (0.9 SEC) | 10% (0.1 SEC) |

---

# 🛠 Build Dependencies

The project is based on the Bitcoin/Dash codebase and requires the standard development libraries used for building cryptocurrency wallets.

Typical dependencies include:

- C++
- Qt
- Berkeley DB
- Boost
- OpenSSL
- MiniUPnPc
- LevelDB
- Protobuf

---

# 🌐 Network Features

- Decentralized blockchain
- Peer-to-peer communication
- Masternode support
- Wallet encryption
- Instant transaction propagation
- Blockchain synchronization
- RPC interface
- Staking
- Network governance

---

# 📂 Repository Structure

```
src/            Core blockchain source code
doc/            Documentation
share/          Shared resources
depends/        Build dependencies
contrib/        Development utilities
```

---

# ⚙ Build

```bash
git clone https://github.com/FelicioX/insurance-blockchain.git

cd insurance-blockchain

mkdir build

cd build

cmake ..

make -j$(nproc)
```

---

# 📜 Historical Note

Insurance Core represents an independent blockchain project developed using the Bitcoin/Dash architecture.

This repository has been preserved as part of my software engineering portfolio to demonstrate experience with blockchain development, cryptocurrency infrastructure, desktop wallet applications and masternode technology.

---

# 📄 License

Distributed under the MIT License.
