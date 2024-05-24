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

pas fini

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

As you can see here, Arkham was not sufficient since it does not map all the chains. Therefore, I had to use DeBank and Dune to refine the identification of this cluster.

![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/49895731-497f-499b-a761-440c2fed134b)

https://platform.arkhamintelligence.com/visualizer/entity/0x0b08063Ff2b8f04AfB65268Bae43223Ac2D6b0b5,0xbC8744370bCb6D5AbF5dE8B4086ecfBB4C5629C3,0x2eD3F43F52afEf1Cf5235d71052779e45B9dA70c,0x03f528fb4F141660e28Ad57a0fE575bf74a2f3d8,0x27092FF6a7Be233F12e68592B4374677175572A2,0x9f89fa91440Dd9084182d22ce044d46695Ec5536,0x560FBE5649e78fF8987519F12cD917d436f32Df6,0x2CeF35DDad95CD702aC8bc9ef423aBae9155ee1C,0x30c98Ab8FB66212634bF284F3C13b1e1fe61B3CE,0x20d677DDA669EfD7AEbf5140B3556590Fb811F8C,0xF0B11e644F1b40AeA32a3F078C0603751e54e49c,0x93A3869aE9Abf012A3301EDF8ADd89c4c6cc6285,0xD6a02bbcc789BEcA35b72bdf1092AF64ce019193,0x4cD575b1233c07674090A1C138ffca76DF7771b7,0x69B62C4Fb201F7509BB0c3aCcc20F1291f801a46,0x17236F75F5a83ff632Ee3Ca9102EDEBB9A888888,0x69187183E33161eC98f77F9154feb61DE56fB53A,0xB0e53390e4697e65d6c2ed5213e49b8390da9853,0x692f04B913C7c88208acE123bAF36752C86Da64b,0xee78C446fABB72eEB9cc9D314E35125FD4E257C7,0xb2b9300475aF157676C44eE64d39a5eB3C294DbD,0x3b54b824ccFe122397C44d99f2Df5B5adB39A919,0x70e4FBcE45615cEB161d5F06e1815D27bec5F47a,0x7A0Ea4Aeb66411F76d0D8298BC074e45eBDFE15D,0x37BC1d287251978C968d64290Cb94B681bE7e57f,0x42EeD31a8BB26099364b301ae087ACFB037Ba864,0x12c162D1a60B518feE11686044210FfFc14B71d4,0xeD65878F505A6f2789F4f166169E37226Adf6c5f,0x47cd28396e01f0000e6Fa5B6c0d27952660158c5?flow=self&positions=%7B%220x3b54b824ccFe122397C44d99f2Df5B5adB39A919%22%3A%7B%22fx%22%3A68%2C%22fy%22%3A-34%7D%2C%220x20d677DDA669EfD7AEbf5140B3556590Fb811F8C%22%3A%7B%22fx%22%3A81%2C%22fy%22%3A-29%7D%2C%220xB0e53390e4697e65d6c2ed5213e49b8390da9853%22%3A%7B%22fx%22%3A97%2C%22fy%22%3A-26%7D%2C%220x37BC1d287251978C968d64290Cb94B681bE7e57f%22%3A%7B%22fx%22%3A28%2C%22fy%22%3A31%7D%2C%22anhtun01965484%22%3A%7B%22fx%22%3A70%2C%22fy%22%3A-19%7D%2C%22bqngvv%22%3A%7B%22fx%22%3A87%2C%22fy%22%3A-12%7D%2C%22dangnhuuyen1%22%3A%7B%22fx%22%3A-116%2C%22fy%22%3A13%7D%2C%220x69187183E33161eC98f77F9154feb61DE56fB53A%22%3A%7B%22fx%22%3A-59%2C%22fy%22%3A20%7D%2C%220x7A0Ea4Aeb66411F76d0D8298BC074e45eBDFE15D%22%3A%7B%22fx%22%3A49%2C%22fy%22%3A49%7D%2C%22egrabens1%22%3A%7B%22fx%22%3A42%2C%22fy%22%3A-48%7D%2C%22motbang1%22%3A%7B%22fx%22%3A42%2C%22fy%22%3A-28%7D%2C%220x12c162D1a60B518feE11686044210FfFc14B71d4%22%3A%7B%22fx%22%3A19%2C%22fy%22%3A-45%7D%2C%22195zinh%22%3A%7B%22fx%22%3A-2%2C%22fy%22%3A-33%7D%2C%22jacky01548810%22%3A%7B%22fx%22%3A23%2C%22fy%22%3A-18%7D%2C%220x93A3869aE9Abf012A3301EDF8ADd89c4c6cc6285%22%3A%7B%22fx%22%3A-68%2C%22fy%22%3A-20%7D%2C%220x27092FF6a7Be233F12e68592B4374677175572A2%22%3A%7B%22fx%22%3A-34%2C%22fy%22%3A55%7D%2C%220x70e4FBcE45615cEB161d5F06e1815D27bec5F47a%22%3A%7B%22fx%22%3A53%2C%22fy%22%3A17%7D%2C%220xF0B11e644F1b40AeA32a3F078C0603751e54e49c%22%3A%7B%22fx%22%3A36%2C%22fy%22%3A-3%7D%2C%22lemai23397379%22%3A%7B%22fx%22%3A-47%2C%22fy%22%3A-28%7D%2C%22muaprofoto%22%3A%7B%22fx%22%3A-40%2C%22fy%22%3A10%7D%2C%220x2eD3F43F52afEf1Cf5235d71052779e45B9dA70c%22%3A%7B%22fx%22%3A-16%2C%22fy%22%3A27%7D%2C%220x03f528fb4F141660e28Ad57a0fE575bf74a2f3d8%22%3A%7B%22fx%22%3A-22%2C%22fy%22%3A3%7D%2C%220x560FBE5649e78fF8987519F12cD917d436f32Df6%22%3A%7B%22fx%22%3A-25%2C%22fy%22%3A-12%7D%7D&sortDir=desc&sortKey=time&usdGte=0.1

pour gagner du temps je peux deja eliminer les 6 address ayant des liens evident d'utilisation par la meme personne, grace au graphique arkham: 

```
0xbc8744370bcb6d5abf5de8b4086ecfbb4c5629c3
0x27092ff6a7be233f12e68592b4374677175572a2
0x03f528fb4f141660e28ad57a0fe575bf74a2f3d8
0x2ed3f43f52afef1cf5235d71052779e45b9da70c
0x560fbe5649e78ff8987519f12cd917d436f32df6
0x9f89fa91440dd9084182d22ce044d46695ec5536
```

![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/be6984a9-7c38-452b-9304-6c482c8dae9e)


Pour la suite de l'analyse, j'utillise debank et layerzeroscan pour trouver des pattern commun. 


## CLUSTER 2
