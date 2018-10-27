# Equihash Coins

Most cryptocurrencies rely on Proof-of-Work mining to secure their networks from double-spending in a censorship resistant way. In order to maintain censorship resistance, the individual miners must be sufficiently decentralized.

In the early days of cryptocurrency it became apparent that ASICs were leading to centralization of mining. There were many attempts to create algorithms that would be "impossible" to implement on specialized hardware in response. Litecoin is one such example of this first wave of ASIC resistance with their Scrypt algorithm.

However, by 2014 almost every one of these algorithms had an ASIC built for it that was orders of magnitude more powerful than any other hardware on the network. It  wasn't long before most coins were in threat of mining centralization and the trend was getting worse.

This culmination of events is what inspired a couple of scientists from Luxembourg to look into the problem themselves and see if they could offer any solution. The result was the creation of the Equihash algorithm.

## What is Equihash?

Equihash is a Proof-of-Work mining algorithm that was invented by Alex Biryukov and Dmitry Khovratovich from the University of Luxembourg's Interdisciplinary Centre for Security, Reliability and Trust (SnT). They sought to create a memory intensive algorithm that would be impossible to implement in an ASIC. This would lower the entry costs for new miners, foster decentralization of miners, and fragment manufacturers of the hardware.

Equihash was first introduced in early 2016 at a symposium on system security in San Diego. ZCash was the first cryptocurrency to implement it in April of that same year. Their team stated that they chose this algorithm for its efficiency, security, and most of all ASIC resistance.

Two of the Zcash founders, Zooko Wilcox and Jack Grigg, explained in a [blog post](https://z.cash/blog/why-equihash/):

>Equihash is a memory-oriented Proof-of-Work, which means how much mining you can do is mostly determined by how much RAM you have. We think it is unlikely that anyone will be able to build cost-effective custom hardware (ASICs) for mining in the foreseeable future.

In spite of all the effort and intelligence that went into creating Equihash, it has ultimately failed in its original form. ASICs hit the market in May 2018 and are now dominating some Equihash coins. Other coins have decided to tweak the algorithm to fend off ASICs, though they may be unavoidable in the end.

## Coins Using Equihash
(ordered by market cap)

+ ZCash (ZEC)
+ Bitcoin Gold (BTG)
+ Komodo (KMD)
+ ZenCash (ZEN)
+ Bitcoin Private (BTCP)
+ ZClassic (ZCL)
+ Bitcoin Interest (BCI)
+ Zelcash (ZEL)
+ BitcoinZ (BTCZ)
+ Zero (ZER)
+ Hush (HUSH)

1. [ZCash](https://z.cash)

ZCash is a fork of Bitcoin with added privacy options, shorter block time, a "Slow Start" emission, and a "Founder's Reward" (20% of miner income) built into the protocol. Utilizing zero knowledge proofs (zk-snarks), ZCash can offer shielded transactions which hide the sender, receiver, and amount. Only a small percentage of users utilize private transactions, and no exchanges support them, leaving the true anonymity benefits a subject of debate. The developers of ZCash have chosen not to devote effort to protecting the network from ASICs.

2. [Bitcoin Gold](https://bitcoingold.org/)

Bitcoin Gold is a fork of Bitcoin that has changed nothing except for the Proof-of-Work algorithm. The team's original goal was to decentralize mining, and indeed they followed this course by altering the algorithm to block ASICs. Recently, the coin has been de-listed from some major exchanges such as Bittrex and Yobit.

3. [Komodo](https://komodoplatform.com/)

Komodo is a fork of ZCash that was originally intended to be a cryptocurrency platform. Some time in 2016 Komodo rebranded to an ICO platform and had their own ICO. Currently their focus is on providing a selectively private and secure platform for issuance and interaction with tokens. Like ZCash, this coin did not make an effort to resist the ASICs.

4. [ZenCash](https://zencash.com/)

ZenCash forked from ZClassic on May 18, 2017. They have since rebranded to Horizen but maintain the original ticker symbol (ZEN). The goal of the project is to deliver everything that Ethereum can do, but with strong privacy. Deriving from ZClassic (itself a fork of ZCash), ZenCash has inherited the zk-snarks privacy features. Additionally, ZenCash uses "Secure Nodes" to offer encrypted communication between peers.

5. [Bitcoin Private](https://btcprivate.org/)

Bitcoin Private is a co-fork of Bitcoin and ZClassic by the founder of ZClassic, Rhett Creighton. In this case that means the code was forked from ZClassic, but the initial coins were distributed 1-to-1 to any holders of Bitcoin or ZClassic on February 28th, 2018. The coin inherited shielded transactions from ZCash, and they changed the algorithm accordingly to stop ASICs.

6. [ZClassic](https://zclassic.org/)

ZClassic was the first fork of ZCash, beginning in late 2016. The project's aim was to remove the "Founder's Reward" and "Slow Start" mining from ZCash. Since the "Founder's Reward" was controversial from the beginning, ZClassic offers miners a way to opt out of it while still supporting privacy. The team splintered upon the creation of Bitcoin Private, but development hasn't stalled.

7. [Zelcash](https://zel.cash)

Zelcash is a combination of ZCash and Ethereum, providing zk-snark privacy as well as DAPP support. The coin uses a combination of Proof-of-Work to secure the blockchain and Proof-of-Stake for DAPP security. The aim of the project is to foster distributed development.

8. [BitcoinZ](https://btcz.rocks/)

BitcoinZ was created by an anonymous developer that forked the ZCash codebase. Their blockchain launched on September 9, 2017 with no premine or ICO. The goal of the team is to be a community driven coin that has the ZClassic spirit, ZCash core, and Bitcoin fundamentals. The notable changes they have made to the original code was the addition of bigger blocks and tweaking the algorithm to protect from ASICs.

9. [Zero](https://zerocurrency.io/)

Zero forked from ZCash on February 19, 2017. They've made some minor adjustments to the mining algorithm in an effort to resist ASIC production and removed the "Founder's Reward". In the future the team plans to implement staking and reduced block times.

10. [Hush](https://myhush.org/)

Hush is a fork of ZCash which has removed the "Founder's Reward". The developers added Tor to the protocol to protect users IP addresses, and a private messaging system and list system. There's also a Counterparty port for Hush which allows users to create and issue assets.
