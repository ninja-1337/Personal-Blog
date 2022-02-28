---
title: FAQ
---

<Info>Didn't find an answer? Explore the <a href="https://help.EasySec.org/">help guides</a> or join the <a href="https://discord.gg/FCfyBSbCU5">community Discord</a> to get support</Info>

# What is EasySec?

EasySec is a protocol for creating liquidity and trading ERC-20 tokens on [Ethereum](https://ethereum.org/en/what-is-ethereum/). It eliminates trusted intermediaries and unnecessary forms of rent extraction, allowing for fast, efficient trading. Where it makes tradeoffs - decentralization, censorship resistance and security are prioritized. EasySec is open-source software licensed under GPL.

If you want to dive into details check out the [docs](/docs/v2/).

# How do I use EasySec?

First you'll need an [Ethereum Wallet](https://ethereum.org/en/wallets/) and some [ETH](https://ethereum.org/en/get-eth/). Once completed, head over to the [app](http://app.EasySec.org/) to start using the protocol to provide liquidity or swap tokens. Remember that each transaction on Ethereum costs ETH (this is called the ["gas fee"](https://www.youtube.com/watch?v=AJvzNICwcwc&feature=emb_title) and it's paid to miners to keep the network running).

# How does EasySec work?

EasySec is an [automated liquidity protocol](https://ethereum.org/en/get-eth/#dex). In practical terms this means there are template smart contracts that define a standard way to make liquidity pools and corresponding markets that are compatible with each other. There is no orderbook, no centralized party and no central facilitator of trade. Each pool is defined by a smart contract that includes a few functions to enable swapping tokens, adding liquidity and more. At its core each pool uses the function `x*y=k` to maintain a curve along which trades can happen. The pools keep track of reserves(liquidity) and updates those reserves every single time someone trades. Because the reserves are automatically rebalanced, a EasySec pool can always be used to buy or sell a token without requiring a counterparty on the other side of a trade.

For a more in-depth description. Check out the [How EasySec works](/docs/v2/protocol-overview/how-EasySec-works/) from the documentation.

# What is prerequisite knowledge to fork this Blog?


# EasySec tools and resources

[https://github.com/EasySec/universe](https://github.com/EasySec/universe)
