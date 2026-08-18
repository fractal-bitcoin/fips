# FIP\-102 Community FAQ

## FIP\-102 Community FAQ

Thank you to everyone who has reviewed FIP\-102 and shared questions, concerns, and suggestions on Github and during our Community AMA\. We have read and thought over every piece of feedback meticulously\.  

The discussion has raised important considerations around Fractal’s emission structure, miner and indexer incentives, Bitcoin\-mainnet distribution, and the potential role of existing infrastructure\. This FAQ addresses the main questions raised so far\. 

Not every suggestion can necessarily be adopted, but all feedback will be carefully considered and will contribute to our strategy and implementation going forward\. 

### Does FIP\-102 increase FB’s supply?

No\. FIP\-102 does not increase FB’s maximum supply or create a separate supply on Bitcoin mainnet\.

It changes where part of the post\-halving emission budget is distributed\. At full rollout, the combined emission path continues to follow the original progression of 25 → 12\.5 → 6\.25 FB, while the budget is divided between Fractal and Bitcoin mainnet\.

### Why bring the two Fractal\-side reward reductions together?

Introducing Bitcoin\-mainnet distribution without reducing the corresponding Fractal\-side reward would create additional issuance\.

For example, retaining 12\.5 FB on Fractal while adding another 6\.25 FB for Bitcoin mainnet would produce a combined budget of 18\.75 FB, exceeding the original post\-halving emission budget\.

FIP\-102 instead proposes bringing forward the second Fractal\-side reduction and redirecting the corresponding 6\.25 FB budget to Bitcoin mainnet\. This allows FB to reach Bitcoin users without increasing the combined target emission budget\.

### Why does Fractal need to update its distribution model?

Fractal’s original tokenomics were designed for the network’s initial mainnet launch\. Since then, the ecosystem and broader market have evolved\.

FIP\-101 began expanding FB distribution beyond traditional mining by introducing Index Mining\. FIP\-102 continues this evolution by proposing a native distribution path for Bitcoin\-mainnet users\.

The objective is to broaden participation, support new uses of FB, and create a more sustainable long\-term distribution structure across both Fractal and Bitcoin mainnet\.

### Could the lower Fractal reward push miners or indexers away?

This is a valid concern, and the impact on miners, indexers, stakers, and other existing participants should not be understated\.

However, a larger nominal reward does not necessarily guarantee sustainable participation\. Mining and infrastructure operators ultimately depend on whether the economic value of their rewards can justify their operating costs\.

FIP\-102 seeks to improve the long term value and utility of FB, which will benefit the miners despite its short\-term impacts\. Merged Mining, Permissionless Mining, and Index Mining would all remain active after FIP\-102, and the existing 1:1:1 allocation among these three Fractal infrastructure roles would not change\.

### Why will Bitcoin\-mainnet distribution not begin immediately at block 2,100,000?

The Fractal\-side reward change requires a coordinated consensus upgrade at a defined block height\. Bitcoin\-mainnet distribution, however, requires separate infrastructure, development, testing, and operational preparation\.

FIP\-102 establishes the consensus change and emission\-allocation framework that makes Bitcoin\-mainnet distribution possible\. It does not require the Bitcoin\-mainnet distribution mechanism to become operational at the same moment that the Fractal\-side reward change takes effect\.

After FIP\-102 is activated at block 2,100,000, the new emission structure will need to be observed for a period of time to ensure that the transition is operating safely and as intended\. Additional development and testing on the Bitcoin\-mainnet side will also be required before distribution can begin\.

The Bitcoin\-mainnet distribution mechanism is therefore expected to launch after an implementation and research period of approximately three to six months, with a target launch in Q1 2027\.

### Why was the timeline for Bitcoin mainnet distribution \(FIP\-103\) changed to a longer implementation period?

The earlier concept assumed that Bitcoin\-mainnet distribution would begin after FIP\-102 activation and progressively reach its target rate over approximately three months\.

Following further consideration, the implementation plan has been revised\. The priority is now to ensure that FIP\-102’s consensus and emission changes are activated smoothly, observed in operation, and supported by sufficient Bitcoin\-mainnet infrastructure before distribution begins\.

This approach provides additional time for research, development, testing, security review, and operational preparation\. It also separates the activation of the emission framework from the launch of the user\-facing Bitcoin\-mainnet distribution mechanism\.

The revised timeline does not change the intended target allocation\. It changes the order and timing of implementation so that Bitcoin\-mainnet distribution can be introduced with stronger safety and operational integrity\.

The current expectation is for FIP\-103 research and development to continue for approximately three to six months after FIP\-102 activation, with Bitcoin\-mainnet distribution targeted for launch in Q1 2027\.

### Could existing FIP\-101 indexers participate in Bitcoin\-mainnet distribution?

Community members have suggested that FIP\-101’s standardized, lightweight indexing infrastructure could potentially support parts of the Bitcoin\-mainnet distribution mechanism\.

This is a constructive and technically relevant suggestion\. However, FIP\-102 does not assign a new role to existing indexers, and the architecture of FIP\-103 has not yet been finalized\.

Whether FIP\-101 indexers or related decentralized indexing infrastructure could participate meaningfully is one of the possibilities that may be explored during the design of FIP\-103\.

### Does this make Fractal’s future monetary policy less predictable?

FIP\-102 is a significant proposed adjustment, and this is precisely why it has been presented through an open community review process\.

Under the proposal, future halving milestones would remain defined in advance, with the Fractal and Bitcoin\-mainnet allocations reducing proportionally\. The intention is to update the current distribution structure while maintaining a clear and predictable long\-term emission path\.

### Is FIP\-102 already final?

Yes\. FIP\-102 has been finalized as a proposal\.

However, the implementation process, rollout details, and the development of Bitcoin\-mainnet distribution will remain subject to community review and feedback, particularly through the preparation of FIP\-103\.

This does not mean that every proposed change or suggestion will automatically be adopted\. However, every piece of feedback will be seriously considered because it helps identify concerns, clarify trade\-offs, improve the implementation, and strengthen the final system\.

Thank you again to everyone who has contributed to the discussion\. Constructive feedback—whether supportive, critical, or technical—is an important part of improving Fractal’s long\-term design\.



