# Martian Token Crowdsale

![](images/application-image.png)

## Create the KaseiCoin Token Contract

The KaseiCoin token contract is implemented in the solidity file [KaseiCoin.sol](KaseiCoin.sol). 

We are able to compile KaseiCoin.sol:
![](images/img1.png)

## Create the KaseiCoin Crowdsale Contract and KaseiCoin Deployer Contract

The KaseiCoin Crowdsale contract and KaseiCoin Deployer contract are implemented in the solidity file [KaseiCoinCrowdsale.sol](KaseiCoinCrowdsale.sol).

We are able to compile KaseiCoinCrowdsale.sol:
![](images/img2.png)

## Deploy and Test the Crowdsale on a Local Blockchain

In Remix, we employ `Injected Provider - MetaMask` environment which connects to Ganache through MetaMask. 
![](images/img3.png)

We first deploy the KaseiCoinCrowdsaleDeployer contract:
![](images/img4.png)

We then deploy the KaseiCoin contract at address `0x7479B7F6685177cA7ec34765Bf0110DBb050A2D0`:

<img src="images/img7.png" width="300"/> <img src="images/img8.png" width="300"/>

Finally we deploy the KaseiCoinCrowdsale contract at address `0x581Dfeca54AF2095B5119068C28543777aD32e0F`:

<img src="images/img9.png" width="300"/> <img src="images/img10.png" width="300"/>

To test the functionality of the crowdsale, we bought 1000 Wei:

<img src="images/img11.png" width="300"/> <img src="images/img12.png" width="300"/> <img src="images/img13.png" width="300"/>

The transaction was successful:

![](images/img14.png)


![](images/img15.png)


