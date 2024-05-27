This report consolidates 35 clusters of addresses into a single document for practicality. 

Each cluster is independent, with detailed arguments provided as to why each qualifies as a Sybil cluster potentially detrimental to the Layer Zero project. 
This report format is inspired by the one shared by Bryan on Twitter on May 24, though the **clusters are solely derived from my personal research**. 

As a French speaker not fully fluent in English, this report has been translated using ChatGPT-4; apologies for any syntactic imprecisions.

# Detailed Methodology

**All my clusters are independent**   
(because the argumentation is done manually and independently).


To identify these clusters, I capitalized on a common mistake among Sybil schemes: using the same deposit address on a centralized exchange (CEX). 

I employed SQL queries on Dune Analytics to create a custom dashboard, which helped me find multiple addresses interacting with the same CEX deposit address. I refined my searches to discover wallets interacting with the initially identified addresses, broadening my clusters to include at least 20 wallets for relevance. 

I also used a **graph algorithm** to find all these addresses, which is why I occasionally use terms like gen0, gen1, gen2. Gen0 refers to the addresses with the same CEX deposit, gen1 includes addresses that interacted with gen1, gen2, and so on.

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
23. [Cluster 23](#cluster-23)
24. [Cluster 24](#cluster-24)
25. [Cluster 25](#cluster-25)
26. [Cluster 26](#cluster-26)
27. [Cluster 27](#cluster-27)
28. [Cluster 28](#cluster-28)
29. [Cluster 29](#cluster-29)
30. [Cluster 30](#cluster-30)
31. [Cluster 31](#cluster-31)
32. [Cluster 32](#cluster-32)
33. [Cluster 33](#cluster-33)
34. [Cluster 34](#cluster-34)
35. [Cluster 35](#cluster-35)

</details>

As the cluster are independant and a description comes with every cluster, the two following sections have been regrouped.

This following section is an rotation of the list of the addresses of the cluster and its description: the CEX deposit address some of the addresses share, an Arkham diagram & the second layer of detection.

# Reported Addresses & Description







## CLUSTER 1

20 first address linked to CEX deposit (Binance)
0x7843B8A057676ee7E57df1Fa8aABfabFa32F1d1A

```
0xc4d0ee5b642d3b429c58cc4d10bdcd92312ac180
0x882668c887286d3dd0eb894a78eb92798484978d
0xeed8403b6513c80bfcedeb8b616796e4b91d1a0b
0xffed310be751fc94780f12884a641a507122cf0e
0x04c17d923fd9f18f2399e9589ab80ab62f85b407
0x81077dea57decabfbbeb8648adca22d42d106c8c
0x3b0f2700b69a59dc6d1a9eb0c0cf86c5530a0d62
0xb2ddb1f4c1404b9e35ba5c3012119bc0aa4d687e
0x41953a807a5a1dcd1f171f443af72381fbcc89eb
0xdef2262aa7c28dea9aeaf43603ac2b6913e19dee
0x87a670ea67703d1268d93634eac67cb8549627a6
0x1bfd59fbc137d6d98416679d0d59ed9f0c2438d6
0x60948b99d47b5d6ae1201252ccf5208990bb55a5
0xc7358117caf4d922b05bd9892999da40b1db0356
0x5631326134b98eac44613eb469e94d27bad0fcd5
0x2eeab694b866120fee008620d92e4474de17d418
0x3f3cd2a6086c033aa5e39b12243d21c8c210bd72
0x65d07d0f836a976acfd7847235aef3259255eb1c
0x388b1782c280b4055318608e1333c5608f382c93
0x4998b45f0ceebe955ddce8afdab9233894569559
0xe0d43ed0ea6e8edd4aeb500aa922ab2e11c82807
0x259152761eafd5c2521feb3c605105548c2088c0
0x4ddd8828f1c801bbc87061ba9a5cdd5b94c88938
0x7851d53222a1e85791fdffc96988177cb5108a30
0xdafb27190fec1f2e11b28c7b7239cef2a580e24b
0xe4447ead4001addd3e7e4c27e70a936b7df68bc1
0xb0240794108fd89c99bb828c9ebc0e7d9703c2f8
```

<details>
  
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839750/bnsmi4chqgdgpgq2upqb.png)


https://platform.arkhamintelligence.com/visualizer/entity/0xc4D0EE5b642D3B429C58CC4D10BDCd92312ac180,0x882668c887286d3dD0EB894A78Eb92798484978d,0xEeD8403B6513c80Bfcedeb8b616796e4b91D1a0b,0xFFEd310bE751FC94780f12884a641a507122cF0E,0x04c17D923Fd9f18f2399E9589aB80Ab62f85B407,0x81077DEA57DecabFBbEB8648aDca22d42D106C8c,0x3B0F2700B69a59DC6D1a9Eb0C0Cf86C5530a0D62,0xB2DdB1F4c1404B9e35ba5c3012119bC0AA4D687E,0x41953a807a5a1dcd1f171f443aF72381fBcC89EB,0xdeF2262AA7c28DEa9aeaF43603Ac2b6913e19deE,0x87a670EA67703D1268d93634EAc67cb8549627a6,0x1bFd59FbC137D6D98416679d0D59eD9f0c2438d6,0x60948B99D47B5d6ae1201252ccf5208990bB55a5,0xc7358117CAf4D922b05bD9892999DA40b1db0356,0x5631326134b98EAc44613Eb469E94d27Bad0FCd5,0x2EeAb694B866120FEe008620D92e4474de17d418,0x3f3cd2A6086c033aa5E39B12243D21C8C210BD72,0x65d07D0F836A976aCfD7847235AEf3259255EB1c,0x388b1782C280b4055318608E1333c5608f382C93,0x4998B45F0cEEbe955dDcE8afdab9233894569559,0xe0D43ED0EA6e8EDD4aeB500Aa922Ab2E11C82807,0x259152761Eafd5c2521FEb3c605105548C2088c0,0x4ddd8828f1C801BBc87061Ba9A5cdd5B94C88938,0x7851D53222a1E85791fDffc96988177Cb5108a30,0xDAFB27190fEC1F2e11B28c7B7239CeF2a580e24B,0xe4447EAd4001adDd3E7E4C27E70a936B7dF68BC1,0xb0240794108Fd89C99BB828C9eBc0e7d9703C2f8?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

Same tx Holograph, same source chain, same date
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/4dfa5b36-d39a-494b-a12c-bd908056c625)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/d62aac6d-203f-481c-8c26-1b1dad6fab03)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/64b51a55-c3e9-40b3-9fa6-cc28c943b040)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/16e0ea0c-5b9d-4e02-b9ef-679a0d443b42)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/80425c30-d7b5-45ea-be07-18a8bb28193b)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/008ea548-2c81-4010-8428-2bb011a1c305)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/b74ab313-cef6-48ec-8bfd-9b491385bba5)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/e6df22e3-110f-4624-a75b-d3e8b59fb409)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/2faab866-a7fe-4d54-82cc-96f7042682ea)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/faa240b1-c390-4fec-a4ea-5bcf9dea6d2e)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/bf696d12-d1f2-4d60-bfe0-34c65569d795)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/0bed603c-5a34-4bf8-a0a5-27231bf28ee8)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/88b5c5bc-2998-4f37-95b0-3cc72a190dfa)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/d5363f41-4e9b-478d-b94a-43c7c597c997)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/d91031e6-b3f8-49dd-8525-f01955d64da9)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/e5bea084-94a1-475f-8be8-590891d45a5f)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/49aa0db1-26b6-4eab-a954-446e30afa148)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/c85c60a2-fa45-41f8-ab8f-f7bf05981b62)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/6c0e8357-373d-4430-b5eb-d9332c3cb30b)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/9a298565-3adb-4e72-9d99-8f58b3be2796)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/018a4be1-c5ae-4926-99b8-376af7a556f3)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/c36c6cae-fe73-4649-85c3-922506cc2742)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/333b4009-7edc-4a83-b886-240b5a819077)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/cb001db9-af32-4a5e-a20c-62b90b5b241c)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/f06c7250-f2a2-4cad-9fb2-d147cec3f052)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/ec5f8338-1055-499d-a39a-8d3ef920c92c)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/a1e5e7cd-a550-4536-8d63-0c06128630d7)



```
polygonzkevm 1 0xc4d0ee5b642d3b429c58cc4d10bdcd92312ac180 2023-06-27 2023-06-26
2 0x882668c887286d3dd0eb894a78eb92798484978d 2023-06-27 2023-06-26
3 0xeed8403b6513c80bfcedeb8b616796e4b91d1a0b 2023-06-27 2023-06-26
4 0xffed310be751fc94780f12884a641a507122cf0e 2023-06-27 2023-06-26 2023-06-26 2023-06-26
5 0x04c17d923fd9f18f2399e9589ab80ab62f85b407 2023-06-26 2023-06-26 2023-06-26
6 0x81077dea57decabfbbeb8648adca22d42d106c8c 2023-06-27 2023-06-26 2023-06-26
7 0x3b0f2700b69a59dc6d1a9eb0c0cf86c5530a0d62 2024-04-16 2023-06-27 2023-06-26 2023-06-26
8 0xb2ddb1f4c1404b9e35ba5c3012119bc0aa4d687e 2023-06-27 2023-06-26 2023-06-26
10 0xdef2262aa7c28dea9aeaf43603ac2b6913e19dee 2023-06-27 2023-06-26 2023-06-26
11 0x87a670ea67703d1268d93634eac67cb8549627a6 2023-06-27 2023-06-26 2023-06-26
12 0x1bfd59fbc137d6d98416679d0d59ed9f0c2438d6 2023-06-27 2023-06-26 2023-06-26
13 0x60948b99d47b5d6ae1201252ccf5208990bb55a5 2023-06-27 2023-06-26
14 0xc7358117caf4d922b05bd9892999da40b1db0356 2023-06-27 2023-06-26
15 0x5631326134b98eac44613eb469e94d27bad0fcd5 2023-06-27 2023-06-26
16 0x2eeab694b866120fee008620d92e4474de17d418 2023-06-27 2023-06-26
20 0x4998b45f0ceebe955ddce8afdab9233894569559 2023-06-27 2023-06-26 2023-06-26
21 0xe0d43ed0ea6e8edd4aeb500aa922ab2e11c82807 2023-06-27 2023-06-26
22 0x259152761eafd5c2521feb3c605105548c2088c0 2023-06-27 2023-06-26
25 0xdafb27190fec1f2e11b28c7b7239cef2a580e24b 2023-06-27 2023-06-26
26 0xe4447ead4001addd3e7e4c27e70a936b7df68bc1 2023-06-27 2023-06-26
```

</details>

## CLUSTER 2

ALL address linked to Binance deposit 
0x7032B3Da4ae9Affea76B2453d2420A93A6F29561

**TLDR**
same binance deposit address
native arbitrum nova bridge date
native starknet bridge date
polygon STG lock date


```
0x3019e7df6cfc75ccb90452e90454712ba1659bf9
0xe1df003d4a8b5059a64733e503258690e6cd3cad
0xda550016c984001c8b0e1319140ebe520a1f9b5c
0x60dcf46d6ae3ac642d04d19f219a758c1ca44f66
0x9f030d219f24acfeea312aa87c79a2c02ea59065
0xe362fcff4d298d134f107dc65feb61a197e24f5b
0x5c5a84f90b153c7cf95c1dcb695602dd1a7713fc
0x4a85e68ed0bd9316025fa7b57057ae4f10f000a0
0x1e408f8cb597a2ab50fc1445e53f3fcf3a113d79
0xb50f657ee68df2a4695d6f3c6ae0077463b12edc
0x389b5ca886bb3f5db3b6907b7bb54e7edb83c557
0x51263874865b2aa327e5afbbbc9619a3a1e21353
0xe15f9d9b3ba32758e28b2ab059ce4a49a4b1c98a
0x0866413c57281268edaf85a325fa2be9fb641b22
0x9970a2c648362f8f0469773ed58687090f95d646
0xbc87182ea77d7a4587ad8ecaef7301dd14916565
0xc593bcb105e9afb4c20ba057fdfb95b58afc8e3c
0xfc84100fae97319a47519b221853e1b9bc7eb634
0x2e83c6833c171939d0bb3653defce00fc76c8ed2
0xa04bf9cd9ef858f7c6d9c36539c3478634b27022
```

<details>
  
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839751/xjfuu1q3ypb5k3vtiups.png)
https://platform.arkhamintelligence.com/visualizer/entity/0x7032B3Da4ae9Affea76B2453d2420A93A6F29561,0x3019E7Df6CFc75cCB90452e90454712BA1659bF9,0xe1dF003d4a8b5059A64733e503258690E6cD3cAd,0xda550016C984001c8b0E1319140ebE520a1f9b5c,0x60DcF46d6aE3ac642D04D19F219A758C1CA44F66,0x9f030d219F24aCfeEa312AA87c79A2C02ea59065,0xE362fCff4d298D134F107dC65FEB61A197e24f5B,0x5C5A84f90B153c7cf95C1dcB695602Dd1A7713Fc,0x4A85E68ED0bD9316025Fa7b57057aE4f10F000a0,0x1e408f8cB597a2ab50FC1445E53f3fCf3A113D79,0xB50f657eE68dF2a4695d6f3C6Ae0077463b12eDc,0x389B5Ca886bb3f5db3B6907B7bb54e7eDb83c557,0x51263874865B2Aa327e5AfBbbc9619A3A1e21353,0xe15f9d9b3bA32758e28b2ab059Ce4a49a4B1C98a,0x0866413C57281268EdAf85a325Fa2Be9FB641B22,0x9970A2C648362f8f0469773ed58687090F95D646,0xbC87182eA77d7A4587Ad8ECAeF7301DD14916565,0xC593BcB105E9afb4C20Ba057fdFb95b58AFC8e3c,0xfC84100FAe97319A47519B221853E1B9Bc7EB634,0x2E83c6833c171939D0Bb3653dEfCe00FC76c8eD2,0xa04bF9CD9ef858F7C6d9C36539c3478634b27022?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

Very similar layer zero days !
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839753/rwz6scjqlvqjhenr9ldf.png)


ARBITRUM NOVE NATIVE BRIDGE 
```
1 0x3019e7df6cfc75ccb90452e90454712ba1659bf9 2023-03-25 
2 0xe1df003d4a8b5059a64733e503258690e6cd3cad 2023-03-24 
3 0xda550016c984001c8b0e1319140ebe520a1f9b5c 2023-03-25 
4 0x60dcf46d6ae3ac642d04d19f219a758c1ca44f66 2023-03-25 
5 0x9f030d219f24acfeea312aa87c79a2c02ea59065 2023-03-25 
6 0xe362fcff4d298d134f107dc65feb61a197e24f5b 2023-03-25 
7 0x5c5a84f90b153c7cf95c1dcb695602dd1a7713fc 2023-03-25 
8 0x4a85e68ed0bd9316025fa7b57057ae4f10f000a0 2023-03-25 
9 0x1e408f8cb597a2ab50fc1445e53f3fcf3a113d79 2023-03-25 
10 0xb50f657ee68df2a4695d6f3c6ae0077463b12edc 2023-03-25 
11 0x389b5ca886bb3f5db3b6907b7bb54e7edb83c557 2023-03-25 
12 0x51263874865b2aa327e5afbbbc9619a3a1e21353 2023-03-25 
13 0xe15f9d9b3ba32758e28b2ab059ce4a49a4b1c98a 2023-03-25 
14 0x0866413c57281268edaf85a325fa2be9fb641b22 2023-03-25 
15 0x9970a2c648362f8f0469773ed58687090f95d646 2023-03-25 
16 0xbc87182ea77d7a4587ad8ecaef7301dd14916565 2023-03-25 
17 0xc593bcb105e9afb4c20ba057fdfb95b58afc8e3c 2023-03-25 
18 0xfc84100fae97319a47519b221853e1b9bc7eb634 2023-03-25 
19 0x2e83c6833c171939d0bb3653defce00fc76c8ed2 2023-03-25 
20 0xa04bf9cd9ef858f7c6d9c36539c3478634b27022 2023-03-25 
```


POLYGON STG lock date 
```
1 0x3019e7df6cfc75ccb90452e90454712ba1659bf9 2022-11-09   
2 0xe1df003d4a8b5059a64733e503258690e6cd3cad 2022-11-08   
3 0xda550016c984001c8b0e1319140ebe520a1f9b5c 2022-11-08   
4 0x60dcf46d6ae3ac642d04d19f219a758c1ca44f66 2022-11-08   
5 0x9f030d219f24acfeea312aa87c79a2c02ea59065 2022-11-08   
6 0xe362fcff4d298d134f107dc65feb61a197e24f5b 2022-11-08   
7 0x5c5a84f90b153c7cf95c1dcb695602dd1a7713fc 2022-11-08   
8 0x4a85e68ed0bd9316025fa7b57057ae4f10f000a0 2022-11-09   
9 0x1e408f8cb597a2ab50fc1445e53f3fcf3a113d79 2022-11-09   
10 0xb50f657ee68df2a4695d6f3c6ae0077463b12edc 2022-11-09   
11 0x389b5ca886bb3f5db3b6907b7bb54e7edb83c557 2022-11-09   
12 0x51263874865b2aa327e5afbbbc9619a3a1e21353 2022-11-08   
13 0xe15f9d9b3ba32758e28b2ab059ce4a49a4b1c98a 2022-11-08   
14 0x0866413c57281268edaf85a325fa2be9fb641b22 2022-11-09   
15 0x9970a2c648362f8f0469773ed58687090f95d646 2022-11-09   
16 0xbc87182ea77d7a4587ad8ecaef7301dd14916565 2022-11-09   
17 0xc593bcb105e9afb4c20ba057fdfb95b58afc8e3c 2022-11-09   
18 0xfc84100fae97319a47519b221853e1b9bc7eb634 2022-11-09   
19 0x2e83c6833c171939d0bb3653defce00fc76c8ed2 2022-11-08   
20 0xa04bf9cd9ef858f7c6d9c36539c3478634b27022 2022-11-08

```

STARKNET NATIVE BRIDGE
```
1 0x3019e7df6cfc75ccb90452e90454712ba1659bf9 2023-04-13 2023-04-12 2023-04-11 2023-03-26 
2 0xe1df003d4a8b5059a64733e503258690e6cd3cad 2023-04-12 2023-04-11 2023-04-11 2023-03-25 2023-02-16 2023-02-07 
3 0xda550016c984001c8b0e1319140ebe520a1f9b5c 2023-04-11 2023-03-26 
4 0x60dcf46d6ae3ac642d04d19f219a758c1ca44f66 2023-04-11 2023-03-26 
6 0xe362fcff4d298d134f107dc65feb61a197e24f5b 2023-04-11 2023-03-26 
7 0x5c5a84f90b153c7cf95c1dcb695602dd1a7713fc 2023-04-11 2023-03-26 
8 0x4a85e68ed0bd9316025fa7b57057ae4f10f000a0 2023-04-11 2023-03-26 
9 0x1e408f8cb597a2ab50fc1445e53f3fcf3a113d79 2023-04-11 2023-03-26 
10 0xb50f657ee68df2a4695d6f3c6ae0077463b12edc 2023-04-11 2023-03-26 
11 0x389b5ca886bb3f5db3b6907b7bb54e7edb83c557 2023-04-11 2023-03-26 
12 0x51263874865b2aa327e5afbbbc9619a3a1e21353 2023-04-11 2023-03-26 
13 0xe15f9d9b3ba32758e28b2ab059ce4a49a4b1c98a 2023-04-11 2023-03-26 
14 0x0866413c57281268edaf85a325fa2be9fb641b22 2023-04-11 2023-03-26 
15 0x9970a2c648362f8f0469773ed58687090f95d646 2023-04-11 2023-03-26 
16 0xbc87182ea77d7a4587ad8ecaef7301dd14916565 2023-04-11 2023-03-26 
17 0xc593bcb105e9afb4c20ba057fdfb95b58afc8e3c 2023-04-11 2023-03-26 
18 0xfc84100fae97319a47519b221853e1b9bc7eb634 2023-04-11 2023-03-26 
19 0x2e83c6833c171939d0bb3653defce00fc76c8ed2 2023-04-11 2023-03-26 
20 0xa04bf9cd9ef858f7c6d9c36539c3478634b27022 2023-04-11 2023-03-26 
```


</details>


## CLUSTER 3

The first 10 addresses of the cluster share the same Binance deposit address 0x10167822FaaBE05D5506d60CE73C340adaC2d8e3. 
The rest are linked to numerous addresses of the cluster, multiple times.


**TLDR**

Stagate bridge with same amount of STG, same day, same binance deposit address, same lzd
All the wallets in this cluster that locked STG did so on the same day.

```
0x29e6c5d260e4b800e5a2226afbfca66568310da7
0x80019ceb167ef8e1d3d991fc42739e4c06e587d6
0x08c144c7da146189a4097e771e54512c5ff9d145
0xb43e0b414d156570d9123bf5286d15ed2e22fa72
0x392cb58fb7d6c27943d16ddd68d943dfb2695da9
0x92c814b4bba46af24d887aa0e34e63b7b381ba03
0xcdaa39e7bcc311de7970e6fc8bba92cef0b8c4e1
0x5ace6f229552901c69c914529f0d99ec757c265d
0x604040c5a2b04008d97739482906d40214f7ca3b
0xcddd83a4ce477bc8d81aeed33539b0338273a4fc
0x4d60c23d86dc8da36c8d739e0db921f15553b6f7
0x71954e31c0a79aaac6c9cde641691ee6a5c3d936
0xa1da0e1100e88aa6c4f5555cfa5ac24d5ff4088d
0xaf08d3360369ca473d2dbd1e2dc4f69296bb0e5b
0x0aca8c735159fea6705080d80a1959622f647a59
0x30c795f8ab70fbeb2b1e79ac88cccaf2966cd058
0xe4125a0edfb48070b60d33368fae03b40ac4f0ea
0xdc7a3734d9cf7efecc0d53a4854be2a4e00cf81f
0xb22223f2f433700d095797facd6a7212d6779675
0xbeb616971159c12971df15cfc195b11a0cca30d7
0xc2e5b466e3a0b116ad1f8f62cd3903d5cb314c78
0xcfd426deb6f9f1e4e959aa7c28b42d546cded891
0x41261fb9e642318994528e8a902c3582b50d9034
0x1e0740315d6014c9bbc4423b09c8fb5aac39d8d7
0x0aada189cbb5743f9e6123464ee7c1553818796e
0x5c357023e4b0afb0224ac6159e4df0eb672ec355
0x9434cf7b244958dc6cbaf9fb46173caba8d2595f
0xde52e9ab7282c060e763db278fcc0a3ff839cfdb
0x404844c9af8617760227a311617ebf79203523af
0x2b98345ac86b4f6fe57956f2d69e83b6f7c063cd
0x16589a27ed90d732d0cafae0ed71d404c06df4aa
0x7e6fc028bf7c9ca7a2ebe72b40e43f1464aa5e66
```

<details>
  

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839755/tepieusxfeuxnfkuqgtt.png)


https://platform.arkhamintelligence.com/visualizer/entity/0x29e6c5D260e4b800e5A2226aFbFca66568310dA7,0x80019ceB167ef8e1d3d991FC42739E4c06E587d6,0x08C144C7dA146189A4097e771E54512C5FF9d145,0xb43E0b414D156570d9123bF5286D15eD2E22FA72,0x392cB58Fb7D6C27943d16ddD68d943DFB2695dA9,0x92C814b4BBA46aF24D887AA0E34e63B7B381ba03,0xcDAA39e7bcc311De7970E6Fc8BBA92CeF0b8c4e1,0x5acE6F229552901C69C914529f0d99ec757C265D,0x604040c5a2B04008d97739482906D40214F7Ca3b,0xCddD83a4cE477bC8d81aEED33539b0338273a4fC,0x4d60C23D86dc8DA36C8D739e0db921f15553b6F7,0x71954E31c0A79aAaC6C9cDE641691EE6A5c3D936,0xa1da0e1100E88AA6c4f5555CFa5aC24d5FF4088d,0xAf08d3360369Ca473d2DBD1E2dc4F69296bb0E5B,0x0aCa8C735159FEA6705080d80A1959622F647A59,0x30c795f8AB70FbeB2B1e79aC88Cccaf2966CD058,0xE4125A0EdFb48070B60D33368fAe03B40aC4f0Ea,0xdc7A3734D9CF7efEcC0d53A4854be2A4e00Cf81F,0xb22223f2f433700D095797facD6A7212D6779675,0xBEB616971159c12971Df15Cfc195B11A0cca30D7,0xC2e5b466e3a0b116ad1F8F62cd3903D5cb314C78,0xcfd426dEb6F9F1e4e959AA7C28B42D546CdeD891,0x41261fb9E642318994528e8a902C3582b50D9034,0x1e0740315D6014C9bBc4423b09C8fB5aaC39d8d7,0x0Aada189CBb5743F9E6123464EE7C1553818796e,0x5C357023e4B0AFb0224aC6159e4Df0Eb672EC355,0x9434Cf7b244958dC6Cbaf9fB46173CAbA8d2595f,0xDE52e9Ab7282c060E763Db278fCc0a3Ff839CfdB,0x404844C9af8617760227A311617ebF79203523aF,0x2B98345Ac86b4F6fe57956F2D69e83B6F7C063cd,0x16589a27Ed90d732d0CaFAE0eD71D404c06DF4AA,0x7e6fC028Bf7c9Ca7a2eBe72b40e43f1464Aa5E66?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

Regarding on-chain:
- same layerzero days
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839757/w2terko4lhmsmdzeypym.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839758/ulaxqb00nbo0ebdzpdk9.png)


- Sending USDT to several wallets from our list.
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839760/zytbqxaynmdvvwq9prqt.png)

Same pattern on Stargate with STG tokens, all on October 4th 2023, about 5000 STG each time, then deposited to Binance. A few DeBank images to illustrate my point. The execution date does not leave room for coincidence, especially since the Binance deposit addresses are similar.

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839762/qj7ytxlr1fstij0w2btu.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839764/lh5puq6ukmwixikhxbsd.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839766/l9rmcofzv7vjuuawwdzm.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839768/tblswio7xgciulzhdnbr.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839770/dhp1cftynlf1hgcxa2pp.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839772/jfobdl3e8lkqppodurm3.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839773/fumohdhtjywfamxqfwcr.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839775/lykdmrgeqshnz95hrfyk.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839777/azig9y6cj458a88md6p8.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839779/ecrlofnynbjwu75im6yc.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839780/e4qrmqiqsgpybdd0nvbp.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839782/kcb9zwckpyeb9lkmebiq.png)

ETC ETC

Similar pattern observed on the transactions seen on LayerZeroScan.
Testnet bridge same days.

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839784/zf7gucjtsjbr9i0klnao.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839785/riqza7etkmxawlg1pwyj.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839787/owk0a5ysxuvxsq9hgcrs.png)

LOCK STG DATE: 
All the wallets in this cluster that locked STG did so on the same day.

1eme 2024-04-17   2024-03-19   2024-02-23   2024-01-26   2023-03-18   2022-10-20   2022-10-13   2022-10-06   2022-10-03   2022-10-03   2022-09-20   
2eme 2024-04-17   2024-03-19   2023-02-16   
3eme 2024-04-17   2024-03-19   
4eme 2024-04-17   2024-03-19   
5eme 2024-04-17   2024-03-19   
6eme 2024-04-17   2024-03-19   2024-03-19   2023-02-16   
7eme 2024-04-17   2024-03-19   
8eme 2024-04-17   
11eme 2024-04-17   
12eme 2024-04-17   
13eme 2024-04-17   
14eme 2024-04-17   
15eme 2024-04-17   
16eme 2024-04-17   
17eme 2024-04-17   
18eme 2024-04-17   
20eme 2024-04-17   
21eme 2024-04-17   
25eme 2024-04-17   
27eme 2024-04-17   
28eme 2024-04-17   
29eme 2024-04-17   2024-03-19   
30eme 2024-04-17   2024-03-19   
31eme 2024-04-17   2024-03-19   2023-02-16   
32eme 2024-04-17   2024-03-19   


ZKSYNC BRIDGE 

2eme 2024-04-17  
3eme 2024-04-17   
14eme 2024-04-17    
28eme 2024-04-17   
29eme 2024-04-17    
30eme 2024-04-17 2024-04-17    
31eme 2024-04-17    


ARBITRUM BRIDGE

1eme 2022-11-18            
2eme 2023-02-17 2023-02-17     
3eme 2023-02-17   
4eme 2023-02-17            
5eme 2023-02-17         
6eme 2023-02-17     
7eme 2023-02-17      
29eme 2023-02-17 2023-02-17   
30eme 2023-02-17 2023-02-17     
31eme 2023-02-17 2023-02-17   
32eme 2023-02-17     

  
</details>

## Cluster 4

The first 12 addresses of the cluster share the same ByBit deposit address 0x5820CAf64483A7cB29Ba3Ef93f9AB34b6a54bFcD. 


**TLDR**
Same Bybit deposit address.
Same strategy to rank higher on the Layer Zero Dune leaderboard (Stargate wash trading).
STG was locked on the BSC on the same dates
Same goes for ZKSYNC native bridge


```
0x420c769af76ae6a065808f1a67c9f53bbd98a455
0x4f020ec2b43bdad10e30e885c99c0cdea134af77
0xaf591924ba8261aacf87dc444806177f99ab0d8b
0x7f1ea099d396d76f41c22a4159a0d4931f1afc4c
0x9adb99789a7d2fd9c6506d12e92a7a3f715dee07
0x9ef07caa3517273ae4bded736d3678a447eb7f3e
0x7303c823d2c992302c8cc7596900d8f80879aacb
0xeb04d45667f9f555bb868fe83759c2b57e4c7716
0xe7bd4088b944b644fca7afe7c84a1ed71f3f3109
0x0c6fed6b745727c906d4b50a906dced536df9f64
0x94a76e7b7a503e0342755b223b6321bb03fed1c1
0x29faf75ad1bfe4ff545b64a57a76881f0ff42ccb
0x8ec9e390c846ca749535f9fbd4bbd67c39957f04
0xc8729f0853e25bc694e1f55901ee620058191fd0
0xad14f125f22ffac70432f28587aafdb8d83e34a7
0xb061032dfc753bf123b8bb2c3a48cf2a39bd9bb9
0x3432fa91b8c8d7d5a627fad339f4f174b83192b6
0x726b8631e87459e6ab53a4102eec714cebe24ee9
0xa337198f4eede41257980d8f2e3ed3d5c7084306
0x618e4f464b143bcc3b10f252d02bba0411d34d76
0x9981316e8fcd782f7d956b5b1bed861ec2f9e477
0x77d47537212dfc5b920f784fd2dba5978c1f2565
0x9ae2fb2c0385a28959a2cd400be47d4337dff28c
0x6f6f2b5afc9021a4baaab518f632a5f8438a9f49
```


<details>


![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839789/tmd7ai5vknof64za1tqx.png)

https://platform.arkhamintelligence.com/visualizer/entity/0x5820CAf64483A7cB29Ba3Ef93f9AB34b6a54bFcD,0x420c769Af76AE6A065808F1a67c9F53BbD98A455,0x4f020Ec2b43BDaD10e30e885C99c0CdEA134aF77,0xaF591924Ba8261AAcF87DC444806177f99Ab0D8B,0x7f1Ea099d396D76F41C22a4159A0D4931F1afC4C,0x9adb99789a7D2Fd9c6506d12e92A7A3f715DeE07,0x9eF07CAa3517273AE4bded736d3678a447EB7F3e,0x7303C823d2c992302C8cC7596900d8f80879aACb,0xEB04D45667F9F555bb868FE83759C2B57E4c7716,0xe7BD4088B944b644fCA7AFe7C84A1ED71f3f3109,0x0c6feD6b745727C906D4B50a906dceD536dF9f64,0x94a76e7B7A503E0342755b223b6321bb03FEd1C1,0x29faf75Ad1Bfe4fF545B64a57a76881F0fF42ccb,0x8Ec9E390C846ca749535F9fBd4Bbd67C39957F04,0xc8729f0853E25bC694e1F55901Ee620058191fD0,0xAd14f125F22fFAc70432f28587AAfDb8D83E34a7,0xB061032dfc753Bf123B8bB2C3A48CF2a39bd9Bb9,0x3432FA91B8C8D7D5a627fAD339F4f174B83192b6,0x726B8631e87459e6aB53a4102eeC714cebE24eE9,0xA337198F4EEdE41257980d8f2e3eD3d5C7084306,0x618e4f464B143Bcc3B10f252D02bBA0411D34D76,0x9981316e8FcD782F7D956b5b1BeD861Ec2F9e477,0x77D47537212dfc5b920F784FD2dbA5978C1f2565,0x9AE2Fb2c0385A28959A2Cd400bE47d4337dff28C,0x6F6F2b5aFc9021A4baaab518f632a5f8438a9F49?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

We can clearly see the link between the different addresses on the Arkham graph. Now, I will delve deeper with on-chain arguments.

On-chain analysis:

Firstly, we see that many wallets have a similar start of on-chain activity for Layer Zero, as shown on Dune:
addresses with activity starting on the same day within a very short time interval.

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839791/utqdco51uzbmtuj9ysja.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839792/kr0y0wt0cr3ayepyrwxv.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839794/ny9q3dhfvhoeywul45yu.png)

Next, we'll delve deeper by examining the pattern of Layer Zero messages across the different addresses in the cluster:
We notice that our prospect primarily used Stargate in their Layer Zero farming, engaging in volume farming across all their wallets, which is commonly used to gain numerous rankings in the Layer Zero dune ranking.
Here are a few examples:

0x9adb99789a7d2fd9c6506d12e92a7a3f715dee07
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839795/rm5lmjwcpkxcvenm7u7y.png)

0x7f1ea099d396d76f41c22a4159a0d4931f1afc4c
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839797/kzofhmqqxglby0hxkutj.png)

0xaf591924ba8261aacf87dc444806177f99ab0d8b
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839798/jqtxvgu2rlb9hrvenuqv.png)

0x4f020ec2b43bdad10e30e885c99c0cdea134af77
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839800/vypzfd8lfwiq8ajjbpcb.png)

0x420c769af76ae6a065808f1a67c9f53bbd98a455
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839802/m6y09g7qiwcy9k5lbgiu.png)

0x9ef07caa3517273ae4bded736d3678a447eb7f3e
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839803/mqlyozvsdp0wlbej85qz.png)

This is the case for all the addresses in this cluster.

ETC ETC 


LOCK STG ON BSC 
We notice that STG was locked on the BSC on the same dates, which clears up many doubts about this cluster.

1 0x420c769af76ae6a065808f1a67c9f53bbd98a455 2023-12-16   2023-11-08   2023-10-25   2023-06-04      
2 0x4f020ec2b43bdad10e30e885c99c0cdea134af77 2023-12-15   2023-12-15   2023-12-15   2023-11-08   2023-11-07   2023-08-15     
3 0xaf591924ba8261aacf87dc444806177f99ab0d8b 2023-12-16   2023-11-19   2023-11-07   2023-10-30     
4 0x7f1ea099d396d76f41c22a4159a0d4931f1afc4c 2023-12-15   2023-11-08     
5 0x9adb99789a7d2fd9c6506d12e92a7a3f715dee07 2023-12-15   2023-11-18   2023-11-15   2023-11-08   2023-10-31   2023-10-24      
6 0x9ef07caa3517273ae4bded736d3678a447eb7f3e 2023-12-15   2023-11-08   2023-10-26    
7 0x7303c823d2c992302c8cc7596900d8f80879aacb 2023-11-06   2023-11-04   2023-10-11         
8 0xeb04d45667f9f555bb868fe83759c2b57e4c7716 2023-11-06   2023-11-05   2023-10-12         
9 0xe7bd4088b944b644fca7afe7c84a1ed71f3f3109 2023-11-07   2023-11-07   2023-11-06          
10 0x0c6fed6b745727c906d4b50a906dced536df9f64 2023-12-15   2023-11-20   2023-11-19   2023-11-08   2023-10-26      
11 0x94a76e7b7a503e0342755b223b6321bb03fed1c1 2023-12-15   2023-10-30   2023-10-30   2023-10-25       
12 0x29faf75ad1bfe4ff545b64a57a76881f0ff42ccb 2023-12-15   2023-11-18   2023-11-15   2023-11-08   2023-10-30   2023-08-17      
13 0x8ec9e390c846ca749535f9fbd4bbd67c39957f04 2023-12-16   2023-11-19   2023-11-19   2023-11-07   2023-10-30   2023-10-22      
14 0xc8729f0853e25bc694e1f55901ee620058191fd0 2023-11-07   2023-11-06   2023-11-05   2023-11-04   2022-01-04      
15 0xad14f125f22ffac70432f28587aafdb8d83e34a7 2023-12-15   2023-11-08   2023-10-27   2023-08-06      
16 0xb061032dfc753bf123b8bb2c3a48cf2a39bd9bb9 2023-12-15   2023-11-19   2023-11-08   2023-10-27   2023-10-25    
17 0x3432fa91b8c8d7d5a627fad339f4f174b83192b6 2023-12-15   2023-11-18   2023-11-15   2023-11-08   2023-10-30      
18 0x726b8631e87459e6ab53a4102eec714cebe24ee9 2023-12-15   2023-11-19   2023-11-08   2023-11-08   2023-10-26      
19 0xa337198f4eede41257980d8f2e3ed3d5c7084306 2023-12-15   2023-11-08   2023-10-26        
20 0x618e4f464b143bcc3b10f252d02bba0411d34d76 2023-12-15   2023-11-18   2023-11-15   2023-11-08   2023-10-30   2023-08-17   2023-08-17       
21 0x9981316e8fcd782f7d956b5b1bed861ec2f9e477 2023-12-15   2023-11-19   2023-11-07   2023-10-30   2023-10-22   2023-08-17      
22 0x77d47537212dfc5b920f784fd2dba5978c1f2565 2023-12-15   2023-11-19   2023-11-08   2023-10-30   2023-10-23       
23 0x9ae2fb2c0385a28959a2cd400be47d4337dff28c 2023-12-15   2023-11-15   2023-11-08   2023-10-30   2023-08-17        
24 0x6f6f2b5afc9021a4baaab518f632a5f8438a9f49 2023-11-06   2023-11-04   2023-10-17   


ZKSYNC NATIVE BRIDGE 
Same goes for ZKSYNC, no doubt about this cluster.


1 0x420c769af76ae6a065808f1a67c9f53bbd98a455 2024-01-04 2023-06-03    
2 0x4f020ec2b43bdad10e30e885c99c0cdea134af77 2023-06-29         
3 0xaf591924ba8261aacf87dc444806177f99ab0d8b 2023-10-05 2023-09-19 2023-07-30             
4 0x7f1ea099d396d76f41c22a4159a0d4931f1afc4c 2023-08-23               
5 0x9adb99789a7d2fd9c6506d12e92a7a3f715dee07 2023-12-25               
6 0x9ef07caa3517273ae4bded736d3678a447eb7f3e 2023-12-24               
7 0x7303c823d2c992302c8cc7596900d8f80879aacb 2023-12-29             
8 0xeb04d45667f9f555bb868fe83759c2b57e4c7716 2023-12-31              
9 0xe7bd4088b944b644fca7afe7c84a1ed71f3f3109 2023-12-31                    
10 0x0c6fed6b745727c906d4b50a906dced536df9f64 2023-12-24               
11 0x94a76e7b7a503e0342755b223b6321bb03fed1c1 2023-12-25              
12 0x29faf75ad1bfe4ff545b64a57a76881f0ff42ccb 2023-12-25               
13 0x8ec9e390c846ca749535f9fbd4bbd67c39957f04 2023-12-26             
14 0xc8729f0853e25bc694e1f55901ee620058191fd0 2023-12-29 2023-06-09                
15 0xad14f125f22ffac70432f28587aafdb8d83e34a7 2023-12-25 2023-08-24               
16 0xb061032dfc753bf123b8bb2c3a48cf2a39bd9bb9 2023-12-25                         
17 0x3432fa91b8c8d7d5a627fad339f4f174b83192b6 2023-12-25              
18 0x726b8631e87459e6ab53a4102eec714cebe24ee9 2023-12-24                
19 0xa337198f4eede41257980d8f2e3ed3d5c7084306 2023-12-24                     
20 0x618e4f464b143bcc3b10f252d02bba0411d34d76 2023-12-25             
21 0x9981316e8fcd782f7d956b5b1bed861ec2f9e477 2023-12-26 2023-09-24                  
22 0x77d47537212dfc5b920f784fd2dba5978c1f2565 2023-12-26                 
23 0x9ae2fb2c0385a28959a2cd400be47d4337dff28c 2023-12-25                  
24 0x6f6f2b5afc9021a4baaab518f632a5f8438a9f49 2023-12-29               


</details>

## Cluster 5

The first 12  addresses are linked by the same CEX deposit on ByBit:
0x5e8c3a2B1c88D61558DFd4B810150CAe188ec65D
sybil cluster farming multiple airdrops across +20 wallets

**TLDR**
Same date  & amount Linea Renzo Mint on ALL WALLETS
Same ZKSYNC/ZKSYNCLITE/STARKNET native bridge date
Same STG lock date on arbitrum 


```
0x7abd480bdad5ccfe1acc840ce408b1336b747ad3
0xbe6513762d4b65d74322fecbe3aecd0e944a5c1d
0x0316b816ed6addccec0963f730375e6b4991a5d3
0xa93e7678f0b90c0dc454e9a3ef5260e6ed7c12f3
0xa2aa23e428ba5b8abc52c733a1a9635841e737a1
0x7069e41d9e7099fdc4a4270e14acc29003d9df51
0x9547b0c194707ec1ee64ea08975f1201802e9453
0x460314a8d83dc7ce9fa4a61f330d0bb452e1793a
0xfcf5db30d7403a90ab625fa850a5577e944117ea
0x29d5fad4c0f8ecc705ca2ad4bf47610ae88291f1
0x7ff48f78ca1855bad9a3daee8d2c3b29269ebd52
0x10b0d3b4293ab1112ed0c96f37ed9b1d22c1dd53
0x04a0476daedaffc743a8c2d29e5562064b744e7c
0x44b34f5a043357f62f2061f4a4fd6f21dd7bc51f
0xdeb73de3c89189122fe621e8171b65da7fab0613
0x5998de36dbf222a0735a8e3004fd90cdcfd7a4ab
0xa0080a7bc272624355d3104e60c0354502624b38
0x2b699bfa91bd12954f8e1fb5e891c4cdcc3b4071
0xc429db30e778d44143688bed7aa223540aab3429
0x6cb35c0427e0c44b10da4687d5e0a96380a2ca0f
0x019cc201dfd4ce85f83e84a2c6a1294f1e66fa86
0x3a179bf9b4f581696b1eefe6f2bb4ad82ba8a690
0xbc593ec4039e1281449f17da98d0d4e46116ecac
0x48b889640b16d8ee8b575249d99669d5094c3b0e
0x3601362b8df6d2f87c4f0fe329bded64589e467a
0xdeb862a3b982f9278b258c72375ea2db9ad21d5f
```

<details>
  

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839805/xrvetosqzuqeg3fphtsp.png)

https://platform.arkhamintelligence.com/visualizer/entity/0x7ABd480bDad5CCFe1AcC840cE408B1336b747ad3,0xBe6513762d4b65d74322FeCbe3aeCd0e944A5C1d,0x0316b816eD6aDDcCEC0963f730375E6B4991A5D3,0xa93e7678F0B90c0Dc454E9A3EF5260E6eD7C12F3,0xA2aA23E428ba5b8aBC52C733A1a9635841E737a1,0x7069e41d9E7099fDc4a4270E14aCC29003d9Df51,0x9547b0C194707EC1Ee64eA08975f1201802e9453,0x460314a8d83dc7ce9fA4a61F330D0Bb452e1793a,0xfCf5DB30D7403a90aB625FA850A5577E944117EA,0x29D5FAd4C0F8ECc705cA2AD4BF47610aE88291F1,0x7fF48F78cA1855bAd9a3Daee8d2c3B29269eBd52,0x10b0D3B4293ab1112ed0c96f37Ed9B1D22c1DD53,0x04A0476DaedaFfC743A8c2d29e5562064b744E7c,0x44b34F5A043357F62f2061f4A4FD6f21dD7bC51f,0xdEB73dE3C89189122fE621e8171b65DA7fAB0613,0x5998dE36DBf222A0735a8e3004fD90CDCfD7A4ab,0xA0080a7bc272624355d3104E60c0354502624B38,0x2b699BFa91bD12954f8E1Fb5E891c4cdcC3B4071,0xC429Db30e778d44143688BEd7aA223540aAB3429,0x6Cb35c0427E0C44B10Da4687D5E0a96380a2Ca0F,0x019cc201dfd4CE85f83e84A2c6a1294F1E66FA86,0x3a179Bf9B4F581696B1EEFE6F2bB4AD82ba8A690,0xBc593Ec4039E1281449F17da98D0d4E46116eCac,0x48b889640B16d8ee8b575249d99669D5094C3B0e,0x3601362b8DF6D2F87C4f0FE329BdEd64589e467a,0xdeb862a3b982F9278B258c72375EA2DB9aD21D5F?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

Layerzeroday verysimilar
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839806/f767shfaxypwbcuxnisv.png)

RENZO    

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839808/tlmnpc6iwijxjjogn9vw.png)



Renzo Linea Mint on same date with same amount:

https://lineascan.build/tx/0x31d5838cbdcbb3461ef663d2385f471760adfc293bed0ea75f7c7002d4737962      
https://lineascan.build/tx/0xe296283b059da2c1efda533b5795825bac96b7dbcef87b2b228966f52f23041a     
https://lineascan.build/tx/0xfe7231e0a3abd4bf7cd4c419958f6d997ae7d88ad96a854009c838baa6af2bc5    
https://lineascan.build/tx/0x8802609ab6f683815e23dd0d32eecee0fe9f1d1131b89a368eb030d1f89e3f94     
https://lineascan.build/tx/0x101038346b1f5d982594a2b14993e7af8f2bb75a516556e8385d0fb50f28b582     
https://lineascan.build/tx/0x5af61148bfe5d6bf37411822496589c9e417fc648eba2b27cd27768d9332892a       
https://lineascan.build/tx/0x198fa2ecd9dcef4d774b082880682deb91d6581b6ceba3877961bd292b5eff67         
https://lineascan.build/tx/0xfcf078be86e38dd70a58d640910f889b4549aa36580522f558fee869a360261b     
https://lineascan.build/tx/0x2c6a7aed6ab820f84c8459d61a59d1fda5f78ed18695bc915ce0e70aa0b80b5b       
https://lineascan.build/tx/0x2a1133b5079e577c58124c29e5e0606941f549f0228c08c7ea8940a4e2925a1f      
https://lineascan.build/tx/0x52eb2a1211cbeede2cb65688326e4bc8e8bc353cbb6b58e0d79aa178cd211db6    
https://lineascan.build/tx/0xf95937cd79431fb1a46edf9f70d445c0e86c457602353d92a2e81fb1f575572f      
https://lineascan.build/tx/0x6c1a57754fc395b06e651be0a3aa006885045d3dfae58988b31a73c65de4a531     
https://lineascan.build/tx/0x96b7c8c79db72a1b5bab8512afe0f658c7a9d5cfa31eb3e4a8e779da552f4938     
https://lineascan.build/tx/0xa2bb2cbcba9d225c638d6f6a5e41fea08af7cee290e6ba7a2ad8f9823ede2b3f
https://lineascan.build/tx/0xfe5c6ec85b21d1ec93e38a61c573d9f119c3dfef398297197648030c221c6ed4    
https://lineascan.build/tx/0x0f9db065a7b72b3800cc91e706907765dc6bd740bffff0480b2ff549a5c5be4e    
https://lineascan.build/tx/0x31ec369519f40b42438a182d0c013cf2f9de48863a814d76534e67781102f4ff     
https://lineascan.build/tx/0x3e1af24381f38b52585ba0b7706686eb8df57a586c738fb33fef6e233fd5bbc7    
https://lineascan.build/tx/0xa212ee8bb999b85532352230c20acf8d37bb6ebf5c0bfefa55fd1e8fcca8eed5       
https://lineascan.build/tx/0x1a67b03cfcbcfd4fb2063642448ee9535954664290314b8c577afbc051bab7bc     
https://lineascan.build/tx/0x8aeeb7ba311c6b7c4d78bbf22815882b1db4e954c763e826574ade36680a6f3c     
https://lineascan.build/tx/0x05469bb3b0fca3c6d21da88ce4867e76e9c85b21db4979e0bd075e6535a1be58     
https://lineascan.build/tx/0xa4d8c902c373975c8f7f00b789a39c65e1ff5b42e6471b605f88b1d837a19427      
https://lineascan.build/tx/0xcf0043b6027b229adf3b5d13db0464040a699a5f08fd2db8ee4ce7d4a8b86ac5     
https://lineascan.build/tx/0x4c742ce663144fbced1f489f0b0a61bcfc85d48722b8fb45834e0790f0aad671


Many wallets locked similar amounts of STG on the same day.

https://arbiscan.io/tx/0x94b7cd90fec65c54f76c653b5710dcf2b11f559503ea058fcc9466f66e6ebc4b
https://arbiscan.io/tx/0x9917a3b154f33e2d3c0b029e615fbc31fbeb72933bae9b807d0eb6beef4030b6


1 0x7abd480bdad5ccfe1acc840ce408b1336b747ad3 2022-10-27   2022-10-26   2022-08-08      
2 0xbe6513762d4b65d74322fecbe3aecd0e944a5c1d 2022-11-02     
3 0x0316b816ed6addccec0963f730375e6b4991a5d3 2022-11-02      
4 0xa93e7678f0b90c0dc454e9a3ef5260e6ed7c12f3 2023-02-03      
5 0xa2aa23e428ba5b8abc52c733a1a9635841e737a1 2023-02-03      
6 0x7069e41d9e7099fdc4a4270e14acc29003d9df51 2022-11-02      
7 0x9547b0c194707ec1ee64ea08975f1201802e9453 2023-02-03      
8 0x460314a8d83dc7ce9fa4a61f330d0bb452e1793a 2023-02-03      
12 0x10b0d3b4293ab1112ed0c96f37ed9b1d22c1dd53 2022-10-21      
13 0x04a0476daedaffc743a8c2d29e5562064b744e7c 2022-10-21      
14 0x44b34f5a043357f62f2061f4a4fd6f21dd7bc51f 2022-11-02   
15 0xdeb73de3c89189122fe621e8171b65da7fab0613 2022-11-02      
16 0x5998de36dbf222a0735a8e3004fd90cdcfd7a4ab 2023-02-03   
17 0xa0080a7bc272624355d3104e60c0354502624b38 2022-11-02   
18 0x2b699bfa91bd12954f8e1fb5e891c4cdcc3b4071 2022-11-02      
19 0xc429db30e778d44143688bed7aa223540aab3429 2023-02-03   
20 0x6cb35c0427e0c44b10da4687d5e0a96380a2ca0f 2023-02-03       
21 0x019cc201dfd4ce85f83e84a2c6a1294f1e66fa86 2023-02-03   
22 0x3a179bf9b4f581696b1eefe6f2bb4ad82ba8a690 2023-04-12      
23 0xbc593ec4039e1281449f17da98d0d4e46116ecac 2023-02-03      
24 0x48b889640b16d8ee8b575249d99669d5094c3b0e 2023-02-03   
25 0x3601362b8df6d2f87c4f0fe329bded64589e467a 2023-04-12      
26 0xdeb862a3b982f9278b258c72375ea2db9ad21d5f 2023-04-12      

What is much more revealing is the date of the native bridges for ZkSYNC, ZKSYNC LITE, STARKNET, almost all on the same day.
zksync

```
1 0x7abd480bdad5ccfe1acc840ce408b1336b747ad3 2023-11-11 2023-03-27 2023-03-24 
2 0xbe6513762d4b65d74322fecbe3aecd0e944a5c1d 2023-10-29 2023-08-20 2023-03-27 
3 0x0316b816ed6addccec0963f730375e6b4991a5d3 2023-10-29 2023-08-20 
4 0xa93e7678f0b90c0dc454e9a3ef5260e6ed7c12f3 2023-08-20 
5 0xa2aa23e428ba5b8abc52c733a1a9635841e737a1 2023-08-20 
6 0x7069e41d9e7099fdc4a4270e14acc29003d9df51 2023-10-26 2023-08-20 2023-03-28 
7 0x9547b0c194707ec1ee64ea08975f1201802e9453 2023-08-20 
8 0x460314a8d83dc7ce9fa4a61f330d0bb452e1793a 2023-08-20 
9 0xfcf5db30d7403a90ab625fa850a5577e944117ea 2023-08-20 
10 0x29d5fad4c0f8ecc705ca2ad4bf47610ae88291f1 2023-08-20 
11 0x7ff48f78ca1855bad9a3daee8d2c3b29269ebd52 2023-08-20 
12 0x10b0d3b4293ab1112ed0c96f37ed9b1d22c1dd53 2023-08-20 
13 0x04a0476daedaffc743a8c2d29e5562064b744e7c 2023-10-26 2023-08-20 2023-03-27 
14 0x44b34f5a043357f62f2061f4a4fd6f21dd7bc51f 2023-10-23 2023-08-20 
15 0xdeb73de3c89189122fe621e8171b65da7fab0613 2023-08-20 
16 0x5998de36dbf222a0735a8e3004fd90cdcfd7a4ab 2023-08-20 
17 0xa0080a7bc272624355d3104e60c0354502624b38 2023-08-20 
18 0x2b699bfa91bd12954f8e1fb5e891c4cdcc3b4071 2023-10-23 2023-08-20 
19 0xc429db30e778d44143688bed7aa223540aab3429 2023-08-20 
20 0x6cb35c0427e0c44b10da4687d5e0a96380a2ca0f 2023-08-20 
21 0x019cc201dfd4ce85f83e84a2c6a1294f1e66fa86 2023-08-20 
22 0x3a179bf9b4f581696b1eefe6f2bb4ad82ba8a690 2023-08-20 
23 0xbc593ec4039e1281449f17da98d0d4e46116ecac 2023-08-20 
24 0x48b889640b16d8ee8b575249d99669d5094c3b0e 2023-08-20 
25 0x3601362b8df6d2f87c4f0fe329bded64589e467a 2023-08-20 
26 0xdeb862a3b982f9278b258c72375ea2db9ad21d5f 2023-08-20 
```

```
zksynclite
1 0x7abd480bdad5ccfe1acc840ce408b1336b747ad3 2022-09-08 2022-09-07 2021-12-21 2021-12-03 2021-11-19 
2 0xbe6513762d4b65d74322fecbe3aecd0e944a5c1d 2023-03-23 2023-01-05 2022-11-30 2022-11-30 2022-09-09 2021-11-19 
3 0x0316b816ed6addccec0963f730375e6b4991a5d3 2023-03-23 2023-01-03 
4 0xa93e7678f0b90c0dc454e9a3ef5260e6ed7c12f3 2023-03-23 2022-12-29 
5 0xa2aa23e428ba5b8abc52c733a1a9635841e737a1 2023-03-23 2022-12-29 
6 0x7069e41d9e7099fdc4a4270e14acc29003d9df51 2023-03-23 2023-01-05 2022-11-16 2021-11-23 
7 0x9547b0c194707ec1ee64ea08975f1201802e9453 2023-03-23 2023-01-09 2023-01-02 2023-01-01 
8 0x460314a8d83dc7ce9fa4a61f330d0bb452e1793a 2023-03-23 2023-01-09 2022-12-31 
9 0xfcf5db30d7403a90ab625fa850a5577e944117ea 2023-03-20 
10 0x29d5fad4c0f8ecc705ca2ad4bf47610ae88291f1 2023-03-20 
11 0x7ff48f78ca1855bad9a3daee8d2c3b29269ebd52 2023-03-21 
12 0x10b0d3b4293ab1112ed0c96f37ed9b1d22c1dd53 2023-03-24 2023-01-03 
13 0x04a0476daedaffc743a8c2d29e5562064b744e7c 2022-09-09 2021-12-03 2021-11-19 
14 0x44b34f5a043357f62f2061f4a4fd6f21dd7bc51f 2023-03-23 2023-01-02 
15 0xdeb73de3c89189122fe621e8171b65da7fab0613 2023-03-23 2023-01-02 
16 0x5998de36dbf222a0735a8e3004fd90cdcfd7a4ab 2023-03-23 2023-01-07 2022-12-30 
17 0xa0080a7bc272624355d3104e60c0354502624b38 2023-03-23 2023-01-02 
18 0x2b699bfa91bd12954f8e1fb5e891c4cdcc3b4071 2023-03-23 2023-01-02 
19 0xc429db30e778d44143688bed7aa223540aab3429 2023-03-23 2023-01-08 2022-12-31 
20 0x6cb35c0427e0c44b10da4687d5e0a96380a2ca0f 2023-03-23 2023-01-06 2022-12-30 2022-12-30 
21 0x019cc201dfd4ce85f83e84a2c6a1294f1e66fa86 2023-03-23 2023-01-08 2022-12-31 
22 0x3a179bf9b4f581696b1eefe6f2bb4ad82ba8a690 2023-03-18 
23 0xbc593ec4039e1281449f17da98d0d4e46116ecac 2023-03-23 2023-01-06 2022-12-29 
24 0x48b889640b16d8ee8b575249d99669d5094c3b0e 2023-03-23 2023-01-07 2022-12-30 
25 0x3601362b8df6d2f87c4f0fe329bded64589e467a 2023-03-18 
26 0xdeb862a3b982f9278b258c72375ea2db9ad21d5f 2023-03-18 
```

```
starknet
1 0x7abd480bdad5ccfe1acc840ce408b1336b747ad3 2023-03-24 2023-03-20 2023-03-12 2023-02-07 2023-02-06 2022-12-17 2022-12-15 2022-12-09 2022-11-10 2022-11-08 2022-10-27 2022-10-26 2022-10-25 
2 0xbe6513762d4b65d74322fecbe3aecd0e944a5c1d 2023-03-24 2022-12-28 2022-12-27 2022-12-03 2022-12-03 2022-12-02 2022-12-01 2022-11-30 
3 0x0316b816ed6addccec0963f730375e6b4991a5d3 2023-03-24 2022-12-27 2022-12-27 2022-12-07 2022-12-06 2022-12-06 2022-12-05 
4 0xa93e7678f0b90c0dc454e9a3ef5260e6ed7c12f3 2023-03-24 2022-12-27 2022-12-27 2022-12-08 2022-12-07 2022-12-07 2022-12-06 
5 0xa2aa23e428ba5b8abc52c733a1a9635841e737a1 2023-03-24 2022-12-27 2022-12-27 2022-12-08 2022-12-07 2022-12-07 2022-12-06 
6 0x7069e41d9e7099fdc4a4270e14acc29003d9df51 2023-03-24 2022-12-28 2022-12-27 2022-12-04 2022-12-03 2022-12-03 2022-12-02 
7 0x9547b0c194707ec1ee64ea08975f1201802e9453 2023-03-24 2023-01-10 2023-01-09 2022-12-26 2022-12-26 2022-12-24 2022-12-23 
8 0x460314a8d83dc7ce9fa4a61f330d0bb452e1793a 2023-03-24 2023-01-10 2023-01-09 2022-12-26 2022-12-26 2022-12-24 2022-12-23 
9 0xfcf5db30d7403a90ab625fa850a5577e944117ea 2023-08-20 
10 0x29d5fad4c0f8ecc705ca2ad4bf47610ae88291f1 2023-08-20 
11 0x7ff48f78ca1855bad9a3daee8d2c3b29269ebd52 2023-08-20 
12 0x10b0d3b4293ab1112ed0c96f37ed9b1d22c1dd53 2023-03-24 2023-03-24 2022-12-02 2022-12-01 2022-12-01 2022-11-30 
13 0x04a0476daedaffc743a8c2d29e5562064b744e7c 2023-03-24 2023-03-15 2022-12-28 2022-12-27 2022-12-02 2022-12-01 2022-12-01 2022-11-30 
14 0x44b34f5a043357f62f2061f4a4fd6f21dd7bc51f 2023-03-24 2022-12-28 2022-12-27 2022-12-04 2022-12-04 2022-12-03 2022-12-03 2022-12-02 
15 0xdeb73de3c89189122fe621e8171b65da7fab0613 2023-03-24 2022-12-27 2022-12-27 2022-12-06 2022-12-06 2022-12-05 2022-12-05 2022-12-04 
16 0x5998de36dbf222a0735a8e3004fd90cdcfd7a4ab 2023-03-24 2023-01-08 2023-01-07 2022-12-27 2022-12-26 2022-12-23 2022-12-22 
17 0xa0080a7bc272624355d3104e60c0354502624b38 2023-03-24 2022-12-28 2022-12-27 2022-12-05 2022-12-04 2022-12-04 2022-12-03 
18 0x2b699bfa91bd12954f8e1fb5e891c4cdcc3b4071 2023-03-24 2022-12-27 2022-12-27 2022-12-06 2022-12-05 2022-12-05 2022-12-04 
19 0xc429db30e778d44143688bed7aa223540aab3429 2023-03-24 2023-01-09 2023-01-08 2022-12-27 2022-12-26 2022-12-23 2022-12-23 2022-12-22 
20 0x6cb35c0427e0c44b10da4687d5e0a96380a2ca0f 2023-03-24 2023-01-07 2023-01-06 2022-12-27 2022-12-26 2022-12-23 2022-12-22 
21 0x019cc201dfd4ce85f83e84a2c6a1294f1e66fa86 2023-03-24 2023-01-09 2023-01-08 2022-12-26 2022-12-26 2022-12-24 2022-12-23 
22 0x3a179bf9b4f581696b1eefe6f2bb4ad82ba8a690 2022-12-26 2022-12-26 2022-12-24 2022-12-23 
23 0xbc593ec4039e1281449f17da98d0d4e46116ecac 2023-03-24 2023-01-07 2023-01-06 2022-12-27 2022-12-26 2022-12-23 2022-12-22 
24 0x48b889640b16d8ee8b575249d99669d5094c3b0e 2023-03-24 2023-01-08 2023-01-07 2022-12-27 2022-12-26 2022-12-23 2022-12-22 
25 0x3601362b8df6d2f87c4f0fe329bded64589e467a 2022-12-26 2022-12-25 2022-12-25 2022-12-24 
26 0xdeb862a3b982f9278b258c72375ea2db9ad21d5f 2022-12-26 2022-12-25 2022-12-25 2022-12-24 
```


</details>

## Cluster 6 

11 first address same CEX deposit 0xf9f24433BE35f0f14673eE30B079a0727d3278F5 (OKX)

**TLDR**
STG stargate bridge wash trading with huge amount, then deposit to Binance
Similar layer zero days

```
0xb9e5817f583e523bb93915152c9bf59a86b3bb1a
0x63500fae0e488188d48fb4706e4d2837947e7e1d
0x298d0e720af139793a406a52e5cd1031fe203892
0xfa0a1f52fa4cb247d5e7c594ab86cb79f317cc32
0x7bed252b6140cfa8d138742c7252cbe38cb22408
0x42af53e406ffc8a5a697e361a849530e483d36ef
0x513175a72d357f3c8a3ed297d70c1a9b214b582f
0x02218b484d5783eec60a3eac0593efa69602ecaa
0xa459a1f385db5829388573ca75f0417550e765db
0x676f5a22bdd5fe1f1d8780c3e4e1eca2185f7a09
0x139e72d1eb1c3639372df153f946a7dad3cb5b97
0x901fd2bfff72851f450af7e5782ac4e7c256dd7d
0x60f89804f77abb1918c2b9281f75dd4d7c7e3583
0xb75691a28d322f5193af9cd1e6417127d24110fb
0x407fe4cbc8a2529aec8502602d998c91552c476f
0x89db0c9a875a87d89d2d8ebb254cec257f561850
0x73591b5643bd7a4827de0b0a97e0e0414453115d
0xfd7791947f29a5cee9351426e7323f3fb250b782
0xb8a7622daf4549fbc774bd3e1d4903079386af1f
0xbb94514a1b3a3212308f0adf6383baae1f5921f5
0xb86c20fd1265d26da93d1de0991dfbbe98d1efa4
0x26b7e8faaead192acc4e197a72ba99721eb84acc
0xec3b8726c53c2bceddd720293725ad34abf9f8b7
0x943e3b444029fd55a53e85aff203c3dd19881e87
0x429d9e1cf998abd7288fd0ab535b55f24ae57ca6
0xd54238c508268694e5aa0129ecf9d08cf7f433de
0x3e608ddc9a4832f1cf8fb7bef8cf0aaac2c2e2a7
0x248cd65f6d6179b1501afac5c41a8540446a35e1
0x20e4fd1d84eab14effce8e3dcc1c9ecc1f63bd28
0xc9d88b20ef4099d0c0acd797b2c9916d137658dc
0x4a043886f563221bc2db9abb775105a1d837daa0
0xb26d7e82e3d29c0519d3ee96b99d6c3a686d903d
0x131aaafde6ab1598ac391e34db0a7999a34f1963
0x1790d77c7fb3b08bf05a650337a5d27a0d977d71
0x025cfb057b1ac30fe9ecf0087c6bc5a305679252
0x5406e303c82e86fa837816ba36cf2e6dbeb8d79e
0x95a37ac97050add5afb1419895691278a848e402
0xf7ae08ae54e010be11b8b1bc6ad8d1d93af05236

```


<details>

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839810/bo86cwlr6x9vrnrgfhyw.png)
https://platform.arkhamintelligence.com/visualizer/entity/0xb9E5817f583e523bB93915152C9bF59a86B3BB1A,0x63500Fae0E488188d48fb4706E4D2837947e7E1D,0x298d0E720af139793a406A52e5CD1031FE203892,0xFA0a1f52fa4CB247D5e7c594aB86cb79F317cC32,0x7BEd252b6140CFa8d138742c7252cBE38Cb22408,0x42aF53e406FfC8A5a697e361A849530E483D36Ef,0x513175A72D357f3C8A3ED297d70C1a9B214b582F,0x02218B484d5783Eec60A3eac0593EfA69602eCaa,0xa459a1F385DB5829388573ca75F0417550e765dB,0x676F5a22Bdd5FE1f1d8780C3E4e1Eca2185f7a09,0x139e72D1eb1C3639372Df153F946A7dAd3cB5b97,0x901Fd2bfFF72851F450AF7e5782AC4e7c256DD7D,0x60f89804f77aBb1918C2b9281f75dd4D7C7e3583,0xb75691a28d322F5193Af9cd1e6417127D24110FB,0x407FE4CbC8A2529aEc8502602d998c91552c476F,0x89Db0C9a875A87D89D2d8EBB254CEc257f561850,0x73591b5643bD7A4827dE0b0a97E0E0414453115d,0xFd7791947f29a5CeE9351426e7323F3fB250B782,0xb8a7622DAf4549FBc774BD3e1d4903079386Af1F,0xbB94514A1b3A3212308F0aDf6383bAAe1F5921f5,0xB86c20Fd1265D26Da93D1DE0991DFbBe98D1efA4,0x26B7E8faaead192aCC4e197a72ba99721EB84ACC,0xEc3B8726c53C2bceDDd720293725ad34abf9f8b7,0x943e3B444029Fd55a53e85afF203C3DD19881E87,0x429d9E1CF998abd7288FD0ab535b55F24aE57CA6,0xd54238C508268694e5aa0129eCf9D08cF7f433DE,0x3e608ddC9a4832F1cF8fB7BEf8cF0aaaC2c2e2a7,0x248CD65F6D6179B1501aFAC5c41a8540446a35E1,0x20e4Fd1d84eab14EFFCE8E3DCc1C9eCc1F63BD28,0xC9D88b20eF4099D0C0acd797B2C9916D137658DC,0x4A043886F563221bc2db9ABB775105a1d837DAA0,0xB26d7e82E3D29c0519d3ee96b99D6C3a686D903D,0x131AAaFde6AB1598ac391E34DB0A7999A34f1963,0x1790d77c7Fb3b08bF05a650337a5D27a0d977D71,0x025cFB057b1Ac30Fe9EcF0087c6Bc5a305679252,0x5406E303C82e86fA837816bA36cf2E6DBEB8d79E,0x95a37ac97050aDd5AFb1419895691278a848e402,0xf7aE08aE54E010bE11B8b1bc6ad8D1D93AF05236?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

Layerzerodays:
for exemple, 11 address with 315 layerzerodays, created within less than 2 hours!
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839812/wmtolziruzfbfumd9b6o.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839813/rm8qekkqw2jskc3s6jrv.png)

On-chain analysis:
- Similar number of LayerZero messages across all wallets (approximately 100).
- Similar patterns observed across multiple wallets.

STG Bridge with a huge amount, on very close dates. Bridge with a large amount then deposit to Binance, and the chain continues.

Binance withdraw and deposit chain: 
2023/12/20 -> 2023/12/27 wash trading with Binance
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839814/toiwgre8g497xoiif203.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839816/gurvfbywwgec6vvbqwjo.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839817/umhcei8q5vzxgbsgimaz.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839819/jjcaxqelbk75cpkcdyeu.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839820/ofcdlk0myrw6splqthei.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839822/ui8xyfxaedzvqmhrbttc.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839823/dyh9qoiuprbzzakibl0c.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839825/t3qwavjuzrpo5jq6xgdg.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839826/tmgklevyhimvgtfc7ux5.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839828/lmgbb2uolk7wwpr3ogzu.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839830/qua85l1lukkxqt2xf7eq.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839831/rhhk8nk85oo4pthwcv0v.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839833/zv4izdjfqzf8ovpiywsj.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839834/vgcn8zctl9b459jkjwqi.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839835/b9d6rstymt09x2dzfocf.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839837/mrqpnm47g7dg5uuljqjs.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839839/g33onmhotbevocjwbkwc.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839841/gnkjd5kfnsktdvkifi9a.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839842/nwcaljozx8f0et4hn2wq.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839844/siu4nqkbxrhkxlpnurge.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839845/ojlk5luehrjqihrewx6h.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839846/dsnmbuu5vvo0yfa2qkhs.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839848/jnegtxgkdqrbkvt02bix.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839850/rf7gfhe5a9py6kttpjt4.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839851/j7ks14d4kr7epjz9povx.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839852/nt9mbx6am2bp8nxj1qd4.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839854/razhggckqyry5j0viruf.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839855/ostkq5apx2a40xi7kgwy.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839857/jouqomhm9qqvik1tmgu4.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839858/wqkgx5uay5ps500mtsla.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839860/halsjuoppk3psylpxsdq.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839861/sec1vrsby69ppfstwbyu.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839863/qrcnszbst6n0zwk0bwkm.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839864/mhveoq9fe6gpxmo3mesr.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839866/nty3fevoerivrrtdgjgl.png)







Wash trading exemples: 
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839867/pynnxmuiqwwmturn20nv.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839868/wfbfhidcoa0hmbndlkab.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839870/yuerawn1odcnah0l4w8y.png)





</details>

## Cluster 7 

21 first address same CEX deposit 0x54BA5493436cE5Cfdc83eE7c95D04c926716ae02 (Binance)

**TLDR**
Disperse de USDC pour farm le bridge Orderly (layerzero)
Wallet avec des LZD tres proche

```
0x31ce6f9e94c76522a22306f4ebde99d0337f25c4
0x120b3bd4c51cd9afb054991deadd8f3921f72fd9
0xf9e298c3f0e9531c0f2a87e8d5647b2ab59d2171
0xf706eb749eb8e94742ed9ad5234882fd1d74f7b4
0x335f9602dadbd97c956a628514e1c06660304f17
0x8ae99e4e53bfe644f5fcbf70860c9476f531e54a
0xd18a806ec1198a960f858cd6a16da6a7630d06c8
0x71d361dbfc1b44adc35168a4edba882cb9bfc1df
0xa28468cd24bef4a11e0f56f640520b4e99f6c36f
0x2313e8d99612a06000fce8a22151127d14b15bdc
0xa05995f580c024f216c0d8b69fb819f2c6f22b67
0x9605cecd3105653c9877876dc2c18773415ed49a
0xc361d995d14bbbf144e19b29f301a79681aa6f26
0x8c6ca92ed894ae08b862797a9d3074999fe56f74
0xd5798089637d49e99decc9918fd1210d0d853716
0x4d426d51d79fbf5c3f0941c547e71bf5b990d28d
0x58e522a90453a846595272d261fc1343648c5cf2
0xa38125d2ccc23299b2ea3957cb778694318b317b
0x1565488dae872828d1361b28a2e5c177881cd61f
0x0d87d7a49344754def8ae853acb4a20907d0e464
0x3f15900a92345782c73c46658118f8c5f63db92a
0x82aA02620393fcf6Ae31F14276c054Bf15a4D885
0xce8500Cf7edD55e900e9CA6f374ECDb19428C96A
0xB7829Fd2Ea87Bb03200838480F451fF2521A7F4F
0x02eb4eA27D0476C96536D45594885349BD597071
0x87a7054A5Ae3dE3214c46d0cFC6f9bff13a9d853
0xEBed5D8C2228d6037b2D8cf5a4112969c2177E17
0xfFb7DCa21C077427336b8C0b09867c43445294b2
0x3115F63b988bEdbc6364ce74b02c31593c9685e0
0x97792FCc8Fb31EbA6737c785607d641D3bDcDe4e
0x0cA2DBcBBfd0F0b11efE697cB80Ad08096B132e9
0x75521D0fa2A13afcb22934b6EC9DC6F94363BDEC
0x58eD441FaD1761192E02d8625F6F011570E9cFd6
0xB7FC07CDD7b559395Ac358c1Cd174D2897356D08
0xDd5868A795e540F125FA017A6E51f9375fB10421
0xF87ADa8a6559057eb17194A152CC0B7b954100B1
0xb974e3933218b63D8641c5D20db411B2713b1405
0x3266e91cFeF333e4F21bAaFB2C7AC12AaB2EeB4a
0x630CBa1BD582BE03bbc383306E8F7766F94b8c1C
0xd68d861110a0C564bD6DA1dBDB7670ABE319164f
0xa967a5D9F782d1e23267026c5A59314e5102205d
0x565EC4BaAb11c4775458F27213C1B43BB3d01106
0x0e58D4C338d02312bD926C3784C74233Ad29B6Eb
0xF7b42b8eA9Ccca777f5cDECAAFD6fB52Ded22933
0x7CCEd1135A99E196835Ba9564B2886513eE28738
0x461562556a0E91b6C703Fbaf7650E334CdCda492
0x119468039ff58EAD48924484F45C0bF487610596
0x6a5F6A37Bdaf0d391952809e497C88cCF033Edf7
0x1be5629269bc588a14b3318AfBcfC75D5BCD3A4D
0x163B466E164e5f50168D9E08906B1ECc17053F30
0xfb429D6CbC8Ca02eaEC147d26Ed4fb42D9d82A2B
0x02377F6f16724f0d601e84b0D7DDbda25B8b98Df
0x85dE98a32dC868c89EdbFc0A302286B8B58A91bc
0x3306dc0f9Dd3807e41c397d8BbdF2DDbDDd19D7d
0x530C1d096848A2542bb6f97d740B4b29B976C96f
0xa0c3a793D47fD29c76392603058753C3fD923246
0xe8d101BaFC74b086FE92A12d39DC190b9bd4f278
0x4Aa30280846C70f4bd89453593796B8f5a9D12E9
0xB896bd73Bf58B97978b41cc7bDDC534209660296
0x93470c662Fbdf23F72217A62268dA356e8E46B56
0x71323939a751E2c0312C73390F83505fbADdCF56
0x0E949fD1FE58257c15C9f7bb18Bb894E09F74c79
0xC877bd8aD20D744815282695C0b3E9e5D59f449c
```

<details>


![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839872/gnwazutcvzopb57sxfwo.png)

https://platform.arkhamintelligence.com/visualizer/entity/0x31Ce6f9e94C76522A22306f4Ebde99d0337F25c4,0x120b3bD4c51cD9aFB054991DeADd8f3921f72FD9,0xF9e298c3f0e9531C0f2A87E8d5647B2aB59d2171,0xf706eb749EB8E94742ed9AD5234882Fd1d74F7B4,0x335f9602DAdbD97c956A628514e1C06660304F17,0x8Ae99e4e53BFE644F5FCBf70860C9476f531e54a,0xd18a806Ec1198A960f858Cd6a16da6a7630D06c8,0x71d361dBfc1b44Adc35168a4eDba882CB9BFC1Df,0xA28468cD24BEF4A11E0f56F640520b4E99f6C36f,0x2313E8D99612a06000FcE8A22151127D14b15BDC,0xa05995F580c024f216c0d8B69fb819f2C6F22B67,0x9605ceCd3105653C9877876dc2C18773415ED49a,0xc361d995D14bBBF144e19b29F301a79681aa6f26,0x8C6CA92eD894ae08B862797A9D3074999fe56F74,0xd5798089637D49e99deCc9918FD1210d0D853716,0x4D426d51d79fBf5c3F0941c547e71bf5b990d28d,0x58E522a90453a846595272D261Fc1343648c5cf2,0xa38125d2CCC23299b2eA3957CB778694318b317B,0x1565488daE872828D1361B28a2e5C177881Cd61f,0x0d87D7A49344754DEf8aE853aCb4A20907D0E464,0x3F15900A92345782C73c46658118F8C5F63Db92a,0x82aA02620393fcf6Ae31F14276c054Bf15a4D885,0xce8500Cf7edD55e900e9CA6f374ECDb19428C96A,0xB7829Fd2Ea87Bb03200838480F451fF2521A7F4F,0x02eb4eA27D0476C96536D45594885349BD597071,0x87a7054A5Ae3dE3214c46d0cFC6f9bff13a9d853,0xEBed5D8C2228d6037b2D8cf5a4112969c2177E17,0xfFb7DCa21C077427336b8C0b09867c43445294b2,0x3115F63b988bEdbc6364ce74b02c31593c9685e0,0x97792FCc8Fb31EbA6737c785607d641D3bDcDe4e,0x0cA2DBcBBfd0F0b11efE697cB80Ad08096B132e9,0x75521D0fa2A13afcb22934b6EC9DC6F94363BDEC,0x58eD441FaD1761192E02d8625F6F011570E9cFd6,0xB7FC07CDD7b559395Ac358c1Cd174D2897356D08,0xDd5868A795e540F125FA017A6E51f9375fB10421,0xF87ADa8a6559057eb17194A152CC0B7b954100B1,0xb974e3933218b63D8641c5D20db411B2713b1405,0x3266e91cFeF333e4F21bAaFB2C7AC12AaB2EeB4a,0x630CBa1BD582BE03bbc383306E8F7766F94b8c1C,0xd68d861110a0C564bD6DA1dBDB7670ABE319164f,0xa967a5D9F782d1e23267026c5A59314e5102205d,0x565EC4BaAb11c4775458F27213C1B43BB3d01106,0x0e58D4C338d02312bD926C3784C74233Ad29B6Eb,0xF7b42b8eA9Ccca777f5cDECAAFD6fB52Ded22933,0x7CCEd1135A99E196835Ba9564B2886513eE28738,0x461562556a0E91b6C703Fbaf7650E334CdCda492,0x119468039ff58EAD48924484F45C0bF487610596,0x6a5F6A37Bdaf0d391952809e497C88cCF033Edf7,0x1be5629269bc588a14b3318AfBcfC75D5BCD3A4D,0x163B466E164e5f50168D9E08906B1ECc17053F30,0xfb429D6CbC8Ca02eaEC147d26Ed4fb42D9d82A2B,0x02377F6f16724f0d601e84b0D7DDbda25B8b98Df,0x85dE98a32dC868c89EdbFc0A302286B8B58A91bc,0x3306dc0f9Dd3807e41c397d8BbdF2DDbDDd19D7d,0x530C1d096848A2542bb6f97d740B4b29B976C96f,0xa0c3a793D47fD29c76392603058753C3fD923246,0xe8d101BaFC74b086FE92A12d39DC190b9bd4f278,0x4Aa30280846C70f4bd89453593796B8f5a9D12E9,0xB896bd73Bf58B97978b41cc7bDDC534209660296,0x93470c662Fbdf23F72217A62268dA356e8E46B56,0x71323939a751E2c0312C73390F83505fbADdCF56,0x0E949fD1FE58257c15C9f7bb18Bb894E09F74c79,0xC877bd8aD20D744815282695C0b3E9e5D59f449c?flow=self&positions=%7B%220x120b3bD4c51cD9aFB054991DeADd8f3921f72FD9%22%3A%7B%22fx%22%3A142%2C%22fy%22%3A-61%7D%2C%220x2313E8D99612a06000FcE8A22151127D14b15BDC%22%3A%7B%22fx%22%3A48%2C%22fy%22%3A-97%7D%2C%220x71d361dBfc1b44Adc35168a4eDba882CB9BFC1Df%22%3A%7B%22fx%22%3A15%2C%22fy%22%3A-79%7D%2C%220xA28468cD24BEF4A11E0f56F640520b4E99f6C36f%22%3A%7B%22fx%22%3A9%2C%22fy%22%3A-70%7D%2C%22basutano6015%22%3A%7B%22fx%22%3A79%2C%22fy%22%3A30%7D%2C%22kwbrars30%22%3A%7B%22fx%22%3A-6%2C%22fy%22%3A-61%7D%2C%22mamun-mulyadi%22%3A%7B%22fx%22%3A-5%2C%22fy%22%3A-31%7D%7D&sortDir=desc&sortKey=time&usdGte=0.1

Same layer zero days
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839873/ugcrngzgqdxmmevsm6jn.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839875/qjkilbbzvat4g3167he6.png)


On chain analysis

Dispersed 55k USDC among all their wallets on Arbitrum to farm the Orderly bridge (Layer Zero interaction), distributing about 1.1k per wallet.
https://arbiscan.io/tx/0xd104245414238ca2fce89fd8609750f0139a1b7d71398832f535d237baf18027


</details>

## Cluster 8 

10 first address same CEX deposit (Binance)
0xC88c6f5a305D7bdEB04F000c4F1BF02413ded106

**TLDR**
Linea Renzo Deposit Scrpited 
Same deposit & withdraw date, same amount
2 batch of STG lock date

```
0x078a0b6d78d6fa119655fe6a1b7c02fc9dc7ff73
0x228b1e6e41189f3a66a8e4e088d3bba9ab5de5fa
0xacd54246eda0c5638a247c4717a8782c21497eb6
0xae21a3b475a5e6cdccf389ed81530e1ee3da6464
0xae80fdcc486e493ef3d5be81ec1bdc6c492c25e3
0x2e424c44266713c829b76f34171660b98e8f74ed
0x1fd9053c40351e83aed0d7b1fd7ef3d5ccf13a39
0x1841aa56deba1e83425791fbe827b0d6ffb03e10
0x442f7980dbf32cae7c8e5bf11af0f252f5bbee5b
0x272034ff890c1cdd59606afc50798459694e1968
0xb3902eb498681193c6fd65c653a8970c2a1b8044
0x4182035e9ad2546d1f5960aec93c2c852227e6b4
0x7d740a3b8221ad036987d7653bee8fd32a14a7bc
0xe0aab54593d19336d77f460f055211892d5f8876
0x8b5d6dd501d5899de869eb875b04dc76e7fd5f08
0xf380a00a96c85ba7d509fda02b583824f9342495
0x8c118d7ad7a62ef0ecc6a88c3116bd8050c6195a
0x0e1ad80810f133b6608df93de34060044ce88e9c
0x616f3b0259564367b66f4d5a2d8525b4f7737d72
0xc436489b54bdce304d0b1802ca7cf72a82f50446
```

<details>

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839877/cxspkzncxchicg6cmc6j.png)
https://platform.arkhamintelligence.com/visualizer/entity/0x078A0B6D78D6Fa119655Fe6a1b7c02Fc9dC7FF73,0x228b1E6E41189F3a66A8E4e088D3bbA9AB5de5fA,0xAcd54246EDa0c5638a247C4717a8782c21497eb6,0xaE21A3B475a5E6Cdccf389ed81530e1ee3DA6464,0xAE80fDcc486e493eF3D5bE81Ec1BDc6C492C25e3,0x2E424C44266713c829b76f34171660B98E8f74ed,0x1fD9053c40351E83AEd0D7B1FD7ef3d5CCF13A39,0x1841Aa56dEBA1e83425791FbE827B0d6ffb03E10,0x442f7980DbF32CaE7C8E5bF11Af0F252F5bBee5b,0x272034Ff890C1cdD59606aFC50798459694e1968,0x7DA04356B9536F4a949Bfc17114e242e84AFCdF4,0xb3902eb498681193C6fd65C653A8970C2A1b8044,0x4182035e9ad2546D1F5960AEC93C2c852227E6B4,0x7D740a3B8221aD036987D7653bEE8Fd32a14a7bC,0xE0AAb54593d19336D77f460F055211892D5f8876,0x8B5d6DD501d5899DE869eB875b04DC76e7FD5f08,0xF380a00A96c85BA7d509Fda02B583824f9342495,0x8C118d7aD7A62Ef0Ecc6a88c3116bd8050c6195A,0x0e1ad80810F133B6608dF93De34060044cE88e9c,0x616f3B0259564367b66F4d5A2d8525B4f7737D72,0xC436489b54bdce304D0b1802cA7Cf72a82f50446?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

Similar layer zero Days over 2 batch 
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839879/xraap7agz9r3rbbgrg6f.png)

Renzo Linea Scrpited 
Deposit & withdraw date
Same amount

```
1 0x078a0b6d78d6fa119655fe6a1b7c02fc9dc7ff73 2024-04-06 2024-04-17  0.10125   
2 0x228b1e6e41189f3a66a8e4e088d3bba9ab5de5fa 2024-04-06 2024-04-17  0.10125   
3 0xacd54246eda0c5638a247c4717a8782c21497eb6 2024-04-06 2024-04-13  1.0125
4 0xae21a3b475a5e6cdccf389ed81530e1ee3da6464 2024-04-06 2024-04-17  0.10125
5 0xae80fdcc486e493ef3d5be81ec1bdc6c492c25e3 2024-04-06 2024-04-17  0.10125
6 0x2e424c44266713c829b76f34171660b98e8f74ed 2024-04-06 2024-04-17  0.10125
7 0x1fd9053c40351e83aed0d7b1fd7ef3d5ccf13a39 2024-04-06 2024-04-17  0.10125
8 0x1841aa56deba1e83425791fbe827b0d6ffb03e10 2024-04-06 2024-04-17  0.10125
9 0x442f7980dbf32cae7c8e5bf11af0f252f5bbee5b 2024-04-06 2024-04-17  0.10125
10 0x272034ff890c1cdd59606afc50798459694e1968 2024-04-06 2024-04-17  0.10125
11 0xb3902eb498681193c6fd65c653a8970c2a1b8044 2024-04-06 2024-04-17  0.10125
12 0x4182035e9ad2546d1f5960aec93c2c852227e6b4 2024-04-06 2024-04-17  0.10125
13 0x7d740a3b8221ad036987d7653bee8fd32a14a7bc 2024-04-06 2024-04-17  0.10125
14 0xe0aab54593d19336d77f460f055211892d5f8876 2024-04-06 2024-04-17  0.10125
15 0x8b5d6dd501d5899de869eb875b04dc76e7fd5f08 2024-04-06 2024-04-17  0.10125
16 0xf380a00a96c85ba7d509fda02b583824f9342495 2024-04-06 2024-04-17  0.10125
17 0x8c118d7ad7a62ef0ecc6a88c3116bd8050c6195a 2024-04-06 2024-04-17  0.10125
18 0x0e1ad80810f133b6608df93de34060044ce88e9c 2024-04-06 2024-04-17  0.10125
19 0x616f3b0259564367b66f4d5a2d8525b4f7737d72 2024-04-06 2024-04-17  0.10125
20 0xc436489b54bdce304d0b1802ca7cf72a82f50446 2024-04-06 2024-04-17  0.10125
```

bsc stg lock
```
1 0x078a0b6d78d6fa119655fe6a1b7c02fc9dc7ff73 2023-04-05   
2 0x228b1e6e41189f3a66a8e4e088d3bba9ab5de5fa 2023-04-05   
3 0xacd54246eda0c5638a247c4717a8782c21497eb6 2023-04-05   
4 0xae21a3b475a5e6cdccf389ed81530e1ee3da6464 2023-04-05   
5 0xae80fdcc486e493ef3d5be81ec1bdc6c492c25e3 2023-04-05   
6 0x2e424c44266713c829b76f34171660b98e8f74ed 2023-04-05   
7 0x1fd9053c40351e83aed0d7b1fd7ef3d5ccf13a39 2023-04-05   
8 0x1841aa56deba1e83425791fbe827b0d6ffb03e10 2023-04-05   
9 0x442f7980dbf32cae7c8e5bf11af0f252f5bbee5b 2023-04-05   
10 0x272034ff890c1cdd59606afc50798459694e1968 2023-04-05   
11 0xb3902eb498681193c6fd65c653a8970c2a1b8044 2024-03-20   
12 0x4182035e9ad2546d1f5960aec93c2c852227e6b4 2024-03-20   
13 0x7d740a3b8221ad036987d7653bee8fd32a14a7bc 2024-03-20   
14 0xe0aab54593d19336d77f460f055211892d5f8876 2024-03-20   
15 0x8b5d6dd501d5899de869eb875b04dc76e7fd5f08 2024-03-20   
16 0xf380a00a96c85ba7d509fda02b583824f9342495 2024-03-20   
17 0x8c118d7ad7a62ef0ecc6a88c3116bd8050c6195a 2024-03-20   
18 0x0e1ad80810f133b6608df93de34060044ce88e9c 2024-03-20   
19 0x616f3b0259564367b66f4d5a2d8525b4f7737d72 2024-03-20   
20 0xc436489b54bdce304d0b1802ca7cf72a82f50446 2024-03-20   
```

</details>

## Cluster 9

All addresses are linked by the same CEX deposit wallet. (Binance)
0xd59Fe06386D34ADb4E54F11945Cf72EaB9C60404

**TLDR**
Same CEX deposit 
Same ZKSYNC bridge timestamp 
ZKSYNC washtrading thanks to Binance deposit address

```
0x76f58de66f282b098e92d2e263878c25d711798d
0x75e840bf2a6a385741c69f239bf5605e5659968c
0x15130d3ca687e16aab26dbe64d00110482b3ac64
0x9b00ce25837d4e1b1f0ee8e6fa5029697d7aae68
0xdfcf5cf0c2d4214ac92ceb2783303dbc8c3af687
0x48db6b16dbea2578696f5aceb80b0358e3b0d5af
0x2edc3e996fa79d5bd9f4879ef533f09b9f28e4be
0xf85b691ca9c63cfd72e04d7a4fcea8c30d15d015
0x27482bb566ec0bb8ceb60efb620eec54e324d3a0
0x21b429819625ee1b2963f54ce31bbdbb851e2b62
0xba7bb922140e3d364ced86daf39b58ca1a4b4b44
0x017a7d6d1dd982be91a5cb5ec3f39b0525376875
0x78c0a5ca2149f6d8f800fbe33030867e5962f268
0xb54a60bc745be730130ca0d232280aec19424966
0x546bda9fc7013120b6bcf88d87f9c61f289735a9
0xf28d95389e8dcb5a8ef726b2bc1b68505ac15a21
0xe2bae51d63549a577729c4f6b94c2c0cf82cb799
0xe170f6fa50034fca2b8e245fd7ebd55b95f90d5b
0x519bab280d2255bbc1a9f53bc6807f49cb7aeeec
0x77321ba9ea9e588453ab006af4092dc603edec23
0x92e50034439db73aab36634cace1da45d213c77a
0x842ca458c1e0ca6f0eb24f87530be788e18adc33
0x664ee8bdb83358df5bbb5194ea6b1b4a9104b0e9
0x57df552d9a9447ef954a305453bcc22ec4ad5753
0x13c3ad942a09321d033a174453f79f2db47af874
0x85fc976af1091e95d34538e7250e74d5b20a26ac
0x6b73caf86603ba01f422a5b65ce025417f1876cd
0x2c1909b9b4fc32f0c4929558cc2517d84d429d95
```


<details>


![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839881/w3v48dmmfwq17ojrhph6.png)
https://platform.arkhamintelligence.com/visualizer/entity/0xd59Fe06386D34ADb4E54F11945Cf72EaB9C60404,0x76F58De66F282b098e92D2e263878C25d711798d,0x75e840Bf2a6a385741c69f239BF5605e5659968c,0x15130D3cA687e16aaB26DBe64d00110482b3Ac64,0x9b00Ce25837d4E1B1F0Ee8e6fa5029697d7AAe68,0xdFCf5CF0C2d4214Ac92CEb2783303DbC8C3Af687,0x48db6B16dBeA2578696f5ACeB80B0358E3B0D5Af,0x2EdC3e996fA79d5Bd9f4879eF533F09b9f28E4Be,0xF85B691CA9c63CFD72E04d7A4fCEa8c30d15D015,0x27482bB566eC0bB8ceb60efb620EEc54e324D3A0,0x21B429819625Ee1B2963f54CE31bBdBB851E2b62,0xBA7BB922140E3D364CEd86DAF39B58Ca1a4b4B44,0x017A7d6d1dd982Be91a5cB5ec3f39b0525376875,0x78c0A5CA2149f6d8f800Fbe33030867e5962F268,0xB54a60Bc745be730130CA0d232280aec19424966,0x546bdA9fC7013120b6BCF88D87f9C61F289735a9,0xF28D95389E8dCb5a8ef726b2bC1B68505AC15A21,0xE2BAe51D63549a577729C4f6b94C2C0Cf82cB799,0xE170f6Fa50034FCA2b8e245fd7EBD55B95f90D5B,0x519Bab280D2255bbc1A9f53Bc6807F49CB7AEeec,0x77321ba9ea9e588453AB006af4092Dc603eDEc23,0x92E50034439dB73Aab36634CacE1dA45d213C77a,0x842ca458C1E0Ca6F0EB24f87530Be788E18ADc33,0x664Ee8Bdb83358df5bBB5194Ea6b1B4a9104B0e9,0x57dF552d9A9447ef954A305453BcC22Ec4aD5753,0x13C3AD942A09321d033a174453F79F2db47Af874,0x85fC976af1091E95d34538E7250e74d5b20a26Ac,0x6b73CAf86603Ba01f422A5b65ce025417f1876Cd,0x2c1909B9B4Fc32F0c4929558Cc2517d84D429d95?flow=self&positions=%7B%22its-me-emma-dee%22%3A%7B%22fx%22%3A-53%2C%22fy%22%3A-5%7D%2C%220x9b00Ce25837d4E1B1F0Ee8e6fa5029697d7AAe68%22%3A%7B%22fx%22%3A-36%2C%22fy%22%3A6%7D%7D&sortDir=desc&sortKey=time&usdGte=0.1

On chain analysis
Similar amount on same Binance Cex deposit on same day
Wash trading volume on ZKSYNC 

For example:
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839882/u4xxl41chljg5xys03ky.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839884/ydal7k0uzxhqzhwebqvc.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839885/w8qvizgjflsrx6adigy1.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839887/znxfrzu2cobygha71tw7.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839888/mu3grsdxqt0hm9auyb5s.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839890/gvjoxwfjttbvvv3lcz5z.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839891/trcxena7ptbsa1lic1la.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839893/uxb18n0pmgns8i6kxjcp.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839894/cayttkspg8pwp7ymhvsf.png)


Similare layer zero days
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839896/a0j7eainm6lcorcd5dbh.png)

ZKSYNC Bridge Date very smilar 

```
1 0x76f58de66f282b098e92d2e263878c25d711798d 2023-08-02 
2 0x75e840bf2a6a385741c69f239bf5605e5659968c 2023-06-10 
3 0x15130d3ca687e16aab26dbe64d00110482b3ac64 2023-06-13 
4 0x9b00ce25837d4e1b1f0ee8e6fa5029697d7aae68 2023-06-13 
5 0xdfcf5cf0c2d4214ac92ceb2783303dbc8c3af687 2023-06-13 
7 0x2edc3e996fa79d5bd9f4879ef533f09b9f28e4be 2023-06-13 
8 0xf85b691ca9c63cfd72e04d7a4fcea8c30d15d015 2023-06-13 
9 0x27482bb566ec0bb8ceb60efb620eec54e324d3a0 2023-06-09 
10 0x21b429819625ee1b2963f54ce31bbdbb851e2b62 2023-06-09 
11 0xba7bb922140e3d364ced86daf39b58ca1a4b4b44 2023-06-09 2023-04-24 
12 0x017a7d6d1dd982be91a5cb5ec3f39b0525376875 2023-06-09 
13 0x78c0a5ca2149f6d8f800fbe33030867e5962f268 2023-06-09 
14 0xb54a60bc745be730130ca0d232280aec19424966 2023-06-09 
15 0x546bda9fc7013120b6bcf88d87f9c61f289735a9 2023-06-09 
16 0xf28d95389e8dcb5a8ef726b2bc1b68505ac15a21 2023-06-09 
17 0xe2bae51d63549a577729c4f6b94c2c0cf82cb799 2023-08-07 2023-07-31 2023-03-25 
18 0xe170f6fa50034fca2b8e245fd7ebd55b95f90d5b 2023-06-11 
19 0x519bab280d2255bbc1a9f53bc6807f49cb7aeeec 2023-06-11 
20 0x77321ba9ea9e588453ab006af4092dc603edec23 2023-06-11 
21 0x92e50034439db73aab36634cace1da45d213c77a 2023-06-11 
22 0x842ca458c1e0ca6f0eb24f87530be788e18adc33 2023-06-11 
23 0x664ee8bdb83358df5bbb5194ea6b1b4a9104b0e9 2023-06-11 
24 0x57df552d9a9447ef954a305453bcc22ec4ad5753 2023-06-11 
25 0x13c3ad942a09321d033a174453f79f2db47af874 2023-06-11 
26 0x85fc976af1091e95d34538e7250e74d5b20a26ac 2024-04-28 2023-06-11 
27 0x6b73caf86603ba01f422a5b65ce025417f1876cd 2024-04-28 2023-06-09 
28 0x2c1909b9b4fc32f0c4929558cc2517d84d429d95 2023-06-13
```

</details>

## Cluster 10

13 first addresses are linked by the same CEX deposit wallet. (OKX)
0x0b9A7D9d5348143C6C8054Cf4ccc4061cEC6F29e

```
0x8e00d744ffcb7f49f4bc735ceb805c441d7fe256
0xe9042f1f7d1643e99c3a9d068ab27016dcfb1a5b
0xb6e9179e84afad68b94af65cd3b41fd158b53474
0xe5885fff1f2455ce2ff84b74bac51184e1e6be55
0x57c17a6703855c1d64424d40d014967f623af6ab
0xb93ad6d8f6c49a06b25532378e3c77ebfa8f209f
0x58665af74632f3411cb7d93aff9df6718584e9a1
0xf1fe705fc4e8ed4e64e4e0a8a0a0e2c8ad03c73f
0x24869f992e320ff31068e114745b249f5fda3223
0x6b90277db05b6d81536e85408595414ce0c24adb
0xbcbe8e5c223d5849b809689fb4174ceadeb2d6e6
0x38035b7b33921a58cb5154d7f87503cb2a81a03c
0xad4934e4926cbfdcfda310e141d5c106727aa4fa
0xf684608d99872b9e7112f03ddbc605cd68429154
0x130ed5007192ba6da2e394dc317d0d15235a2be6
0xab5a7ba3d59f1ce9c91ffb196406d49fa6fad3d8
0xfb9aac7d07f148f14e2f814f217c819c28d2e33e
0xba3d0c6a4dacde85a812cfd18e7111b6069d1f34
0x80d2dbf74453f71adeb22a99cb996f7af1afa262
0xb8b95005bd5c73b0da5f373d7a3208e0c1ba4b63
0xfe6e4b07c3fed0a9c9a22c40625768e3d5d6371d
0x39ce2440e86caef8793bcac10c02aa3e06569921
0x85b6388d5dbbd989b0dfb42ae2ff038dd2e8b65c
0x7163c17fb672a232f58df25a37de02a518b35471
0x1b3358a70a4e3b7481b1bb4b38a7798e708a3af5
0x8aca18d346eaf98ff1fc609b6043a60677f2cb14
0x9b4b186b07a6997747b95f40cc30bf941f47e5c1
0x446f0dab5f326624978c86cbc3d7a7d504d87e43
0xcec15153527b682cd6afdc2ba8785999eb44c92c
0xce58de72c8cb712be36718ef08e097e0f2845046
```


<details>


![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839897/yjf90kmjxxoyfpngcmav.png)
https://platform.arkhamintelligence.com/visualizer/entity/0x0b9A7D9d5348143C6C8054Cf4ccc4061cEC6F29e,0x8e00d744FFCb7f49F4bc735Ceb805C441D7FE256,0xe9042f1f7d1643E99C3a9d068AB27016DCfB1A5B,0xb6E9179e84aFAD68b94Af65CD3B41fd158B53474,0xe5885FFF1f2455CE2fF84B74bac51184E1E6BE55,0x57c17A6703855C1d64424D40d014967F623aF6ab,0xb93aD6d8F6c49a06B25532378e3c77EbFa8f209f,0x58665af74632F3411cB7d93Aff9Df6718584E9a1,0xF1fe705FC4E8Ed4E64e4E0A8a0a0e2C8aD03C73f,0x24869F992e320ff31068e114745b249f5FdA3223,0x6b90277dB05b6D81536e85408595414Ce0C24ADb,0xbcBE8E5C223D5849B809689fb4174cEADEb2d6E6,0x38035b7B33921A58CB5154D7F87503cB2A81A03c,0xaD4934e4926CBFDcfDA310e141D5c106727aA4fA,0xf684608d99872b9E7112F03DdbC605Cd68429154,0x130eD5007192ba6DA2E394dC317d0d15235a2BE6,0xAb5A7bA3d59F1Ce9c91FFB196406d49Fa6Fad3d8,0xFB9aAc7d07f148f14E2F814F217c819c28d2e33e,0xba3d0c6a4DAcde85a812cFD18e7111B6069d1f34,0x80D2dBf74453F71adeB22A99cb996F7AF1Afa262,0xB8B95005Bd5C73B0DA5F373d7a3208E0C1BA4B63,0xFe6e4B07C3fEd0A9C9a22c40625768e3d5d6371d,0x39cE2440E86CAeF8793bcAc10c02Aa3e06569921,0x85B6388d5dbBD989B0dFB42aE2fF038dd2E8B65C,0x7163c17Fb672A232F58df25a37de02A518b35471,0x1B3358A70A4E3b7481b1BB4B38a7798E708A3aF5,0x8ACA18D346EaF98fF1fC609b6043A60677f2cb14,0x9B4B186b07a6997747B95F40Cc30BF941f47e5C1,0x446F0Dab5f326624978C86cbC3D7A7D504D87e43,0xcec15153527b682Cd6Afdc2bA8785999eB44c92C,0xCE58de72c8CB712be36718eF08E097e0F2845046?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

Layer Zero Days
We observe 3 main batches of wallets that will give us directions on where to look
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839899/xoqve1dgqmkwzu7f3ed4.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839900/hdujzxaapxkzqcmdxt9p.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839902/t6ygoy456t1yi1r6laug.png)

Lot of Similar on chain behavior
bsc stg lock
```
1 0x8e00d744ffcb7f49f4bc735ceb805c441d7fe256 2023-06-04   
2 0xe9042f1f7d1643e99c3a9d068ab27016dcfb1a5b 2023-06-29   
3 0xb6e9179e84afad68b94af65cd3b41fd158b53474 2023-06-28   
4 0xe5885fff1f2455ce2ff84b74bac51184e1e6be55 2023-06-28   
5 0x57c17a6703855c1d64424d40d014967f623af6ab 2023-06-29   
6 0xb93ad6d8f6c49a06b25532378e3c77ebfa8f209f 2023-09-22   
8 0xf1fe705fc4e8ed4e64e4e0a8a0a0e2c8ad03c73f 2023-10-20   
11 0xbcbe8e5c223d5849b809689fb4174ceadeb2d6e6 2023-10-18   
12 0x38035b7b33921a58cb5154d7f87503cb2a81a03c 2023-09-10   
13 0xad4934e4926cbfdcfda310e141d5c106727aa4fa 2023-06-28   
14 0xf684608d99872b9e7112f03ddbc605cd68429154 2023-06-04   
15 0x130ed5007192ba6da2e394dc317d0d15235a2be6 2023-06-04   
16 0xab5a7ba3d59f1ce9c91ffb196406d49fa6fad3d8 2023-06-03   
17 0xfb9aac7d07f148f14e2f814f217c819c28d2e33e 2023-06-04   
19 0x80d2dbf74453f71adeb22a99cb996f7af1afa262 2023-06-29   
20 0xb8b95005bd5c73b0da5f373d7a3208e0c1ba4b63 2023-09-07   
21 0xfe6e4b07c3fed0a9c9a22c40625768e3d5d6371d 2023-06-04   
22 0x39ce2440e86caef8793bcac10c02aa3e06569921 2023-06-28   
24 0x7163c17fb672a232f58df25a37de02a518b35471 2023-06-28   
25 0x1b3358a70a4e3b7481b1bb4b38a7798e708a3af5 2023-06-04   
27 0x9b4b186b07a6997747b95f40cc30bf941f47e5c1 2023-06-28   
28 0x446f0dab5f326624978c86cbc3d7a7d504d87e43 2023-09-20   
29 0xcec15153527b682cd6afdc2ba8785999eb44c92c 2023-06-04   
30 0xce58de72c8cb712be36718ef08e097e0f2845046 2023-06-04   
```

On many wallets, only 2 STG have been locked. 
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839903/znof2kr3l9ddkd86bqk2.png)

We will analyze more deeply to find common patterns, it seems to be a daily routine farmer on many wallets.
for exemple this pattern 
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839905/ytaisqccjfo414cqythq.png)

on va suivre la chaine: 
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839906/p3vexy23zukclbeqkak8.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839908/knladgxee0iwmltzh34u.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839909/irnzegi2yxlhlmylr2lz.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839911/dvtscytpu86cynfqnm1w.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839912/qwbyv3ssvu4zdikko0w5.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839914/g2lz3h4iwkyqd31ujwr4.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839915/wkzhraw8vrizlsvm6kf8.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839916/ozf1kbjd8by28uhzriab.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839918/skqvqlyrtzkkz73iqjll.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839919/azi8kzo84wbz93gyncou.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839921/gzz0hw4rkka8hnkaavy2.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839922/hujdwn80bjc64f6cukaj.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839924/fnykixwfj2b0jjxlcug2.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839926/gwcwe4kak6zmdi2dj6c3.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839927/u0ofiay3gtnoc4dc41av.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839929/mjx8femug2hny03gznx3.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839931/s1tsym1pq2fayamov50l.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839932/fyqpomrjdlctwjsxtcfs.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839934/touqitqathoixpdcukzu.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839935/mgglqi4bj0ibhxkhuqty.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839937/wkkmagfpi0mtdjwyrsxf.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839938/ni7gtq4tj3rpsqjhwrxf.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839940/c0s6udgxbxpyfduah5zs.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839941/egygg0fyazqyncaitcrk.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839943/q2nnfisvo368bekwdxza.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839945/wnoyfraxvw3qnqvtdk7f.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839946/betgfxdclerks0uqpidu.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839948/oiqa1jwxilqn4b16mg7c.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839949/wfixsik8syjrxwft3f9v.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839950/zaum5d8ozblv3tq0ujrr.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839952/dwhsuuhaxsyfawvratva.png)



zksync
```
1 0x8e00d744ffcb7f49f4bc735ceb805c441d7fe256 2024-02-25 2023-08-06 
2 0xe9042f1f7d1643e99c3a9d068ab27016dcfb1a5b 2024-02-28 2023-07-21 
3 0xb6e9179e84afad68b94af65cd3b41fd158b53474 2024-03-01 2023-07-23 
4 0xe5885fff1f2455ce2ff84b74bac51184e1e6be55 2024-03-03 2023-07-30 2023-07-23 
5 0x57c17a6703855c1d64424d40d014967f623af6ab 2024-02-28 2023-07-19 
6 0xb93ad6d8f6c49a06b25532378e3c77ebfa8f209f 2024-03-09 2023-11-16 
10 0x6b90277db05b6d81536e85408595414ce0c24adb 2024-02-27 2023-08-07 
13 0xad4934e4926cbfdcfda310e141d5c106727aa4fa 2024-03-03 2023-07-23 
14 0xf684608d99872b9e7112f03ddbc605cd68429154 2024-02-24 2023-08-06 
15 0x130ed5007192ba6da2e394dc317d0d15235a2be6 2024-02-25 2023-08-06 
16 0xab5a7ba3d59f1ce9c91ffb196406d49fa6fad3d8 2024-02-24 2023-08-06 
17 0xfb9aac7d07f148f14e2f814f217c819c28d2e33e 2024-02-24 2023-08-06 
18 0xba3d0c6a4dacde85a812cfd18e7111b6069d1f34 2024-02-27 2023-08-07 
19 0x80d2dbf74453f71adeb22a99cb996f7af1afa262 2024-02-28 2023-07-23 
20 0xb8b95005bd5c73b0da5f373d7a3208e0c1ba4b63 2024-03-03 2023-11-16 
21 0xfe6e4b07c3fed0a9c9a22c40625768e3d5d6371d 2024-02-25 2023-08-06 
22 0x39ce2440e86caef8793bcac10c02aa3e06569921 2024-03-01 2023-07-23 
23 0x85b6388d5dbbd989b0dfb42ae2ff038dd2e8b65c 2024-02-27 2023-08-07 
24 0x7163c17fb672a232f58df25a37de02a518b35471 2024-03-01 2023-07-23 
25 0x1b3358a70a4e3b7481b1bb4b38a7798e708a3af5 2024-02-24 2023-08-06 
26 0x8aca18d346eaf98ff1fc609b6043a60677f2cb14 2024-03-08 2023-11-16 
27 0x9b4b186b07a6997747b95f40cc30bf941f47e5c1 2024-03-02 2023-07-23 2023-07-23 
28 0x446f0dab5f326624978c86cbc3d7a7d504d87e43 2024-02-26 2023-08-07 
29 0xcec15153527b682cd6afdc2ba8785999eb44c92c 2024-02-24 2023-08-06 
30 0xce58de72c8cb712be36718ef08e097e0f2845046 2024-02-26 2023-08-06 
```


</details>

## Cluster 11

11 first addresses are linked by the same CEX deposit wallet. (Kucoin) 
0x1A3Fd7f8CEa7AE69C82643979234a95C4Ff2E91e

**TLDR**
SImilar layerzerodays
Similar STG lock date
Same MEXC/KUCOIN deposit Address
BTC.B traderjoe farming same date 

```
0xf17bd2cb625342a85c5d1aeed348fda6e5fb29a3
0xb569f21eb2450868b52710cfc7d9d8b3c28e591b
0x053e1fe30e5dbdb1592f6334edc52d6cad61e62c
0xe1a455f397c84728d215db8e8d2206bdc94f9e97
0x8ac4c075c852da4b31b3502762b9a431142ae5c8
0x659f0e3886b1ea41d14b68857f12d4922b4a9f1c
0xc44b836d8bef83a0e1db472ab5d5b5a2abf35e05
0x0bca47a0952dc724bd58ff43895d909fdaf059b5
0x26079110e26fea2a0953e7059f65954d610a513c
0x632a25c80506dee22547908a51682ab3b5e1e022
0xb7c7394feb40d2e8e51a36eb287eb655d7f71a6f
0x0904fba1912d5fb284886fb82443516c1046c8e6
0x865e87a645fb537da7a5e3fdb9e1dc6b60e273a0
0xc26a8444e853d8489e0bdab04670cfffaad116fd
0x8ce9662e31fcdce40d1226ffc05b33fc6824bb24
0x160d3a8ccb081c04497c8c5e2eb2d1ef572a0b56
0x39cb1fe05c3346821e07dd30e6b5328414cb7949
0xd547bf20a617152f31a038f34e4183852a6d41b1
0x1ecdee4265c1bfa2d3f46c623df04f25e9603aa9
0x032cedbcd22c2eb5cb471936daa4dc867a23f041
0x50c33fd72718d3394a98268bf9753481ebbbe548
0x6ed077d8d6255f2c383fe26bb108bb8fa4d81fa0
```

<details>
  
  
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839954/ihjzpe8vaqcx4abhpmyc.png)
https://platform.arkhamintelligence.com/visualizer/entity/0x1A3Fd7f8CEa7AE69C82643979234a95C4Ff2E91e,0xF17bd2cb625342A85C5d1AEeD348FdA6e5fB29A3,0xB569F21Eb2450868B52710cfC7D9d8b3c28e591B,0x053E1fE30E5DBdb1592f6334EDC52D6Cad61e62C,0xe1A455F397c84728d215Db8E8d2206Bdc94F9E97,0x8aC4c075c852dA4b31b3502762B9A431142aE5c8,0x659F0e3886b1EA41D14b68857F12d4922B4A9f1C,0xC44b836d8bef83A0e1Db472ab5D5B5A2Abf35e05,0x0Bca47A0952Dc724bd58fF43895D909Fdaf059B5,0x26079110e26FEA2A0953e7059f65954D610A513c,0x632a25c80506dee22547908a51682aB3b5e1e022,0xb7C7394Feb40d2E8e51A36EB287EB655d7F71a6f,0x0904fBa1912D5FB284886fb82443516C1046c8e6,0x865E87a645FB537Da7a5e3fdB9E1DC6b60e273A0,0xc26a8444e853d8489E0BDAb04670cfFFAad116fd,0x8Ce9662E31FcDCE40D1226FFC05B33fc6824bb24,0x160d3a8CCb081C04497C8C5e2EB2d1EF572A0b56,0x39cB1Fe05C3346821e07dd30e6B5328414Cb7949,0xd547Bf20a617152f31A038f34e4183852a6D41b1,0x1ECdEE4265c1Bfa2d3F46C623df04F25E9603aa9,0x032CEDBCD22c2EB5Cb471936daa4DC867a23f041,0x50c33FD72718D3394A98268Bf9753481eBbBe548,0x6Ed077D8d6255F2c383FE26Bb108bB8FA4d81Fa0?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

Similar layerzerodays
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839956/mb6bswcmkkuharlipg4v.png)

Similar STG lock 

eth stg lock

```
1 0xf17bd2cb625342a85c5d1aeed348fda6e5fb29a3 2022-11-30   
3 0x053e1fe30e5dbdb1592f6334edc52d6cad61e62c 2022-11-26   
4 0xe1a455f397c84728d215db8e8d2206bdc94f9e97 2022-11-26   
5 0x8ac4c075c852da4b31b3502762b9a431142ae5c8 2022-11-26   
6 0x659f0e3886b1ea41d14b68857f12d4922b4a9f1c 2022-11-26   
7 0xc44b836d8bef83a0e1db472ab5d5b5a2abf35e05 2022-11-26   
8 0x0bca47a0952dc724bd58ff43895d909fdaf059b5 2022-11-26   
9 0x26079110e26fea2a0953e7059f65954d610a513c 2022-11-26   
10 0x632a25c80506dee22547908a51682ab3b5e1e022 2022-11-26   
11 0xb7c7394feb40d2e8e51a36eb287eb655d7f71a6f 2022-11-27   
13 0x865e87a645fb537da7a5e3fdb9e1dc6b60e273a0 2022-11-26   
14 0xc26a8444e853d8489e0bdab04670cfffaad116fd 2022-11-26   
16 0x160d3a8ccb081c04497c8c5e2eb2d1ef572a0b56 2022-11-26   
17 0x39cb1fe05c3346821e07dd30e6b5328414cb7949 2022-11-26   
18 0xd547bf20a617152f31a038f34e4183852a6d41b1 2022-11-27   
19 0x1ecdee4265c1bfa2d3f46c623df04f25e9603aa9 2022-11-27   
20 0x032cedbcd22c2eb5cb471936daa4dc867a23f041 2022-11-27  
```

arbi stg lock

```
1 0xf17bd2cb625342a85c5d1aeed348fda6e5fb29a3 2022-11-17   
2 0xb569f21eb2450868b52710cfc7d9d8b3c28e591b 2022-11-17   
3 0x053e1fe30e5dbdb1592f6334edc52d6cad61e62c 2022-11-17   
4 0xe1a455f397c84728d215db8e8d2206bdc94f9e97 2022-11-17   
5 0x8ac4c075c852da4b31b3502762b9a431142ae5c8 2022-11-17   
6 0x659f0e3886b1ea41d14b68857f12d4922b4a9f1c 2022-11-17   
7 0xc44b836d8bef83a0e1db472ab5d5b5a2abf35e05 2022-11-17   
8 0x0bca47a0952dc724bd58ff43895d909fdaf059b5 2022-11-17   
9 0x26079110e26fea2a0953e7059f65954d610a513c 2022-11-17   
10 0x632a25c80506dee22547908a51682ab3b5e1e022 2022-11-17   
11 0xb7c7394feb40d2e8e51a36eb287eb655d7f71a6f 2023-07-12   2023-05-29   2022-11-20   
12 0x0904fba1912d5fb284886fb82443516c1046c8e6 2022-11-21   
13 0x865e87a645fb537da7a5e3fdb9e1dc6b60e273a0 2022-11-17   
14 0xc26a8444e853d8489e0bdab04670cfffaad116fd 2022-11-17   
15 0x8ce9662e31fcdce40d1226ffc05b33fc6824bb24 2023-08-12   2023-07-12   2023-06-03   2022-11-20   
16 0x160d3a8ccb081c04497c8c5e2eb2d1ef572a0b56 2023-08-12   2023-07-12   2023-06-03   2022-11-20   
17 0x39cb1fe05c3346821e07dd30e6b5328414cb7949 2023-08-12   2023-07-12   2023-06-03   2022-11-20   
18 0xd547bf20a617152f31a038f34e4183852a6d41b1 2023-07-12   2023-05-30   2022-11-20   
19 0x1ecdee4265c1bfa2d3f46c623df04f25e9603aa9 2022-11-21   
20 0x032cedbcd22c2eb5cb471936daa4dc867a23f041 2023-07-12   2023-06-03   2022-11-21   
21 0x50c33fd72718d3394a98268bf9753481ebbbe548 2023-06-18   2022-11-20   
22 0x6ed077d8d6255f2c383fe26bb108bb8fa4d81fa0 2023-08-12   2023-06-03   2022-11-23   
```

Polyhedra (ZK) same cex deposit address
MEXC   
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839957/lspd4qzwiaxjsrgy8nlk.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839959/ntzrmfzhswr6fqchbmad.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839961/i30ir1hi9rzkq27afo9x.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839962/kui7lzci8lhvob0pzfn7.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839964/hczbcfwjraqtwla23moi.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839965/bbknvp3fvkz5wtonpyp7.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839966/rbud9ppfa4emnoqxc99l.png)

KUCOIN   
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839968/uotkp1jzf6zu8o2dylbs.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839969/i32iwretke6pdwjvlfym.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839970/qohuo039egxaxmge3gui.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839972/mxzzyfaa21sg5lq6onkp.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839973/f9ehkrnyuafnn3cpb4nx.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839975/z9qucnduffxtip31yxdu.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839976/azolch20yzytowhql9qs.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839977/gwbe5c5haxau8eyhkj8w.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839979/wnvkcapdzsjdfnnqvx73.png)

Traderjoe BTC.b farming on ALL WALLETS, same date !!!
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839980/zfyxvjzbkhrjj1g0ahk9.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839982/kipziieyejrwaoyp1m2z.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839983/eqc3tu8bgz24ojqvrpso.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839985/tgd9zqanytd9e2ujmpal.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839986/wpqjaozz0yvuscf8aqut.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839988/snt4hmdlbdtbxnijzllo.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839989/nhgq71yuxatruzytlafz.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839990/bgqlqkim4awcxd2kndir.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839992/mgkjl4fmiudg8qlhybs6.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839993/zheh3big7wnobp9euued.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839995/pcvzc67ex4llds9a1zzr.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839996/laxhfpmoufmvvcaomlge.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839998/n1ls6zru4hyregdezt1u.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716839999/bynlrxirsyr222cgejp3.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840001/lsd77drg8zwtcphpurio.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840002/h9lkqt0gwfulqwm12ybz.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840004/pfnjanpaxoxnfldr0s9e.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840006/faycfqna7o0p0undiqkr.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840007/ui026ae7xokjfuwih79a.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840009/bdszqvcx51zsntwd2zjn.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840010/gfgn3i19pvwrlu5vklwt.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840012/deqbpgnadzd2bfsumql0.png)


</details>

## Cluster 12

All addresses are linked by the same CEX deposit wallet. (Binance) 
0x1C7d67fe362956230ed18841537d3cEd9B4Cb230

**TLDR**
Stargate Wash trading thanks to Binance account
Same CEX deposit address

```
0x764d4d060b7fc5b3f3b62a77efaa9f61c1d7fed1
0x3b05fb7f3701352728e06c429d967d5b6f26c8ce
0xce86fc84af756e20fb6c45456db97f58cd1e1c88
0xbc12414c014f251d9dd004b7be2fff19800e4993
0xc7a7a708214b7c40f83a025226478362dd3a7ad8
0x182a0683df58bc2763a5bb44c8c06c55d7187c9e
0xb69cdfd78aa7be8ecae982af92a4ac22dda60ad5
0x724ac2c3d7b4ab46d90a44a143a9a854253fa1c9
0x1da3b14cb6c27726e38adb3fafc91180371ad148
0x5c915e90f99f58f2953d25a88506f7e30af2565e
0xad12a6972ef411e97be99db18eeefe40a7ca1f4e
0xffd07610e17417302d457128620adb87a903e3d2
0x5c4d6b20b502fcf33b05f3ecc02e73811e4c7d19
0xfae43078538f40d44f201aaf0255f703e909e158
0xe38429b664de066f7ccca925c03382654810cfbd
0xc3b0917391c21b4babfda0580a09a3610d0efb09
0xe2b8735e12dce1f53096dfd3bea4ed2b18cc8a1d
0xbad84d73a16199293f48b8e94217f0994c713de1
0x50e4d22eb78ff27da0252857043ac96bc2e51f03
0x003042604c750a38a379a0823fa809e8bcc879c5
```

<details>


![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840013/csusco1daihvxtfixvgz.png)


https://platform.arkhamintelligence.com/visualizer/entity/0x1C7d67fe362956230ed18841537d3cEd9B4Cb230,0x764d4d060b7fc5b3f3b62a77efaa9f61c1d7fed1,0x3b05fb7f3701352728e06c429d967d5b6f26c8ce,0xce86fc84af756e20fb6c45456db97f58cd1e1c88,0xbc12414c014f251d9dd004b7be2fff19800e4993,0xc7a7a708214b7c40f83a025226478362dd3a7ad8,0x182a0683df58bc2763a5bb44c8c06c55d7187c9e,0xb69cdfd78aa7be8ecae982af92a4ac22dda60ad5,0x724ac2c3d7b4ab46d90a44a143a9a854253fa1c9,0x1da3b14cb6c27726e38adb3fafc91180371ad148,0x5c915e90f99f58f2953d25a88506f7e30af2565e,0xad12a6972ef411e97be99db18eeefe40a7ca1f4e,0xffd07610e17417302d457128620adb87a903e3d2,0x5c4d6b20b502fcf33b05f3ecc02e73811e4c7d19,0xfae43078538f40d44f201aaf0255f703e909e158,0xe38429b664de066f7ccca925c03382654810cfbd,0xc3b0917391c21b4babfda0580a09a3610d0efb09,0xe2b8735e12dce1f53096dfd3bea4ed2b18cc8a1d,0xbad84d73a16199293f48b8e94217f0994c713de1,0x50e4d22eb78ff27da0252857043ac96bc2e51f03,0x003042604c750a38a379a0823fa809e8bcc879c5?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

Layerzerodays
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840015/bhsrjv2xoosn8bjzzmod.png)

Stargate Wash trading thanks to Binance account:
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840017/gj09kfy6mmxrftmuiqna.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840018/q2xxquxyvv1xzfxehnaq.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840020/wzn5ksndst5zo5vxwrle.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840022/dzbvqivdkzvee6wbassp.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840023/pvc4yxhhekn9ca0kears.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840025/zcobqrgvq8kl34tkhuht.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840027/nphena7amt8e64duxgbc.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840029/yyg4pgsiinyibyuhaimm.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840030/lwjyqyxgkz03seitlptc.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840032/klgjxyprxfqxwb6eanyz.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840034/zgo0wnbb5dzxbhss6snb.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840036/e28av2h1kan4np6es8nb.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840037/wlidd0hunhvs9ybze559.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840039/zgbwefiiyorskyabldgp.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840041/wheiw33afgw1fut2kysm.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840043/mcquy624sqp3priug10h.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840044/phhixvutahypgu0qhh6x.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840046/cclxympdrnczv654z1ns.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840048/f7uofhjbrmpwgjrvwbqu.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840050/wowilwhvlv6t8u2vhpj9.png)



</details>

## Cluster 13 

15 fisrt addresses are linked by the same CEX deposit wallet. (OKX)
0x390ca2DF6A0B8607B81EC07E420Dd730F39A9AA7

**TLDR**
Linea Native bridge same date 

```
0x2600544f150db80438004be4bbc7114aa21615a9
0x3ae8e01536785f47eaa87ff1542ee509671ec8df
0xde765b9d2a5b5b8e9e952da5ac3e43b011cdb289
0x90d4aa3bf552999e7ca9ce89cf8e6fada4c69aab
0x2bba0ec0af14a633693ed73d36b5ab2eea4ea888
0x22338f6036bd28d10e4180735fae96346283c886
0x11a9ad3e94ce7a21f5bf14174e328bc7c5eeb6fa
0x782f17e27322fb4d8a331f58f5d0e25dd0484a23
0x0611133571496e814294cd17067f4c14eee7d04f
0xeb3843caa198420fbbe5a023541a43bc9e8ec01c
0x6762391958d87d5fa4d1252997615412a6a70651
0x3fa4a5319fe925770965f5a4d12361cceb39311e
0x805a58e0d9b797249dee2e19f6d5e7e6fffda769
0x4ca644b441749ac1b29a26f2189ad7c29435c20a
0xf72390c118188d6706bb303606c06457f198bf79
0xfcace87fb6e1dfeeda16533cd41ee2852a0f14b2
0x058b9c1ba7cded2150335464ca1951cf1ce38fde
0x3b5c6db44c2e63309e3c570b0f7c3569d2371ffa
0xcf30a573e3ac5e855fe23bf85ff78ef62db9e52b
0x10bea37df7bd76a48ca5fef2f124fb177cc8683d
0x0aacf7dd8fbd05aab11e3c6f170f9213b701baef
0x391ecebb351714ec949795f63d093b05a124c3a2
0x7aa819e41693e9f435ec7da54e8cfd08d03dba6b
```



<details>
  

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840052/kpttwjtqpwmf8shpmact.png)

https://platform.arkhamintelligence.com/visualizer/entity/0x390ca2DF6A0B8607B81EC07E420Dd730F39A9AA7,0x2600544f150db80438004be4bbc7114aa21615a9,0x3ae8e01536785f47eaa87ff1542ee509671ec8df,0xde765b9d2a5b5b8e9e952da5ac3e43b011cdb289,0x90d4aa3bf552999e7ca9ce89cf8e6fada4c69aab,0x2bba0ec0af14a633693ed73d36b5ab2eea4ea888,0x22338f6036bd28d10e4180735fae96346283c886,0x11a9ad3e94ce7a21f5bf14174e328bc7c5eeb6fa,0x782f17e27322fb4d8a331f58f5d0e25dd0484a23,0x0611133571496e814294cd17067f4c14eee7d04f,0xeb3843caa198420fbbe5a023541a43bc9e8ec01c,0x6762391958d87d5fa4d1252997615412a6a70651,0x3fa4a5319fe925770965f5a4d12361cceb39311e,0x805a58e0d9b797249dee2e19f6d5e7e6fffda769,0x4ca644b441749ac1b29a26f2189ad7c29435c20a,0xf72390c118188d6706bb303606c06457f198bf79,0xfcace87fb6e1dfeeda16533cd41ee2852a0f14b2,0x058b9c1ba7cded2150335464ca1951cf1ce38fde,0x3b5c6db44c2e63309e3c570b0f7c3569d2371ffa,0xcf30a573e3ac5e855fe23bf85ff78ef62db9e52b,0x10bea37df7bd76a48ca5fef2f124fb177cc8683d,0x0aacf7dd8fbd05aab11e3c6f170f9213b701baef,0x391ecebb351714ec949795f63d093b05a124c3a2,0x7aa819e41693e9f435ec7da54e8cfd08d03dba6b,0x9075e2b4f1778bf527ca6605a98f720f3954dd5f?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

Layerzerodays
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840053/kfwoeaiqp4hg1iyapsis.png)



Same transaction on Orderly with the same source chain, same possible start date suitable for 18 out of 20 wallets, and the other date suitable for the remaining two wallets (but linked to cex deposit address):

![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/e0804d71-6fb0-45ba-aa91-aa360e39d823)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/6f0ec529-2f3a-4a34-8055-fe6256b6ef9a)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/2d3b3308-6df8-4306-bf11-26fe086bc500)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/ce9ee81c-9174-45fe-95b6-43356397237c)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/5cfc5a51-6f72-4982-9224-cf51ad52452c)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/e9451d3e-52f2-4cca-88ed-d05f4168fec9)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/eef2f2d9-79eb-4e94-879b-606284df3fbb)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/e54abb38-0b9b-42ec-bf73-8e05e89a8829)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/d4ee34ed-f401-4c3d-89ef-4a996215d951)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/86ab3f9e-afb5-4435-83bd-9d0d7204fa61)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/5bd903cb-f23c-4087-b0c3-38ace816a863)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/61aad958-e0b7-4c02-b384-406d2f6f3b0f)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/d96447c9-8f21-42a1-b4f3-fe242eb6dc7b)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/42c73cbb-5184-4f6a-9625-0fd11206f2cf)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/4e1048b9-cb69-42ca-b602-0959bd060b27)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/f1ca8f18-2129-4846-a39f-d6d6a33fa394)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/9dc8b155-3216-4773-95d4-de7f1856b8d5)







Linea native bridge

```
1 0x2600544f150db80438004be4bbc7114aa21615a9 2023-07-26 
2 0x3ae8e01536785f47eaa87ff1542ee509671ec8df 2023-07-22 
3 0xde765b9d2a5b5b8e9e952da5ac3e43b011cdb289 2023-07-22 
4 0x90d4aa3bf552999e7ca9ce89cf8e6fada4c69aab 2023-07-22 
6 0x22338f6036bd28d10e4180735fae96346283c886 2023-07-22 
7 0x11a9ad3e94ce7a21f5bf14174e328bc7c5eeb6fa 2023-07-22 
8 0x782f17e27322fb4d8a331f58f5d0e25dd0484a23 2023-07-22 
9 0x0611133571496e814294cd17067f4c14eee7d04f 2023-07-22 
10 0xeb3843caa198420fbbe5a023541a43bc9e8ec01c 2023-07-22 
11 0x6762391958d87d5fa4d1252997615412a6a70651 2023-07-22 
12 0x3fa4a5319fe925770965f5a4d12361cceb39311e 2023-07-22 
14 0x4ca644b441749ac1b29a26f2189ad7c29435c20a 2023-07-22 
15 0xf72390c118188d6706bb303606c06457f198bf79 2023-07-22 
16 0xfcace87fb6e1dfeeda16533cd41ee2852a0f14b2 2023-07-22 
17 0x058b9c1ba7cded2150335464ca1951cf1ce38fde 2023-07-23 
18 0x3b5c6db44c2e63309e3c570b0f7c3569d2371ffa 2023-07-22 
19 0xcf30a573e3ac5e855fe23bf85ff78ef62db9e52b 2023-07-23 
20 0x10bea37df7bd76a48ca5fef2f124fb177cc8683d 2023-07-22 
21 0x0aacf7dd8fbd05aab11e3c6f170f9213b701baef 2023-07-23 
22 0x391ecebb351714ec949795f63d093b05a124c3a2 2023-07-23 
23 0x7aa819e41693e9f435ec7da54e8cfd08d03dba6b 2023-07-23 
```


</details>

## Cluster 14 

CEX address 

```

0xff392e83a03f1870b67522b48bf515af9ec124e0
0xba3a6834b0a63accaf549df47e103ad20bb24790
0x7cd1c3c1df5c7823d535b05c1729d819f77708f9
0xa48a8bc0cddd25fb412b698947e78a1a654a44fb
0x952ea1788fd32e2c54ac36000a348bd2a09d7d4a
0x26cc2c944c4cffa64ce7b3802a71445aedadc88d
0xf1dacb55a999edbeeb650ffc473205fab048c68e
0x5af376c0569085882c1050e06b24fe847e5c0ac6
0x20b163cc91733b54fddc7a28d9d97062b0d9befd
0xfecb5afbc756a866ea67572350a4078913ecfe76
0xdab2c2c884bed87e3ab008d365965e96d663b85e
0x1086cc94f3960e7e676fa13ffc75a876f4b64fbc
0x04db1cd8de77e2c5bdc79a57e7c09fbf4debe1a5
0x85da7e0205e9aaab7f85e837a396455aa8076b39
0xbe5bb9a4f8e624db61462c1ce0a156b6fa0cc15d
0x1770d754b4c573a31ed89d587aa05bb847982b90
0xc8fde0cd13fdfb00546203b0457058c5a5ce233e
0xe977c0e8c689b073f4e7c3122789b6e6db98f48e
0xe20fa7405c507b6116313db21a4c433c6e1e453e
0x6125791e34a5b45c69ca78fe9df1177f84fd3fae
0x89e72be12a7811c436667874a0842a3124908e3e
0x44b16ee7cd1b077a466e7313e7ec49d104503d8a
0x3ecdd7256d7fb82c976b75afb1d02dd497aabea8
0x2b20eb02b5a90d80f8176b02a35e770cd49a9991
0xed322d17419876a528fa361d4e233ddbbd7eeb65
0x4bd29ad21a57e076ad3fbfb4dcafa053155dff4e
0xa4fe0e805cf3f75e3e5a55d5baca097e6cbab5b7
0x4fe9ce347b21b364448943f0f00f476280f85c55
0x50bf8eac4ef20ac6b2b2c3d14c808a40ed44c1a1
0x019c233261fe26baa5a66ee3e840f8dc7cc433eb
0x909d2ddb0e72f26a551e784b528d52897fb3cb27
0x2fe2ae8209530e0ab809ee96a10ced3ae1311d73
0x9c50d01c356a172d754c5a583435a552401970d5
0x554de9ec9b67da361d79a316f866e66158f19851
0x702c331b04637bdd0a64ab05fd8a33657c95a4b3
0xdb130d9edb097773b45e60978aa5771ab61046f0
0xaa257cc014752cc690595dcaac438c86f7face2d
0x96266ab667484c4167ae9011a6ab454ed8c91240
0x08ccf6bb513d5cd16de3206a5e0f87725918fc49
0xd2c3b7b0d791d638b22dca82da6ed68974635939

```

<details>



![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840058/rtfm7uzgt3aiq96letcw.png)

</details>

## Cluster 15

The first 7 addresses are linked by the same Binance CEX deposit:
0x09A11feBfF82042699CcFE93ae4AF4965198Bc27

**TLDR**
Same Layer Zero activity days.
Same CEX deposit address.
Same Stargate lockup amount, on the same date.

```
0x5eb1b7b2ef9ce6e523985375b910b879da321bc6
0x8e3a87c8503faffc3845c0e958c590a30952a2b4
0x1e4c701bd9734826f0ff206009e1e2b8284324fa
0xa25aa0e97ba46d02cafc0c5750e726533a2e07f2
0x71263dacc983cb4aaa57bb398e03d1ddd1d760a1
0xef99e86121c4bb1ce0a02fb0207aa9219392088e
0x2ba226018757c3e3cb531b0d85a63fa4dfce0856
0x06c22c7768e6f4fdd11f2d74bb07f8279f7ac63e
0xb065e3247afafba37b98209bc62195fb6e980c8f
0x15af8d0d3df4c6b1c1d93f9119fbb94ea6973ba6
0x39486e8b16424a3a8050ca710265620c3d2e17fd
0x244cbcf5a7d9e3271422fc76d6ae7a3a2a0e9d09
0x3fb92bd83a30681ef87d5cceabf3269d0655a9f1
0x2ca8886c71cb5c0b0b01c6c8749497cf85b4b974
0x2686da9a830f9fd1a4c6e840f3542de0b9d54002
0x8c9df0438ff434fae90ee9ad6225c1538aa75311
0xa390762d2ada9f850400dc627c3d5ce419aa2854
0x5b3a5d5e25be3b2376c43e59663fda4503a17443
0x7d5eef85e3147b99131d9b60d1f3ca8455cdb721
0xaafbaec081ed11b692c4e993fe77e308b50c8cfc
```


<details>



Unquestionably, on Arkham, it is clear that we are dealing with a cluster of 20 addresses.


![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840060/synzuk53swgemmedezxe.png)
https://platform.arkhamintelligence.com/visualizer/entity/0x5Eb1b7B2ef9CE6e523985375B910B879dA321bC6,0x8e3a87c8503FAFfc3845c0E958c590A30952A2b4,0x1E4C701bD9734826F0FF206009e1E2B8284324FA,0xA25Aa0E97ba46D02Cafc0C5750e726533A2E07f2,0x71263dACC983Cb4aAa57bB398E03D1ddd1D760a1,0xEF99E86121C4Bb1ce0A02fB0207aa9219392088e,0x2bA226018757C3E3cb531B0D85a63fA4dfCe0856,0x06c22c7768e6F4Fdd11F2d74bb07F8279F7AC63e,0xB065e3247afAfbA37b98209bC62195fB6e980C8F,0x15AF8D0d3df4C6B1C1d93f9119fbB94ea6973bA6,0x39486e8b16424a3A8050CA710265620c3d2e17FD,0x244CBCf5A7d9e3271422Fc76d6AE7a3a2a0E9D09,0x3FB92BD83a30681EF87d5cCeABF3269d0655a9F1,0x2CA8886C71cB5c0b0B01C6c8749497Cf85B4B974,0x2686dA9a830F9fD1a4C6e840F3542de0b9D54002,0x8c9df0438fF434fAe90EE9AD6225C1538AA75311,0xa390762d2adA9f850400Dc627C3D5ce419aa2854,0x5B3A5D5e25BE3b2376C43E59663FdA4503a17443,0x7D5eef85E3147b99131d9b60d1F3CA8455CDB721,0xaafbAec081eD11b692C4E993fE77e308b50c8CFC?flow=self&positions=%7B%22zuoan150%22%3A%7B%22fx%22%3A-83%2C%22fy%22%3A4%7D%2C%220x2686dA9a830F9fD1a4C6e840F3542de0b9D54002%22%3A%7B%22fx%22%3A-31%2C%22fy%22%3A-35%7D%2C%220x8c9df0438fF434fAe90EE9AD6225C1538AA75311%22%3A%7B%22fx%22%3A22%2C%22fy%22%3A29%7D%2C%220x5Eb1b7B2ef9CE6e523985375B910B879dA321bC6%22%3A%7B%22fx%22%3A-35%2C%22fy%22%3A-20%7D%2C%220x71263dACC983Cb4aAa57bB398E03D1ddd1D760a1%22%3A%7B%22fx%22%3A-48%2C%22fy%22%3A-8%7D%7D&sortDir=desc&sortKey=time&usdGte=0.1

On chain analysis:
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840061/onmrwsndopnp93hmjbnm.png)
13 of these wallets started farming Layer Zero on the same day.

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840063/sxbtg186hyiepikmirqb.png)
3 started farming within only a 10-minute difference!

Regarding on-chain behaviors, we notice similarities. 
Looking at when they made deposits, the date of 2023/07/05 is common for all from the gen 0. More specifically, the $STG are received and deposited between 1 AM and 5 AM, creating a chain:

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840064/hcu1hvhhugsjzi9sbgob.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840066/tjzfpi6xr9erfancrghx.png)

Looking at the originating address:
https://bscscan.com/tx/0xcd8e88b27f1c59d05960589dbe33fd3c1fc372204103fe4119e5e97f96657cdf

We find 0x71263dACC983Cb4aAa57bB398E03D1ddd1D760a1, and from this address:
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840067/ffuxlhxnz55krtvnyoyr.png)

We trace back to: 0x8e3a87c8503FAFfc3845c0E958c590A30952A2b4
(https://bscscan.com/tx/0x91437ea4a643ee322e2dd572a4550b845f65027872465b449ead2eaa79fdf5cf):
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840069/iofratzx9mv9gwkqjfik.png)

etc etc…

All gen 1 and 2 wallets have the same amount of STG deposited and the same unlock time. Same deposit period…
It cannot be a coincidence! 

</details>

## Cluster 16

The first 7 addresses are linked by the same Kucoin CEX deposit:
0x13645493baDBEA2cC67e83f92eff7bBFc820124D

```
0xcdcacc1623428893b5e5460e3a1e2811a23ecbf2
0x5ccd93a30be7cbbbd32fabfc7bf8e0ad59239c4e
0xd2eb1fc07318f07bfb109cd1cc62be12d74d30ce
0xff42ae25b73c245fd5dee535d098b65ea7dc9d05
0x9759f8f96e54b8d166859e1fc4081819d4c3d0ad
0x35cf73070c709f4d0b45a1b2060fd91e5f02c19d
0xc73b4f316e31569a28f3730fed8af7b6623f1314
0x22e45db423c0974de0f5f2dde836519d1a173e5f
0x465fbece3182eac3f2d07916ba63a8ad9ae4d049
0xd146c0c79bc5bba7d624086eeebae19d01e7bdd3
0xed834b19348f69ce3f5a32d9b6f485bf359242dc
0xc7cda73dc62d249ddb02179a8b609e313db68c47
0x1381596e9711fa5bc5fb2144002f7dcdd96ca6f8
0xd712014756d1939cc28d9dccaf69d809f46e9985
0xe92b05b112a79f398a41d403945452f25415d099
0xc50d0c8474862c5a0a8438057ccb98b2947eb40b
0xf694bce69fc21eed7cf6f9f31866324b4162d540
0x8d4318e216e0a310974be68438872bd35d7e888d
0x2ae9d32b5c242ca88cd649c688d7648870b6ab3d
0x618b5be4b2c9c913783336321409d6ba5392e056
0x7729e207c1b6e59f339ee1eef4fc5200232c6e9d
0x97aaeada4af107dd030ae84fc6be6b1db6bed10f
0x48be6ae9cb888141fbd1dc7c6ef208109521b11f
0x667958fefc62eca961dac1795577b54ec32d4337
0xf136ef21bac2da012328ba79da8840683543d8a7
0x1e2e671a87aad52cd889f7ac144ea20e2ed0c490
0xdb2a14f3052ee802a2057f8c59e0e27624f61761
0xcc992cc074a9bfea85f3eb02964ab49fcab317a1
0x28341b10bfb264a3dea16f74d9fdecc5c12f3b3a
0xca033d2fa80ff58d470582d4810e1620ab2475fd
0x8f1cb6168112695041acbbdecbf0e91546a9c08c
0xde54629b1d4ef12ae12f3bfa44b526c6a4a04f2b
0x5e24798d05065ffc4ad1022726ca998f92b67135
0x0780469ce3ae3ad82d689a0affa46da37a4eb4f3
0xca4773c16885e6f2ea655afcb6b8d2be329b03b7
0x710758e8058039bff15d97adcda9c15ec5ae20d2
0x36dac34ea1c95c48f1f0f31bf745147b0023a42c
```


<details>
  

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840071/yp6iatpwxqslwr8e8ohk.png)


https://platform.arkhamintelligence.com/visualizer/entity/0xCDcaCC1623428893b5E5460E3a1E2811A23ecbF2,0x5CcD93a30be7cbBBD32Fabfc7Bf8E0aD59239c4e,0xd2eB1Fc07318F07BFb109cd1cc62be12d74d30cE,0xff42AE25b73C245FD5deE535D098B65Ea7DC9d05,0x9759f8f96e54B8d166859E1fc4081819d4C3D0AD,0x35cF73070C709F4d0b45a1b2060Fd91e5F02c19d,0xc73b4f316E31569a28f3730fed8AF7b6623f1314,0x22E45db423c0974dE0F5f2dDE836519D1a173E5F,0x465FBecE3182eaC3F2D07916ba63a8Ad9ae4D049,0xd146c0c79BC5bbA7d624086eEEBAe19d01E7Bdd3,0xED834b19348f69CE3f5a32D9B6f485BF359242dC,0xC7CdA73dc62D249dDb02179A8b609e313Db68C47,0x1381596e9711fA5BC5Fb2144002F7DCdD96CA6f8,0xD712014756d1939Cc28D9dCCAf69d809f46e9985,0xe92B05B112A79f398A41d403945452f25415D099,0xC50D0c8474862c5a0A8438057CCB98B2947eB40B,0xf694BcE69Fc21eED7cf6F9F31866324B4162d540,0x8d4318e216E0a310974bE68438872bd35d7E888d,0x2aE9D32B5C242Ca88cD649C688D7648870B6AB3D,0x618B5Be4B2c9C913783336321409d6Ba5392e056,0x7729e207C1B6e59F339Ee1Eef4fc5200232C6E9d,0x97AAeaDA4af107dd030ae84Fc6bE6B1Db6BEd10f,0x48be6ae9cb888141FBd1Dc7C6eF208109521b11f,0x667958FeFC62ECa961DAC1795577b54ec32d4337,0xF136ef21bac2Da012328bA79Da8840683543D8a7,0x1e2E671A87AaD52CD889F7Ac144EA20e2ed0C490,0xDB2A14f3052eE802a2057F8c59e0e27624F61761,0xcC992Cc074a9BfEA85F3Eb02964aB49FCAb317A1,0x28341b10Bfb264A3DEa16F74d9fDecC5C12f3b3A,0xCA033D2Fa80Ff58d470582d4810E1620Ab2475fd,0x8f1cB6168112695041acbbdEcbf0e91546a9c08c,0xdE54629b1d4EF12Ae12F3BFA44b526c6a4A04f2B,0x5e24798d05065ffc4ad1022726CA998f92b67135,0x0780469CE3Ae3aD82D689A0affA46Da37A4eb4F3,0xcA4773C16885E6F2eA655aFCb6B8D2BE329B03B7?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

No doubt about it on Arkham, we are definitely dealing with a cluster; the addresses have interacted many times amongst themselves. Let's look more in detail on-chain.

L0 days: 
5 on day 344, 1 on day 345 thus groups of 6,
10 on days 540/541,
8 on days 546/547,
8 between days 551 and 558,
the rest are scattered.
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840073/sng9enwvq6spbfx8agzh.png)

Looking at the first address in our cluster
https://debank.com/profile/0xcdcacc1623428893b5e5460e3a1e2811a23ecbf2/history?chain=arb&token=0x6694340fc020c5e6b96567843da2df01b2ce1eb6_STG

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840075/gjgikilkwsmqtax5fusn.png)

We look at where STG comes from
- 0x2ae9d32b5c242ca88cd649c688d7648870b6ab3d (gen1):
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840077/arycf6yis9jvmjvkmbdy.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840078/j0ypcxvmi7jhvaq4dbwc.png)

- 0x465fbece3182eac3f2d07916ba63a8ad9ae4d049 (gen 1 too)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840080/mceazbt5dkb4o4zkk0qu.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840081/yfnx7dgro4wg2kupsr9h.png)

0x710758e8058039bff15d97adcda9c15ec5ae20d2 (same behavior)
0x36dac34ea1c95c48f1f0f31bf745147b0023a42c (same behavior)
0xd712014756d1939cc28d9dccaf69d809f46e9985 (gen 1, same behavior)
0xe92b05b112a79f398a41d403945452f25415d099 (gen1, non-whole USDC amount and some purchase via OpenOcean but deposit too on Stargate of the STG)
​​0x35cf73070c709f4d0b45a1b2060fd91e5f02c19d (same CEX deposit, non-whole USDC amount and some purchase via ODOS but deposit too on Stargate of the STG)
0x22e45db423c0974de0f5f2dde836519d1a173e5f (gen 1, no USDC purchase, direct lock)
⇒ Same behavior, buying STG using a generally whole amount of USDC through Open Ocean and Slingshot then lock. (not the same date but same behavior)

Initial wallet received 90 STG from 0x48be6ae9cb888141fbd1dc7c6ef208109521b11f (gen 2) which itself initiates similarly:

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840083/exrqudffjkxh7clllj9u.png)

Now, if we look at L0scan, we can see that all the wallets from gen0, except for one (0xcdcacc1623428893b5e5460e3a1e2811a23ecbf2), have a transaction on Abracadabra Money between Friday, June 16, 2023, and Saturday, June 17, 2023:
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840084/z7zejcalckl416fdsja2.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840086/dwriczqddoyrbwg9kmff.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840087/oiwgxq3rxxowc50axeqc.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840089/ahu1jk33hwyqwzc8mmyl.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840091/rkk1mwjbxpohtndrxycr.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840092/v4janqrabsdkp05tfhby.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840094/rjtvikiqjcsho17ufiiv.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840096/ktgtyvkdf2jv79ttb2ik.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840097/mumrmx8f5gy7essnvev6.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840099/ajwfppncbn6rttqyeiui.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840101/ejwf2pc8v4vvx14pngws.png)

Additionally, they all made about twenty DeFi Kingdoms transactions on either Friday the 16th or Saturday the 17th (before or after the Abracadabra transaction, depending on the wallet):

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840102/jz5qqt7tnurr2y1wqpb0.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840104/k7og27keuldd6vzjbz61.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840106/himpo3p4fafzvqzgdlxm.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840108/qv4vilnnuuemnarc16v7.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840110/cc2wuwssaqrx3qe8fqwy.png)


</details>

## Cluster 17 

14 first address linked to this wallet
0x326C1475BCE07e9929797C35107baa3dabEA709B

**TLDR**
STG stacking loop on polygon 
same STG lock date 
Same Starknet native bridge 

```
0x326c1475bce07e9929797c35107baa3dabea709b
0xf833c34a795c0b5612af027e23800e8090c64934
0x54cee5080bfd348e2601a36c146a5dcfa7d8b106
0xe56426b87637b5f516c9a4b6b1ce1b914ff197c7
0x1a7cb54e27dbbcbf5b3c24c91f36ba9d922f0b92
0x61fd3f38d60effd953b31e531fb80eeaa37a285c
0x9a5350aaeb4f3a5d896783b4c122919a7d0f9f83
0x0c7f9dfe5f484dc75eedbb76d1fcdfc8970d0cb7
0x64de89a86ee0c666952319e162cf3c5224d45566
0xe205473109564210b726d5227ea56c92c4eb7ae7
0xf0579b201b2baecdd6472eb044d9b96f6d314779
0x0fd32cfe822823b7c01ee22fff31d27c6f6b1a8f
0x6c15b0b3ee98c39c390c1108fa3410f9dacb0ffd
0xdaf393b0082922d75465c2a08ba6f93f47c54918
0xccbf77fa01ea919a599eb8d0a68d12a3e277a5d2
0x09f31c0aee729ba208971f07bed903b0d0135e4f
0xff758cb857571ba5fe7891cdece84346c698ec26
0xb9fbebc86634184448742c918b127672071a6f19
0x834684ddb8c11eb58fddf1159e9c74953b892cfe
0x9a9b64f79e9f2ff806da3e912f826941b39404c2
0x8abe5c1b066b30069838e8ba35f2e4b02db15d64
0x875484c305e532a485ae6f79bab05e4677c15be5
0xa5bedade8c873b871d08f2d4b1684a9bd6945ba7
0x2f6c8ad9b90f03f1444f8512e30f48dd225f0dbd
0xacbd8887d3d14c90573453074e7098a909a3fa15
0xf793f9ebbfc6470835c7cdaf83c9788a445cea13
0x565a4eb5da4621c0d6032e4bfb3a5068ecc9ddb4
0xaedb26f3d279529c7670f2761ffea889f4c1798b
0x8f55cd4e6d20db42dbd868865686027dd346b97c
0x8c6a9e2006bd71989967854cc5fc9dafdeadf64c
0x6a21b81376ef4759f2635a8f6f3c9858cea457a8
0x0cb470a536e6e48333f7182cc7fabc945a2cd93b
0xdcd993c9482fa22a873c85a7018044106e1d6fa2
0xec753095b07f476a07846e14775025f3de52038b
0xb383c276d3db85a58866f6cd1ea949db9cee2723
0xd0261878928ada35a3fc58c9d34caa753b9e6306
0x21a9e6f106f4d4247db9462ebf2c9c4241578da7
0x93da1d0d77e7483fb199cecd0b2077a58ab9abc1
0x300a1410c148458e50fd1eabaabd3cd94a576b20
0x1a76d23b5051d6489ffde65b7722ecc40eddd4f7
0x7b991594ec3f0128db02cc7affb39d9f7a56fd83
0x49e4e78a657bc92566d9aab0b762ec62f25e6a09
0x55ff014e09019a4e962b8dd1cf32d4a81f50ada9
```


<details>
  

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840113/lvsvpisur916czf3xbpb.png)

https://platform.arkhamintelligence.com/visualizer/entity/0x326C1475BCE07e9929797C35107baa3dabEA709B,0xF833c34a795C0b5612AF027e23800E8090C64934,0x54CEE5080BFd348e2601A36c146A5DcFA7D8B106,0xE56426b87637B5F516C9a4B6b1CE1b914Ff197C7,0x1a7cb54e27dbBCBF5b3C24C91f36BA9d922f0b92,0x61FD3F38d60efFD953b31e531fB80EeAa37A285c,0x9a5350aaeB4f3A5D896783b4C122919A7d0f9F83,0x0c7F9dfe5F484dC75EEdbb76d1fcdFc8970d0cb7,0x64DE89A86ee0c666952319E162Cf3c5224d45566,0xE205473109564210b726D5227Ea56c92c4eb7ae7,0xf0579b201B2baeCdD6472EB044D9b96F6d314779,0x0FD32cfe822823b7C01ee22FFF31D27C6f6B1A8f,0x6C15B0b3eE98c39C390c1108fa3410F9dAcB0fFD,0xDAf393B0082922d75465C2A08Ba6F93F47c54918,0xccBf77fA01eA919A599EB8d0A68d12a3e277A5D2,0x09F31C0aEe729Ba208971f07BED903b0d0135e4f,0xff758cb857571Ba5FE7891cDeCE84346c698EC26,0xB9FbEbc86634184448742C918B127672071A6f19,0x834684DdB8C11EB58fDDf1159E9C74953B892CfE,0x9a9B64F79E9f2ff806DA3E912f826941b39404C2,0x8AbE5C1B066b30069838e8BA35F2E4B02db15d64,0x875484C305e532a485aE6f79bAb05e4677c15bE5,0xA5Bedade8C873B871d08f2d4b1684a9BD6945ba7,0x2f6c8ad9b90f03F1444F8512e30f48dd225F0Dbd,0xAcbD8887d3D14C90573453074e7098A909a3fA15,0xF793F9EBBFC6470835C7Cdaf83C9788A445Cea13,0x565A4eb5DA4621C0D6032e4bFB3A5068ECC9Ddb4,0xAedb26F3D279529c7670F2761FFeA889F4c1798b,0x8f55Cd4E6d20dB42dBd868865686027DD346B97c,0x8c6A9E2006BD71989967854cc5Fc9dafDEadf64c,0x6a21b81376ef4759f2635a8F6f3C9858ceA457A8,0x0cb470a536e6E48333F7182Cc7faBC945A2Cd93b,0xdcd993c9482fA22a873c85a7018044106E1D6FA2,0xEc753095B07F476A07846E14775025F3de52038B,0xB383c276D3Db85A58866f6Cd1Ea949DB9cEE2723,0xd0261878928AdA35A3FC58C9D34CAa753b9E6306,0x21a9e6f106f4D4247dB9462ebf2C9C4241578Da7,0x93da1d0d77E7483FB199ceCD0B2077a58aB9aBC1,0x300A1410c148458E50Fd1eAbAABD3cd94A576B20?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

39 wallets ranked between 90k and 280k.

L0 DAY: all wallets are between 507 and 530: 4 at 507/508, 7 at 516/517, 3 at 524, 4 at 529...

The first five have 20 STG locked on Polygon (same unlock time ending) (the sixth one a slightly different number of STG but same characteristics):
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840114/pq2ehrgnyf23ccvrwemc.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840116/pul4j255dplgerjasjht.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840117/ptxxslsxxptx5zfhy6td.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840119/iptddrxbaerf9koaozof.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840120/mqo08rhfdv6zxpq881if.png)

They all have the Stargate allocation on Polygon, only the amount changes. Let’s look at the transactions, starting from the first address (0x326c1475bce07e9929797c35107baa3dabea709b):
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840121/d748eivzzumqgikglkrx.png)

We look at where the STG originates from (0x326c1475bce07e9929797c35107baa3dabea709b), another wallet from the cluster:
[image](https://github.com/altaccounteth/report_layerzero/assets/151371773/2bd6ae95-d64f-4395-a186-4cdb0078491b)

same
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840123/eca05asihhgfx3sqovr8.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840124/zxzikpfpt8tvb1kva4yf.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840126/phhhlfuoegwsx04t1kwv.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840127/year3bdbb0wqammvftp3.png)

=> 0x1a76d23b5051d6489ffde65b7722ecc40eddd4f7, so let's dig!
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840129/zzdehyuu2xakyc4aeeia.png)
in the cluster 
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840131/tn62wrxq5gqcabevjlwl.png)
same
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840132/aqh8jz9iyqcm5rmpvxxd.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840134/y6p0vm6uxwbhsrpobn0l.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840136/iyacbrrjrh0ueaxixbos.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840137/yzczqcj3ucvjdebi3pih.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840139/bczemqh4cryxk5vww5eg.png)

Well, the outgoing transaction is split into two parts, so 0x8f55cd4e6d20db42dbd868865686027dd346b97c remains to be addressed later (it's in the cluster).
We focus on the address that sent the 567 STG (it's in the cluster):

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840140/ep6wwdeavnlwpdtfmkhy.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840142/eitt5a3cujetrbdt9vdf.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840143/ulomdw6alltyng83aicn.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840145/qov09ul9onaxsbnpsnn4.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840146/qwulrzfijq71jgnagklj.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840148/h90fh8ohqxgykb8symbc.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840149/xfyjmswpt03feypc697y.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840151/ebhri26nzsvgxju0pvbu.png)

We end up back at a CEX.

We revisit the one we left on standby, 0x8f55cd4e6d20db42dbd868865686027dd346b97c:
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840152/b9jq2r5idh7oscdliazd.png)

This time we go in the other direction (we look at where the transaction is going), the destination address is in the cluster:

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840154/ir5yugdllcjwjsk9rqc0.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840155/fkoxl68akckthtzxekgi.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840157/wzbhfbvt0m7dgpkvhhpv.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840158/f1owtoxwvuasnuzmqyp4.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840160/imzavbrobcyryphkk0hh.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840161/dnde74htetxnqx0n1x2u.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840163/wwxz1fujigogfgkywd3z.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840164/fjnulej9noqf5wuwlycd.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840166/vqods4ps5jbwi3ez1nsb.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840167/auc8kiugunfwa1bofhgo.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840169/ltu1g1t3lmnhimf2bbzc.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840170/rdfrjzfpf6mkp4l6onlz.png)


STARKNET NATIVE BRIDGE

```
1 0x326c1475bce07e9929797c35107baa3dabea709b 2023-09-15 
2 0xf833c34a795c0b5612af027e23800e8090c64934 2023-09-15 
3 0x54cee5080bfd348e2601a36c146a5dcfa7d8b106 2023-09-15 
4 0xe56426b87637b5f516c9a4b6b1ce1b914ff197c7 2023-09-15 
5 0x1a7cb54e27dbbcbf5b3c24c91f36ba9d922f0b92 2023-09-15 
6 0x61fd3f38d60effd953b31e531fb80eeaa37a285c 2023-09-15 
7 0x9a5350aaeb4f3a5d896783b4c122919a7d0f9f83 2023-09-14 2023-09-12 
8 0x0c7f9dfe5f484dc75eedbb76d1fcdfc8970d0cb7 2023-09-15 
10 0xe205473109564210b726d5227ea56c92c4eb7ae7 2023-09-14 2023-09-12 
11 0xf0579b201b2baecdd6472eb044d9b96f6d314779 2023-09-14 
12 0x0fd32cfe822823b7c01ee22fff31d27c6f6b1a8f 2023-09-15 
13 0x6c15b0b3ee98c39c390c1108fa3410f9dacb0ffd 2023-09-14 
14 0xdaf393b0082922d75465c2a08ba6f93f47c54918 2023-09-15 
15 0xccbf77fa01ea919a599eb8d0a68d12a3e277a5d2 2023-09-15 
16 0x09f31c0aee729ba208971f07bed903b0d0135e4f 2023-09-15 
17 0xff758cb857571ba5fe7891cdece84346c698ec26 2023-09-14 
18 0xb9fbebc86634184448742c918b127672071a6f19 2023-09-15 
19 0x834684ddb8c11eb58fddf1159e9c74953b892cfe 2023-09-14 
20 0x9a9b64f79e9f2ff806da3e912f826941b39404c2 2023-09-14 
21 0x8abe5c1b066b30069838e8ba35f2e4b02db15d64 2023-09-14 2023-09-12 
22 0x875484c305e532a485ae6f79bab05e4677c15be5 2023-09-14 
23 0xa5bedade8c873b871d08f2d4b1684a9bd6945ba7 2023-09-14 
24 0x2f6c8ad9b90f03f1444f8512e30f48dd225f0dbd 2023-09-14 
25 0xacbd8887d3d14c90573453074e7098a909a3fa15 2023-09-14 
26 0xf793f9ebbfc6470835c7cdaf83c9788a445cea13 2023-09-15 
27 0x565a4eb5da4621c0d6032e4bfb3a5068ecc9ddb4 2023-09-15 
28 0xaedb26f3d279529c7670f2761ffea889f4c1798b 2023-09-14 
29 0x8f55cd4e6d20db42dbd868865686027dd346b97c 2023-09-14 
30 0x8c6a9e2006bd71989967854cc5fc9dafdeadf64c 2023-09-14 
31 0x6a21b81376ef4759f2635a8f6f3c9858cea457a8 2023-09-14 
32 0x0cb470a536e6e48333f7182cc7fabc945a2cd93b 2023-09-14 
33 0xdcd993c9482fa22a873c85a7018044106e1d6fa2 2023-09-14 
34 0xec753095b07f476a07846e14775025f3de52038b 2023-09-14 
35 0xb383c276d3db85a58866f6cd1ea949db9cee2723 2023-09-14 
36 0xd0261878928ada35a3fc58c9d34caa753b9e6306 2023-09-15 
37 0x21a9e6f106f4d4247db9462ebf2c9c4241578da7 2023-09-14 
38 0x93da1d0d77e7483fb199cecd0b2077a58ab9abc1 2023-09-14 
39 0x300a1410c148458e50fd1eabaabd3cd94a576b20 2023-09-14 
```

ZKSYNC NATIVE BRIDGE

 ```
1 0x326c1475bce07e9929797c35107baa3dabea709b 2023-10-03 2023-07-20 
2 0xf833c34a795c0b5612af027e23800e8090c64934 2023-10-03 2023-07-20 
3 0x54cee5080bfd348e2601a36c146a5dcfa7d8b106 2023-10-03 2023-07-19 
4 0xe56426b87637b5f516c9a4b6b1ce1b914ff197c7 2023-10-03 2023-07-19 
5 0x1a7cb54e27dbbcbf5b3c24c91f36ba9d922f0b92 2023-10-03 2023-07-19 
6 0x61fd3f38d60effd953b31e531fb80eeaa37a285c 2023-10-03 2023-07-20 
7 0x9a5350aaeb4f3a5d896783b4c122919a7d0f9f83 2023-09-28 2023-08-27 
8 0x0c7f9dfe5f484dc75eedbb76d1fcdfc8970d0cb7 2023-10-03 2023-07-19 
9 0x64de89a86ee0c666952319e162cf3c5224d45566 2023-10-03 2023-07-20 
10 0xe205473109564210b726d5227ea56c92c4eb7ae7 2023-09-28 2023-08-27 
11 0xf0579b201b2baecdd6472eb044d9b96f6d314779 2023-09-28 2023-08-27 
12 0x0fd32cfe822823b7c01ee22fff31d27c6f6b1a8f 2023-09-28 2023-08-27 
13 0x6c15b0b3ee98c39c390c1108fa3410f9dacb0ffd 2023-10-01 2023-07-19 
14 0xdaf393b0082922d75465c2a08ba6f93f47c54918 2023-10-03 2023-07-19 
15 0xccbf77fa01ea919a599eb8d0a68d12a3e277a5d2 2023-10-03 2023-07-19 
16 0x09f31c0aee729ba208971f07bed903b0d0135e4f 2023-10-03 2023-07-19 
17 0xff758cb857571ba5fe7891cdece84346c698ec26 2023-09-28 2023-09-27 
18 0xb9fbebc86634184448742c918b127672071a6f19 2023-10-01 2023-07-19 
19 0x834684ddb8c11eb58fddf1159e9c74953b892cfe 2023-09-28 2023-08-27 
20 0x9a9b64f79e9f2ff806da3e912f826941b39404c2 2023-09-28 2023-08-27 
21 0x8abe5c1b066b30069838e8ba35f2e4b02db15d64 2023-09-28 2023-09-27 
22 0x875484c305e532a485ae6f79bab05e4677c15be5 2023-09-28 2023-08-27 
23 0xa5bedade8c873b871d08f2d4b1684a9bd6945ba7 2023-09-28 2023-08-27 
24 0x2f6c8ad9b90f03f1444f8512e30f48dd225f0dbd 2023-09-28 2023-08-27 
25 0xacbd8887d3d14c90573453074e7098a909a3fa15 2023-10-01 2023-07-19 
26 0xf793f9ebbfc6470835c7cdaf83c9788a445cea13 2023-10-03 2023-07-19 
27 0x565a4eb5da4621c0d6032e4bfb3a5068ecc9ddb4 2023-10-01 2023-07-19 
28 0xaedb26f3d279529c7670f2761ffea889f4c1798b 2023-09-28 2023-09-27 
29 0x8f55cd4e6d20db42dbd868865686027dd346b97c 2023-10-01 2023-07-19 
30 0x8c6a9e2006bd71989967854cc5fc9dafdeadf64c 2023-09-28 2023-09-27 
31 0x6a21b81376ef4759f2635a8f6f3c9858cea457a8 2023-09-28 2023-09-27 
32 0x0cb470a536e6e48333f7182cc7fabc945a2cd93b 2023-09-28 2023-09-27 
33 0xdcd993c9482fa22a873c85a7018044106e1d6fa2 2023-09-28 2023-08-27 
34 0xec753095b07f476a07846e14775025f3de52038b 2023-10-01 2023-07-19 
35 0xb383c276d3db85a58866f6cd1ea949db9cee2723 2023-10-01 2023-07-19 
36 0xd0261878928ada35a3fc58c9d34caa753b9e6306 2023-09-29 2023-07-19 
37 0x21a9e6f106f4d4247db9462ebf2c9c4241578da7 2023-09-28 2023-08-27 
38 0x93da1d0d77e7483fb199cecd0b2077a58ab9abc1 2023-09-28 2023-08-27 
39 0x300a1410c148458e50fd1eabaabd3cd94a576b20 2023-10-01 2023-07-19 
 ```

op stg lock 
```
1 0x326c1475bce07e9929797c35107baa3dabea709b 2023-01-25   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-11   2023-01-04   
2 0xf833c34a795c0b5612af027e23800e8090c64934 2023-01-25   2023-01-25   
3 0x54cee5080bfd348e2601a36c146a5dcfa7d8b106 2023-01-04   2022-12-26   2022-12-26   2022-12-26   
4 0xe56426b87637b5f516c9a4b6b1ce1b914ff197c7 2023-01-04   2023-01-04   2023-01-04   2023-01-04   2023-01-04   2023-01-04   
5 0x1a7cb54e27dbbcbf5b3c24c91f36ba9d922f0b92 2023-01-04   2023-01-04   2023-01-04   2023-01-04   2023-01-04   2023-01-04   2022-12-29   
6 0x61fd3f38d60effd953b31e531fb80eeaa37a285c 2023-01-10   2023-01-04   2023-01-04   2023-01-04   2023-01-04   2023-01-04   2023-01-04   
7 0x9a5350aaeb4f3a5d896783b4c122919a7d0f9f83 2023-01-24   2022-12-13   2022-12-13   2022-12-08   2022-12-07   2022-12-07   2022-12-07   
8 0x0c7f9dfe5f484dc75eedbb76d1fcdfc8970d0cb7 2023-01-04   2022-12-27   2022-12-27   2022-12-27   2022-12-27   2022-12-26   
9 0x64de89a86ee0c666952319e162cf3c5224d45566 2023-01-10   2023-01-04   2023-01-04   2023-01-04   2023-01-04   
10 0xe205473109564210b726d5227ea56c92c4eb7ae7 2023-04-20   2023-01-24   2023-01-24   2023-01-24   2022-12-13   2022-12-09   2022-12-07   2022-12-07   
11 0xf0579b201b2baecdd6472eb044d9b96f6d314779 2023-01-25   2023-01-25   2023-01-25   2022-12-21   2022-12-13   2022-12-13   2022-12-13   2022-12-13   2022-12-13   
12 0x0fd32cfe822823b7c01ee22fff31d27c6f6b1a8f 2023-01-25   2023-01-25   2023-01-25   2023-01-25   2022-12-21   2022-12-14   2022-12-14   2022-12-14   2022-12-14   
13 0x6c15b0b3ee98c39c390c1108fa3410f9dacb0ffd 2023-01-25   2023-01-25   2023-01-25   2023-01-25   2023-01-25   2023-01-25   2023-01-25   2023-01-25   2023-01-25   2023-01-25   2022-12-21   2022-12-21   2022-12-15   2022-12-15   2022-12-15   2022-12-15   
14 0xdaf393b0082922d75465c2a08ba6f93f47c54918 2023-01-04   2022-12-27   2022-12-27   2022-12-27   2022-12-27   2022-12-27   
15 0xccbf77fa01ea919a599eb8d0a68d12a3e277a5d2 2023-01-04   2022-12-26   2022-12-26   2022-12-26   2022-12-26   2022-12-26   
16 0x09f31c0aee729ba208971f07bed903b0d0135e4f 2023-01-04   2022-12-27   2022-12-27   2022-12-27   
17 0xff758cb857571ba5fe7891cdece84346c698ec26 2023-01-24   2022-12-13   2022-12-09   2022-12-09   2022-12-09   
18 0xb9fbebc86634184448742c918b127672071a6f19 2022-12-22   2022-12-22   2022-12-19   2022-12-19   2022-12-19   2022-12-19   2022-12-19   
19 0x834684ddb8c11eb58fddf1159e9c74953b892cfe 2023-01-25   2022-12-16   2022-12-13   2022-12-13   2022-12-13   2022-12-13   
20 0x9a9b64f79e9f2ff806da3e912f826941b39404c2 2023-01-25   2022-12-15   2022-12-15   2022-12-12   2022-12-12   2022-12-12   2022-12-12   
21 0x8abe5c1b066b30069838e8ba35f2e4b02db15d64 2023-01-24   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-13   2022-12-08   2022-12-08   2022-12-08   2022-12-08   
22 0x875484c305e532a485ae6f79bab05e4677c15be5 2023-01-25   2022-12-21   2022-12-21   2022-12-14   2022-12-14   2022-12-14   
23 0xa5bedade8c873b871d08f2d4b1684a9bd6945ba7 2023-01-25   2022-12-21   2022-12-13   2022-12-13   2022-12-13   
24 0x2f6c8ad9b90f03f1444f8512e30f48dd225f0dbd 2023-01-25   2023-01-25   2022-12-21   2022-12-13   2022-12-13   2022-12-13   2022-12-13   2022-12-13   
25 0xacbd8887d3d14c90573453074e7098a909a3fa15 2022-12-22   2022-12-19   2022-12-19   2022-12-19   2022-12-19   2022-12-19   2022-12-19   2022-12-16   
26 0xf793f9ebbfc6470835c7cdaf83c9788a445cea13 2022-12-26   2022-12-19   2022-12-19   2022-12-19   
27 0x565a4eb5da4621c0d6032e4bfb3a5068ecc9ddb4 2022-12-26   2022-12-19   2022-12-19   2022-12-19   2022-12-19   2022-12-19   
28 0xaedb26f3d279529c7670f2761ffea889f4c1798b 2023-01-24   2022-12-13   2022-12-08   2022-12-08   2022-12-08   2022-12-08   
29 0x8f55cd4e6d20db42dbd868865686027dd346b97c 2023-01-25   2022-12-21   2022-12-21   2022-12-14   2022-12-14   2022-12-14   2022-12-14   2022-12-14   
30 0x8c6a9e2006bd71989967854cc5fc9dafdeadf64c 2023-01-25   2022-12-15   2022-12-12   2022-12-12   2022-12-12   2022-12-12   
31 0x6a21b81376ef4759f2635a8f6f3c9858cea457a8 2023-01-24   2022-12-13   2022-12-08   2022-12-08   2022-12-08   
32 0x0cb470a536e6e48333f7182cc7fabc945a2cd93b 2023-01-25   2022-12-13   2022-12-09   2022-12-09   2022-12-09   2022-12-09   2022-12-09   2022-12-09   
33 0xdcd993c9482fa22a873c85a7018044106e1d6fa2 2023-01-25   2022-12-21   2022-12-13   2022-12-13   2022-12-13   
34 0xec753095b07f476a07846e14775025f3de52038b 2023-01-25   2022-12-21   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-15   2022-12-15   
35 0xb383c276d3db85a58866f6cd1ea949db9cee2723 2022-12-21   2022-12-16   2022-12-16   2022-12-16   2022-12-16   
36 0xd0261878928ada35a3fc58c9d34caa753b9e6306 2023-01-25   2022-12-21   2022-12-14   2022-12-14   2022-12-14   
37 0x21a9e6f106f4d4247db9462ebf2c9c4241578da7 2023-01-25   2022-12-21   2022-12-13   2022-12-13   2022-12-13   
38 0x93da1d0d77e7483fb199cecd0b2077a58ab9abc1 2023-01-25   2022-12-21   2022-12-14   2022-12-14   2022-12-14   
39 0x300a1410c148458e50fd1eabaabd3cd94a576b20 2022-12-22   2022-12-19   2022-12-19   2022-12-19   2022-12-19   2022-12-19   2022-12-19   2022-12-19   2022-12-19   
40 0x1a76d23b5051d6489ffde65b7722ecc40eddd4f7 2022-12-22   2022-12-19   2022-12-19   2022-12-19   2022-12-19   2022-12-19   
41 0x7b991594ec3f0128db02cc7affb39d9f7a56fd83 2022-12-21   2022-12-16   2022-12-16   2022-12-16   2022-12-16   2022-12-16   2022-12-16   2022-12-16   2022-12-16   
42 0x49e4e78a657bc92566d9aab0b762ec62f25e6a09 2022-12-21   2022-12-16   2022-12-16   2022-12-16   2022-12-16   2022-12-16   2022-12-15   
43 0x55ff014e09019a4e962b8dd1cf32d4a81f50ada9 2023-01-25   2023-01-25   2023-01-25   2022-12-21   2022-12-14   2022-12-14   2022-12-14   2022-12-14   
```

bsc stg lock
```
1 0x326c1475bce07e9929797c35107baa3dabea709b 2023-08-21   
3 0x54cee5080bfd348e2601a36c146a5dcfa7d8b106 2023-08-21   
5 0x1a7cb54e27dbbcbf5b3c24c91f36ba9d922f0b92 2023-08-21   
7 0x9a5350aaeb4f3a5d896783b4c122919a7d0f9f83 2023-03-22   
10 0xe205473109564210b726d5227ea56c92c4eb7ae7 2023-03-22   
11 0xf0579b201b2baecdd6472eb044d9b96f6d314779 2023-08-21   2023-03-22   
12 0x0fd32cfe822823b7c01ee22fff31d27c6f6b1a8f 2024-02-07   2023-03-22   
13 0x6c15b0b3ee98c39c390c1108fa3410f9dacb0ffd 2023-08-21   
14 0xdaf393b0082922d75465c2a08ba6f93f47c54918 2023-08-21   
17 0xff758cb857571ba5fe7891cdece84346c698ec26 2023-03-22   
18 0xb9fbebc86634184448742c918b127672071a6f19 2023-08-21   
19 0x834684ddb8c11eb58fddf1159e9c74953b892cfe 2023-03-22   
20 0x9a9b64f79e9f2ff806da3e912f826941b39404c2 2023-03-22   
21 0x8abe5c1b066b30069838e8ba35f2e4b02db15d64 2023-08-21   2023-03-22   
22 0x875484c305e532a485ae6f79bab05e4677c15be5 2023-08-21   2023-03-22   
23 0xa5bedade8c873b871d08f2d4b1684a9bd6945ba7 2023-03-22   
24 0x2f6c8ad9b90f03f1444f8512e30f48dd225f0dbd 2024-02-07   2023-08-21   2023-03-22   
26 0xf793f9ebbfc6470835c7cdaf83c9788a445cea13 2023-08-21   
28 0xaedb26f3d279529c7670f2761ffea889f4c1798b 2023-08-21   2023-03-22   
29 0x8f55cd4e6d20db42dbd868865686027dd346b97c 2023-08-21   2023-03-22   
30 0x8c6a9e2006bd71989967854cc5fc9dafdeadf64c 2023-08-21   2023-08-21   2023-03-22   
31 0x6a21b81376ef4759f2635a8f6f3c9858cea457a8 2023-03-22   
32 0x0cb470a536e6e48333f7182cc7fabc945a2cd93b 2023-03-22   
33 0xdcd993c9482fa22a873c85a7018044106e1d6fa2 2023-03-22   
35 0xb383c276d3db85a58866f6cd1ea949db9cee2723 2023-08-21   
36 0xd0261878928ada35a3fc58c9d34caa753b9e6306 2023-08-21   2023-03-22   
37 0x21a9e6f106f4d4247db9462ebf2c9c4241578da7 2023-08-21   2023-03-22   
38 0x93da1d0d77e7483fb199cecd0b2077a58ab9abc1 2023-03-22   
39 0x300a1410c148458e50fd1eabaabd3cd94a576b20 2023-08-21   
43 0x55ff014e09019a4e962b8dd1cf32d4a81f50ada9 2023-03-22   
```
polygon stg lock 

```
1 0x326c1475bce07e9929797c35107baa3dabea709b 2023-03-01   
2 0xf833c34a795c0b5612af027e23800e8090c64934 2023-03-01   
3 0x54cee5080bfd348e2601a36c146a5dcfa7d8b106 2023-02-16   
4 0xe56426b87637b5f516c9a4b6b1ce1b914ff197c7 2023-03-01   
5 0x1a7cb54e27dbbcbf5b3c24c91f36ba9d922f0b92 2023-03-01   
6 0x61fd3f38d60effd953b31e531fb80eeaa37a285c 2023-03-01   
7 0x9a5350aaeb4f3a5d896783b4c122919a7d0f9f83 2022-10-28   
8 0x0c7f9dfe5f484dc75eedbb76d1fcdfc8970d0cb7 2023-02-16   
9 0x64de89a86ee0c666952319e162cf3c5224d45566 2023-03-01   
10 0xe205473109564210b726d5227ea56c92c4eb7ae7 2022-10-28   
11 0xf0579b201b2baecdd6472eb044d9b96f6d314779 2022-12-22   
12 0x0fd32cfe822823b7c01ee22fff31d27c6f6b1a8f 2022-12-22   
13 0x6c15b0b3ee98c39c390c1108fa3410f9dacb0ffd 2022-12-22   
14 0xdaf393b0082922d75465c2a08ba6f93f47c54918 2023-02-16   2023-02-16   
15 0xccbf77fa01ea919a599eb8d0a68d12a3e277a5d2 2023-02-16   
16 0x09f31c0aee729ba208971f07bed903b0d0135e4f 2023-02-16   
17 0xff758cb857571ba5fe7891cdece84346c698ec26 2022-10-28   
18 0xb9fbebc86634184448742c918b127672071a6f19 2023-02-16   
19 0x834684ddb8c11eb58fddf1159e9c74953b892cfe 2022-10-28   
20 0x9a9b64f79e9f2ff806da3e912f826941b39404c2 2022-10-28   
21 0x8abe5c1b066b30069838e8ba35f2e4b02db15d64 2022-10-28   
22 0x875484c305e532a485ae6f79bab05e4677c15be5 2022-12-22   
23 0xa5bedade8c873b871d08f2d4b1684a9bd6945ba7 2022-12-22   
24 0x2f6c8ad9b90f03f1444f8512e30f48dd225f0dbd 2022-12-22   
25 0xacbd8887d3d14c90573453074e7098a909a3fa15 2023-02-16   
26 0xf793f9ebbfc6470835c7cdaf83c9788a445cea13 2023-02-16   
27 0x565a4eb5da4621c0d6032e4bfb3a5068ecc9ddb4 2023-02-16   
28 0xaedb26f3d279529c7670f2761ffea889f4c1798b 2022-10-28   
29 0x8f55cd4e6d20db42dbd868865686027dd346b97c 2022-12-22   
30 0x8c6a9e2006bd71989967854cc5fc9dafdeadf64c 2022-10-28   
31 0x6a21b81376ef4759f2635a8f6f3c9858cea457a8 2022-10-28   
32 0x0cb470a536e6e48333f7182cc7fabc945a2cd93b 2022-10-28   
33 0xdcd993c9482fa22a873c85a7018044106e1d6fa2 2022-12-22   
34 0xec753095b07f476a07846e14775025f3de52038b 2022-12-22   
35 0xb383c276d3db85a58866f6cd1ea949db9cee2723 2023-02-16   
36 0xd0261878928ada35a3fc58c9d34caa753b9e6306 2022-12-22   
37 0x21a9e6f106f4d4247db9462ebf2c9c4241578da7 2022-12-22   
38 0x93da1d0d77e7483fb199cecd0b2077a58ab9abc1 2022-12-22   
39 0x300a1410c148458e50fd1eabaabd3cd94a576b20 2023-02-16   
40 0x1a76d23b5051d6489ffde65b7722ecc40eddd4f7 2023-02-16   
41 0x7b991594ec3f0128db02cc7affb39d9f7a56fd83 2023-02-16   
42 0x49e4e78a657bc92566d9aab0b762ec62f25e6a09 2023-02-16   
43 0x55ff014e09019a4e962b8dd1cf32d4a81f50ada9 2022-12-22 
```


</details>

## Cluster 18


7 first address linked to CEX deposit address (BINANCE)
0x33e65f576DcA44D4042F386eF932efab4aAD1C9C

**TLDR**
same zksync bridge date
STG lock on arbitrum 
same layerzero on chain behavior 

```
0x2f91922aa4caba7ae19c1223c0007a1a598dff51
0xf366adde5b682a8e0d5e4f09663844ea95332f94
0xe59e6365e879aebf001de470e3281a4c0d6fb0c8
0x469cbdfb1f88b41aa89e9ce49af5e758ac4d1d5c
0x1e98efc80b1b71809b6ce4fa0b09f071143b2c02
0xbae2a1899e06cab91fb9251db3b2e7d31acdca44
0x19d995a031576e10e3138b92a8523b7b9fb6f6bc
0x767b97aabeb5d46a0b33e862374f24b87a7679a9
0x263d6480291fcad81f1dd3c9f5bcc08b5ac5ed1d
0xcf41fa770b2529d26bdb604cb16d61a65e74ae7a
0xb6afd7dcf48ed53fdea3d304bbb2179ee24d209c
0x4db45526d4c0cae762a2ff5e4d1ad32c5855000f
0x7a0604aa59f054f0d25d859c21222afa0086a959
0x445259622cd7453dd92d3c23ec7af004947c73ea
0x3e897e924842dab543f30352afad81e5e4886ef7
0x8f7a5c571816ed31182108a7c3046e75033f4fe0
0xf11b354a61b18b619f8f4e553fcd5db5fb64adf0
0xde1569da8f95de2ccccbfbda7d05ae5bd788a99f
0x8052e45555e66f0de48d195a4aab947578134b4a
0xbcb30d55d932a15f430a5b4553fca71e8aeee57a
0x7132becef1e3d8d4d9061598c860cae2c86197e6
```

<details>



![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840172/vzq7av5qtplvrfzfubln.png)

https://platform.arkhamintelligence.com/visualizer/entity/0x33e65f576DcA44D4042F386eF932efab4aAD1C9C,0x2f91922aa4caba7ae19c1223c0007a1a598dff51,0xf366adde5b682a8e0d5e4f09663844ea95332f94,0xe59e6365e879aebf001de470e3281a4c0d6fb0c8,0x469cbdfb1f88b41aa89e9ce49af5e758ac4d1d5c,0x1e98efc80b1b71809b6ce4fa0b09f071143b2c02,0xbae2a1899e06cab91fb9251db3b2e7d31acdca44,0x19d995a031576e10e3138b92a8523b7b9fb6f6bc,0x767b97aabeb5d46a0b33e862374f24b87a7679a9,0x263d6480291fcad81f1dd3c9f5bcc08b5ac5ed1d,0xcf41fa770b2529d26bdb604cb16d61a65e74ae7a,0xb6afd7dcf48ed53fdea3d304bbb2179ee24d209c,0x4db45526d4c0cae762a2ff5e4d1ad32c5855000f,0x7a0604aa59f054f0d25d859c21222afa0086a959,0x445259622cd7453dd92d3c23ec7af004947c73ea,0x3e897e924842dab543f30352afad81e5e4886ef7,0x8f7a5c571816ed31182108a7c3046e75033f4fe0,0xf11b354a61b18b619f8f4e553fcd5db5fb64adf0,0xde1569da8f95de2ccccbfbda7d05ae5bd788a99f,0x8052e45555e66f0de48d195a4aab947578134b4a,0xbcb30d55d932a15f430a5b4553fca71e8aeee57a,0x7132becef1e3d8d4d9061598c860cae2c86197e6?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

20 wallets ranked between 170,000 and 1,300,000.

Layer0 day: 5 wallets on day 151, 4 on days 251 or 252, 7 on days 504/505.

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840173/pauzdka6uyg9zyvkysp0.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840175/ezlngcozpb6npldif6j3.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840176/gz4kfuuj94lrqhswj12t.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840178/mx3mvt9yque0xeu32d2m.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840179/d4xgzrzkpcvhxvk6hddx.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840180/h37vhmavyjwjmjdhvkgb.png)

all addrees : arbi stg lock

```
1 0x2f91922aa4caba7ae19c1223c0007a1a598dff51 2023-03-30   
2 0xf366adde5b682a8e0d5e4f09663844ea95332f94 2023-09-17   
3 0xe59e6365e879aebf001de470e3281a4c0d6fb0c8 2023-09-17   
4 0x469cbdfb1f88b41aa89e9ce49af5e758ac4d1d5c 2023-03-31   
5 0x1e98efc80b1b71809b6ce4fa0b09f071143b2c02 2023-09-17   
6 0xbae2a1899e06cab91fb9251db3b2e7d31acdca44 2023-12-27   
7 0x19d995a031576e10e3138b92a8523b7b9fb6f6bc 2023-09-17   
8 0x767b97aabeb5d46a0b33e862374f24b87a7679a9 2023-03-30   
9 0x263d6480291fcad81f1dd3c9f5bcc08b5ac5ed1d 2023-03-31   
10 0xcf41fa770b2529d26bdb604cb16d61a65e74ae7a 2024-02-07   
11 0xb6afd7dcf48ed53fdea3d304bbb2179ee24d209c 2023-09-17   
12 0x4db45526d4c0cae762a2ff5e4d1ad32c5855000f 2023-03-31   
13 0x7a0604aa59f054f0d25d859c21222afa0086a959 2023-03-31   
14 0x445259622cd7453dd92d3c23ec7af004947c73ea 2023-03-31   
15 0x3e897e924842dab543f30352afad81e5e4886ef7 2023-04-09   
16 0x8f7a5c571816ed31182108a7c3046e75033f4fe0 2024-02-20   
17 0xf11b354a61b18b619f8f4e553fcd5db5fb64adf0 2023-03-31   
18 0xde1569da8f95de2ccccbfbda7d05ae5bd788a99f 2024-02-20   
19 0x8052e45555e66f0de48d195a4aab947578134b4a 2023-03-31   
20 0xbcb30d55d932a15f430a5b4553fca71e8aeee57a 2024-02-07   
221 0x7132becef1e3d8d4d9061598c860cae2c86197e6 2023-09-17   
```

zksync native bridge same date !

```
1 0x2f91922aa4caba7ae19c1223c0007a1a598dff51 2023-09-22 
2 0xf366adde5b682a8e0d5e4f09663844ea95332f94 2023-09-23 
3 0xe59e6365e879aebf001de470e3281a4c0d6fb0c8 2023-09-22 2023-09-09 
4 0x469cbdfb1f88b41aa89e9ce49af5e758ac4d1d5c 2023-09-22 
5 0x1e98efc80b1b71809b6ce4fa0b09f071143b2c02 2023-09-22 2023-09-09 
6 0xbae2a1899e06cab91fb9251db3b2e7d31acdca44 2023-09-23 
7 0x19d995a031576e10e3138b92a8523b7b9fb6f6bc 2023-09-22 2023-09-09 
8 0x767b97aabeb5d46a0b33e862374f24b87a7679a9 2023-09-23 
9 0x263d6480291fcad81f1dd3c9f5bcc08b5ac5ed1d 2023-09-22 2023-03-31 
10 0xcf41fa770b2529d26bdb604cb16d61a65e74ae7a 2023-09-23 
11 0xb6afd7dcf48ed53fdea3d304bbb2179ee24d209c 2023-09-22 2023-09-09 
12 0x4db45526d4c0cae762a2ff5e4d1ad32c5855000f 2023-09-22 2023-04-01 
13 0x7a0604aa59f054f0d25d859c21222afa0086a959 2023-09-23 
14 0x445259622cd7453dd92d3c23ec7af004947c73ea 2023-09-22 2023-04-05 
15 0x3e897e924842dab543f30352afad81e5e4886ef7 2023-09-23 
16 0x8f7a5c571816ed31182108a7c3046e75033f4fe0 2023-09-24 
17 0xf11b354a61b18b619f8f4e553fcd5db5fb64adf0 2023-09-22 
18 0xde1569da8f95de2ccccbfbda7d05ae5bd788a99f 2023-09-24 
19 0x8052e45555e66f0de48d195a4aab947578134b4a 2023-09-22 
20 0xbcb30d55d932a15f430a5b4553fca71e8aeee57a 2023-09-23 
21 0x7132becef1e3d8d4d9061598c860cae2c86197e6 2023-09-22 2023-09-09 
```

For (0xf366adde5b682a8e0d5e4f09663844ea95332f94, 0xe59e6365e879aebf001de470e3281a4c0d6fb0c8, 0x1e98efc80b1b71809b6ce4fa0b09f071143b2c02, 0x19d995a031576e10e3138b92a8523b7b9fb6f6bc, 0xb6afd7dcf48ed53fdea3d304bbb2179ee24d209c, 0x7132becef1e3d8d4d9061598c860cae2c86197e6) that is 6 out of 20 addresses, same date, same amount, same protocol:
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840182/vun9prdfhycomiiruywl.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840183/a8tnz6ozym9ddfl50wmh.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840184/zarykdsykujvdvhwg2bp.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840186/p7lkclsn2xxeqmlp2dqb.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840187/yjsxnyjbhxq8o12tzp85.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840189/pxp8mzyqz6lkk9e3s7ff.png)

For (0x469cbdfb1f88b41aa89e9ce49af5e758ac4d1d5c,
0x2f91922aa4caba7ae19c1223c0007a1a598dff51,
0x767b97aabeb5d46a0b33e862374f24b87a7679a9,
0x263d6480291fcad81f1dd3c9f5bcc08b5ac5ed1d,
0x4db45526d4c0cae762a2ff5e4d1ad32c5855000f,
0x7a0604aa59f054f0d25d859c21222afa0086a959,
0x445259622cd7453dd92d3c23ec7af004947c73ea,
0xf11b354a61b18b619f8f4e553fcd5db5fb64adf0,
0x8052e45555e66f0de48d195a4aab947578134b4a), which is 9 out of 20 addresses, same amount, same date:

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840190/avv9kqhmdl0x8bea1spr.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840192/uahjug4vtttlt8dkweyb.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840193/gswyifnasshasbjqcm9u.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840195/im0jgaqoyvnpgpvug19l.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840196/epi3saoi5ckmmjqck7oo.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840197/glx4pitnfuljfkrvsr1o.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840199/uw1adbgd99gfz89okqkk.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840200/idturwplmisbs5uu99hr.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840202/cmsxsmjgsfmprsi3gv8l.png)

If we look at L0 scan, we find common transactions on certain protocols:

Shimmer Bridge (9 wallets, addresses: 0x2f91922aa4caba7ae19c1223c0007a1a598dff51, 0xf366adde5b682a8e0d5e4f09663844ea95332f94, 0xbae2a1899e06cab91fb9251db3b2e7d31acdca44, 0x767b97aabeb5d46a0b33e862374f24b87a7679a9, 0xcf41fa770b2529d26bdb604cb16d61a65e74ae7a, 0x3e897e924842dab543f30352afad81e5e4886ef7, 0x8f7a5c571816ed31182108a7c3046e75033f4fe0, 0xde1569da8f95de2ccccbfbda7d05ae5bd788a99f, 0xbcb30d55d932a15f430a5b4553fca71e8aeee57a)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840203/v19drznvmodgmpg59u6o.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840205/y7onzd5li58azxuepjcb.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840207/uivshdakhsd0vjj9g5d6.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840208/dv6vnloacgrotv7nmfkh.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840209/gy7ygkqxkotvdd9obv8f.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840211/zzcpnsvkmntscm1r0nrw.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840212/xtyp2yxkbxtqnsglwyhf.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840214/j8z6xvsatymmfmbiubzl.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840215/e8inuz5rnyn0v0w9hrmf.png)

Maverick (16 wallets, addresses: 0x2f91922aa4caba7ae19c1223c0007a1a598dff51, 0xf366adde5b682a8e0d5e4f09663844ea95332f94, 0xe59e6365e879aebf001de470e3281a4c0d6fb0c8, 0x469cbdfb1f88b41aa89e9ce49af5e758ac4d1d5c, 0x1e98efc80b1b71809b6ce4fa0b09f071143b2c02, 0x19d995a031576e10e3138b92a8523b7b9fb6f6bc, 0x767b97aabeb5d46a0b33e862374f24b87a7679a9, 0x263d6480291fcad81f1dd3c9f5bcc08b5ac5ed1d, 0xb6afd7dcf48ed53fdea3d304bbb2179ee24d209c, 0x4db45526d4c0cae762a2ff5e4d1ad32c5855000f, 0x7a0604aa59f054f0d25d859c21222afa0086a959, 0x445259622cd7453dd92d3c23ec7af004947c73ea, 0x3e897e924842dab543f30352afad81e5e4886ef7, 0xf11b354a61b18b619f8f4e553fcd5db5fb64adf0, 0x8052e45555e66f0de48d195a4aab947578134b4a, 0x7132becef1e3d8d4d9061598c860cae2c86197e6)
on same date 

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840217/myj8au6uqasa9gntjafx.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840219/mo7ijz2jenfuhhbfqhux.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840221/ylqh8xgnee5bql1yf3ki.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840223/huyjtdnjq4uikwctzaqv.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840225/swldxh7vbsxtssrmsvqv.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840227/hw2ilm4dtqxqcby4yu79.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840228/vwthwyh1ksmcl2vrte7b.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840230/ogrfgnbylhhdm2d57txq.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840232/mwacsdmknshicakginz5.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840234/tlw5carc534h7w5bpjvy.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840236/xxfu8goicnrv5nxwio09.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840238/bwxthzgivn34vqhhwmrd.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840239/i58xds7rnsparhpwxcp8.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840241/kjaxs3wmfofcua7qh6rj.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840243/ydabqdgut7prpva4xoqh.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840245/migcufypsswnxl9oxkzm.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840246/gsb3suia2kzfiesyej4m.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840248/wkapwzhjg4ool60bbacq.png)

Finally, USDV (10 wallets, addresses: 0x2f91922aa4caba7ae19c1223c0007a1a598dff51, 0x469cbdfb1f88b41aa89e9ce49af5e758ac4d1d5c, 0x767b97aabeb5d46a0b33e862374f24b87a7679a9, 0x263d6480291fcad81f1dd3c9f5bcc08b5ac5ed1d, 0x4db45526d4c0cae762a2ff5e4d1ad32c5855000f, 0x7a0604aa59f054f0d25d859c21222afa0086a959, 0x445259622cd7453dd92d3c23ec7af004947c73ea, 0x3e897e924842dab543f30352afad81e5e4886ef7, 0xf11b354a61b18b619f8f4e553fcd5db5fb64adf0, 0x8052e45555e66f0de48d195a4aab947578134b4a)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840250/b3zdw4uxemhuz6konomo.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840252/jno6dvfddorjwjxuuq8g.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840253/bcxbmdaleqauplklrjmn.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840255/qtcocap7qkzwevegv0xz.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840256/k8htno7ootk2r1txdpvl.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840258/kmemgwyk6cewuso2oqub.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840259/obvllvr3yjsqjyff2c1u.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840261/tc14xamzhyxsfqekfwuz.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840262/h0ww0v1u5sypu0sf1a5l.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840264/legc3gng47gwepacty1u.png)


</details>

## Cluster 19

7 first address are linked to CEX deposit address: (Binance)
0x8a2BD650db0762bF53CaeCa1F9d86B7AdEd34EE7

**TLDR**
STG lock on Arbitrum with similar amounts
STG loop between all wallets, then locked
ZKEVM / BASE / LINEA bridge on same date! 

```
0xc177e7ffefaf566d3b3ebb6859c5e47989b74e08
0x9f863dc1204c5e8fbe549ee4ae26a00980094fd6
0x3bf80e10d6b84ce68f95293d05847ff6b3110237
0x33915ce1f8a6d32d5be31d4b28474a1b546e1c3f
0xd635a7555c23e7c6529f3d759afae86954bc1c0c
0xd43bef3ed093b0fc66dddf9b5effde13f0b1e7be
0xed99cd1539860f849a0e730434c25b6efb5e5791
0xc237e0560446124a6c838013c7d95757e2672604
0x8f753462180957fae5352bb68a7b52ab94186271
0x899367bdafd942b547b9e0572ace53ad4bdcf7c0
0xc66cef4b49642f99107ad58bcb01331d39539d27
0x8e2126b6a8988ca61fd01c1af66eea4798a08404
0x651527d697829c62f15a86cf993dd515d4ff6154
0x4f2c49987effb3185491435c6b6c299a10545176
0xe5515d72ec752441db928e82fb5b9adb07e9843a
0x84b6cb80d11e16ec9658f37b2099843ef065d272
0xc22177ee6a3cf69811a064672e78c4dca3322217
0x30e0a6ffb5a2030feb67b01529c8709265f474fd
0x57e11965feb9f73732fbef1a4fd0b9e2bb70ffa6
0xaaad486f27b628dadca71a1a76d976f2c2f2291d
```


<details>

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840266/ga3ichiqfnxxm9hsikzc.png)

https://platform.arkhamintelligence.com/visualizer/entity/0x8a2BD650db0762bF53CaeCa1F9d86B7AdEd34EE7,0xc177e7ffefaf566d3b3ebb6859c5e47989b74e08,0x9f863dc1204c5e8fbe549ee4ae26a00980094fd6,0x3bf80e10d6b84ce68f95293d05847ff6b3110237,0x33915ce1f8a6d32d5be31d4b28474a1b546e1c3f,0xd635a7555c23e7c6529f3d759afae86954bc1c0c,0xd43bef3ed093b0fc66dddf9b5effde13f0b1e7be,0xed99cd1539860f849a0e730434c25b6efb5e5791,0xc237e0560446124a6c838013c7d95757e2672604,0x8f753462180957fae5352bb68a7b52ab94186271,0x899367bdafd942b547b9e0572ace53ad4bdcf7c0,0xc66cef4b49642f99107ad58bcb01331d39539d27,0x8e2126b6a8988ca61fd01c1af66eea4798a08404,0x651527d697829c62f15a86cf993dd515d4ff6154,0x4f2c49987effb3185491435c6b6c299a10545176,0xe5515d72ec752441db928e82fb5b9adb07e9843a,0x84b6cb80d11e16ec9658f37b2099843ef065d272,0xc22177ee6a3cf69811a064672e78c4dca3322217,0x30e0a6ffb5a2030feb67b01529c8709265f474fd,0x57e11965feb9f73732fbef1a4fd0b9e2bb70ffa6,0xaaad486f27b628dadca71a1a76d976f2c2f2291d?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

Layer Zero days
20 Wallets ranked from 230k to 530k ranking 
LZ day: 14 wallets at 581 days


Tous les wallets on lock des STG sur Stagate Arbitrum

```
1 0xc177e7ffefaf566d3b3ebb6859c5e47989b74e08 2022-10-21 
2 0x9f863dc1204c5e8fbe549ee4ae26a00980094fd6 2022-10-21   
3 0x3bf80e10d6b84ce68f95293d05847ff6b3110237 2022-10-21   
4 0x33915ce1f8a6d32d5be31d4b28474a1b546e1c3f 2022-10-21   
5 0xd635a7555c23e7c6529f3d759afae86954bc1c0c 2022-10-31   
6 0xd43bef3ed093b0fc66dddf9b5effde13f0b1e7be 2022-10-21   
7 0xed99cd1539860f849a0e730434c25b6efb5e5791 2023-02-01   
8 0xc237e0560446124a6c838013c7d95757e2672604 2022-10-21   
9 0x8f753462180957fae5352bb68a7b52ab94186271 2022-10-23   
10 0x899367bdafd942b547b9e0572ace53ad4bdcf7c0 2022-10-21   
11 0xc66cef4b49642f99107ad58bcb01331d39539d27 2022-10-21   
12 0x8e2126b6a8988ca61fd01c1af66eea4798a08404 2022-10-21   
13 0x651527d697829c62f15a86cf993dd515d4ff6154 2022-10-23   
14 0x4f2c49987effb3185491435c6b6c299a10545176 2022-10-31   
15 0xe5515d72ec752441db928e82fb5b9adb07e9843a 2022-10-31   
16 0x84b6cb80d11e16ec9658f37b2099843ef065d272 2022-10-21   
17 0xc22177ee6a3cf69811a064672e78c4dca3322217 2022-10-21   
18 0x30e0a6ffb5a2030feb67b01529c8709265f474fd 2022-10-21   
19 0x57e11965feb9f73732fbef1a4fd0b9e2bb70ffa6 2022-10-21   
20 0xaaad486f27b628dadca71a1a76d976f2c2f2291d 2022-10-21   
```
 let's dig on this argument:
 
 0xed99cd1539860f849a0e730434c25b6efb5e5791 in the cluster
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840267/xpz2emls6atsxkftlkx2.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840269/ztxespzksfhdd0evs3oo.png)

0x57e11965feb9f73732fbef1a4fd0b9e2bb70ffa6 in the cluster
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840270/ubhzmzz6vrung1qcnn0s.png)

0x8f753462180957fae5352bb68a7b52ab94186271 in the cluster
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840272/ru2y0rrtleg5etwrk844.png)

0xc177e7ffefaf566d3b3ebb6859c5e47989b74e08 in the cluster
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840274/sks3yo8otqpr3klm5puu.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840275/nzbyp4ciwln0uk87tmp7.png)

0x33915ce1f8a6d32d5be31d4b28474a1b546e1c3f in the cluster
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840277/nvas3q7wlnnpkn1hgtcf.png)

0x8e2126b6a8988ca61fd01c1af66eea4798a08404 in the cluster
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840278/gvnpilnnbwseffg2shkg.png)

0xc66cef4b49642f99107ad58bcb01331d39539d27 in the cluster
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840280/syxssn0qhzspasasm8rq.png)

0xc237e0560446124a6c838013c7d95757e2672604 in the cluster
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840281/od2bpopk63n5iqqhpdkm.png)

0x899367bdafd942b547b9e0572ace53ad4bdcf7c0 in the cluster
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840282/ugyjwmsudorstgppxbg7.png)

0x9f863dc1204c5e8fbe549ee4ae26a00980094fd6 in the cluster
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840284/gd5cexqwdpo2eom1uo1h.png)

0x84b6cb80d11e16ec9658f37b2099843ef065d272 in the cluster
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840285/toixnf6se97uztgatvcd.png)

0x30e0a6ffb5a2030feb67b01529c8709265f474fd in the cluster!
[image](https://github.com/altaccounteth/report_layerzero/assets/151371773/5d14daac-7381-4fd0-964e-db2a23d8a0b9)

0xd43bef3ed093b0fc66dddf9b5effde13f0b1e7be in the cluster
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840287/ggsinke7btwmhm6svitg.png)

0xaaad486f27b628dadca71a1a76d976f2c2f2291d in the cluster
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840288/uk86qci87uwkhypuk9gd.png)

0xc22177ee6a3cf69811a064672e78c4dca3322217 in the cluster
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840289/q3nx740mlkblr6pmdbz7.png)

0x57e11965feb9f73732fbef1a4fd0b9e2bb70ffa6 in the cluster
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840291/g9urlc52aimsmqzvz2dz.png)

We still have 4 addresses from the cluster that have not been reached.
We will now dig into each one individually:

in the cluster
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840292/onz2z0pq6yywjebyzzbo.png)

0x57e11965feb9f73732fbef1a4fd0b9e2bb70ffa6 sent to 0xc22177ee6a3cf69811a064672e78c4dca3322217 (already review)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840294/woitazxnefcw8kmmadpy.png)

0x8f753462180957fae5352bb68a7b52ab94186271 in the cluster sent to 0x4f2c49987effb3185491435c6b6c299a10545176 
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840295/e9dluj4o2jtnomaqbrfl.png)

0xc177e7ffefaf566d3b3ebb6859c5e47989b74e08  in the cluster sent to 0x651527d697829c62f15a86cf993dd515d4ff6154 
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840296/guqseadszwkecyzn68vy.png)

0x33915ce1f8a6d32d5be31d4b28474a1b546e1c3f
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840298/xqhekvxr6x5qmyhps0da.png)
It received from 0x8e2126b6a8988ca61fd01c1af66eea4798a08404, which has already been processed, and sent to 0xd635a7555c23e7c6529f3d759afae86954bc1c0c, who is the second-to-last missing one.

0x8e2126b6a8988ca61fd01c1af66eea4798a08404
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840300/cjgcksyqhudgitu9dpbr.png)
He received from 0xc66cef4b49642f99107ad58bcb01331d39539d27 who is already in the cluster and sent to 0x33915ce1f8a6d32d5be31d4b28474a1b546e1c3, who is also already in the cluster.

Now, I'm just looking for the last address (0xe5515d72ec752441db928e82fb5b9adb07e9843a).
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840302/npbdbbxvpck291myimlz.png)

He had exchanges with 0x3bf80e10d6b84ce68f95293d05847ff6b3110237 and 0xd635a7555c23e7c6529f3d759afae86954bc1c0c, who are in the cluster.

DONE, we have all the wallets, the loop is closed.

ZKEVM native bridge all wallets the same days 

```
1 0xc177e7ffefaf566d3b3ebb6859c5e47989b74e08 2023-07-30 
2 0x9f863dc1204c5e8fbe549ee4ae26a00980094fd6 2023-07-30 
3 0x3bf80e10d6b84ce68f95293d05847ff6b3110237 2023-07-30 
4 0x33915ce1f8a6d32d5be31d4b28474a1b546e1c3f 2023-07-30 
5 0xd635a7555c23e7c6529f3d759afae86954bc1c0c 2023-07-30 
6 0xd43bef3ed093b0fc66dddf9b5effde13f0b1e7be 2023-07-30 
7 0xed99cd1539860f849a0e730434c25b6efb5e5791 2023-07-30 
8 0xc237e0560446124a6c838013c7d95757e2672604 2023-07-30 
9 0x8f753462180957fae5352bb68a7b52ab94186271 2023-07-30 
10 0x899367bdafd942b547b9e0572ace53ad4bdcf7c0 2023-07-30 
11 0xc66cef4b49642f99107ad58bcb01331d39539d27 2023-07-30 
12 0x8e2126b6a8988ca61fd01c1af66eea4798a08404 2023-07-30 
13 0x651527d697829c62f15a86cf993dd515d4ff6154 2023-07-30 
14 0x4f2c49987effb3185491435c6b6c299a10545176 2023-07-30 
15 0xe5515d72ec752441db928e82fb5b9adb07e9843a 2023-07-30 
16 0x84b6cb80d11e16ec9658f37b2099843ef065d272 2023-07-30 
17 0xc22177ee6a3cf69811a064672e78c4dca3322217 2023-07-30 
18 0x30e0a6ffb5a2030feb67b01529c8709265f474fd 2023-07-30 
19 0x57e11965feb9f73732fbef1a4fd0b9e2bb70ffa6 2023-07-30 
20 0xaaad486f27b628dadca71a1a76d976f2c2f2291d 2023-07-30 
```

base native bridge all wallets the same days 
```
1 0xc177e7ffefaf566d3b3ebb6859c5e47989b74e08 2023-08-05
2 0x9f863dc1204c5e8fbe549ee4ae26a00980094fd6 2023-08-05 
3 0x3bf80e10d6b84ce68f95293d05847ff6b3110237 2023-08-05 
4 0x33915ce1f8a6d32d5be31d4b28474a1b546e1c3f 2023-08-05 
5 0xd635a7555c23e7c6529f3d759afae86954bc1c0c 2023-08-05 
6 0xd43bef3ed093b0fc66dddf9b5effde13f0b1e7be 2023-08-05 
7 0xed99cd1539860f849a0e730434c25b6efb5e5791 2023-08-05 
8 0xc237e0560446124a6c838013c7d95757e2672604 2023-08-05 
9 0x8f753462180957fae5352bb68a7b52ab94186271 2023-08-05 
10 0x899367bdafd942b547b9e0572ace53ad4bdcf7c0 2023-08-05 
11 0xc66cef4b49642f99107ad58bcb01331d39539d27 2023-08-05 
12 0x8e2126b6a8988ca61fd01c1af66eea4798a08404 2023-08-05 
13 0x651527d697829c62f15a86cf993dd515d4ff6154 2023-08-05 
14 0x4f2c49987effb3185491435c6b6c299a10545176 2023-08-05 
15 0xe5515d72ec752441db928e82fb5b9adb07e9843a 2023-08-05 
16 0x84b6cb80d11e16ec9658f37b2099843ef065d272 2023-08-05 
17 0xc22177ee6a3cf69811a064672e78c4dca3322217 2023-08-05 
18 0x30e0a6ffb5a2030feb67b01529c8709265f474fd 2023-08-05 
19 0x57e11965feb9f73732fbef1a4fd0b9e2bb70ffa6 2023-08-05 
20 0xaaad486f27b628dadca71a1a76d976f2c2f2291d 2023-08-05 
```

linea native bridge all wallets the same days 
```
1 0xc177e7ffefaf566d3b3ebb6859c5e47989b74e08 2023-07-30 
2 0x9f863dc1204c5e8fbe549ee4ae26a00980094fd6 2023-07-30 
3 0x3bf80e10d6b84ce68f95293d05847ff6b3110237 2023-07-30 
4 0x33915ce1f8a6d32d5be31d4b28474a1b546e1c3f 2023-07-30 
5 0xd635a7555c23e7c6529f3d759afae86954bc1c0c 2023-07-30 
6 0xd43bef3ed093b0fc66dddf9b5effde13f0b1e7be 2023-07-30 
7 0xed99cd1539860f849a0e730434c25b6efb5e5791 2023-07-30 
8 0xc237e0560446124a6c838013c7d95757e2672604 2023-07-30 
9 0x8f753462180957fae5352bb68a7b52ab94186271 2023-07-30 
10 0x899367bdafd942b547b9e0572ace53ad4bdcf7c0 2023-07-30 
11 0xc66cef4b49642f99107ad58bcb01331d39539d27 2023-07-30 
12 0x8e2126b6a8988ca61fd01c1af66eea4798a08404 2023-07-30 
13 0x651527d697829c62f15a86cf993dd515d4ff6154 2023-07-30 
14 0x4f2c49987effb3185491435c6b6c299a10545176 2023-07-30 
15 0xe5515d72ec752441db928e82fb5b9adb07e9843a 2023-07-30 
16 0x84b6cb80d11e16ec9658f37b2099843ef065d272 2023-07-30 
17 0xc22177ee6a3cf69811a064672e78c4dca3322217 2023-07-30 
18 0x30e0a6ffb5a2030feb67b01529c8709265f474fd 2023-07-30 
19 0x57e11965feb9f73732fbef1a4fd0b9e2bb70ffa6 2023-07-30 
20 0xaaad486f27b628dadca71a1a76d976f2c2f2291d 2023-07-30 
```



</details>


## Cluster 20

7 first address linked to CEX deposit
0xD732573c8892E0e00404822D3E078B86cfcBa468

**TLDR**
same layerzerotx on zksync within 2 hours
similar zksync bridge date

```
0x666f5f8cb7870f33317db349799cbee427f9e72a
0x1e903fd5be070c1a8056fc525346afb00219a59f
0xca8cf17da5a91cce8ca898adc5428b436ddea1dc
0x67b1ee22e7493e94450a55cba50f6a6ca67f7a3e
0x22cb1d945d23fa08323e59fec9abbcd359e59095
0x5f8f9cb5a25450d1fe78a0ec06a087ca3b36a883
0xeafb1a7bb2da730911e246ba071a59551d581a40
0x97242b533bbbf6375d33c0d6a11cbdd55970ebad
0x53c7c04f1c24a31ba5da10cca82c1bf2139f43b4
0x16adbaabeec90a7e9ef839bf68d90df03668f6a1
0xe9fb4775cbedc7bb6bf36f397de5da1bf7e5b7cf
0x9ce2774ecced375abcdfd04152728caf486b5744
0x5ef55868c28777f00f8fc456f2f09cbf6f3964a8
0x06083744ed88399f6856a2d9b6c140816ade0708
0xe8f69e74a4d24172831ae48b026796f727e1eb4b
0x8f312aac0d57e6a7322dfaad4cc29f030a985f96
0xf00ded727cffdae8ad4981e212eeab2adb0e8da5
0x6bfb5845e869ec2d222bdf89b94c8e79ed5984e1
0x3ee6170ea6d16268e48d67362fa65fa82bb5a6be
0x3d503521439aa08dc8009427b7a48475bcb211f1
0x827eaee2b64ebc45f7fcfc2747d037e37b37b62d
0x8116c3bb43372179ccba51f4374bddbce5c15fbd
0xc2240ee369f82094a4036e0f6ae47cc7919fcaaf
0x7266021ad5e81e79b859b505d411afa99e3d935d
0x921e8b903cbaf28747fad40b3846420b41bcf970
0x2788c9a8a417c50654277189aabf098900ff55d5
0xeffdbc30574a4261713bbdb91a29732326b946bb
0xdc4d52e4bb24544ae55b358d3ee6c73db8a686b2
0xab1f5815ae3ddc8381896072759db5232127cec3
```

<details>

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840304/hdlisy8kz3rdzc9eb6ml.png)

https://platform.arkhamintelligence.com/visualizer/entity/0xD732573c8892E0e00404822D3E078B86cfcBa468,0x666f5f8cb7870f33317db349799cbee427f9e72a,0x1e903fd5be070c1a8056fc525346afb00219a59f,0xca8cf17da5a91cce8ca898adc5428b436ddea1dc,0x67b1ee22e7493e94450a55cba50f6a6ca67f7a3e,0x22cb1d945d23fa08323e59fec9abbcd359e59095,0x5f8f9cb5a25450d1fe78a0ec06a087ca3b36a883,0xeafb1a7bb2da730911e246ba071a59551d581a40,0x97242b533bbbf6375d33c0d6a11cbdd55970ebad,0x53c7c04f1c24a31ba5da10cca82c1bf2139f43b4,0x16adbaabeec90a7e9ef839bf68d90df03668f6a1,0xe9fb4775cbedc7bb6bf36f397de5da1bf7e5b7cf,0x9ce2774ecced375abcdfd04152728caf486b5744,0x5ef55868c28777f00f8fc456f2f09cbf6f3964a8,0x06083744ed88399f6856a2d9b6c140816ade0708,0xe8f69e74a4d24172831ae48b026796f727e1eb4b,0x8f312aac0d57e6a7322dfaad4cc29f030a985f96,0xf00ded727cffdae8ad4981e212eeab2adb0e8da5,0x6bfb5845e869ec2d222bdf89b94c8e79ed5984e1,0x3ee6170ea6d16268e48d67362fa65fa82bb5a6be,0x3d503521439aa08dc8009427b7a48475bcb211f1,0x827eaee2b64ebc45f7fcfc2747d037e37b37b62d,0x8116c3bb43372179ccba51f4374bddbce5c15fbd,0xc2240ee369f82094a4036e0f6ae47cc7919fcaaf,0x7266021ad5e81e79b859b505d411afa99e3d935d,0x921e8b903cbaf28747fad40b3846420b41bcf970,0x2788c9a8a417c50654277189aabf098900ff55d5,0xeffdbc30574a4261713bbdb91a29732326b946bb,0xdc4d52e4bb24544ae55b358d3ee6c73db8a686b2,0xab1f5815ae3ddc8381896072759db5232127cec3?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

Same layer zero tx on zksync, the same day, at very similar time, on all wallet! 
open name()

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840306/dz4kdwhl38k30nj8gvzm.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840308/nqsyfwextkth8vlexnnh.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840309/mabz7vbij1b1yx7wciiz.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840311/hve5osiposyu7hev2a9g.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840313/sgux0xk5zckxzhu8a9qw.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840314/oe6xwc0q8f0ooncgdjj3.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840316/rsymrnjpiuhufoucbgyj.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840318/on9ctvc1icbvats9w45p.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840320/c5lpkhc1a1ctckluviu8.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840321/cpf3o2qmnkrwcakw5hpd.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840324/dagefjbpbk4oewkdvgwi.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840326/qmqkyxkhqk0bk71ii7oe.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840327/siw5b0imysfnw9opp86o.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840330/cgd8evr729ap3h6zib9s.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840332/nydzbcilr3adxl4ic4wh.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840334/useu1lvdfk2cy8yo8jbr.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840336/bsszsrkic0gbgzs9eixm.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840338/dav53dk8j8uggkqjjvw4.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840339/ciyy9lbkiklps2mhzbu0.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840341/mt2lzfikh6b35qhthxr4.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840343/anhngteglrckbsxeue6n.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840345/np0xrhzljboqtwxsun7u.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840346/eo7y7vfnjtbjxjwcc5g5.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840348/rjqij2us1cd7to2jueke.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840350/h2hwuoygtiq4t5bl71o2.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840352/boiyaczisk2rnqe7pgme.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840353/ic5snmskzzrqqychjlxl.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840355/wpbxc9vwkjfedkjrlxqh.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840357/fokghieeyafo6npcate0.png)


zksync native bridge

```
1 0x666f5f8cb7870f33317db349799cbee427f9e72a 2023-10-30 2023-06-08 2023-03-28 
2 0x1e903fd5be070c1a8056fc525346afb00219a59f 2023-10-29 2023-06-09 2023-03-25 
3 0xca8cf17da5a91cce8ca898adc5428b436ddea1dc 2023-03-25 
4 0x67b1ee22e7493e94450a55cba50f6a6ca67f7a3e 2023-03-25 
5 0x22cb1d945d23fa08323e59fec9abbcd359e59095 2023-10-30 2023-06-08 2023-03-28 
6 0x5f8f9cb5a25450d1fe78a0ec06a087ca3b36a883 2023-10-29 2023-06-09 2023-03-25 
7 0xeafb1a7bb2da730911e246ba071a59551d581a40 2023-10-29 2023-06-09 2023-03-24 
8 0x97242b533bbbf6375d33c0d6a11cbdd55970ebad 2023-06-09 2023-03-25 
9 0x53c7c04f1c24a31ba5da10cca82c1bf2139f43b4 2023-10-29 2023-06-09 2023-03-25 
10 0x16adbaabeec90a7e9ef839bf68d90df03668f6a1 2023-03-25 
11 0xe9fb4775cbedc7bb6bf36f397de5da1bf7e5b7cf 2023-10-30 2023-06-08 2023-03-28 
12 0x9ce2774ecced375abcdfd04152728caf486b5744 2023-10-30 2023-06-08 2023-03-28 
13 0x5ef55868c28777f00f8fc456f2f09cbf6f3964a8 2023-10-30 2023-06-08 2023-03-29 
14 0x06083744ed88399f6856a2d9b6c140816ade0708 2023-10-29 2023-03-25 
15 0xe8f69e74a4d24172831ae48b026796f727e1eb4b 2023-10-30 2023-06-08 2023-03-29 
16 0x8f312aac0d57e6a7322dfaad4cc29f030a985f96 2023-10-30 2023-06-08 2023-03-29 
17 0xf00ded727cffdae8ad4981e212eeab2adb0e8da5 2023-03-25 
18 0x6bfb5845e869ec2d222bdf89b94c8e79ed5984e1 2023-10-29 2023-03-25 
19 0x3ee6170ea6d16268e48d67362fa65fa82bb5a6be 2023-10-29 2023-06-09 2023-03-25 
20 0x3d503521439aa08dc8009427b7a48475bcb211f1 2023-10-29 2023-03-25 
21 0x827eaee2b64ebc45f7fcfc2747d037e37b37b62d 2023-06-09 2023-03-25 
22 0x8116c3bb43372179ccba51f4374bddbce5c15fbd 2023-03-25 
23 0xc2240ee369f82094a4036e0f6ae47cc7919fcaaf 2023-06-09 2023-03-25 
24 0x7266021ad5e81e79b859b505d411afa99e3d935d 2023-10-29 2023-06-09 2023-03-25 
25 0x921e8b903cbaf28747fad40b3846420b41bcf970 2023-06-09 2023-03-25 
26 0x2788c9a8a417c50654277189aabf098900ff55d5 2023-06-09 2023-03-25 
27 0xeffdbc30574a4261713bbdb91a29732326b946bb 2023-03-25 
28 0xdc4d52e4bb24544ae55b358d3ee6c73db8a686b2 2023-03-25 
29 0xab1f5815ae3ddc8381896072759db5232127cec3 2023-03-25 
```

</details>


## Cluster 21 

7 first address linked to cex deposit address:
0xFb62EF0D95956a9E8762957c9558F432B49E6947


```
0xd581f0b4493f6f5177165dca75b64f0fba02b61f
0xb8c9aed31f543d51f01b5f89ccdd2a28f0517e19
0xe064bd0dd80ed0b3135254b5c8d6782a04b029ab
0x44fa549d359e9c0bf9d5d4ef9c3c703869730f3f
0xe1399d2a7eb186247cc116239294a8e2327905ba
0x61e1e7ca42c702def5129cdd6300ecea9438df62
0x0e34e66c9a1cca50ef2cb4b08b13a907f7852af3
0x17807d5c8024aff6b1bd7516f230a77ecf63e89b
0x67e20712877b89f2984dcc3f62f5a80621238311
0x68ec70f9788f7eb1a3d77a530a2ed23ad5000d52
0x78e7bc2f2a5f9c6e4377ee53ef67377603e00874
0x4c565df6d8231108348f7d527a8aeacef984db60
0x5dc6c10cbe4dfbadb87f3df9468931573b9640a5
0x0ed4e17f1a26ef333b3e8cfca4026f4757d6c5f5
0x956f0917c6d85af6f5617ab5493a78fe312857ee
0x352fc52a31e7f2e049f0a86f998f19abcd938cb0
0x0304ce0021f218c599a71964ad0330b8eea6a54d
0x52a6b8803104ae64517ce77fb6b361c504dd1b80
0xf1baeee754ade85c39ce17ff9c7134c874f5cb1f
0x150c6bb40ff9f21fc619696e130564c6c69a8689
0x7a454e7fc2ef38fcf2e9ef543da6eabb6436d444
0x7be681f67f8cb515af1439ba8b02df1061fec7d0
0x80e7f5527ac143d9e6a0e3198dd95b749fc1755d
0xc4fb3efb72aea4aca97a68739044e546c02697a7
0xd7b24eb9cc30388afe22b8f46efebb42f208bc52
0x0a4ce45855136ea52aa207e817e67c3c5a899c5c
0x89d2030ebf0320491cb8230904ef3457f51f5e53
0x951fba59969c4a140a0bd410f27b54a0d636d11a
0x5bbf248fa2f08c14036681a7d2b797f64f575654
0x9eb00ad9a31c9d7fa26f54cd1b562c0567f2bbe7
0xb330ef053c8757af1dae7cfff1a099da729c7052
0x082347c166e2b8c5fa378adbc308214446f46fdd
0xdabe6d5f5e08407ba9ffbf8914e7ab039d2dafb3
0xcd24aa1d300d0213e4b142def75bc9603141b8fa
0xca0f86a9680d89efebc2f7d9c5fcc013a68fb985
0x520b9d1c114d09298b6325e59e3ae3a07c61b7c9
0x356d3bee3080b21ff0b91dff3d849eb2f24578f6
0x2b83a03db4fa319b609c08d894514cb10f10c8e5
0xbb3714ce155526fa2ac0c85a1affd6aea91813df
0xa58b2103479442a362a77d2c6fb3afa3531fc2f9
0x18f2fde723cd8b7c5f5c6efeb3172338bee2b027
0xe7effa42c95e52208eadf8bdb144baf08fc91508
0x8795ee72a276640d0bc2af1e5a4f5c59add94d4a
0xef5c5bf0738d2d9ccdf5e60974d4343aeebab52b
0x2088d86c38dfd48d5d879cd7f7bb885b3c45dd60
0xbfbc0e79c09ad1b05a5d3357a3ba147b3ec287a0
0x4dc83d1b3c56d9ac640efcdf6df26d05487ce2c4
0x8f4a0562d2ca4335cfbe854218d1ed1a8703e23e
0x99ed512659c874d9a0c8bf99af97f73cb947eb83 
0x05cdc1970971ea66a43e6e86d9dd0e2fb5d52393
0x604bba1fb4574456df8c875fc878c4c377de3c8e
0xe73fe3e3e50db8c2950072705f1613f4a34f1cac
```
<details>

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840359/uasd4a3b1jyu7m1eezqf.png)
https://platform.arkhamintelligence.com/visualizer/entity/0xFb62EF0D95956a9E8762957c9558F432B49E6947,0xd581f0b4493f6f5177165dca75b64f0fba02b61f,0xb8c9aed31f543d51f01b5f89ccdd2a28f0517e19,0xe064bd0dd80ed0b3135254b5c8d6782a04b029ab,0x44fa549d359e9c0bf9d5d4ef9c3c703869730f3f,0xe1399d2a7eb186247cc116239294a8e2327905ba,0x61e1e7ca42c702def5129cdd6300ecea9438df62,0x0e34e66c9a1cca50ef2cb4b08b13a907f7852af3,0x17807d5c8024aff6b1bd7516f230a77ecf63e89b,0x67e20712877b89f2984dcc3f62f5a80621238311,0x68ec70f9788f7eb1a3d77a530a2ed23ad5000d52,0x78e7bc2f2a5f9c6e4377ee53ef67377603e00874,0x4c565df6d8231108348f7d527a8aeacef984db60,0x5dc6c10cbe4dfbadb87f3df9468931573b9640a5,0x0ed4e17f1a26ef333b3e8cfca4026f4757d6c5f5,0x956f0917c6d85af6f5617ab5493a78fe312857ee,0x352fc52a31e7f2e049f0a86f998f19abcd938cb0,0x0304ce0021f218c599a71964ad0330b8eea6a54d,0x52a6b8803104ae64517ce77fb6b361c504dd1b80,0xf1baeee754ade85c39ce17ff9c7134c874f5cb1f,0x150c6bb40ff9f21fc619696e130564c6c69a8689,0x7a454e7fc2ef38fcf2e9ef543da6eabb6436d444,0x7be681f67f8cb515af1439ba8b02df1061fec7d0,0x80e7f5527ac143d9e6a0e3198dd95b749fc1755d,0xc4fb3efb72aea4aca97a68739044e546c02697a7,0xd7b24eb9cc30388afe22b8f46efebb42f208bc52,0x0a4ce45855136ea52aa207e817e67c3c5a899c5c,0x89d2030ebf0320491cb8230904ef3457f51f5e53,0x951fba59969c4a140a0bd410f27b54a0d636d11a,0x5bbf248fa2f08c14036681a7d2b797f64f575654,0x9eb00ad9a31c9d7fa26f54cd1b562c0567f2bbe7,0xb330ef053c8757af1dae7cfff1a099da729c7052,0x082347c166e2b8c5fa378adbc308214446f46fdd,0xdabe6d5f5e08407ba9ffbf8914e7ab039d2dafb3,0xcd24aa1d300d0213e4b142def75bc9603141b8fa,0xca0f86a9680d89efebc2f7d9c5fcc013a68fb985,0x520b9d1c114d09298b6325e59e3ae3a07c61b7c9,0x356d3bee3080b21ff0b91dff3d849eb2f24578f6,0x2b83a03db4fa319b609c08d894514cb10f10c8e5,0xbb3714ce155526fa2ac0c85a1affd6aea91813df,0xa58b2103479442a362a77d2c6fb3afa3531fc2f9,0x18f2fde723cd8b7c5f5c6efeb3172338bee2b027,0xe7effa42c95e52208eadf8bdb144baf08fc91508,0x8795ee72a276640d0bc2af1e5a4f5c59add94d4a,0xef5c5bf0738d2d9ccdf5e60974d4343aeebab52b,0x2088d86c38dfd48d5d879cd7f7bb885b3c45dd60,0xbfbc0e79c09ad1b05a5d3357a3ba147b3ec287a0,0x4dc83d1b3c56d9ac640efcdf6df26d05487ce2c4,0x8f4a0562d2ca4335cfbe854218d1ed1a8703e23e,0x99ed512659c874d9a0c8bf99af97f73cb947eb83,0x05cdc1970971ea66a43e6e86d9dd0e2fb5d52393,0x604bba1fb4574456df8c875fc878c4c377de3c8e,0xe73fe3e3e50db8c2950072705f1613f4a34f1cac?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1


52 wallets de 130 k à 1.8M (sans compter le CEX)

LZ day: 2 à 386, 10 à 406, 2 à 413, 3 à 500, 9 à 704, 19 à 705

  
arbi stg lock

```
2 0xd581f0b4493f6f5177165dca75b64f0fba02b61f 2022-10-30   
3 0xb8c9aed31f543d51f01b5f89ccdd2a28f0517e19 2022-10-30   
4 0xe064bd0dd80ed0b3135254b5c8d6782a04b029ab 2022-10-30   
5 0x44fa549d359e9c0bf9d5d4ef9c3c703869730f3f 2022-10-30   
6 0xe1399d2a7eb186247cc116239294a8e2327905ba 2022-10-30   
7 0x61e1e7ca42c702def5129cdd6300ecea9438df62 2022-10-30   
8 0x0e34e66c9a1cca50ef2cb4b08b13a907f7852af3 2022-10-30   
9 0x17807d5c8024aff6b1bd7516f230a77ecf63e89b 2022-10-30   
10 0x67e20712877b89f2984dcc3f62f5a80621238311 2022-10-30   
11 0x68ec70f9788f7eb1a3d77a530a2ed23ad5000d52 2022-10-30   
12 0x78e7bc2f2a5f9c6e4377ee53ef67377603e00874 2022-10-30   
13 0x4c565df6d8231108348f7d527a8aeacef984db60 2022-10-30   
14 0x5dc6c10cbe4dfbadb87f3df9468931573b9640a5 2022-11-29   
15 0x0ed4e17f1a26ef333b3e8cfca4026f4757d6c5f5 2022-10-30   
16 0x956f0917c6d85af6f5617ab5493a78fe312857ee 2023-04-16   
17 0x352fc52a31e7f2e049f0a86f998f19abcd938cb0 2023-04-16   
18 0x0304ce0021f218c599a71964ad0330b8eea6a54d 2023-04-16   
19 0x52a6b8803104ae64517ce77fb6b361c504dd1b80 2022-10-30   
20 0xf1baeee754ade85c39ce17ff9c7134c874f5cb1f 2022-10-30   
21 0x150c6bb40ff9f21fc619696e130564c6c69a8689 2022-10-30   
22 0x7a454e7fc2ef38fcf2e9ef543da6eabb6436d444 2022-10-30   
23 0x7be681f67f8cb515af1439ba8b02df1061fec7d0 2022-10-30   
24 0x80e7f5527ac143d9e6a0e3198dd95b749fc1755d 2022-10-30   
25 0xc4fb3efb72aea4aca97a68739044e546c02697a7 2022-10-30   
26 0xd7b24eb9cc30388afe22b8f46efebb42f208bc52 2022-10-30   
27 0x0a4ce45855136ea52aa207e817e67c3c5a899c5c 2022-10-30   
28 0x89d2030ebf0320491cb8230904ef3457f51f5e53 2022-10-30   
29 0x951fba59969c4a140a0bd410f27b54a0d636d11a 2022-10-30   
30 0x5bbf248fa2f08c14036681a7d2b797f64f575654 2022-10-30   
31 0x9eb00ad9a31c9d7fa26f54cd1b562c0567f2bbe7 2023-04-16   
32 0xb330ef053c8757af1dae7cfff1a099da729c7052 2022-10-30   
33 0x082347c166e2b8c5fa378adbc308214446f46fdd 2023-04-16   
34 0xdabe6d5f5e08407ba9ffbf8914e7ab039d2dafb3 2023-04-16   
35 0xcd24aa1d300d0213e4b142def75bc9603141b8fa 2022-10-30   
36 0xca0f86a9680d89efebc2f7d9c5fcc013a68fb985 2022-10-30   
37 0x520b9d1c114d09298b6325e59e3ae3a07c61b7c9 2023-04-16   
38 0x356d3bee3080b21ff0b91dff3d849eb2f24578f6 2023-04-16   
39 0x2b83a03db4fa319b609c08d894514cb10f10c8e5 2023-04-16   
41 0xa58b2103479442a362a77d2c6fb3afa3531fc2f9 2023-04-16   
42 0x18f2fde723cd8b7c5f5c6efeb3172338bee2b027 2023-04-16   
43 0xe7effa42c95e52208eadf8bdb144baf08fc91508 2022-10-30   
44 0x8795ee72a276640d0bc2af1e5a4f5c59add94d4a 2023-05-11   
45 0xef5c5bf0738d2d9ccdf5e60974d4343aeebab52b 2023-06-20   
46 0x2088d86c38dfd48d5d879cd7f7bb885b3c45dd60 2023-04-16   
47 0xbfbc0e79c09ad1b05a5d3357a3ba147b3ec287a0 2023-04-16   
48 0x4dc83d1b3c56d9ac640efcdf6df26d05487ce2c4 2023-04-16   
49 0x8f4a0562d2ca4335cfbe854218d1ed1a8703e23e 2022-10-30   
50 0x99ed512659c874d9a0c8bf99af97f73cb947eb83 2022-10-30   
51 0x05cdc1970971ea66a43e6e86d9dd0e2fb5d52393 2022-10-30   
52 0x604bba1fb4574456df8c875fc878c4c377de3c8e 2022-10-30   
53 0xe73fe3e3e50db8c2950072705f1613f4a34f1cac 2022-10-30   
```
Regardons 0xd581f0b4493f6f5177165dca75b64f0fba02b61f et plus particulièrement ses STG sur Arbitrum:
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840360/glbmav5ns4sxwcxfwwcc.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840362/xinndxucggy1bgod0flw.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840364/qab0esavx3gjxd3mnwd9.png)

Now we will look at L0 scan to link all wallets:
Common TX Tevaera:

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840366/sqfzj8gxjsjqu1ztbwgc.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840367/x1doyio31gm42tya2apl.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840369/acu7loxhymu7rbsxzfba.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840371/cefkameh6jha9jqoyax2.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840373/gasyq3ozcwd2uj5fsfpc.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840375/srxowcz1b28ooi84he7u.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840377/o0ojfwrqcoabjge8cjvc.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840379/zuyrjb7pzrsandmfum9p.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840380/ghy59xvllmrx98ryum3b.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840382/mgxrasmbiiau09ocrkuk.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840384/m4o3ogdkl97sszmpnxxq.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840386/k8h3kgbfz51163dh1kc9.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840387/bwxdze2cpaxxmewrw6lh.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840389/maa0gr1r7ujmwdoy6yor.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840391/tpkg8wagrce5ulv9yu1y.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840392/mepff9s14aaqveppekrr.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840394/gbrlpkwzns4sckdkwfmd.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840396/lamzplt4pugkx6aiem6k.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840398/ata0wu2thtlxmxiioc4b.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840400/aegfp1ugmjgljbwjcli8.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840402/nfgjej5suy9oudxd6q03.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840403/xnbpmmq8r4euvfy6spyz.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840405/og4vzyesifcnosjqkh8i.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840407/szil6s1evohwvkxktkzz.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840409/xsvar9vhzyvxbfoudbtw.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840410/cwibuwjn94cpjgomanox.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840412/ur17bjnh1tj5jhwmwxcg.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840414/utobxe0lndwwswvhrsrr.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840416/fcg84bs0ikipd3eigpdj.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840418/suo6bmvff4srcfk3q7gr.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840419/v2cclx4pfyahmqbt4fi0.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840421/nachdu02wzrypcufvmyb.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840423/jsirbzwxfzxgllpatbm9.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840425/qiqdszuhe56hvauai9zc.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840427/gpiux5vlo9qv6nlwwep4.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840429/oxebfoethreigmt0xxky.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840430/jos0ktlmpr5btwa97ykn.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840432/vvhbnru9bk64fyfxtnci.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840434/yfcfwk4em7xuzqqjskmv.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840436/m8k3dotfirsrj7thapro.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840438/xdhzocyfuanbz28kc85r.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840441/lznfl3lubzrqxtue1wso.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840442/nxktqrbn4di8oiojejsz.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840444/cwfc9yn593zng1t8ed42.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840446/vwxm6o7ejh4fxbf7d2z3.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840448/wq4fpo4areu6devvcs6t.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840449/bf5k1goa4f16ak32xv09.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840451/fkeuempdetlees3uxrtk.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840453/bpnacvq23qnovilhn69s.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840455/yumproprhex2y34xhgxj.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840456/odnziahbmzcboac9mykl.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840458/o6tsi4wzapzzfz6z3zc6.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840460/q6o9clqojqbhwdmdhhnp.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840462/n0utddtuajhyridqdlv9.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840463/zsadiryucnxsh7aa2v2q.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840465/jrelseczgq4ecwq7thkf.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840467/odvlkjpexjtjyqyv2ggx.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840469/bptfkeqhi6kqflgrwxne.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840471/lshcmjmi0rg9ssevl7rt.png)

TLDR
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840474/s8nsa4avzo9rkddnskep.png)


```
base
2 0xd581f0b4493f6f5177165dca75b64f0fba02b61f 2023-08-08 2023-08-08 2023-07-15 
3 0xb8c9aed31f543d51f01b5f89ccdd2a28f0517e19 2023-08-09 2023-07-16 
4 0xe064bd0dd80ed0b3135254b5c8d6782a04b029ab 2023-08-10 2023-08-09 
6 0xe1399d2a7eb186247cc116239294a8e2327905ba 2023-08-09 2023-08-09 2023-08-08 
7 0x61e1e7ca42c702def5129cdd6300ecea9438df62 2023-08-08 2023-08-08 
8 0x0e34e66c9a1cca50ef2cb4b08b13a907f7852af3 2024-04-23 2023-09-15 2023-08-08 2023-08-08 
9 0x17807d5c8024aff6b1bd7516f230a77ecf63e89b 2023-08-09 2023-07-16 
10 0x67e20712877b89f2984dcc3f62f5a80621238311 2023-08-08 2023-08-08 2023-07-15 
11 0x68ec70f9788f7eb1a3d77a530a2ed23ad5000d52 2023-08-09 2023-07-16 
12 0x78e7bc2f2a5f9c6e4377ee53ef67377603e00874 2023-08-10 2023-08-09 2023-07-16 
14 0x5dc6c10cbe4dfbadb87f3df9468931573b9640a5 2023-07-16 
15 0x0ed4e17f1a26ef333b3e8cfca4026f4757d6c5f5 2023-07-16 
16 0x956f0917c6d85af6f5617ab5493a78fe312857ee 2023-07-16 
18 0x0304ce0021f218c599a71964ad0330b8eea6a54d 2023-07-16 
19 0x52a6b8803104ae64517ce77fb6b361c504dd1b80 2023-08-10 2023-08-09 2023-07-16 
20 0xf1baeee754ade85c39ce17ff9c7134c874f5cb1f 2023-08-09 2023-08-09 2023-07-15 
21 0x150c6bb40ff9f21fc619696e130564c6c69a8689 2023-08-09 2023-08-09 2023-07-15 
22 0x7a454e7fc2ef38fcf2e9ef543da6eabb6436d444 2023-08-09 2023-07-15 
23 0x7be681f67f8cb515af1439ba8b02df1061fec7d0 2023-08-10 2023-08-09 
24 0x80e7f5527ac143d9e6a0e3198dd95b749fc1755d 2023-08-10 2023-08-09 2023-07-16 
25 0xc4fb3efb72aea4aca97a68739044e546c02697a7 2023-08-09 2023-07-15 
26 0xd7b24eb9cc30388afe22b8f46efebb42f208bc52 2023-08-09 2023-07-16 
27 0x0a4ce45855136ea52aa207e817e67c3c5a899c5c 2023-08-08 
28 0x89d2030ebf0320491cb8230904ef3457f51f5e53 2023-08-08 2023-07-15 
29 0x951fba59969c4a140a0bd410f27b54a0d636d11a 2023-08-09 2023-08-09 2023-07-15 
30 0x5bbf248fa2f08c14036681a7d2b797f64f575654 2023-08-09 2023-07-16 
31 0x9eb00ad9a31c9d7fa26f54cd1b562c0567f2bbe7 2023-07-16 
32 0xb330ef053c8757af1dae7cfff1a099da729c7052 2023-08-09 2023-08-09 2023-07-15 
33 0x082347c166e2b8c5fa378adbc308214446f46fdd 2023-07-16 
35 0xcd24aa1d300d0213e4b142def75bc9603141b8fa 2023-07-16 
36 0xca0f86a9680d89efebc2f7d9c5fcc013a68fb985 2023-07-16 
37 0x520b9d1c114d09298b6325e59e3ae3a07c61b7c9 2023-07-16 
39 0x2b83a03db4fa319b609c08d894514cb10f10c8e5 2023-07-16 
41 0xa58b2103479442a362a77d2c6fb3afa3531fc2f9 2023-07-16 
43 0xe7effa42c95e52208eadf8bdb144baf08fc91508 2023-08-09 2023-07-15 
44 0x8795ee72a276640d0bc2af1e5a4f5c59add94d4a 2023-09-17 2023-09-15 
45 0xef5c5bf0738d2d9ccdf5e60974d4343aeebab52b 2023-08-10 2023-08-09 2023-07-16 
47 0xbfbc0e79c09ad1b05a5d3357a3ba147b3ec287a0 2023-07-16 
48 0x4dc83d1b3c56d9ac640efcdf6df26d05487ce2c4 2023-07-16 
49 0x8f4a0562d2ca4335cfbe854218d1ed1a8703e23e 2023-08-09 2023-07-15 
50 0x99ed512659c874d9a0c8bf99af97f73cb947eb83 2023-08-10 2023-08-09 2023-07-16 
51 0x05cdc1970971ea66a43e6e86d9dd0e2fb5d52393 2023-08-09 2023-07-15 
52 0x604bba1fb4574456df8c875fc878c4c377de3c8e 2023-08-10 2023-08-09 2023-07-16 
53 0xe73fe3e3e50db8c2950072705f1613f4a34f1cac 2023-08-09 2023-07-15 
 ``` 
</details>

## Cluster 22

ALL wallet linked to the same cex deposit address 
(OKX)
0xbF7e7150F31f25a857Df5C1aDe3C1FdA54311d00

**TLDR**


```
0xe9e6a0ec4f0b979a28cbe09c852c86b31769a88b
0xc2b877c9bf9ed8821b2adb0adab8d236e9462cd5
0xcf10556fc23d69789abbb4e0cc78ec09f91594ff
0xf12478f003c4cccfc31872b2853de0916129929b
0x648efe3dfe395843b9c8ae424929d5a9e83f9e92
0xc185b40545faf7fb21e69ce26b9282881db42fa7
0x73b22acb6ce9fbd26c3d9f275c5e756a2e312d0a
0xa52bfd65df1cb8b762d97bbb08b298b0bf42c6a7
0x50844f97ed5dd518a06509860cc56f8e269c8008
0x0f11535265a0f8c2389451c30d0d2f8f7b43c82c
0x61d5a6185bfa3890bf952d4fff6730d023395247
0xd9c43c9d1eb379f8707d4113cf2237d6aa48cfca
0x08a984f1856bdc4234d35af3780ee9a21949cf18
0x3a393d7f3c93566aefb8f4b4780e60778a1f41ab
0xfcbec207ad1d9bd652146eb5ce9b217efe8ab322
0x3defba427321071823d85afdbf5aba2982d5c628
0x5115c9953ec110f54ee71f0f4ea0a7ca60f998dc
0x03e907505bd499a04fafd06f36b99a6572b4d25a
0x2833879c4b1cdcac6c997876f073c923d7d284a8
0x37bd12023a5661c55495952fff2ab16a61a75e1d
0x73d733eefee4284f03eff748cc075d6e01345cd2
0x96c649c7de7610772d7b94d67e08c9da2a43a624
0x7d6d569a3e2eaaf67637e40fd8b88bf547832bd8
0x8b41829209922ef799a84be019a49d2e036fb3c0
```

<details>

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840476/eukrbyorrumld5at5bzc.png)

https://platform.arkhamintelligence.com/visualizer/entity/0xbF7e7150F31f25a857Df5C1aDe3C1FdA54311d00,0xe9e6a0ec4f0b979a28cbe09c852c86b31769a88b,0xc2b877c9bf9ed8821b2adb0adab8d236e9462cd5,0xcf10556fc23d69789abbb4e0cc78ec09f91594ff,0xf12478f003c4cccfc31872b2853de0916129929b,0x648efe3dfe395843b9c8ae424929d5a9e83f9e92,0xc185b40545faf7fb21e69ce26b9282881db42fa7,0x73b22acb6ce9fbd26c3d9f275c5e756a2e312d0a,0xa52bfd65df1cb8b762d97bbb08b298b0bf42c6a7,0x50844f97ed5dd518a06509860cc56f8e269c8008,0x0f11535265a0f8c2389451c30d0d2f8f7b43c82c,0x61d5a6185bfa3890bf952d4fff6730d023395247,0xd9c43c9d1eb379f8707d4113cf2237d6aa48cfca,0x08a984f1856bdc4234d35af3780ee9a21949cf18,0x3a393d7f3c93566aefb8f4b4780e60778a1f41ab,0xfcbec207ad1d9bd652146eb5ce9b217efe8ab322,0x3defba427321071823d85afdbf5aba2982d5c628,0x5115c9953ec110f54ee71f0f4ea0a7ca60f998dc,0x03e907505bd499a04fafd06f36b99a6572b4d25a,0x2833879c4b1cdcac6c997876f073c923d7d284a8,0x37bd12023a5661c55495952fff2ab16a61a75e1d,0x73d733eefee4284f03eff748cc075d6e01345cd2,0x96c649c7de7610772d7b94d67e08c9da2a43a624,0x7d6d569a3e2eaaf67637e40fd8b88bf547832bd8,0x8b41829209922ef799a84be019a49d2e036fb3c0?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

25 wallets ranked from 655k to 2M.
All wallets have between 16 and 24 messages.
Tx Omi X on all at two possible dates except for 0xa8deaa308935ccffa268614eab7fa3789085d443):

![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840477/ldo8wrk9xerfogtkhvp8.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840479/x36gtamtopzw5n1mvgvp.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840480/dti9xbmgetjiyn2xzcbs.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840482/cw5uk5mkoczayryjgee1.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840483/yup7djbm2cnqln7y79wp.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840485/duwqfqwpcfi0otuuixx0.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840486/o2flmn48o7hh4kldxzrs.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840488/faslrke3e71ozpjhacuw.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840489/e2f9mdgp4qvanek5jl1r.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840491/mywob3ih7gufxrlxfsjn.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840492/zgaxgqfj5njfyrnfycpm.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840494/kcs85nfq3bax1jd3wd7e.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840496/t0j59lnefowwodzjajm0.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840497/uu4dkebe0speeixcyi4n.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840499/orbvqixrx1puz2nxluvw.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840500/quhzlvxgztyg5defxjxs.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840502/riedmmdidmj4taalxvni.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840503/okf3zxntlwkq4x8k6btp.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840505/ytlo67gjzq6eerphe2mi.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840506/zrtvkwmyu0pcfsqktnyz.png)

Stargate on the same date, same arrival and departure chain, almost identical amount:
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840508/asrsrfk4vk0h4tfvp2ba.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840509/njhbfkt314gmbgzphv2n.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840511/tmiko4glev60fkcb5g3u.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840512/jj1jex8lriysg2nzwdze.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840514/nai4vphccuippfm03vt1.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840515/jcx1jn07mrfivnvusaj9.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840517/coxgkxdcdinwdyrnmnzg.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840518/tbcwniktv1p6toodzghr.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840520/xjuin8tx3qo4x9k4nxbp.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840522/t8qkx2rmosidfltqom3h.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840523/e3lpnkjdxxfpq5y1bx60.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840525/xzkvehoezwnjjjofslph.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840526/rdcyjeuntstyd6j2laxh.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840528/hjkffsxro0vpuyxt44s0.png)

For the wallets that did not have a Stargate transaction before the OMni X one (0x3a393d7f3c93566aefb8f4b4780e60778a1f41ab, 0xfcbec207ad1d9bd652146eb5ce9b217efe8ab322, 0x3defba427321071823d85afdbf5aba2982d5c628, 0x5115c9953ec110f54ee71f0f4ea0a7ca60f998dc, 0x03e907505bd499a04fafd06f36b99a6572b4d25a, 0x2833879c4b1cdcac6c997876f073c923d7d284a8, 0x37bd12023a5661c55495952fff2ab16a61a75e1d, 0x73d733eefee4284f03eff748cc075d6e01345cd2, 0x96c649c7de7610772d7b94d67e08c9da2a43a624, 0x7d6d569a3e2eaaf67637e40fd8b88bf547832bd8, 0x8b41829209922ef799a84be019a49d2e036fb3c0, and 0xa8deaa308935ccffa268614eab7fa3789085d443) they have a holograph transaction (burning of the same NFT on the same chain, oh how strange KEK):
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840529/t4feda3gqnlucymrtvu2.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840531/nglxfsof9o9ibfstcu2d.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840532/giq3cl9vraem8vivph6h.png)
![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840534/jdqypgz2timjuabnwj9h.png)


```
2 0xe9e6a0ec4f0b979a28cbe09c852c86b31769a88b 2023-08-26 2023-08-21 
3 0xc2b877c9bf9ed8821b2adb0adab8d236e9462cd5 2023-08-26 2023-08-21 
4 0xcf10556fc23d69789abbb4e0cc78ec09f91594ff 2023-08-26 2023-08-21 
5 0xf12478f003c4cccfc31872b2853de0916129929b 2023-08-26 2023-08-21 
6 0x648efe3dfe395843b9c8ae424929d5a9e83f9e92 2023-08-26 2023-08-21 
7 0xc185b40545faf7fb21e69ce26b9282881db42fa7 2023-08-26 2023-08-21 
8 0x73b22acb6ce9fbd26c3d9f275c5e756a2e312d0a 2023-08-26 2023-08-21 
9 0xa52bfd65df1cb8b762d97bbb08b298b0bf42c6a7 2023-08-26 2023-08-21 
10 0x50844f97ed5dd518a06509860cc56f8e269c8008 2023-08-26 2023-08-21 
11 0x0f11535265a0f8c2389451c30d0d2f8f7b43c82c 2023-08-26 2023-08-21 
12 0x61d5a6185bfa3890bf952d4fff6730d023395247 2023-08-23 
13 0xd9c43c9d1eb379f8707d4113cf2237d6aa48cfca 2023-08-23 
14 0x08a984f1856bdc4234d35af3780ee9a21949cf18 2023-08-23 
20 0x2833879c4b1cdcac6c997876f073c923d7d284a8 2023-09-16 
21 0x37bd12023a5661c55495952fff2ab16a61a75e1d 2023-09-16 
22 0x73d733eefee4284f03eff748cc075d6e01345cd2 2023-09-16 
23 0x96c649c7de7610772d7b94d67e08c9da2a43a624 2023-09-16 
24 0x7d6d569a3e2eaaf67637e40fd8b88bf547832bd8 2023-09-16 
25 0x8b41829209922ef799a84be019a49d2e036fb3c0 2023-09-16
```

</details>

## Cluster 23 
6 addy linked to cex deposit 
0x0F70cB29CC848934247E1CC3b2367A72636bFf38

**TLDR**

```
0xc7c79e78e590c05a4a5cbf711904c10a7b4ce75d
0x09691b075f3d87f074c90ada793b9a43decf943d
0x0c0d6460d8939ae75fb8da54e98cdf242e76fa7c
0x573242f52145b2ff1a52a72daeb410b5d209a01a
0xfbde5dbb7407143f633ba20e57f44cdb86918e1b
0x626a2e5bf815e7de174ab1cc06eafe1c10c4e299
0x04f8ce211d3323bb8aeac8cbc47571a8ec0ee119
0x0848d6b87e7fef86ddbf0bed2d1bc192420db003
0xfd6df311e24dded518bc621c81cffbd5d5c2745f
0x10432c560930503064115b78cd13c9bddadd15e5
0x0267215cdabe0e4bbba57d794f9d26ba690371a3
0x7baab6f70119684fa694bf527edfa3dc654a0808
0x7e453f2dbcbc734c2e35efa286021b9994b2caa2
0x0545eb9af253359626cd9856d7a889e641a88ef3
0xa3fec59dcc95ac98434c2f0ce4d6bde7ffa6f2dd
0x98ee6740ca70ae8d5562509f8e05e5d249556a18
0x5b06e163885363d5594bfbe82375023991047060
0x4b133c63ad94d55e8e03be9d94be89d7cbeb7621
0x911631b2582e2f1c71df557f84f3ff3a89aa0c27
0x1e03c73d22253150cd760c9af6682ba8bfc19a1e
0x48957e90ed96a8c7d60d0e4ffbea0e0fae356fa9
0x0e6649fa2de5d631f801e68827eafbbf826def8a
0xe4c34e6503445492727b52b023cb12632d733339
```

<details>
  
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/331840ee-1b24-466c-a35a-8418f4306936)

https://platform.arkhamintelligence.com/visualizer/entity/0x0F70cB29CC848934247E1CC3b2367A72636bFf38,0xc7c79e78e590c05a4a5cbf711904c10a7b4ce75d,0x09691b075f3d87f074c90ada793b9a43decf943d,0x0c0d6460d8939ae75fb8da54e98cdf242e76fa7c,0x573242f52145b2ff1a52a72daeb410b5d209a01a,0xfbde5dbb7407143f633ba20e57f44cdb86918e1b,0x626a2e5bf815e7de174ab1cc06eafe1c10c4e299,0x04f8ce211d3323bb8aeac8cbc47571a8ec0ee119,0x0848d6b87e7fef86ddbf0bed2d1bc192420db003,0xfd6df311e24dded518bc621c81cffbd5d5c2745f,0x10432c560930503064115b78cd13c9bddadd15e5,0x0267215cdabe0e4bbba57d794f9d26ba690371a3,0x7baab6f70119684fa694bf527edfa3dc654a0808,0x7e453f2dbcbc734c2e35efa286021b9994b2caa2,0x0545eb9af253359626cd9856d7a889e641a88ef3,0xa3fec59dcc95ac98434c2f0ce4d6bde7ffa6f2dd,0x98ee6740ca70ae8d5562509f8e05e5d249556a18,0x5b06e163885363d5594bfbe82375023991047060,0x4b133c63ad94d55e8e03be9d94be89d7cbeb7621,0x911631b2582e2f1c71df557f84f3ff3a89aa0c27,0x1e03c73d22253150cd760c9af6682ba8bfc19a1e,0x48957e90ed96a8c7d60d0e4ffbea0e0fae356fa9,0x0e6649fa2de5d631f801e68827eafbbf826def8a,0xe4c34e6503445492727b52b023cb12632d733339?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1

23 wallets ranked between 500k and 1.13M

LZ AGE: 2 at 334 days, 6 at 378 days, 2 at 385 days, 3 at 390 days, 3 at 421 days, and 3 at 423 days.

BTC.b transactions (0xc7c79e78e590c05a4a5cbf711904c10a7b4ce75d, 0x0c0d6460d8939ae75fb8da54e98cdf242e76fa7c, 0xfbde5dbb7407143f633ba20e57f44cdb86918e1b, 0x626a2e5bf815e7de174ab1cc06eafe1c10c4e299, 0x04f8ce211d3323bb8aeac8cbc47571a8ec0ee119, 0x0848d6b87e7fef86ddbf0bed2d1bc192420db003, 0xfd6df311e24dded518bc621c81cffbd5d5c2745f, 0x10432c560930503064115b78cd13c9bddadd15e5, 0x0267215cdabe0e4bbba57d794f9d26ba690371a3, 0x7baab6f70119684fa694bf527edfa3dc654a0808, 0x7e453f2dbcbc734c2e35efa286021b9994b2caa2, 0x0545eb9af253359626cd9856d7a889e641a88ef3, 0x98ee6740ca70ae8d5562509f8e05e5d249556a18, 0xa3fec59dcc95ac98434c2f0ce4d6bde7ffa6f2dd, 0x5b06e163885363d5594bfbe82375023991047060, 0x4b133c63ad94d55e8e03be9d94be89d7cbeb7621, 0x911631b2582e2f1c71df557f84f3ff3a89aa0c27, 0x48957e90ed96a8c7d60d0e4ffbea0e0fae356fa9, 0x0e6649fa2de5d631f801e68827eafbbf826def8a, 0xe4c34e6503445492727b52b023cb12632d733339) cover all the wallets in the cluster except for 3 (but this 3 are linked by CEX wallet deposit & some other similar l0 behavior):
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/8ca772c2-1f45-489c-b9cc-b4c898b28cba)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/cfeec8db-3173-486d-83aa-4c6e0ca6b523)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/b9678d67-5fb7-48db-8750-d3f01c782cbf)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/966c9a19-f18d-4b9f-9601-4271d8814f80)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/faa696d2-83d9-4388-817e-c7f0220c749e)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/0e4f793c-5452-4d46-8516-6050f289e911)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/c7a7e25e-6495-4c34-be7a-1ba3454763e3)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/6994b4de-bebc-473a-a9fe-237afbc538a9)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/1709bfc2-e7ee-468e-b384-388ead3e35a8)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/6ea50d3c-5123-43b6-aa83-75858b4017a1)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/edac0ad8-9e1e-4387-a03d-4cc8ba4ad597)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/11e9e2eb-200c-42b5-83be-ac8f8f9d4005)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/0a823902-ffe2-4e92-99a5-c006ecb30866)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/482eff3a-3e4c-45f5-89f3-a15c3a260533)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/e94fbf89-b7c5-48f1-8dd6-8e85e9244ece)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/7ffec922-b824-4bf5-aa25-2798873bcbe6)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/38027c09-31ec-423b-8caa-067c0fe9ec55)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/8d8f609e-dca1-49d9-b463-139cb8a19a32)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/30bb2daa-bb06-496a-8c8f-b98f5310de75)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/3bba79ff-3765-4a20-a385-5b038913217c)

Finally, many addresses have APTOS Bridge transactions in common, on close dates for all the following addresses: 0xc7c79e78e590c05a4a5cbf711904c10a7b4ce75d, 0x0c0d6460d8939ae75fb8da54e98cdf242e76fa7c, 0xfbde5dbb7407143f633ba20e57f44cdb86918e1b, 0x626a2e5bf815e7de174ab1cc06eafe1c10c4e299, 0x04f8ce211d3323bb8aeac8cbc47571a8ec0ee119, 0x0848d6b87e7fef86ddbf0bed2d1bc192420db003, 0xfd6df311e24dded518bc621c81cffbd5d5c2745f, 0x10432c560930503064115b78cd13c9bddadd15e5, 0x0267215cdabe0e4bbba57d794f9d26ba690371a3, 0x7baab6f70119684fa694bf527edfa3dc654a0808, 0x7e453f2dbcbc734c2e35efa286021b9994b2caa2, 0x0545eb9af253359626cd9856d7a889e641a88ef3, 0xa3fec59dcc95ac98434c2f0ce4d6bde7ffa6f2dd, 0x98ee6740ca70ae8d5562509f8e05e5d249556a18, 0x5b06e163885363d5594bfbe82375023991047060, 0x4b133c63ad94d55e8e03be9d94be89d7cbeb7621, 0x911631b2582e2f1c71df557f84f3ff3a89aa0c27, 0x48957e90ed96a8c7d60d0e4ffbea0e0fae356fa9, 0x0e6649fa2de5d631f801e68827eafbbf826def8a, and 0xe4c34e6503445492727b52b023cb12632d733339.

![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/032d661b-370f-45cc-bd17-00c80bded96f)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/2e6c7a83-3fc3-47b9-8d5a-ed1378acda06)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/420441ba-ef5e-4833-9364-1575f951ac14)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/67b60c96-a115-4bd5-bfa3-1ee2e5824e1d)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/7b9a2f81-bbf8-46eb-9d48-ba8c6e1e0629)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/76ef610c-8038-43ea-af06-49f4eb37bc2c)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/1c82300d-ff13-4b50-b0d3-8a4a84c83829)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/70aa32c7-79e5-40a0-b8e8-c89fd2ebfd27)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/e209032c-76a5-4bc7-b290-df54774b8138)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/63781131-242b-4a73-9092-99be456ad9e8)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/801d4b74-d27c-43ff-ae9a-738ac9bdcd59)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/13111af2-d6da-4c0d-9747-91e7d766e1d5)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/911aff8d-3ff5-4001-a16b-072747204277)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/98d363a1-86bd-408f-aec7-bb1f5395abf6)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/fc8fa0c3-36ba-4789-871e-78628f7f9d1e)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/3b15504f-058a-4c65-8d65-6d22edc2201c)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/3a240476-c08a-4b1a-ae99-aa0e3994baee)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/b90ce077-7935-4360-9add-59cc36dc3044)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/162a4e5e-ab9e-4ef8-93c5-317301924c8c)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/21f41469-1fb8-421c-be82-6764552ee707)

  
</details>

## Cluster 24 

ALL LINKED TO SAME CEX DEPOSIT ADDRESS (Binance)
0x262D078F1992c69e262702091e87a4264163EFc4

```
0xc38ef02b2bd402abb636b25c357363dc1d72778d
0xc3bab196e6e7d7ad96d015d929ffb89092b3787a
0x3affc191c8ebcaf8ce6223af19dac32f14fce1da
0xeca6f41e19515abd044d0908658d94b4e1cd4f50
0x43a44db9aca6d3d24accdb896010fc2564c5460b
0x8b6addb0fabccd670209514418d64cb1b7054fcc
0xd4ea9478ea1d7ea32d4ffb1ea60806738f37ca86
0x6dcebcfc394f9a2dc97c608f622ae9a9f95ef17a
0x113cb8839465b288ecbfe029fdd7a863569994b9
0x062ee106ee7357a9aace9f6ed943a3150e80dd9a
0x9f21587a29c5396f78b40c3db04e29445dd0cca0
0xc1524b6852275fe05d78efa22df107f180775e28
0xfbade72509f3e60ddbceab82af68255630de72e8
0xbcc6a551c78ab65f99b10a487cccb1ca832badc2
0xdf28b746de984279d4ff9f29283e4c09ece75e50
0xd436f298ccfa39a7f1a55ae78df326dd75716bcd
0x1d6f018cfc832e2f09466a184cb3e781d11ce5c1
0x1423f0fb45bec4cd4f84599a0bda7ab0c502138a
0xd735d490b7169e3a3f6fe25e0875f9686fb425ea
0xfc676a4e5ce0a3cf65669f37e9ebd301efeed2d4
0x922745fe9ac1e9467e8b2d57f80fddd49961933a
0xb5dc80fce25f5d38dfa1d8b97f6bbf8c769d5a73
0x2538a4fc329da01340990461d2d357086aabdd55
0x08d28455f55bc83d100c934e62bf66aedf307659
0xd75368c11af7b7df4d67e9f123f54f1a331fda19
0x911e6c4e67119c7ea9915fe07aa24be5732c3a47
0xc4ae6ece3c4eafdc26f6c83044b5e881932a1152
0x7974925f460182ce7bcead10c7c0c81ae38b7c86
0x5fbb35a9949623357028c707f1d84040a5db0369
0xd10dfe34ebf963ad2519dc0fd5f6bffca6effe51
0x73c3de7be6349d201d709862e5a4002897eb0a8f
0xeb0b0ffb7de50613380ed2da39af397ff568ba43
0x7287c77dd1059193c464ddc4631faff175a9986b
0x9170075d875db55d1753f1782d978840dfa0f112
0x9333a6aeb69301d72a1ac06aae4156f2c011de23
0xef1320e6cddf67a7adfcd08acac821a1617dc147
0x7f17b443df49c03cd5a44eaadc96bc01c1162f08
0x918e6c4d06595cd563eee33876168969a2f24759
0x393f40e48b3924a18365fda57fa0f7b6178140ce
0x0926b01d2f778389a7d21a9d584978d0819b1c31
0x8ad8eb7817dad784e5e19ae2ae852b9adb1dc741
0x8e4cc79d57291fb1fc1bfe1b9f48d21cc3ba8092
0x61874c6ecf80650858e8cb7c7a650e6f6daefd18
```


<details>

![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/6d068df8-def4-4ff4-a5b3-6743011a8f44)



https://platform.arkhamintelligence.com/visualizer/entity/0x262D078F1992c69e262702091e87a4264163EFc4,0xc38ef02b2bd402abb636b25c357363dc1d72778d,0xc3bab196e6e7d7ad96d015d929ffb89092b3787a,0x3affc191c8ebcaf8ce6223af19dac32f14fce1da,0xeca6f41e19515abd044d0908658d94b4e1cd4f50,0x43a44db9aca6d3d24accdb896010fc2564c5460b,0x8b6addb0fabccd670209514418d64cb1b7054fcc,0xd4ea9478ea1d7ea32d4ffb1ea60806738f37ca86,0x6dcebcfc394f9a2dc97c608f622ae9a9f95ef17a,0x113cb8839465b288ecbfe029fdd7a863569994b9,0x062ee106ee7357a9aace9f6ed943a3150e80dd9a,0x9f21587a29c5396f78b40c3db04e29445dd0cca0,0xc1524b6852275fe05d78efa22df107f180775e28,0xfbade72509f3e60ddbceab82af68255630de72e8,0xbcc6a551c78ab65f99b10a487cccb1ca832badc2,0xdf28b746de984279d4ff9f29283e4c09ece75e50,0xd436f298ccfa39a7f1a55ae78df326dd75716bcd,0x1d6f018cfc832e2f09466a184cb3e781d11ce5c1,0x1423f0fb45bec4cd4f84599a0bda7ab0c502138a,0xd735d490b7169e3a3f6fe25e0875f9686fb425ea,0xfc676a4e5ce0a3cf65669f37e9ebd301efeed2d4,0x922745fe9ac1e9467e8b2d57f80fddd49961933a,0xb5dc80fce25f5d38dfa1d8b97f6bbf8c769d5a73,0x2538a4fc329da01340990461d2d357086aabdd55,0x08d28455f55bc83d100c934e62bf66aedf307659,0xd75368c11af7b7df4d67e9f123f54f1a331fda19,0x911e6c4e67119c7ea9915fe07aa24be5732c3a47,0xc4ae6ece3c4eafdc26f6c83044b5e881932a1152,0x7974925f460182ce7bcead10c7c0c81ae38b7c86,0x5fbb35a9949623357028c707f1d84040a5db0369,0xd10dfe34ebf963ad2519dc0fd5f6bffca6effe51,0x73c3de7be6349d201d709862e5a4002897eb0a8f,0xeb0b0ffb7de50613380ed2da39af397ff568ba43,0x7287c77dd1059193c464ddc4631faff175a9986b,0x9170075d875db55d1753f1782d978840dfa0f112,0x9333a6aeb69301d72a1ac06aae4156f2c011de23,0xef1320e6cddf67a7adfcd08acac821a1617dc147,0x7f17b443df49c03cd5a44eaadc96bc01c1162f08,0x918e6c4d06595cd563eee33876168969a2f24759,0x393f40e48b3924a18365fda57fa0f7b6178140ce,0x0926b01d2f778389a7d21a9d584978d0819b1c31,0x8ad8eb7817dad784e5e19ae2ae852b9adb1dc741,0x8e4cc79d57291fb1fc1bfe1b9f48d21cc3ba8092,0x61874c6ecf80650858e8cb7c7a650e6f6daefd18,0xf7609b80fd824559b7db33b056abe4bf0275cde0?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1



44 wallets classés entre 170k et 1,9M

LZ day: 4 à 369, 6 à 371, 13 à 372, 6 à 373, 3 à 374, 6 à 375, 2 à 376, 




USDT transactions on Pancake Swap around the same day and similar pattern for the following wallets:

0xdf28b746de984279d4ff9f29283e4c09ece75e50
0xd436f298ccfa39a7f1a55ae78df326dd75716bcd
0xbcc6a551c78ab65f99b10a487cccb1ca832badc2
0x9f21587a29c5396f78b40c3db04e29445dd0cca0
0xfbade72509f3e60ddbceab82af68255630de72e8
0xc1524b6852275fe05d78efa22df107f180775e28
0x1423f0fb45bec4cd4f84599a0bda7ab0c502138a
0x5fbb35a9949623357028c707f1d84040a5db0369
0xd735d490b7169e3a3f6fe25e0875f9686fb425ea
0xb5dc80fce25f5d38dfa1d8b97f6bbf8c769d5a73
0x2538a4fc329da01340990461d2d357086aabdd55
0x7974925f460182ce7bcead10c7c0c81ae38b7c86
0xd75368c11af7b7df4d67e9f123f54f1a331fda19
0xc4ae6ece3c4eafdc26f6c83044b5e881932a1152
0xd10dfe34ebf963ad2519dc0fd5f6bffca6effe51
0x911e6c4e67119c7ea9915fe07aa24be5732c3a47
0x393f40e48b3924a18365fda57fa0f7b6178140ce
0x918e6c4d06595cd563eee33876168969a2f24759
0x0926b01d2f778389a7d21a9d584978d0819b1c31
0x7287c77dd1059193c464ddc4631faff175a9986b
0xeb0b0ffb7de50613380ed2da39af397ff568ba43
0x9170075d875db55d1753f1782d978840dfa0f112
0x9333a6aeb69301d72a1ac06aae4156f2c011de23
0x7f17b443df49c03cd5a44eaadc96bc01c1162f08
0xef1320e6cddf67a7adfcd08acac821a1617dc147
0x1d6f018cfc832e2f09466a184cb3e781d11ce5c1
0xeca6f41e19515abd044d0908658d94b4e1cd4f50
0xd4ea9478ea1d7ea32d4ffb1ea60806738f37ca86
0x8b6addb0fabccd670209514418d64cb1b7054fcc
0x43a44db9aca6d3d24accdb896010fc2564c5460b
0x6dcebcfc394f9a2dc97c608f622ae9a9f95ef17a
0xc3bab196e6e7d7ad96d015d929ffb89092b3787a
0x3affc191c8ebcaf8ce6223af19dac32f14fce1da
0x01bc3aebbe7352619ebb37fe258036d81475b84c


![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/7e34b662-a937-4e9e-9421-cd4f619526be)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/1edfff0f-2c88-4d93-abe0-0a8d4a3a2048)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/94e7ae51-bcc4-45a2-a797-3a22ec09d9a9)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/3f845cf5-9604-4b9c-aa9c-4d37fa1cf546)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/7c0b4f7a-be5a-4146-b68d-5477342f804c)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/b5d324ab-1009-40b4-a7ac-b128791ea5d6)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/e06e2aba-3e33-4726-b618-9f35d3fbd008)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/3281fb10-d587-4eae-ae8a-94c72686f2d5)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/924477a1-e67c-403f-8815-f1bc66867008)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/3e836419-7d45-4083-be32-fa11ae0663dd)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/057afce1-fb64-490c-8553-843897d1a2c9)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/86a6995b-379c-4a7a-8e4a-4b38b97277a7)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/a4d98f8e-0fc3-4355-a090-9eaf084d16c4)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/9fe86f7c-cae5-49ef-b8bd-cea20373c15b)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/30b055cb-8ebc-4ac1-ab3f-6db1c3678b56)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/292d174a-49a3-4628-b2fc-c5c39d014e33)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/b4a7b05f-4d59-4100-9b9b-d3318bc5cdcc)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/9ea6ea2a-4cf1-4e2e-99d1-d68a85513e6e)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/8eb060c2-44db-4c87-be25-34d3c8c9f578)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/c35702dc-1596-4b68-83e8-b61641e9565b)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/afcc6ecb-b0d6-43d7-bf3e-95efbcad1668)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/798c9cda-19d6-4b03-97b7-b7f3369e6073)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/05559540-aae3-4bfe-89c1-70592156185f)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/040e089d-8a0b-4a76-83f0-6fccab70d4af)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/fadf4553-58d2-4755-8cf6-1b32d0e0dacd)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/212e85f8-33c2-42f3-b1a4-3b03404f308e)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/f1473f50-86d6-4ac2-a721-0b15a3644d94)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/1dd2d97a-943b-4116-95c6-e358eaea66c8)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/e07471af-cd6c-4b4d-ae5e-8e3692bc86f8)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/7b2a9bf0-3a16-4153-b839-ef752ccac5c8)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/4e255f14-705e-4d8d-a741-ce0595fd0bae)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/677a8365-227e-448d-bf3b-db28963a0a19)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/01977e2e-ff87-4b8a-a1d0-1443d5640047)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/dc6abf44-3c15-448d-a2b9-f7332fb41764)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/fefeb913-4704-44b7-a25b-4c1b57659aa5)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/36bd4a33-54e3-49ac-8ae0-e34b982c0e6b)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/736f41b3-134a-40a9-932e-cabadd419cc6)

Additionally, all wallets except for 0x01bc3aebbe7352619ebb37fe258036d81475b84c share a common activity: they used the Harmony bridge from Harmony to BSC between May 17 and May 23. There is one transaction on June 13, but it has the same amount and same source/destination chain. The amounts transferred are nearly always 0.017 ONE.
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/5eda88f0-4876-40e6-9aac-02b5ac181044)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/c804151f-31df-4ae2-9bab-4e966320a157)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/b9403d8f-2bb9-4685-883b-1a2e7b820c15)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/f6138cb0-8ebf-4b66-990c-e0af3bec25ac)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/5288df17-d3f0-43fd-b581-7531d1a77b2b)

ETC ETC (they still CEX linked, this is just more obvious arguements)

bsc stg lock
```
1 0xe2f7102b63119ee436a80a79a554e5d16954a125 2024-02-27   2023-12-25   2023-02-24   
2 0x84993422cb9f8ed9cd605c06499d3806bbe606d7 2023-12-25   2023-02-24   
3 0xcbacba5318efbfcd9b86564d4eca555c1ba0d6de 2023-12-30   2023-02-23   
4 0x3fdd65ba78d1d94cc8a567404bf28be1dc6029ff 2024-02-29   2023-12-25   2023-02-22   
5 0x9b6f406875ba9ebd798d156b063909ecbee4ff85 2024-02-29   2023-12-25   2023-02-22   
6 0x6e0f64bfa3d879abafcbf71dc5252ea40d08ceda 2024-02-29   2023-12-25   2023-02-22   
7 0x67689bf78640cdfe82b44935ceaf8aa462d60f69 2024-02-29   2023-12-25   2023-02-19   
8 0xeb52c531a253e4c849fd39b515405f4d6370964e 2024-01-19   2023-02-19   
9 0x36aa63b68dc4bc4d02d475a9481eee62049eef57 2024-01-19   2023-02-19   
10 0xb0918acfaeba07c0fa55fc972c56e41a4ade0c70 2024-02-29   2023-12-25   2023-02-19   
11 0x8768e65712b747fabf39e00e3c07a9d49dfcf677 2023-12-25   2023-02-19   
12 0x28134f152c2117666d7568889d3b9c54316cf032 2024-02-29   2023-12-25   2023-02-18   
13 0xeed6a9df7fae961b756cd4576305698f45ca8673 2024-02-28   2023-12-25   2023-02-22   
14 0xe5195d2faed140e5f24ba67706dc765f353d6d3b 2023-12-27   2023-02-18   
19 0xcd34cc3569ec6a6ba0e5fecf8841b3d02551a465 2024-02-29   2023-12-27   2023-02-15   
20 0xb0a2e7a1a6c27b8b6c3b5ea3643c3230c59bd0a9 2024-02-29   2023-12-27   2023-02-17   
21 0x9d47915995cc40494cc3eebf251758171cfd334a 2024-02-29   2023-12-27   2023-02-18   
22 0x3584f16cf0182ff810b6b1066361d44f5f38a5a9 2024-02-29   2023-12-27   2023-02-17   
23 0x341d386cafc5469e65244640f7ecfb3d86084223 2024-02-28   2023-12-25   2023-02-22   
24 0x591629548d30dbc9c15480a5692e158545efcfce 2024-02-28   2023-12-25   2023-02-22   
25 0x29f6dd6473dfeafc508f06b487c915017b9e04da 2024-02-28   2023-12-25   2023-02-22   
```

</details>



## Cluster 25


17 wallets linked to cex deposit (binance)
0x2acDe5683b7157D9646Ed9C2f6f2363BC590dc01

```
0x929bd1f03942125e1dccf0cfeb012e9c165351dc
0x523356181f718b6b830fddfcd00b54f497afceb2
0x15b786cbd9247ed31618aaf4a80420ef0098a270
0xcc81adc585668bfa0bccbd2f39f0ce42dd2bc3ee
0x08026662852f39a61632963968d683faf2beab42
0x741f536fe8f32e612dcb3f1d4a7996474060bf8c
0x5a49686eab54a9e357ab258c016206006cf9e9a0
0x34d3db5a50779f4419a571d25e831880f5e64e23
0x33dd3e3962d7e526478831b90e0006f9db7b9ee3
0xb623bfd0e079f1fcb62f42ab570532778bacc267
0x0922c4f24980dbfd8f6cfd2b922dd3b7c16a37ae
0x007e1a4fb6af68ce1ab1dd2713b5dc9e534f90ec
0x24d4f6ab1c147655bd0225228cb631323674d176
0x1e22d40b6bf7b91b17af80ed55d210cebec36bab
0x221fe5c30cfba203cf3baae4cafe23750b7091d1
0xf06bf69206eb67213bb7587956023e285f00d644
0x736b190f0151765dbe88e6cf657051bc1db509a1
0xa1b803cd60e50743447b6f426298c40dbc28c416
0x59ef91c1e5439c063c53a82cb63a4142f473381b
0x56ebaaafd8724400197ad0e2bbb9ba4cecc6a689
0xb9544ccb2121a63b2c5e8c17443b47fd4a07b0ea
```

<details>

![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/84166af1-5549-4367-becd-2252470f0359)


https://platform.arkhamintelligence.com/visualizer/entity/0x2acDe5683b7157D9646Ed9C2f6f2363BC590dc01,0x929bd1f03942125e1dccf0cfeb012e9c165351dc,0x523356181f718b6b830fddfcd00b54f497afceb2,0x15b786cbd9247ed31618aaf4a80420ef0098a270,0xcc81adc585668bfa0bccbd2f39f0ce42dd2bc3ee,0x08026662852f39a61632963968d683faf2beab42,0x741f536fe8f32e612dcb3f1d4a7996474060bf8c,0x5a49686eab54a9e357ab258c016206006cf9e9a0,0x34d3db5a50779f4419a571d25e831880f5e64e23,0x33dd3e3962d7e526478831b90e0006f9db7b9ee3,0xb623bfd0e079f1fcb62f42ab570532778bacc267,0x0922c4f24980dbfd8f6cfd2b922dd3b7c16a37ae,0x007e1a4fb6af68ce1ab1dd2713b5dc9e534f90ec,0x24d4f6ab1c147655bd0225228cb631323674d176,0x1e22d40b6bf7b91b17af80ed55d210cebec36bab,0x221fe5c30cfba203cf3baae4cafe23750b7091d1,0xf06bf69206eb67213bb7587956023e285f00d644,0x736b190f0151765dbe88e6cf657051bc1db509a1,0xa1b803cd60e50743447b6f426298c40dbc28c416,0x59ef91c1e5439c063c53a82cb63a4142f473381b,0x56ebaaafd8724400197ad0e2bbb9ba4cecc6a689,0xb9544ccb2121a63b2c5e8c17443b47fd4a07b0ea?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1


21 wallets ranked between 500k and 1.8M.

Layer Zero Days: 3 at 283, 2 at 286, 3 at 300, 2 at 409, 2 at 413, and 2 at 429 among others.

Swap via MetaMask and then lock STG Stargate on Polygon for 7 addresses (0x929bd1f03942125e1dccf0cfeb012e9c165351dc, 0x523356181f718b6b830fddfcd00b54f497afceb2, 0x15b786cbd9247ed31618aaf4a80420ef0098a270, 0x741f536fe8f32e612dcb3f1d4a7996474060bf8c, 0x33dd3e3962d7e526478831b90e0006f9db7b9ee3, 0xb623bfd0e079f1fcb62f42ab570532778bacc267, 0x7263267aca13ef96ed425c957760b6f20edee9bb).
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/9e2facf7-3759-4604-962e-c9b7713160dd)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/1716eeaa-dd72-4017-8968-b9360954ede0)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/5ac5db11-3497-419b-99bc-5afed36f5d7c)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/5a158c7a-f6df-459d-8556-da7ab5e79a2e)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/b300d5cd-8a60-4ba3-8e8f-9664bb5ae59f)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/d14eacff-71ad-47d4-b093-7e456e9ff567)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/eaab4974-2a43-4efe-b83d-a89cbfac62e4)


There is a Stargate transaction from 2 months ago between two Merkly transactions (there are many Merkly transactions, so it already suggests a sybil) for all the wallets except one (0x7263267aca13ef96ed425c957760b6f20edee9bb) from OP to ARBI with similar amounts on April 10th.
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/67cf16b1-f7ab-4227-9231-b207b2cbf91a)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/66a4a4f8-711f-461e-b6b6-ed9d5743b29b)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/6686e645-cef8-4a8f-8426-2cb67040e5b2)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/116becca-835a-4676-8732-75c56b96daf1)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/d70fa36b-5a6e-4da8-91be-ae864ca315dd)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/256a3f1b-bdfe-44df-8a75-dc0413cc6c4e)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/5cbf4f43-3e4a-49de-a5d0-53421a9c8525)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/12066853-17ee-4124-8159-6de1d265aeea)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/a51c665b-a0f2-4ec1-925c-3e81a62ac0d2)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/22fab057-552c-4567-b21a-802580683e6e)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/09f5b53d-cad5-46a3-9746-962913097398)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/d161a2a3-538c-4b95-8d41-648f9ac900a6)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/40503f7d-41a5-4bc0-b464-80266d21c3fc)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/dd15fc0d-1458-4abf-a271-4b0a51007cd7)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/56d8bd42-1ccd-4827-bf2a-4647b803c18d)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/a15df161-9338-4713-ab3f-29984f858b33)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/45e4900f-275d-4025-9463-c6445f3272db)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/f416f2c1-ab02-40dc-9f4f-c351d60f08aa)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/d593d607-d3df-4732-bd2d-7182f4800e90)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/dc4a38f5-5ab0-4795-bc66-e0ec854b3e3b)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/299fc4f1-9901-453f-b059-2c035bb3b548)


</details>

## Cluster 26

15 linked cex wallet deposit OKX
0x838A9b0270bEa444E0268464E7e178337721F33F

```
0x2c1fe28d9025c436fa9332bbcb3065d9108106bb
0xb0d9791bc4fb96a5efd342fe7637dba42bd1c33a
0x3ebc0b58f1a24381ef63d972a67412eaec96f1c7
0x09671e6abe947c26b37c26ff6713211409a62c0e
0x42336f5828270acbf33891b9b7bb0a231e750000
0x2340220b8de22ddcf36e128f03ec2eda42a19081
0x54c5dbbd063793afaa5643cfc103cb825cc1001e
0xc8d6d3ab0880af69adfa3bdede290584018aaa72
0xa0f8f114f3ce69abe93bcf7661ab17615564933c
0xb6c6620a398fe658a236f526e8f7a8e1d91ac74f
0xaaf19920c876997184d370c8a26afc81e0f53069
0x3e1ca33b00314691c910519126c14cb636b156b4
0x329bbee2be26fa6a18a469690081ec7f1dc92256
0x18d8f615790a9bc7277a0c7888627c26f98a6a71
0x6c7c5830f7278cdf75b2c9aed6022c99b43bf063
0xf86d9def2488eb81570ad0f8c3309e3611d65de8
0x9a1b60e68f13927dc64b22657e162d2b1ff6066f
0x27c0c6d39fd6412b4fbe8a0f1b2d752baf8898f7
0x6b5f7f0758f9267a23f7cd4f999c7a5236c5e38c
0xb820c484bac96f6569ee7cbc32f5e5f4845b3ee5
0xa26976292ae8cc8d5fb877a0c204404bf8deb399
0x7b9338e8439296a2bc1512130fda03e3a6d3c822
0x5ff4e80c345eb0b582cd512a10bcc0698e884032
0x271fed2c756f87fbba4ff0874c4924b6813db589
0xe8d604527f6ce050ba012e180f5b492820682575
```

<details>

![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/a85a529a-bd08-46d4-a7f3-2a11fcdc4232)


https://platform.arkhamintelligence.com/visualizer/entity/0x838A9b0270bEa444E0268464E7e178337721F33F,0x2c1FE28d9025c436Fa9332BbcB3065D9108106BB,0xb0D9791BC4fb96A5efd342FE7637dBa42bd1C33a,0x3ebc0B58F1A24381EF63d972a67412EaEC96f1C7,0x09671E6AbE947C26b37C26ff6713211409a62C0E,0x42336f5828270aCBF33891b9B7BB0A231E750000,0x2340220b8DE22dDCF36e128F03EC2Eda42a19081,0x54c5DBBD063793aFAa5643Cfc103Cb825cC1001e,0xC8D6d3AB0880aF69adFa3bDEde290584018AAA72,0xa0f8F114F3cE69ABe93bCf7661ab17615564933C,0xb6c6620a398fe658A236f526e8F7A8E1D91aC74F,0xaAf19920c876997184d370c8a26Afc81e0F53069,0x3E1ca33B00314691c910519126c14cB636B156b4,0x329BBEe2Be26Fa6A18a469690081Ec7F1DC92256,0x18d8f615790a9bc7277A0C7888627c26f98A6A71,0x6C7C5830F7278CDF75B2C9AEd6022c99B43BF063,0xf86d9def2488eB81570Ad0F8C3309e3611d65De8,0x9A1b60e68F13927dc64b22657e162D2B1FF6066F,0x27C0c6D39fd6412b4fBe8a0f1b2d752bAf8898f7,0x6B5f7f0758f9267A23F7cD4F999C7a5236c5E38c,0xb820C484BAc96f6569Ee7cbC32f5e5F4845b3ee5,0xA26976292Ae8Cc8D5FB877A0c204404Bf8DEB399,0x7b9338E8439296A2Bc1512130FDa03E3a6d3C822,0x5Ff4e80C345Eb0b582cd512A10bCc0698e884032,0x271FED2c756f87fBBa4FF0874C4924B6813DB589,0xe8D604527f6CE050Ba012e180f5B492820682575?flow=self&positions=%7B%220x54c5DBBD063793aFAa5643Cfc103Cb825cC1001e%22%3A%7B%22fx%22%3A-7%2C%22fy%22%3A-59%7D%2C%220x2340220b8DE22dDCF36e128F03EC2Eda42a19081%22%3A%7B%22fx%22%3A-24%2C%22fy%22%3A-60%7D%2C%220x6B5f7f0758f9267A23F7cD4F999C7a5236c5E38c%22%3A%7B%22fx%22%3A-39%2C%22fy%22%3A-56%7D%2C%220x7b9338E8439296A2Bc1512130FDa03E3a6d3C822%22%3A%7B%22fx%22%3A-12%2C%22fy%22%3A-11%7D%2C%220x27C0c6D39fd6412b4fBe8a0f1b2d752bAf8898f7%22%3A%7B%22fx%22%3A-48%2C%22fy%22%3A-44%7D%2C%220xC8D6d3AB0880aF69adFa3bDEde290584018AAA72%22%3A%7B%22fx%22%3A-56%2C%22fy%22%3A-30%7D%2C%220xa0f8F114F3cE69ABe93bCf7661ab17615564933C%22%3A%7B%22fx%22%3A-57%2C%22fy%22%3A-17%7D%2C%220xb6c6620a398fe658A236f526e8F7A8E1D91aC74F%22%3A%7B%22fx%22%3A-54%2C%22fy%22%3A-4%7D%2C%220x42336f5828270aCBF33891b9B7BB0A231E750000%22%3A%7B%22fx%22%3A-47%2C%22fy%22%3A6%7D%2C%220x3E1ca33B00314691c910519126c14cB636B156b4%22%3A%7B%22fx%22%3A-40%2C%22fy%22%3A17%7D%2C%220xf86d9def2488eB81570Ad0F8C3309e3611d65De8%22%3A%7B%22fx%22%3A-33%2C%22fy%22%3A-37%7D%2C%220xb0D9791BC4fb96A5efd342FE7637dBa42bd1C33a%22%3A%7B%22fx%22%3A-5%2C%22fy%22%3A-39%7D%2C%220x3ebc0B58F1A24381EF63d972a67412EaEC96f1C7%22%3A%7B%22fx%22%3A7%2C%22fy%22%3A-54%7D%2C%220xA26976292Ae8Cc8D5FB877A0c204404Bf8DEB399%22%3A%7B%22fx%22%3A22%2C%22fy%22%3A-46%7D%2C%220x18d8f615790a9bc7277A0C7888627c26f98A6A71%22%3A%7B%22fx%22%3A36%2C%22fy%22%3A-36%7D%2C%220x329BBEe2Be26Fa6A18a469690081Ec7F1DC92256%22%3A%7B%22fx%22%3A40%2C%22fy%22%3A-19%7D%2C%220x5Ff4e80C345Eb0b582cd512A10bCc0698e884032%22%3A%7B%22fx%22%3A42%2C%22fy%22%3A-4%7D%2C%220x6C7C5830F7278CDF75B2C9AEd6022c99B43BF063%22%3A%7B%22fx%22%3A39%2C%22fy%22%3A8%7D%2C%220xe8D604527f6CE050Ba012e180f5B492820682575%22%3A%7B%22fx%22%3A30%2C%22fy%22%3A18%7D%2C%220xb820C484BAc96f6569Ee7cbC32f5e5F4845b3ee5%22%3A%7B%22fx%22%3A18%2C%22fy%22%3A25%7D%2C%220x2c1FE28d9025c436Fa9332BbcB3065D9108106BB%22%3A%7B%22fx%22%3A-29%2C%22fy%22%3A2%7D%2C%220xaAf19920c876997184d370c8a26Afc81e0F53069%22%3A%7B%22fx%22%3A-27%2C%22fy%22%3A25%7D%2C%220x9A1b60e68F13927dc64b22657e162D2B1FF6066F%22%3A%7B%22fx%22%3A-13%2C%22fy%22%3A27%7D%2C%220x09671E6AbE947C26b37C26ff6713211409a62C0E%22%3A%7B%22fx%22%3A3%2C%22fy%22%3A28%7D%2C%220x271FED2c756f87fBBa4FF0874C4924B6813DB589%22%3A%7B%22fx%22%3A19%2C%22fy%22%3A-23%7D%7D&sortDir=desc&sortKey=time&usdGte=0.1

25 wallets, ranging from 600k to 1.3M, all utilized the Aptos Bridge on the same day, with transfers originating either from Arbitrum (Arbi) or Optimism (OP) and terminating on Aptos.
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/85dcf0b3-7c57-4685-ab9f-c7d8d533019d)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/e660bc37-609b-409a-a23c-1d3faa74706f)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/763cbd00-1563-4afa-b1c4-6d741dbf7696)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/24f9c9b8-eeb9-4e56-a999-07bb67121dbb)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/04bef2fa-7ac8-43db-96f5-270cc29ed949)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/f56a28d5-fb51-4e71-b7dd-02cd6c33a414)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/78202401-d4a9-4e26-b3d8-42d1088405df)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/512d487c-1b7e-4a5a-82f2-78c5684edbaf)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/14acc368-df63-4685-82df-bafbb9da1722)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/1f02d1e5-925e-41b3-abd3-5d38fe1a4280)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/c5f76c61-18f2-4224-af30-cd83fc9d8dd3)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/a93b9875-9123-4518-8c08-424450f17e05)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/990f1ca7-4952-4520-801e-d4642e994ada)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/fe4d9b41-0845-4c80-806c-43d3c24a3eaa)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/6fc7c7f0-4800-4af4-8dd7-609a0ee36e0c)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/018ad7f8-bc6f-48fc-a405-33fcde5c07ed)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/b1437afe-80ee-45bc-ab8e-33ede9558e59)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/731adabf-db03-4bf2-9b22-155e58c91078)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/55264d9e-e5be-478f-8520-b3fbbb964505)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/dc617967-c85c-42a6-ab48-3b0506a48821)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/88520e05-54eb-4beb-8bb0-08dcb2b9b146)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/714732b7-a28f-444b-a422-b2161f87d845)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/fcf5189a-0614-4e65-bc09-edbf578de357)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/25a49b4e-3d64-461d-b8d0-2901068997ca)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/0fd5b7d3-731f-4e68-9b52-732f1a2d567c)

  
</details>

## Cluster 27

7 linked 
0x888c7fc7dFced7b23F20D621a4496fb1BdBa0568

```
0x39ed2edc4eecbaf67d301915d41718a2453ce81e
0xedda713a5875df7af78ba6907e3a8f3299ae58dd
0x70d912fb0315c94693a66f1e7384c593594bf476
0x53630aa134efbfba925938ada988922bbab42443
0x5d9179c204655d562b8e6fb6faa3c1693725101d
0x4c30d8ee462240f927dd94c5a214784594b0b58e
0x139b0bf3426f35aa4fa807d88e181f6c6de5e01f
0x1865286096e66f464261f4f2aa1b5311fc0ce2f5
0x18936900603b18d12f2dbbeab558468fdfde5a7b
0x1b5505a22057f68136d5938156b71e6a385df533
0x4ab4bae5c75155716fda8ec7704a29e38525eb82
0x7965eb18c68f26f01db9677bd61e656a79217dc0
0x897cb796c5d296b4a32d8e0604b23947d9b29c8d
0x75be24119348435d29d45f2182624ba4104d7920
0x7f41ce43077b02906d30961f2053ac1a57e10b6a
0xb4560bc65ba37f84f65c2f71c70d0815d356818f
0x789e4be4e102a0a69e6d793969ae5a1ba8173586
0xd1df2ff3dbcbdbb0ef9fc896944fd026801829f5
0xd6b0a3a1c174abd461decaba5ff0eff50d6f8071
0x69866b4c6839ea8c44b36bbd63e617528d703af1
0x6288a8705124658586a5414c915c6d89e3dc7e59
```

<details>
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/340ff8b2-8540-4398-8463-036b4e0c2466)

https://platform.arkhamintelligence.com/visualizer/entity/0x888c7fc7dFced7b23F20D621a4496fb1BdBa0568,0x39eD2eDC4eEcbaF67D301915d41718a2453CE81E,0xEDdA713a5875df7Af78Ba6907e3A8F3299aE58DD,0x70d912Fb0315C94693a66F1e7384C593594bF476,0x53630aa134efbfbA925938ADA988922bbab42443,0x5D9179C204655d562b8e6fB6fAA3c1693725101d,0x4C30d8EE462240f927dd94C5A214784594B0b58e,0x139b0BF3426F35aa4FA807d88e181f6C6dE5E01F,0x1865286096E66f464261f4f2aA1B5311fC0CE2f5,0x18936900603B18d12F2dBbEAb558468fDfDE5A7B,0x1B5505a22057f68136D5938156B71E6A385DF533,0x4ab4bAE5c75155716fDA8EC7704A29e38525Eb82,0x7965eB18c68F26f01DB9677bd61E656a79217Dc0,0x897CB796c5D296b4A32d8E0604B23947d9b29c8D,0x75BE24119348435d29D45f2182624ba4104D7920,0x7F41Ce43077b02906d30961F2053AC1a57E10b6a,0xb4560Bc65BA37F84f65c2F71C70d0815d356818f,0x789e4Be4e102A0A69e6D793969ae5A1Ba8173586,0xd1Df2ff3dBCbdbb0eF9fC896944fD026801829f5,0xD6b0a3A1c174ABD461DecaBa5fF0efF50d6F8071,0x69866b4C6839Ea8c44b36bBD63E617528D703AF1,0x6288a8705124658586A5414C915c6d89e3dc7e59?flow=self&positions=%7B%220x6288a8705124658586A5414C915c6d89e3dc7e59%22%3A%7B%22fx%22%3A8%2C%22fy%22%3A-60%7D%2C%220x5D9179C204655d562b8e6fB6fAA3c1693725101d%22%3A%7B%22fx%22%3A30%2C%22fy%22%3A-53%7D%2C%220x75BE24119348435d29D45f2182624ba4104D7920%22%3A%7B%22fx%22%3A43%2C%22fy%22%3A-40%7D%2C%220x4C30d8EE462240f927dd94C5A214784594B0b58e%22%3A%7B%22fx%22%3A48%2C%22fy%22%3A-26%7D%2C%220x18936900603B18d12F2dBbEAb558468fDfDE5A7B%22%3A%7B%22fx%22%3A52%2C%22fy%22%3A-12%7D%2C%220x888c7fc7dFced7b23F20D621a4496fb1BdBa0568%22%3A%7B%22fx%22%3A52%2C%22fy%22%3A2%7D%2C%220x1B5505a22057f68136D5938156B71E6A385DF533%22%3A%7B%22fx%22%3A48%2C%22fy%22%3A13%7D%2C%220x789e4Be4e102A0A69e6D793969ae5A1Ba8173586%22%3A%7B%22fx%22%3A37%2C%22fy%22%3A24%7D%2C%220xD6b0a3A1c174ABD461DecaBa5fF0efF50d6F8071%22%3A%7B%22fx%22%3A24%2C%22fy%22%3A30%7D%2C%220x139b0BF3426F35aa4FA807d88e181f6C6dE5E01F%22%3A%7B%22fx%22%3A-6%2C%22fy%22%3A-58%7D%2C%220xb4560Bc65BA37F84f65c2F71C70d0815d356818f%22%3A%7B%22fx%22%3A-20%2C%22fy%22%3A-49%7D%2C%220x7F41Ce43077b02906d30961F2053AC1a57E10b6a%22%3A%7B%22fx%22%3A-26%2C%22fy%22%3A-37%7D%2C%220x897CB796c5D296b4A32d8E0604B23947d9b29c8D%22%3A%7B%22fx%22%3A-30%2C%22fy%22%3A-24%7D%2C%220x70d912Fb0315C94693a66F1e7384C593594bF476%22%3A%7B%22fx%22%3A-31%2C%22fy%22%3A-10%7D%2C%220xd1Df2ff3dBCbdbb0eF9fC896944fD026801829f5%22%3A%7B%22fx%22%3A-26%2C%22fy%22%3A2%7D%2C%220x53630aa134efbfbA925938ADA988922bbab42443%22%3A%7B%22fx%22%3A34%2C%22fy%22%3A-20%7D%2C%220x69866b4C6839Ea8c44b36bBD63E617528D703AF1%22%3A%7B%22fx%22%3A-17%2C%22fy%22%3A15%7D%2C%220x7965eB18c68F26f01DB9677bd61E656a79217Dc0%22%3A%7B%22fx%22%3A9%2C%22fy%22%3A27%7D%2C%220xEDdA713a5875df7Af78Ba6907e3A8F3299aE58DD%22%3A%7B%22fx%22%3A8%2C%22fy%22%3A-26%7D%2C%220x4ab4bAE5c75155716fDA8EC7704A29e38525Eb82%22%3A%7B%22fx%22%3A-4%2C%22fy%22%3A23%7D%2C%220x39eD2eDC4eEcbaF67D301915d41718a2453CE81E%22%3A%7B%22fx%22%3A19%2C%22fy%22%3A9%7D%2C%220x1865286096E66f464261f4f2aA1B5311fC0CE2f5%22%3A%7B%22fx%22%3A-4%2C%22fy%22%3A-8%7D%7D&sortDir=desc&sortKey=time&usdGte=0.1


21 addresses ranked from 270k to 850k

LZ day: 8 at 234, 5 at 237, and 6 at 239.

According to Debank, they all have $1 or $2 maximum on Stargate on BNB. Additionally, they all executed identical transactions on the same day, involving similar amounts to buy STG on Slingshot and lock them on Stargate.
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/a7e9827e-c664-45fb-b3cb-a7597c06c02d)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/7dc49680-b2b2-4413-b29b-96dfb9b1df79)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/040f04fc-679e-4af0-9e3d-c5df728b2ae2)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/5ec069cd-699b-4987-8910-3661ba5e8445)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/49412d96-057b-4d78-9c76-1f748aec4d8c)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/aa742e8d-e5af-4d0e-80cd-3acf4988759b)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/f10907d1-d7ae-4695-83eb-23bf290ba6c3)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/374eb1e1-ef3f-4c8b-a1e4-64d82341f887)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/3dcd0d7b-711e-478c-b7bc-bca049ee6c48)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/64d1e96c-ae85-421e-87b4-931491927e36)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/3b9fc227-f7da-40ed-82bc-a49646ac76cb)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/740e2b70-c7cb-4d04-93ec-18bb71487e05)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/688832f0-60dd-4eea-9a9b-1e31382ac004)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/f4e6cf04-6815-4fcb-acb3-1c2bc9be1905)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/5dbfcb3e-6471-4c45-80a9-e4a0af89d8ae)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/f37f1b9c-ee31-47d1-95b8-c1350870ae27)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/ea90cbfb-fcb1-48d0-a93d-842f440b9c1b)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/5ed0ec6a-2c85-4e97-8e23-bffb5ee2657f)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/6ff3683f-2353-41bb-b64b-635e9df6410a)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/de6f80d8-a3de-48ed-9fc5-ba922e824a28)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/aced9926-0487-4908-a714-e85c8e91257c)

```
2 0x39ed2edc4eecbaf67d301915d41718a2453ce81e 2023-10-26   
3 0xedda713a5875df7af78ba6907e3a8f3299ae58dd 2023-10-26   
4 0x70d912fb0315c94693a66f1e7384c593594bf476 2023-10-26   
5 0x53630aa134efbfba925938ada988922bbab42443 2023-10-26   
6 0x5d9179c204655d562b8e6fb6faa3c1693725101d 2023-10-26   
7 0x4c30d8ee462240f927dd94c5a214784594b0b58e 2023-11-02   
8 0x139b0bf3426f35aa4fa807d88e181f6c6de5e01f 2023-10-26   
9 0x1865286096e66f464261f4f2aa1b5311fc0ce2f5 2023-10-26   
10 0x18936900603b18d12f2dbbeab558468fdfde5a7b 2023-10-26   
11 0x1b5505a22057f68136d5938156b71e6a385df533 2023-10-26   
12 0x4ab4bae5c75155716fda8ec7704a29e38525eb82 2023-10-26   
13 0x7965eb18c68f26f01db9677bd61e656a79217dc0 2023-10-26   
14 0x897cb796c5d296b4a32d8e0604b23947d9b29c8d 2023-10-26   
15 0x75be24119348435d29d45f2182624ba4104d7920 2023-10-26   
16 0x7f41ce43077b02906d30961f2053ac1a57e10b6a 2023-10-26   
17 0xb4560bc65ba37f84f65c2f71c70d0815d356818f 2023-10-26   
18 0x789e4be4e102a0a69e6d793969ae5a1ba8173586 2023-10-26   
19 0xd1df2ff3dbcbdbb0ef9fc896944fd026801829f5 2023-10-26   
20 0xd6b0a3a1c174abd461decaba5ff0eff50d6f8071 2023-10-26   
21 0x69866b4c6839ea8c44b36bbd63e617528d703af1 2023-10-26   
22 0x6288a8705124658586a5414c915c6d89e3dc7e59 2023-10-26  
```

</details>

## Cluster 28

26 first linked to CEX deposit address
0x324Ec2F26161303f59196d3439a7211E19d1bd84 (OKX)


```
0xfc40c28541ee229cfd0a9435c38779673c6bd5fe
0x9d21fc5b5cfbf6510eb7e60dacf348208882f5b6
0x7613c38eb6c1da437de23b28527a790910c1ba78
0xa98082a2ff0fdcf719c9d1b885eab67a35f714c9
0xa4068acc31fcff871966afe6290f54de681b3af0
0x69e9e57a8934bad2dc1d9647da60fc891234c586
0x26f275d27c3a66ccc54e7cdaf484f48283ae0ec0
0x86bb7c64ff1a286cc97e3bc734e59cb8b8e1cf70
0x9d04d73855e50558d1a3a150e6d562dc84cdb9b4
0x3c9f0a4e5c7c987dde1f3ef8abf4a40dc8380377
0xba357f63056c63e71959babfa4f3f89ad85de886
0x4f772ebb54226a001486d92cba2bbdcb7f9b63e5
0xb281d4da1620bdce9b1236d8b693c238af150b2a
0x95503b5a3cdf8b5929108e4cbcf661f8abfc8095
0x97d9e85bbe539f49915490f8bcadb1dc8da80c6a
0x4f6d12ea2fb49908cc81f9e5476ef1055ae29892
0x6130efe431dd939d8a6a62999663fda6ffe9cf78
0x4f9a84aea72d72886453c125f3a14e10f8f6e86b
0xb7723f91c69e09052553d4f971235b9d1cfae482
0xc8ae75132dea617de0e96c29be4f161be7f27dcc
0x6d7d0c9207bb2ea136c95ce153abe35e51caad37
0x914e0fdbb9a6b2d8f9d58b2302cec55b43e7fe13
0xff89ea6275406ae7d3ea2ae87f1db3476a5e57c8
0x5d364d28c42ea5feabab39165356e5802ff07015
```

<details>

![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/74a6876b-42cc-496e-bda6-ef0b13393d9e)
  
https://platform.arkhamintelligence.com/visualizer/entity/0x324Ec2F26161303f59196d3439a7211E19d1bd84,0xFc40C28541EE229CfD0A9435C38779673C6BD5fe,0x9D21fC5b5CfBF6510eB7e60DAcF348208882f5b6,0x7613c38eB6C1da437De23B28527a790910c1ba78,0xa98082a2ff0fDcf719c9d1B885eaB67A35F714c9,0xa4068AcC31FcFF871966afE6290F54DE681B3aF0,0x69e9E57A8934BAd2DC1D9647Da60Fc891234C586,0x26f275d27c3a66CcC54e7cDaf484F48283ae0eC0,0x86bb7c64Ff1A286CC97E3bc734e59CB8b8e1CF70,0x9d04d73855E50558D1A3a150e6D562dc84CDB9B4,0x3C9F0A4E5C7c987DdE1F3Ef8aBF4a40dc8380377,0xBA357f63056C63E71959babFa4f3f89Ad85de886,0x4F772ebb54226A001486d92Cba2bBDCb7f9B63e5,0xb281d4Da1620BdCe9B1236d8b693c238Af150b2a,0x95503b5a3Cdf8B5929108E4cBCF661F8AbFc8095,0x97D9e85BBe539f49915490F8BcadB1DC8Da80C6a,0x4f6D12EA2fB49908Cc81f9E5476ef1055aE29892,0x6130EFe431DD939D8a6A62999663fDa6FFe9CF78,0x4f9A84aEA72D72886453C125f3a14E10F8f6e86B,0xB7723F91c69E09052553d4F971235b9d1cfaE482,0xC8Ae75132dea617de0e96C29bE4F161be7f27dCC,0x6d7D0c9207bb2Ea136c95ce153abE35e51CaAd37,0x914E0FDBb9A6B2D8F9d58B2302cec55B43e7fe13,0xfF89eA6275406ae7d3EA2ae87f1db3476A5e57c8,0x5D364d28C42Ea5fEabab39165356e5802fF07015?flow=self&positions=%7B%220x95503b5a3Cdf8B5929108E4cBCF661F8AbFc8095%22%3A%7B%22fx%22%3A-13%2C%22fy%22%3A-51%7D%2C%220xBA357f63056C63E71959babFa4f3f89Ad85de886%22%3A%7B%22fx%22%3A-27%2C%22fy%22%3A-43%7D%2C%220xb281d4Da1620BdCe9B1236d8b693c238Af150b2a%22%3A%7B%22fx%22%3A3%2C%22fy%22%3A-50%7D%2C%220x3C9F0A4E5C7c987DdE1F3Ef8aBF4a40dc8380377%22%3A%7B%22fx%22%3A22%2C%22fy%22%3A-46%7D%2C%220x69e9E57A8934BAd2DC1D9647Da60Fc891234C586%22%3A%7B%22fx%22%3A31%2C%22fy%22%3A-35%7D%2C%220xC8Ae75132dea617de0e96C29bE4F161be7f27dCC%22%3A%7B%22fx%22%3A38%2C%22fy%22%3A-25%7D%2C%220x9D21fC5b5CfBF6510eB7e60DAcF348208882f5b6%22%3A%7B%22fx%22%3A47%2C%22fy%22%3A-14%7D%2C%220xFc40C28541EE229CfD0A9435C38779673C6BD5fe%22%3A%7B%22fx%22%3A52%2C%22fy%22%3A-2%7D%2C%220x4f6D12EA2fB49908Cc81f9E5476ef1055aE29892%22%3A%7B%22fx%22%3A-39%2C%22fy%22%3A-34%7D%2C%220x97D9e85BBe539f49915490F8BcadB1DC8Da80C6a%22%3A%7B%22fx%22%3A-48%2C%22fy%22%3A-20%7D%2C%220x26f275d27c3a66CcC54e7cDaf484F48283ae0eC0%22%3A%7B%22fx%22%3A-49%2C%22fy%22%3A-5%7D%2C%220xa98082a2ff0fDcf719c9d1B885eaB67A35F714c9%22%3A%7B%22fx%22%3A-45%2C%22fy%22%3A9%7D%2C%220xB7723F91c69E09052553d4F971235b9d1cfaE482%22%3A%7B%22fx%22%3A-36%2C%22fy%22%3A22%7D%2C%220x4F772ebb54226A001486d92Cba2bBDCb7f9B63e5%22%3A%7B%22fx%22%3A-24%2C%22fy%22%3A30%7D%2C%220x86bb7c64Ff1A286CC97E3bc734e59CB8b8e1CF70%22%3A%7B%22fx%22%3A-9%2C%22fy%22%3A36%7D%2C%220x914E0FDBb9A6B2D8F9d58B2302cec55B43e7fe13%22%3A%7B%22fx%22%3A4%2C%22fy%22%3A34%7D%2C%220x5D364d28C42Ea5fEabab39165356e5802fF07015%22%3A%7B%22fx%22%3A21%2C%22fy%22%3A31%7D%2C%220xa4068AcC31FcFF871966afE6290F54DE681B3aF0%22%3A%7B%22fx%22%3A24%2C%22fy%22%3A-9%7D%2C%220x324Ec2F26161303f59196d3439a7211E19d1bd84%22%3A%7B%22fx%22%3A48%2C%22fy%22%3A13%7D%2C%220x6d7D0c9207bb2Ea136c95ce153abE35e51CaAd37%22%3A%7B%22fx%22%3A36%2C%22fy%22%3A22%7D%2C%220x6130EFe431DD939D8a6A62999663fDa6FFe9CF78%22%3A%7B%22fx%22%3A-3%2C%22fy%22%3A-32%7D%2C%220x7613c38eB6C1da437De23B28527a790910c1ba78%22%3A%7B%22fx%22%3A-29%2C%22fy%22%3A-14%7D%2C%220x9d04d73855E50558D1A3a150e6D562dc84CDB9B4%22%3A%7B%22fx%22%3A-1%2C%22fy%22%3A-15%7D%2C%220xfF89eA6275406ae7d3EA2ae87f1db3476A5e57c8%22%3A%7B%22fx%22%3A-3%2C%22fy%22%3A20%7D%2C%220x4f9A84aEA72D72886453C125f3a14E10F8f6e86B%22%3A%7B%22fx%22%3A3%2C%22fy%22%3A5%7D%7D&sortDir=desc&sortKey=time&usdGte=0.1


LZ Day: 2 at 252, 5 at 253, 3 at 254, 2 at 255, 2 at 274, 2 at 292, 3 at 294, 2 at 307, 2 at 309, 2 at 326, 2 at 328, and 3 at 333 among others.

Analyzing the holding of STG on BNB via Debank:
0xfc40c28541ee229cfd0a9435c38779673c6bd5fe
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/0a2b3a66-7d6b-4f2d-8dcf-f3641f42992c)
Cette adresse est dans le cluster (0xa98082a2ff0fdcf719c9d1b885eab67a35f714c9)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/f0393555-a91a-4ef9-9312-6b7498c4ff17)
déja dans le cluster (0x9d21fc5b5cfbf6510eb7e60dacf348208882f5b6)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/e89493c1-bc8f-4549-a459-dbf5fca6785a)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/07790673-c770-4e65-878d-cbb741518418)
Cette adresse est dans le cluster (0x4f6d12ea2fb49908cc81f9e5476ef1055ae29892)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/0fd46841-fb78-493a-9c8e-089c4b3c0c67)
Cette adresse est dans le cluster (0x6130efe431dd939d8a6a62999663fda6ffe9cf78)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/6701d6ae-1817-42cc-b1fe-912f138030d6)
Cette adresse est dans le cluster (0x8b455ae33f9d76346eefa2a51dca4085ff9850f5)
0x9d21fc5b5cfbf6510eb7e60dacf348208882f5b
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/2ea94f66-d0cc-46d6-a881-753fb9992eb5)
Cette adresse est dans le cluster
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/b9be9f58-da40-437d-9367-d4a85aa78dd2)
Cette adresse est dans le cluster (0x9d04d73855e50558d1a3a150e6d562dc84cdb9b4)
0x7613c38eb6c1da437de23b28527a790910c1ba78
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/61c1bdb5-6c8d-43c4-9f50-c369fa3947be)
0xb7723f91c69e09052553d4f971235b9d1cfae482 dasn le cluster
[image](https://github.com/altaccounteth/report_layerzero/assets/170960041/3d22fd36-1f9a-4e9b-8142-b59c1122e425)
0x86bb7c64ff1a286cc97e3bc734e59cb8b8e1cf70 dans le cluster
0xa98082a2ff0fdcf719c9d1b885eab67a35f714c9
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/84017064-5cd5-441a-83f3-cdf5be6a6af4)
0x26f275d27c3a66ccc54e7cdaf484f48283ae0ec0 est dans le cluster
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/1308e2ba-8fee-4878-8fcd-b29aaf178d14)
0x23b109ebfa0938a044f5bd00ae214d21009023e8 est dans le cluster
0xa4068acc31fcff871966afe6290f54de681b3af0
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/072fb112-be75-4c98-a9c8-963db50352a6)
0x914e0fdbb9a6b2d8f9d58b2302cec55b43e7fe13 est dans le cluster
On a une qui n'échangent avec personne (0x4403901829bd5dbcc0dc0b8ef2aa8ef173efaa27) des STG mais elle a fait les mêmes tx le même jour qu’une autre:
(0xa4068acc31fcff871966afe6290f54de681b3af0, 0x4403901829bd5dbcc0dc0b8ef2aa8ef173efaa27)
![image](https://github.com/altaccounteth/report_layerzero/assets/170960041/cfa0d081-c230-405b-983a-10440b392d80)
0x69e9e57a8934bad2dc1d9647da60fc891234c586
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/027aa402-60bf-4cd4-a02e-f7963889b652)
0x18d850d35fcb63cdf95e317a747d515a4429f37b qui est dans le cluster
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/f3bbb0ee-4e90-40c4-9d61-6b50c050dd77)
0x3c9f0a4e5c7c987dde1f3ef8abf4a40dc8380377 qui est dans le cluster
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/2b69be55-f63a-4b66-b1c0-0e47280dd798)
0xb281d4da1620bdce9b1236d8b693c238af150b2a qui est dans le cluster
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/50dcda1c-cc51-4615-9941-6946fd128535)
0xba357f63056c63e71959babfa4f3f89ad85de886 qui est dans le cluster

0xf1f49950f21646bd0d0eb74393aeacc3eea84104
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/adb88242-4e69-4c24-99e8-c6cdebaafdd3)
La première on l’avait déja parcouru et la deuxième 0xff89ea6275406ae7d3ea2ae87f1db3476a5e57c8 est dans le cluster.
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/aeec204e-2a67-49e1-a812-1f0df659e4d6)
0x733ef3b73175bf2bb87c8402ec87c87945f201f7 dans le cluster
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/aa8a94e0-4153-4e48-9c84-371948d4fcf6)
0xc6e793c6457cdd70555e6bc9828ffb561ca269cc dans le cluster

0x4f772ebb54226a001486d92cba2bbdcb7f9b63e5
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/d0f37521-51f3-4c03-8015-e1aa6eb1f973)
0x9d04d73855e50558d1a3a150e6d562dc84cdb9b4 on l’avait déja parcourue, ainsi par transitivité, elle est relié à tous celles déja identifier.
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/dcbcd0fa-dece-4345-a929-b36529c7f6cb)
0x4f9a84aea72d72886453c125f3a14e10f8f6e86b dans le cluster.

0x95503b5a3cdf8b5929108e4cbcf661f8abfc8095
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/786cd2b8-41dc-4b3d-91dc-51ec1850b908)
0xba357f63056c63e71959babfa4f3f89ad85de886 on l’avait déja parcourue, ainsi par transitivité, elle est relié à tous celles déja identifier.

0xe2137651aa80a4bb37cdf381ff113114a3697f7e
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/94f2582c-3e92-46b7-a246-435fb8eac4dd)
0xc6e793c6457cdd70555e6bc9828ffb561ca269cc on l’avait déja parcourue, ainsi par transitivité, elle est relié à tous celles déja identifier.

0x524188735e048fc292b021434c75550b244de471
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/d67b171e-421c-4613-ad20-ec503064b2d3)
0xb281d4da1620bdce9b1236d8b693c238af150b2a on l’avait déja parcourue, ainsi par transitivité, elle est relié à tous celles déja identifier.

0x563fbba79fc6b7a710e3545d0c251dc32ba1fccb
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/1d0add85-ab9f-474e-8420-8a4c55988220)
Ressemble à celels vu toute à l’heure à un jour près a voir ce qu’on trouve avec LZ Scan

0x97d9e85bbe539f49915490f8bcadb1dc8da80c6a
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/f0e44e41-777f-4fa0-ac58-68ef97eb8391)
0x4f6d12ea2fb49908cc81f9e5476ef1055ae29892 on l’avait déja parcourue, ainsi par transitivité, elle est relié à tous celles déja identifier.
0x26f275d27c3a66ccc54e7cdaf484f48283ae0ec0 same.

0x6d7d0c9207bb2ea136c95ce153abe35e51caad37
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/a9e51b3f-48d1-4b6a-b3cb-3eee70f528ca)
Déja identifié

0x3d03ce276e9da9bc027c4b1a3c272a02e3c5cfa6
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/e90574c8-15d0-40e1-9b68-cbd1605d021d)

![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/b783863a-ff7c-4abf-a2dd-238c3b12333c)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/af458355-4f61-4725-973e-7b3c490becad)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/dd84f3af-943a-47cd-9b00-d65fae8d178a)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/ace001e2-fb06-4d36-9074-47c25ac58a08)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/757ef947-13d4-4c79-b4d7-216ae9875fd7)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/654c1590-7e51-4408-beee-6294e46ced01)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/0475b8ff-7713-4036-9756-f6af535a9a78)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/91bc7574-ad75-4522-a7c7-2546615b92ee)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/702cdb73-b7f9-41db-901d-8e3f4adacdea)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/68431268-a9ca-4fe9-8ef7-51e95ed324c1)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/3deb2cfa-1e6e-4d75-b45b-663dad9a32f2)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/46ac9d85-0e5b-41cd-af8c-61005b028fa0)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/1c0087b6-336b-4b03-8dfc-b62c1e8fc77f)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/193dc3c8-2ed4-4dc6-beb1-39bd07fe8fe2)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/e6d20dde-93f6-446f-b28f-122eeba5e46f)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/8530e896-07c0-4542-8bdb-3b0f4e7ea668)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/849cb6f0-bee2-40d2-aadd-bbd89717e840)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/7d36f745-650a-4cb9-a386-16ded46be2be)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/a4f4d2b9-c6b0-4e59-bacb-3f3820188f03)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/cf366be4-a419-4dbc-9447-3ad20bcc937e)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/59705ba2-54ca-49bd-a48e-5632960e4f8c)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/c16f2107-6b78-46f7-8c77-cee2e8eb41aa)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/9dce118c-ade1-432b-9413-15307c64ecc4)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/7be2c017-fc8a-4fac-bb0f-8a40b0516a91)


```
zksync
1 0xfc40c28541ee229cfd0a9435c38779673c6bd5fe 2024-02-22 2023-07-21 
2 0x9d21fc5b5cfbf6510eb7e60dacf348208882f5b6 2024-02-22 2023-07-21 
3 0x7613c38eb6c1da437de23b28527a790910c1ba78 2024-02-24 2023-07-23 
4 0xa98082a2ff0fdcf719c9d1b885eab67a35f714c9 2024-02-24 2023-08-07 
5 0xa4068acc31fcff871966afe6290f54de681b3af0 2024-02-27 2023-09-30 
6 0x69e9e57a8934bad2dc1d9647da60fc891234c586 2024-02-25 2023-08-17 
7 0x26f275d27c3a66ccc54e7cdaf484f48283ae0ec0 2024-02-25 2023-08-07 
8 0x86bb7c64ff1a286cc97e3bc734e59cb8b8e1cf70 2024-02-24 2023-07-22 
9 0x9d04d73855e50558d1a3a150e6d562dc84cdb9b4 2024-02-24 2023-07-22 
10 0x3c9f0a4e5c7c987dde1f3ef8abf4a40dc8380377 2024-02-25 2023-08-19 
11 0xba357f63056c63e71959babfa4f3f89ad85de886 2024-02-25 2023-08-19 
12 0x4f772ebb54226a001486d92cba2bbdcb7f9b63e5 2024-02-24 2023-07-22 
13 0xb281d4da1620bdce9b1236d8b693c238af150b2a 2024-02-25 2023-08-19 
14 0x95503b5a3cdf8b5929108e4cbcf661f8abfc8095 2024-02-25 2023-08-19 
15 0x97d9e85bbe539f49915490f8bcadb1dc8da80c6a 2024-02-25 2023-08-07 
16 0x4f6d12ea2fb49908cc81f9e5476ef1055ae29892 2024-02-25 2023-08-07 
17 0x6130efe431dd939d8a6a62999663fda6ffe9cf78 2024-02-25 2023-07-29 
18 0x4f9a84aea72d72886453c125f3a14e10f8f6e86b 2024-02-23 2023-07-22 
19 0xb7723f91c69e09052553d4f971235b9d1cfae482 2024-02-24 2023-07-23 
20 0xc8ae75132dea617de0e96c29be4f161be7f27dcc 2024-02-23 2023-07-22 
21 0x6d7d0c9207bb2ea136c95ce153abe35e51caad37 2024-02-23 2023-07-22 
22 0x914e0fdbb9a6b2d8f9d58b2302cec55b43e7fe13 2024-02-29 2023-09-30 
23 0xff89ea6275406ae7d3ea2ae87f1db3476a5e57c8 2024-02-28 2023-09-30 
24 0x5d364d28c42ea5feabab39165356e5802ff07015 2024-02-27 2023-09-30
```



</details>

## Cluster 29
Same CEX deposit (Binance)
0x5BAF2a6ac47AE3270e78263177ABdeb70892DaE2

```
0xe2f7102b63119ee436a80a79a554e5d16954a125
0x84993422cb9f8ed9cd605c06499d3806bbe606d7
0xcbacba5318efbfcd9b86564d4eca555c1ba0d6de
0x3fdd65ba78d1d94cc8a567404bf28be1dc6029ff
0x9b6f406875ba9ebd798d156b063909ecbee4ff85
0x6e0f64bfa3d879abafcbf71dc5252ea40d08ceda
0x67689bf78640cdfe82b44935ceaf8aa462d60f69
0xeb52c531a253e4c849fd39b515405f4d6370964e
0x36aa63b68dc4bc4d02d475a9481eee62049eef57
0xb0918acfaeba07c0fa55fc972c56e41a4ade0c70
0x8768e65712b747fabf39e00e3c07a9d49dfcf677
0x28134f152c2117666d7568889d3b9c54316cf032
0xeed6a9df7fae961b756cd4576305698f45ca8673
0xe5195d2faed140e5f24ba67706dc765f353d6d3b
0xcd34cc3569ec6a6ba0e5fecf8841b3d02551a465
0xb0a2e7a1a6c27b8b6c3b5ea3643c3230c59bd0a9
0x9d47915995cc40494cc3eebf251758171cfd334a
0x3584f16cf0182ff810b6b1066361d44f5f38a5a9
0x341d386cafc5469e65244640f7ecfb3d86084223
0x591629548d30dbc9c15480a5692e158545efcfce
0x29f6dd6473dfeafc508f06b487c915017b9e04da
```

<details>

![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/41b747c6-4621-4786-a700-fbdb3e3e3ccd)

https://platform.arkhamintelligence.com/visualizer/entity/0x5BAF2a6ac47AE3270e78263177ABdeb70892DaE2,0xE2F7102b63119Ee436A80a79A554E5D16954A125,0x84993422Cb9f8ed9cD605C06499D3806BbE606d7,0xCbAcBA5318eFbfcd9B86564d4eCA555c1Ba0D6dE,0x3FdD65Ba78D1D94cc8a567404Bf28bE1DC6029fF,0x9b6f406875Ba9eBD798d156B063909ECBee4Ff85,0x6e0F64bfA3D879ABAFCbf71Dc5252EA40d08CEDa,0x67689bF78640CDfe82B44935ceAF8Aa462D60F69,0xEb52C531A253E4C849fd39B515405F4D6370964E,0x36AA63b68Dc4bC4d02d475A9481EEE62049eEf57,0xb0918ACfAeBA07C0FA55fc972c56E41a4ADE0c70,0x8768e65712B747FAbF39e00E3c07A9D49dfCF677,0x28134f152C2117666D7568889d3B9C54316cf032,0xEeD6a9DF7Fae961B756CD4576305698F45cA8673,0xe5195D2FaeD140E5f24bA67706dC765F353d6D3b,0xcd34cc3569EC6A6BA0e5feCF8841b3d02551A465,0xB0a2E7a1A6c27b8b6c3b5Ea3643C3230C59BD0a9,0x9D47915995cc40494CC3EEbf251758171cfD334A,0x3584f16cf0182FF810B6B1066361d44f5f38A5a9,0x341d386CaFc5469e65244640F7ECfB3d86084223,0x591629548d30dbc9c15480a5692e158545EFcFCe,0x29F6dD6473DfEafc508F06b487c915017B9E04DA?flow=self&positions=%7B%220x3FdD65Ba78D1D94cc8a567404Bf28bE1DC6029fF%22%3A%7B%22fx%22%3A51%2C%22fy%22%3A-14%7D%2C%220x36AA63b68Dc4bC4d02d475A9481EEE62049eEf57%22%3A%7B%22fx%22%3A56%2C%22fy%22%3A0%7D%2C%220xEeD6a9DF7Fae961B756CD4576305698F45cA8673%22%3A%7B%22fx%22%3A57%2C%22fy%22%3A13%7D%2C%220x6e0F64bfA3D879ABAFCbf71Dc5252EA40d08CEDa%22%3A%7B%22fx%22%3A50%2C%22fy%22%3A24%7D%2C%220x341d386CaFc5469e65244640F7ECfB3d86084223%22%3A%7B%22fx%22%3A38%2C%22fy%22%3A30%7D%2C%220x9D47915995cc40494CC3EEbf251758171cfD334A%22%3A%7B%22fx%22%3A25%2C%22fy%22%3A35%7D%2C%220x29F6dD6473DfEafc508F06b487c915017B9E04DA%22%3A%7B%22fx%22%3A11%2C%22fy%22%3A38%7D%2C%220x9b6f406875Ba9eBD798d156B063909ECBee4Ff85%22%3A%7B%22fx%22%3A38%2C%22fy%22%3A-26%7D%2C%220xb0918ACfAeBA07C0FA55fc972c56E41a4ADE0c70%22%3A%7B%22fx%22%3A23%2C%22fy%22%3A-35%7D%2C%220xEb52C531A253E4C849fd39B515405F4D6370964E%22%3A%7B%22fx%22%3A10%2C%22fy%22%3A-38%7D%2C%220x28134f152C2117666D7568889d3B9C54316cf032%22%3A%7B%22fx%22%3A-3%2C%22fy%22%3A-36%7D%2C%220xB0a2E7a1A6c27b8b6c3b5Ea3643C3230C59BD0a9%22%3A%7B%22fx%22%3A-15%2C%22fy%22%3A-31%7D%2C%220xCbAcBA5318eFbfcd9B86564d4eCA555c1Ba0D6dE%22%3A%7B%22fx%22%3A-24%2C%22fy%22%3A-22%7D%2C%220x84993422Cb9f8ed9cD605C06499D3806BbE606d7%22%3A%7B%22fx%22%3A-2%2C%22fy%22%3A38%7D%2C%220x3584f16cf0182FF810B6B1066361d44f5f38A5a9%22%3A%7B%22fx%22%3A-15%2C%22fy%22%3A34%7D%2C%220xE2F7102b63119Ee436A80a79A554E5D16954A125%22%3A%7B%22fx%22%3A-26%2C%22fy%22%3A26%7D%2C%220xe5195D2FaeD140E5f24bA67706dC765F353d6D3b%22%3A%7B%22fx%22%3A-35%2C%22fy%22%3A17%7D%2C%220xcd34cc3569EC6A6BA0e5feCF8841b3d02551A465%22%3A%7B%22fx%22%3A-42%2C%22fy%22%3A6%7D%2C%220x8768e65712B747FAbF39e00E3c07A9D49dfCF677%22%3A%7B%22fx%22%3A-41%2C%22fy%22%3A-6%7D%2C%220x67689bF78640CDfe82B44935ceAF8Aa462D60F69%22%3A%7B%22fx%22%3A-37%2C%22fy%22%3A-18%7D%2C%220x591629548d30dbc9c15480a5692e158545EFcFCe%22%3A%7B%22fx%22%3A26%2C%22fy%22%3A20%7D%7D&sortDir=desc&sortKey=time&usdGte=0.1

21 wallets ranging from 161k to 2M
LZ day: 6 at 460, 5 at 463, 5 at 464, 2 at 517 among others

Digging into LayerZero scan:

Stargate transactions noted as STG in late April:
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/ff08bb88-1a7d-46c9-a88f-6a533a1cfa09)

![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/e1607995-7b1c-42fb-8249-7a1f4160c4dc)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/27130209-4458-4bb1-987c-9791c2955903)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/12fecb02-c7d5-41ae-ade4-da0e737c46d3)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/3bdddb78-eb67-4d61-97eb-9a997d0aca51)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/02bddacc-81a2-45c7-be3d-1fa73b52c568)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/691d969b-2eef-497e-b655-57d8da219ed9)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/d26c0994-8b86-4ee2-bdcc-c766a51de36b)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/49ea501f-4d51-4255-938f-9b78d421f7ff)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/3168fa98-996c-4e21-997d-3d9b952c620f)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/ab1c81fc-3fc0-4708-a6c4-ce77b3245cd4)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/11dd8e4b-a3bb-4e1e-ab5e-0adc13666ecf)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/de75840e-04af-4bc1-ae91-2347b898ae62)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/9ff8d416-96d4-42b8-9c74-f7f59d861246)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/d0a192dc-c80e-4cca-ba5d-38f089ef3dc0)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/f787d982-9478-4cdf-ae93-7ffba1a0399b)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/01516f8e-9973-4dd1-904d-c251f053eb44)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/d4f27ced-106c-4992-a78f-554457c8426a)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/9dd893d8-0539-4b8f-8a52-a258fbb75d62)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/398baa49-586f-485f-a284-979c4649e1c9)
![image](https://github.com/altaccounteth/report_layerzero/assets/151371773/aaeae2d4-50a8-478c-a504-eaa6f8ee50fd)

```
bsc stg lock

1 0xe2f7102b63119ee436a80a79a554e5d16954a125 2024-02-27   2023-12-25   2023-02-24   
2 0x84993422cb9f8ed9cd605c06499d3806bbe606d7 2023-12-25   2023-02-24   
3 0xcbacba5318efbfcd9b86564d4eca555c1ba0d6de 2023-12-30   2023-02-23   
4 0x3fdd65ba78d1d94cc8a567404bf28be1dc6029ff 2024-02-29   2023-12-25   2023-02-22   
5 0x9b6f406875ba9ebd798d156b063909ecbee4ff85 2024-02-29   2023-12-25   2023-02-22   
6 0x6e0f64bfa3d879abafcbf71dc5252ea40d08ceda 2024-02-29   2023-12-25   2023-02-22   
7 0x67689bf78640cdfe82b44935ceaf8aa462d60f69 2024-02-29   2023-12-25   2023-02-19   
8 0xeb52c531a253e4c849fd39b515405f4d6370964e 2024-01-19   2023-02-19   
9 0x36aa63b68dc4bc4d02d475a9481eee62049eef57 2024-01-19   2023-02-19   
10 0xb0918acfaeba07c0fa55fc972c56e41a4ade0c70 2024-02-29   2023-12-25   2023-02-19   
11 0x8768e65712b747fabf39e00e3c07a9d49dfcf677 2023-12-25   2023-02-19   
12 0x28134f152c2117666d7568889d3b9c54316cf032 2024-02-29   2023-12-25   2023-02-18   
13 0xeed6a9df7fae961b756cd4576305698f45ca8673 2024-02-28   2023-12-25   2023-02-22   
14 0xe5195d2faed140e5f24ba67706dc765f353d6d3b 2023-12-27   2023-02-18   
19 0xcd34cc3569ec6a6ba0e5fecf8841b3d02551a465 2024-02-29   2023-12-27   2023-02-15   
20 0xb0a2e7a1a6c27b8b6c3b5ea3643c3230c59bd0a9 2024-02-29   2023-12-27   2023-02-17   
21 0x9d47915995cc40494cc3eebf251758171cfd334a 2024-02-29   2023-12-27   2023-02-18   
22 0x3584f16cf0182ff810b6b1066361d44f5f38a5a9 2024-02-29   2023-12-27   2023-02-17   
23 0x341d386cafc5469e65244640f7ecfb3d86084223 2024-02-28   2023-12-25   2023-02-22   
24 0x591629548d30dbc9c15480a5692e158545efcfce 2024-02-28   2023-12-25   2023-02-22   
25 0x29f6dd6473dfeafc508f06b487c915017b9e04da 2024-02-28   2023-12-25   2023-02-22   
```

```
zksync
1 0xe2f7102b63119ee436a80a79a554e5d16954a125 2023-05-17 
2 0x84993422cb9f8ed9cd605c06499d3806bbe606d7 2023-05-17 
3 0xcbacba5318efbfcd9b86564d4eca555c1ba0d6de 2023-05-17 
4 0x3fdd65ba78d1d94cc8a567404bf28be1dc6029ff 2023-05-17 
5 0x9b6f406875ba9ebd798d156b063909ecbee4ff85 2023-05-17 
6 0x6e0f64bfa3d879abafcbf71dc5252ea40d08ceda 2023-05-17 
7 0x67689bf78640cdfe82b44935ceaf8aa462d60f69 2023-05-17 
8 0xeb52c531a253e4c849fd39b515405f4d6370964e 2023-05-17 
9 0x36aa63b68dc4bc4d02d475a9481eee62049eef57 2023-05-17 
10 0xb0918acfaeba07c0fa55fc972c56e41a4ade0c70 2023-05-17 2023-05-17 
11 0x8768e65712b747fabf39e00e3c07a9d49dfcf677 2023-05-21 2023-05-21 
12 0x28134f152c2117666d7568889d3b9c54316cf032 2023-05-21 
13 0xeed6a9df7fae961b756cd4576305698f45ca8673 2023-05-17 
14 0xe5195d2faed140e5f24ba67706dc765f353d6d3b 2023-05-21 
16 0x4d38b5d222b644b58f94c4c68fba416690b5e253 2023-05-20 2023-04-08 
17 0xb54a146d12d87fee3dedc3b2ff1105d6aca13794 2023-05-20 2023-04-08 
18 0xd4cf8c1bdd61148f676e10de22b36b5e108d75c2 2023-05-20 2023-04-08 
19 0xcd34cc3569ec6a6ba0e5fecf8841b3d02551a465 2023-05-21 
20 0xb0a2e7a1a6c27b8b6c3b5ea3643c3230c59bd0a9 2023-05-21 
21 0x9d47915995cc40494cc3eebf251758171cfd334a 2023-05-21 
22 0x3584f16cf0182ff810b6b1066361d44f5f38a5a9 2023-05-21 
23 0x341d386cafc5469e65244640f7ecfb3d86084223 2023-05-17 
24 0x591629548d30dbc9c15480a5692e158545efcfce 2023-05-17 
25 0x29f6dd6473dfeafc508f06b487c915017b9e04da 2023-05-17 
```

```
base
1 0xe2f7102b63119ee436a80a79a554e5d16954a125 2023-09-22 
2 0x84993422cb9f8ed9cd605c06499d3806bbe606d7 2023-09-22 
3 0xcbacba5318efbfcd9b86564d4eca555c1ba0d6de 2023-09-22 
4 0x3fdd65ba78d1d94cc8a567404bf28be1dc6029ff 2023-09-24 
5 0x9b6f406875ba9ebd798d156b063909ecbee4ff85 2023-09-24 
6 0x6e0f64bfa3d879abafcbf71dc5252ea40d08ceda 2023-09-24 
7 0x67689bf78640cdfe82b44935ceaf8aa462d60f69 2023-09-24 
8 0xeb52c531a253e4c849fd39b515405f4d6370964e 2023-09-25 
9 0x36aa63b68dc4bc4d02d475a9481eee62049eef57 2023-09-25 
10 0xb0918acfaeba07c0fa55fc972c56e41a4ade0c70 2023-09-25 
11 0x8768e65712b747fabf39e00e3c07a9d49dfcf677 2023-09-25 
12 0x28134f152c2117666d7568889d3b9c54316cf032 2023-09-25 
13 0xeed6a9df7fae961b756cd4576305698f45ca8673 2023-09-23 
14 0xe5195d2faed140e5f24ba67706dc765f353d6d3b 2023-09-29 
16 0x4d38b5d222b644b58f94c4c68fba416690b5e253 2023-09-14 
17 0xb54a146d12d87fee3dedc3b2ff1105d6aca13794 2023-09-15 
18 0xd4cf8c1bdd61148f676e10de22b36b5e108d75c2 2023-09-15 
19 0xcd34cc3569ec6a6ba0e5fecf8841b3d02551a465 2023-09-30 
20 0xb0a2e7a1a6c27b8b6c3b5ea3643c3230c59bd0a9 2023-09-30 
21 0x9d47915995cc40494cc3eebf251758171cfd334a 2023-09-29 
22 0x3584f16cf0182ff810b6b1066361d44f5f38a5a9 2023-09-29 
23 0x341d386cafc5469e65244640f7ecfb3d86084223 2023-09-23 
24 0x591629548d30dbc9c15480a5692e158545efcfce 2023-09-23 
25 0x29f6dd6473dfeafc508f06b487c915017b9e04da 2023-09-23 
```


</details>


## Cluster 30

First 7 address linked to OKX cex deposit:
0x33eA3165630a600e5d9BA8b52A7f203D12dc6a8E

**TLDR**
Clustered sybil farming script 
ZKSYNC bridge scripted
LINEA bridge scripted


```
0xf1d968251fc105da8c42945beaa0af7486340af1
0xe94d009dbfde68b247f7301eeea7f61be39f6e3b
0x11f0f6b2bb2032f349940d7f87ad1b3ee13cffee
0x2fe11917ec11a966abd938edc1729daf6c15c470
0x507451c67e5d9faba3734b3a93cec36bcfcbac70
0x51b3335c908e97d597aec4d813b0ac7b3ac26b9f
0xc09359201ca79775682848b79feadb9789f66a93
0x6338db79f1e159abce037dcc74d55d29cbf69232
0x0ed9dbb8ad4b1512797cf65e5e7be293b7d8117d
0xae2d429375b86d121ded40f415baafb763c8efdb
0x460b8718b5b80d4302b2bc3bbc9a4e23ff5e35c8
0x2f4cbfb4c0f406d8eac4f90322cab0d79272f048
0x7ac694007f853cfc1b549b150e8c2245d086b889
0xb8b86cc205329906830ddd44bada1e60148ece51
0xa060a88a79b525c8a21ea60970f647b01a53fb76
0x67f50b32c3d2bdca444746599fcb56eb7c872e03
0xc2b99edd6cfa9139d331e0fa066350ef91ed72ed
0xc4842be80353c20ba4169361ddb8205f726764ce
0x8fcfa0906419cfefb92f6cba0c3ac5ac8d6f3731
0xb08faa26f9c599af46a38a9b999563923469f2b6
0x2b507470474e10a4568d638817be95c43b39c8ee
0x0d5f63361e3feb7a6cab2ea3b5e742f75a8804d1
0xde8afa2c7d06506e7f49860ef380043fdb7f66e6
0x983555da9b89e5edabd1e294ae665117814fe641
0x857eee4cd166f6fee4291f16498fea5175153a0d
0xf73ac391b59c65a46293c1ef23362f19a5bd94b3
0x29c5666e84fbb060e50c2701299d088d600ff786
0xdfaf90b8ae0585c2f9412149d2c263993afd880f
0xef5c9297bdaa6d3c0da26e62feaeaa6e52ea2548
0xe093d7fb0149cd75d0c255e402a41e6aa839c064
0xa05144e0ffe8139881252cec0965ce6323a3d16a
0xa9c4d3cc0e7e1f5c4a946093581ac271b4f90fe6
0x8ee366f9ba93e8f8feb629c63baf572d26a32d65
0xa7d7d210b4d5a4aaefed82c571ad8814d7a5465c
0xfb7640108338f8a9113f49bc40a7c7c669620858
0x3fdcf3823b2ab78a0284f821caab936715c06d6b
0x06d4b669e8ced33642a3d898eae2c14d6443c45b
0xf9189759bed2df7a615b8999d8897871b10cb17f
0xce3d843257126cdb9c6da94c182e9541386eb978
0x580cee565fd5c133276a37cb6aaf184de29f455b
0x3d2e0e704f9853d491bc3bd8e8454aaca0109921
0x6966575866dd29f6db2caadbc645e15d8e868403
0x701482d029322e986cf778c282d1839c9f70fc8a
0x4cf8ded542a12f07671dd61980a9585f8d6bd74d
0xd96c4273179f3761ca2aa1bae283ca3b4201d879
0x2f925597b242f283cbada91667831555a76f635b
0x1f1c599472d1b0431a89df59740d74f0f87ee4f6
0xd888fbbbb591a07a7015ace5509aca2483733c76
0x596c0c491f981565d47a0ad8a611f792ffda8aab
0x5bcf034913b5a9bb141949f22e6bdb5f4572b993
0x7d4ec5d458e5e180561b19a4dbf0cd17558efaed
0x05128e9af115ba970cd5dd34fe3c1fa8df517f61
0x68dc2377ae20652d392611ca815633cc87842729
0x90ebb93dbc3a26f7793fc60af766afce63622d62
0xae1bc91f91496fbc1cf0f04a958953cd5aa51241
0x9af4f5151957deecceb035c9ca2aeb4ed8a0ec0e
0x94eb520127de2a323b4d89f46ca85c1ca6f3ebb4
0xcbacbb3dac498e1310b2732cf7728d657d622ac8
0xacae7c1f36428a37bb002d1418ae7449b5297ed4
0x636a6b9cb77040a9fc263a11ff911402a267c5e7
0x7f91cf010175f8416745a8c1fffe6a86d7c87869
0x35aa41a273a78bf08675549db514890d83e36b81
0x2b47e0ca4f24e40d029464fa7c25e7d800eef55c
0x39972ec19c65ef3995a766fd6c742c10073b7705
0x1af3469ee64be477283fd7bf46a63afac07bf88d
0x4846002d1803b522f211c57553e1bd69fa6b31cd
0x1bfece0f8c8718ed9edbf2938d757c0a2d039433
0xf3d3cdcb12718fc8860a3b58e577630521317a1a
0xc1429057be5d4db24c8dc51eb46a738d55617b56
0x6c9594226ad2accf79ac087c36bdd63d21640fac
0xfc19d702478a3e1df8f013700d25ae3ce9a51f5b
0x7082486b93e80996e59edcccd7f8601f7a16a535
0xe456ec754b04d83acc99ef6c39c13076f3c7a6f7
0x1d6f9dd6fe36a8c976bfa53d7e27eae71a03a63f
0x43b9fd8864102db4b2aa16562a522b31cf263ff6
0x284a3e94f575386708af4ee62862735f28c1be19
0x0f5c0f6e2c42d65abf7fb38cfc171ff6207b30f9
0xf78f351b04c1bf2857feb0d0f623de04efc7076a
0xf3d1c44af06cf95a20f66ef1537b7f5cd227e6e5
0xbbc4b8a14b76f4f9cbab5b1d2049acdf11aa3571
0xd408696815cb9b4974e016430812fb444a7cbfc1
0x8c29cdadfc797c775fd9ccb3cbe8856cc3b29aaf
0xa3ddae122e6287464207cc0afb68c605df9ffe9e
0xcba70cf05d532cce6efa87e21278b271c465cb4a
0x7297eca78a3f2bbdbf98ce7ef51189a857342bd9
0x84e6b0a97b839d454f55d1428d1e88285feb7e8d
0x9298db55504f95dcec4b60349a909e6cab006f7a
0xdbfdd24f859439e07235b45d529bbf789af2abe4
0x5a352432131a5ae6b96ea333af12ee8ace539efb
0x45765be0a3a4eebc53643c3e9250fa7184af40bb
0x735cd4ef75dcbb99b0659c32f5c8083eeee4a77b
0x7e7250be6a32ed140e1361e939c1025fe66623e2
0x488dc7f7064a9ebb9df1de923da729464a18f416
0x41f8e3ba433cbe955ad07397167f164aae2db00d
0xab768df3aac7c76b07b8c37d6e94f4385c11aa50
0x7384d84ae8023742f956d1152b9c2906fcf2061b
0x7b9c4b6c80dc278c8b6a7ddb957d9c07a52f5bda
0x48269d4b02070d2ec55597d587b2ab2c71bf2f23
0x51266e8454f4c34ac5fd7efa657de4f67fc198d7
0x5ce2498c8004dd1c7c4f3387893cc22d15a923c7
0x2b748d41060de40ee8f1053a89ff4f4bf6bb40c4
0x5f17612758d0a0f76646797a019bd8e1babb67c5
0x3d463e1a2533a8cd24682c8070da980c6c09f4e1
0x6e96ca94449204a9f3098299a63086c2cb050c51
0x22ffe947d4e88de7d56706b243e5206987868220
0x9c1805b485255aa50a988e607ebfa0245a3f8d32
0x28274f670827dde8ed103854e753b3219f64eb93
0x0c97b99bece0dae7e07848160b0ced5a42dbda14
0xf9e05010df1b9ea59ddac4c5e17b7a7b9b65201f
0x5c3b787e80aa3a358bdc848e193cd9a744f397bb
0xb033c98e75b5fefb916965e29b4c2cf3bb78ed45
0x6e270fc07f469651423166c4c3697edce4f232cf
0x6bdaafa7b66f81fbe952ff5abceec8c3132cfeb6
0xdd5565917e56edaf9fd7b242b9242367051163d7
0xfcf21167428857a2d3ec34a2365148c12d774fe1
0x427b7b51c549e391714b7958f437bb51865ebcb9
0xc9a9c8d9c12b775bcd79f172c9827cd77e1fd2d4
0x3aa0ba56a9f5e9cfa286d0de5955bb647877e80b
0x2d405e95db99c70986e826208a86fc1b7ac9cc44
0xed85dbc2c59a1cfa5af6e3ad3d75ddb03f0a2b09
0x88c8af64e4198af892d0634415e48158585ca667
0xebb8e715c4c4d338a3c08872c252db06ff6a59c5
```


<details>



![image](http://res.cloudinary.com/di6higy77/image/upload/v1716840536/o4xjkk4maoyyvinfar8t.png)


https://platform.arkhamintelligence.com/visualizer/entity/0xf1d968251FC105da8c42945Beaa0AF7486340aF1,0xe94d009dbFDE68b247f7301eEEa7f61Be39f6E3B,0x11f0F6B2Bb2032F349940d7F87ad1b3eE13CFfEe,0x2FE11917Ec11A966abD938edc1729DAf6C15C470,0x507451c67E5D9fABa3734B3a93CeC36bcFCBaC70,0x51b3335C908e97D597aeC4d813B0AC7B3Ac26b9F,0xC09359201CA79775682848B79fEaDb9789f66A93,0x6338Db79F1e159ABCE037Dcc74d55D29CBF69232,0x0ed9Dbb8AD4b1512797cF65e5E7be293B7d8117d,0xae2d429375B86d121deD40f415BaafB763c8EfdB,0x460B8718B5B80d4302b2bC3BbC9a4e23FF5e35C8,0x2f4cBfB4c0f406D8eac4F90322CAB0D79272F048,0x7Ac694007f853cFC1b549B150E8c2245D086B889,0xb8B86Cc205329906830Ddd44BAda1E60148ECE51,0xa060A88a79B525c8A21Ea60970f647b01a53Fb76,0x67f50b32C3d2bDca444746599fcb56eb7c872e03,0xc2B99eDD6CFa9139d331e0FA066350ef91Ed72ED,0xC4842Be80353C20bA4169361DdB8205F726764CE,0x8FCfA0906419cFefb92F6CbA0c3ac5ac8d6f3731,0xb08FAA26F9C599af46A38a9b999563923469f2b6,0x2b507470474e10a4568d638817BE95C43B39C8Ee,0x0D5f63361e3fEB7A6CAb2Ea3B5e742f75a8804D1,0xde8AFA2c7D06506e7f49860EF380043fDb7f66e6,0x983555dA9B89e5eDabD1e294ae665117814Fe641,0x857eee4cd166F6fEE4291f16498fEa5175153a0D,0xf73ac391b59C65a46293c1Ef23362f19A5bD94b3,0x29c5666E84fBB060E50C2701299D088d600Ff786,0xdfAF90B8aE0585c2f9412149d2c263993AFd880f,0xef5c9297BDAa6d3c0da26e62FeaEAa6E52eA2548,0xe093d7fB0149Cd75D0c255e402A41E6Aa839c064,0xA05144E0fFE8139881252cec0965Ce6323a3d16A,0xa9C4d3cc0e7e1f5C4a946093581AC271b4f90fe6,0x8EE366F9Ba93E8F8FeB629C63bAf572d26A32D65,0xa7D7d210b4D5A4aAEfed82C571AD8814D7A5465c,0xfb7640108338F8A9113F49bc40a7c7C669620858,0x3FdcF3823b2AB78a0284f821cAAb936715C06D6b,0x06D4B669e8CEd33642A3d898EAE2c14d6443C45b,0xF9189759bEd2df7a615B8999D8897871b10cb17F,0xce3d843257126CDB9c6dA94c182e9541386eb978,0x580CeE565FD5C133276A37cB6Aaf184De29F455B,0x3D2e0e704F9853d491bC3BD8E8454AacA0109921,0x6966575866dD29F6Db2caadbc645e15d8E868403,0x701482d029322e986CF778c282d1839C9f70FC8a,0x4CF8Ded542a12f07671DD61980a9585F8d6Bd74d,0xD96c4273179f3761cA2aa1bAe283ca3b4201d879,0x2F925597b242F283CbAda91667831555A76F635B,0x1f1c599472D1b0431A89DF59740D74F0f87ee4f6,0xd888fbbbB591A07A7015aCE5509ACa2483733c76,0x596C0c491F981565D47A0AD8A611F792ffDa8Aab,0x5bcf034913B5a9Bb141949f22e6BDb5F4572B993,0x7d4Ec5D458E5e180561B19a4Dbf0cd17558eFAed,0x05128E9Af115ba970Cd5dD34fE3C1fa8df517F61,0x68dC2377AE20652D392611Ca815633cC87842729,0x90EBB93dbC3A26F7793fc60Af766AFCe63622d62,0xAe1bC91f91496fBC1cF0f04A958953CD5Aa51241,0x9aF4F5151957dEEccEb035C9ca2AEB4eD8a0EC0e,0x94eB520127dE2A323b4D89f46CA85c1CA6f3eBb4,0xCBACBb3DAC498E1310b2732cF7728D657D622AC8,0xACae7C1F36428A37bb002d1418ae7449B5297eD4,0x636a6B9CB77040a9FC263A11fF911402A267C5e7,0x7F91CF010175f8416745a8c1fffE6A86d7c87869,0x35aA41a273A78Bf08675549db514890D83e36B81,0x2B47E0cA4F24E40D029464fA7C25e7d800eEF55c,0x39972Ec19C65ef3995a766fd6C742c10073B7705,0x1aF3469eE64bE477283Fd7BF46a63AFac07BF88d,0x4846002d1803b522F211C57553E1bD69Fa6B31Cd,0x1BfECE0F8c8718ED9EdBf2938D757c0A2D039433,0xf3D3CDCB12718fC8860A3B58e577630521317A1a,0xc1429057bE5D4dB24c8dc51eB46A738d55617b56,0x6c9594226Ad2ACCf79Ac087C36bdD63d21640faC,0xFc19d702478a3E1df8f013700d25ae3cE9a51F5b,0x7082486b93e80996e59eDCCCd7f8601f7A16a535,0xe456eC754B04D83ACC99Ef6c39C13076f3C7a6f7,0x1D6F9DD6FE36a8c976bfa53D7e27eAe71a03a63F,0x43B9fd8864102db4b2aa16562A522b31cF263fF6,0x284A3E94f575386708Af4ee62862735F28c1Be19,0x0F5c0F6E2c42d65abF7fB38CfC171fF6207B30F9,0xF78F351b04C1bf2857fEB0d0F623dE04EFC7076a,0xf3d1C44Af06Cf95A20f66Ef1537b7F5Cd227e6E5,0xbBC4b8A14B76F4f9Cbab5b1d2049acdF11aa3571,0xd408696815Cb9B4974e016430812fb444a7cBfc1,0x8C29cdaDfc797C775FD9cCB3Cbe8856CC3b29AaF,0xA3ddAE122E6287464207cc0aFb68C605dF9FFE9e,0xcBa70Cf05d532cce6EFa87E21278b271c465Cb4a,0x7297eCa78a3f2BbdbF98ce7EF51189a857342Bd9,0x84e6B0a97b839d454f55d1428D1E88285fEb7e8D,0x9298db55504F95DCeC4B60349a909E6CAB006f7A,0xDbfdD24f859439E07235B45d529bbF789AF2aBe4,0x5A352432131A5AE6B96EA333AF12EE8ACe539Efb,0x45765Be0A3a4EEbC53643C3E9250fa7184af40BB,0x735CD4Ef75DCBb99b0659c32f5c8083EeeE4a77B,0x7e7250be6a32ED140E1361E939c1025fE66623E2,0x488Dc7f7064A9Ebb9DF1dE923DA729464A18f416,0x41F8e3Ba433cBE955Ad07397167f164AaE2db00d,0xab768dF3AaC7C76B07b8C37d6E94F4385C11AA50,0x7384d84ae8023742f956D1152b9c2906fCF2061B,0x7b9C4b6c80DC278c8b6a7ddb957d9c07A52f5BdA,0x48269d4B02070D2Ec55597D587b2AB2C71Bf2f23,0x51266E8454f4c34Ac5fD7efA657dE4f67fC198d7,0x5cE2498c8004dd1c7C4F3387893cc22d15a923C7,0x2B748D41060DE40ee8F1053A89fF4f4bf6bB40C4,0x5f17612758d0a0F76646797a019bd8e1bABB67C5,0x3d463E1a2533A8Cd24682C8070DA980C6c09f4e1,0x6E96cA94449204a9f3098299A63086C2cb050C51,0x22FFE947d4E88de7D56706b243E5206987868220,0x9C1805b485255aA50A988e607EbFA0245a3F8d32,0x28274F670827DdE8eD103854e753b3219f64eb93,0x0C97B99beCe0daE7E07848160b0ced5a42DBdA14,0xf9E05010dF1b9Ea59DDac4c5e17b7A7B9b65201F,0x5c3B787E80aa3A358bdC848e193cD9a744f397Bb,0xb033c98E75B5FEFB916965E29b4c2cF3bb78eD45,0x6E270fc07f469651423166c4C3697edcE4f232cF,0x6BDAAfa7b66F81fbe952Ff5abCEEC8C3132cFEB6,0xDd5565917e56EDaf9Fd7b242b9242367051163d7,0xfcF21167428857A2D3EC34A2365148c12D774fE1,0x427b7B51C549E391714b7958f437bB51865ebCB9,0xC9a9c8d9c12b775Bcd79f172C9827cd77E1fd2d4,0x3aa0Ba56A9F5e9CfA286d0dE5955bb647877E80b,0x2D405E95Db99c70986E826208A86FC1b7Ac9cC44,0xEd85dBC2c59a1cFA5af6e3aD3d75Ddb03f0a2B09,0x88C8af64E4198af892D0634415E48158585cA667,0xebB8E715c4c4D338A3c08872c252DB06ff6A59c5?flow=self&positions=%7B%7D&sortDir=desc&sortKey=time&usdGte=0.1


ZKSYNC NATIVE BRIDGE scripted 
same exact gas => scripted


timestamp / amount / gas / tx hash
```
1 0xf1d968251fc105da8c42945beaa0af7486340af1 2023-04-08   0.010476942947516351   150024   0xe66ef5042c7385f7f8c714b5ea3fcf5565927de1c8888c2224e46c550619ecd2 // 2023-05-22   1.200699513705773   149210   0x6d59a41c7378d36df2cdc58d5fd6e392b16d226207a8bf7a55eebca27d5e5e1d // 2023-06-05   6.0005245968994965   149210   0xad9e1572088300320fdafddbb471cc02be997057dedfb580be46e8bebe187bd4 // 
2 0xe94d009dbfde68b247f7301eeea7f61be39f6e3b 2023-05-13   0.10098649685028194   149181   0xcb9ebc59b498ca6fbcff66f362f1ffcffc429eb962e20e1182a1f2bd49f2aad3 // 2023-06-05   6.010447047250346   149181   0x4b69c7296635e447831721e64f7db5b7f8b8fa38cbdf14de81f46bcdb85489ce // 
3 0x11f0f6b2bb2032f349940d7f87ad1b3ee13cffee 2023-05-13   0.10092650000901687   149210   0x3ce3f41d496de9ac7b444563bf5e8d8d8deb3ae110fe5dde71ddd23ef8694df5 // 2023-06-05   6.005480085969324   149210   0x4497e56d6ebc40cc8605f0cf9ba6b1f4acdd1836f4c3857a9cdd40351cb80392 // 
4 0x2fe11917ec11a966abd938edc1729daf6c15c470 2023-05-13   0.10093732232700663   149210   0x0ec7561b0f1d681f0576d14be322f465a5cf0d6929ecd9293309c4eda13d684c // 2023-06-05   6.020443343996447   149210   0x55d515031457191e9e97b54593ddc624f1b619f6a6334da600f50a68fa3f0f41 // 
5 0x507451c67e5d9faba3734b3a93cec36bcfcbac70 2023-05-13   0.1009429049708024   149210   0xe88c51965f38e88aee44aa255566cce9672b09cfdfe728a67bf3c25a0e93be57 // 2023-06-05   6.015532551323869   149210   0xf45adb2acb9f917ed5cfeb6006b4277197a199caeb8cefc93e43866b70fc4cd1 // 
6 0x51b3335c908e97d597aec4d813b0ac7b3ac26b9f 2023-05-13   0.11094232359568158   149210   0x5b3809d44b9b56a602c97887144d19c1d65c5556dfae079840471b325c4d2572 // 2023-05-22   2.020697983831569   149210   0xf8327323197bc90fda7905d83833fce4972b4ca3d2c96b0ce70e83f823e463aa // 2023-06-05   6.010571643032658   149210   0x28ab80bf18a168609a03b74fedd67423897f3baf618a3ff043a7ce1fb0047447 // 
7 0xc09359201ca79775682848b79feadb9789f66a93 2023-05-13   0.11093379586194103   149210   0x9f9079938cbdb045ec4edb874cb43916c58a7e5f2f358f0317d33049070132ad // 2023-06-05   6.020498903340701   149210   0xf9bc5ecaa7b4c75af308d1ea9b0e5ef1c39152d7a11fd8bc94406c4d9776b314 // 
8 0x6338db79f1e159abce037dcc74d55d29cbf69232 2023-06-05   0.07225934046868264   149210   0x485b103d5f31d5755d7088ad5f86183e4c74b0857d9fc78a6486a961338dab65 // 
9 0x0ed9dbb8ad4b1512797cf65e5e7be293b7d8117d 2023-06-05   0.06855066553968808   149210   0x78eea059c193f83f5db730d38aecd6616b8e4183090e1e45ccec6b121db8e2d3 // 
10 0xae2d429375b86d121ded40f415baafb763c8efdb 2023-06-05   0.06902769888139146   149210   0x11ae126050da8ea9a8b386f8412203c437de3127fb0269a16048bc24cbc31e74 // 
11 0x460b8718b5b80d4302b2bc3bbc9a4e23ff5e35c8 2023-06-05   0.06809539411004656   149210   0x85a7d794755d1e74f714229440b58ec999b6fc0ba35f33c7e9b5ad264d66eeef // 
12 0x2f4cbfb4c0f406d8eac4f90322cab0d79272f048 2023-06-05   0.07000006095753954   149210   0x759188a6fef70f7aade65573cddd44bcc35ec1cc26b7b70d9334c9098f886ad4 // 
13 0x7ac694007f853cfc1b549b150e8c2245d086b889 2023-06-04   2.925583109971641   149181   0xa5b605d509f42bef0796a0274a503db0a6fd195128a857f6d57dac027a154bfe // 
14 0xb8b86cc205329906830ddd44bada1e60148ece51 2023-05-22   1.9907193094192845   149210   0xcbd0a64b187b88088fdc55cf861f0ae6be1bf921667883390086d415a125a3e6 // 
15 0xa060a88a79b525c8a21ea60970f647b01a53fb76 2023-06-05   0.07196078051110778   149210   0xa339be5da6e792f01d3cca3eb6e07bb1f38436a6377ac9bb0aa858e3b5f99cec // 
16 0x67f50b32c3d2bdca444746599fcb56eb7c872e03 2023-06-05   0.07189986073840332   149210   0x4334db1d1e57540e00400d55179d0df1071959db752bd82e95bfbf1a3d1ff80d // 
17 0xc2b99edd6cfa9139d331e0fa066350ef91ed72ed 2023-06-05   0.07178979182681718   149210   0x4a60c9793c6e1b73c8fb0140bfa924b02d52f331877eb06c574f4d3f54f52756 // 
18 0xc4842be80353c20ba4169361ddb8205f726764ce 2023-06-05   0.06879055636611921   149210   0xc2a4ff76f057f4ab3dad0420e25ab6db51591748127ad5f79676e1c32f11cb7d // 
19 0x8fcfa0906419cfefb92f6cba0c3ac5ac8d6f3731 2023-06-05   0.06856931467724317   149210   0x8823606cd2f82f0149661cc98e106793629d5fec82d548c33270ba51de0bb0ea // 
20 0xb08faa26f9c599af46a38a9b999563923469f2b6 2023-06-05   0.0689007463098979   149210   0x546bf324eaa9c7ccdee7a954f70fdc0618adb2744169710b7f812a80ef217d7c // 
21 0x2b507470474e10a4568d638817be95c43b39c8ee 2023-06-05   0.06844877978318918   149210   0x2af28cf8bca5b7399695050224fea1ea23bc9cfb52b3c9cce50802be616ef4ba // 
22 0x0d5f63361e3feb7a6cab2ea3b5e742f75a8804d1 2023-06-05   0.06831940866586597   149210   0x493b3634e01c090fa45e5f20c3f76d070c464797e8bc7af695fdf39849aa4c28 // 
23 0xde8afa2c7d06506e7f49860ef380043fdb7f66e6 2023-06-05   0.06985968410304562   149210   0x73a0cccfb452ed31720edd45e436d1f85e1c67a71f2658dac2b4730798c34f17 // 
24 0x983555da9b89e5edabd1e294ae665117814fe641 2023-06-05   0.07137635469188205   149210   0xc651f4f9fb443f34ba7054c770a932b016c47a526d09073170806a5f36d02549 // 
25 0x857eee4cd166f6fee4291f16498fea5175153a0d 2023-06-05   0.0684998248110034   149210   0xbce6efd11f1324d663662d2d2e749bf06714ed398ffbe273683b9b3fb7a69130 // 
26 0xf73ac391b59c65a46293c1ef23362f19a5bd94b3 2023-06-05   0.069317037999134   149210   0xe5d8919f1a6d876ccef710c80f8a805a4975045fb54449a74ffd9f6cd38ee573 // 
27 0x29c5666e84fbb060e50c2701299d088d600ff786 2023-06-05   0.06787523369557873   149210   0x5a1a19ef29325e812d50b71b170426fdacbb67824537d9eebfa290ffd80d733d // 
28 0xdfaf90b8ae0585c2f9412149d2c263993afd880f 2023-06-05   0.06840839542819059   149210   0x36130542873f59c4b24545ee0bef07faab3b53d257f20d160fd23769d104d837 // 
29 0xef5c9297bdaa6d3c0da26e62feaeaa6e52ea2548 2023-05-23   1.9906598130043776   149210   0x9e8c751c0679e81e48cb8d0c57935c0d48ad83cef6f4e8a33bc23306f93e76d7 // 
30 0xe093d7fb0149cd75d0c255e402a41e6aa839c064 2023-06-04   2.5005131788498196   149210   0x5f3ae8563cec82bb3b80bcb7c4912d39eda2266442c0f3826f59d905eabb664b // 
31 0xa05144e0ffe8139881252cec0965ce6323a3d16a 2023-06-04   2.930587574266642   149210   0x45a94b0f0d8677cae572039b2b17d88cb634d1314d46ef918554f61e5e054359 // 
32 0xa9c4d3cc0e7e1f5c4a946093581ac271b4f90fe6 2023-06-05   0.07035247325551736   149210   0xa3ad2414e1104ba410d9ac2982931da3648748a9c663abf51fa95a8f1f7091f3 // 
33 0x8ee366f9ba93e8f8feb629c63baf572d26a32d65 
34 0xa7d7d210b4d5a4aaefed82c571ad8814d7a5465c 2023-06-18   0.07269185609287872   149210   0xfbdf8e9f43457eb028393c9640a2548a1e446e1121d0811542edfeaadb4b2062 // 
35 0xfb7640108338f8a9113f49bc40a7c7c669620858 2023-06-05   0.07473092308596585   149210   0xd76c98d2e91a486594df36bb03d4b1c1d7c090c11aa0bdb9c620f04dd1133db7 // 
36 0x3fdcf3823b2ab78a0284f821caab936715c06d6b 2023-06-18   0.0720272789507662   149210   0x6b019515f00820a0f6ad676ffdc929b75b1730e1e43f99d5c7576a9df7365984 // 
37 0x06d4b669e8ced33642a3d898eae2c14d6443c45b 2023-06-18   0.07266514553103236   149210   0x98335d96df2b95a9f6a5bd7e13c7642ee39943924f26170cf2733e2ddcbf8ee8 // 
38 0xf9189759bed2df7a615b8999d8897871b10cb17f 2023-06-05   0.07251369972164622   149210   0x5e3fff512784bba5c85eacefb28726ea85141178360db91d567dc5798a156e1b // 
39 0xce3d843257126cdb9c6da94c182e9541386eb978 2023-06-05   0.06952113006164308   149210   0xc35ffc2aa09bf7c0e7b4a3287e600d53a59ac9f7140578df9484c3ca8d8a1383 // 
40 0x580cee565fd5c133276a37cb6aaf184de29f455b 2023-06-05   0.07160128992674003   149210   0x3e626e19761b6e8be0805dc890ef7f320400a89387b408fcba074a9cb08a3641 // 
41 0x3d2e0e704f9853d491bc3bd8e8454aaca0109921 2023-06-05   0.0684888733670111   149210   0x483e240efa57f803ff38c1abd5e1fbba99e99f12ca318619f065668899ebaf4e // 
42 0x6966575866dd29f6db2caadbc645e15d8e868403 2023-06-05   0.06779865682882968   149210   0x7934d28590113a825d0bcc0540511a3c60e843a58fe4f2b738f8df2bb917f763 // 
43 0x701482d029322e986cf778c282d1839c9f70fc8a 2023-06-05   0.07138483838703415   149210   0x4731068b7ee42e01dfbe1711d707d52e02318fb402ce04a9340bc99cc4c00138 // 
44 0x4cf8ded542a12f07671dd61980a9585f8d6bd74d 2023-06-05   0.06795710725466121   149210   0x08c7bc9d6ce065a1eaed4482f2569338848f2493f16a82abcb74c339efea9341 // 
45 0xd96c4273179f3761ca2aa1bae283ca3b4201d879 2023-06-05   0.06859264785518215   149210   0xe16b87f1400dc51ac968e3a35c3b31d788a73852f746bb5bb3a6bc0eb480b0fa // 
46 0x2f925597b242f283cbada91667831555a76f635b 2023-06-05   0.0723622806354856   149210   0xf33d1dd75a0c31b624b8fe0e41dad386413140abb2c79cba2cdc769cd2eff581 // 
47 0x1f1c599472d1b0431a89df59740d74f0f87ee4f6 2023-06-06   0.07247830146374969   149210   0x38996360b1d2d96f8d0892aa4c6fa1a8d88e80127700b654c7434e0421120059 // 
48 0xd888fbbbb591a07a7015ace5509aca2483733c76 2023-06-05   0.07092478114604085   149210   0x9a506320dbd87642303c13f7f55decf4d8cfaf55082a0777d8b8430cef0da8e5 // 
49 0x596c0c491f981565d47a0ad8a611f792ffda8aab 2023-06-05   0.0721104687565196   149210   0x320710bf3a69a0a0598749d29117747112b1157df7e6143250d77c9d8a167070 // 
50 0x5bcf034913b5a9bb141949f22e6bdb5f4572b993 2023-06-05   0.07251764495626638   149210   0x61d05804cb80908845739a239ad105219cd6a1066200451db79952b826472bd8 // 
51 0x7d4ec5d458e5e180561b19a4dbf0cd17558efaed 2023-06-05   0.07188491091900202   149210   0xfad1eaf5d0ed336e1a12544bfaf5c24058bef91ba8e5aab2fe48ee16e4d9f963 // 
52 0x05128e9af115ba970cd5dd34fe3c1fa8df517f61 2023-06-05   0.06864070886773332   149210   0xd32b16a19c326947aca833da88e5605a519db8331a3f706d1ba21107c8bb62a6 // 
53 0x68dc2377ae20652d392611ca815633cc87842729 2023-06-05   0.06782992528679492   149210   0xd97840769ba0d9f1c10c8636738e95085666cbc4f678d8cd58ec61bce4c99b1c // 
54 0x90ebb93dbc3a26f7793fc60af766afce63622d62 2023-06-05   0.06924096601651886   149210   0x910343c76fc97466cb46f185e3cdd12f745fc686b202ed8bd39d45622939682d // 
55 0xae1bc91f91496fbc1cf0f04a958953cd5aa51241 2023-06-05   0.06418024763345373   149210   0x03bb724a0022cc8e7bd86228d5ba6300d6e36d12eaa7179aa74171a34e9a501e // 
56 0x9af4f5151957deecceb035c9ca2aeb4ed8a0ec0e 2023-06-05   0.06623303069027313   149210   0x1dddcd1bbf1f57e81905ec956587feb17f01d0ceeafc7e937b82bcd87bf24f33 // 
57 0x94eb520127de2a323b4d89f46ca85c1ca6f3ebb4 2023-06-05   0.06854421487257895   149210   0x1f6b332eea6a796706d07a607e8931b7ee90753f88fe88f2f63e21e4137e452f // 
58 0xcbacbb3dac498e1310b2732cf7728d657d622ac8 2023-06-05   0.0687505767200902   149210   0xda58e69f1f1222e6d02bc61998c358bd86a7972115edbd62581334e3ed14b69e // 
59 0xacae7c1f36428a37bb002d1418ae7449b5297ed4 2023-06-05   0.06998308461493612   149181   0x5088dd04508878110c293661725571504c2174c65a537c916ac3a006b5c64699 // 
60 0x636a6b9cb77040a9fc263a11ff911402a267c5e7 2023-06-05   0.06348812280542418   149210   0xbec3cb2639061473b79b96af996fea0c13db73cdada20f2cabddcca6eab62707 // 
61 0x7f91cf010175f8416745a8c1fffe6a86d7c87869 2023-06-05   0.07221600778628647   149210   0x2880bee1fc7a1d70752a3663422351ffbb73d68056420fd4fab0a46c0b76014b // 
62 0x35aa41a273a78bf08675549db514890d83e36b81 2023-06-05   0.07203210279807055   149210   0x1802694b133a01e7f959caa59622bf563060e02f9cfe8e5fe72294beec463b6f // 
63 0x2b47e0ca4f24e40d029464fa7c25e7d800eef55c 2023-06-18   0.07087700039273084   149181   0xaf4efac04af3005470eb7a34340689ed1d35095ca41f211bc332496f6f29c5b4 // 
64 0x39972ec19c65ef3995a766fd6c742c10073b7705 2023-06-05   0.06844978148678862   149210   0x9482dec06c44b1fe706dde9b3c4cc3a0f2eed48d54261734ea45413a139eb92f // 
65 0x1af3469ee64be477283fd7bf46a63afac07bf88d 2023-06-05   0.07292272204402608   149210   0x7b0cee2e36c03c75d04e01067effda489098d740267779922e5873d1c937b32e // 
66 0x4846002d1803b522f211c57553e1bd69fa6b31cd 2023-06-05   0.07163825638134406   149181   0x2b5d59d4e6ad790e5205ff6a2cf0b1ed83ff7c553ddb9c9fc80036545966fe53 // 
67 0x1bfece0f8c8718ed9edbf2938d757c0a2d039433 2023-06-18   0.07256922268452026   149210   0xfe8ca140c9aed2ae01b80dde090a9fa89d23ff8d72377fda98b617ff9eabb28d // 
68 0xf3d3cdcb12718fc8860a3b58e577630521317a1a 2023-06-18   0.07269272177018014   149210   0x500dcea280d94c5736640a42da0aea9ceaa766b898760eff5d0129b31cbab6e9 // 
69 0xc1429057be5d4db24c8dc51eb46a738d55617b56 2023-06-18   0.065504201525112   149210   0xeb0431701d655f458906e8390d60718c57adbbb6911140d542085177fb5fc617 // 
70 0x6c9594226ad2accf79ac087c36bdd63d21640fac 2023-06-18   0.07284579260581989   149210   0x6579e57645ac3f89157f36f0ee6284dfa2c5f33743c177e3c8801a59d49dfb95 // 
71 0xfc19d702478a3e1df8f013700d25ae3ce9a51f5b 2023-06-05   0.07168383391849474   149210   0x864c261e930abfdf3429901e46497903e6bd8c52f5336f649cbe17eff4fdbd60 // 
72 0x7082486b93e80996e59edcccd7f8601f7a16a535 2023-06-05   0.07256520509432243   149210   0xfb914f70c7ccc9e8142d94d892769f36d13fa19a6d0010a4a81fceefdd521e70 // 
73 0xe456ec754b04d83acc99ef6c39c13076f3c7a6f7 2023-06-05   0.07198372187600673   149210   0xceeb0137bb050a82a45b8d35e30e5a7fcdec18388c5345970fa8ec560f71e881 // 
74 0x1d6f9dd6fe36a8c976bfa53d7e27eae71a03a63f 2023-06-18   0.0730525724220314   149210   0x8872ced67914ecb9a410d60cfc992455263bc19ae539d08dba600f6e19d90632 // 
75 0x43b9fd8864102db4b2aa16562a522b31cf263ff6 2023-06-18   0.07209362289163491   149210   0xe09fb18f07263f51ca1ab5010d97fb39099e9721803a8dbabd46419ab7c95713 // 
76 0x284a3e94f575386708af4ee62862735f28c1be19 2023-06-18   0.07257245463612634   149210   0x1f095fc0194f0ca4e5f9a965ebe6267df2d33f862e96ff2bad4070d06c17181f // 
77 0x0f5c0f6e2c42d65abf7fb38cfc171ff6207b30f9 2023-06-18   0.07334601755634958   149210   0x743137f82fc3b2275249f590d57fa80ac069c52a25728714b72210109968c84b // 
78 0xf78f351b04c1bf2857feb0d0f623de04efc7076a 2023-06-18   0.07352304484465683   149210   0xb945bf0be23aafa33dc4276baa0c3052e4ab709fffd777d9ebd70cbd92510bc1 // 
79 0xf3d1c44af06cf95a20f66ef1537b7f5cd227e6e5 2023-06-18   0.07314737500674152   149210   0x4bb165b3b1558975c311446e519ba939209eac90b8732e79329017f207f7e30e // 
80 0xbbc4b8a14b76f4f9cbab5b1d2049acdf11aa3571 2023-06-06   0.07189457556422871   149210   0xf0c228233a5abffb29e41506d36cd2bbfe332922c4fde385226a62eae119ff28 // 
81 0xd408696815cb9b4974e016430812fb444a7cbfc1 2023-06-05   0.07166904487804701   149210   0x9fffe2c1e6878bcccd7e0c147d00e585a5d9f8a2018a6985cc6a698d2be0ead5 // 
82 0x8c29cdadfc797c775fd9ccb3cbe8856cc3b29aaf 2023-06-05   0.07261494723690624   149210   0xa1a4a8c6b0674e66b7e43aeb63f809e0ee6a160e3e711d0a7f4f710c2d6db476 // 
83 0xa3ddae122e6287464207cc0afb68c605df9ffe9e 2023-06-05   0.07169816144322116   149210   0x1dc8eb7c2a416ba5a68225e6a23e8caef70afaf5942fcc854d12eacda8d792a0 // 
84 0xcba70cf05d532cce6efa87e21278b271c465cb4a 2023-06-18   0.0733022388055309   149210   0x9a9b3917721eb338575c9f2a389972ab4e5a24f11163ae356375dd13c9149a6c // 
85 0x7297eca78a3f2bbdbf98ce7ef51189a857342bd9 2023-06-05   0.06858127785231496   149210   0xd1c847888085ba2ce5c343ea03f5181030a577660dc1f5f39c666f1bf28f58c7 // 
86 0x84e6b0a97b839d454f55d1428d1e88285feb7e8d 2023-06-05   0.0712930466620615   149210   0x7a87e7f726dadfd70992322c73f8e93f9ae9e2875f7bd5a4c57d6706d330a1b0 // 
87 0x9298db55504f95dcec4b60349a909e6cab006f7a 2023-06-18   0.07247738971983723   149181   0x87774bb103ad4392a142c72f24b46e55712a5d2bf1e14bbb5f0d4f9b0420d3b6 // 
88 0xdbfdd24f859439e07235b45d529bbf789af2abe4 2023-06-05   0.07138593319248294   149210   0x0866e812b47284928fc364d501a2c7046b15179586a8b480afe587673d35691b // 
89 0x5a352432131a5ae6b96ea333af12ee8ace539efb 2023-06-05   0.07229970803805015   149210   0x5af9907214f49f58b280acac688850ff2d2c382b6e49d4a674eea1161ec69101 // 
90 0x45765be0a3a4eebc53643c3e9250fa7184af40bb 2023-06-05   0.06930136061962625   149210   0x7530e72f31bdb944bff00291e1dc81e7741b279924f2c75bd50a486beeb5d73d // 
91 0x735cd4ef75dcbb99b0659c32f5c8083eeee4a77b 2023-06-05   0.07227858626535948   149210   0xc5ebe21fa660dd110b0bdd2d4e629cda4e2eae9e53c499ca18db7475da68f184 // 
92 0x7e7250be6a32ed140e1361e939c1025fe66623e2 2023-06-05   0.0724829283500367   149210   0x370ed5c0f9a7a21675130d50538410c7b8ae4e580bef49c2163290cadcc4c74d // 
93 0x488dc7f7064a9ebb9df1de923da729464a18f416 2023-06-05   0.0714744781347394   149210   0x80f3835e8e9ed53b325bda993ff658bdcf91326205402f4193fd630a05342d47 // 
94 0x41f8e3ba433cbe955ad07397167f164aae2db00d 2023-06-05   0.07249792036989236   149210   0x32c8c7da7288244d4bef24c5b6ccd6b8417edac51882f0308144ca17455a35f2 // 
95 0xab768df3aac7c76b07b8c37d6e94f4385c11aa50 2023-06-05   0.07179474660925211   149210   0x70bc26b1b0e1a1cb68e01c07d2cc9b60d3e0cadd986e03eab7d85ad8e3ed4bce // 
96 0x7384d84ae8023742f956d1152b9c2906fcf2061b 2023-06-05   0.06879310302012677   149210   0x4f9abafc620be614906eee4cd7160905bdf69b1dad59483847f250dc4ec38213 // 
97 0x7b9c4b6c80dc278c8b6a7ddb957d9c07a52f5bda 2023-06-05   0.06890771366351386   149210   0xdbbd904e81017026dc3c1bff65474ffdbf2a6ffaafad44f265fd4ee5c869ed42 // 
98 0x48269d4b02070d2ec55597d587b2ab2c71bf2f23 2023-06-05   0.07065684068068895   149210   0xf0c83b030e788bfc1106764fcb15df11ac30157f963b2e1c3bf16e8dea585e2f // 
99 0x51266e8454f4c34ac5fd7efa657de4f67fc198d7 2023-06-05   0.0717873595540071   149210   0x93069ce30e8b58ef8970708def6bc7110601a2e7ce8ea02304a233f66089ebf4 // 
100 0x5ce2498c8004dd1c7c4f3387893cc22d15a923c7 2023-06-18   0.06663448284149905   149210   0x15aece950edf3a4cc8a039af18c3f0c5f4f61a6e2c37856ca36b89247cbbaec6 // 
101 0x2b748d41060de40ee8f1053a89ff4f4bf6bb40c4 2023-06-05   0.07202539878935445   149210   0x0dad51c744589efc2770d885f1410b02d078d17c74a7e85a763bb2d5569a15c1 // 
102 0x5f17612758d0a0f76646797a019bd8e1babb67c5 2023-06-05   0.07138108848437127   149210   0x327fca91bd0a6d10fb7564c4af9cfce9f5a53cdd4162e242debd645ee1405b18 // 
103 0x3d463e1a2533a8cd24682c8070da980c6c09f4e1 2023-06-05   0.07224352091169521   149210   0x274704a9b38468a20a0541fc8db53a15a6196e181f37e5eb3349e23ee3885233 // 
104 0x6e96ca94449204a9f3098299a63086c2cb050c51 2023-06-05   0.06874698439125997   149210   0x58a8d17d801bddff3bd2f1f62552f8e2298647d6af7f3464760271da275f1d24 // 
105 0x22ffe947d4e88de7d56706b243e5206987868220 2023-06-05   0.06859308007790162   149210   0x7a19c011e26137abf2f2d2432e569e5163e44f75ceeebf4f4054096aee7e01e8 // 
106 0x9c1805b485255aa50a988e607ebfa0245a3f8d32 2023-06-05   0.07055438423472532   149210   0x299d87fda854e4c46459c908d751fe5f6a48129986a053b5646c064a117588df // 
107 0x28274f670827dde8ed103854e753b3219f64eb93 2023-06-18   0.07296655705620742   149210   0x7f7f1bca5466a4aca1e9a9eac8de8556d81ec1b5e2fb2d213df036ac98baacf6 // 
108 0x0c97b99bece0dae7e07848160b0ced5a42dbda14 2023-06-18   0.0727873973626163   149210   0xe41a83ecacf2d8ad00f29f0c787872c15251ee09c91e5e119f331dfc81fbeaa3 // 
109 0xf9e05010df1b9ea59ddac4c5e17b7a7b9b65201f 2023-06-18   0.07325516815694685   149210   0xb4db71b82da89f2533add43b37f830b4250e9e3aefa4eaa5f7eecd7c613e7d81 // 
110 0x5c3b787e80aa3a358bdc848e193cd9a744f397bb 2023-06-18   0.07313610422723327   149210   0xd27ebb62109b8eda21a3fbb4284951b1d0c0c13c535d8045971e59bb9f83dc05 // 
111 0xb033c98e75b5fefb916965e29b4c2cf3bb78ed45 2023-06-18   0.06906200015591588   149210   0xaf774ce046d896e4a13960d2f0a656bca2b959f4806b326ead0f963d98c2ea69 // 
112 0x6e270fc07f469651423166c4c3697edce4f232cf 2023-06-18   0.07213706988311613   149210   0xe358861be1ef66dfdb18604d2a8a40ecf48baa17c5ba95bf9c50c1b48d412e44 // 
113 0x6bdaafa7b66f81fbe952ff5abceec8c3132cfeb6 2023-06-05   0.07142806394934482   149210   0xecd54f358bb810bf1e1079d1cbae9f70e381894fcca1d433a6b45b17c9d66bf2 // 
114 0xdd5565917e56edaf9fd7b242b9242367051163d7 2023-06-05   0.07160543618173695   149210   0x27cfd924bbe531dc4bbc71f4b8ae5d30832a01fffc11bb46ab972bac448af619 // 
115 0xfcf21167428857a2d3ec34a2365148c12d774fe1 2023-06-18   0.07281519067542164   149210   0x97aaa0c7eca30d8c2dc2e896102189ca76b6630cd1496252880efb28d1ab0bef // 
116 0x427b7b51c549e391714b7958f437bb51865ebcb9 2023-06-18   0.0689343908107972   149210   0xbc102236b8499a9738b0222fb46a84b49b8e8c777294dcadb6b6c50cbe8e56ed // 
117 0xc9a9c8d9c12b775bcd79f172c9827cd77e1fd2d4 2023-06-05   0.071925218300575   149210   0x62d80c4043ada12404c9357bf0de49b3b0f262ee55a449f912f9c7a566213840 // 
118 0x3aa0ba56a9f5e9cfa286d0de5955bb647877e80b 2023-06-06   0.07199704960177201   149210   0x5cc5a7eddea2118a23b0c59711b48a3c75b3c63f0d7970ff68135da7717801f1 // 
119 0x2d405e95db99c70986e826208a86fc1b7ac9cc44 2023-06-05   0.0707682373381885   149210   0xf611326883683f2f83fc020fbfdc80f5d5caded2513bb1aa4452a4358ee3b420 // 
120 0xed85dbc2c59a1cfa5af6e3ad3d75ddb03f0a2b09 2023-06-05   0.07187275389824815   149210   0xd28e9810b861d02a6e9986ed4a2c4f0a1aad983ef883b628c5eac45e32a3b2eb // 
121 0x88c8af64e4198af892d0634415e48158585ca667 2023-06-18   0.07361125908474786   149210   0x4b2b28e889344c0c4949b2f56e5e319349225e65f080c9c42a255449b4044dce // 
122 0xebb8e715c4c4d338a3c08872c252db06ff6a59c5 2023-06-18   0.07313593219175146   149210   0x3edd8e4c874e6f0faf661decadbc00689dcf370ec6c3e6624b1438540f4ee203 // 
```

LINEA NATIVE BRIDGE 
same exact gas => scripted

```
1 0xf1d968251fc105da8c42945beaa0af7486340af1 2023-07-19   0.1109964   99301   0xf0deb7b0c64fb6f77820dadc689bc61a0f55952c672c77af8384fa053fcb8bb9 // 2023-08-26   0.300232366238768   99301   0x1c9ba2e23f53290d04649a48504215a87e553c1c317da9d6cf001bdb4f4d53e9 // 2023-09-10   0.040154656451568   99301   0x9d752b9462b637bf17c60c5cf56c97e9acff17d86392035c2852f30d464c358c // 
2 0xe94d009dbfde68b247f7301eeea7f61be39f6e3b 2023-09-18   0.075831626340156   99283   0x3ac65af0e5bda22d12e725ec8a30c5859e4dfcb264bf394f15cbf85645606d45 // 
3 0x11f0f6b2bb2032f349940d7f87ad1b3ee13cffee 2023-08-26   0.320232464351944   99301   0xc477b91a1de75076e3af7c3e856576c4db280fed844a30ed78356fe2a808bfc7 // 2023-09-18   0.075831507418544   99301   0x6c3491e0e59324639a69ed06d294ea3bc4bae73c36b82068541889421fb3d09b // 
4 0x2fe11917ec11a966abd938edc1729daf6c15c470 2023-09-18   0.07693193516204   99301   0xafdfc04c065d1a7fb4fdce65ff37ffa0d931923104be795505f78e472dd9b857 // 
5 0x507451c67e5d9faba3734b3a93cec36bcfcbac70 2023-09-18   0.075931687221256   99301   0x1419866776087d0fadb151c75a070fed1a617a8900c0ff7fae94eefd2e30788c // 
6 0x51b3335c908e97d597aec4d813b0ac7b3ac26b9f 2023-08-26   0.31023299853852   99301   0x85aead90cec00ec47d99202d22123ca9217be4ee1a7c171c15195fa8b450f772 // 
7 0xc09359201ca79775682848b79feadb9789f66a93 2023-09-18   0.076631426347412   99301   0xd08465d15f296153b15f6b39ce45d4489b0c8f278d4fe73452d17ae7c4b1b41a // 
8 0x6338db79f1e159abce037dcc74d55d29cbf69232 2023-09-18   0.076134740083584   99283   0xfc39e21ad3cc0965803b92131e2ae3a8c4733fe3f2adbd465105f19ad8c0c18e // 
9 0x0ed9dbb8ad4b1512797cf65e5e7be293b7d8117d 2023-09-18   0.07517016683394   99301   0xd70b78447414f79852a23f0783b3be3f1c1a71a6efbe72fb10a0e3172bf10de3 // 
10 0xae2d429375b86d121ded40f415baafb763c8efdb 2023-09-18   0.076138404178376   99301   0x38ad9c150e27fc6f66715748301bd0cb5b9cd0162ba593b093e52910d7b7f478 // 
11 0x460b8718b5b80d4302b2bc3bbc9a4e23ff5e35c8 2023-09-18   0.07613851584026   99301   0xda23133aa3f73997b271bb4eee81bdb127072ff550d475da8f83c9f96fb49bbf // 
12 0x2f4cbfb4c0f406d8eac4f90322cab0d79272f048 2023-09-18   0.076438449752016   99301   0xe498cfaaa4783550e8208369b243e2f4cdf6c9cb2751bc65c956a61aacda649e // 
13 0x7ac694007f853cfc1b549b150e8c2245d086b889 2023-09-18   0.076233801806352   99283   0xb6213bd770ba33d810ee6f690a47d4c0502c3585ae34c058ddf939054c5f0783 // 
14 0xb8b86cc205329906830ddd44bada1e60148ece51 2023-09-18   0.07633237458822   99301   0x3a4e4a72e5a8f5e7365ab515036c757457005811ebaa8423d987dc0f4130b297 // 
15 0xa060a88a79b525c8a21ea60970f647b01a53fb76 2023-09-18   0.07634090432872   99301   0x8aaf6fde3646606e7b58c399c38b0c2f287006559314db63edb482b36a70b336 // 
16 0x67f50b32c3d2bdca444746599fcb56eb7c872e03 2023-09-18   0.075941993717008   99301   0xae5e223d4adfd97e2a981e58993230b1e92b937e8c42441aec7b794c4c385489 // 
17 0xc2b99edd6cfa9139d331e0fa066350ef91ed72ed 2023-09-18   0.076541837185748   99283   0xd69b56e2f7352850bbc0944ccbcd2789d02c47ebd6fb4fe0609ea4e560af255d // 
18 0xc4842be80353c20ba4169361ddb8205f726764ce 2023-09-18   0.076136011847628   99301   0xb2a0a623d46b42383b036462dc23163e754570f6afdf13fc2c6be52b2c416cb6 // 
19 0x8fcfa0906419cfefb92f6cba0c3ac5ac8d6f3731 2023-09-18   0.076235082036616   99301   0xf61bb1f0ef907318c3a3c61d0e3567d24f8584ba8ecc825506c60bac57df0c3e // 
20 0xb08faa26f9c599af46a38a9b999563923469f2b6 2023-09-18   0.076735505059084   99301   0xb18fb2d4d1485405adfe28f4bea8db89f35fb4863d09b7f4caa587c7b90a9bba // 
21 0x2b507470474e10a4568d638817be95c43b39c8ee 2023-09-18   0.07673981682278   99301   0xf454beef1b14c509628ebdb699bd31ea7f9537bbe72126cb2f07f9fa2aade308 // 
22 0x0d5f63361e3feb7a6cab2ea3b5e742f75a8804d1 2023-09-18   0.076040093166052   99301   0x81f4b15f765cd5a4c2a381f3dfc3b983f8c414c847cc6bf96f907baf4a3d027b // 
23 0xde8afa2c7d06506e7f49860ef380043fdb7f66e6 2023-09-18   0.076965830621768   99301   0x96e4cdd0d4d5f0731417d4f740a4ebaf2566b407302ce38677ad94b1f2245823 // 
24 0x983555da9b89e5edabd1e294ae665117814fe641 2023-09-18   0.076434591063696   99301   0x4577c5c75b6fa64efd3752955698ef2bbb2b8be284f54bf24ed99aa92ed49a2f // 
25 0x857eee4cd166f6fee4291f16498fea5175153a0d 2023-09-18   0.076641221437472   99283   0xde9e0bc8d12f798823782efe7f41c5aaceb026a8803b2ebe4fd7d780602fd8dc // 
26 0xf73ac391b59c65a46293c1ef23362f19a5bd94b3 2023-09-18   0.076136019080856   99301   0xf9125436750ea4e76b02d773c699221bb5cdc2d72b91d793e069536699c2b1ed // 
27 0x29c5666e84fbb060e50c2701299d088d600ff786 2023-09-18   0.075840166172916   99301   0xfb6e181881a43e7260f9fa4a8726779d1bbd31acf97b38c5f4e498aafe9293e9 // 
28 0xdfaf90b8ae0585c2f9412149d2c263993afd880f 2023-09-18   0.075170235741572   99301   0x44e473ca34c40d42d077c903ce52de3bd0721cc336c96a55a561a0ac56c174fb // 
29 0xef5c9297bdaa6d3c0da26e62feaeaa6e52ea2548 2023-09-18   0.076832372671316   99301   0x022200092154a2ddc0de8b040ec86d52d949076f81f0f2f2ca3131fb88ffbbb3 // 
30 0xe093d7fb0149cd75d0c255e402a41e6aa839c064 2023-09-18   0.07673289884408   99301   0x21809439c6b41daf8131feb6c52b2bc92d261e564821c7b9e0e426f0dc5a68d3 // 
31 0xa05144e0ffe8139881252cec0965ce6323a3d16a 2023-09-18   0.075933343524468   99301   0x415b605e7293dc89c20d3f6bc235f63531a142c072d73a771b0c30e52d407fc2 // 
32 0xa9c4d3cc0e7e1f5c4a946093581ac271b4f90fe6 2023-09-18   0.07703419644626   99301   0x023c7b3af0a8420bdd575407813b0505d11f5b2370c6e9c2006eb351237c40fc // 
33 0x8ee366f9ba93e8f8feb629c63baf572d26a32d65 
34 0xa7d7d210b4d5a4aaefed82c571ad8814d7a5465c 
35 0xfb7640108338f8a9113f49bc40a7c7c669620858 2023-09-18   0.07573508367474   99301   0xd7a41ff1f789ee7988c665f3cae2097b14c5fb9ce6edd56252ae0cabb51175b8 // 
36 0x3fdcf3823b2ab78a0284f821caab936715c06d6b 
37 0x06d4b669e8ced33642a3d898eae2c14d6443c45b 
38 0xf9189759bed2df7a615b8999d8897871b10cb17f 2023-09-18   0.076258035108924   99301   0x75d46cc0869b1b66689bff1da153e42dcfc7dc6254a710a2b48b028c28a07484 // 
39 0xce3d843257126cdb9c6da94c182e9541386eb978 2023-09-18   0.076338922057064   99301   0x4dd6775d23668755b2486008345d530a011fe5ca801ec2a91d1f2415035c0d5e // 
40 0x580cee565fd5c133276a37cb6aaf184de29f455b 2023-09-18   0.07674058267278   99301   0x76ce70a3546f56a1870243a6a46b9c7a5e7ba2ce5a04b36f3095826ea8c73ab0 // 
41 0x3d2e0e704f9853d491bc3bd8e8454aaca0109921 2023-09-18   0.076441798780252   99301   0xf78c17012ebc246944862c72a6007719ce1bb080e4e40484cc5ca6ed3b38207c // 
42 0x6966575866dd29f6db2caadbc645e15d8e868403 2023-09-18   0.076541411690088   99301   0x07bea7f336b4a260b5418c1e84b5c6801070ca7c593589e73bdb879baef192e3 // 
43 0x701482d029322e986cf778c282d1839c9f70fc8a 2023-09-18   0.076941778404932   99301   0x9ed1f84778f1f43a8be0853b145b5a0cda6e7fde0ba2f8499424665fab686e97 // 
44 0x4cf8ded542a12f07671dd61980a9585f8d6bd74d 2023-09-18   0.076541700310704   99301   0x961cfcfcfa55f6f9f10a287479ac9d549b6917e7775f35c1a6cb4347224e1726 // 
45 0xd96c4273179f3761ca2aa1bae283ca3b4201d879 2023-09-18   0.07624154207666   99301   0x7724208958923fbc99535b6e73a26fc390948c770a2ef4ec767c543df28d5200 // 
46 0x2f925597b242f283cbada91667831555a76f635b 2023-09-18   0.076639947454424   99301   0x6d0ed7f300c0aba8d8cb3898b3e77eb1d2b8912e03f4cfea1f77a03569cc7a7b // 
47 0x1f1c599472d1b0431a89df59740d74f0f87ee4f6 2023-09-18   0.076140144725936   99301   0x3654dead11ea23538d884c9ec81d1db392968b462a773298641823872ad07e6b // 
48 0xd888fbbbb591a07a7015ace5509aca2483733c76 2023-09-18   0.075740355966128   99301   0x6e19c963a16cb9c723cdc9d71e95cdd400e71bcfda158a8ff394a1a08bed076c // 
49 0x596c0c491f981565d47a0ad8a611f792ffda8aab 2023-09-18   0.07644112807988   99301   0xb56b18c9f10dab58d831a699fef11c8c02694065367d791d234b74982eaebd4c // 
50 0x5bcf034913b5a9bb141949f22e6bdb5f4572b993 2023-09-18   0.076641526700724   99301   0xb9e9be9de2833a2822f18540f6c57ac4c7f3e46f5efd02d1beb79c7096a89d6d // 
51 0x7d4ec5d458e5e180561b19a4dbf0cd17558efaed 2023-09-18   0.076541421171364   99301   0x433ce0c244bb245bc1546ae93b6aad00970cd0aa116c0f66cf00ec11d7239ddc // 
52 0x05128e9af115ba970cd5dd34fe3c1fa8df517f61 2023-09-18   0.07704011524988   99301   0x3754a43fb8ae296c14edd96d0dad5c9d8e4df092c5870a6226c1f95617fbf643 // 
53 0x68dc2377ae20652d392611ca815633cc87842729 2023-09-18   0.075839868607596   99301   0x0850d258d3245a897931c86759f30cd5084a40614367468b8e0530626f686a71 // 
54 0x90ebb93dbc3a26f7793fc60af766afce63622d62 2023-09-18   0.076640858079012   99301   0x6d0d71735808c9d1a53c747d5b6131a7a359e565117ed88dc1370a183a7a09d3 // 
55 0xae1bc91f91496fbc1cf0f04a958953cd5aa51241 2023-09-18   0.076640146763468   99301   0xc199410398842d027b18f36b80456e005a86fba3c0bf238e91a3abcbfe1c1b45 // 
56 0x9af4f5151957deecceb035c9ca2aeb4ed8a0ec0e 2023-09-18   0.076941053505488   99301   0xa94e1a8b063152a6850d76b9d7c1c71bbf22cd309ca7afe60ed2bb593ca961f9 // 
57 0x94eb520127de2a323b4d89f46ca85c1ca6f3ebb4 2023-09-18   0.076840356596616   99301   0x54cb16a69c0bd78b622e65f35530b309a70fcd73b2e8a22ccb1c9053fedbe2fc // 
58 0xcbacbb3dac498e1310b2732cf7728d657d622ac8 2023-09-18   0.076640448222592   99283   0xa468bde259e7be3f62e096d1267068588d3250295d2c9c0922fc790f6f655dcd // 
59 0xacae7c1f36428a37bb002d1418ae7449b5297ed4 2023-09-18   0.076366059363832   99283   0xc124c31445e45fb96fa3f8af6bcfd27c87b4bcde5c37802d5c7e44aeeb35530d // 
60 0x636a6b9cb77040a9fc263a11ff911402a267c5e7 2023-09-18   0.076637264956308   99301   0x890beef93289c8c6d6a69ba64d7b51cc7ad6efe663664c6a4a8ba66cc7d5436e // 
61 0x7f91cf010175f8416745a8c1fffe6a86d7c87869 2023-09-18   0.075740484381948   99301   0x68e359391f5f25796f33343468284e51d86388f3aeaea242791373d1c11b090f // 
62 0x35aa41a273a78bf08675549db514890d83e36b81 2023-09-18   0.076268271474228   99301   0x417f70e446e26eb261a2bab88a61b6002459bfa5b1865787e18eef890a8430b4 // 
63 0x2b47e0ca4f24e40d029464fa7c25e7d800eef55c 
64 0x39972ec19c65ef3995a766fd6c742c10073b7705 2023-09-18   0.076537894966248   99301   0xf5876b0428f21f78e33d7fe53d6abd07f3c32ccebdc955c7cde2cf01f625e9f2 // 
65 0x1af3469ee64be477283fd7bf46a63afac07bf88d 2023-09-18   0.076240082033508   99301   0xd55036657084199829cc48f8f145db9d24551f4dbf3317b7323f61ee7382902e // 
66 0x4846002d1803b522f211c57553e1bd69fa6b31cd 2023-09-18   0.0767390808457   99283   0x4ab5eb667c965749abd5fa166d2e1766d6674585709e1544d736bb67bbef09f6 // 
67 0x1bfece0f8c8718ed9edbf2938d757c0a2d039433 
68 0xf3d3cdcb12718fc8860a3b58e577630521317a1a 
69 0xc1429057be5d4db24c8dc51eb46a738d55617b56 
70 0x6c9594226ad2accf79ac087c36bdd63d21640fac 
71 0xfc19d702478a3e1df8f013700d25ae3ce9a51f5b 2023-09-18   0.076241118276576   99283   0x081a14d7d974d8c291a3c378bb01eab9e921a98a96b18ff4be0a738f7edad97d // 
72 0x7082486b93e80996e59edcccd7f8601f7a16a535 2023-09-18   0.076841357775096   99301   0x707d84e19d17c5d6b77064f5e5036f527fd945bf71d3a79e9c9506a6a3d98808 // 
73 0xe456ec754b04d83acc99ef6c39c13076f3c7a6f7 2023-09-18   0.075941342313088   99283   0x5815592c728c6bdf2910094ebb4ed78b323fdc57969876c47af9913792d50544 // 
74 0x1d6f9dd6fe36a8c976bfa53d7e27eae71a03a63f 
75 0x43b9fd8864102db4b2aa16562a522b31cf263ff6 
76 0x284a3e94f575386708af4ee62862735f28c1be19 
77 0x0f5c0f6e2c42d65abf7fb38cfc171ff6207b30f9 
78 0xf78f351b04c1bf2857feb0d0f623de04efc7076a 
79 0xf3d1c44af06cf95a20f66ef1537b7f5cd227e6e5 
80 0xbbc4b8a14b76f4f9cbab5b1d2049acdf11aa3571 2023-09-18   0.076240034678856   99301   0xc48a25093774ef5d85a06c805173872650694d59029de00c4fe03714fe95803d // 
81 0xd408696815cb9b4974e016430812fb444a7cbfc1 2023-09-18   0.076141342313088   99283   0x7bef8948f7043d6e4e3be560291c40c64bb6ad39a403a684ba5bd2e98376e539 // 
82 0x8c29cdadfc797c775fd9ccb3cbe8856cc3b29aaf 2023-09-18   0.07624090432872   99301   0x6b2263cec0c43771edaf37f12169b296192194fd1a9bacb998d7bf5aa48f4d1d // 
83 0xa3ddae122e6287464207cc0afb68c605df9ffe9e 2023-09-18   0.07704090432872   99301   0x5c78d7dbffcd8a8dabc8cdfc77e4d877df273feb3a9645167c10f7924f53b89e // 
84 0xcba70cf05d532cce6efa87e21278b271c465cb4a 
85 0x7297eca78a3f2bbdbf98ce7ef51189a857342bd9 2023-09-18   0.076638483177208   99301   0xb16996b881a39df622aa61d46a2fd25d507104bda12c9550ad0cd4f52e960da9 // 
86 0x84e6b0a97b839d454f55d1428d1e88285feb7e8d 2023-09-18   0.075939103915964   99301   0x875f71523d3cca9097df9834b2b5c0f7480b9678ffd6e434cf4574f4000ce9c4 // 
87 0x9298db55504f95dcec4b60349a909e6cab006f7a 
88 0xdbfdd24f859439e07235b45d529bbf789af2abe4 2023-09-18   0.07625391544818   99301   0x7f802119df20e00661b5910262dc452ae64f8ccf74d24d6c6a03ae8f5676a872 // 
89 0x5a352432131a5ae6b96ea333af12ee8ace539efb 2023-09-18   0.07665696082394   99301   0x3efc47bc79ce9ffdbd3577cf0e0b1d9618e3d58a6e7f7682d766df099d4ca431 // 
90 0x45765be0a3a4eebc53643c3e9250fa7184af40bb 2023-09-18   0.076938449302364   99301   0x32b86f398d6b49ab1d4c08a0febdf244df7f711bf289756535974d53b7339a4c // 
91 0x735cd4ef75dcbb99b0659c32f5c8083eeee4a77b 2023-09-18   0.07584090432872   99301   0x7ec3bf719d3607f6103269fd2f0898aac0b75996a5d1fdd39b3f79d987c10c89 // 
92 0x7e7250be6a32ed140e1361e939c1025fe66623e2 2023-09-18   0.07644090432872   99301   0xf6bd59acb6dd2c063bb7a7e6217c151d6b46d973bc8196405631798487f6e79f // 
93 0x488dc7f7064a9ebb9df1de923da729464a18f416 2023-09-18   0.07674090432872   99301   0x51d599d4ef046b988f5fb6570a3933a5c9d4eaa564147175525fa5d4cf53533a // 
94 0x41f8e3ba433cbe955ad07397167f164aae2db00d 2023-09-18   0.076267223445868   99301   0xc199416f786e46ef6cbaef0f58b912a8e6bb6125a2910ad80a5c4d73a5b86041 // 
95 0xab768df3aac7c76b07b8c37d6e94f4385c11aa50 2023-09-18   0.076141000406696   99301   0xc8b690cb6ca93141ef7b1ec03ea84d70910909050c13d515bf7fa53429cf8ca4 // 
96 0x7384d84ae8023742f956d1152b9c2906fcf2061b 2023-09-18   0.07683993505306   99301   0x5972ebe993407e0ef0900c07afb06c033d0d985d2ea31897b30cc6bf53099b81 // 
97 0x7b9c4b6c80dc278c8b6a7ddb957d9c07a52f5bda 2023-09-18   0.075836521206248   99283   0x0d196dbec302076c1d1c8229408e2e52d39be945f08f30b3116666a4beb365ee // 
98 0x48269d4b02070d2ec55597d587b2ab2c71bf2f23 2023-09-18   0.076639208555772   99301   0x31ba51e1b15e80aa916bd7b614e01d0fa7fc69c4c4274c524fabe438959c3cdf // 
99 0x51266e8454f4c34ac5fd7efa657de4f67fc198d7 2023-09-18   0.075940637904504   99301   0xf51a3ea68595c384e364b96a7b5b71eda508c6ac5cd692b9590202b5e1946587 // 
100 0x5ce2498c8004dd1c7c4f3387893cc22d15a923c7 
101 0x2b748d41060de40ee8f1053a89ff4f4bf6bb40c4 2023-09-18   0.07633973217224   99301   0x5c8e86e6038d65d0f507b71040e309f3b740bbf58564383fd64c411fce529ef4 // 
102 0x5f17612758d0a0f76646797a019bd8e1babb67c5 2023-09-18   0.07613940258326   99301   0xa5595a8cd405c868b39a3b2edc0a04d63b04e69a5f80e830a87d62bea826aae4 // 
103 0x3d463e1a2533a8cd24682c8070da980c6c09f4e1 2023-09-18   0.076940082033508   99301   0x47006c21a2b8a257144eeceb3090e5636b171a3e88d04ce13bebec97b5ee9920 // 
104 0x6e96ca94449204a9f3098299a63086c2cb050c51 2023-09-18   0.076536157194404   99301   0x9f1d562b103f27ebfd2fd800bc2487dcc59bfe51468c273005657922b2a65b03 // 
105 0x22ffe947d4e88de7d56706b243e5206987868220 2023-09-18   0.076736685036668   99301   0x025de4d1650e6cfbc6c054ef41f4844342a4bd69da63db3170f0244559ee99a7 // 
106 0x9c1805b485255aa50a988e607ebfa0245a3f8d32 2023-09-18   0.076034888676716   99301   0x10ba7be081adba8e423b35b6d4c86a5c2a5dfced280cdb7cce6c090ccd08b44f // 
107 0x28274f670827dde8ed103854e753b3219f64eb93 
108 0x0c97b99bece0dae7e07848160b0ced5a42dbda14 
109 0xf9e05010df1b9ea59ddac4c5e17b7a7b9b65201f 
110 0x5c3b787e80aa3a358bdc848e193cd9a744f397bb 
111 0xb033c98e75b5fefb916965e29b4c2cf3bb78ed45 
112 0x6e270fc07f469651423166c4c3697edce4f232cf 
113 0x6bdaafa7b66f81fbe952ff5abceec8c3132cfeb6 2023-09-18   0.07625696082394   99301   0xfb78f9c0937351a0e91a087b6a8f42107bc415562b3414e7df683e82d67e653a // 
114 0xdd5565917e56edaf9fd7b242b9242367051163d7 2023-09-18   0.075840193439932   99301   0x6e0ba727b212a8e7b8449f53f0080823f6ed4b025d23c91865d310dd15c152e2 // 
115 0xfcf21167428857a2d3ec34a2365148c12d774fe1 
116 0x427b7b51c549e391714b7958f437bb51865ebcb9 
117 0xc9a9c8d9c12b775bcd79f172c9827cd77e1fd2d4 2023-09-18   0.076041294108952   99301   0x586f5e3547e2506b4b60682c3281df451a0e2fc8d2f741ce4a94166e51f40bf2 // 
118 0x3aa0ba56a9f5e9cfa286d0de5955bb647877e80b 2023-09-18   0.0759667817197   99301   0xb80c00bc83f24f4acf78da4c2fcbd9fb5a34fb0eda825e65ac34c6f83365db80 // 
119 0x2d405e95db99c70986e826208a86fc1b7ac9cc44 2023-09-18   0.07574109487326   99301   0x248fa435603c7a2a6ef6a282c02d6dd24efabf364501e0a18f74a60bfaedc365 // 
120 0xed85dbc2c59a1cfa5af6e3ad3d75ddb03f0a2b09 2023-09-18   0.07664090432872   99301   0x2319d9abb43971012020a513cfa7c9617ae8da77644cdef320e5e88109e39453 // 
121 0x88c8af64e4198af892d0634415e48158585ca667 
122 0xebb8e715c4c4d338a3c08872c252db06ff6a59c5 
```





</details>
