# What is Blockchain?

On January 9, 2009 Satoshi Nakamoto shared with us the invention of Bitcoin and its underlying technology, the blockchain. Now this tech that allows cryptocurrencies to exist is being tested in nearly every industry. Companies ranging from real estate and public records to forecasting and cloud storage are jumping into blockchains. Still, many people don't have a good understanding of what a blockchain is.

Blockchains excel at a very specific function: being a distributed, trustless, immutable ledger for data. Before the invention of blockchains, there was no way to share a database with the entire internet and still trust that its data was reliable and tamper resistant. Thanks to blockchains we can not only rely on this data, but in the case of Bitcoin, we can use it to secure a network currently valued at $146 billion.

In this article I'll help you understand blockchains by exploring:

+ What Does a Blockchain Do?
  - History
  - General Overview
+ How Is a Blockchain Secure?
  - Game Theory
  - Decentralization
+ Why Use a Blockchain?
+ Summary

## What Does a Blockchain Do?

### History

Blockchains were first thought of in 1991 by a group of cryptographers as a theoretical type of data structure. It would be another 18 years before a person or group named Satoshi Nakamoto actually put a blockchain into use as the ledger for the cryptocurrency Bitcoin.

Previous to Bitcoin, other attempts had been made at creating digital currencies. Some of them are even referenced in the Bitcoin [white paper](https://bitcoin.org/bitcoin.pdf). All of these predecessors to Bitcoin had some things in common: their databases were centralized and their creators were public. They were eventually all shut down for various legal reasons.

Satoshi, having learned from the mistakes of these past attempts, knew two things for sure. First, they knew that their identity should remain hidden. They solved this problem by using the pseudonym Satoshi Nakamoto. Secondly, they knew that there could be no one in control of the ledger or that entity would risk legal trouble. The blockchain was their breakthrough concept that solved the second issue.

### General Overview

A blockchain is a type of database where the data is organized into groups, called blocks. Each new block uses a cryptographic method, called hashing, to include a reference to the data in the previous block. This creates a chain in the sense that to change any data in a block would in turn change the next block, and so on down the line.

![hash chain pic](/articles/what-is-blockchain_03-16-18/what-is-blockchain-media/blockchain_aantonop.png)

Depending on the difficulty required to add new blocks to the chain, the fact that there is a reference to the previous block makes the chain resistant to mutation. The longer the chain becomes the more resistant it becomes to change. This makes the data on the blockchain extremely secure and reliable.

## How Is a Blockchain Secure?

What does it mean for a blockchain to be secure? Essentially it means that the information stored on the blockchain can't be altered. So how can a database completely built and maintained by strangers, some of them known bad actors, be so reliable? It comes down to two main things: smart planning of reward vs. penalty and decentralization.

### Game Theory

One of the properties that secures a blockchain is the balance between the difficulty in adding new blocks and the reward received for doing so. If the blocks are too difficult to create, no transactions will ever get confirmed. When the blocks are too easy to create, a malicious actor may roll back the chain, give themselves more funds, and then easily build the blocks back.

The analysis of how participants in a competitive system will act in regards to reward and punishment is referred to as game theory. Some people will say that the great invention of blockchain had little to do with cryptography or economics, but was instead a brilliant leap forward for global game theory in this interconnected world. What Satoshi did was use the inherent cost in creating electricity as the penalty and new Bitcoin as the reward. Which did two helpful things, it created and incentive to remain honest and a method by which new coins are generated.

When transactions are made on any cryptocurrency network they are first spread to other nodes and stored in a group waiting to be included in a block. This group of unconfirmed transactions is referred to as the "mempool." In order for these transactions to be included in a block, a certain amount of "work" must be done. The specialized hardware that does this work are referred to as a miners, and they use a massive amount of electricity to do this.

As long as the reward and difficulty remain in balance, it will always be in a miners best interest to confirm transactions according to the rules. By trying to break the rules, or rewrite part of the blockchain, the miners are penalized with enormous electricity costs. Even with an extreme amount of money available to anyone that does, no one has come up with an attack that is more profitable than simply following the rules.

### Decentralization

Another important feature of a healthy blockchain is to remain decentralized. Which means that there is diversification in the operation of nodes. Also, it's important that there are a sufficient number of nodes storing the full historical record of every transaction, these as called "full nodes." This diversification serves a few purposes, the first of which is to keep everyone else honest. If the only holders of the historical record are the ones that collude to change it, then doing so is trivial.

Another logical reason to have the blockchain distributed widely is to make it difficult to censor. You would have to get almost 100% of nodes to agree on any censorship being imposed. Without near majority you end up with two different versions of reality, with some nodes having the censored data and some having the uncensored data. These two subsets of nodes will stop communicating with each other creating a fork in the history and the coin, possibly with catastrophic effects for both sides.

This type of fork [actually happened](https://en.wikipedia.org/wiki/Ethereum_Classic#History) with Ethereum (ETH) when the devs decided to roll back the blockchain to fix a coding error and a portion of nodes refused to follow. The nodes that refused to follow now have their own coin: Ethereum Classic (ETC).

The final reason to keep the network decentralized is not about security, but for the overall health of the system. When new nodes come online, whether they are attempting to acquire the entire blockchain or just check the balance of a single address, they need to request this data from other nodes. If there is not a decent number of nodes out there to serve the data, then the ones that exist can become overloaded easily. This could Slow down or even completely stop the entire network.

## Why Use a Blockchain?

For decades our digital information has resided in databases which require minimal effort to maintain and are often the responsibility of just a single person. If you think about it, a blockchain is one of the least efficient ways possible to store data. So, why use all of the resources required to build and maintain a blockchain? So far no one has come up with another way to achieve trustless consensus.

In a traditional data storage system there is a lot of trust involved, even if you don't realize it. Think about your bank account for instance. When you spend or deposit money, that action is entered into the banks database. Your account balance is the sum of all the information in this database relating to your account. Unless an employee of the bank makes a mistake, this information tends to be accurate because the bank has a reputation uphold and often a legal responsibility.

In order to safeguard these centralized database huge amounts of effort are expended on security, both technological and physical. A blockchain, on the other hand, allows us to open this database for everyone to use and still remain secure. Participants are able to agree on a public ledger of data without needing to trust or impose legal responsibility on any of the parties involved.

The reason that you don't need to trust anyone on a proper blockchain is because you can trust the laws of thermodynamics. The fact that there is a cost to convert energy into electricity is the reason that it will always be ultimately unsuccessful to cheat.

## Summary

There is no doubt that the concept of using a blockchain for Bitcoin was profound, without it no cryptocurrency could exist as we know them today. Blockchains actually did even more than this though, they solved a crucial trust issue for the internet era in an elegant and secure way.

We now have the ability to share information with more security and dependability than we ever have. The full implications of this creation are still yet to be realized. I'm sure in the future, people will look back at the invention of the blockchain and compare it with the invention of the internet itself.

It's still very early in the life of blockchains, and outside of cryptocurrencies, it's not clear where they will be effective. Nevertheless, they're being tested in other areas and it is only a matter of time before some other industry is disrupted by them. Over the next few years it should be exciting to find out where else blockchains can thrive and how we can improve them.
