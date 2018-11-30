### [Risk #8 - 8/30/2018](https://www.youtube.com/watch?v=bSITCcLmd0k)
##### Introductions
* Rich, Steven

##### Defaults in the system are a sign of a healthy economy. Is that correct?
* Natural rate of unemployment: a certain number of people being unemployed is expected in a healthy economy
* Balance between liquidation ratio and business competitiveness for providing leverage on collateral
* The maker ecosystem is comprised of risk avoiders and risk seekers and without that risk (and the default) there would be no mechanism to provide stability
* Individual defaults prevent overall default

##### Will there be caps on individual CDP sizes?
* Initially no, but ideally there would be
* The impact on liquidity is based on the size of outstanding collateral
* We’ll rely on the overall defensive ceilings to prevent over exposing to one collateral type for now

##### Doesn’t this require monitoring every collateral type constantly? How often will risk teams be checking on models and collateral?
* Yes it’ll be continuous monitoring
* Dashboards would relay information to teams to keep them in the know

##### What happens when risk teams are reacting to events around specific collateral types?
* If it is a material change in the status in the market then an emergency proposal could be brought forward
* In general, the next actions would take place during the next executive vote
* Governance should occur period to period, rather than knee-jerk reactions

##### If we have 3 distributed risk teams, what are they there to push forward? Where do their allegiances lie?
* Their allegiances align with their individuals
* MKR holders would have significant interest in creating many, many risk teams
* Service providers could provide value and would be reimbursed in a grant program or other

##### How do we factor in the auction mechanism in the liquidation ratio?
* The liquidation ratio is assuming that someone has already bought the collateral, so the auction
* Liquidation doesn’t necessarily mean getting to USD. Could mean another more liquid collateral

##### Can [Emergency shutdown] apply to a single collateral type?
* You could, but its intended to protect from existential or systemic risks
* All CDPs being bitten would be the same as an isolated shutdown

##### Now we're talking more about building the buffer above 100% collateral to determine Liquidation Ratio
* Given a specific period of time, what is the likelihood of a collateral falling 1% in 1 day? 
* How much could you possibly lose in a single day?
* What is drift? —> the general direction is this token heading
* In a bear market, the movement downward will be exaggerated

##### What does the parameter of the liquidation ratio attempt to control for
* Liquidity risk
    * You’ve got XX collateral and you have 7 days to get rid of it. So you plan to sell 1/7 of it each day
    * Run up against the spread
* The volatility risk is calculated off daily price, usually closing price which isn’t indicative of intra day volatility

##### Correlation risk
* We’re not working with a traditional portfolio where we can use a risk adjusted return point of view. We’re seeking to maximize stability and integrity of the system.
* Diversification of two different assets occurs by looking at the two assets volatility which have slightly different volatilities that provide a natural buffer.
* Want to be cognizant of creating pockets of concentrated exposure around some collateral types

We’re building up a whole set of tools to manage the risk exposures of our portfolio.

##### Price feed risk
* Largely unique to crypto markets
* Most countries have 1 exchange, so there is very limited price discovery. Some have 2 or 3 exchanges. The US is unique and has dozens of exchanges.
* How do we determine the correct representation of price?
    * A centralized exchange like Coinbase or Gemini?
    * Need some sort of consensus around a real source of truth
* Median transform - (12- 15) oracles that bring in the appropriate prices and we take the median of those
    * Mean is vulnerable to statistical outliers

##### What is the difference between Price and Value?
* When you look at an exchange you’ll see the ‘advertised price’.
* Value is a more pure sense because of liquidity in the market. Given exiting large positions will include endogenous cost

##### Why are some countries limited to few exchanges?
* First and foremost a function of regulation, a form of control
* Barriers to entry for liquidity and licensing are generally high
* If an exchange is run by the state then there would be extended risk

##### How do we weight or apply trust values to the data coming from exchanges that we’ll rely on for price feed data?
* If we’re looking to exclude wash trading, we can apply a simple proxy: daily volume vs market cap
* Apply this proxy while assessing trading volume during asset qualification
* Need to make a distinction of the issue from the quality of the assessment

##### How much are the MKR token holders on the hook for is something goes wrong?
* Economic capital - expected short fall, we’ll explore more next time

##### What are some of the existential threats to the maker system?
* Stupidity, manipulate the parameters of the system to crazy 
* Landscape, if Ethereum stops, then we’d need to adapt to that 
