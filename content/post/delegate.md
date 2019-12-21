+++
title = "Delegate to Replicator Network"
date = 2019-12-21T13:35:44-08:00
description = "How to stake Atoms on Cosmos Hub by delegating to Replicator Network."
draft = false
toc = false
categories = ["cosmos"]
tags = ["delegate", "atom"]
images = [
  "https://source.unsplash.com/collection/983219/1600x900"
] # overrides site-wide open graph image
[[copyright]]
  owner = "👾replicator.network"
  date = "2019"
  license = "cc-by-nc-sa-4.0"
+++

Replicator Network's validator operator address is `cosmosvaloper1et77usu8q2hargvyusl4qzryev8x8t9wwqkxfs`.

Atoms can be staked on Cosmos Hub by delegating to Replicator Network. 

Using [`gaiacli`](https://hub.cosmos.network/docs/gaiacli.html):
```sh
$ gaiacli tx staking delegate \
cosmosvaloper1et77usu8q2hargvyusl4qzryev8x8t9wwqkxfs 10000uatom \
--from <delegatorKeyName> --gas auto --gas-prices 0.025uatom
```

<!--more-->
