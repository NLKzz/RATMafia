# SNIPER BOT RAT MAFIA DISCORD

***

**In order to use this bot, you first need to setup your settings in the "config.json" file.**

**Then simply launch the main.py file. And enjoy.**

***

## Setup Config.json :  
\
**HTTPProvider** : The HTTP link to the node (You can create one for free by creating an account to https://moralis.io/speedy-nodes/ DO NOT USE A WEBSERVER!)  
\
**metamask_address** : The address of the wallet you want to use to buy/approve/sell.  
\
**metamask_private_key** : The private key of the wallet you want to use to buy/approve/sell.  
\
**api_id** : https://my.telegram.org/auth sign in using your telegram informations and paste here the variable "App api_id".  
\
**api_hash** : https://my.telegram.org/auth sign in using your telegram informations and paste here the variable "App api_hash".  
\
**token_paired_address** : The address of the coin with which the token is paired. For example UNIV/WAVAX, the token $UNIV is paired with the $WAVAX coin. (Currently not implemented in all functions. To avoid bugs dont touch it.)  
\
**amount_in** : The amount of paired token you want to trade on each buy transaction.  
\
**blocks_to_wait** : The number of blocks mined to wait in order to toggle the buy transaction after the addLiquidity event has been detected.  
\
**slippage** : The slippage you want to aplly on each buy/sell transaction (for launchs rather use 49.)  
\
**gas_price_superfast** : Should always be around +150 gwei  
\
**gas_price_fast** : Should always be around 100 gwei (x1.5 normal)  
\
**gas_price_normal** : Should be around "Fast/Medium" available on gas tracker : https://cointool.app/gasPrice/avax  
\
**gas_limit** : Limit amount of gas each TX can use. (Do not touch this setting.)

***

## Available modes :  
<br>

### - [1] Snipe Token Stealth Launch (Manually)

> This function allow you to trade any token on trader joe, and makes it faster to send transaction since all your TX Settings are already registered. Simply enter a contract address and you will then buy, approve and track the evolution of the gains/loss of the token, and sell it afterwards.

<br>

### - [2] Snipe Token Stealth Launch (Telegram Scrapper)

> Same functions as the one presented before, but here the contract will automatically be detected in the specified telegram channel. If the script detects a string that looks like a contract address he will ask you to verify the arithmetic operation.

<br>

### - [3] Snipe Liquidity
> Will pre-approve the contract specified by the user and then detect when the liquidity is added, and wait for the given time in the _config.json_ file to toggle the buy transaction. And will track the evolution of the gains/loss of the token, and sell it afterwards.

<br>

### - [4] Approve contract
> A function to approve any kind of contract on trader joe. (Will use the lowest available fees on the network)

<br>

***
![Lambo](https://efe.kim/avax/lambo)
<center>see ya in the lambo &copy; NLKzz_ </center>
