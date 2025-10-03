<img width="332" height="502" alt="final version of the FundMe50 contract" src="https://github.com/user-attachments/assets/aa052e24-6ffe-419e-8bbb-84d490b1c58e" />

# 🥳🥳 Contract is now Verified and Published 
Now anyone can interact with the contract (`https://sepolia.etherscan.io/address/0x027c7a6b6e8793c239df22ee69cd7dca950e95ea#writeContract`)

# FundMe50-Solidity
This is a simple crowdfunding contract built in Solidity.  (contract hash - 0x027c7a6b6e8793c239df22ee69cd7dca950e95ea on sapolia testnet)

Anyone can fund the contract with ETH as long as the amount is worth more than $50.  
Only the contract owner (the one who deployed it) can withdraw the funds.  

## Features
- Minimum contribution: $50 (using Chainlink price feeds).
- Keeps track of funders and the amount they contributed.
- Only owner can withdraw funds.

## Contract Details
- Network: Sepolia Testnet  
- Deployed Address: `0x027c7a6b6e8793c239df22ee69cd7dca950e95ea`
- https://sepolia.etherscan.io/address/0x027c7a6b6e8793c239df22ee69cd7dca950e95ea

## How to Use
- Don't use my work.  
- Just kidding 😅 — feel free to clone this repo.  
- Deploy `FundMe.sol` on the **Sepolia testnet**.  
- If you want to deploy on another network, make sure to update the price feed address in  
  `AggregatorV3Interface(0x694AA1769357215DE4FAC081bf1f309aDC325306)`  
  because the address I used is specific to the Sepolia testnet.  
- Apart from that, the rest of the code works fine on any EVM-compatible chain.
