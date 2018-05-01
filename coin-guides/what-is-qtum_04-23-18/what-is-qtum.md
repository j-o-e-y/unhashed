# What is Qtum

## Intro

Qtum (pronounced "quantum") is a cryptocurrency and smart contract platform that combines what they see as the best parts of Bitcoin and Ethereum to create a superior solution for industrial scale businesses. Founded in 2016 by Patrick Dai of the Singapore-based Qtum Foundation, they raised $16.6M in two rounds of a crowdfunding ICO in early 2017.

Qtum was built by combining Bitcoin's base transaction layer with Ethereum's smart contracts and Proof-of-Stake consensus. Their goal is provide the tools and framework necessary to execute Ethereum style smart contracts and Dapps on a Turing-complete and globally scalable blockchain, targeted for use by big industrial companies.

Using a foundation based on Bitcoin and Ethereum, Qtum is able to make use of many of the already available tools that exist for each of these coins. This gives their developers the advantage of not having to bootstrap all of their software from scratch. They can focus instead on writing the code and developing the tools that will expand the limits of smart contract technology and empower users to harness it.

## Table of Contents

+ What is Qtum
  - Snapshot
  - Team
  - Goals
+ How Does Qtum Work
  - Technical Info
  - Governance
  - Mining
  - Partnerships
+ Pros and Cons
  - Pros
  - Cons
+ How to Buy
+ How to Store
+ Conclusion

## What is Qtum?

### Snapshot

| | |
|-----|--------|
| Age | 11 mos |
| Marketcap (current) | $1.8B
| Price (USD) | $20.83
| Price (BTC) | 0.0022฿
| All Time High | $106.88
| ATH Date | 01-07-2018
| Down From ATH | 80.51%
| Github Repo | https://github.com/qtumproject/qtum
| Total Coins | 100M
| Inflation | ~1% PoS
| Block Time | 120 seconds
| Block Size | 2MB
| Block Reward | 4 QTUM + Fees
| Block Explorer | https://qtum.info, https://qtumexplorer.io

### Team

Qtum has a [team](https://qtum.org/en/team) of 18 people worldwide. They are made up of individuals from both the Bitcoin and Ethereum space, as well as from companies and institutions outside of cryptocurrency. The group is both young and experienced with a passion for pushing blockchains to reach their full potential.

![qtum team pic](/coin-guides/what-is-qtum_04-23-18/media_what-is-qtum/qtum_team-pic.jpg)

The lead developer is [Jordan Earls](https://github.com/earlz), a self taught coder from the age of 13 with an impressive history of open source projects that includes a [review](https://github.com/Earlz/coinreviews) of over 200 cryptocurrencies. This clearly gives Jordan a deep and thorough understanding of the history of blockchain development, and also the knowledge to not repeat mistakes already made by others.

Jordan, together with a handful of other team members, comprise the vast majority of contributors to the code in their Github repo. However, since they share a code base, Qtum can pull in upgrades from Bitcoin's repo. This is exactly the point of open source development, and it's very smart of them to take advantage of the expansive development that has and continues to happen on Bitcoin's code. It's also worth mentioning that the Qtum developers always give proper attribution when they borrow code from Bitcoin. In my opinion, this says something positive about their ethics as open source developers.

![github commit insight pic](/coin-guides/what-is-qtum_04-23-18/media_what-is-qtum/qtum_github-insight-commits.png)

### Goals

In the long term, Qtum's goal is to act as the bridge which connects traditional industries stuck using slower, and often wasteful, procedures with a more secure and automated future. They aspire to make smart contracts, distributed applications, and ERC20 tokens easier to use, more secure, and more scalable specifically for businesses. By providing click-and-play solutions that are adaptable to many cases, they feel that they can offer decreased cost and improved efficiency to industries such as mobile telecoms, industrial logistics, manufacturing, etc.

The current objectives of the Qtum development team are all about gearing up for the future. Already having success on their testnet, the x86 Virtual Machine should be on the mainnet in late 2018, which will be the third platform for smart contract execution after Solidity and the Ethereum Virtual Machine. This will provide the resources for contracts that can process more data and be written in a larger number of languages, making the procedure of creating a contract accessible to more users.

One of Qtum's intentions is to make it possible for users to not need a PC or laptop. Already you can create and interact with smart contracts via their mobile app, and soon the team will add a feature which increases security and privacy for mobile users. Also on the roadmap is adding Lightning Network, creating a Dapp store, and building more robust and easier to use developer tools.

![qtum roadmap pic](/coin-guides/what-is-qtum_04-23-18/media_what-is-qtum/qtum-roadmap.png)

## How Does Qtum Work?

### Technical Info

Qtum's main technological achievement to date is their unique [Account Abstraction Layer](https://qtum.org/en/account-abstraction-layer-overview). This layer of their software stack allows for communication between contracts that utilize Ethereum's account management system and Qtum's base layer which uses an adaption of Bitcoin's [UTXO](http://earlz.net/view/2017/07/27/1820/what-is-a-utxo-and-how-does-it) model. This is a crucial step in Qtum's vision which includes executing smart contracts and Dapps in mobile environments and at scales previously unattainable by other cryptocurrencies.

![qtum software stack pic](/coin-guides/what-is-qtum_04-23-18/media_what-is-qtum/qtum_software-stack.png)

The first benefit of the use of the UTXO model is that Qtum can use [SPV](https://bitcoin.org/en/glossary/simplified-payment-verification) for mobile clients. SPV was invented by Satoshi Nakamoto, and to date is still the most secure way for a client to look up balances without downloading blocks. The importance of having a quick, trustless, and secure way to check balances from any device should not be underestimated. Most cryptocurrency ecosystems lack this and many Bitcoin wallets don't even make use of this available feature. Instead they end up relying on centralized, closed source servers that at best might have some down time. At worst they can lie about the balance of your addresses, or keep you from accessing your funds in some cases where the user does not control the keys. This could cause havoc in the industries that Qtum is trying to provide tools for, and would be a deal breaker for most prospective users.

The next advantage of using a base layer with significant development behind it is adoption of their future achievements. Qtum, like any blockchain, is going to have scaling issues, especially if they meet their target market of global industries. In order to handle a larger number of transactions they will inevitably have to move to a second layer and settle on the base blockchain. To address this concern, Qtum has decided to implement the Lightning Network on their chain some time in the next 6-18 months. Once Lightning is running on their network, they will also be able to perform trustless cross-chain [atomic swaps](https://en.bitcoin.it/wiki/Atomic_cross-chain_trading) with other coins.

Some other assets gained from the merger of the two most established technologies in cryptocurrency is familiarity and modularity. Contracts written for Ethereum can run on Qtum with no modification. Any wallet provider, exchange, or service that has experience with Bitcoin payments will be able to adopt Qtum easily. Equally, any developer familiar with writing Ethereum contracts or creating Bitcoin tools will have a small learning curve to move into Qtum development.

### Governance

An interesting aspect of open source development in project governance. The outcome of what can happen when there is not a well defined model for making decisions within a decentralized group could be seen all too well in Bitcoin's scaling debate over the past couple years. In order to avoid situations like that, which are ultimately unhealthy for a project, many teams have come up with governance structures.

Qtum's [governance](https://qtum.org/en/the-qtum-foundation-governance-structure) is handled by the Qtum Foundation along with [PwC](https://www.pwc.com). PwC teamed up with Qtum in March 2017 to assist in various areas including quality assurance, advisory, and tax services.

In Bitcoin Magazine, Patrick Dai said:
>"PwC has helped the Qtum Foundation setting up our governance model, project management, and risk management."

The model of administration that Qtum has adopted consists of committees and directors, and is outlined in their [white paper](https://qtum.org/uploads/files/ef2723f33deef1875ef17361f7c696ef.pdf). Basically, each of them have specific tasks and they provide checks and balances for each other. The focus of the entire structure is based around security, sustainability, and effectiveness.

### Mining

The mining algorithm is an important piece of any cryptocurrencies architecture, it is one of the ways that security is implemented on a blockchain. So when it came to choosing a mining method for Qtum, the team did more than just think about it. They actually spoke with people working in large industrial settings to find out what their need are. Their main concern, it turns out, was Proof-of-Work and it's energy waste.

Patrick Dai had this to say on Bitcoin.com:
>"In all of our talks to businesses... They asserted that efficiencies of blockchain technology shouldn’t be undermined by the inefficiencies of mining."

For many reasons, including the concerns of their possible users, Qtum decided to implement Proof-of-Stake mining. Specifically [Proof-of-Stake 3.0](http://earlz.net/view/2017/07/27/1904/the-missing-explanation-of-proof-of-stake-version) which attempts to be more egalitarian by giving each QTUM a single vote regardless of age. They hope this will promote more individuals to stake since the odds can't be gamed as easily as earlier versions of Proof-of-Stake. The more diverse the stakers are, the more secure the network is through its decentralization.

In order to stake QTUMs you must have them stored in an address for 500 blocks (or about 17 hours), and then run their full node software on a computer that remains connected to the Qtum network 24/7. Proof-of-Stake is like a lottery, and you can only be eligible to win if your node is connected. This is the least energy efficient aspect of Qtum, but still orders of magnitude more efficient than any Proof-of-Work mining hardware. The team promotes the use of a [Raspberry Pi](https://steemit.com/qtum/@cryptominder/qtum-staking-tutorial-using-qtumd-on-a-raspberry-pi-3) for the least amount of energy consumption. According to [this](https://qtumexplorer.io/qtum-staking-calculator) staking reward calculator, the current yearly ROI is 4.43%.

### Partnerships

The Qtum project was first funded by $1 million in investments from various backers to build their testnet and initial software. In March 2017, 3 months later and with a working model, they were able to raise an additional $15.6 million in just 5 days. At this time, according to their team [page](https://qtum.org/en/team), the Qtum project is backed by 10 investors.

Furthermore, any project running on the Qtum network has a vested interest in the well being of the base layer. Although these are not traditional partnerships, teams running Dapps on their chain and the Qtum development team need to work together for the benefit of everyone involved. Already there are some interesting [Dapps](https://qtumeco.io/dapps) with talented developers which are building on Qtum including [Bodhi](https://www.bodhi.network), [BitClave](https://www.bitclave.com), and [Spacechain](https://spacechain.com). Hopefully for Qtum these relationships will be mutually beneficial.

## Pros and Cons

### Pros

+ Healthy development team: Qtum has put together a well-rounded group of diverse, talented, and progressive individuals that have the potential to take this project to great places.
+ Strong foundation: the blockchain is built on Bitcoin's anti-fragile base layer, which has been thoroughly tested. In addition to their own upgrades, the team stands to inherit any further upgrades made to Bitcoin.
+ Security in mind: the team puts security first, but without sacrificing convenience.
+ Executes Ethereum contracts: users can easily port existing Ethereum contracts, developers will be familiar with it, and can be an alternative chain for existing Ethereum contracts should the need ever arise (congestion, fatal Ethereum flaw, etc.).
+ Modular design: built with mobile and IoT in mind, now users can create and interact with smart contracts and tokens on their mobile app.
+ Explosive use cases: Qtum's sights are set on global industry use cases. Shipping logistics, telecommunication tokens, fisheries, factories, etc. Should their platform bring success to a big industrial company, more will no doubt follow.

### Cons

+ Market saturation: there is no shortage of smart contract platforms, and even the most promising teams sometimes don't make the best product at the end of the day.
+ Proof-of-Stake hasn't been pressure tested: Qtum is the first Proof-of-Stake smart contracts, and they don't have the usage yet to claim to have been tested under extreme conditions either caused by mass adoption or an attacker.
+ Staking machine on 24/7: users staking need to keep their QTUM in a hot wallet on a device connected to the Qtum network, users cannot use a hardware wallet for staking. This is a potential security risk and inconvenient for some users.
+ Marketing focused on one region: so far there has been little marketing or outreach outside of Asia.

## How to Buy

QTUM coins can be bought at a plethora of [exchanges](https://coinmarketcap.com/currencies/qtum/#markets). Most exchanges only have trading pairs in BTC, ETH, or the South Korean won (KRW). So, unless you're in South Korea, you would need to first own or acquire Bitcoin or Ether. Bitfinex is the only exchange where you can buy QTUM with USD, however you must first pass their verification process.

![exchange volume pic](/coin-guides/what-is-qtum_04-23-18/media_what-is-qtum/qtum_exchange-volumes.png)

## How to Store

It is always in a users best interest to move their coins off of exchanges as soon as possible. The most secure solution for most people is typically a hardware wallet. Ledger supports Qtum on their Nano S and Blue models. You can refer to their [guide](https://support.ledgerwallet.com/hc/en-us/articles/115003776913-How-to-install-and-use-Qtum-with-Ledger) for using Qtum on a Ledger device. This will not give you the ability to stake your QTUM coins or to interact with smart contracts, you can only send and receive QTUM.

There are wallets available for [Android](https://play.google.com/store/apps/details?id=org.qtum.wallet) and [iOS](https://itunes.apple.com/us/app/qtum-wallet/id1277563210?mt=8) developed by the Qtum team. These are less secure than a hardware wallet, but more convenient. You cannot stake from a mobile client, but you can interact with smart contracts. The Qtum team has a mobile client [tutorial](https://github.com/qtumproject/qtum/wiki/Qtum-Mobile-wallet-tutorial).

The final option is to run a full node using the core Qtum software found on their [Github](https://github.com/qtumproject/qtum/releases), with options for Linux, Mac, and Windows. As a node, you will contribute to the connectivity and overall health of the Qtum network by validating and relaying transactions. You also will have the ability to mine by staking QTUM which helps to secure the blockchain and could potentially earn you a reward. Always be sure to exercise best practices when it comes to [securing](https://steemit.com/qtum/@cryptominder/encrypting-backing-up-and-restoring-your-qtum-wallet) your wallet.

## Conclusion

In the world of smart contracts and Dapps, it seems Qtum may be flying below the radar. They're less than a year old, and have already created a very nice foundation for themselves. Their tools are powerful and well designed and the team puts real security and decentralization ahead of buzz word upgrades that might make the price pump. If they are able to continue this quality and momentum of development, their sought after use cases may become a reality.

On the other hand, there are a ton of smart contract platforms already established. Some with the same backers as Qtum, showing that many even within the industry don't know which project will end up taking the lead in this space. In order to come out ahead, Qtum will need to do something different or better than the competition. Whether that could be the Account Abstraction Layer, their unique governance model, or something not yet built is still to be seen.

