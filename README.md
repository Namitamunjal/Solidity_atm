# Overview

For this project, create a simple contract with 2-3 functions. Then show the values of those functions in frontend of the application.

This project is a simple React application that serves as a basic Ethereum-based ATM (Automated Teller Machine) interface. The project allows users to connect their MetaMask wallet and interact with a deployed smart contract to perform deposit and withdrawal operations using Ethereum.

Here's an overview of the main features and functions:

# State Variables used :

The project uses useState to manage four state variables: ethWallet, account, atm, and balance.
1. ethWallet: Holds the MetaMask wallet instance (if available).
2. account: Represents the user's Ethereum account address.
3. atm: Represents the instance of the deployed ATM smart contract.
4. balance: Stores the user's balance fetched from the smart contract.

# Smart Contract Interactions:

~ The project connects to the MetaMask wallet, retrieves the user's Ethereum account, and stores it in the account state variable.
~ The atmContract is instantiated using the ABI and the contract address. It enables interaction with the deployed smart contract.
~ The project provides functions for depositing and withdrawing 1 ETH from the smart contract.
The user's account balance is fetched from the smart contract and displayed.


# To Get the code running

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. Typically at http://localhost:3000/


# Deployment Environment
This contract can be deployed in any version of solidity between 0.7.0 to 0.9.0.

# Author
Namita Munjal

namitamunjal27@gmail.com
