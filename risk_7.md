### Risk #7 - 8/23/2018
##### Introductions
* Rich, Steven

##### Recap:
* Risks inherent in generating CDPs: Volatility, qualitative, liquidity, exposure, correlation, and price feed
* Qualitative risk assessment
* Debt Ceiling

##### What do we know about the Debt Ceiling? 
* A parameter used to control for exposure risk, liquidity risk, and contributes to correlation risk
* Theoretical debt ceiling -> top-down, what overall percentage of the market could we take without inducing a liquidity event on ourselves (15-20% more or less)
* Practical debt ceiling -> bottom up, what does the trading environment look like, how much liquidity is available in the market to exit the entire position
* Defensive debt ceiling -> build a uniform portfolio and mitigate against volatility risk in specific collateral types
* Start with a nominal debt ceiling and build it up slowly

##### If we take on a new asset class, would it be necessary to re-balance the debt ceilings for the other collateral types to maintain balance in the portfolio?
* Most collateral might start with 10 million each, if we find a precious metals token with great liquidity, we could start higher.
* It will depend on where the current exposure lies. We wouldn’t want to over expose to new assets.
* Our objective is to maintain the integrity and stability of the system, not to grow an investment portfolio

##### In terms of determining the debt ceiling, if it was one giant CDP that got liquidated how would we exit that position to pay back the debt.
Any diversification benefit we’re able to find should be kept in the system to maintain integrity.

##### Would the defensive debt ceiling always be the smallest?
* Three subsets: Theoretical > Practical > Defensive
* Ideally the defensive debt ceiling would grow to the practical debt ceiling over time and as the system grows
* The practical debt ceiling could grow into the theoretical given significant liquidity

##### [Emergency shutdown] may seriously affect market prices for those collateral markets?
* Emergency shutdown can be triggered for a number of reasons
    * Bad actors can crop up in many ways
* Different from a black swan, where Ethereum might stop

##### Can emergency shutdown be triggered on specific collateral types?
* Only intended to protect the overall system and not be used in black swan events for assets
* If there is a significant drop in ‘sliver’ price, CDPs will be bitten and probably a large chunk of them will be bitten. The debt ceiling should be in place to make sure we can properly liquidate that collateral.

There remains existential risk if Ethereum shuts down.

##### What mechanism is there to phase an asset out of the collection of collateral types?
* Debt ceilings don’t automatically grow. The underlying assessment of the collateral will change and update constantly.
* If the organization changes from our expectations we would take the necessary measures to change our exposure to those risks
* If the trading environment changes there could be indication of volatility in the market
* Risk teams will be on the lookout for any changes in asset valuation

##### When the debt ceiling needs to be lowered below the outstanding collateralized debt, what could occur?
* It will need to be communicated to those CDP holders that the CDPs with that collateral will need to be closed. Could be done over time or might need to be in a hurry
* The thing about a black swan will manifest in an unexpected way.
* Stress test, take worst conditions and increase those conditions to a desired cushion for unexpected risks

##### The debt ceiling highlights a very important feature: liquidity.
* When setting the ceiling you’re making an assumption that the liquidity will persist for at least [3 months].

##### How will we account for a sudden unexpected loss of liquidity?
* Make an assumption that the liquidity profile will persist for a certain period of time
* Statistical probabilities of the outlooks
* In crypto, the time frame can probably only be stretched to 3 months, compared to 6 months or a year in the traditional market.
* Crypto hasn’t found it’s proper cycles yet, but need to be cognizant of how the portfolio may look over a specific period of time

##### What is the Liquidation ratio?
* Encapsulates two risks: volatility and liquidity
* Looking at the liquidity from a single CDP being bitten and understanding the trading profile of exiting that position
* Looking at volatility: probability expressed in extent and time period of changes
    * Extent - how much is the price changing
    * Time period - how quickly is it changing

##### How is the probability of volatility assessed?
* Normal distributions and probabilities can be derived from historical data
* Assess tail risk at 1% or 5% or whatever
* If something goes wrong, how much cushion do we need to get out of the position and still be above water
* There could be some benefit to slowly liquidating collateral through endogenous cost saved.
* Initially we could assume CDP holders would need to get rid of collateral over longer periods of time, like 7 days.

##### Currently liquidated assets are sold on the dashboard directly, in the future they will be auctioned. The risk teams will have to consider the first movers in collateral auctions as well?
* In the traditional world, someone defaults on their house you can take their house and sell the house to get your value back. 
* In the crypto world, someone defaults you don’t have to go back to USD necessarily, but to a more liquid token (ETH, for example)
* All other tokens that have more liquidity than the one that’s being defaulted on, could be used to exit from the current asset to another liquidity option
* Some may see liquidity into Dai as ideal
