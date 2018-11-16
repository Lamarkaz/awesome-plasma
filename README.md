# Awesome Plasma [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated collection of resources for Ethereum Plasma research and implementations.

New items and improvment suggestions are welcome. Check the [contribution guidelines](contributing.md) then Submit a pull request if you have something to add.

<!-- MarkdownTOC depth=5 -->
## Table of Contents
- [Articles](#articles)
    - [Introductory](#introductory)
        - [Scalability Challenges](#scalability-challenges)
        - [Ethereum Plasma](#ethereum-plasma)
    -  [Research](#research)
        - [General Plasma](#general-plasma)
            - Cheaper Commitments
            - Fast Finality
            - Running the Numbers
            - zk-SNARKs
            - Generalized Plasma
        - [Plasma MVP](#plasma-mvp)
            - Mass Exits
            - Fast Withdrawals
            - Atomic Swaps
            - Confirmation Signatures
        - [Plasma Cash](#plasma-cash)
            - Merging/Splitting
            - Shorter Proofs
            - Checkpoints
            - Plasma Coin Defragmentation
            - Atomic Swaps
        - [Plasma Prime](#plasma-prime)
            - Cash History Reduction (RSA-ACC)
-  [Papers](#papers)
-  [Specs (Flavours)](#specs-flavour)
    - [Minimal Viable Plasma](#mininal-viable-plasma)
    - [More Viable Plasma](#more-viable-plasma)
    - [Plasma Cash](#plasma-cash)
    - [Plasma Prime](#plasma-prime)
-  [Videos and Talks](#videos-and-talks)
    - [Introductory Videos](#introductory-videos)
    - [Plasma Implementors Call](#plasma-implementors-call)
    - [Plasma Cryptoeconomics](#plasma-cryptoeconomics)
    - [General Plasma](#general-plasma)
    - [Plasma MVP](#plasma-mvp)
    - [Plasma Cash](#plasma-cash)
    - [Plasma Prime](#plasma-prime)
    
-  [Podcasts](#podcasts)
- [Links](#links)
    - [Plasma](#plasma)
    - [Plasma Cryptography](#plasma-cryptography)
    - [Plasma Cryptoeconomics](#cryptoeconomics)
- [Implementations](#implementations)
    - [Plasma MVP](#plasma-mvp)
    - [Plasma Cash](#plasma-cash)
    - [Plasma Prime](#plasma-prime)

<!-- /MarkdownTOC -->



## Articles

### Introductory

#### Scalability Challenges
1. [Breaking Down The Blockchain Scalability Trilemma](https://bitcoinist.com/breaking-down-the-scalability-trilemma/) by Bisade Asolo
2. [Blockchain’s Scaling Problem, Explained](https://media.consensys.net/the-state-of-scaling-ethereum-b4d095dbafae) by Connor Blenkinsop
3. [A beginner’s guide to Ethereum Scaling and Plasma](https://medium.com/elph/a-beginners-guide-to-ethereum-scaling-and-plasma-8c9ee8c8d498) by Abhinav Lanka
4. [The State of Scaling Ethereum](https://media.consensys.net/the-state-of-scaling-ethereum-b4d095dbafae) by ConsenSys


#### Plasma Ethereum
1. [Explained: Ethereum Plasma](https://medium.com/@argongroup/ethereum-plasma-explained-608720d3c60e) by Lukas Schor of Argon Group
2. [Plasma in 10 minutes](https://medium.com/chain-cloud-company-blog/plasma-in-10-minutes-c856da94e339) by Anthony Akentiev
3. [Ethereum Plasma Introduction](https://docs.google.com/presentation/d/1S9TQj-KjtUr0mGe16azwSlBkNV7chsypqvzyj1G7_ZE/edit#slide=id.g3b4fd31626_0_31)
4. [WTF is plasma? | EthResearch](https://ethresear.ch/t/wtf-is-plasma-link-and-info-repo-catching-people-up-on-plasma/2519)

## Research

### General Plasma
1. [Minimal Viable Plasma](https://ethresear.ch/t/minimal-viable-plasma/426) by Vitalik Buterin

#### Cheaper Commitments
1. [Merkle Mountain Ranges](https://github.com/opentimestamps/opentimestamps-server/blob/master/doc/merkle-mountain-range.md)
2. [Double-batched Merkle log accumulator](https://ethresear.ch/t/double-batched-merkle-log-accumulator/571)
3. [Double Batched Merkle Log Accumulators for Efficient Plasma](https://ethresear.ch/t/double-batched-merkle-log-accumulators-for-efficient-plasma-commitments/2313) Commitments

#### Fast Finality
1. [On Settlement Finality](https://blog.ethereum.org/2016/05/09/on-settlement-finality/)
2. [Cryptoeconomic finality](https://github.com/omisego/research/issues/29)

#### Running the Numbers
1. [Zk-SNARKs: Under the Hood](https://medium.com/@VitalikButerin/zk-snarks-under-the-hood-b33151a013f6)
2. [Zk-SNARKs for Plasma](https://ethresear.ch/t/plasma-is-plasma/2195)
3. [Plasma snapp]()

#### Generalized Plasma

### Plasma MVP

#### Mass Exits
1. [Proving UTXO sum validity for mass exits](https://ethresear.ch/t/proving-utxo-sum-validity-for-mass-exits/2023)
2. [Basic Mass Exits for Plasma MVP](https://ethresear.ch/t/basic-mass-exits-for-plasma-mvp/3316)

#### Fast Withdrawals
1. [Simple Fast Withdrawals](https://ethresear.ch/t/simple-fast-withdrawals/2128)
2. [Enabling Fast Withdrawals for Faulty Plasma Chains](https://ethresear.ch/t/enabling-fast-withdrawals-for-faulty-plasma-chains/2909)

#### Atomic Swaps
1. [Using Relayers for Order Matching](https://github.com/omisego/research/issues/20)

#### Confirmation Signatures
1. [Why Do We Need Confirmation Signatures?](https://ethresear.ch/t/why-do-dont-we-need-two-phase-sends-plus-confirmation/1866/14?u=kfichter)
2. [Confirmation Signatures Must Be Included on the Plasma Chain](https://ethresear.ch/t/plasma-vulnerabiltity-sybil-txs-drained-contract/1654)
3. [Griefing Vectors in Confirmation Signatures](https://ethresear.ch/t/griefing-vectors-in-confirmation-signatures/2301)

### Plasma Cash
1. [ELI5: Plasma Cash — Scaling Ethereum](https://hackernoon.com/eli5-plasma-cash-ff242c55e8de) by Elie Steinbock

#### Merging/Splitting
1. [Proposal for Plasma Cash Splitting and Merging](https://ethresear.ch/t/one-proposal-for-plasma-cash-with-coin-splitting-and-merging/1447)
2. [Arbitrary Coin Merging in Plasma Cash](https://ethresear.ch/t/plasma-cash-plasma-with-much-less-per-user-data-checking/1298/53)

#### Shorter Proofs
1. [Plasma XT](https://ethresear.ch/t/plasma-xt-plasma-cash-with-much-less-per-user-data-checking/1926)
2. [Plasma Cash Without Any Blockchain at All](https://ethresear.ch/t/plasma-cash-without-any-blockchain-at-all/1974)

#### Checkpoints
1. [Plasma XT](https://ethresear.ch/t/plasma-xt-plasma-cash-with-much-less-per-user-data-checking/1926)
2. [Plasma checkpoint cost](https://ethresear.ch/t/plasma-checkpoint-cost-and-block-time/2016)

#### Plasma Coin Defragmentation
1. [Plasma Cash Defragmentation](https://ethresear.ch/t/plasma-cash-defragmentation/3410)
2. [Plasma Cash Defragmentation, take 2](https://ethresear.ch/t/plasma-cash-defragmentation-take-2/3515)
3. [Plasma Cash Defragmentation, take 3](https://ethresear.ch/t/plasma-cash-defragmentation-take-3/3737)

#### Atomic Swaps
1. [Plasma Cash Minimal Atomic Swap](https://ethresear.ch/t/plasma-cash-minimal-atomic-swap/3409)

### Plasma Prime
#### Cash History Reduction (RSA-ACC)
1. [RSA Accumulators for Plasma Cash history reduction](https://ethresear.ch/t/rsa-accumulators-for-plasma-cash-history-reduction/3739)

## Papers 
1. [Plasma: Scalable Autonomous Smart Contracts](https://plasma.io/plasma.pdf) by Joseph Poon and Vitalik Buterin
2. [Efficient verifiable delay functions](https://eprint.iacr.org/2018/623.pdf) by Benjamin Wesolowski

## Specs (Flavours)

### Minimal Viable Plasma
1. [Minimal Viable Plasma Specification | EthResearch](https://ethresear.ch/t/minimal-viable-plasma/426) by Vitalik Buterin
2. [Plasma MVP Specification](https://www.learnplasma.org/en/resources/#plasma-mvp-specification) - Learn Plasma

### More Viable Plasma
1. [More Viable Plasma Specification](https://ethresear.ch/t/more-viable-plasma/2160) by Ben Jones and Kelvin Fichter

### Plasma Cash
1. [Plasma Cash Simple Spec](https://karl.tech/plasma-cash-simple-spec/) by Karl Floersch

### Plasma Prime
Currently, there's now official Plasma Prime Implementation spec, but proposals.
1. [Plasma Prime design proposal](https://ethresear.ch/t/plasma-prime-design-proposal/4222) - by Igor Gulamov
2. [Log(coins)-sized proofs of inclusion and exclusion for RSA accumulators](https://ethresear.ch/t/log-coins-sized-proofs-of-inclusion-and-exclusion-for-rsa-accumulators/3839) by Vitalik Buterin  
3. [Plasma Prime is Plasma Cash with RSA Accumulators](https://ethresear.ch/t/plasma-prime-spec/4181/2) - Vitalik buterin explanation of Plasma Prime in Plasma Implementers Call #17 intrepreted by Sourabh Niyogi.

## Videos and Talks

### Introductory Videos 
1. [Ethereum Plasma MVP Overview](https://www.youtube.com/watch?v=jTc_2tyT_lY) by Karl Floersch
2. [Scaling Ethereum with Plasma](https://www.youtube.com/watch?v=plf-kG8jt9c) by Joseph Poon | Silicon Valley Ethereum Meetup
3. [Ethereum Plasma Explained for Beginners](https://www.youtube.com/watch?v=nGCATfbuaXw) - Financial Responsibility

### Plasma Implementer Calls
1. [Call #1](https://www.youtube.com/watch?v=_DPftmg7zR8&t=41s) - During this call we discussed the purpose of the group, logistics, introductions, technical details, and more!
2. [Call #2: Q&A](https://www.youtube.com/watch?v=c_Z8F6FUJxU) - During this call we went over a number of common Plasma questions.
3. [Call #3: ❤️ & Updates](https://www.youtube.com/watch?v=JHRXrvdvLd0) - Today we welcome the Taiwan team--a group of talented engineers who came together to implement the Plasma MVP. We also discuss Cosmos's challenges when exploring Plasma, a number of David's designs, and more fun stuff.

4. [Call #4: Cryptokitties Designs & Updates](https://www.youtube.com/watch?v=IFuxe3vL--k) - Today we discuss some constructions which can be used to scale Cryptokitties! And of course update Plasma progress and have some fun technical discussions--including a new Plasma implementation from voltairelabs.

5. [Call #5: Plasma Cash!](https://www.youtube.com/watch?v=GSDc_F8xHKo) - Today we discuss Plasma Cash and potential designs and research topics which are worth exploring. We dive deep into technicals! :)
6. [Call #6: PoS, Splitting & Exits, oh my!](https://www.youtube.com/watch?v=k82L4YohW_E) - Today we discuss designs for Plasma Cash with PoS and sharded validation, coin splits, exits which allow for invalid state transitions, a cryptoeconomics course, and more!
7. [Call #7: Merkle Trees in Bloom (filters)](https://www.youtube.com/watch?v=uxKcK-4PgLk) - Today we discuss designs which involve sparse merkle trees, bloom filters, and some more splitting! We also welcome the Blockchain @ Berkeley crew who are working on a great Plasma Cash implementation! Yay!
8. [Call #8: CAS Checkpointing!](https://www.youtube.com/watch?v=2GgoYSFdTtQ) - Today we discuss a whole bunch of topics, from account abstraction to Plasma XT which uses cryptoeconomic aggregate signatures (CAS) for checkpointing! Tons of fun!
9. [Call #9: Plasma Debit & Instant Withdrawals!](https://www.youtube.com/watch?v=sgr8bHRZUEM) - Today we get to chat about simple splits in Plasma Cash, called Plasma Debit--a critical part of the Plasma Cash spec! Thanks Dan! Plus Vitalik explains instant withdrawals and Plasma with general state transitions.
10. [Call #10: MVP Implementation & DB Merkle log Accumulators](https://www.youtube.com/watch?v=M_PtvXrrTko) - Today we get to welcome Loom and Kyber to the call! Plus we discuss an update to the Plasma MVP implementation which Kelvin is working on--a research version is pretty much complete! We also cover Plasma Cash & debit atomic swaps, as well as Double-batched Merkle log accumulators!
11. [Call #11: State Channels](https://www.youtube.com/watch?v=w45PXH0DJa0) - Today we celebrate Loom's release of their Plasma Cash implementation, discuss state channels which are opened on and off of Plasma chains, Plasma Debit with Dan, and wrap it up with some experimental zkSNARKs talk! Amazing times!

12. [Call #12: Run the Gamut](https://www.youtube.com/watch?v=Wbnr-9euMic) - Today we discuss a wide variety of topics! We start out discussing Plasma educational materials, then move on to BLS signatures, smart contracts in Plasma, light clients, and finally we get SNARKy! 
13. [Call #13: Have Fun with Batch Auction Plasma!](https://www.youtube.com/watch?v=SETRL75eDgE) - Today we begin with discussions around nitty gritty Plasma Debit liquidity markets. Then we talk about Plasma working groups to get the Plasma research done in person, plus hosting a LIVE Plasma call in devcon! We chat about Plasma XT & then Gnosis gives an awesome presentation on their batch auction Plasma construction. Fun!

14. [Call #14: Care for Collateral](https://www.youtube.com/watch?v=lGqNTzluX10) - Today we start out discussing using collateral to reduce user validation load in Plasma Cash. This gets us into triple spends & eventually we talk about the importance and difficulty of analyzing the value of in-flight transactions. Then we mention some core cryptoeconomic principles around past provability & future accountability.

15. [Call #15: Atomic Swaps!](https://www.youtube.com/watch?v=NQJfUUe2-pA) - Today we dive deep into atomic swaps in both Plasma Debit and Plasma Cash. We discuss different implementation details and greifing opportunities. Next some fun discussions around watch towers!

16. [Call #16: Cashflow and Leap](https://www.youtube.com/watch?v=0ApUUoWYt8U&t=6s) - Today is especially exciting! We start out by discussing Plasma Cashflow which enables fungible assets on Plasma Cash! Woo! It's finally here! Then we talk about Plasma Leap, the first attempt at a general EVM Plasma!

17. [Call #17: Really Super Awesome Episode (RSA)](https://www.youtube.com/watch?v=YjTF05SeYxo&t=306s) - Today Vitalik reviews his solution to the tx history proof size growth in Plasma Cash! Woo! It uses RSA accumulators & is super stylish. We are nearly there... Then we discuss Plasma Leap (even more fun!)


### Plasma Cryptoeconomics
1. [De/2018 - Cryptoeconomic Incentive Mechanisms](https://www.youtube.com/watch?v=6kv0DTU3T_E) by Joseph Poon, Plasma & Lightning Network
2. [Reading the Plasma White Paper with Ameen Soleimani](https://www.youtube.com/watch?v=jvlunzEl_so) - Decypher Media
3. 

### Plasma Cryptography
1. [Accumulators for UTXOs - Scaling Bitcoin 2018 "Kaizen" Day 1 Part 3](https://www.youtube.com/watch?v=IMzLa9B1_3E&t=3521s) by Benedikt Bünz


## Podcasts
1. [Plasma Cash and the Ethereum Roadmap](https://epicenter.tv/episode/232/) by Karl Floersch

## Links
1. [Learn Plasma](http://learnplasma.org)
2. [Cryptoeconomics: An Introduction](https://cryptoeconomics.study)
3. [Plasma Officical Website and Whitepaper](https://plasma.io)
4. [EthResearch | Plasma Board](https://ethresear.ch/c/plasma)

## Implementations

### Plasma MVP and MoreVP
1. [OmiseGO's Plasma MVP](https://github.com/omisego/plasma-mvp)
2. [Kyokan's Plasma MVP](https://github.com/kyokan/plasma)
3. [Taiwans team's Plasma MVP](https://github.com/ethereum-plasma/plasma)
4. [Voltairelabs's Plasma MVP](https://github.com/voltairelabs/plasma)
5. [Bankex's Plasma Parent Contract](https://github.com/BANKEX/PlasmaParentContract)
4. [Plasma MVP without Confirmations](https://hackmd.io/o16IqtiJSgG2ez5w9Ug5aw?view)

### Plasma Cash and Debit
1. [Loomnetwork's Plasma Cash](https://github.com/loomnetwork/plasma-cash)
2. [Loom Network: Plasma Cash for ERC721 Tokens](https://ethresear.ch/t/loom-network-plasma-cash-for-erc721-tokens/2385)
3. [Using Merklix tree to checkpoint an UTXO set](https://www.deadalnix.me/2016/09/29/using-merklix-tree-to-checkpoint-an-utxo-set/)
4. [State Channels and Plasma Cash](https://ethresear.ch/t/state-channels-and-plasma-cash/1515)
5. [Interlinking plasma exit request with plasma correctness proofs using snark/stark](https://ethresear.ch/t/interlinking-plasma-exit-request-with-plasma-correctness-proofs-using-snark-stark/2331)
6. [Plasma Debit: Arbitrary-denomination payments in Plasma Cash](https://ethresear.ch/t/plasma-debit-arbitrary-denomination-payments-in-plasma-cash/2198)

### Plasma Prime
1. [Plasma Prime](https://github.com/endorphin/plasmaprime) by River Keefer

