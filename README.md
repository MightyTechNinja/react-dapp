# Basic Sample React DApp Project

This project demonstrates a basic dApp development with React, Ethers.js, Solidity, and Hardhat. I wanted to show you how to build full stack Ethereum dapps using the most up to date resources, libraries, and tooling.

# How to install and run 
1. Clone the repo
```
git clone https://github.com/SmartCoding51/hardhat-react-dapp.git
```
2. Set up keys.json file and install dependencies
```
cd hardhat-react-dapp
cp keys.example.json keys.json
npm install
```
3. Set up .env file in react frontend directory, and install dependencies
```
cp env.example .env
npm install
```
4. Run the app
npm start

# How to start local test network and deploy contract
1. Start the local test node
```
cd hardhat-react-dapp
npx hardhat node
```
2. Deploy the contract
```
npx hardhat run scripts/deploy.js --network localhost
```
3. Update src/App.js with the value of your contract address
4. Run the app
```
cd frontend
npm start
```