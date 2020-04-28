# Wallet Protocol

- [Libraries and Utils](#libraries-and-utils)
- [Examples](#examples)


## Libraries and Utils

### Java

- #### Newton web3j for Java

  This library is forked from [web3j](https://github.com/web3j/web3j). 

  See more at **[newton-web3j](https://github.com/newtondevelop/newton-web3j/tree/newton)**.

### Android 

- #### Newton web3j for Android

  This library is forked from [web3j](https://github.com/web3j/web3j). 

  See more at **[newton-web3j](https://github.com/newtondevelop/newton-web3j/tree/newton-android)**(It\`s in the same repo with java library but in different branch).

- #### NewPay keystore for Java

  This library is forked from [Bitcoinj](https://github.com/bitcoinj/bitcoinj), which is to support [bip44](https://github.com/satoshilabs/slips/blob/master/slip-0044.md) protocol. And it\`s a basic library for [NewPay Android example](https://github.com/newtondevelop/newpay-android-example) to depend on.

  We changed [Bitcoin seed](https://github.com/bitcoinj/bitcoinj/blob/master/core/src/main/java/org/bitcoinj/crypto/HDKeyDerivation.java#L65) to [Nist256p1 seed](https://github.com/newtondevelop/newton-keystore-java/blob/master/core/src/main/java/org/bitcoinj/crypto/HDKeyDerivation.java#L66).

  See more at **[newpay-keystore-java](https://github.com/newtondevelop/newton-keystore-java)**.

### iOS

- #### Newpay Crypto iOS

  A CocoaPods wrapper around the [trezor-crypto](https://github.com/trezor/trezor-crypto) C library.

  See more at **[newpay-crypto-ios](https://github.com/newtondevelop/newpay-crypto-ios)**.

- #### Newpay Contract Utility

  Core Ethereum data structures and algorithms, which is forked and modified from [trust-core](https://github.com/trustwallet/trust-core).

  See more at **[newpay-contract-utility-ios](https://github.com/newtondevelop/newpay-contract-utility-ios)**.

- #### NewPay Keystore for iOS

  A general-purpose Ethereum keystore for managing wallets, which is forked and modified from [trust-keystore](https://github.com/trustwallet/trust-keystore).

  See more at **[newpay-keystore-ios](https://github.com/newtondevelop/newpay-keystore-ios)**.

### Python

- #### Newton BIP44 Python

  This repo support the bip44 protocol about newpay wallet with python.

  See more at **[newton-bip44-python](https://github.com/weixuefeng/newton-bip44-python)**.

## Examples

### NewChain SDK example

  This document describes how to get started with Newton's NewChain SDK.

  See more at **[newchain-sdk-example](https://github.com/newtonproject/newchain-sdk-example)**.

### Android

- #### NewPay Android example 

  This is an Android demo of Newpay. You can refer to this demo to build your own Newpay Android wallet.

  See more at **[newpay-android-example](https://github.com/newtondevelop/newpay-android-example)**.

### iOS

- #### NewPay iOS example

  This is an iOS demo of Newpay. You can refer to this demo to build your own Newpay iOS wallet。

  See more at **[newpay-ios-example](https://github.com/newtondevelop/newpay-ios-example)**.

### Java

- #### Java example

  Example of NewChain SDK for java.

  See more at **[Java example](https://github.com/newtondevelop/newton-example-java)**.

### Node

- #### Node example

  Example of NewChain SDK for node.

  See more at **[node example](https://github.com/newtonproject/newchain-sdk-example/tree/master/examples/node)**.

### Python

- #### Python example

  Example of NewChain SDK for python.

  See more at **[python example](https://github.com/newtonproject/newchain-sdk-example/tree/master/examples/python)**.

## Others

### [NewChain Address Identifier (NAI)](https://github.com/newtonproject/newchain-sdk-example/blob/master/address_standards.md)

This documentation explains the address identification system used by NewChain, the blockchain behind Newton's ecosystem.

### [NewChain RPC API Reference](https://github.com/newtonproject/newchain-sdk-example/blob/master/RPC_API_reference.md)

This documentation explains the RPC api which is supported by NewChain.

### [NewChain IDs for Different Environments](https://github.com/newtonproject/newchain-sdk-example/blob/master/chain_id.md)

This documentation explains the chain ID in different environments.

