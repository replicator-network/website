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
  owner = "Replicator Network 👾"
  date = "2019"
  license = "cc-by-nc-sa-4.0"
+++

Replicator Network address: `cosmosvaloper1et77usu8q2hargvyusl4qzryev8x8t9wwqkxfs`

Commission rate: 0%

Delegate using [gaiacli](https://hub.cosmos.network/docs/gaiacli.html):

{{< hackcss-alert >}}
{{< highlight shell >}}
$ gaiacli tx staking delegate \
cosmosvaloper1et77usu8q2hargvyusl4qzryev8x8t9wwqkxfs 10000uatom \
--from <delegatorKeyName> --gas auto --gas-prices 0.025uatom
{{< /highlight >}}
{{< /hackcss-alert >}}

{{< hackcss-alert type="warning" >}}
<strong>Note:</strong> You may need to add <code>--gas-adjustment 1.5</code> if the above fails due to insufficient gas. See {{< external href="https://hub.cosmos.network/docs/delegator-guide-cli.html#a-note-on-gas-and-fees" text="A Note on Gas and Fees" />}}
{{< /hackcss-alert >}}

<!--more-->
