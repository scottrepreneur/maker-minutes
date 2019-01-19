### [Risk #18 Special Edition: Stability Fee - 1/17/19](https://www.youtube.com/watch?v=FCQqpIAF8U4)

#### Introductions
* Rich, Steven

#### When should the stability fee be increased or decreased? What is our point of reference (outer bounds)? [[1:48]](https://www.youtube.com/watch?v=FCQqpIAF8U4&t=108)
* The Dai exchange rate will be a heavy indicator as to the policy being adopted around stability fee
* Supply and demand fracture also contributes
* Look at a combination of exchange rates and trigger a force of action

#### When it comes to data we should look for exchanges that have aggressive wash trading policies. How much backtesting should we consider before establishing a range of exchange rates? [[5:54]](https://www.youtube.com/watch?v=FCQqpIAF8U4&t=354)
* The reliability of the data will drive the efficacy of any empirical analysis based on that data
* While we are bootstrapping we have to work with imperfect data

#### What models are we relying on right now to draw these empirical conclusions? [[8:33]](https://www.youtube.com/watch?v=FCQqpIAF8U4&t=513)
* Largely abstract models during bootstrap, looking at data points and understand what insights they can provide

#### One of the factors is considering the natural arbitrage opportunities of market making teams and how the pressures affect them as the peg is drifted [[13:41]](https://www.youtube.com/watch?v=FCQqpIAF8U4&t=821)
* Even though market makers will tend not to reveal all information to remain competitive they could contribute to their desired stability fee rate through a rate like LIBOR in the traditional world.

#### Can we trust market maker's analysis of what the stability fee should be? [[15:10]](https://www.youtube.com/watch?v=FCQqpIAF8U4&t=910)
* On it’s face, no but they should have self serving interest so we can view it in that light

#### So we want to have a signal that allows us to rigorously say that if `x` happens we want to come together and consider `y` action? [[18:44]](https://www.youtube.com/watch?v=FCQqpIAF8U4&t=1124)
* The implementation is still being bootstrapped but that the’s general idea
* It could be a matter of the community taking initiative and putting together proposals for adjusting the stability fee by a quarter of a point or half a point

#### It appears the change of the stability from 2.5% to 0.5% has had the intended affect given data on the exchange rate since the change. Is that fair to say? [[20:55]](https://www.youtube.com/watch?v=FCQqpIAF8U4&t=1255)
* It’s tough to call causation rather than correlation
* It could be an anticipatory effect, but we should look to collect more data for empirical analysis of future decisions

#### We should also consider what we want the models to achieve for us [[25:36]](https://www.youtube.com/watch?v=FCQqpIAF8U4&t=1536)
* Sensitive to mismatches in supply and demand
* Be cognizant of the inventiveness of MakerDAO in the context of the broader ecosystem
* The stability fee should be utilized to support the system itself and needs to be allocated appropriately for grants, Dai Savings Rate, etc to spur growth in the right ways

#### [What is the stability fee?](https://github.com/scottrepreneur/maker-minutes/blob/15d159fa5417adf1f4489fb8c40f3900ed4a410c/risk_4.md#what-is-the-stability-fee) [[32:38]](https://www.youtube.com/watch?v=FCQqpIAF8U4&t=1958)

#### What happens if the fee is set too high or too low? How do we know that has happened? [[34:35]](https://www.youtube.com/watch?v=FCQqpIAF8U4&t=2075)
* Since we don’t have the breadth and depth of feedback we don’t really know when it has happened
* What is an increment we’ve seen before, how did the exchange rate react to those changes?
* Where is the ceiling? 3.5 - 4% when no longer being competitive

#### How do we know that Dai isn’t trading where we want? [[37:10]](https://www.youtube.com/watch?v=FCQqpIAF8U4&t=2230)
* We need to put proxy metrics in place
* This meeting can help establish those practices
* We can solicit from the community what types of things they’re looking for in good data sources
* Establishing how the stability fee affects —> creating risk teams —> and compensating those teams

#### Is there a case for a feedback-loop controller framework? Will there be an algorithm to determine the appropriate stability fee? [[43:24]](https://www.youtube.com/watch?v=FCQqpIAF8U4&t=2604)
* We’ll need a robust algorithm from the information analyzed
* The algorithm would remain a recommendation while governance is the last say. Eventually that could change

#### It’s becoming apparent that the stability fee is a classic variable rate. Is there friction in describing it this way and setting the expectation that it can and very well might change? [[46:24]](https://www.youtube.com/watch?v=FCQqpIAF8U4&t=2784)
* At critical mass in the traditional world, a few basis points can have a large effect
* As we’re bootstrapping the system the movements are less detectable on the intra-percent level
* Fixed rate interest has benefits for very large CDP holders or risk seekers

####  We’ve adjusted the fee in 2% increments so far. Should we consider smaller movements at 0.5 or 1%? [[49:32]](https://www.youtube.com/watch?v=FCQqpIAF8U4&t=2972)
* We should consider that and the cadence in which votes are considered or at least what the “normal” looks like
* A general suggestion would be around 0.5% at a time
* We could continue having weekly discussions or place for contributions. We have open chats that any one is welcome to share ideas in those channels

#### Closing thoughts: We should consider raising the stability fee by 0.5% [[55:38]](https://www.youtube.com/watch?v=FCQqpIAF8U4&t=3338)
* We’ve moved at a 2% change and seen the effect. We could make a smaller change and consider the further effect
* Please raise feedback through reddit, rocket chat or on the next risk call



