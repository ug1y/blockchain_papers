# Blockchain papers
According to my preference, I collect prevalent papers about blockchain and also make some notes for academic research. All papers are classified into seven categories.

## List of categories
- [Overview](#Overview)
- [Consensus](#Consensus)
- [Scalability](#Scalability)
- [Privacy](#Privacy)
- [Analysis](#Analysis)
- [Smart Contract](#Smart-Contract)
- [Application](#Application)

---

## Overview
['08] [Bitcoin: A Peer-to-Peer Electronic Cash System](Overview/2008_Bitcoin_A_Peer-to-Peer_Electronic_Cash_System.pdf). Nakamoto S. 
>Note: The first paper that introduced the concept of blockchain. This paper presented a complete system by mainly defining transactions with multi-input and multi-output, chain structure of blocks containing transactions and proof of work for the majority decision. Besides, the incentive mechanism implies that the one who creates a new block gains reward.

[S&P '15] [SoK: Research Perspectives and Challenges for Bitcoin and Cryptocurrencies](Overview/2015_SoK_Research_perspectives_and_challenges_for_bitcoin_and_cryptocurrencies.pdf). Bonneau J, Miller A, Clark J, Narayanan A, Kroll JA, Felten EW. 
>Note: This paper provided the first systematic exposition Bitcoin and the many related cryptocurrencies. The authors identified three key components of Bitcoin’s design, which is Transaction & Scripts, Consensus & Mining, and Peer-to-Peer Network. The analysis of Bitcoin’s properties and future stability stands in theory position to get some insight. This paper is good for readers to grasp the core of Bitcoin.

## Consensus
[S&P '14] [Permacoin: Repurposing Bitcoin Work for Data Preservation](Consensus/2014_Permacoin_Repurposing_Bitcoin_Work_for_Data_Preservation.pdf). Miller A, Juels A, Shi E, Parno B, Katz J. 
>Note: The authors modified Bitcoin by repurposing mining resources from electric power to distributed storage of archival data. The scheme designs an alternative block header based on Proofs-of-Retrievability (PORs), which means that miners should work for generating valid PORs to get block reward. Successfully minting money with this SOP requires local, random access to a copy of a file.

[SOSP '17] [Algorand Scaling Byzantine Agreements for Cryptocurrencies](Consensus/2017_Algorand_Scaling_Byzantine_Agreements_for_Cryptocurrencies.pdf). Gilad Y, Hemo R, Micali S, Vlachos G, Zeldovich N. 
>Note: Algorand is a new cryptocurrency with high confidence in transaction confirmation. It uses a sortition algorithm based on Verifiable Random Functions (VRF) to scale the consensus to many users, which are selected to participate in a new Byzantine Agreement (BA) protocol to reach consensus. The sortition algorithm can control the number of users in each consensus phase by adjusting parameters.

## Scalability
[CCS '16] [A Secure Sharding Protocol For Open Blockchains](Scalability/2016_A_Secure_Sharding_Protocol_For_Open_Blockchains.pdf). Luu L, Narayanan V, Zheng C, Baweja K, Gilbert S, Saxena P. 
>Note: This paper proposed a new distributed agreement protocol for permission-less blockchains called ELASTICO. It uniformly partitions the mining network into smaller committees, each of which processes a disjoint set of transactions (or “shards”). The sharding protocol assigns each identity to an s-bit committee, where each miner gets its own identity by computing a POW-like solution.

[NSDI '16] [Bitcoin-NG: A Scalable Blockchain Protocol](Scalability/2016_Bitcoin-NG_A_Scalable_Blockchain_Protocol.pdf). Eyal I, Gencer AE, Sirer EG, Renesse R. 
>Note: This paper presents Bitcoin-NG, a new blockchain protocol that is designed to scale for higher transaction throughput. The protocol divides time into epochs. In each epoch, a single leader is in charge of transaction processing. Thus, it introduces two types of blocks: key blocks for leader election and microblocks that contain the ledger entries, and proposes heaviest chain rule for security concern.

## Privacy


## Analysis
[INFOCOM '18] [Understanding Ethereum via Graph Analysis](Analysis/2018_Understanding_Ethereum_via_Graph_Analysis.pdf). Chen T, Zhu Y, Li Z, Chen J, Li X, Luo X, Lin X, Zhang X. 
>Note: This paper conducts the first systematic study to characterize Ethereum through graph analysis. Firstly, the authors collect all transaction data and then construct three graphs, namely money flow graph (MFG), smart contract creates graph (CCG), and smart contract invocation graph (CIG). Lastly, they conduct graph analysis by computing metrics including degree distribution, clustering, degree correlation, etc.

[USENIX '18] [An Empirical Analysis of Anonymity in Zcash](Analysis/2018_An_Empirical_Analysis_of_Anonymity_in_Zcash.pdf). Kappos G, Yousaf H, Maller M, Meiklejohn S. 
>Note: This paper examines the extent to which anonymity is achieved in Zcash. To achieve the goal, the authors applied well-known clustering heuristics developed for Bitcoin and attribution heuristics into Zcash's shielded pool, the anonymity set for users wishing to spend coins privately. Based on identifiable patterns of usage, They conclude that it is also possible to shrink privacy.

## Smart Contract


## Application
[USENIX '16] [Blockstack A Global Naming and Storage System Secured by Blockchains](Application/2016_Blockstack_A_Global_Naming_and_Storage_System_Secured_by_Blockchains.pdf). Ali M, Nelson J, Shea R, Freedman MJ. 
>Note: This paper first describes the experiences about deploying a decentralized PKI service built on top of the Namecoin blockchain. Learning from the experiences, the authors concluded various challenges and proposed Blockstack, a blockchain-based naming and storage system. The system worked in Bitcoin with separate control plane (blockchain layer and virtualchain layer) and data plane (routing layer and data storage layer).
