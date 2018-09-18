### Risk #6 - 8/16/2018
##### Introductions
* Rich, Steven, Jess

##### Recap:
* What are the inherent risks? Volatility, qualitative, liquidity, exposure, correlation, and price feed
* Starting to dive into the qualitative risk assessment tools

##### What are the aspects of qualitative risk management?
* Start with fundamental analysis or due diligence
    * Where an organization is and how it fits into its industry/sub industry?
    * What factors of the economy keep the organization running?
* Financial analysis to determine valuation
* What are the inherent risks that take away from what the organization/protocol are doing?

##### How do we go about conducting this (qualitative risk) analysis?
* Initial collateral onboarding
    * Who are you as an organization? 
    * What does your trading profile look like in the secondary market. \*not all tokens have good price discovery in the secondary market
    * What is the potential recourse?
* Operational assessment of the organization
    * What is the asset looking to accomplish?
    * What does the underlying governance look like?
    * What rights do token holders have toward potential revenue streams (or underlying assets)?
* Technological assessment of token and organization
    * Need to make sure it fits with the Maker ecosystem nicely

##### What do the assessment results look like ^ —> gives you a rank out of 10
* Look at the team and core advisors, do they have enough experience?
* What does the community sentiment look like?
* Technology: how complete is it? How well reviewed is it? What is the level of security backing the network?
    * Internal/external audits conducted? MKR (-sponsored) audit?
* Market competitiveness: where is the organization in terms of the market landscape?
* Business model: where do you categorize the token (security, collateral, utility)? 

##### What does the ranking derived mean?
* The value we ascribed to the organization will ultimately affect the quantitative values calculated (debt ceiling, stability fee, etc)

##### The crypto market is especially volatile and vulnerable to misfired signals (tweets, PR, fake hacks, etc). How do we anticipate things that could cause significant decline in price?
* There is only so much insight into the inner working of the organization and corporate events could influence the price
* Ideally we can capture as much as possible in the risk profiles over time based on the history
* Starting to get into black swan territory - Value at risk assessment and then expected short fall/stress testing
    * Looking at the worst cases in the past or imagining future worst cases

##### In some ways Maker can be viewed as a rating agency
* Maker DAO is facilitating growth of a new economy. Dai can be used to facilitate purchase of goods and services at consistent prices (transactional basis)
* As things become tokenized, they can be included as collateral
* One of the functions could include rating. It’s not what we’ll set out to do.

##### How often will we evaluate collateral types?
* Risk teams will continuously monitor collateral types
* Risk is real time
* If there is a significant event that needs to be acted on then there could be a need for an emergency proposal

##### As Maker diversifies, does it get harder to create CDPs given the need for multiple asset types with varying demand for long leverage on those assets?
* Multiple collateral types allow you to broaden the ‘market’ for creators of CDPs
* It is not a requirement that individual CDPs are created with multiple collateral types
* Some collateral type may exhaust their debt ceiling quite quickly, which can be adjusted lock step 
* The diversification of collateral and ease-of-use (to liquidate that collateral) will define how readily supply is made available.
    * If it’s fluid then we’d expect an increased use of CDPs and supply could out pace demand.
    * On a global level, we’ll set ceilings so that when they are all met the portfolio is in an ideal position

##### What are the prospects of paying “safe” (not-volatile) CDP holders to open CDPs to stabilize the system?
* Precious medals would have great stabilizing benefits for the portfolio 
* We’ll want to use the extra benefit delivered from diversification as a capital buffer
* The part of stability fee manipulated in policy tools will allow some incentive on different collateral types to potentially make the portfolio more ideal without disrupting the makeup as a whole

##### How are trading profiles of various assets proved to be legitimate?
* Unless you’re involved with the immediate trading it is difficult to pare down where the wash trading is occurring
* A general proxy might look like taking daily volume in comparison to the market cap
    * If a token, given its utility and functionality, is above a certain percentage then we’ll need to consider why that is the case especially if it volume is impacting price
    * Will factor in where the tokens are traded as well. Would affect weighings between fee-less exchanges versus decentralized (on-chain) exchanges
* We’ll have to start self-regulating while we’re currently lacking regulation in that area

##### What is the purpose of the debt ceiling? How does it work?
* Why do we want a debt ceiling in the first place?
It comes down to liquidity risk. 

##### Given a giant CDP that gets liquidated, how long would it take to liquidate? How was the price affected during that liquidation?
* What is our desired (longest) time from liquidation to auction complete?
* What is our desired (max %) slippage we’re willing to give up in the liquidation?
    * Liquidity-adjusted value at risk, liquidity discounting
* If you need to get rid of collateral now, you’ll be impacted by 
    * Endogenous cost - impact on the price
    * Large transaction cost
* If you take time liquidating the position there is less endogenous cost but you’re exposed to more market risk
* There is a balance based on your utility curve or risk aversion.

##### When considering debt ceiling, the liquidation ratio is inherent of two things
* Volatility
* Ability to liquidate the collateral
* It is paramount to understand how much will be impacted as collateral is being liquidated as you could consume the entire ‘extra’ collateral 

##### What would be the debt ceiling if there was fluid liquidity and unlimited collateral?
Need ways to increment the debt ceiling in a manageable way. There could be an attack vector with hitting the system with a huge amount of collateral quickly.
If a collateral type has a significantly higher tail risk then there should be compensation with a higher stability fee.

##### How much exposure should we take on a specific collateral type? (—> debt ceiling)
* Don’t take too much that getting rid of it kills you
* Max out somewhere around 15 - 20% of total market cap

##### Can risk teams be voted in and out? Yep
* There’s two parties with bias toward creating risk teams, because there’s a natural incentive for MKR holders to maximize their returns and collateral types to be added to the system. 
* Need to show rigorously with data that they are not subjective.

##### What are the criteria for becoming a risk team?
* Internal risk team will be constructed like the framework for the process
* Teams and incorporation are not required, but show longevity
* Anyone that wants to dedicate to the longevity can propose constructs around the risk parameters to be tested

##### What are the benefits of being a risk team?
* Investors want to improve their chances of gains. Similar incentives for token teams.
* Decentralized service providers will be created around the ecosystem and should be incentivized appropriately by MKR holders & CDP creators & Dai holders to support the longevity of the system.

Will the risk team be involved in existential governance decisions? Paying foundation workers, etc.
* There are many services that serve the ecosystem so companies will include multiple functions potentially (risk & consulting support)
* Risk teams would need to consider these risks as a part of their models, but would still ultimately lie in the hands of MKR holders 

How will the community become aware of upcoming votes? What are the communication channels in place to keep people up-to-date?
* Social media: Reddit, Rocket Chat. Email and RSS feeds potentially
* Alert services are welcome from the ecosystem

When will be the first Governance Vote? 
* Stability fee vote, will be CLI for this vote still
* The Foundation Vote will be the first with the new voting user interface (in September)

For collateral-backed assets, would we consider our debt ceiling (exposure) in terms of the collateral backing the token or the token itself?
* We’re exposed to the token itself’s liquidity not necessarily the liquidity of the market as a whole

Bunch of announcements coming about MCD stuff!! 💥 💥 💥 
