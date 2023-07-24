# ETH ATM and Crypto investment calculator.

This is a simple React component for a ETH ATM application. It allows users to connect their MetaMask wallet, view their account balance, deposit custom and withdraw custom ETH.Additionally, users can use the crypto investment calculator to estimate the potential value of their investment over a specified duration.

## Features

The ETH ATM component provides the following features:

- Connect your MetaMask wallet by clicking the "Connect" button.
- Deposit funds by entering the desired amount in ETH and clicking the "Deposit" button.
- Withdraw funds by entering the withdrawal amount and clicking the "Withdraw" button.
- Use the crypto investment calculator to estimate the potential investment value:
- Enter the principal amount (in ETH) you wish to invest.
- Set the annual interest rate (in percentage).
- Specify the investment duration (in years).
- Click the "Calculate Investment" button to see the estimated value after the specified duration.


## Setup

After cloning the github, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. 
Typically at http://localhost:3000/
