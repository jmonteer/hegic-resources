# Hegic Frequently Asked Questions

Below is a compilation of the most commonly asked questions about Hegic's ecosystem. If you still have any questions fter reading through the FAQ please reach out on [Discord](https://discordapp.com/invite/znjdj8q) or [Telegram](https://t.me/HegicOptions).

## THE HEGIC TOKEN

    - What is the HEGIC token contract address? 
        - [0x584bC13c7D411c00c01A62e8019472dE68768430](https://etherscan.io/token/0x584bC13c7D411c00c01A62e8019472dE68768430)
    - Why is a token needed?
        - You need HEGIC to buy a staking lot and for Protocol's governance purpose. More use cases will arise. 
    - What is the total supply?
        - Total supply is **3,012,009,888 HEGIC**. This is the total amount of HEGIC that will ever exist. 
    - What are the benefits of holding HEGIC?
        - HEGIC holders will be able to buy a staking lot. Also, in the future, it will be the way to delegate governance of the Hegic Protocol to the community of token holders. TBD
    - What is the fully diluted total market cap?
        - Fully Diluted total market cap is always changing. The way to calculate it is: HEGIC price * TOTAL SUPPLY. You can check these variables in [hegic.co](https://www.hegic.co/)
    - What is the market cap?
        - Market cap is always changing. The way to calculate it is: HEGIC price * TOTAL CIRCULATING SUPPLY. You can check these variables in [hegic.co](https://www.hegic.co/)
    - How will total supply be distributed?
        - Total supply will be split up in 6 blocks: 
            - 3% will be used in IBCO (read below for more info)
            - 22% will be used to provide liquidity to BC (read below for more info)
            - 5% will be allocated to provide liquidity to a DEX liquidity pool
            - 40% will be distributed as rewards to Hegic Protocol users (option holders and liquidity providers)
            - 10% will be allocated to the Hegic Development Fund (HDF, read below). This amount is subject to linear vesting (read below) among 48 months after IBCO end date (12/09/2020 19:00:00 UTC)
            - 20% will be allocated to reward Early Contributors (read below). This amount is subject to linear vesting (read below) among 24 months after IBCO end date (12/09/2020 19:00:00 UTC)
    - Should I buy HEGIC?
        - Did you do your own research? To know if you did, can you answer these questions?
            - What is an option? What is Call option? What is Put option?
            - When does option holders earn money? 
            - Who is selling options in Hegic?
            - Who are liquidity providers? 
            - How much money can liquidity providers lose?
            - What are the benefits of holding HEGIC?
            - What are the risks of holding HEGIC?

## TRADING HEGIC / BUYING HEGIC

    - How Can I buy/sell $HEGIC?
        - Currently $HEGIC is available only on decentralized exchanges. You can purchase/sell HEGIC at:
            - [Uniswap](https://exchange.sushiswapclassic.org/#/swap?outputCurrency=0x584bc13c7d411c00c01a62e8019472de68768430)
            - [Sushiswap](https://exchange.sushiswapclassic.org/#/swap?outputCurrency=0x584bc13c7d411c00c01a62e8019472de68768430)    
        - $HEGIC can also be purchased/sold through the Bonding Curve in the [TOKEN HOLDER] tab on [hegic.co](https://www.hegic.co/)
            - Each time $HEGIC is purchased through the Bonding Curve, the price of $HEGIC on the curve increases by a fixed value. This fixed value is set to 0.00000000001 ETH and can never be changed.
            - Each time $HEGIC is sold through the Bonding Curve, the price of $HEGIC on the curve decreases by a fixed value. This fixed value is set to 0.00000000001 ETH and can never be changed. 
            - Note: There is also a 10% swap fee for selling HEGIC on the bonding curve that is distributed 50/50 to staking lot holders and the Hegic Development Fund (HDF).
    - What is the Bonding Curve?
        - The Bonding curves is a new crypto economic token model that automates the relationship between price and supply. The bonding curve acts as a primary source of supply for the market as a protocol scales and demand for tokens starts to outpace the supply available to the market. Through a fixed relationship with price (described below), users can interact with the Bonding Curve to either 'buy up' the curve (thus minting new supply) or 'sell down' the curve (thus burning liquid supply). Such a mechanism allows for transparent price discovery and allows supply to inflate/contract with market demand. 
    - Bonding Curve example:
        - When demand for HEGIC tokens increase on secondary markets (exchanges) and price inflates beyond that of the Bonding Curve, users can interact with the Bonding Curve to mint HEGIC at a pre-defined price, thus increasing supply in markets and alleviating some of the demand pressure.
        - Similarly, if the supply of HEGIC tokens decreases on secondary markets (exchanges) and price decreases below that of the Bonding Curve, users can burn tokens by selling into the curve (this assumes the Bonding Curve's price is above the floor as defined in the IBDO - see below for explanation).
    - What is the initial price in BC?
        - The initial price in Bonding Curve is 0.000356600004999993 ETH (~$0.13) per HEGIC. This was been set from the resulting price of the IBCO. 
    - Will you list $HEGIC on Centralized Exchanges?
        - There are currently no plans to list HEGIC in a Centralized Exchange.
        - If a Centralized Exchange chooses to list Hegic that would be at their discression. 
    - What is the price oracle for options pricing and settlement?
        - Hegic uses ChainLink oracles for the market prices of underlying assets. Currently Implied Volatility (IV) is set manually but is expected to become automated using an IV oracle from ChainLink once available.

## OPTIONS ON HEGIC

    - What is a call/put option?
        - Please refer to the [Gitbook](https://hegic.gitbook.io/start/).
    - How do I buy call/put options?
        - Please refer to the Gitbook for a [detailed walkthrough](https://hegic.gitbook.io/start/guides/how-to-buy-a-call-option).
    - When is my option in profit?
        - A user will make a profit from option trading once the underlying asset's price exceeds the sum of the strike price plus the fee associated with purchasing the option.
    - When can I exercise my option?
        - Anytime your option is in the money (ITM) you can exercise your option. 
        - A call option is ITM once the underlying asset's price is higher than the strike price of the option.
        - A put option is ITM once the underlying asset's price is lower than the strike price of the option. 
        - NOTE: Users pay the fee for purchasing the option up front. Thus, ITM options are not profitable until the underlying asset's price is higher than the strike price + fee paid. Despite this, users should still exercise unprofitable ITM options before expiry as it will at least partially pay back the fee paid up front.
    - Exercising my options.
        - If your option is Out of The Money (OTM) you will not be able to exercise it since there is negative value in the option (i.e. you would have to pay more coin to exercise).
        - If your option is In The Money (ITM) at any time during the option's duration, you can manually exercise the option on the [HOLDERS] tab.
        - There is no option to partially exercise the option. You must exercise an option in its entirety when you decide to do so.
    - Do I need the capital to buy the underlying when exercising my options?
        - No, Hegic options do not pay out the underlying asset, rather just the difference between the price at the time of exercising and the strike price. The only requirement is enough gas to exercise the option. 
    - Why does my breakeven price keep changing?
        - The price of the option is denominated in ETH and is not translated into USD at the time of purchase. So as the price of ETH changes throughout the duration of your option, so to does the price of what you paid for the option (and thus your breakeven point). E.g. If you pay 0.1 ETH ($40) for an option and the price increases 10% during the contract, your breakeven price will go up $4 to reflect the higher price of ETH. 
    - What happens when my option expires?
        - Hegic options do not auto exercise. If your option is Out of The Money (OTM) at expiry, nothing will happen since there is no value in exercising the option. If you are In The Money (ITM) you will have to manually exercise the option before it expires or forego any potential upside that you might have received otherwise.
    - Can I trade my options on secondary markets?
        - Currently there is no ability to HEGIC trade options on secondary markets.
    - How are options priced? 
        - Option purchasers pay a premium and fixed fee (currently 1%) on top of the strike price that is pre-determined prior to purchase. Given the flexibility of Hegic options, this premium is variable but directly related to: 
            - The duration of the option is set by the option purchaser.
            - The strike price is set by the option purchaser.
            - Underlying asset pricing is obtained from ChainLink Oracles.
            - Implied volatility is currently obtained from Skew and manually updated but a plan to transition to ChainLink Oracles once they are implemented.
    - How do I earn HEGIC rewards as an options purchaser?
        - Options purchasers will be distributed HEGIC rewards proportionate to the size and duration of their options (please refer to the REWARDS section for more detail).


## BECOMING A LIQUIDITY PROVIDER (LP)

    - What is a liquidity pool?
        - A Liquidity pool is the aggregation of tokens that are locked into a smart contract. Liquidity pools are used to facilitate the trading of the asset(s) within the pool and provide deep levels of liquidity. 
    - What is providing liquidity?
        - Providing liquidity on Hegic will require a user to deposit either ETH or wBTC into one of the Hegic liquidity pools. Hegic utilizes an innovative bi-directional pool design (described below) that allows for a single liquidity pool to provide depth to both put and call option purchasers.
    - What are the benefits of providing liquidity?
        - By providing liquidity, a user is contributing to the usability and tradability of Hegic options. The liquidity provided is drawn upon by options purchasers to collateralize their trade. Once an option expires/executes, the liquidity that was drawn to collateralize the option is returned to/partially removed from/wholly removed from the pool for future trading. The premiums paid for purchasing an option also accrue and are paid to liquidity providers. If the premiums paid are higher than the payouts to options holders, the liquidity providers will accrue more value in ETH/wBTC proportionate to their share of the pool. For providing liquidity, options will receive rewards in HEGIC (described in the rewards section below). 
    - What are bi-directional pools?
        - HEGIC's bidirectional liquidity pool design is unique and innovative in DeFi. The base asset that is deposited in the pool can be utilized simultaneously for both selling put and call options in an automated fashion. By doing so, liquidity providers do not have to 'guess' which way price will move in the next weeks or hedge liquidity provision on the long and short side. 
    - How do I add liquidity?
        - Please refer to the Hegic Docs page for a [detailed walkthrough](https://github.com/jmonteer/hegic-resources/blob/main/docs/Becoming_an_LP.md)
        - NOTE: When providing liquidity, you are subject to a minimum 14 day lock-up period on your ETH/wBTC. The purpose of this is to maintain stability in the liquidity pool for options buyers.
    - What are write tokens (writeWBTC and writeETH)?
        - Write tokens are LP tokens a liquidity provider will receive once the deposit ETH or wBTC into the Hegic liquidity pools.
    - How do I stake liquidity?
        - Once liquidity is added to HEGIC pools you will need to stake it to start earning the HEGIC rewards. For information on how to do this please refer to the Gitbook for a detailed walkthrough (https://hegic.gitbook.io/start/) **We could add the guide I wrote to the Gitbook?**
    - How do I remove liquidity? 
        - To remove liquidity will take *up to 14 days* from the day you decide to do so! 
        - If you do not stake your liquidity (and forgo earning reward HEGIC (rHEGIC) tokens), you will be able to withdraw your write tokens 14 days after you first deposit ETH or wBTC. 
        - If you have staked write tokens, the 14 day lock timer will reset once you unstake your write tokens (which re-deposits them into your Ethereum wallet). 
        - To withdraw: Once the 14 days has passed, you will need to navigate to the [WRITERS] tab and under ///YOUR EARNINGS select WITHDRAW. By confirming the withdrawal, you will burn write tokens from your Ethereum wallet and receive the corresponding ETH or wBTC. 
        - In both scenarios, the earliest withdrawal date for write tokens sitting idle in your wallet will be displayed on the screen that pops-up when hit WITHDRAW on the [WRITERS] tab.
        - *Attention:* do not send write tokens to the contract address because you will lose your funds forever.
    - What is my risk exposure?
        - Being a liquidity provider, you are short volatility. What this means is that if price movements are not too significant, liquidity providers have little risk exposure. However, despite providing liquidity to both put and call options, if a significant market move occurs the profits from deep in the money options will be paid for by the liquidity providers. By nature, puts and calls have limited downside, but on big market moves can have significant upside. If for example the price of Ethereum pumps $200 within a week, put options will be out of the money and only lose the fee they initially payed at the time of purchase. However, call options will be deep in the money and their profits (claim to ETH) will be funded by the liquidity pool.
        - Liquidity providers can track their current profits/losses from providing liquidity on the [WRITERS] tab under ///YOUR EARNINGS. Here you will not only be able to observe your current profits or losses but also the upcoming Net Profit impact (to the pool and yourself) from all options if they were to expire at the current price of the underlying asset.
    - What rewards will I receive for being a LP?
        - Currently there are two types of rewards LP's receive:
            - LPs receive rHEGIC in proportion to their contribution to the liquidity pool.
            - LPs receive a share in the pool's premiums that are distributed after an option contract expires. 
        - For more information on rewards please refer to the rewards section below.
    - Are my LP rewards locked?
        - The pool premiums (ETH/wBTC) are not locked and can be claimed at any time. 
        - The reward HEGIC received (rHEGIC) for being an LP are currently locked and will start to become available once the cumulative on-chain trading volume on Hegic during the Phase I exceeds $100M or on the 11/11/2021. Once either of these events happen, rHEGIC will start vesting (unlocking) on a weekly basis (4.17% per week) for the next 6 months and vest.
    - I was a v1 LP, how do I withdraw from the early v1 LP pools?
        - You can now withdraw from v1 liquidity pools through this interface: https://v1.hegic.co/


## STAKING LOTS

    - What is a staking lot?
        - Staking lots represent a right to claim on the fees generated by the Hegic protocol. 100% of settlement fees in ETH and WBTC generated by the protocol are distributed among the staking lots holders. 
    - How many HEGIC do I need for a staking lot?
        - Each staking lot requires 888,000 HEGIC.
    - I do not have 888,000 HEGIC, can I still stake?
        - There are a few staking pools that have been independently developed and are not directly associated with Hegic so you should do your own risk analysis before providing funds to any of these pools. Lost funds from bad staking pools have nothing to do with Hegic.
            - [Jmonteers Hegic Staking](https://www.hegicstaking.co/)
            - [zLots Hegic Pools](http://zlot.finance/)
            - [Yearn Finance's vaults](https://twitter.com/Macarse/status/1324566137594617857)
    - How do I purchase a staking lot?
        - Holders with 888,000 HEGIC can navigate to the [TOKEN HOLDER] tab to purchase a staking lot. You will need to decide if you wish to stake within the wBTC or the ETH staking lot to partake in a share of the revenue generated by each lot.
    - Are HEGIC locked when deposited into a staking lot?
        - Once a staking lot is either staked into an ETH or wBTC lot there is a 1 day lockup.
        - Once the one day has passed, stakers are free to change or withdraw from staking lots.
    - Why stake HEGIC tokens?
        - Staking lots will receive three types of rewards:
            - wBTC/ETH: 1% of each option's size will be evenly distributed amongst each asset specific staking lots (e.g. all 1% of all wBTC option size will be distributed between wBTC staking lots). These rewards can be withdrawn at any time.
            - HEGIC: Asset's raised from the IBCO will be allocated into liquidity pools over the next months. The LP HEGIC rewards earned from these assets will be evenly distributed to all staking lot holders. Since LP rewards have a 6 month vesting schedule, so too will these HEGIC rewards to staking lot holders.
            - HEGIC: Each time HEGIC is sold through the bonding curve, a 10% swap fee is incurred. Half of this fee is then allocated to staking lot holders proportionally.


## REWARDS AND rHEGIC

    - What are rewards?
        - In Hegic, rewards are used to let the users of Hegic Protocol to become its owners, aligning interests of token holders and users. A total of 1,204,809,000 HEGIC will be distributed as a reward to Protocol Users (both Option holders and Liquidity Providers).
    - How can I access rewards from participating in Hegic?
        - The total amount of Hegic rewards to be distributed over the next two years is 1,204,809,000.
        - There are three ways that users of Hegic will get rewards:
            - Liquidity providers (LPs) will receive liquidity mining rewards over a 2 year period (80% of total rewards or 963,847,200) in exchange of providing liquidity to Pools. Rewards will be distributed proportionally to the total Liquidity in Pools.
            - Option holders will receive utilization rewards over a 2 year period (20% of total rewards or 240,961,800 HEGIC) for holding options and using the Protocol. Rewards will be distributed proportionally to the total value and duration of purchased Options.
            - Hegic staking lots will indirectly be distributed rewards as well. The LP rewards earned by the IBCO contributions that are deposited into liquidity pools will be distributed to Staking Lot holders. $500K will be added to both the wBTC liquidity pool and the ETH liquidity pool every two weeks for 6 months as outlined in the v888 launch announcement (https://medium.com/hegic/hegic-v888-is-live-1c790de1b38).
    - How are rewards scheduled?
        - Rewards will be released in three phases.
        - During Phase I (10/10/2020 — 10/10/2021), 50% of rewards will be released (602,250,000 HEGIC).
            - Rewards will be released on daily basis in a linear fashion (i.e. up to 1,650,000 HEGIC per day)
            - 80% of daily rewards (1,320,000) will be distributed to LPs in proportion to the liquidity they provide. This is split evenly (660,000 HEGIC per Pool) between the wBTC Pool and the ETH Pool.
            - Up to 20% of daily rewards (330,000) will be distributed to Options purchasers relative to their position size and duration (please refer to the 'How many rewards do I receive?' sub-section below for more detail).
        - During Phase II (10/10/2021 — 10/10/2022), 37.6% of rewards will be released (452,600,000 HEGIC).
            - Rewards will be released on daily basis in a linear fashion (i.e. up to 1,240,000 HEGIC per day)
            - 80% of daily rewards (990,000) will be distributed to LPs in proportion to the liquidity they provide. This is split evenly (495,000 HEGIC per Pool) between the wBTC Pool and the ETH Pool.
            - Up to 20% of daily rewards (250,000) will be distributed to Options purchasers relative to their position size and duration (please refer to the 'How many rewards do I receive?' sub-section below for more detail).
        - During Phase III (10/10/2022 — 10/10/2023), 12.4% of rewards will be released (149,650,000 HEGIC).
            - Rewards will be released on daily basis in a linear fashion (i.e. up to 410,000 HEGIC per day)
            - 80% of daily rewards (330,000) will be distributed to LPs in proportion to the liquidity they provide. This is split evenly (165,000 HEGIC per Pool) between the wBTC Pool and the ETH Pool.
            - Up to 20% of daily rewards (800,000) will be distributed to Options purchasers relative to their position size and duration (please refer to the 'How many rewards do I receive?' sub-section below for more detail).
    - What is rHEGIC?
        - rHEGIC is the reward HEGIC received for being a liquidity provider. They represent a claim to HEGIC at a future point in time (see 'Are my LP rewards locked?') in the ratio of 1 rHEGIC = 1 HEGIC.
        - rHEGIC cannot be used for staking in staking lots.
        - rHEGIC can be claimed and issued to your Ethereum wallet but will not start to be redeemable for HEGIC until the cumulative on-chain trading volume on Hegic during the Phase I exceeds $100M or on the 11/11/2021.
        - Once either of these milestones is reached, holders will be able to convert their rHEGIC to HEGIC over a 24 week period (4.17% each week).
        - The rHEGIC contract is [0x47C0aD2aE6c0Ed4bcf7bc5b380D7205E89436e84](https://etherscan.io/token/0x47C0aD2aE6c0Ed4bcf7bc5b380D7205E89436e84)
    - Does rHEGIC have any value?
        - rHEGIC has zero value, zero price and zero utility at the minute. It is an IOU for future HEGIC tokens.
    - How do I claim rewards on Hegic?
        - LP liquidity mining rewards (rHEGIC):
            - rHEGIC that are received every block can be claimed at any time in the LIQUIDITY MINING REWARDS section of the [TOKEN HOLDERS] tab. These however can only be converted for HEGIC once they vest (see what is rHEGIC above for more detail).
            - Assuming there is profit (not loss), ETH/wBTC rewards from the payment of premiums to LPs can be claimed 14 days after your Ethereum wallets most recent write token deposit. Navigate to the [WRITERS] tab and under the ///YOUR EARNINGS section hit the WITHDRAW NET PROFITS button.
        - Option holders liquidity utilization rewards (rHEGIC):
            - rHEGIC that are received every time an option is purchased can be claimed at any time in the LIQUIDITY UTILIZATION REWARDS section of the [TOKEN HOLDERS] tab. These however can only be claimed for HEGIC once they vest (see what is rHEGIC above for more detail).
        - Staking lot holder rewards (ETH/wBTC):
            - ETH/wBTC can be claimed immediately after they become available for staking lot holders. This can be done by navigating to the STAKING section of the [TOKEN HOLDERS] tab.


## HEGIC STATISTICS

    - Most HEGIC statistics can be viewed on the analytics page: https://www.hegic.co/analytics
        - Amount of ETH/wBTC paid in premium and settlement fees
        - Number of open, expired and exercised options
        - Notional volume of options in the underlying asset
        - Liquidity pool depth and availability
    - Where can I see how much liquidity (Total Value Locked, TVL) is in Hegic pools?
        -  [DeBank analytics](https://debank.com/projects/hegic)
        -  [DefiLlama](https://defillama.com/protocol/hegic)

## DEFINITIONS

    - Who are the early contributors (EC)?
        - Early Contributors are people that funded initial expenses of Hegic when nobody knew about it. Those funds have been used to pay for expenses like security audits and refund users affected by initial bugs. To reward their initial contributions when nobody believed in Hegic, they will receive 20% of HEGIC.
    - What is the vesting schedule for early contributors?
        - Early contributors will receive their allocated HEGIC following a linear vesting (read below) schedule during the first 24 months after IBCO ends. There will be 0% of their allocated HEGIC unlocked right after IBCO ends. 
    - What is linear vesting?
        - Linear vesting is the mechanism in which EC and HDF will receive their tokens. It means that each block, stakeholders affected by this schedule (not you), will receive a proportional number of tokens. For example, if you were an EC and your allocation is 1,000 HEGIC and your vesting time window is 1,000 blocks, you will receive 1 HEGIC per block. This means that they do not have their full amount of HEGIC until their vesting ends, which in case of EC is 24 months after IBCO ends. 
    - Will early contributors dump on IBCO participants?
        - They have no reason to do that. If they want to sell, they will only be able to do so in small batches until their total allocation is delivered to them (2 years after IBCO ends = September 2022). If they tank the price on purpose, they are damaging their future holdings. 
    - What is HDF?
        - HDF stands for Hegic Development Fund. This is, the allocation of HEGIC that dev team will use to pay for expenses of developing Hegic Protocol. It is unlocked in a vesting schedule of 48 months (i.e. 4 years - September 2024). 
    - How is the vesting schedule for HDF?
        - Vesting schedule for HDF (read above) is done through linear vesting (read above) among the 48 months that follow IBCO's end. This means that developers of Hegic will receive a small percentage of its allocated funds each block, incentivizing long-term achievements instead of short term thinking and dumping. 

## RISKS
    - What are the risks of buying Hegic?
        - Read https://medium.com/hegic/hegic-protocol-risks-breakdown-d3dcf8c85d01
    - What are the risks of providing liquidity?
        - Read https://medium.com/hegic/hegic-protocol-risks-breakdown-d3dcf8c85d01
    - What are the risks of buying Hegic Options Contracts?
        - Read https://medium.com/hegic/hegic-protocol-risks-breakdown-d3dcf8c85d01




## Archived topics
 
### Initial Bonding Curve Offering (IBCO)
    - What was the IBCO?
        - The IBCO is a new mechanism that has been thought and put in place for the first time in Hegic. In Hegic, the total amount of tokens offered through IBCO is 3% of total supply (90,360,300 HEGIC). The main objective of the IBCO is the initial price discovery. Hegic's IBCO contract is https://etherscan.io/address/0x1b8782d4a7da5b63a934e78a6563fdd122e9915d
    - How did the IBCO work?
        - During the IBCO, all Hegic buyers deposited ETH into the IBCO's smart contract. When the IBCO period ended (12/09/2020 19:00:00 UTC), the total provided ETH amount was used to buy the total amount of tokens allocated to IBCO (3% of total supply). Each user then received their share of the amount of tokens offered through IBCO in proportion to the ETH they provided (e.g. if Alice provided 10ETH and total provided amount is 1,000ETH, Alice would receive 1% of IBCO's HEGIC (c.9,000,000)).  
    - How was the IBDO price determined?
        - The final price until IBCO was determined once the application period ended (12/09/2020 19:00:00 UTC) as follows: Total ETH expected / 90,360,300 = Price in ETH.
    - How long after the IBCO were HEGIC available to transfer/transact?
        - HEGIC were made immediately available to subscribers with no restrictions at the end of the IBCO's application period (12/09/2020 19:00:00 UTC).
    - What are the proceeds of the IBCO being used for?
        - All proceeds from the IBCO will be used to bootstrap liquidity for both the wBTC and ETH pools. $500K of liquidity will be added to each pool every 2 weeks for 6 months as outlined in the v888 launch announcement (https://medium.com/hegic/hegic-v888-is-live-1c790de1b38).