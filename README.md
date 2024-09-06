

# BetterFund: Crowdfunding Platform Powered by Ethereum Blockchain

**BetterFund** is a decentralized crowdfunding platform built on the Ethereum blockchain, designed to provide enhanced security, transparency, and global accessibility. The platform is live on the Rinkeby Test Network and can be accessed [here](https://betterfund.vercel.app/).

## Problem Statement and Solution

Crowdfunding has become a crucial method for raising funds, especially during crises like the COVID-19 pandemic. However, existing platforms have several limitations:

1. **Security**: Traditional platforms can be vulnerable to hacking despite encryption measures. Blockchain offers unparalleled security, as it has never been compromised.
   
2. **Transparency and Anti-Fraud**: Current platforms lack transparency regarding fund usage, leading to scams. Our platform ensures full transparency at every stage of the funding process to prevent misuse.

3. **Global Contribution**: Many platforms restrict contributions to specific countries. Using blockchain technology, BetterFund enables anyone in the world to contribute quickly and easily.

We were inspired by the [CryptoRelief initiative](https://www.cryptorelief.in), which raised nearly $1 billion for COVID relief in India through transparent and global crowdfunding.

## Tech Stack

- **Frontend**: Next.js, Chakra UI
- **Blockchain**: Solidity, Web3.js

## How to Install and Run Locally

1. **Fork and Clone the Project**:
   ```bash
   git clone https://github.com/your-username/BetterFund.git
   cd BetterFund
   ```

2. **Install Dependencies**:
   ```bash
   yarn install
   ```

3. **Run the Application**:
   ```bash
   yarn dev
   ```

## Prerequisites to Create a Campaign or Contribute

1. **Install MetaMask** as a Google Chrome Extension and create an account.
2. **Get Rinkeby Test Ether**:
   - Share your Ethereum address on social media to request Ether: [Rinkeby Faucet](https://faucet.rinkeby.io/)
   - Alternatively, get free Ether by providing your Ethereum address: [Rinkeby Faucet](http://rinkeby-faucet.com/)

## How to Deploy Your Own Contract

1. **Create an Account on [Infura](https://infura.io/)**.
2. **Create a `.env` File** in the Ethereum directory with the following variables:
   ```bash
   MNEMONIC='Your mnemonic code'
   LINK='Your Infura endpoint link'
   ```
3. **Modify Solidity Files** as needed.
4. **Compile the Contract**:
   ```bash
   node compile.js
   ```
5. **Deploy the Contract** by navigating to the smart-contract directory and running:
   ```bash
   node deploy.js
   ```
   - Copy the contract deployment address and update it in the `factory.js` file.
6. **Update `web3.js`** with your Infura endpoint link.

## Deploying on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new). For more details, refer to the [Next.js deployment documentation](https://nextjs.org/docs/deployment).

## Screenshots

Here are some screenshots to help you understand the platform better:

### Home Page
![Home Page](https://user-images.githubusercontent.com/49694914/119785319-ba2cf580-beec-11eb-92f4-73c5d686e058.png)

### Campaign Page
![Campaign Page](https://user-images.githubusercontent.com/49694914/119785442-d2047980-beec-11eb-8cfd-ac246582a4af.png)

### Create Campaign Page
![Create Campaign Page](https://user-images.githubusercontent.com/49694914/119785522-e47eb300-beec-11eb-88f8-8cc65a7c42ec.png)

### Withdrawal Request Page
![Withdrawal Request Page](https://user-images.githubusercontent.com/49694914/119785617-ff512780-beec-11eb-961a-b7857665f031.png)

### New Withdrawal Request Page
![New Withdrawal Request Page](https://user-images.githubusercontent.com/49694914/119785671-0d06ad00-beed-11eb-9554-6786c58cc19d.png)

## Detailed Documentation

- [Project Report](https://docs.google.com/document/d/1_CdJ5pEimTrejDSBnq9Ze6kz2BcKJ6qtiikqWs0rglc/edit?usp=sharing)
- [Presentation](https://docs.google.com/presentation/d/1X5CMPB_Mece3C7NI5dvB7eTKJjbn0E70NY3pjVZn5ho/edit?usp=sharing)

