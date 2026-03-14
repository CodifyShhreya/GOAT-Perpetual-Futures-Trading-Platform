# GOAT-Perpetual-Futures-Trading-Platform
GOAT-Perpetual-Futures-Trading-Platform is a decentralized finance (DeFi) protocol built on Monad, enabling perpetual trading, staking, and liquidation mechanics. It leverages Scaffold-ETH 2 for rapid development and a seamless developer experience.

## 🏗 Built with Scaffold-ETH 2

Parallel Perps is developed using the **Scaffold-ETH 2** framework, which provides:

- **📜 Smart Contract Hot Reload**: Automatic updates to the frontend as contracts are modified.
- **🪝 Custom Web3 Hooks**: Simplified interactions with contracts using TypeScript.
- **🧱 Pre-built Web3 Components**: Quickly assemble UI components for blockchain interactions.
- **🔥 Burner Wallet & Local Faucet**: Instantly test transactions and contracts.
- **🔐 Wallet Integration**: Supports various wallet providers like MetaMask and WalletConnect.

## 📂 Folder Structure

```
parallel-perps/
├── packages/
│   ├── hardhat/            # Smart contract development
│   │   ├── contracts/      # Solidity smart contracts
│   │   ├── deploy/         # Deployment scripts
│   │   ├── hardhat.config.ts # Hardhat configuration
│   ├── nextjs/             # Frontend application
│   │   ├── app/            # Next.js app pages
│   │   ├── components/     # Reusable UI components
│   │   ├── scaffold.config.ts # Scaffold-ETH configuration
│   ├── subgraph/           # (Optional) Graph Protocol subgraph
```

## 🚀 Quickstart

### 1. Install dependencies

```sh
cd parallel-perps
yarn install
```

### 2. Start a local blockchain

```sh
yarn chain
```

### 3. Deploy smart contracts

```sh
yarn deploy
```

### 4. Run the frontend

```sh
yarn start
```

Visit `http://localhost:3000` to interact with Parallel Perps.

## 🛠 Development

- **Smart Contracts:** Edit contracts in `packages/hardhat/contracts`
- **Frontend:** Modify the UI in `packages/nextjs/app/page.tsx`
- **Deployment Scripts:** Customize scripts in `packages/hardhat/deploy`
- **Testing:** Run smart contract tests with `yarn hardhat:test`

## 📖 Documentation

For a deep dive into Scaffold-ETH 2, visit the [official documentation](https://docs.scaffoldeth.io).

## 🤝 Contributing

We welcome contributions! Please check the `CONTRIBUTING.md` for guidelines.

## 🔗 Links

- Project Website: [Coming soon]
- Scaffold-ETH 2: [https://scaffoldeth.io](https://scaffoldeth.io)
