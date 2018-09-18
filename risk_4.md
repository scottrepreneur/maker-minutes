### Risk #4 [Special Edition: Stability Fee Raise] - 8/2/2018
##### Introductions
* Rich, Jess, Steven, Lev - Economic Research, Greg - Head of BD, Rune - CEO

##### What is the stability fee?
* The stability fee is an interest rate. There are 4 components to interest:
    * Inflation
    * Credit premium - covering default of the counter party
    * Operational - covers the cost of providing the services
        * Policy tools - parameters for maker holders to adjust to influence behavior in the system to ensure its longevity 
    * Liquidity preference - premium increases with the duration (term) of the loan (not really applicable to Maker loans)

##### Why do you need Policy Tools?
* There will always be frictions in the market that need to be compensated for
    * Cost of transactions -> Tax implications
* Supports the governance of the system by allowing some flexibility to original models to be combined with the other assessment tools
* As the blockchain economy is growing we need to account for those inflections
* Gives you a lever to influence growth of supply as price of borrowing changes

We’ve discovered the price of Dai trending down on the open market because more people have opened CDPs and drawn dai than people purchasing on the open market. The price of is depressed and a mechanism to influence this is to increase the cost of borrowing.

##### Why have we not seen CDP owners buying cheaper Dai on the market to pay back debt?
* It is happening, but the market remains immature and inefficient at this time
* Influencing this increase allows for balancing the first part of the equation rather than relying on the arbitrage to hold the system in line
* The Dai system has been giving loans very cheaply so participants have seen no brainer deals. There is less incentive to move over from bank accounts as they may receive some interest reward there.

##### How significant is the risk of lost liquidity from the risk of losing the (USD) peg?
* The reduced liquidity will be good for the system in the long run as we pull the demand back in line with supply.
* Changes expectations to increase faith in holding the peg. Uncertainty could significantly impact market views

##### Would Dai/USD pair impact the liquidity and peg stability?
* Jurisdiction based pairs, but absolutely will help liquidity on both sides and especially on ramp from USD in new cases
* Doesn’t address systemic supply-demand imbalances

##### Are we strengthening the stability (peg/liquidity) before multi-collateral Dai? Are we addressing the demand side in other capacities?
* The liquidity will be significantly different because we’ll be ready to start scaling the demand use cases.
* The exponential growth of Dai demand will be largely out of the hands of the Maker community. These tools are preemptive to some significant increase in any of the balances.

##### Why the dramatic increase in Stability Fee? (5 fold from 0.5%) [Super-cheap Loan Land^TM, 🤣]  
* The introductory rate was extraordinarily low, due to many user experience considerations.
* This is a more well considered rate given market rates and supply interest
* Incremental changes will get repetitive/ potentially

In general we can compare rates to understand how this new rate stands in the macro market (crypto-margin rates, T-bill rates, etc).

##### a. Will each stability fee include a base rate for all Dai and a spread on specific collateral types?
* Definitely

##### b. How will it work in practice?
* It should be implemented this way in practice

##### c. Will the rates be used to influence a better distribution of collateral types in Multi-collateral Dai?
* The short term USD-LIBOR rate is about 2.5% which is great to adapt to our model
* Base rate considers purchasing power and the operational risk we’ve discussed
* The spread rate would be specific to the volatility of the collateral’s risk profile

##### When we have multi-collateral types, can we have CDPs with a variety of interest rates?
* Consumer surplus argument, will depend on what consumers are looking for in the space
* The technical and UX complexities will need to be worked out to match up with desired consumer risk profiles

##### How does the Stability Fee compare with the TRFM?
* The mechanisms have the same goals, targeting them different ways technically
* TRFM has a usability issue, when the target price is adjusted from the original unit of account it introduces another layer of confusion/complexity
    * i.e. every app using Dai now has to account for what the target price of Dai. Has a similar effect on borrowing
    * The reliance on incoming feed data increases when adjusting target rate
