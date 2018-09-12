## Decred In Depth: On-chain Governance
### Voice Over Script

Without a form of inclusive on-chain governance, pure proof-of-work currencies like Bitcoin are at the mercy of their proof-of-work miners.  With *no* way to keep miners in check *or* agree on consensus rule changes, Bitcoin leaves itself open to 51% attacks and community splitting hard forks.

**Decred's** **Proof-of-Stake Voting** system, (which is *one half* of its hybrid proof-of-work - proof-of-stake protocol), puts power over the Decred chain in the hands of its stakeholders as opposed to its miners. By participating in proof-of-stake voting, stakeholders have the power to stop 51% attacks, prevent unwanted hard forks, and shape the future of the project.

Here's how it works:

Decred Proof-of-stake voting is a lottery-like system that runs on tickets.

Decred stakeholders prove their stake by *purchasing* tickets. In return, they get a chance to cast their votes *and* increase their stake (as *reward* for their *active* voting efforts).

The *price* of a ticket is automatically adjusted by an algorithm at the end of each **ticket window** or every 144 blocks; ( about 12 hours, given Decred's average **block time** of roughly 5 minutes.) This keeps the number of *live* tickets in the system as close as possible to the target 40,960 tickets. Since *each* block can contain up to 20 new ticket transactions, there are a maximum of 2,880 tickets up for grabs at the current price per ticket window.

A ticket's life *begins* when it is first mined into a block, and *ends* when it votes. In rare circumstances, it is possible for a ticket to never vote. This occurs with only about 2.2 percent of all tickets and results in a full refund of the revoked ticket's price.

After being mined into a block, a ticket enters the immature stage of its vote casting quest. At this point, the ticketholder's funds used to purchase the ticket are locked, but the ticket is not yet eligible to vote.

All tickets remain in the immature stage for 240 blocks (or about 20 hours), and then become live. All *live* tickets are added to the **ticket pool** where they wait (amongst about 40,960 other tickets) to be randomly selected to vote. 

In addition to the 20 new tickets transactions, miners randomly select 5 live tickets from the ticket pool for inclusion in the next block.

How long an individual ticket will wait in the pool before being selected is entirely up to chance, but averages 30 days.

When a ticketholder's ticket *is* selected to vote, their ballot must be broadcast to the network from either their own *self-hosted* **voting wallet** or by a designated **voting service provider** on their behalf. 

A ticketholder's ballot will contain one **block vote** and zero to many **consensus votes** to be recorded *on-chain*.

Stakeholders can take action to keep proof-of-work miners in check with block votes. The 5 block votes contained in each new block decide whether to accept or reject the previous block. If stakeholders decide to reject the block, pending transactions are returned to the mempool and the miner is stripped of their block reward.

[short transition to consensus vote]

Consensus voting is a two stage process where stakeholders vote for or against changes to Decred's consensus rules, or, the rules that determine the parameters of a valid block.

Before the consensus vote can begin, a majority of nodes must upgrade to the newly released version of their software containing the proposed change. The update threshold is met when 95% of the 1000 most recent blocks and 75% of the proof of stake votes within *one* **stake version interval**, 2016 blocks (or about 1 week), have the latest version. 

After the update threshold is met voting will being on the *first block* of the next **rule change interval**. 

Each rule change interval spans 8,064 blocks (or about 4 weeks) during which consensus votes are collected to be tallied. A revote occurs if 90% of collected votes are abstaining at the end of the interval. If 75% of non-abstaining votes signal yes, then the changes to the consensus rules will be automatically activated after a grace period of one additional rule change interval.

After a ticketholders ticket has voted and a 240 block waiting period has passed (about 12 hours), the funds used to purchase the voted ticket are unlocked and a portion of the block reward is credited to their account as reward.

While their live tickets are waiting in the ticket pool, ticketholders also have access to proposal voting through Politeia, Decred's chain-anchored proposal system. Through Politeia anyone can shape the future of Decred by proposing new ideas for stakeholders to vote on.

To begin participating in the governance of Decred, download Decrediton at Decred.org and purchase Decred at any one of the many supporting exchanges.

Decred; Decentralized credits.



