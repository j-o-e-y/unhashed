# MyEtherWallet Review and User-Guide

MyEtherWallet (MEW) is a browser tool for interacting with the Ethereum network. You can perform a range of procedures with MEW including receiving, sending, and storing Ether (ETH), Ether Classic (ETC), and other [ERC-20](https://en.wikipedia.org/wiki/ERC20) tokens. Originally released in 2015, MEW is open source, free, and in active development on [Github](https://github.com/kvhnuke/etherwallet).

MEW provides users with a light weight method of communicating with the Ethereum blockchain. The benefits of MEW are that you don't have to download or store the entire blockchain, all of your private information is generated and stored on your computer, and MEW can be used in combination with [hardware wallets](https://unhashed.com/best-bitcoin-ethereum-altcoin-wallet-reviews/#hardware) for added security.

This review of MyEtherWallet will cover:

+ Ease of Use
+ Aesthetics
+ Security
+ Unique Features
+ User Guide
+ Summary

## MyEtherWallet Review

### Ease of Use

MyEtherWallet's main benefit is its ease of use. With MEW you can create a new wallet and be interacting with the Ethereum network within minutes. MEW runs in a web browser and uses very few resources of your computer.

As opposed to other wallet solutions, MEW does not require downloading blockchain data. Storing the entire blockchain requires over 100GB of disk space and can take weeks to download. According to [some reports](https://ethereum.stackexchange.com/a/826), consumer grade hardware isn't even capable of downloading and storing the entire Ethereum chain at this point.

The fact that MEW has a small footprint, it is quick to start using, and gives the user so many tools has made it one of the most popular ways to store and use ETH and tokens.

### Aesthetics

MyEtherWallet's primary objective is not design, and at first you really notice it. The first impression is a busy page with a red warning at the top which doesn't ever go away.

![aesthetic pic](/reviews-guides/myetherwallet_02-04-18/myetherwallet-media/myether_aesthetic_cropped.png)

After using the wallet a few times you don't notice the design shortcomings as much. Once you become familiar with the wallet you'll find that the features outshine the style.

### Security

MyEtherWallet leaves security completely in your hands. The wallet is only a tool which connects to the Ethereum network and performs some useful tasks. Unlike most wallets, it does not store private keys. Instead MEW uses javascript code to generate and store private keys on your computer.

The positive side of this is that your sensitive information doesn't reside on web servers which become targets for hackers. On the other hand, if your computer is compromised your keys could be stolen. That is why it's [recommended](https://myetherwallet.github.io/knowledge-base/hardware-wallets/hardware-wallet-recommendations.html) to use a hardware wallet in combination with MEW.

### Unique Features

MyEtherWallet offers many features that you won't find in other wallets. You can get an idea of how much this wallet can do by taking a look at the navigation bar.

![unique features pic](/reviews-guides/myetherwallet_02-04-18/myetherwallet-media/myether_unique-features_cropped.png)

A few of the most useful and powerful features are: swapping between Bitcoin (BTC) and Ether (ETH), creating and interacting with smart contracts, registering with the Ethereum Name Service (ENS), and selling registered domains. These types of services usually require visiting an external website. Achieving this all within a light wallet is pretty rare.

## MyEtherWallet User Guide

### 1. Create a new wallet.

In a web browser, go to https://myetherwallet.com. You'll have to click through about 10 pages of introductions, warnings, and best practices. It can be a little annoying, but the information provided is useful.

![firstrun pic](/reviews-guides/myetherwallet_02-04-18/myetherwallet-media/myether_firstrun_cropped.png)

After the pop-ups, the first page you're presented with is the `New Wallet` page. Here you set a password and click the `Create New Wallet` button. Always keep a backup of your password.

![new wallet button pic](/reviews-guides/myetherwallet_02-04-18/myetherwallet-media/myether_new-wallet_cropped.png)

### 2. Backup your keystore file.

You'll be brought to the first backup of your wallet. This backup will be an encrypted keystore file. This file, in combination with your password, will unlock your wallet. If a thief gets this file they won't be able to use it without knowing or guessing your password.

Click `Download Keystore File (UTC / JSON)` button, then select the download location and filename.

When the download is finished you can click the `I understand. Continue.` button.

![keystore backup pic](/reviews-guides/myetherwallet_02-04-18/myetherwallet-media/myether_keystore-backup_cropped.png)

### 3. Backup your private key.

This is the last of the standard backup procedures, saving your private key. This key is unencrypted and does not need a password to use. If you lose your keystore file and/or your password, the private key will still give you access to your funds. If a thief gets your private key they don't need anything else to steal your funds.

Click the `Print Paper Wallet` button.

![privkey backup pic](/reviews-guides/myetherwallet_02-04-18/myetherwallet-media/myether_privkey-backup_cropped.png)

You'll be brought to another tab where you will see what your printable private key looks like.

![print privkey pic](/reviews-guides/myetherwallet_02-04-18/myetherwallet-media/myether_privkey-paper_cropped.png)

When you are ready to print, close this tab and you will be see your print options. After printing you can click the `Save Your Address.` button.

### 4. Access your wallet.

Now that you have secured two backup types, it's time to test that you can successfully unlock your wallet with them. The next page your brought to will give you some options for unlocking your wallet. You may select `Keystore / JSON File` or `Private Key` since you have both.

If you choose to use the keystore file, you'll need the file and your password. Once you have selected your keystore file and entered your password you can click the `Unlock` button.

![unlock keystore pic](/reviews-guides/myetherwallet_02-04-18/myetherwallet-media/myether_login-keystore_cropped.png)

If you choose to use your private key, you will not need a password. Once you have entered your private key you can click the `Unlock` button.

![unlock privkey pic](/reviews-guides/myetherwallet_02-04-18/myetherwallet-media/myether_login-privkey_cropped.png)

After successfully unlocking your wallet you will be able to scroll down to where you can see your address for receiving Ether and tokens. You can also check your balance and make additional backups here.

![unlocked wallet pic](/reviews-guides/myetherwallet_02-04-18/myetherwallet-media/myether_unlocked-wallet_cropped.png)

### 5. Sending Ether.

To send Ether to another address click on `Send Ether & Tokens` in the navigation bar. You'll be asked to unlock your wallet again, you can use either your keystore file or private key.

Now you can enter the details of your transaction. You'll need to enter the recipients address and the amount to send. `Gas Limit` is the transaction fee, and should remain default.

![send details pic](/reviews-guides/myetherwallet_02-04-18/myetherwallet-media/myether_send-addramt_cropped.png)

Review the details and click the `Generate Transaction` button. You'll be shown what the completed transaction looks like before it's broadcast to the network. When you're ready click the `Send Transaction` button.

![send pushtx](/reviews-guides/myetherwallet_02-04-18/myetherwallet-media/myether_send-pushtx_cropped.png)

This will be your last chance to review the transaction details and be sure you want to broadcast it. Once a transaction is broadcast it is irreversible. When you are positive about the details you can click the `Yes, I am sure! Make transaction.` button.

![send pushtx verify](/reviews-guides/myetherwallet_02-04-18/myetherwallet-media/myether_send-pushtx-verify_cropped.png)

At this point you'll be brought back to the send page where you will see a pop-up explaining how to track your payment. Depending on network congestion, the verification time of your transaction can vary. Click on the links in the pop-up to find out details about your transaction verification.

![send pushtx success](/reviews-guides/myetherwallet_02-04-18/myetherwallet-media/myether_send-pushtx-success_cropped.png)


## MyEtherWallet Review Summary

In 3 years MyEtherWallet has become one of the most popular ways to use ETH, ETC, and tokens. You don't have to download a ton of data and you can start using the wallet almost immediately. Although the interface can be a little cluttered at first, you will easily see past that once you start using it.

MEW has a low barrier to entry, all you need is a web browser. As a matter of fact, you can even use it [offline](https://myetherwallet.github.io/knowledge-base/offline/running-myetherwallet-locally.html) or as [cold storage](https://myetherwallet.github.io/knowledge-base/offline/ethereum-cold-storage-with-myetherwallet.html). The robust tool set, and the fact that it can be used in combination with hardware wallets makes MyEtherWallet an attractive choice for both newcomers and veterans alike.