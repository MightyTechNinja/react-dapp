# Basic Sample React DApp Project

This project demonstrates a basic dApp development with React, Ethers.js, Solidity, and Hardhat. I wanted to show you how to build full stack Ethereum dapps using the most up to date resources, libraries, and tooling.

# How to install and run 
1. git clone https://github.com/SmartCoding51/hardhat-react-dapp.git
2. cd hardhat-react-dapp
```
copy keys.example.json to keys.json, and paste your infura key & account private key
npm install
```
3. cd frontend
```
copy env.example to .env, and paste your infura key & account private key
npm install
```
4. npm start

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