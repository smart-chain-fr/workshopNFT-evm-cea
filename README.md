# workshop-nft
Short tuto to deploy an ERC-721 contract, mint an NFT and publish it on Opensea on Mumbai testnet


## 1) Install Metamask
Go to https://metamask.io/download/ and install the Metamask plugin for your web browser.

## 2) Create a wallet
Open the Metamask plugin and follow the steps to create a wallet. Don't forget to write down your recovery phrase. It will allow you to recover access to your funds if you lose access to your computer for any reason.

## 3) Add Mumbai Testnet network
Authorize Testnet networks in Metamask settings. Add a new network, enter the following data:<br>
Network Name: Mumbai Testnet<br>
New RPC URL: https://rpc-mumbai.maticvigil.com<br>
Chain ID: 80001<br>
Currency Symbol: MATIC<br>
Block Explorer URL: https://polygonscan.com/

## 4) Get MATIC from the faucet
Go to https://mumbaifaucet.com/ and paste your address from your Metamask account. The transfer can take time depending on the congestion on the faucet.
While waiting for your MATIC, you can continue with the next steps.

## 5) Open the template on Remix IDE
Go to https://remix.ethereum.org/.
Choose "LOAD FROM: Gist" and paste this ID `6c6e9e24da34d014215a6632bc077f04`. It will open a DemoERC721.sol file. This is a simple implementation of the ERC721 standard with an auto-incrementing minting function. It is based on OpenZeppelin reference implementation.

## 6) Deploy the contract, mint an NFT and publish it on testnet OpenSea
On stage explanations...<br>
https://testnets.opensea.io/

## Tutos
Here are a series of easy and clear tutos to create your NFTs : <br>
https://www.gun.io/blog/how-to-create-an-nft-from-scratch <br>
https://www.gun.io/blog/blog/easy-nft-development <br>
https://www.gun.io/blog/easy-nft-blockchain-smart-contract
