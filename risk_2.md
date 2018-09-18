### Risk #2 - 7/19/2018
##### Introductions
* Rich, Steven, Soren

##### Recap:
* We're diving into what the risk governance looks like.
* Risk management: looking at the stability in the system, then by extension the stability of Dai itself
    * Economic Risk, Financial Risk, Operational Risk
* Scientific governance: what is it? How do we handle it?
* Our goal is to create a construct to effectively manage the risks identified in these layers.
* What is the blockchain (to you)? (In an economic sense and growth potential)
* The decentralized governance function overview

##### What is Scientific Governance?
* Governing using the science of risk management as a basis of argument
* Risk management is a deeply studied, organized body of knowledge. Create a claim and then justify it (with data).
* __Lightning History Lesson:__
    * [Probability Theory - 17th Century, Pascal & Fermat](
https://www.york.ac.uk/depts/maths/histstat/pascal.pdf)
    * Brought on property insurance and reinsurance - resulting from the Great Fire of 1666
    * Marine Insurance - became first business insurance markets (1686, Edward Lloyd, Lloyd's of London)
    * Life (expectancy) tables first described by Edmond Halley (Halley’s comet) - probability in the context of mortality
    * Normal distribution (Bell Curve) - in 1730, Abraham Demoivre With Gauss 
    * Bayes Theorem - application to decision making - 1715, Thomas Bayes
    * Linear regression - data will fall toward the mean over time - 1875, Francis Gaulton 
    * Portfolio selection - diversification (alpha, beta) - 1952, Harry Markowitz
    * Value at Risk -  what is our full exposure? - 1980s, Bankers Trust
* Applying to decisions
    * Take an look at initial thoughts when considering a specific collateral type for the portfolio? What do I know about them?
    * New information updates outlook on risks

##### Will people be able to take a dataset and apply risk management strategies, approach it from two different schools of thought and arrive at different conclusions?
* Coming from different institutional frameworks (company specific assumptions and constraints)
* Many of different perspectives can be used to apply different maps

##### How will we select which methodologies we should be incorporating?
* In order to coordinate scientific governance through decentralized risk, we’ll establish Risk Team 0 and the potential frameworks utilized. During the initial coordination we’ll be providing those to the community to run with, sharpen, and improve.
* Together we’ll flesh out: What is a risk construct?

##### Would it make sense for Maker to provide a documentation repository for risk models?
* Yes, providing initial research around the 0 frameworks will establish this resource. We’re looking to have these challenged and reviewed by those with even more experience. Ideally they can deconstruct the model(s) to its initial foundation and recreate them in better ways.
* Should include videos and usable tools to experiment with

##### How do we implement Scientific Governance with decentralized risk management?
* In the case of competing risk constructs, we’ll need to select one or the other
    * Could potentially weight competing structs where a variable parameter can be set
    * Adding independent constructs gives a higher likelihood of diversifying out the chance of measuring a risk inappropriately (or missing identification altogether.
* Representative arguments to different perspectives
* Some models will be collaborative
* It’s very difficult to identify all risks -> unknown, unknowns

##### When MKR holders gather to vote on new asset classes, they are voting on two different things? a) A model b) The results of that model
* Taking a step back, governors will first decide on including a risk team
* Risk teams will have to put forth their models in clear and concise ways
* Then after researching different (suggested) collateral types teams will propose risk profiles for different assets
* More of an advisory role

##### In traditional statistical modeling, confidence level can be assigned to results to indicate the degree to which they believe the outcomes are feasible. Are there similar risk management indicators?
* Based in probability theory. Not prescribing one outcome, but likely that an entire set would provided with their probabilities
* Sampling, hypothesis testing
* Didn’t branch from Scientific Method - deep learning is starting to take the place, but based empirically which has cons

##### In testing there are two ways of testing the data
* Back testing - propose a specific construct. Considering past data how it would’ve acted in the past? How has it worked across regimes?
    * i.e. Great model. How did it work over ‘08
* Forward testing - looking long-term. Assessing from competing teams to decide how it would work with present indicators

##### What happens when a construct is proposed, with an asset rating and risk profile, that is determined inaccurate after its been implemented? What would be the next step?
* It would be a weighting against that construct and team
* If it’s a cataclysmic thing then either didn’t spot some obvious risk in the underlying asset or this was outside of everyone’s purview or domain space
* Economic capital - you apply wonderful risk management techniques, but you can only incorporate the things you can statistically understand
* Anticipating that the buffers are established to handle the de facto black swan, depending on how bad the impact is

##### Will there be a process for the community to gauge the impact of a black/grey swan?
* Yes

##### Will each decision progression have different models or will we update/tweak the existing models?
* The taxonomy of modeling, especially financial models, is fairly clear. Its the application of those models that gets interesting
* Included models won’t be so out there that they provide completely unexpected results. Some base vetting will occur on all constructs

##### Will the models be public? (Assuming that they’re not stored or implemented on chain)
* Yes, models should be explicit in order to provide others for thorough review
* Some models might be implicit but will be weighted lower
* “It’s better to know on average, than not know something going fabulously.”

##### Do you envision the models living on chain?
* No. Executive votes will be used to implement accepted changes
* The main contract pieces are firmly in place. We can adjust the delineated parameters of the system: liquidation ratio, stability fee, debt ceiling, etc.

##### Are there more factors to consider than the stability fee, debt ceiling, liquidation ratio, and the asset type itself?
* Vote on risk teams & risk constructs. Those teams will have the parameters including the profile for each
* Vote on collateral types

##### Layers of Risk for Digix? It seems unlikely DGX would decrease in value more than 5 or 10% in a day 
* Categorize risks that you’ve identified: Market risk, liquidity risk, credit risk, operational risk
* GARP has determined the most impactful risks are operational - if the organization starts to divert from the originally intended market
* Very difficult to assess low frequency/high impact risks, unique to individual institutions

##### DGX and ETH have few similar market risks. We could recommend a lower collateralization ratio paired with lower debt ceiling, because they have lower small band movement but operational risk would be near catastrophic.
* Debt ceiling has three factors:
    * Liquidity of the actual token - we wouldn’t want to fully lock it up, creates liquidation crisis
    * Operational risks would bring down the ceiling from a regular gold backing
    * How quickly can you get out of the position? ->Execution trajectory optimization problem
    * Defensive debt ceiling - grow ceiling with the business

##### You have to consider the debt ceiling with respect to the token liquidity, but also the ceiling with respect to the portfolio’s allocation.
* Right, we can borrow portfolio construction tools from traditional finance with the appropriate return given desired risk
Liquidation vectors
    * What is a liquidation event?
    * What does liquidation mean?
    * Does it mean moving from token ABC to token 123?
    * Does it mean getting out to ETH?
    * Or do we need to get to Fiat?

##### Why would the stability fee need to be higher or lower?
* Similar to interest rate in traditional finance
* Must compensate for inflation and credit risk
* Expected short fall theory - if you go past a threshold in a risk you may be liable to an entirely new risk distribution
* Economic capital - set aside for cases when risk’s risks occur
* Credit premium established through the exposure MKR token likelihood of needing to be printed

##### Will there be a case where an asset will have two or more risk profiles? i.e. lower collateralization ratio, higher stability fee or vice versa
* Probably, risk constructs could propose slightly different profiles. We could find the weighted average of all compiled constructs.
* Meant to be consultant roles, advisors

This allows for MKR token holders to allow for different levels of risk at different prices.
