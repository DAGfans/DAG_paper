
The Swirlds Hashgraph Consensus Algorithm: Fair, Fast, Byzantine Fault Tolerance
by Leemon Baird

MAY 31, 2016

### Abstract
A new system, the Swirlds hashgraph consensus algorithm, is proposed
for replicated state machines with guaranteed Byzantine fault tolerance.
It achieves fairness, in the sense that it is difficult for an attacker to manipulate
which of two transactions will be chosen to be first in the consensus
order. It has complete asynchrony, no leaders, no round robin, no proof-ofwork,
eventual consensus with probability one, and high speed in the absence
of faults. It is based on a gossip protocol, in which the participants don’t
just gossip about transactions. They gossip about gossip. They jointly build a
hashgraph reflecting all of the gossip events. This allows Byzantine agreement
to be achieved through virtual voting. Alice does not send Bob a vote over
the Internet. Instead, Bob calculates what vote Alice would have sent, based
on his knowledge of what Alice knows. This yields fair Byzantine agreement
on a total order for all transactions, with very little communication overhead
beyond the transactions themselves.

- http://www.swirlds.com/downloads/SWIRLDS-TR-2016-01.pdf
- http://www.swirlds.com/downloads/SWIRLDS-TR-2016-02.pdf
