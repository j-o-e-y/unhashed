# What is Qtum

## Intro

Qtum (pronounced "quantum") is a blockchain system that combines what they see as the best parts of Bitcoin and Ethereum to create a superior solution for industrial scale businesses. Founded in 2016 by Patrick Dai of the Singapore-based Qtum Foundation, they raised $16.6M in two rounds of a crowdfunding ICO in early 2017.

Qtum was built by combining Bitcoin's base transaction layer with Ethereum's smart contracts and proof-of-stake consensus. Their goal is provide the tools and framework necessary to execute Ethereum style smart contracts and Dapps on a Turing-complete and globally scalable blockchain, targeted for use by big industries.

By creating a foundation based on Bitcoin and Ethereum, Qtum is able to make use of many of the already available tools that exist for each of these coins. Since their developers don't have to spend time bootstrapping all of their software from scratch, they can focus instead on writing the code that they hope will bring these technologies to next level.

## Table of Contents

+ What is Qtum?
  - Snapshot
  - Team
  - Goals
+ How Does Qtum Work?
  - Technical

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

Qtum has a [team](https://qtum.org/en/team) of 18 people worldwide. They are made up of individuals from both the Bitcoin and Ethereum space, as well as from companies and institutions outside of cryptocurrency. The group is both young and experienced with a passion for pushing blockchain technologies beyond their current limits.

![qtum team pic](/coin-guides/what-is-qtum_04-23-18/media_what-is-qtum/qtum_team-pic.jpg)

The lead developer is [Jordan Earls](https://github.com/earlz), a self taught coder from the age of 13 with an impressive history of open source projects that includes a [review](https://github.com/Earlz/coinreviews) of over 200 cryptocurrencies. This undoubtedly gives Jordan a deep and thorough understanding of the history of blockchain development which should lead to faster and more effective progress for Qtum.

Jordan, together with about 6 members of the Qtum team, have contributed most of the code to their Github repo. However, since they share a code base, Qtum can pull in upgrades from Bitcoin's repo. This is exactly the point of open source development, and it's very smart of the Qtum team to take advantage of the robust development that happens on Bitcoin's code. It's also worth mentioning that the Qtum developers always give proper attribution when they borrow code from Bitcoin. In my opinion, this says something positive about their ethics.

![github commit insight pic](/coin-guides/what-is-qtum_04-23-18/media_what-is-qtum/qtum_github-insight-commits.png)

### Goals

In the long term, on a high level, Qtum's goal is to act as the bridge which connects legacy industries with the future. They aspire to make smart contracts, distributed applications, and ERC20 tokens easier to use, more secure, and more scalable specifically for businesses. By providing click-and-play solutions that are adaptable to many cases, they can offer decreased cost and improved efficiency to industries such as mobile telecoms, industrial logistics, manufacturing, etc.

The current objectives of the Qtum development team are all about gearing up for the future. Already having success on their testnet, the x86 Virtual Machine should be on the mainnet in late 2018, which will be the third platform for smart contract execution after Solidity and the Ethereum Virtual Machine (EVM). This will provide the resources for contracts that can process more data and be written in a larger number of languages, making the procedure of coding a contract more familiar to traditional developers.

One of Qtum's intentions is to make it possible for users to not need a PC or laptop, and already you can create and interact with smart contracts via their mobile app. Coming soon the team will introduce a lightweight SPV wallet, hardware wallet integration, they plan to build more robust developer tools, they will add the lightning network for scalability, and there are plans to create a Dapp store.

![qtum roadmap pic](/coin-guides/what-is-qtum_04-23-18/media_what-is-qtum/qtum-roadmap.png)

## How Does Qtum Work?

### Technical Info

Qtum's main technological achievement to date is their unique [Account Abstraction Layer](https://qtum.org/en/account-abstraction-layer-overview). This layer of their software stack allows for communication between contracts that utilize Ethereum's account management system and Qtum's base layer which uses an adaption of Bitcoin's UTXO model. This is a crucial step in Qtum's vision which includes executing smart contracts and Dapps in mobile environments and at scales previously unattainable by other cryptocurrencies.

![qtum software stack pic](/coin-guides/what-is-qtum_04-23-18/media_what-is-qtum/qtum_aal.png)

The first benefit of the use of the UTXO model is that Qtum can use [SPV](https://bitcoin.org/en/glossary/simplified-payment-verification) for mobile clients. SPV was invented by Satoshi Nakamoto, and to date is still the most secure known way for a light client to look up balances without downloading blocks. The importance of having a quick, trustless, and secure way to check balances from any device should not be underestimated. Most cryptocurrency ecosystems lack this and many Bitcoin wallets don't even make use of this available feature. Instead they end up relying on centralized, closed source servers that at best might have some down time. At worst they can lie about the balance of your addresses, or keep you from accessing your funds in some cases where the user does not control the keys. This could cause havoc in the industries that Qtum is trying to provide tools for, and would be a deal breaker for most prospective users.

The next advantage of using a base layer with significant development behind it is adoption of their future achievements. Qtum, like any blockchain, is going to have scaling issues, especially if they meet their target market of global industries. In order to handle a larger number of transactions they will inevitably have to move to a second layer and settle on the base blockchain. To address this concern, Qtum has decided to implement the Lightning Network on their chain some time in the next 6-18 months. Once Lightning is running on their network, they will also be able to perform trustless cross-chain [atomic swaps](https://en.bitcoin.it/wiki/Atomic_cross-chain_trading) with other coins.

Some other assets gained from the merger of the two most established technologies in cryptocurrency is familiarity and modularity. Contracts written for Ethereum can run on Qtum with no modification. Any wallet provider, exchange, or service that has experience with Bitcoin payments will be able to adopt Qtum seamlessly. Equally, any developer familiar with writing Ethereum contracts or creating Bitcoin tools will have a small learning curve to move into Qtum development.

### Governance

An interesting aspect of open source development in project governance. The outcome of what can happen when there is not a well defined model for making decisions within a decentralized group could be seen all too well in Bitcoin's scaling debates over the past couple years. In order to avoid situations like that, which are ultimately unhealthy for a project, many teams have come up with governance structures.

Qtum's [governance](https://qtum.org/en/the-qtum-foundation-governance-structure) is handled by the Qtum Foundation along with [PwC](https://www.pwc.com). PwC teamed up with Qtum in March 2017 to assist in various areas including quality assurance, advisory, and tax services.

In Bitcoin Magazine, Patrick Dai said:
>"PwC has helped the Qtum Foundation setting up our governance model, project management, and risk management."

The model of administration that Qtum has adopted, and outlined in their [white paper](https://qtum.org/uploads/files/ef2723f33deef1875ef17361f7c696ef.pdf), consists of committees and directors. Each of them have specific tasks and provide checks and balances for each other. The focus of the entire structure is based around security, sustainability, and effectiveness.

### Mining

The mining algorithm is an important piece of any cryptocurrencies architecture, it is one of the ways that security is implemented on a blockchain. So when it came to choosing a mining method for Qtum, the team did more than just think about it. They actually spoke with people working in large industrial settings to find out what their need are. Their main concern, it turns out, was Proof-of-Work and it's energy waste.

Patrick Dai had this to say on Bitcoin.com:
>"In all of our talks to businesses... They asserted that efficiencies of blockchain technology shouldn’t be undermined by the inefficiencies of mining."

For many reasons, including the concerns of industry, Qtum decided to use Proof-of-Stake mining. Specifically [Proof-of-Stake 3.0](https://allthingscrypto.tech/introduction-to-proof-of-work-and-proof-of-stake-3-0-part-4/) which attempts to be more egalitarian by giving each QTUM a single vote regardless of age. They hope this will promote more individuals to stake since the odds can't be games as easily as earlier versions of Proof-of-Stake. The more diverse the stakers are, the more secure the network is through its decentralization.

In order to stake QTUMs you must leave your computer running 24/7, which is the least energy efficient aspect, but still orders of magnitude more efficient than any Proof-of-Work mining hardware. As a matter of fact, the team promotes the use of a [Raspberry Pi](https://steemit.com/qtum/@cryptominder/qtum-staking-tutorial-using-qtumd-on-a-raspberry-pi-3) for the least amount of energy assumption. According to [this](https://qtumexplorer.io/qtum-staking-calculator) staking reward calculator, the current yearly ROI is 4.43%.

### Partnerships

The Qtum project was first funded by $1 million in investments from various backers to build their testnet and initial software. 3 months later, in March 2017, with a working model, they were able to raise an additional $15.6 million in just 5 days. At this time, the Qtum project is backed by 10 investors.

Furthermore, any project running on the Qtum network has a vested interest in it's well being. Although not a traditional partnership, teams running Dapps on their chain and the Qtum development team need to work together for each others benefit. Already there are some interesting Dapps live on Qtum including Bodhi and Bitclave.

![live dapps pic](/coin-guides/what-is-qtum_04-23-18/media_what-is-qtum/qtum_live-dapps.png)


## Pros/Cons



## How to Buy



## How to Store
