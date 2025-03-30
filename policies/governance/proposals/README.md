---
description: >-
  Standards for proposals submitted to All In For Sport governance. Based on the
  MIP standard by ananth.eth
---

# Proposal Standards

The AIFSIP (All In For Sport Improvement Proposal) standard governs the acceptable use and requirements for proposals made to AIFS governance.&#x20;

The purpose of this proposal standard is to ensure that voting members of the DAO have sufficient information to accurately assess incoming governance proposals, participate in constructive debate and cast well-informed votes.

* [Proposal Requirements](./#proposal-requirements)
* [Proposal Formatting](./#proposal-formatting)
* [Proposal Templates](./#proposal-templates)

### Types of Proposals <a href="#types" id="types"></a>

Proposals are request for community consent and can result in an update to the [DAO State document](https://github.com/All-In-For-Sport/governance). Here are some things that proposals can do:

* [Change the way the DAO governs itself](metagovernance.md)

More proposal types can be added by proposing a new standard via a [Governance State Update](metagovernance.md).

## Proposal Requirements <a href="#requirements" id="requirements"></a>

All proposals submitted for vote by the DAO must meet the following requirements.&#x20;

If your proposal does not comply with these requirements, you'll be asked to update your proposal to ensure compliance before submitting for consideration by the DAO.

*   #### Proposal Number (`proposalNumber`)

    The sequential number of your proposal within the AIFS voting space, preceded by "AIFSIP-". If you're unsure what number to use, check the [Proposals page](https://app.clarity.so/allinforsport/tags/7405f102-5cd5-44a8-9da6-765abf322fdc) in Clarity and/or ask the governance team for assistance.
*   #### Title (`proposalTitle`) <a href="#title" id="title"></a>

    The title of your proposal as a level-1 heading. Your title should be descriptive and concise (ie. "Set up a Partnerships Team").
*   #### Description (`proposalDescription`)

    A single sentence summarizing your proposal and its purpose.
*   #### Author (`proposalAuthor`)

    The author or co-authors of your proposal.&#x20;
*   #### Replaces/Amends (`replacesOrAmends)`

    Description (with pretty links) of previous proposals amended or replaced by the current proposal. This can be removed if not relevant to your proposal.
*   #### Summary (`proposalSummary`)

    A short paragraph summarizing your proposal and its intended outcome.
*   #### Body Text (`proposalBody`)

    The full text content of your proposal. Body text must comply with the requirements for your particular [proposal type](./#types-of-proposals).\
    \
    Full proposal templates are available for the following pre-approved proposal types:\
    \- [Governance State Update Proposals](metagovernance.md)
*   #### Proposed Outcome (`proposalOutcome`)

    The intended outcome of voting for each option in the poll, and description of next steps as needed.

## Proposal Formatting <a href="#format" id="format"></a>

Proposals should be formatted in an organized manner in order to provide easy reading and comprehension for your fellow DAO members. It is recommended that you use the following format to present your proposal to DAO governance:

<details>

<summary>Proposal Model</summary>

## proposalNumber: proposalTitle

proposalDescription

Proposed by: proposalAuthor

_replacesOrAmends_

### Summary

proposalSummary

### Details

proposalBody

### Proposed Outcome

proposalOutcome

</details>

<details>

<summary>Example Proposal</summary>

## AIFSIP-01: Adopt Initial Governance State

Proposal by the governance CELL to adopt the [initial DAO state](https://state.allinforsport.org/), [multisig safe](https://etherscan.io/address/0x8FA66238EB372E348AA4071aA8a52B7565384D75), [voting space](https://snapshot.org/#/allinforsport.eth), [discussion forum](https://discuss.allinforsport.org/) and [membership badges](https://polygonscan.com/address/0xeed76f3d0de104827357b37aa2f0ce3701e4ae28) for ongoing use as AIFS core infrastructure.

**Proposed by:** yeoro.eth, ananth.eth, rathermercurial.eth

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

</details>

### Proposal Templates <a href="#templates" id="templates"></a>

Preformatted templates are available for DAO members who wish to author their own proposals. Alternatively, you can contact the governance team for assistance with the creation and submission of your proposal.

Most governance tooling (such as Snapshot, Discourse, Station, etc.) uses Markdown for text input. Markdown can be edited in any text editor, or you can use an advanced editor like [VS Code](https://code.visualstudio.com/) to check for spelling and formatting errors before publication.

{% tabs %}
{% tab title="Markdown" %}
<pre class="language-markdown" data-title="Generic Markdown" data-line-numbers><code class="lang-markdown"># proposalNumber: proposalTitle

proposalDescription

<strong>**Proposed by:** proposalAuthor
</strong>
<strong>*replacesOrAmends*
</strong>
## Summary

proposalSummary

## Details

proposalBody

## Proposed Outcome

proposalOutcome
</code></pre>
{% endtab %}

{% tab title="GitHub" %}
{% code title="GitHub-Flavored Markdown" lineNumbers="true" %}
```markdown
---
description: >-
  proposalDescription
---
# proposalNumber: proposalTitle

Proposed by: proposalAuthor

{% raw %}
{% hint %}*replacesOrAmends*{% endhint %}
{% endraw %}

## Summary

proposalSummary

## Details

proposalBody

##Proposed Outcome

proposalOutcome
```
{% endcode %}
{% endtab %}

{% tab title="Telegram/Discord" %}
<pre class="language-markdown" data-title="Discord-Flavored Markdown" data-line-numbers><code class="lang-markdown">__**proposalNumber: proposalTitle**__
proposalDescription
*Proposed by: proposalAuthor*

<strong>__replacesOrAmends__
</strong>
**Summary**
proposalSummary

**Details**
proposalBody

**Proposed Outcome**
proposalOutcome
</code></pre>
{% endtab %}

{% tab title="Clarity" %}
[**Proposal Development Task Template:**](https://app.clarity.so/allinforsport/template/ac886d40-fa1e-411f-9cb7-03a09d0337a7)\
Use this template to create a new task for proposal development\
[https://app.clarity.so/allinforsport/template/ac886d40-fa1e-411f-9cb7-03a09d0337a7](https://app.clarity.so/allinforsport/template/ac886d40-fa1e-411f-9cb7-03a09d0337a7)

[**Proposal Format Snippet:**](https://app.clarity.so/allinforsport/snippet/f04688b7-084b-4a34-ab9e-7618a47b03dd)\
Use this snippet to populate an existing document with the proposal format\
[https://app.clarity.so/allinforsport/snippet/f04688b7-084b-4a34-ab9e-7618a47b03dd](https://app.clarity.so/allinforsport/snippet/f04688b7-084b-4a34-ab9e-7618a47b03dd)
{% endtab %}
{% endtabs %}

#### How to Use Proposal Templates

You can use these templates to create your own proposals using this format by following the instructions below.

1. Prepare your proposal content using the [requirements](./#proposal-requirements) listed above.
2. Copy the relevant proposal template and paste the into your preferred text editor (VS Code, Notion, Snapshot, Station, etc).
3. Replace the element placeholders (such as `proposalTitle`) with your proposal content.
4. Copy and paste the completed proposal into your destination (Snapshot, Station, Discord, Notion, etc).

You can use [this snippet](https://app.clarity.so/allinforsport/snippet/f04688b7-084b-4a34-ab9e-7618a47b03dd) to draft your proposal in [Clarity](https://app.clarity.so/allinforsport). If you're creating a proposal as part of a task or project, you can use [this template](https://app.clarity.so/allinforsport/template/ac886d40-fa1e-411f-9cb7-03a09d0337a7) instead.
