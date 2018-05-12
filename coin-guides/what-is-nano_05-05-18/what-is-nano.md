# What is Nano Cryptocurrency? | The Ultimate Beginners Guide

## Intro

Nano (NANO), re-branded from Raiblocks (XRB) in January 2018, aims to be a cryptocurrency that follows the philosophy of "do one thing, and do it right." Nano advertises itself as having instant transactions, no transaction fees, and infinite scaling potential. There is no mining, no incentive structure, and each wallet stores a blockchain of its own transactions. This is all done in an effort to maximize the efficiency of cryptographic value transfer.

The project was created in 2014, but not officially [announced](https://bitcointalk.org/index.php?topic=1381323.0) until 2016, as a solution to what was seen as design failures in Bitcoin. Above all else, Nano strives to be a cryptocurrency that can be adopted by a large portion of the world with minimal impact. The team believes this can be achieved by limiting the amount of data that needs to be stored and by using the least amount of energy possible to maintain the ledger.

## Table of Contents

+ What is Nano?
  - Snapshot
  - Team
  - Goals
+ How Does Nano Work?
  - Coin Distribution
  - Transactions
  - Mining
  - Future Plans
+ Pros and Cons
+ How to Buy
+ How to Store
+ Conclusion

## What is Nano?

### Snapshot

| Date | May 11, 2018 |
|-----|--------|
| Age | 1yr |
| Marketcap | $825.71M
| Price (USD) | $6.20
| Price (BTC) | 0.00073฿
| All Time High | $34.43
| ATH Date | 01/02/2018
| Down From ATH | 73.71%
| Total Supply | 340,282,366.920939
| Available Supply | 133,248,290.904028
| Inflation | 0% DPoS
| Block Time | 2 seconds
| Block Size | ~400 bytes
| Block Reward | n/a
| Explorer | https://nano.org/en/explore/
| Github Repo | https://github.com/nanocurrency/raiblocks

### Team

Nano's team is lead by Colin LeMahieu, who created the project and authored the [white paper](https://nano.org/en/whitepaper). There is a 12 person [team](https://nano.org/en/team/) working with him from a range of backgrounds. Most of them have about 10 years of experience in some sort of software or technical development, with a couple of them bringing more business related skills to the table.

### Goals

Nano's long term aspirations are to solve three issues their developer has seen in Bitcoin which he believes will keep it from being successful as a global currency. The first is poor scalability, which he understands to be related to the way Bitcoin's blockchain is designed and the fee structure which prioritizes transactions for confirmation.

The second issues that Nano is attempting to solve is also a symptom of the way Bitcoin's blockchain is designed, high latency. In a cryptocurrency like Bitcoin, new blocks of transactions are added the global ledger every 10 minutes. That's if the system is operating optimally, in moments of excessive use the transaction confirmation times can increase dramatically. As opposed to this 10 minute confirmation time, Nano aims for instant transactions.

The third objective is to overcome the energy consumption of Proof-of-Work (PoW) mining. Nano's white paper, which appears to have been written in November 2017 based on these values compared with the [historical record](https://digiconomist.net/bitcoin-energy-consumption), the average energy use of Bitcoin mining was 27TWh per year. Since then the usage has gone up to 66TWh per year, and the trend seems like it will at least continue to grow at this rate.

## How Does Nano Work?

### Coin Distribution

Under the hood, Nano is completely different technology than most other crypto projects. To begin with, the issuance of coins was done completely through faucet sites. In 2015 the team released faucet sites that would give users NANO for solving CAPTCHAs, the original site would give 1,000 NANO at a time. The coins are now 100% issued with about 130 million NANO given through faucets, 7 million sent to a [developers fund](https://nano.org/en/explore/block/4270F4FB3A820FE81827065F967A9589DF5CA860443F812D21ECE964AC359E05), and the remaining 200+ million were [destroyed](https://nano.org/en/explore/block/ECCB8CB65CD3106EDA8CE9AA893FEAD497A91BCA903890CBD7A5C59F06AB9113).

This method of faucet distribution was meant to negate inflation and give a fair distribution of the coins. While the developers fund is used for paying salaries of the core team, bug bounties, marketing, and various other endeavors that serve to benefit the coin.

However, there is no way to verify if this method led to the intended diversification in stake holders. It could have very well created some whales that exploited these faucets with automated tools. As a matter of fact, there's no way to even prove whether the faucets were the only distribution method. The developers could have sent funds to any address without notice.

### Transactions

Two of Nano's key selling points and free and instant transactions. They're able to achieve these because of a series of design choices. The first step was to create their own method for double spend protection, which involves using accounts instead of addresses. Accounts look and act like normal addresses from the outside, but they operate differently behind the scenes. Instead of a Bitcoin type chain where blocks are added in sequential order, Nano uses a [directed acyclic graph](https://en.wikipedia.org/wiki/Directed_acyclic_graph) (DAG) which can be updated without order.

In Ethereum, which also makes use of a DAG, nodes record all changes to every single account. This creates an enormous amount of data that is retained on their blockchain, currently over 180GB. For Nano this was not an option since one of their design goals is to maintain a small footprint. Nano's solution is for each account to record every deposit and withdraw as individual blocks on their personal blockchain. The DAG is then updated with only the final balance, keeping its current size limited to only 4GB without pruning. This communication of transactions between the individual blockchains of each account has been dubbed a "[block lattice](https://github.com/nanocurrency/raiblocks/wiki/Block-lattice)."

![block lattice pic github](/coin-guides/what-is-nano_05-05-18/media_what-is-nano/nano_block-lattice.png)

In order to keep transactions free, which Colin believes is a necessary feature, there must be something done to prevent spam. Inevitably there will be bad actors that will use free transactions as an attack vector. To defend against this Nano has implemented a small amount of PoW that the senders and receivers wallet must do for each transaction. The work is negligible and can be completed in less than two seconds on a cheap laptop. In an effort to make transactions instant, Nano wallets will do this work ahead of time in preparation of the next transaction.

Now, I have to point out a couple of facts about Nano's claim to free and instant transactions. First, I don't see the transactions as free because the users are paying for them with PoW. Not just to send either, in Nano's system, users pay with PoW to send and to receive transactions.

The second thing I feel that I should point out is that Nano transactions are not instant. They only seem instant if you don't send or receive multiple transactions in rapid succession. Depending on the power of your computer, you will eventually get stuck with a transaction backlog while waiting on the PoW. The only way to increase the speed of the work is to build an expensive mining rig, which is even more evidence to support my first point.

### Mining

In his continuing effort to reduce energy expenditure, Colin has decided against PoW for securing the Nano blockchain. Alternatively, he decided to use a delegated Proof-of-Stake (DPoS) system. In PoS systems, double spend attempts are prevented against by a voting system weighted by the number of coins staked. For coins to be staked their wallet has to remain connected to the network the entire time, which is not feasible for most users and could pose a security hazard.

Nano's DPoS works the same as a typical PoS system, only without the necessity of keeping a hot wallet online 24/7. In this system users whose coins are not online delegate their votes to representatives that do stay online. This gives users the ability to stake from cold storage. It also, unfortunately, leads to centralization of the weighted voting power on the network. This is because Nano wallets have default nodes that they delegate to, and most users don't change the defaults. This has resulted in the known nodes of the developers controlling over 50% of the voting power.

This centralization is likely to get worse as time goes on because of the fact that there is no incentive structure. Having all the coins issued through faucets, and no transaction fees, there is nothing to pay stakers. Without fees or new coins to collect there are very few reasons why a user would want to run a voting node. If adoption takes off, and sophisticated attacks begin to occur, running a voting node may require special hardware. Then, even if users wanted to support the network by running an honest node, most wouldn't be able to.

### Future Plans

Nano's [roadmap](https://developers.nano.org/roadmap/) is focused on improving the user experience, adoption, user interfaces, and the protocol itself. The first point made is that the team plans to maintain accurate and helpful documentation in order to ease user and service adoption. In another effort to increase use, the team is working on Point-of-Sale software that is designed to work on hardware wallets, mobile wallets, or existing Point-of-Sale systems.

![point-of-sale pic github](/coin-guides/what-is-nano_05-05-18/media_what-is-nano/nano_pos.png)

In a move that will improve the protocol, user experience, and adoption all at once, the team plan to implement Universal Blocks. At this moment, Nano has 4 different types of blocks on the network: send, receive, open, and change. The Universal Blocks upgrade will consolidate all of these to one block type. This will improve ledger pruning and make transactions easier to create and validate. Once the transaction operations become more efficient, the team is hoping the door will open to hardware wallet integration.

Coming up in the very near future are the new desktop and mobile wallets from the core team. The most popular mobile wallets at this time are from third parties, and the core team's official desktop wallet was not built with user experience in mind. Colin and his team are hoping that they can fix this by providing users with a better desktop and mobile wallet. Right now both wallets are in private beta testing, but they should be available shortly. The final product is close enough that the developers have already released a preview of the Android app.

![android app pic github](/coin-guides/what-is-nano_05-05-18/media_what-is-nano/nano_android.png)

## Pros/Cons

### Pros

+ Transaction fees are 0 NANO.
+ Most transactions feel instant.
+ The system uses less energy than coins mined with PoW.
+ Staking can be done while coins are in cold storage.

### Cons

+ Spam protection PoW on transactions can cause a bottleneck in high throughput situations.
+ Team is unknown in the cryptocurrency space outside of this project.
+ No incentive structure to maintain network security.
+ Closed source development of new desktop and mobile wallets.
+ No hardware wallet for secure storage.

## How to Buy

The easiest way to get Nano is with Bitcoin on [Binance](https://www.binance.com/trade.html?symbol=NANO_BTC). There are a handful of [other exchanges](https://coinmarketcap.com/currencies/nano/#markets) with NANO trading pairs, but Binance accounts for almost 93% of the total volume. At the time of writing there is no fiat on-ramp for NANO, but it is part of their development [roadmap](https://developers.nano.org/roadmap/fiat-on-ramp/).

![trade vol pic github](/coin-guides/what-is-nano_05-05-18/media_what-is-nano/nano_trade-vol.png)

## How to Store

To follow the best practices of a cryptocurrency holder, you are going to want to move your NANO off of the exchange and into an address that you control. Usually the best option for security is a hardware wallet, but unfortunately that is not an option yet with Nano. While development is finished on the hardware wallet integration, there are three other options available.

There is one wallet from the official development team, until their new wallets come out of beta testing, a [desktop client](https://nano.org/en/wallet/) for Linux, Mac, or Windows. The official Nano client will download the entire 4GB ledger and can become a voting representative. You will generate an address immediately, but you won't be able to send or see received funds until the wallet is completely sync'd.

Aside from the Nano team's own wallet, there are third party options which are endorsed by the team. If you prefer a mobile wallet, [Canoe](https://getcanoe.io/) has an option for Android users and is accepting beta testers for their iOS app. They also have their own desktop wallet for all platforms.

The fastest way to get an address is an officially endorsed web wallet called [NanoVault](https://nanovault.io). The site's code is open source and can be found on [Github](https://github.com/cronoh/nanovault). In just a few clicks you can have your seed backed up and get your first address to start receiving NANO.

## Conclusion

The technology behind Nano seems really promising, the development team has used cryptographic techniques in new and interesting ways. This has allowed them to give this coin some appealing traits, free and instant transactions are features anyone can see the benefits of. Even more so now that we have just seen an extreme fee event we saw in Bitcoin at the end of 2017.

It's also important to remember the environmental impact a technology has on the planet. Considering how  much energy is used on cryptocurrency mining, Nano's approach without miners may be the more sustainable choice. Although, as with all security systems, any added convenience comes with a security trade off.

Bitcoin's proponents would argues that the energy used and confirmation times are necessary. They are two important elements of the security which has kept Bitcoin safe for almost 10 years in the harshest conditions that any financial system has ever been exposed to. Right now Nano may be able to deliver on some of their claims, but if they ever get usage beyond speculation it could be a different story.

