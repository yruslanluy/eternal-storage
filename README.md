Made by [Crypto Chyvak](https://t.me/cryptochy)

This contract allows users to store up to 31 bytes (31 length string, only English and numbers) of data in string format forever. No one except you can change your storage data

**Warning! All data in blockchain is public, don't store private information**

This contract is public available on BSC network: https://bscscan.com/address/0xfb2a35c00e7bfbb46ccedfc2c5c03164717cafc1#writeContract

## Functions

 - **write** - write string (only English and numbers) up to 31 symbols to blockchain storage. You pay only gas fee (approx 45k gas)
 - **rewrite** - delete old string and insert new string to its place. This is a paid function, you need to pay at least 0.001 BNB (or ETH on Ethereum) to call this function + gas fee (approx 30k gas)
 - **read** - read data from your storage cell. Free function
 - **withdraw** - withdraw funds from smartcontract, only for owner of smartcontract

## How to write data

- Open smartcontract in explorer
- Select "Contract" > "Write Contract"
- Connect Web3 wallet
- Select "write"
- In field "_data" enter data that you want to store in blockchain, then click "Write" button

Every data storage in blockchain paid, so you will need to pay only blockchain gas fees

## How to read your storage cell

- Open smartcontract in explorer
- Select "Contract" > "Read Contract"
- Select "cells" > input your wallet address, and then click "Query"

## How to rewrite your data

- Select "Contract" > "Write Contract"
- Connect Web3 wallet
- Select "rewrite" function
- In field "rewrite" enter any amount that you will pay to contract (at least 0.001 BNB (or ETH on Ethereum)), then in field "_data" enter new data and click "Write" button

This function is also paid (smartcontract owner fee + blockchain gas fee)

To delete your data select "rewrite" function, in field "rewrite" enter any amount that you will pay to contract (at least 0.001 BNB (or ETH on Ethereum)), then in field "_data" enter space and click "Write" button


EternalStorage. Open MIT license
By [cryptochy](https://t.me/cryptochy). 2022
 
