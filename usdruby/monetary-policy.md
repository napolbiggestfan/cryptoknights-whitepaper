# Monetary Policy

### Monetary Policy of CryptoKnights

We here define the Monetary Policy of CrytpoKnights as **how the Game Operator influences the in-game currency on blockchains**, presumably in DeFi instruments. How the Operator manages the currency in the server is referred to as the Fiscal Policy.

### Uniswap v3 & Concentrated Liquidity

Uniswap v3 offers [Concentrated Liquidity](https://docs.uniswap.org/protocol/concepts/V3-overview/concentrated-liquidity) to Liquidity Providers: they can **choose to concentrate their capital to a certain price interval**. This allows game operators to influence their token supply and price action in a public manner. The Monetary Policy will incentivize token trades to occur in a certain range while disincentivizing another. Other liquidity providers will react to the incentives accordingly, overall stabilizing the token price market.

### Core Liquidity

CryptoKnights will allocate a sizable amount of its RUBY reserve to a series of Uniswap v3 positions, ranging **from 0.1 USD per RUBY to infinity**. From the players' perspective, this can be interpretated as the Game Operator selling RUBY to them starting at 0.1 USD. As price goes up, the Game Operator sells more RUBY; when price goes down, the Game Operator buys back RUBY instead.

![Core Liquidity on 3 Blockchains | Ranging from Price=x to Infinity | Total Liquidity=y](<../.gitbook/assets/Graph1 Core Liquidity.png>)

**We do not intend to withdraw these Uniswap v3 positions** as it will destabilize the RUBY price. Only when we are migrating to another Automated Market Maker (AMM) will we adjust them.

### Extra Liquidity

We may **put extra liquidity into positions of other price intervals** so as to incentivize RUBY price to remain in a certain range.

![3 Extra Liquidity Positions Added](<../.gitbook/assets/Graph2 Extra Liquidity.png>)

For example, if RUBY price hits 10 USD and we find that price to be overvalued, we may put more RUBY into a position ranging from 10 USD per RUBY to higher. That way it would be harder for buyers to push RUBY price up furthermore.

On the other hand, if RUBY price then drops below 2 USD and we find that price to be undervalued, we may put more USD into a position ranging from 2 USD per RUBY to lower. That way we will be buying back more RUBY in that price range, similar to how a public company buys back treasury stocks.

### Liquidity on Different Blockchains

The "USD" mentioned above refer to USD **stablecoins**. We choose the preferrable stablecoin on whichever blockchains we support. Our Core Liquidity will be shared between those blockchains.

For example, we could provide a Uniswap v3 RUBY/USDC position on Ethereum while having a Uniswap v3 RUBY/XDAI position on Gnosis Chain, both using the same price interval.

Since RUBY can be **natively bridged between multiple chains**, arbitrageurs will keep RUBY price consistent between different markets.

### Other Liquidity Providers

Any RUBY holder can provide liquidity in AMMs, adding more liquidity to the pools. CryptoKnights  allocates a part of its RUBY reserve as **Liquidity Staking Rewards (LP Farming)** to Uniswap v2 LP stakers.

### Royalty Pools as a Tool to Reduce RUBY Supply

Royalty Pools are a type of DAO provided by [monet.market](https://monet.market/) to split royalties and act as AMMs for NFTs on the secondary market. We will launch new NFT Auctions that are denominated in RUBY, which will result in Royalty Pools **taking in RUBY from investors and locking them up**. This is another tool for CryptoKnights to reduce the RUBY supply in the token economy.

We call this **Monet-ary Policy**. 😜
