# Upgradeable NFT contract

This project demonstrates a method where contracts can be upgraded add newer functionalities as opposed to traditional contracts where the contract is unchangeable.  

It uses a proxy contract which delegates call to a implementation contract.The implementation contract always uses the storage of the proxy contract to update or fetch data related to the later interactions.These implementation contracts can later be changed by introducting later versions.



Try running some of the following tasks:

To install dependencies
```shell
npm install
```  

To compile the contract
```shell
npx hardhat compile 
``` 
To deploy the intial version of the contract(In the example contract, any user can mint NFT's)
```shell
npm hardhat run scripts/deploy.js
``` 
To deploy the updated version of the contract(In the example contract,minting NFT is limited to the owner)
```shell
npm install
``` 

