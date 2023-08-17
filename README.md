<h1> KaseiCoin: Cryptocurrency for Mars </h1>


## Background
After years of rigorous testing and selection, the Martian Aerospace Agency has chosen you to lead the fintech frontier on Mars. Your mission: to establish a monetary system for the first Martian colony. Introducing KaseiCoin (Kasei means Mars in Japanese) - a blockchain-based cryptocurrency designed exclusively for Mars. As an ERC-20 compliant fungible token, KaseiCoin will be the heart of Martian commerce, starting with a crowdsale for early adopters looking to convert their Earth currency.

## Setup and Deployment
<b>1. KaseiCoin Token Contract:</b>
   - Import the KaseiCoin.sol starter file into Remix IDE.
   - Use OpenZeppelin libraries: ERC20, ERC20Detailed, and ERC20Mintable.
   - Create the KaseiCoin contract with a constructor specifying its name, symbol, and initial supply.
   - Compile using Solidity version 0.5.0.

<b>2. KaseiCoin Crowdsale Contract</b>
   - Begin with the KaseiCoinCrowdsale.sol starter file.
   - Inherit from OpenZeppelin's Crowdsale and MintedCrowdsale.
   - Define the constructor with your desired parameters for the crowdsale.
   - Again, compile using Solidity version 0.5.0.

<b>3. KaseiCoin Deployer Contract</b>
   - Use the KaseiCoinDeployer.sol as a base.
   - The deployer will handle the creation of both the token and the crowdsale contracts.
   - Store the addresses of the token and crowdsale for easy reference.
   - Make sure the crowdsale contract can mint KaseiCoins.
   - After setting up the crowdsale, the deployer should renounce its minter role.
   - Compile once more with Solidity version 0.5.0.

<b>4. Local Blockchain Deployment and Testing</b>
   - Use Remix, MetaMask, and Ganache to deploy the contracts to a local blockchain.
   - Test the crowdsale with different accounts, simulating token purchases.
   - Verify the total minted token supply and the funds raised in Ether.

## Evidence of Deployment

![DEPLOYED2](https://github.com/Isabel-SIM/WEEK-TWENTY-HOMEWORK/blob/main/Images/DEPLOYED2.png) <br>
<br>
<b>.SOL FILES:</b> <br>
(https://github.com/Isabel-SIM/WEEK-TWENTY-HOMEWORK/blob/main/Images/SOLFILE1.png) <br>
(https://github.com/Isabel-SIM/WEEK-TWENTY-HOMEWORK/blob/main/Images/SOLFILE2.png) <br>
(https://github.com/Isabel-SIM/WEEK-TWENTY-HOMEWORK/blob/main/Images/SOLFILE3.png) <br>

<b>DEPLOYMENT STAGES:</b> <br>
(https://github.com/Isabel-SIM/WEEK-TWENTY-HOMEWORK/blob/main/Images/DEPLOYED1.png) <br>
(https://github.com/Isabel-SIM/WEEK-TWENTY-HOMEWORK/blob/main/Images/DEPLOYED3.png) <br>
(https://github.com/Isabel-SIM/WEEK-TWENTY-HOMEWORK/blob/main/Images/DEPLOYED4.png) <br>


<b>INITIAL ETH:</b> <br>
![METAMARK1](https://github.com/Isabel-SIM/WEEK-TWENTY-HOMEWORK/blob/main/Images/METAMARK1.png) <br>

<b>REDUCED ETH:</b> <br>
![METAMARK2](https://github.com/Isabel-SIM/WEEK-TWENTY-HOMEWORK/blob/main/Images/METAMARK2.png) <br>

<b>FILES INCLUDED:</b> <br>
   - KaseiCoin.sol - Defines the main KaseiCoin token.
   - KaseiCoinCrowdsale.sol - Manages the crowdsale of KaseiCoin.
   - KaseiCoinDeployer.sol - Deploys both the token and crowdsale contracts.
