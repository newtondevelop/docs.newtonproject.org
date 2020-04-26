Wallet Protocol
===


## [Newpay-android-example](https://github.com/newtondevelop/newpay-android-example)

Newpay android example 是 Newpay android 客户端的 demo，可以参考该项目开发自己的 Newpay Android 钱包。

### [Newpay-keystore-java](https://github.com/newtondevelop/newton-keystore-java)

该库 fork 自 [Bitcoinj](https://github.com/bitcoinj/bitcoinj), 以便支持 [bip44](https://github.com/satoshilabs/slips/blob/master/slip-0044.md) 协议, 是 [Newpay-android-example](#Newpay-android-example) 依赖的一个基础库。其中修改[Bitcoin seed](https://github.com/bitcoinj/bitcoinj/blob/master/core/src/main/java/org/bitcoinj/crypto/HDKeyDerivation.java#L65) 为 [Nist256p1 seed](https://github.com/newtondevelop/newton-keystore-java/blob/master/core/src/main/java/org/bitcoinj/crypto/HDKeyDerivation.java#L65) 标识算法差异。

### [Newton-Web3j](https://github.com/newtondevelop/newton-web3j)

该库 fork 自 [Web3j](https://github.com/web3j/web3j), 详见 [README.rst](https://github.com/newtondevelop/newton-web3j/blob/newton/README.rst)

## [Newpay-ios-example](https://github.com/newtondevelop/newpay-ios-example)

Newpay ios example 是 Newpay ios 客户端的 demo，可以参考该项目开发自己的 Newpay IOS 钱包。

### [Newpay-crypto-ios](https://github.com/newtondevelop/newpay-crypto-ios)

### [Newpay-contract-utility-ios](https://github.com/newtondevelop/newpay-contract-utility-ios)

### [Newpay-keystore-ios](https://github.com/newtondevelop/newpay-keystore-ios)

## [Newchain-sdk-example](https://github.com/newtonproject/newchain-sdk-example)

This document describes how to get started with Newton's NewChain SDK.

## [HD-Wallet-Python](https://github.com/weixuefeng/newton-bip44-python)

This repo support the bip44 protocol about newpay wallet with python.
