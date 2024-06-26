       REQUIREMENTS
    1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
    2. Your contract will have a mapping of addresses to balances (address => uint)
    3. You will have a mint function that takes two parameters: an address and a value. 
       The function then increases the total supply by that number and increases the balance 
       of the “sender” address by that amount
    4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
       It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
       and from the balance of the “sender”.
    5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal 
       to the amount that is supposed to be burned.
*****************************************************************************
        DESCRIPTION 

MyToken Smart Contract
Simple overview of use/purpose.

Description
MyToken is a simple ERC-20 compliant smart contract deployed on the Ethereum blockchain. It allows for the creation, minting, and burning of a custom token named META (MTA). The contract includes functions for minting new tokens to specific addresses and burning tokens from specific addresses, with appropriate checks and balances.

Getting Started
Installing
Clone the repository or download the smart contract file.

git clone MyToken Smart Contract
Simple overview of use/purpose.

Description
MyToken is a simple ERC-20 compliant smart contract deployed on the Ethereum blockchain. It allows for the creation, minting, and burning of a custom token named META (MTA). The contract includes functions for minting new tokens to specific addresses and burning tokens from specific addresses, with appropriate checks and balances.

Getting Started
Installing
Clone the repository or download the smart contract file.

git clone gh repo clone coderdevesh2024/Assignment-2
Open the project in your preferred Solidity development environment, such as Remix IDE.

Ensure you have the necessary development tools installed, including Node.js, npm, and Truffle.

Executing program
Compile the smart contract using Remix IDE or your preferred Solidity compiler.

Deploy the contract to your preferred Ethereum network (e.g., Ethereum mainnet, Ropsten, Rinkeby).

Interact with the deployed contract using Remix IDE or a web3 interface.

Example commands:

// Minting tokens
myTokenInstance.mint("0xYourAddress", 100);

// Burning tokens
myTokenInstance.burn("0xYourAddress", 50);
Help
For common issues or troubleshooting, please refer to the following:

Ensure you have sufficient ETH for gas fees when deploying and interacting with the contract.
Make sure the contract address and ABI are correctly referenced in your web3 interface.
// If you encounter issues with deployment or interaction
npx truffle migrate --reset
Authors
Contributors names and contact info

Yash Dhiman @theyashdhiman
License
This project is licensed under the MIT License - see the LICENSE.md file for details.
Open the project in your preferred Solidity development environment, such as Remix IDE.

Ensure you have the necessary development tools installed, including Node.js, npm, and Truffle.

Executing program
Compile the smart contract using Remix IDE or your preferred Solidity compiler.

Deploy the contract to your preferred Ethereum network (e.g., Ethereum mainnet, Ropsten, Rinkeby).

Interact with the deployed contract using Remix IDE or a web3 interface.

Example commands:

// Minting tokens
myTokenInstance.mint("0xYourAddress", 100);

// Burning tokens
myTokenInstance.burn("0xYourAddress", 50);
Help
For common issues or troubleshooting, please refer to the following:

Ensure you have sufficient ETH for gas fees when deploying and interacting with the contract.
Make sure the contract address and ABI are correctly referenced in your web3 interface.
// If you encounter issues with deployment or interaction
npx truffle migrate --reset
Authors
Contributors names and contact info

Devesh Gaur @coderdevesh2024
License
This project is licensed under the MIT License - see the LICENSE.md file for details.
