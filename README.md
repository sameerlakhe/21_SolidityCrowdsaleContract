# Unit 21: Martian Token Crowdsale

![alt=""](Images/application-image.png)

## Background

Developing a monetary system for the new Mars colony based on blockchain technology and define a new cryptocurrency named **KaseiCoin**. (Kasei means Mars in Japanese.)

KaseiCoin will be a fungible token that’s ERC-20 compliant. Launch a crowdsale that will allow people who are moving to Mars to convert their earthling money to KaseiCoin.


## Instructions

The steps for this assignment are divided into the following subsections:

1. Create the KaseiCoin Token Contract

2. Create the KaseiCoin Crowdsale Contract

3. Create the KaseiCoin Deployer Contract

4. Deploy and Test the Crowdsale on a Local Blockchain


Note that the provided starter files for this homework assignment contain a `pragma` statement for Solidity version 0.5.0. 
However, there were errors compiling the files with compiler version 0.5.0 and version 0.5.5 was used to compile.

Created a fungible token that’s ERC-20 compliant and minted by using a `Crowdsale` contract from the OpenZeppelin Solidity library.

The crowdsale contract thus created will manage the entire crowdsale process. 
This process will allow users to send ether to the contract and receive KaseiCoin tokens, or **KAI**, in return.
The contract will automatically mint the tokens and distribute them to a buyer in one transaction.


### Compile KaseiCoin Token Contract
![alt="Compiled KaseiCoin Solidity contract"](Images/1_Compiled_KaseiCoin_sol.png)
-
		
### Compile KaseiCrowdsale  Contract
![alt="Compiled KaseiCrowdsale Solidity contract"](Images/2_Compile_CrowdSale_contract.png)					
-
	
### Compile KaseiCrowdsale Deployer Contract
![alt="Compiled KaseiCoin deployer"](Images/3_Compile_CrowdSaleDeployer.png	)	
-

### Select the Injective-Metamask as provider
![alt="Prepare to deploy KaseiCrowdsaleDeployer"](Images/4_1_PrepareToDeployKaseiDeployer.png)		
-
		
### Deploy and confirm transaction in Metamask
![alt="Use Injective-Metamask as provider"](Images/4_2_UseInjectiveToDeployOnGanacheUsingMetamask.png)		
-

### Check if deployment is success
![alt="Check if deployment is success"](Images/4_3_Successful_deployment_of_KaseiDeployer.png)
-

###  Get address of KaseiCoin contract and KaseiCoinCrowdsale contract from public variables in deployer contract
![alt="Get address of KaseiCoin contract and KaseiCoinCrowdsale contract"](Images/5_getAdrressOfKaseiToken_KaseiCrowdsaleContractFromDeployer.png)
-

###  Check initial balances in Ganache accounts
![alt="Check initial balances in Ganache accounts"](Images/6_initial_ganache_balances.png)
-

###  Verify balance in Metamask connected to Ganache local blockchain
![alt="Verify balance in Metamask connected to Ganache local blockchain"](Images/7_Initial_metamask_balance.png)
-

###  Load crowdsale contract using address from deployer public variable
![alt="Load crowdsale contract using address from deployer public variable"](Images/8_loadCrowdsaleContractUsingAtAddress.png)
-

###  Load KaseiCoin contract using adddress from deployer public variable
![alt="Load KaseiCoin contract using adddress from deployer public variable"](Images/9_Check_KaseiCrowdsale_ContractDeployed.png)
-

###  Buy tokens using loaded crowdsale using buyToken button
![alt="Buy tokens using loaded crowdsale using buyToken button"](Images/10_buyTokensFromCrowdsale.png)
-
					
###  Confirm token purchased					
![alt="Confirm token purchased"](Images/11_ConfirmTokensRaised.png)
-
		
###  Load KaseiCoin contract using address from crowdsale contract							
![alt="Load KaseiCoin contract using address from crowdsale contract"](Images/12_LoadKaseiCoinContract.png)
-
					
###  Verify total coins associated with account	
![alt="Verify total coins associated with account"](Images/13_CheckBalanceAtKaseiCoinContract.png	)
-

### Link to the video on youtube that provides an overview of the application

[![Watch the video](Images/Youtube_thumbnail.png)](https://www.youtube.com/watch?v=k0XJSKDnowg)

---
### The screen recording is also checked in the repo and the name of the file is is ScreenRecording_18_BlockChain.mov

![alt="OverviewApplication"](KaseiCrowdsaleContractDemo.mov)
