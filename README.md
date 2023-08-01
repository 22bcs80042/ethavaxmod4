# ethavaxmod4
#  create a ERC20 token and deploy it on the Avalanche network for Degen Gaming
This repository is made for my ethereum intermediate avax mod 4 project which is used to create ERC20 token. 

## Problem Statement
The smart contract should have the following functionality:
1.Minting new tokens: The platform should be able to create new tokens and distribute them to players as rewards. Only the owner can mint tokens.
2.Transferring tokens: Players should be able to transfer their tokens to others.
3.Redeeming tokens: Players should be able to redeem their tokens for items in the in-game store.
4.Checking token balance: Players should be able to check their token balance at any time.
5.Burning tokens: Anyone should be able to burn tokens, that they own, that are no longer needed.


## Description
This program  written in Solidity by using a simple contract, solidity is  a programming language used for developing smart contracts on the Ethereum blockchain.
FIRST we create a contract with name DegenToken that is ERC20 token and then make a constructor and intialize with it TokenName and TokenSymbol that is "Degan" and "DGN".
THEN we create event member in my contract that stores argument passed in the transaction log. Then create a mint() function that is used to mint the tokens but only by owner.
THEN we create a transfer() function that is used to transfer the tokens to any other address.Then create a CheckBalance() function that will the reaturn the total token . 
THEN we create a redeem() function that is used to redeem the tokens by the players  for items that are in the game store.
THEN we create a burn() function that is used to burn extra tokens by players that is not in used.
And all this transaction should be visible Snowtrace network that is a  Avalanche network.
## Getting Started

### Executing Program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at (https://remix.ethereum.org/.)

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., error.sol). Copy and paste the following code written by me into the file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set heigher to "0.8.1" (or another compatible version), and then click on the "Compile error.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyContract" contract from the dropdown menu, and then click on the "Deploy" button.

After deployment of  the contract call the function Mint(), Transfer() , Burn() , checkBalance() , and test it on #SnowTrace network. 


## Author

Sulochana

## License

This project is licensed under the MIT License - see the LICENSE file for details
