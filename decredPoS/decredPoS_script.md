## Decred In Depth: Stake Voting
### Voice Over Script

Without a form of inclusive on-chain governance, pure proof-of-work currencies like Bitcoin surrender their users to the mercy of the overpowering miners who validate their transactions.  With no way to keep miners in check nor officially agree on consensus rule changes, Bitcoin leaves itself open to 51% attacks and community splitting hard forks.

Decred's Proof-of-Stake Voting system, one half of its hybrid proof-of-work - proof-of-stake protocol, gives control of the Decred chain and its future to its stakeholders, not its miners. Through participation in proof-of-stake voting, stakeholders have the power to stop 51% attacks, prevent unwanted hard forks, and shape the future of the project.

Here's how it works:

Decred's Proof-of-stake voting system is a lottery-like system that runs on tickets.

Decred stakeholders prove their stake by purchasing a ticket. In return, they receive a chance to have their voice heard by casting votes, and receive a portion of the Decred block reward for their efforts.

The price of a ticket is automatically adjusted by an algorithm at the end of each ticket window which spans 144 blocks. ( or, about 12 hours, given Decred's average block time of roughly 5 minutes.) This is done to keep the number of live tickets in the system as close as possible to the target 40,960 tickets.

Since each new block can contain up to 20 new ticket transactions, there are a maximum of 2,880 tickets up for grabs during each ticket window.

[some sort of short transition/intro into lifecycle]

A ticket's life begins when it is first mined into a block, and ends when it casts its vote. In rare circumstances, it is possible for a ticket to never cast its vote. This occurs with only about 2.2 percent of all tickets and results in a full refund on the price of the revoked ticket.

After being mined into a block, a ticket enters the immature stage of its vote casting quest. At this point, the ticketholder's funds used to purchase the ticket are locked but the ticket is not yet eligible to vote.

All tickets remain in the immature stage for 240 blocks (or about 20 hours), after which they become live and are added to the ticket pool where they wait (amongst about 40,960 other tickets) to be randomly selected to vote. 

How long a ticket will wait in the pool is entirely up to chance, but averages 30 days.

In addition to the 20 new tickets transactions, miners also randomly select 5 live tickets from the ticket pool for inclusion in the next block.

When a ticketholders ticket is selected to vote, their ballot must be broadcast to the network from either their own self-hosted voting wallet or on their behalf by a designated voting service provider. 

A ticketholders ballot will contain one block vote and zero to many consensus votes to be recorded on-chain.

Block votes are where stakeholders can take action to keep proof-of-work miners in check. The 5 block votes contained in each new block (block *N*) decided whether to accept or reject the previous one (block *N minus one*). If stakeholders decide to reject the block, then the included pending transactions are returned to the mempool and the miner is stripped of their block reward.

[short transition to consensus vote]

Consensus voting is a two stage process where stakeholders vote for or against the implementation of changes to Decred's consensus rules, or, the rules that determine what a valid block looks like.

Before the consensus vote can begin, a majority of nodes must upgrade to a new version of their software containing the change. The update threshold is met when 95% of the 1000 most recent blocks have the latest block version and 75% of the proof of stake votes within one stake version interval, 2016 blocks (or about 1 week), have the latest vote version. 

After the update threshold is met voting will being on the first block of the next rule change interval. 

Each rule change interval spans 8,064 blocks (or about 4 weeks) during which consensus votes are collected to be tallied. If at the end of the interval 90% of collected votes are abstaining, a revote occurs. Else, if 75% of non-abstaining votes signal yes, then the changes to the consensus rules will be automatically activated after a grace period of one additional rule change interval.

After a ticketholders ticket has voted and a 240 block waiting period, the funds used to purchase the voted ticket are unlocked and a portion of the block reward is credited to their account.

Additionally, live tickets give access to voting through Politeia, Decred's chain-anchored proposal system where anyone can propose new ideas to be voted on by stakeholders and shape the future of Decred.

To begin participating in the governance of Decred, download Decrediton at Decred.org and purchase Decred at any one of the many supporting exchanges.

Decred; Decentralized credits.



