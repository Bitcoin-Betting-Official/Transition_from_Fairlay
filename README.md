# Transition from Fairlay to Bitcoin Betting

Fairlay will soon  transition to the new decentralized version of the Bitcoin Prediction Market called Bitcoin Betting. The company behind Fairlay will cease to exist and with it all centralized infrastructure like servers, hot wallets, funds, emails and so forth. 

## Why is the change necessary?

Uncertainty in the different regulatory environments in the many jurisdictions we want to serve is the key reason making this step necessary. Furthermore, a decentralized network makes us more resilient against DDoS attacks, server outages and many other threats.
The high costs of maintaining our centralized server infrastructure, hosting the website, maintaining a hot wallet and so on will not allow us to keep the old site running for much longer than March 2025.   

## What is getting better?

### No collection of personal data, completely pseudonymous

No collection of private user data like email, name or passport will ever be required. Your entire identity is managed by your crypto currency wallet like MetaMask, WalletConnect or similar.  

### Speed

The new platform is heavily utilizing WebSockets and subscriptions. Thus the speed and update frequency will be much better than before.  Slow server response times, server errors or DDoS attacks will be a thing of the past. The official frontend runs entirely in your local browser and will be available on IPFS. With it you can connect to one of many available nodes.

### Simpler UI

The improved UI is designed to address less advanced users who always had problems with an exchange interface.  Nevertheless all the functionality that you know from the old site and more will continue to be available via the API, that each node is offering by default.

### New Users and Referral Program

With the release it will be again possible to invite new users. We actively encourage you to use this feature and invite all friends, co-workers and family members that take an interest in trading and betting.  The platform will only be available via invite to keep scammers, match fixers, money launderers and other bad actors out.  You will receive 10% of all generated commissions of any user you invite and also of any subsequent user that is referred.

### Full Transparency 

All Transactions are publicly available for anyone to check and verify. 

### Security

Each transaction, let it be a transfer or a bet or a settlement must be signed with the private key that is only held by the respective user. It is impossible for anyone to steal any of your funds. Thus on the platform, there are no admins with special rights that can arbitrarily take or freeze funds. 

### Faster Deposits

The platform will allow transactions in any currency.  From inception BTC, WBTC and ETH will be available. Making deposits via ETH or WBTC can be performed in a trustless manner by using a decentralized so called bridge, a special contract on the Ethereum Blockchain. Such deposits will be available in less than a minute.

## What is getting worse?

### No Privacy

By design, any transaction is open to the public. 

### Signing

Each Transaction has to be signed before it can be transfmitted, making a bit more cumbersome to place a bet.

### No transaction reversal

Bad Actors can no longer be easily stopped. 

### Miner Fees

Each Transaction that is mined to the decentralized ledger like any bet or transfer involves a small fee that is going to the Node that mines this transaction. The usual transaction costs is not more than 1 satoshi per transaction. Always make sure to keep a tiny amount of WBTC or BTC in your wallet to cover these fees. 



## Funding

### Bridge from Fairlay

During the transition period funds can be easily bridged from Fairlay by sending a certain mBTC amount to the Fairlay user "bridge".
You must indicate your Bitcoin Betting user id  in the reference field (and nothing else).  So for example  15. Do not write "15" or 'user 15' or anything further or the transaction will fail.  Test with small amounts first. 
The bridge is free of any charge. 

### Withdraw mBTC from Bitcoin Betting to Fairlay

You can send mBTC back by making a transfer to user 1. Do not send mETH or mWBTC.  You must reference your Fairlay user API ID in the reference field. Fairlay user id can be found in your Profile section. For example: 1016024. Do not write anything further.

### Direct BTC Deposits:

Also during the transition period a very simple Bitcoin wallet is available that allows direct deposits of BTC to the platform. It operates with just one address and is therefor much cheaper to maintain.

Instructions (please read carefully before depositing) : 
- Only deposit to the address bc1qqre694gpveud05y40cy3r5l96ltu6ftn0f7pd7 from a wallet, where you have the private keys and that you control or your might lose all your Bitcoins!  
- Only deposit full mBTC amounts + an amount of satoshis that indicate your user id on the Bitcoin Betting platform.
- Test with small amounts first.

For example:
- by sending  0.00500013 BTC  to bc1qqre694gpveud05y40cy3r5l96ltu6ftn0f7pd7   5.00013 mBTC will be credited to the user with ID 13.
- by sending  0.00710013 BTC  to bc1qqre694gpveud05y40cy3r5l96ltu6ftn0f7pd7 all funds might be LOST because user 10013 does not exist.  
- by sending  0.00700000 BTC  to bc1qqre694gpveud05y40cy3r5l96ltu6ftn0f7pd7 all funds might be LOST because user 0 does not exist.  

### Bridge from Ethereum
It is encouraged to use WBTC as main currency for betting.  To perform any deposit and withdrawal a small amount of Ether is required in your wallet.  To obtain WBTC with BTC there are many possibilities:

1. Bridge BTC to tBTC on https://dashboard.threshold.network/tBTC/mint.  This will take around 1 hour. Then you can swap tBTC vs WBTC on curve.fi. Around 10 USD worth of ETH are probably required to make this transaction.
2. Buy WBTC by depositing BTC on Binance.
3. Use Thorswap

Also ETH or BTC do exist on the platform and can be used for betting. More currencies can be created and minted by using the API.



## Incentives to switch

On Fairlay a fee bomb was implemented. Commissions for newly created markets will rise by 0.01% each two weeks.  This is to incentivize a slow but steady transition to the new platform.  

## How to participate and connect

### Getting in touch

The platform is fully governed by the Bitcoin Betting DAO.  All protocol and UI changes are decided by the DAO. Furthermore the DAO will hold all fees and commissions that are ever collected. 
Proposals can be initiated via :

https://app.aragon.org/#/daos/ethereum/bitcoin-betting.dao.eth/dashboard 

But reports and any feature proposal that is accepted by the DAO will usually be rewarded directly by sending WBTC to the Ethereum address of the initiator of the proposal.

A governance forum is planned, for now it should be sufficient to discuss matters in the chat on:

https://app.bitcoin-betting.com

New Proposals and updates from the DAO will also be published on:

https://x.com/_bitcoinbetting

### Ownership

It should also be possible to trade ownership tokens of Bitcoin-Betting: bbet tokens (Contract address 0x60b8b2bf009a90d3864068bff2c2cb37d86b12ec).   There exist a maximum of 1 million bbet tokens that represent full ownership of all source code, IP, domains and funds associated with Bitcoin Betting.

These tokens can be traded on uniswap. 

### Running a Node

Running your own node is highly encouraged. Requirements are 16 GB of RAM, 2vCPU and a server with ubuntu 20.04 or higher and about 30 minutes of time to set it up.  For instructions please get in touch.  










