---
layout: default
title: Award
group: Conference

awards:
  - type: Best Paper Award
    papers:
    
    - title: "Barracuda: Theoretical Analysis of the Power of l-polling in Proof-of-Stake Blockchains"
      authors: Giulia Fanti (CMU); Jiantao Jiao (UC Berkeley); Ashok Makkuva, Sewoong Oh, Ranvir Rana, Pramod Viswanath (UIUC)
      abstract: 'A blockchain is a database of sequential events that is maintained by a distributed group of nodes. A key consensus problem in blockchains is that of determining the next block (data element) in the sequence. Many blockchains address this by electing a new node to propose each new block. The new block is (typically) appended to the tip of the proposer’s local blockchain, and subsequently broadcast to the rest of the network. Without network delay (or adversarial behavior), this procedure would give a perfect chain, since each proposer would have the same view of the blockchain. A major challenge in practice is forking. Due to network delays, a proposer may not yet have the most recent block, and may therefore create a side chain that branches from the middle of the main chain. Forking reduces throughput, since only one a single main chain can survive, and all other blocks are discarded. We propose a new P2P protocol for blockchains called Barracuda, in which each proposer, prior to proposing a block, polls l other nodes for their local blocktree information. Under a canonical stochastic network model, we prove that this lightweight primitive strongly ameliorates the informational imbalance: the resulting throughput is as if the entire network were a factor of l faster. We provide guidelines on how to implement Barracuda in practice, with a specific emphasis on proof-of-stake blockchains, guaranteeing robustness against several real-world factors.<br/>'
      link: https://doi.org/10.1145/3323679.3326533


---

# ACM MobiHoc 2019 Award

{% include awards.html awards=page.awards %}

## Finalists

- “A Mean Field Game Analysis of Distributed MAC in Ultra-Dense Multichannel Wireless Networks” by Dheeraj Narasimha; Srinivas Shakkottai; Lei Ying

- “Transient Dynamics of Epidemic Spreading and Its Mitigation on Large Networks” by Chul-Ho Lee; Srinivas Tenneti; Do Young Eun

- “Minimizing the Age of Information in Wireless Networks with Stochastic Arrivals” by Igor Kadota; Eytan Modiano

- “Timely-Throughput Optimal Coded Computing over Cloud Networks” by Chien-Sheng Yang; Ramtin Pedarsani; Salman Avestimehr

- “Barracuda: Theoretical Analysis of the Power of l-polling in Proof-of-Stake Blockchains” by Giulia Fanti; Jiantao Jiao; Ashok Makkuva; Sewoong Oh; Ranvir Rana; Pramod Viswanath

- “Side-information-aided Non-coherent Beam Alignment Design for Millimeter Wave Systems” by Yi Zhang; Karthik Patel; Sanjay Shakkottai; Robert Heath Jr.

- “Wideband Full-Duplex Phased Array with Joint Transmit and Receive Beamforming: Optimization and Rate Gains” by Tingjun Chen; Mahmood Baraani Dastjerdi; Harish Krishnaswamy; Gil Zussman

