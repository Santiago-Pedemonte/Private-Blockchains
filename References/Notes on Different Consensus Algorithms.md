# Consensus Algorithms
## Index:
  * [What are Consensus Algorithms and why use them?](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Notes%20on%20Different%20Consensus%20Algorithms.md#what-are-consensus-algorithms-and-why-use-them)
    * [Byzantine Fault Tolerance](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Notes%20on%20Different%20Consensus%20Algorithms.md#byzantine-fault-tolerance)
    * [How Consensus Algorithms solve this problem](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Notes%20on%20Different%20Consensus%20Algorithms.md#how-consensus-algorithms-solve-this-problem)
  * [Types of Consensus Algorithms](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Notes%20on%20Different%20Consensus%20Algorithms.md#types-of-consensus-algorithms)
    * [Proof of Work](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Notes%20on%20Different%20Consensus%20Algorithms.md#proof-of-work)
    * [Proof of Stake](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Notes%20on%20Different%20Consensus%20Algorithms.md#proof-of-stake)
    * [Proof of Authority](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Notes%20on%20Different%20Consensus%20Algorithms.md#proof-of-authority)

<details><summary> Different Consensus Algorithms </summary>
  
   <img class="fit-picture"
     src="https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Images/Different_Consensus_Algorithms.png"
     alt="Different Consensus Algorithms">
  
   [Source: 101 Blockchains](https://101blockchains.com/consensus-algorithms-blockchain/)
</details>

## What are Consensus Algorithms and why use them?

Consensus algorithms are a decision-making process for a group, where individuals of the group construct and support the decision that works best for the rest of them.

### Byzantine Fault Tolerance

Byzantine Fault Tolerance is a system with a particular event of failure. Many times there can be malfunctioning consensus systems.

These components are responsible for further conflicting information. Consensus systems can only work successfully if all the elements work in harmony. However, if even one of the component in this system malfunctions the whole system could break down.

Malfunctioning components always cause inconsistency in the Byzantine Fault Tolerance system, and that’s why it’s not ideal to use these consensus systems for a decentralized network. [Source](https://101blockchains.com/consensus-algorithms-blockchain/)
**Byzantine General's Problem:**
  * Imagine there’s a group of generals, where each one of them owns the Byzantine army. They are going to attack a city and take control, but for that, they’ll need to decide how to attack.
  * The generals can only communicate through a messenger, and some traitorous generals will try to sabotage the whole attack.
  * They can send unreliable information through the messenger, the messenger could also intentionally sabotage by delivering the wrong information or the messenger can even become the enemy.
  * Every general must come to a mutual decision and make sure that even the slightest number of traitors can’t cause the whole mission to fail.
  * According to research, it will take 3n+1 generals to deal with n traitors.
  * More on the [Byzantine Generals' Problem](https://www.youtube.com/watch?v=dfsRQyYXOsQ&ab_channel=MarkReddick)


### How Consensus Algorithms solve this problem

  * A consensus algorithm is a mechanism that allows users or machines to coordinate in a distributed setting. It needs to ensure that all agents in the system can agree on a single source of truth, even if some agents fail. In other words, the system must be fault-tolerant.
  * These Blockchain consensus models are just the way to reach an agreement. However, there can’t be any decentralized system without common consensus algorithms.
  * It won’t even matter whether the nodes trust each other or not. They will have to go by certain principles and reach a collective agreement. To do so, you have to check out all the Consensus algorithms.

The base idea behind any successful consensus algorithm, however, is that: **acting honestly is more profitable than acting dishonestly.** People respond to incentives.

## Types of Consensus Algorithms

### Proof of Work

Proof of Work (PoW) is the godfather of blockchain consensus algorithms. It was first introduced by Satoshi Nakamoto in the 2008 Bitcoin white paper, but the technology itself was conceived long before then:
    
>"Adam Back’s HashCash is an early example of a Proof of Work algorithm in the pre-cryptocurrency days. By requiring senders to perform a small amount of computing before sending an email, receivers could mitigate spam. This computation would cost virtually nothing to a legitimate sender, but quickly add up for someone sending emails en masse."

Proof of Work requires that a miner (the user creating the block) uses up some of their own resources for the privilege: 
  * That resource is computing power, which is used to hash the block’s data until a solution to a puzzle is found.
  * Hashing the block’s data means that you pass it through a hashing function to generate a block hash. 
  * The block hash works like a “fingerprint” – it’s an identity for your input data and is unique to each block.
  * It’s virtually impossible to reverse a block hash to get the input data. 
  * Knowing an input, however, it becomes trivial to confirm that the hash is correct by submitting the input through the function.

**How mining works:**
To create a block, miners must play **a guessing game**. They take information on all of the transactions that need to be added (and some other important data), then hash it all together. 
Since the transactions-to-add won’t change, the miners add a piece of information that is variable to avoid getting the same hash every time- a *nonce*. It’s a number that  changes with every attempt, so so miners a different hash every time.
Finding the hash that satisfies the conditions set out by the protocol, miners get the right to broadcast the new block to the network. At this point, the other participants of the network verify it and update their blockchains to include the new block.

For major cryptocurrencies today, the conditions are incredibly challenging to satisfy. The higher the hash rate on the network, the more difficult it is to find a valid hash. This is done to ensure that blocks aren’t found too quickly.
As one can imagine, trying to guess massive amounts of hashes can be costly in terms of electricity. The protocol will reward you with cryptocurrency if you find a valid hash.

![proof-of-work](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Images/What-is-proof-of-work.jpg)
Source: [Ledger](https://www.ledger.com/academy/blockchain/what-is-proof-of-work)

### Proof of Stake

Proof of Stake (PoS) was proposed in the early days of Bitcoin as an alternative to Proof of Work. In a PoS system, there’s no concept of miners, specialized hardware, or massive energy consumption. 

In PoS, there's no need to put forward an external resource (like electricity or hardware), but rather an internal one – cryptocurrency. Rules differ with every protocol, but there’s generally a minimum amount of funds a node must hold to be eligible for staking.
These funds are locked in a wallet (they can’t be moved while being staked). Each validator selects a block to stake their balance on. In a sense, they’re betting on the block that will be selected, and the protocol will choose one.
Stakers that bet on the chosen block receive a proportion of the transaction fees, depending on their stake. The more funds they have locked up, the more they stand to gain. But if they attempt to cheat by proposing invalid transactions, they’ll lose a portion (or all) of their stake. Therefore, acting honestly is more profitable than acting dishonestly.

Generally, there aren’t freshly-created coins as part of the reward for validators. The blockchain’s native currency must thus be issued in some other way. This can be done either via an initial distribution (i.e., an ICO or IEO) or by having the protocol launch with PoW before later transitioning to PoS.
To date, pure Proof of Stake has only really been deployed in smaller cryptocurrencies. Therefore, it’s unclear if it can serve as a viable alternative to PoW. While it appears theoretically sound, it will be very different in practice. 

Once PoS is rolled out on a network with a large amount of value, the system becomes a playing field of game theory and financial incentives. Anyone with the know-how to “hack” a PoS system would likely only do so if they could gain from it – therefore, the only way to find out if it’s feasible is on a live network.

From: [Binance Academy](https://academy.binance.com/en/articles/what-is-a-blockchain-consensus-algorithm)

![proof-of-stake](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Images/What-is-proof-of-stake.jpg)
Source: [Ledger](https://www.ledger.com/academy/blockchain/what-is-proof-of-stake)

### Proof of Authority

Proof of Authority (PoA) is a reputation-based consensus algorithm that introduces a practical and efficient solution for blockchain networks (especially the private ones). The term was proposed in 2017 by Ethereum co-founder and former CTO Gavin Wood. 

The PoA consensus algorithm leverages the value of identities, which means that block validators are not staking coins but their own reputation instead. Therefore, PoA blockchains are secured by the validating nodes that are arbitrarily selected as trustworthy entities.

PoA consensus algorithm may be applied in a variety of scenarios and is deemed a high-value option for logistical applications. When it comes to supply chains, for example, PoA is considered an effective and reasonable solution. It enables companies to maintain their privacy while availing the benefits of blockchain technology.

Some consider PoA to be a modified PoS, which leverages identity instead of coins. Due to the decentralized nature of most blockchain networks, PoS is not always suitable for certain businesses and corporations. In contrast, PoA systems may represent a better solution for private blockchains because its performance is considerably higher.

**The downside of the PoA mechanism is that it foregoes decentralization.**
