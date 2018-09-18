### Risk #9 - 9/16/2018
##### Introductions
* Rich, Steven, Soren

##### Recap
* Defined first principle risks in the system and what mechanisms are available to manage those
* Introduced correlation risk
* How do we build a collateral portfolio? What should our risk profile look like?

##### Correlation risk
* How is the asset categorized?
    * Security, utility, etc
* Can a token with 50 million market cap have 20 or 30 million in daily transaction/trading volume?
    * Its feasible to have high daily volume for currency tokens
    * It will depend on their use to categorize how daily volume is derived
* Everything is naturally tied back to the system it’s running on
    * Diversification will be difficult, but we can get as much diversification as possible

##### What is the primary consideration when we’re considering an asset type for the portfolio?
* We need a thorough trading profile to understand the liquidity, volatility, and price discovery which we rely on for recourse
* We can account for the profile after inclusion by adjust the system parameters

##### What collateral types would we (the community) suggest?
* Asset-backed tokens — especially precious metal tokens

##### Taking a look at the spot gold market vs Gold representation in crypto world
* Take into consideration the organization that provides that spot market for the underlying market
* Digix currently resembles the futures market and interacts with the retail market in a similar way
* Integrity process - lock-up/unlock process is very formal and heavily regulated
    * If you settle in gold, you’ll have to take care of the infrastructure integrity process
    * Blockchain will make many market’s integrity process much more efficient
* Arbitrage will be improved, just need to factor in the costs of arbitrage and see somewhere it makes sense

##### There are a lot of teams looking at creating asset-backed tokens. We can take on some with a small percentage of their outstanding market with the prospective to grow as their market grows.

##### Will we create relationships with each asset backed token?
* Yes and their supply chain
* Blockchain should reduce their supply chain, however
    * More efficient transfer of information

##### Do you think the recourse process will be a price discovery mechanism? Like through the auction mechanism?
* Recourse will be an industry itself
* Secondary market price discovery doesn’t have to be the only source of recourse. There is an insurance aspect
    * Insurance could eventually be handled by another DAO
* What used to be very exotic derivatives will be clear transparent and understandable on the blockchain

##### What does it look like to have a stable fiat-backed token as a collateral type?
* Should likely be an IOU-type asset type, which would fall into the same recourse component as gold or other precious metal tokens
* We could incidentally create a feedback loop between their mechanisms and ours

##### Doesn’t the user carry that liquidation risk rather than the system?
* To a certain extent, there is an overexposure to that collateral
* For example, if another (stable) asset are using the remaining supply for an asset backed token, then an inherent liquidity problem with all the potential collateral locked and the market closed

##### Have you figured out what the potential collateral types and risk parameters might look like for Multi-collateral dai?
* We have a starting list to work from in McD and their associated risk parameters

##### Which risk parameter should you calculate first?
* Start with a fixed point, like the liquidation ratio. 

We’ll want to give the respective asset teams know they could be impacted by our inclusion of them, so they can make their communities aware.

__Switching topics to voting (coming up)__

Voting is open for two more days. We’re fully looking to move toward decentralized governance.

##### How does the voting work for the foundation proposal?
* We wanted to make sure the MKR was exposed as little as possible so we made a proxy contract connected to your hot wallet and your cold wallet where your Maker is hopefully stored
* The hot wallet only has the option to move MKR to the voting contract or back to the cold wallet
* We’ll extend this functionality so single wallets can vote going forward
* There is a small bug that limits the number of MKR used in a vote to 999, but you can continue to top up your vote with 999 until you’ve exhausted it.

##### What are the different types of votes?
* Governance votes: yes or no on proposals
* Executive votes: approval votes for approved changes in governance votes

##### Will your MKR have to stay locked in the contract for the duration of the vote?
* The vote counts the MKR that is locked in the DS Chief contract when the vote expires

##### Can you proxy multiple wallets to a single hot wallet?
* Not in the current iteration
* Vote delegation is possible down the road

There are a lot of optimizations we have the potential to improve in the process in the future.

##### Will there be a forum component added to the governance dashboard?
* Depends on what users would like for where to have discussions about votes
* We have it on the roadmap to add features that governors find useful
