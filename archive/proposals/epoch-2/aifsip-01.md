---
description: >-
  Proposal by the governance CELL to adopt the initial DAO state, multisig safe,
  voting space, discussion forum and membership badges for ongoing use as AIFS
  core infrastructure.
---

# AIFSIP-01: Adopt Initial Governance State

🗣️ [Commonwealth](https://commonwealth.im/all-in-for-sport/discussion/10346-aifsip01-adopt-initial-governance-state)\
⚡ [Snapshot](https://snapshot.org/#/allinforsport.eth/proposal/0xf370703e0a4a0aec0921f9cb1335dacbfd0a78877afb22875a992de32893947b)

**Submitted:** Mar 16, 2023\
**Result:** Passed ✅

Proposed by: yeoro.eth, ananth.eth, rathermercurial.eth

### Summary

As a result of [#GEN-23 Proposal 03 - Implement a simple starting governance structure for AIFS](https://app.clarity.so/allinforsport/work/GEN-23), the Governance CELL has designed and deployed a simple ecosystem of governance tooling accompanied by a minimum-viable set of policies, standards and best practices. This proposal seeks approval to adopt and ratify these tools as All In For Sport's initial community governance solution.

### Details

In order to achieve the AIFS's purpose, we are implementing a two-house governance design, the first stage of which is the establishment of this formal (but minimum viable) Community Governance model.

This will take our current informal weekly meetings and proposals via telegram and replace them with a more robust and scalable approach that is based on community development of proposals, approval via on-chain voting and then the execution of activities by operational governance.

As part of this, AIFS is adopting a [UNA structure](https://state.allinforsport.org/org/overview). This will give us legitimate legal status and create corresponding liability protections for members of the AIFS community. Approval of this proposal will count as the official decision, made by the AIFS community, to adopt the operating agreement (TUNAA, Trustless Unincorporated Nonprofit Association Agreement. You can read more about it [here](https://docs.wrappr.wtf/how-to/non-profit/#non-profit)) and to abide by the requirements within it.

This proposal will also provide for token/badging infrastructure to recognize contributions to AIFS and reward contributors with governance rights in the network.

Finally, this proposal will provide a platform upon which to develop the Operational Governance side of AIFS. With the community able to develop and safeguard the purpose of AIFS, operational CELLS can start to build out its execution capabilities.

To achieve the above, we propose the adoption of the following as All In For Sport's community governance infrastructure:

* A [pre-configured](https://state.allinforsport.org/archive/approvals/mainnet) "2 of 3" Safe multisig contract ([allinforsport.eth](https://etherscan.io/address/0x8FA66238EB372E348AA4071aA8a52B7565384D75)) for custody of All In For Sport's treasury. This safe will be used by the following signers to execute transactions approved by the DAO:

Shannon Lanigan 0x97f752e1d5F64CA932c32dBfF82f4c92710beE54

Heenal Rajaini 0x3C41f941098681bfDb14ed423709CC7C29c1e5e6

Rowan Yeoman 0x66Ab0BC088212195b0d9e9FEB12F3f93fF6f8fF1

* A [Snapshot voting space](https://snapshot.org/#/allinforsport.eth) which allows All In For Sport badge holders to submit and vote on proposals for approval by the DAO. The accompanying proposal standard can be found [here](https://state.allinforsport.org/policies/proposals).
* A [Commonwealth discussion forum ](https://discuss.allinforsport.org/)for formal discussion of proposals and other matters of the DAO.
* A [Badger NFT contract](https://polygonscan.com/address/0xeed76f3d0de104827357b37aa2f0ce3701e4ae28) to issue non-transferrable membership badges for use with governance and access control tooling.
* The [DAO State Repository](https://state.allinforsport.org/), which contains all DAO policies, member agreements and governance standards, along with archives for proposal, transaction and state change histories.

### Proposed Outcome

If this proposal passes, the following will occur:

* The [DAO state document](https://state.allinforsport.org/) (including the [operating agreement](https://state.allinforsport.org/policies/membership/operating-agreement)) will be ratified as official All In For Sport policy.
* The Governance CELL will push an update to the [AIFS GitHub account](https://github.com/All-In-For-Sport) containing the contents of the [DAO state repository](https://state.allinforsport.org/). The DAO state will remain available on GitBook at [state.allinforsport.org](https://state.allinforsport.org/).
* The proposed multisigners will be added as owners of the pre-configured multisig safe ([allinforsport.eth](https://etherscan.io/address/0x8FA66238EB372E348AA4071aA8a52B7565384D75)).
* A [Ricardian NFT ](https://www.wrappr.wtf/137/0xe22ebfbd3e6609a9550a86545e37af7de1ee688b)will be minted to the primary multisig address on Polygon, containing the Operating Agreement as seen in the [DAO state repository](https://state.allinforsport.org/policies/membership/operating-agreement).
* The [voting space ](https://snapshot.org/#/allinforsport.eth)and [discussion forum](https://discuss.allinforsport.org/) will be adopted as official resources for collective decision-making.
* The Governance CELL will work to publish governance guides, transparency records and other documentation needed to serve the needs of the DAO.

### 🗳️ Voting Result

**Votes:** 6 Yes, 1 Abstain\
**Result:** Passed

### 🏗️ Governance State Changes

* Removal of the "Not official AIFS material" callout from the top-level readme file.
* Addition of example proposal (AISFIP-01) to the Proposal Standards page.
* Removal of callout from State Update Policy page.
* Removal of callout from Treasury Approvals page.
* Addition of Initial Commit entry to DAO State Change log.
* Addition of AISFIP-01 to DAO State archive
* Replace Operating Agreement boilerplate with canonical Ricardian contract. (pending)\
