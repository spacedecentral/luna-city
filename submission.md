# Request for Nest membership and funding (#3)

**Team name**: "That Planning Tab"

**Research whitepaper**: [White paper](http://goo.gl/eXAybm)

**Burn rate**: $25,000/month for 6 months 
* $20,000/month for Full-time team
* $5,000/month for Part-time team, distributed using [RewardDAO](https://medium.com/giveth/how-rewarddao-works-aka-what-are-points-7388f70269a) methodologies
* $50,000 ANT success bonus, distributed using the tools we build in this proposal


**Legal structure**: NA / Non-legal entity

**[Team and roadmap](1/files)**

## Proposal
### Abstract
In the RFP for Nest #3 it mentions implementing Yondon Fu’s OpenCollab solution. While this solution presents a compelling approach to solve the open source software sustainability issue, it places a lot of emphasis on merging and reviewing code. We propose that to begin to tackle alternative models for incentivizing open source, that we should focus on a collaborative planning model that is centered around multiple stakeholders -- designers & application users, in addition to developers. 

Additionally, while the original goal of Nest #3 is related to open source software projects, we propose to broaden the scope for what this incentivization system should ultimately be capable of supporting. After all, Aragon’s mission is to "empower people across the world to easily and securely manage their organizations”. But software development is merely one business function. The other major types of work that can be collaboratively produced online in open source manners are hardware, media and documentation. Hence this toolkit should ideally be used as a building block and base layer for a more generic Planning platform.

We suggest collective issue curation and budgeting as top features that will enable a sustainable ecosystem for open source and distributed collaboration. What we are proposing is a Planning app for Aragon that can be considered a companion to the Nest #3 git team, although in the near-term we propose a Github integration utilizing existing bounty tools that will be cross-compatible. 

One other aim of the Planning app is to create a toolkit of payout and budgeting tools so that organizations can design customized reward programs with the ability to easily account for task-based payouts to either groups or individuals. The current incentive structures that exist in the Ethereum ecosystem most commonly parrot two forms of payout structures: bounties or direct payments. Just as many projects have aimed to create schemes for which labor is directed to specific tasks, permissionless work and group completion of tasks require more complex payout structures that this toolkit would be able to accomodate for. 

We believe that these features are very important for DAOs, as the application team are members of existing organizations Giveth and Space Decentral that highly desire these features. Being funded to develop these enhancements by Nest will allow our DAOs to have the tools needed to operate on Mainnet in 2018. It should be a flexible enough toolkit that we are confident many DAOs will benefit. Plus, we plan on “eating our own dogfood” along the way.

### Details

An organization should be able to seamlessly create and manage multiple projects using a Planning app. The basic system would require:
* **Voting Patterns:** Create two new voting patterns to support range voting and consensus-based voting. These patterns would be able to be utilized on various planning tools.
  * **Range Voting:** Allowing for votes to be placed as a range of numerals. This pattern can be applied to various tools such as issue curation and collective budgeting. 
  * **Consensus Voting:** A consensus voting smart contract would allow for special voting sessions to be created, where the aim is to reach consensus among the voting session participants.
* **Github Integration:** Before we can utilize the decentralized git tool, it would be ideal to have an integration with a Github-based bounty system to provide immediate utility to Aragon DAOs. 
* **Task Planning Toolkit:** Tools should be added to the Planning app that allow issues to be collectively prioritized in addition to applying bulk bounties.
  * **Issue Curation:** In the Planning app, token holders or project members will be able to curate / prioritize the top issues that should be developed.
  * **Bulk Bounties:** Smart contracts will be developed that allow bounties to be allocated to Github issues in a bulk-fashion.
    * **Off-Chain Estimates:** The bounty estimates are determined off-chain or are input by a single party, yet require an approval vote from the DAO
    * **On-Chain Estimates:** Consensus or range voting contract is utilized for members to collectively estimate the value of task bounties. (Planning Poker)
* **Financial Planning Toolkit:** Tools should be added to the Planning app that allow for collective budgeting in addition to distributing rewards and dividends to token holders.
  * **Fixed Payout:** Payroll contract that allows an easy way to setup a recurring fixed allocations to projects or other DAOs.
  * **Dynamic Payout:** Payroll contract that allows for dynamic allocations that are determined using range voting.
  * **Payout Engine:** Pay sharing contract using a percentage-based distribution system, where the percentages are determined using range voting.
  * **Rewards Engine:** Distributes payments to token holders based on the number of tokens one has earned in a specific cycle of time (one-time reward) or based on the total tokens one holds (dividend).

#### Stretch Goals
* **Project Proposal:** Creating a user flow that makes the Project Proposal process more efficient.
* **Reputation Marketplace:** A reputation model will maintain the rules for how contributors can collect non-transferrable reputation tokens that will help with decentralizing management. With the reputation marketplace, organizations can experiment with or create different reputation models.
* **DAI Exchange:** Using a stable currency to allocate bounties will be important in some use cases to provide contributors peace of mind that the volatility of the market will not affect their ultimate payout. 

As part of the set of deliverables for this proposal, an enhancement plan will be developed for how the smart contracts can become cross-compatible with the decentralized git solution. Although ideally, we hope to work closely with the decentralized git team to have that cross-compatibility whenever the decentralized git solution deploys to Mainnet. We are happy to discuss this aspect of the strategy further. 

Ultimately, we do not want to build smart contracts that are “married” to Github, although we expect that it may take some time until all organizations fully transfer to the decentralized git solution, so offering cross-compatibility may be the best approach.

Please review the [White Paper](http://goo.gl/eXAybm) for full details.
