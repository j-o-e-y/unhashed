# What is Nano Cryptocurrency? | The Ultimate Beginners Guide

## Intro

Nano (NANO), formerly Raiblocks (XRB), aims to be a cryptocurrency which maintains the philosophy of "do one thing, and do it right." Some of Nano's features are instant transactions, no fees, and infinite scalability potential. There is no mining, no incentive structure, and each wallet stores a blockchain of its own transactions. This is all done in an effort to maximize the efficiency of cryptographic value transfer.

The project was created in 2014 by Colin LeMahieu as a solution to what he sees as design failures in Bitcoin. Above all else, Nano strives to be a cryptocurrency that can be adopted by a large portion of the world with minimal impact. The team believes this can be achieved by limiting the amount of data that needs to be stored and by using the least amount of energy possible to maintain the ledger.

## Table of Contents



## What is Nano?

### Snapshot

| Date | May 05, 2018 |
|-----|--------|
| Age | 12 mos |
| Marketcap | $1.2B
| Price (USD) | $9.05
| Price (BTC) | 0.00091฿
| All Time High | $34.43
| ATH Date | 01/02/2018
| Down From ATH | 73.71%
| Total Supply | 340,282,366.920939
| Available Supply | 133,248,290.904028
| Inflation | 0% DPoS
| Block Time | n/a
| Block Size | n/a
| Block Reward | n/a
| Explorer | https://nano.org/en/explore/
| Github Repo | https://github.com/nanocurrency/raiblocks

### Team

Leading the Nano team is Colin LeMahieu, the creator of the project and author of the [white paper](https://nano.org/en/whitepaper). There is a 12 person [team](https://nano.org/en/team/) working with Colin from a range of backgrounds. Most of them have about 10 years of experience in some sort of software or technical development, with a couple of them bringing more business related skills to the table.

### Goals

Nano's aspirations, as outlined in their white paper, are to solve three problems with Bitcoin:

>1)  Poor scalability: Each block in the blockchain can store a limited amount of data, which means the system can only  process  so  many  transactions  per  second,  making spots  in  a  block  a  commodity.  Currently  the  median transaction fee is $10.38.
>2)  High  latency:  The  average  confirmation  time  is  164 minutes.
>3)  Power inefficient: The Bitcoin network consumes an estimated 27.28TWh per year, using on average 260KWh per transaction.

### Place in Industry



## How Does Nano Work?

### Distribution of Coins

Under the hood, Nano is really a completely different technology than most other crypto projects. To begin with, the issuance of coins was done completely through faucet sites. In 2015 the team released faucet sites that would give users NANO for solving CAPTCHAs, the original site would give 1,000 NANO at a time. The coins are now 100% issued with about 130 million NANO given through faucets, 7 million sent to a [developers fund](https://nano.org/en/explore/block/4270F4FB3A820FE81827065F967A9589DF5CA860443F812D21ECE964AC359E05), and the remaining 200+ million were [destroyed](https://nano.org/en/explore/block/ECCB8CB65CD3106EDA8CE9AA893FEAD497A91BCA903890CBD7A5C59F06AB9113).

This method of faucet distribution was meant to give the developers incentive to continue improving the code, negate inflation, and give a fair distribution of the coins. However, there is no way to verify whether this ultimately led to diversification in stake holders or created some whales that found a way to exploit the faucets. As a matter of fact, there's no way to prove whether the faucets were the only distribution method, the developers could have very easily sent funds to any address without notice.

### Transactions

Two of Nano's key selling points and free and instant transactions. They're able to achieve these because of a series of design choices. The first step was to create their own method for double spend protection, which involves using accounts instead of addresses. Accounts look and act like normal addresses from the outside, but they operate differently behind the scenes. Instead of transactions building up in a pool and waiting on the next block, like Bitcoin, Nano uses a [directed acyclic graph](https://en.wikipedia.org/wiki/Directed_acyclic_graph) (DAG) which can be updated without order.

In Ethereum, which also makes use of a DAG, nodes record all changes to every account. This creates an enormous amount of data that is retained on their blockchain, currently over 180GB. For Nano this was not an option since one of their design goals is to maintain a small footprint. Nano's solution is for each account to record every deposit and withdraw as individual blocks on their personal blockchain. The DAG is then periodically updated with only the final balance, keeping its current size to 4GB. This communication of transactions between the individual blockchains of each account has been dubbed a "[block lattice](https://github.com/nanocurrency/raiblocks/wiki/Block-lattice)."

![block lattice pic](/media_what-is-nano/nano_block-lattice_small.png)

In order to keep transactions free, which Colin believes is a necessary feature, there must be something done to prevent spam. Inevitably there will be bad actors that will use free transactions as an attack vector. To defend against this Nano has implemented a small amount of proof-of-work that the sender and receiver must do for each transaction. The work is negligible and can be completed in less than two seconds on a cheap laptop. In an effort to make transactions instant, Nano wallets will do this work ahead of time in preparation of the next transaction.

This is a point of contention that I have with Nano's claim to instant and free transactions. First, I don't believe that the transactions are free because the user is paying for them with this small amount of proof-of-work. The second point I would like to make is that transactions are not instant. They only seem instant if you don't send or receive transactions in rapid succession. Depending on the power of your computer, you will eventually get stuck waiting on the proof-of-work. The only way to increase the speed of the work is to build a mining rig, which is even more evidence to support my first point.

### Mining

Proof-of-Work mining for blockchain security is seen by Nano's creator as a waste of electricity. Therefore he decided to use a delegated Proof-of-Stake (DPoS) system. In PoS systems, double spend attempts are prevented against by a voting system weighted by the number of coins staked. For coins to be staked their wallet has to remain connected to the network the entire time, which is not feasible for most users and could pose a security hazard. Nano's DPoS allows users to delegate their votes to a representative, which gives the safety of staking from cold storage.



### Governance structure
### Development Status/Future plans
### Address scaling
### Partnerships

## Pros/Cons
## How to Buy
## How to Store

---
