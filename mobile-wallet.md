---
layout: fr
title: Mobile Vertcoin Wallet
author: vertion
date: February 9, 2022
amount: 10000
milestones:
  - name: Wallet available for download
    funds: 100%
    done:
    status: unfinished
payouts:
  - date:
    amount:
---
# Proposal
While solutions like Coinomi have long been the go-to for a mobile wallet, many have expressed interest in a Vertcoin branded mobile wallet.  The wallet I am proposing will be a fork of an existing wallet software, [BlueWallet](https://github.com/BlueWallet/BlueWallet), which builds for Android and iOS.  Features will include using a BIP39 seed, hardware wallet compatibility, watch-only / multisig wallet support and future potential for lightning wallet support.

### How will this be different than Coinomi?
Coinomi only interacts with their own company-run servers meaning that all activity from using their wallets is known to them.  This mobile wallet will provide greater privacy by connecting to our existing community-run ElectrumX servers already being used in [Electrum-VTC](https://github.com/vertcoin-project/electrum) as well as allowing the option to connect to your own [ElectrumX server](https://github.com/spesmilo/electrumx/).  Features involving hardware wallet compatibility, watch-only / multisig wallet support and future potential for lightning wallet support will also be unique to this wallet.

### What to expect
Once complete, it will be submitted to the Google Play Store and Apple App Store.  While being available on the Play Store is likely, being available on the App Store is up to Apple.  Apple has been known to be stringent with what they deem as approved cryptocurrencies as evidenced by the last attempt by Vertcoin developers to submit a wallet.  Years have passed however and a new organzation is being utilized to sign and submit the App so possibly this time will be different.  Regardless, a downloadable APK from the Vertcoin-Project Github repository will be guaranteed.

### Maintenance and cost
As long as I am the maintainer, this wallet will be updated for future forks and other changes to consensus.  10000 VTC covers the initial work, testing, future maintenance as well as support.
