
# FIP\-102: Native FB on Bitcoin Mainnet

**Version:** 0\.20
**Title:** Native FB on Bitcoin Mainnet
**Author:** Fractal Team
**Status:** Complete
**Type**: Consensus \(Hard Fork\)
**Created:** 2026\-08\-18

---

## Abstract

FIP\-102 proposes to bring FB natively to Bitcoin mainnet, expanding its distribution to a wider Bitcoin audience\.

At Fractal block 2,100,000, the first scheduled halving will reduce the Fractal block reward from 25 FB to 12\.5 FB\. FIP\-102 will simultaneously bring forward the second Fractal halving, reducing that reward again to 6\.25 FB\. Rather than allowing the matching 6\.25 FB emission budget to cease emission, FIP\-102 will direct it to Bitcoin mainnet\. Bitcoin\-mainnet distribution will then roll out progressively over approximately three months, ultimately reaching a target rate equivalent to 6\.25 FB per Fractal block\. This rollout changes the timing of distribution, not the maximum FB supply or the allocation established by this proposal\.

---

## 1\. Proposal at a Glance

FIP\-102 makes five principal changes:

1. **Bring FB natively to Bitcoin mainnet\.**
Enable FB to be distributed natively on Bitcoin mainnet so Bitcoin users and applications can obtain and use it directly\.

2. **Redirect the second\-halving reduction to Bitcoin mainnet and advance every subsequent halving\.**
Activate the first scheduled halving and the brought\-forward second Fractal halving together at block 2,100,000\. The Fractal block reward will fall from 25 FB to 12\.5 FB and then to 6\.25 FB, while the matching 6\.25 FB emission budget that would otherwise cease emission under the second halving will instead be directed to Bitcoin\-mainnet distribution\. Every subsequent Fractal block\-reward level will also be advanced by one 2,100,000\-block interval\.

3. **Preserve equal Fractal\-side distribution\.**
Keep the Fractal\-side allocation equally divided among Merged Mining, Permissionless Mining, and Index Mining\.

4. **Expand distribution beyond mining and staking\.**
Direct the Bitcoin\-mainnet allocation toward eligible on\-chain interactions, user activity, and user participation\.

5. **Enable supply\-neutral 1:1 conversion\.**
Provide a 1:1 conversion path between FB on Fractal and FB on Bitcoin mainnet without increasing the combined FB supply\.

The full target allocation established by FIP\-102 is shown below\. The Fractal\-side allocation takes effect at block 2,100,000\. Distribution to Bitcoin\-mainnet users will be introduced progressively over approximately three months, as described in Section 7\.

|Distribution path|Proportion of full target emission budget|Average FB budget per Fractal block equivalent|
|---|---|---|
|Merged Mining|1/6|Approximately 2\.0833 FB|
|Permissionless Mining|1/6|Approximately 2\.0833 FB|
|Index Mining|1/6|Approximately 2\.0833 FB|
|Bitcoin mainnet distribution|1/2|6\.25 FB|
|**Combined target emission budget**|**1**|**12\.5 FB**|

The amounts shown for the three Fractal mechanisms are averages across all Fractal blocks\. The actual reward on an eligible Fractal block will be 6\.25 FB, with one block in each three\-block cycle allocated to each mechanism\. The Bitcoin\-mainnet amount is the full target budget after the progressive rollout; it does not imply that the full amount will be distributed immediately at activation\.

---

## 2\. Motivation

### 2\.1 Bring FB to a Wider Bitcoin Audience

Fractal was built as an extension of Bitcoin\. Bringing FB natively to Bitcoin mainnet is therefore a natural next step in expanding the Fractal ecosystem\.

Native distribution on Bitcoin will allow active Bitcoin users to obtain and use FB directly on the network where they already hold assets and participate on\-chain\. It will also give Bitcoin\-native applications a direct path to integrate FB, creating more ways for the token to be discovered, distributed, and used\.

Reaching a wider Bitcoin audience can broaden FB adoption, deepen its utility, and strengthen its role across the Bitcoin ecosystem\. As more users and applications interact with FB on Bitcoin mainnet, that activity can create new entry points into Fractal and expand the network’s overall reach\. Because Fractal extends Bitcoin, connecting FB more closely with Bitcoin naturally benefits both the token and the wider Fractal ecosystem\.

This is the central purpose of FIP\-102\. The proposed emission changes provide the foundation for bringing FB to Bitcoin mainnet and opening the next stage of its adoption\.

### 2\.2 Continue the Evolution of Fractal Tokenomics

FIP\-102 also continues a direction already established by FIP\-101\.

Fractal’s original token distribution was based entirely on Proof\-of\-Work mining\. FIP\-101 marked an important evolution by introducing Index Mining, reallocating Fractal block rewards across three mechanisms, and creating an incentive layer for decentralized data infrastructure\. It also gave users a new way to participate in FB distribution through staking\.

FIP\-102 takes the next step\. Mining and Index Mining remain fundamental to Fractal, but they will no longer be the only paths through which new FB reaches participants\. By introducing a Bitcoin\-mainnet allocation linked to eligible on\-chain activity, FB distribution becomes broader, more diverse, and more accessible\.

The progression is clear: from Proof\-of\-Work mining alone, to a model that also includes Index Mining and staking, and now to one that reaches Bitcoin\-mainnet users through direct participation\. This evolution allows FB emissions to support not only the infrastructure that secures and serves Fractal, but also the user activity that can expand the ecosystem around it\.

### 2\.3 Encourage Participation on Bitcoin Mainnet

The Bitcoin\-mainnet allocation will be directed toward eligible on\-chain interactions, tying FB distribution to user activity and participation on Bitcoin\.

The purpose is to make FB broadly obtainable through practical forms of participation that most users can access, while encouraging more users to engage with Bitcoin\-native applications and activity\. FIP\-102 establishes this direction and the emission budget that supports it\. The eligible interactions, distribution rules, and implementation details will be defined separately in FIP\-103\.

---

## 3\. Expected Impact

### FB and the Fractal Ecosystem

The most important expected impact is a broader foundation for FB adoption\. Native distribution on Bitcoin mainnet should make FB easier for Bitcoin users to discover, obtain, and use, while creating new opportunities for Bitcoin\-native applications to integrate the token\. Because Fractal extends Bitcoin, a stronger connection between FB and Bitcoin\-mainnet activity should also expand the reach and relevance of the Fractal ecosystem\.

### Miners, Indexers, and Stakers

From block 2,100,000, each existing Fractal distribution pool will receive half of the amount it would have received after the first scheduled halving alone\.

Before the halving, each mechanism receives an average of approximately 8\.3333 FB per Fractal block\. After FIP\-102 activation, each will receive an average of approximately 2\.0833 FB per Fractal block\. This is a 75% reduction from the pre\-halving level\. At the full target allocation, each mechanism represents one sixth of the combined 12\.5 FB emission budget\. Actual participant rewards will continue to depend on network participation and mechanism\-specific factors such as effective stake and commission\.

### Bitcoin\-Mainnet Users

Bitcoin users will gain a direct and broadly accessible path to obtain FB through eligible on\-chain participation\. This is intended to bring FB to users who may not previously have interacted with Fractal and give them a practical entry point into the wider Fractal ecosystem\.

### FB Holders and Developers

FB will be available across two connected environments under one emission framework\. Holders will have access to 1:1 conversion between FB on Fractal and FB on Bitcoin mainnet, while developers will be able to explore new Bitcoin\-native integrations and use cases\.

---

## 4\. Tokenomics

### 4\.1 Emissions Before Block 2,100,000

Before block 2,100,000, each Fractal block emits 25 FB\.

Fractal blocks are allocated equally among:

- Merged Mining;

- Permissionless Mining; and

- Index Mining\.

This equality is implemented through the block sequence: across each three\-block cycle, one block is allocated to each mechanism\. Each mechanism therefore receives one 25 FB block reward per three\-block cycle\. The ratio is 1:1:1\.

### 4\.2 The First Scheduled Halving

At block 2,100,000, the first scheduled halving takes place as originally planned\.

This reduces the Fractal block reward from 25 FB to 12\.5 FB\. If no additional change were made, the three mechanisms would continue to alternate in the same 1:1:1 ratio, with each eligible block carrying a 12\.5 FB reward\.

### 4\.3 Bringing Forward the Second Halving

Under the original schedule, the second halving would occur at block 4,200,000 and reduce the Fractal block reward from 12\.5 FB to 6\.25 FB\.

FIP\-102 brings that second Fractal block\-reward halving forward to block 2,100,000, so the first and second Fractal halvings activate at the same milestone:

- First scheduled halving: 25 FB → 12\.5 FB per Fractal block\.

- Brought\-forward second Fractal halving: 12\.5 FB → 6\.25 FB per Fractal block\.

Under a conventional second halving, the future emission rate would fall from 12\.5 FB to 6\.25 FB per block, and the other 6\.25 FB would no longer be emitted from that point onward\.

FIP\-102 changes the destination of that second\-halving reduction\. The Fractal block reward still falls from 12\.5 FB to 6\.25 FB, but the other 6\.25 FB does not disappear from the future emission schedule\. Instead, an equivalent 6\.25 FB\-per\-Fractal\-block emission budget is redirected to Bitcoin mainnet\.

The second halving therefore reduces Fractal\-side emissions without removing the matching Bitcoin\-mainnet allocation from the approved FB emission budget\. At full rollout, the combined target budget remains at the 12\.5 FB\-per\-Fractal\-block equivalent established by the first scheduled halving:

- 6\.25 FB through Fractal block rewards; and

- An equivalent 6\.25 FB through Bitcoin\-mainnet distribution\.

The Bitcoin\-mainnet figure is an accounting rate tied to the Fractal block cadence\. It does not mean that 6\.25 FB is distributed for every Bitcoin block\. The Fractal reward changes immediately at block 2,100,000, while actual distribution on Bitcoin mainnet will be introduced progressively over approximately three months\. This transition changes when the Bitcoin\-mainnet allocation enters circulation; it does not increase or reduce the maximum FB supply\.

### 4\.4 Distribution Example

|Stage|Fractal reward per block|Bitcoin\-mainnet target budget per Fractal block equivalent|Combined target emission budget|
|---|---|---|---|
|Before block 2,100,000|25 FB|0 FB|25 FB|
|First scheduled halving only|12\.5 FB|0 FB|12\.5 FB|
|FIP\-102 at full rollout|6\.25 FB|6\.25 FB|12\.5 FB|

At block 2,100,000, the 6\.25 FB Fractal reward takes effect immediately\. The table shows the full Bitcoin\-mainnet target after the progressive rollout, rather than the amount necessarily distributed at the activation block\.

Within the 6\.25 FB Fractal block reward, the 1:1:1 block sequence remains unchanged\. Across each three\-block cycle, Merged Mining, Permissionless Mining, and Index Mining each receive one 6\.25 FB block reward\.

Expressed as an average across all Fractal blocks, each mechanism accounts for approximately 2\.0833 FB per block, or one third of the 6\.25 FB Fractal\-side emission rate\. This average should not be confused with the reward paid on an eligible block, which is 6\.25 FB\.

![Image](https://internal-api-drive-stream-sg.larksuite.com/space/api/box/stream/download/authcode/?code=MjJhYTBhYmQxNmFlODU4MDA1ZTNhMDVkNTRjYmE1ZDJfMzRkZDAwOTA2NDllNmExYjZlNWRjNWVkZDRlZGVkMTNfSUQ6NzY3NTI5NzY0Njk0ODM4ODU4NV8xNzg3MDU0ODQ1OjE3ODcxNDEyNDVfVjM)

![Image](https://internal-api-drive-stream-sg.larksuite.com/space/api/box/stream/download/authcode/?code=ZGYzYWIzNzZjOGE1ZTU5YWM5NzQ5YTAxOTk1NzQ3MmNfY2JhYzMzZjlmZDAwZjVjZjI2MWRmY2Q2NzkzODI2ZTBfSUQ6NzY3NTI5NzY0NTYzMTQ3NTQzM18xNzg3MDU0ODQ1OjE3ODcxNDEyNDVfVjM)

### 4\.5 Future Halving Schedule

Bringing the second Fractal halving forward also advances every subsequent Fractal block\-reward level by one 2,100,000\-block interval\.

The first and second Fractal halvings activate together at block 2,100,000\. The next halving then occurs at block 4,200,000, followed by another every 2,100,000 blocks:

|Block milestone|Fractal reward per block|Full Bitcoin\-mainnet target budget per Fractal block equivalent|Combined target emission budget|
|---|---|---|---|
|Before 2,100,000|25 FB|0 FB|25 FB|
|2,100,000|6\.25 FB|6\.25 FB|12\.5 FB|
|4,200,000|3\.125 FB|3\.125 FB|6\.25 FB|
|6,300,000|1\.5625 FB|1\.5625 FB|3\.125 FB|
|8,400,000|0\.78125 FB|0\.78125 FB|1\.5625 FB|

At each later milestone, the full target allocations for both distribution paths halve proportionally\. The Fractal\-side allocation remains equally divided among Merged Mining, Permissionless Mining, and Index Mining\.

This schedule continues every 2,100,000 blocks unless amended through a later FIP\.

---

## 5\. Bitcoin\-Mainnet Distribution

The Bitcoin\-mainnet allocation will be distributed natively through eligible interactions on Bitcoin mainnet\. It will be directed toward user activity and participation and designed to be broadly accessible\.

FIP\-102 establishes the purpose and budget for this distribution\. The eligible interactions and detailed distribution mechanism will be introduced in FIP\-103\.

---

## 6\. FB on Bitcoin Mainnet and 1:1 Conversion

A 1:1 conversion path will be available between FB on Fractal and FB on Bitcoin mainnet\.

The conversion will operate within the existing unified FB supply: it will not create double issuance, a separate token supply, or an additional emission budget\. The implementation and operational details of the conversion will be introduced in FIP\-103\.

---

## 7\. Transition and Execution

### 7\.1 Proposal Release

FIP\-102 is scheduled for publication on August 9, 2026\.

### 7\.2 Community Discussion and Refinement

From August 9 through August 18, 2026, the proposal remained open for community discussion and feedback\. The Fractal Team refined the proposal and its implementation details in response to that feedback, with the aim of finalizing FIP\-102 by August 18\.

### 7\.3 Published the Node Upgrade RC

On August 9, 2026, the Fractal Team published a new node version fractald v0\.4\.0 rc in preparation for the halving and FIP\-102 activation\.

### 7\.4 Finalize FIP\-102

The Fractal Team aims to finalize FIP\-102 on August 18, 2026, following the community discussion and refinement period\.

### 7\.5 Fractal Node Upgrade and Implementation Preparation

FIP\-102 activation requires a Fractal node upgrade in addition to the new indexer release\. The Fractal Team will publish the compatible node release and upgrade instructions during the implementation period\. All existing Fractal node operators should complete the upgrade before block 2,100,000 so that the new block\-reward rules activate consistently across the network\.

Throughout August and until block 2,100,000, the Fractal Team will undertake the development, testing, and operational preparation required for:

- The first scheduled halving;

- The brought\-forward second Fractal block\-reward halving;

- Native FB distribution on Bitcoin mainnet;

- Bitcoin\-mainnet distribution; and

- 1:1 conversion between FB on Fractal and FB on Bitcoin mainnet\.

The detailed Bitcoin\-mainnet distribution and conversion design will be set out in FIP\-103\.

### 7\.6 Activate at Block 2,100,000

Activation is governed by Fractal block height\. Block 2,100,000 is currently estimated to occur around September 9, 2026, but the calendar date may change as block production varies\.

At block 2,100,000:

- The FIP\-102 Fractal network rules activate through the coordinated node upgrade\.

- The first scheduled halving reduces the Fractal block reward from 25 FB to 12\.5 FB\.

- The brought\-forward second Fractal halving reduces the Fractal block reward again from 12\.5 FB to 6\.25 FB\.

- An equivalent target budget of 6\.25 FB per Fractal block is allocated to Bitcoin\-mainnet distribution\. Actual distribution on Bitcoin mainnet will be introduced progressively rather than necessarily beginning at the full rate at this block\.

- The 1:1:1 block allocation among Merged Mining, Permissionless Mining, and Index Mining remains unchanged\.

### 7\.7 Bitcoin\-Mainnet Distribution with FIP\-103

The Fractal block\-reward change will take effect at block 2,100,000, while the Bitcoin mainnet distribution will be progressively launched\. This time gap ensures the halving and the emission allocation change rolls out smoothly before launching on Bitcoin\. 

FIP\-103 will define the Bitcoin\-mainnet distribution framework, including its technical architecture, distribution mechanisms, rollout requirements, and operational processes\. Accordingly, we plan to dedicate approximately three to six months to implementation and research, begin testing in Q4 2026, and target the full rollout of Bitcoin\-mainnet distribution in Q1 2027\.

### 7\.8 Continue the Halving Schedule

The next Fractal block\-reward halving milestone will occur at block 4,200,000\. Later milestones will continue every 2,100,000 blocks, and the full target allocations for both distribution paths will halve proportionally\.

---

## 8\. Goals and Non\-Goals

### Goals

- Bring FB to be distributed natively on Bitcoin mainnet and make it available to a wider Bitcoin audience\.

- Expand FB adoption and support Bitcoin\-native integrations\.

- Continue the tokenomics evolution initiated by FIP\-101\.

- Establish a full target allocation of 50% of the post\-first\-halving emission budget to Fractal and 50% to Bitcoin mainnet, with the Fractal\-side change taking effect at block 2,100,000 and Bitcoin\-mainnet distribution rolling out progressively\.

- Preserve equal distribution among Merged Mining, Permissionless Mining, and Index Mining within the Fractal\-side allocation\.

- Broaden access to FB through eligible Bitcoin\-mainnet participation\.

- Enable supply\-neutral 1:1 conversion between FB on Fractal and FB on Bitcoin mainnet\.

- Introduce Bitcoin\-mainnet distribution progressively after activation\.

### Non\-Goals

FIP\-102 does not:

- Cancel Merged Mining, Permissionless Mining, or Index Mining\.

- Reverse FIP\-101\.

- Move all future FB emissions to Bitcoin mainnet\.

- Create a second, independent FB supply\.

- Increase the combined FB emission budget\.

- Guarantee a particular token price, level of liquidity, adoption outcome, or transaction volume\.

- Define the detailed Bitcoin\-mainnet distribution or conversion mechanisms, which will be introduced in FIP\-103\.

---

## 9\. Summary

FIP\-102 proposes to bring FB natively to Bitcoin mainnet and make it directly available to a wider Bitcoin audience\.

At block 2,100,000, the first scheduled halving will reduce the Fractal block reward from 25 FB to 12\.5 FB\. At the same milestone, FIP\-102 will bring forward the second Fractal block\-reward halving, reducing the Fractal reward again to 6\.25 FB\.

Under a conventional second halving, the future emission rate would fall again from 12\.5 FB to 6\.25 FB, and the other 6\.25 FB would no longer be emitted\. FIP\-102 changes the destination of that second\-halving reduction: the Fractal block reward will still fall to 6\.25 FB, but the matching 6\.25 FB\-per\-Fractal\-block target budget will instead be allocated to eligible interactions and user participation on Bitcoin mainnet\.

From activation:

- Fractal block rewards will be 6\.25 FB per block;

- Bitcoin\-mainnet distribution will have an equivalent 6\.25 FB\-per\-Fractal\-block budget;

- The combined target emission budget will remain 12\.5 FB per Fractal block equivalent—the same total established by the first scheduled halving; and

- The Fractal\-side block sequence will remain equally divided among Merged Mining, Permissionless Mining, and Index Mining\.

The Fractal\-side reward change will activate exactly at block 2,100,000 through a coordinated node upgrade\. Bitcoin\-mainnet distribution will begin after activation and be introduced progressively over approximately three months, reaching the full target rate of 6\.25 FB per Fractal block equivalent once the rollout reaches 100%\. This transition affects distribution timing, not the maximum FB supply or the allocation established by FIP\-102\.

A 1:1 conversion path will also be made available between FB on Fractal and FB on Bitcoin mainnet\. Neither distribution nor conversion will create an additional FB supply or emission budget\. The detailed implementation of both mechanisms will be introduced in FIP\-103\.

By extending FB distribution from mining, Index Mining, and staking to Bitcoin\-mainnet participation, FIP\-102 brings FB closer to the wider Bitcoin ecosystem and creates a broader foundation for the next stage of Fractal’s development\.

---

## Appendix A: Definitions and Accounting Principles

This appendix provides supplementary terminology and accounting principles for interpreting FIP\-102\.

### A\.1 Definitions

- **Pre\-halving emission:** The combined FB emission distributed through Merged Mining, Permissionless Mining, and Index Mining before block 2,100,000\.

- **Combined emission budget:** The maximum combined amount of new FB allocated across Fractal and Bitcoin mainnet during a given emission period\.

- **Fractal\-side distribution:** FB distributed through Merged Mining, Permissionless Mining, and Index Mining on Fractal\.

- **Bitcoin\-mainnet distribution:** FB distributed through eligible interactions on Bitcoin mainnet\.

- **Bitcoin\-mainnet budget equivalent:** The Bitcoin\-mainnet distribution budget expressed against the Fractal block cadence for supply accounting\. A 6\.25 FB\-per\-Fractal\-block equivalent does not mean 6\.25 FB is distributed for every Bitcoin block\.

- **Native FB distribution on Bitcoin mainnet:** FB distributed and used directly on Bitcoin mainnet under the unified FB supply framework\. It does not represent a separate token supply\.

- **1:1 conversion:** A supply\-neutral mechanism through which one FB can move between Fractal and Bitcoin mainnet without creating an additional circulating unit\.

### A\.2 Accounting Principles

1. **One combined emission budget\.**
Fractal\-side and Bitcoin\-mainnet distributions draw from the same FB emission budget\.

2. **No double issuance\.**
A unit allocated or released through one distribution path cannot also be counted or released through another\.

3. **Supply\-neutral conversion\.**
Conversion between FB on Fractal and FB on Bitcoin mainnet does not increase combined FB supply\.

4. **Proportional future halvings\.**
Unless amended by a later FIP, future halving milestones apply proportionally to the full target budgets for both distribution paths, preserving the 50/50 target allocation after the progressive Bitcoin\-mainnet rollout\.

Fractal Team
