# Advanced_Solidity_CrowdSale
Crowdsale and Minting ERC-20 Tokens

This decentralized application (dApp) was built using:

1. Solidity: Solidity is a smart contract programming language that runs on many blockchains, namely, Ethereum (EVM) compatible chains. 
2. Ethereum: Global, open-source platform for decentralized applications
3. Remix: Open Source IDE that helps your write Solidity contracts inside your browser
4. Ganache: Personal blockchain for rapid Ethereum dApp development

This decentralized application is currently made up of 2 smart contracts:

* [`Crowdsale.sol`](Crowdsale/Crowdsale.sol)  

    - Function: Manage crowd funding process    
    - Smart Contract Detail: This contract leverages open zeppelin libraries to const  

* [`PupperCoin.sol`](Crowdsale/PupperCoin.sol)   
    - Function: Construct an ERC 20 Token  
    - Smart Contract Detail: This contract allows users to send ETH and get back PUP (PupperCoin).This contract will mint the tokens automatically and distribute them to buyers in one transaction.

The dApp will to create an ERC20 token (PUP) that will be minted through a `Crowdsale` contract that you can leverage from the OpenZeppelin Solidity library.

This crowdsale contract will manage the entire process, allowing users to send ETH and get back PUP (PupperCoin).
This contract will mint the tokens automatically and distribute them to buyers in one transaction.

It will inherit `Crowdsale`, `CappedCrowdsale`, `TimedCrowdsale`, `RefundableCrowdsale`, and `MintedCrowdsale` from the OpenZeppelin library available through Github.

The detailed screenshots of the project are available [here](Crowdsale/readme.md).

