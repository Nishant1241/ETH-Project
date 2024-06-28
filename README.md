# Project Title

My smart contract

## Description

The `MyToken` contract defines a basic token with the name "META" and abbreviation "Metacrafters". It utilizes a mapping to keep track of token balances for each address. The `mint` function increases the total token supply and adds tokens to a specified address. On the other hand, the `burn` function reduces the total supply and removes tokens from an address if the balance is sufficient. We have to try minting and burning few tokens to check if our program works aptly and side by side it needs to update our balance . there is a condition that the tokens can only be burnt if it is less than or equal to the balance . for that we have used an if statement . 

## Getting Started

### Installing

To run this program search on the internet remix.ethereum.org this will take you to the ethereum workplace that I have used to create my smart contract named `MyToken`. 

### Executing program

For execution :
* Just go on to the solidity compiler option that is on the left hand side bar and turn on the autocompile . 
* Then go to the deploy option below the solidity compiler and find the deploy button there .
* Then find the file name below in the deploy section then click on it .
* Now copy an address from the accounts section and paste it in the address column .
* Now give certain numbers to mint and to burn and keep checking the balance to check validity of contaract.

## Authors

Kumar Nishant

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
