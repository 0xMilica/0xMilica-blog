---
title: Creating light nodes using substrate-connect
date: 2022-12-15 08:28
tags:
  - light nodes
  - wallets
  - substrate
  - metamask
  - parity
description: How decentralised are blockchain nodes right now in web3, and how
  is Parity tackling this issue
---
![Stefan Sopic presenting substrate_connect](/media/1671302502487.jpeg "Stefan Sopic presenting substrate_connect")

I had the pleasure of joining the discussion about light nodes integrated into wallets hosted by [Stefan Sopic](https://twitter.com/sopke86) from [Parity Technologies](https://twitter.com/paritytech).

Many web3 folks are not quite aware that things are pretty centralised in our decentralised world.

![MetaMask blocked certain countries](/media/screenshot-2023-01-10-at-02.26.18.png "MetaMask blocked certain countries")

## Decentralisation in reality

[MetaMask](https://twitter.com/MetaMask), behind the scenes, is using Infura infrastructure.

Stefan made a solid point that the focal point of all the requests* MetaMask handles is in fact based on the East Coast, USA, through the same blockchain node provider.

If that particular provider happens to experience some issues, users would find themselves unable to use the network 🤯

By mapping out the requests, it makes it possible to create a connection between IP addresses and multiple wallets (given the fact that MetaMask recently announced IP address collection) 🤔

![How is Infura used by MetaMask](/media/matamask-i-infura-za-blog.png "How is Infura used by MetaMask")

## Path to decentralisation

Parity is developing substrate_connect.

They enable running a light node for each individual user, therefore preventing a central point of failure.

![substrate_connect](/media/subs-connect.png "substrate_connect")

Kudos to Parity - for developing both decentralised and more private network 👏



\*𝘶𝘯𝘭𝘦𝘴𝘴 𝘵𝘩𝘦 𝘦𝘯𝘥-𝘶𝘴𝘦𝘳 𝘰𝘱𝘵𝘴 𝘵𝘰 𝘱𝘳𝘰𝘷𝘪𝘥𝘦 𝘵𝘩𝘦𝘪𝘳 𝘰𝘸𝘯 𝘣𝘭𝘰𝘤𝘬𝘤𝘩𝘢𝘪𝘯 𝘯𝘰𝘥𝘦