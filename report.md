This report consolidates 20 clusters of addresses into a single document for practicality. 

Each cluster is independent, with detailed arguments provided as to why each qualifies as a Sybil cluster potentially detrimental to the Layer Zero project. 
This report format is inspired by the one shared by Bryan on Twitter on May 24, though the **clusters are solely derived from my personal research**. 

As a French speaker not fully fluent in English, this report has been translated using ChatGPT-4; apologies for any syntactic imprecisions.

# Detailed Methodology

To identify these clusters, I capitalized on a common mistake among Sybil schemes: using the same deposit address on a centralized exchange (CEX). 

I employed SQL queries on Dune Analytics to create a custom dashboard, which helped me find multiple addresses interacting with the same CEX deposit address. I refined my searches to discover wallets interacting with the initially identified addresses, broadening my clusters to include at least 20 wallets for relevance. 
All addresses were then manually checked using Layer Zero Scan, the premium version of DeBank (an excellent tool once mastered), and Arkham Intel. 
Arkham is a useful tool, but it does not map all the chains used by Layer Zero, so a manual double-check is mandatory to find the Sybils that have used the chains not mapped by Arkham! 

The main indicators for detecting these clusters were the identical CEX deposit address and similar on-chain activities (e.g., the same dates, interaction orders with protocols, transfers of bridgeable Layer Zero tokens like JOE among cluster wallets). 



Every detail was manually verified to minimize false positives.

I hope you find this analysis useful!

# Reward Address (If Eligible)

0xBe971035fD87DBbDdAbf48763d4f12CF08F50895

(fresh wallet)


# Table of Contents

<details>

1. [Cluster 1](#cluster-1)
2. [Cluster 2](#cluster-2)
3. [Cluster 3](#cluster-3)
4. [Cluster 4](#cluster-4)
5. [Cluster 5](#cluster-5)
6. [Cluster 6](#cluster-6)
7. [Cluster 7](#cluster-7)
8. [Cluster 8](#cluster-8)
9. [Cluster 9](#cluster-9)
10. [Cluster 10](#cluster-10)
11. [Cluster 11](#cluster-11)
12. [Cluster 12](#cluster-12)
13. [Cluster 13](#cluster-13)
14. [Cluster 14](#cluster-14)
15. [Cluster 15](#cluster-15)
16. [Cluster 16](#cluster-16)
17. [Cluster 17](#cluster-17)
18. [Cluster 18](#cluster-18)
19. [Cluster 19](#cluster-19)
20. [Cluster 20](#cluster-20)
21. [Cluster 21](#cluster-21)
22. [Cluster 22](#cluster-22)

</details>

As the cluster are independant and a description comes with every cluster, the two following sections have been regrouped.

This following section is an rotation of the list of the addresses of the cluster and its description: the CEX deposit address some of the addresses share, an Arkham diagram & the second layer of detection.

# Reported Addresses & Description







## CLUSTER 1


The first 28 addresses of the cluster share the same Binance deposit address 0x0b08063Ff2b8f04AfB65268Bae43223Ac2D6b0b5. The rest are linked to numerous addresses of the cluster, multiple times.

```
0xbc8744370bcb6d5abf5de8b4086ecfbb4c5629c3
0x2ed3f43f52afef1cf5235d71052779e45b9da70c
0x03f528fb4f141660e28ad57a0fe575bf74a2f3d8
0x27092ff6a7be233f12e68592b4374677175572a2
0x9f89fa91440dd9084182d22ce044d46695ec5536
0x560fbe5649e78ff8987519f12cd917d436f32df6
0x2cef35ddad95cd702ac8bc9ef423abae9155ee1c
0x30c98ab8fb66212634bf284f3c13b1e1fe61b3ce
0x20d677dda669efd7aebf5140b3556590fb811f8c
0xf0b11e644f1b40aea32a3f078c0603751e54e49c
0x93a3869ae9abf012a3301edf8add89c4c6cc6285
0xd6a02bbcc789beca35b72bdf1092af64ce019193
0x4cd575b1233c07674090a1c138ffca76df7771b7
0x69b62c4fb201f7509bb0c3accc20f1291f801a46
0x17236f75f5a83ff632ee3ca9102edebb9a888888
0x69187183e33161ec98f77f9154feb61de56fb53a
0xb0e53390e4697e65d6c2ed5213e49b8390da9853
0x692f04b913c7c88208ace123baf36752c86da64b
0xee78c446fabb72eeb9cc9d314e35125fd4e257c7
0xb2b9300475af157676c44ee64d39a5eb3c294dbd
0x3b54b824ccfe122397c44d99f2df5b5adb39a919
0x70e4fbce45615ceb161d5f06e1815d27bec5f47a
0x7a0ea4aeb66411f76d0d8298bc074e45ebdfe15d
0x37bc1d287251978c968d64290cb94b681be7e57f
0x42eed31a8bb26099364b301ae087acfb037ba864
0x12c162d1a60b518fee11686044210fffc14b71d4
0xed65878f505a6f2789f4f166169e37226adf6c5f
0x47cd28396e01f0000e6fa5b6c0d27952660158c5
```
