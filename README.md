# proofofselection
Consensus Algorithm for Decentralized Ledgers

A consensus algorithm in the most general form is a method in which decentralized nodes (e.g., computers, virtual machines, devices) come to an agreement on what data is added to a digital ledger. Consensus algorithms are often conceptually related to defeating the Byzantine Generals’ problem: How can multiple generals agree on a plan of attack without being able to reliably communicate with each other while having possible traitors sending false messages?

This can be done with something less resource-intensive than Proof of Work, something more balanced than Proof of Stake, something without a centralized coordinating process (Tangle Coordinator), and something that is not proprietary (Swirlds). Proposed instead is Proof of Selection, which involves building a digital ledger with an agreed upon method of ‘selecting’ the next nodes to create a block. A consensus is pre-determined; it is akin to planning a time to attack or retreating and defining a method of detecting traitors before being separated and going to the battlefield.

The concept of 'random' on a blockchain is said to be difficult. But this isn't true. Randomness has been difficult becuase of potential for manipulation, not because generating randomness is difficult. Removing manipulation is a matter of 'validation' and removal of the incentive to manipulate. Validation can occur with 'federated' transactions, or transactions that have been agreed upon by the rest of the nodes, or a large number of nodes. If an actor can't manipulate the transactions, they cannot manipulate the generated random value  resulting.

The goal of this algorithm is to 1. Provide cryptographic security (PoW is currently the baseline for real cryptographically secure blockchain) 2. Decentralize as much as possible. Even git commits eventually should  be governed by the chain. 3. Be modular such that it can be added to existing blockchains and technologies

I will be posting real code eventually, taking from bitcoin most likely (possibly in my other repo seligere).

Please contact me if you're interested or would like to help! 

kennie.jenkins@cyberspec.net
