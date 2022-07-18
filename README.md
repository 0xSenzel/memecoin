# Memecoin Dapp

A simple Dapp to initialize a token providing minting, burning and transfering functionality. Connect through metamask wallet with Rinkeby network to test the functionality.

## [Live Preview:](https://memecoin.janus9.repl.co)

<p align="center">
<img src="https://user-images.githubusercontent.com/62827213/179525792-11680eed-f3fd-4b08-b868-1d7ebe0ed436.PNG" width=60% height=30%>
</p>
<p align="center">
    <em>Dapp Landing Page</em>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/62827213/179525917-fdcfa28b-6080-4d89-9659-3f2b247f1792.PNG" width=60% height=30%>
</p>
<p align="center">
    <em>Connected Wallet</em>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/62827213/179525896-6d4ed5ff-ec57-4996-ad46-63dd35780299.PNG" width=60% height=30%>
</p>
<p align="center">
    <em>After initializing Token</em>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/62827213/179526134-a1d04110-daae-44af-bf41-c4c03f4ca35e.PNG" width=60% height=30%>
</p>
<p align="center">
    <em>After Minting Token</em>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/62827213/179526241-3f441814-3863-4d02-9df4-30c8593636bd.PNG" width=60% height=30%>
</p>
<p align="center">
    <em>After Burning Token</em>
</p>

## Project Setup
```
npm init -y
npm install --save-dev hardhat
npm hardhat
```
### HardHat Environment
Compiling Smart Contract
```
npx hardhat compile
```
Deploying to your local Hardhat Blockchain
1. Start a Hardhat Node
   ```
   npx hardhat node
   ```
2. Deploy Smart Contract in `localhost` or `rinkeby` network
    ```
    npx hardhat run --network localhost scripts/deploy.js
    ```
    ```
    npx hardhat run --network rinkeby scripts/deploy.js
    ```
