#### Pomp – Do Kwon

[apple](https://podcasts.apple.com/us/podcast/880-the-%2410-billion-stablecoin-bet-on-the/id1434060078?i=1000555093692)
[spotify](https://open.spotify.com/episode/1NRaBX1RmHwB3bK1JkRJCu?si=AQLuMwqGQG-QCg6ptML9OQ)
 
#### Terra
* Issues with existing stablecoins
  * centralized – backed by fiat dollars for every issuance
  * based on leverage
* Terra is algorithmic; uses arb. incentives
* LUNA
  * price volatility in UST is absorbed by supply of LUNA
  * users can mint 1UST by burning $1 in LUNA (and vice versa)
  * LUNA expands / contracts its supply to facilitate mints / redemptions in UST
* most buy from existing exchanges, or staking rewards
* algorithmic stable coin risks
  * 3 things when thinking about stablecoins
    * decentralization
    * stability
    * scalability
  * USDC, USDT could hypothetically absorb all demand volatility (since they’re backed)
  * algo s.c. are more brittle: too much of the paired asset could get printed -> death spiral
* death spiral
  * [DSD](https://dynamicsetdollar.medium.com), [basis cash](https://basis.cash), [Tomb Finance](https://tomb.finance): failed due to no inherent driver of demand for the stablecoin except internal incentives
  * [iron finance](https://iron.finance): offered 12k% APR; collapsed if sufficient capital left
  * Terra focused on low-vol use cases with many real-world users
    * UST could be spent at retailers across the countries (Korea, Vietnam)
  * [Pylon](https://medium.com/terra-money/pylon-protocol-e2a622ac553e), [Anchor](https://www.anchorprotocol.com/#), [Mirror](https://mirror-protocol.medium.com): share characteristic of users not using as an ‘endogenous recursive vehicle’; lots of stickiness
* Bitcoin backing
  * economics: can no longer control use cases / apps built on Terra
    * not all are low-vol (options protocols, rate swaps)
* LUNA reserves
  * multisig, steadily buying BTC (<$1B), $1.6B USDT, ~$1B UST (could liquidate to Curve easily)
* $3B-$10B?
  * plan to move $3B to BTC
  * bootstrapping the initial reserve
  * use part of UST to build BTC reserve (40%, 50%)
  * UST grows, more BTC gets stocked in reserve
    * this kicks in when UST demand needs to be absorbed
* what % diverts to BTC (vs burning LUNA)?
  * on-chain parameter determined thru governance
  * this exists: param determines what % of seigniorage is diverted to common good purpose
* what happens to BTC in UST reserves?
  * similar structure to AMM; able to trade UST against it
  * special AMM, subscribes to oracle price of BTC (~30sec). you can trade $1BTC and mint 1UST; or trade 1UST and get $0.99BTC. 
  * spread guarantees that redemption is only used when UST depegs. (arbs will accepts <$1 BTC for their UST, burning supply)
* BTC as a backing asset builds strength with other communities in digital assets space
* 1 takeaway:
  * building a better currency for all of crypto.
