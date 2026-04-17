# 🚀 BlockBase Project

A simple decentralized application (dApp) built using Solidity and JavaScript that allows users to interact with a smart contract and retrieve their stored name using their wallet address.

## 📌 Features

### 🔗 Solidity Feature

Get Your Own Name

Implemented a function getMyName() in the smart contract.  
Fetches the name associated with the connected wallet address.

~~~solidity
function getMyName() public view returns (string memory) {
    return people[msg.sender].name;
}
~~~

### 🌐 JavaScript Feature

Display Connected Wallet Address

Detects and connects to MetaMask.  
Displays the currently connected user's wallet address on the frontend.

## 🛠️ Tech Stack

Solidity – Smart contract development  
JavaScript – Frontend logic  
MetaMask – Wallet integration  
Ethereum Blockchain – Deployment environment  

## ⚙️ How It Works

User connects their wallet using MetaMask.  
The app captures the wallet address.  
Smart contract maps wallet address → user name.  
Calling getMyName() returns the stored name for that wallet.

## 📂 Project Structure

~~~bash
blockbase-project/
│── contracts/        # Solidity smart contracts
│── frontend/         # JavaScript frontend
│── scripts/          # Deployment scripts
│── README.md
~~~

## 🚀 Getting Started

### 1. Clone the Repository

~~~bash
git clone https://github.com/s-asabe/blockbase-project.git
cd blockbase-project
~~~

### 2. Install Dependencies

~~~bash
npm install
~~~

### 3. Run the Project

~~~bash
npm start
~~~

## 🔐 Requirements

MetaMask extension installed  
Ethereum test network (like Sepolia/Goerli)  
Node.js installed  

## 📸 Features Preview

✅ Wallet connection  
✅ Display wallet address  
✅ Fetch user-specific data from blockchain  

## 📌 Future Improvements

Add UI for setting/updating name  
Improve frontend design  
Deploy on mainnet  
Add authentication and validations  

## 🤝 Contributing

Feel free to fork this repo and improve it. Pull requests are welcome!

## 📄 License

This project is open-source and available under the MIT License.
