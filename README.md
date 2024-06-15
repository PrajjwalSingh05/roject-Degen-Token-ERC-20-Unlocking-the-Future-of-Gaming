# Project Title: DegenToken
# Description
* This project defines a simple token contract called DegenToken with the following features:

# Public Variables:
* REDEMPTION_RATE: Constant defining the rate at which tokens can be redeemed for in-game items.
* swordsOwned: A mapping to keep track of the number of swords owned by each address.
# Functions:
* mintTokens(address to, uint256 amount): Allows the owner to mint new tokens and distribute them to players.
* transferTokens(address to, uint256 amount): Enables players to transfer their tokens to others.
* redeemSword(uint256 quantity): Allows players to redeem their tokens for swords in the in-game store.
* checkBalance(address account): Lets players check their token balance at any time.
* burnTokens(uint256 amount): Allows anyone to burn their tokens that are no longer needed.
* checkSwordsOwned(address user): Lets players check how many swords they own.
# Getting Started
* To run this program, you can use Remix, an online Solidity IDE:
 * Go to the Remix website:

* Visit Remix IDE.
* Create a new file:

* Click on the "+" icon in the left-hand sidebar.

* Compile the Code
* Open the "Solidity Compiler" tab:

* Click on the "Solidity Compiler" tab in the left-hand sidebar.
* Set the Compiler version:

* Compile the contract:

* Click on the "Compile DegenToken.sol" button.
* Deploy the Contract
* Open the "Deploy & Run Transactions" tab:

* Click on the "Deploy & Run Transactions" tab in the left-hand sidebar.

# Authors
Prajjwal Singh

# License
This project is licensed under the MIT License - see the LICENSE.md file for details.
