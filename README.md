# Ethereum based PetShop

* It is an adoption system for a pet shop, the customers are provided with an Web-UI to adopt the pets using digital money called ethers,provided by testrpc and the public key of the customer is stored in blockchain to track the transactions.
* Build using Ethereum, Truffle and Metamask.
* This is my first dapp and helped me to understand blockchain, ethereum, solidity, truffle framework and metamask.
______________________

#### Installation:

- npm
- git
- To install truffle:
*(npm install -g truffle)*

#### Using Truffle box:
*truffle unbox pet-shop*

#### Smart contract:
Write the smart contract in solidity
* *Adopiton.sol*
* *migration.sol*

#### Run the ethereum testrpc in terminal
*testrpc*
(It is simulation that provides us with 10 fake accounts with 100 ethers for each account.)

#### Compile:
*truffle compile*

#### Migration:
To migrate the smart contracts into the blockchian.

*truffle migrate*

#### Test:
After migrating, test the contracts by providing input values and checking if necessary output is obtained.

*truffle test*

#### Metamask:
Use the mnenomic and an account provided in testrpc in metamask, it is chrome plugin which provides an user interface to buy or sell products using ethers.

#### Run the dapp:
Start the local web server and run the dapp.

*npm run dev*

______________________






