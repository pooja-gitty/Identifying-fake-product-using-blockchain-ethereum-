# 🛡️ Fake Product Identification using Blockchain (Ethereum + Web3)

This project helps track products from manufacturers to consumers using Ethereum smart contracts. It ensures **product authenticity**, **tamper-proof transaction records**, and **transparent traceability** across the supply chain.

---

## 🚀 Features

- ✅ Add products and sellers by manufacturer  
- ✅ Sell products from manufacturer → seller → consumer  
- ✅ Query seller and product ownership  
- ✅ Consumer can verify authenticity of a product  
- ✅ Blockchain-based immutable ledger using Ganache

---

## 🧰 Tech Stack

- 🔗 **Ethereum Smart Contracts (Solidity)**
- 🌐 **Web3.js** for interacting with contracts
- 🦊 **MetaMask** for transaction signing
- 💻 **Ganache** (local Ethereum test network)
- 🖥️ HTML/CSS + JavaScript (Vanilla frontend)
- 🧪 **Truffle** for contract compilation & migration

---

## 🛠️ How to Run This Project Locally

Follow the steps below to run the app on your local machine:

### 🔧 Step 1: Install Prerequisites

Ensure the following are installed on your system:

- [Node.js and npm](https://nodejs.org)
- [Truffle](https://trufflesuite.com/truffle)

```bash
npm install -g truffle
```

- [Ganache (Desktop)](https://trufflesuite.com/ganache/)
- [MetaMask Chrome Extension](https://metamask.io)

---

### 🧪 Step 2: Start Ganache and Create Workspace

1. Open **Ganache**
2. Click on **New Workspace**
3. Add your local project's `truffle-config.js` to the workspace
4. Ensure the RPC server runs at the default:

```
http://127.0.0.1:7545
```

5. Start the workspace and keep it running in the background
6. Note down one of the **accounts** and its **private key** (you'll use this in MetaMask)

---

### 🦊 Step 3: Set Up MetaMask in Chrome

1. Open the **MetaMask extension** in Chrome  
2. Click **Import Wallet**  
3. Paste the **private key** from any Ganache account  
4. Go to **Settings → Networks → Add Network**  
5. Enter the following:

```
Network Name: Ganache Local
New RPC URL:  http://127.0.0.1:7545
Chain ID:     1337
Currency Symbol: ETH
```

6. Save and **switch to the Ganache Local** network in MetaMask

---

### 📦 Step 4: Install Project Dependencies

In your terminal, navigate to the project directory and run:

```bash
npm install
```

This installs all frontend and web3 dependencies listed in `package.json`.

---

### 🧱 Step 5: Compile and Deploy Smart Contracts

To compile and deploy the contracts to the Ganache blockchain, run:

```bash
truffle compile
truffle migrate --reset
```

This will deploy your contracts to the network running at `http://127.0.0.1:7545`.

---

### 🖥️ Step 6: Run the Frontend

Start your frontend application using:

```bash
npm run dev
```

This will launch your application locally at:

```
http://localhost:3000
```

Open it in your browser, and make sure MetaMask is connected to the Ganache Local network.

---

## 📸 Screenshots



---



---

## 📄 License

This project is open-source under the [MIT License](LICENSE).

---


