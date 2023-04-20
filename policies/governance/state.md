---
description: Policies governing updates to the AIFS governance state repository
---

# State Update Policy

## Org Details Updates

Updates to the [organization](broken-reference) directory should be made to provide current information related to All In For Sport Governance, and **do not require approval by community or operational governance**.

## Policy Updates

**Updates to the** [**Policies & Agreements**](broken-reference) **directory must be approved by a State Update Proposal** via Community Governance, or by _both_ Community Governance _and_ the DAO Advisory Group in the case of [changes to the operating agreement](state.md#changes-to-the-operating-agreement).

### Changes to the [Operating Agreement](../membership/#operating-agreement)

The following policies govern changes made to the Trustless Unincorporated Nonprofit Association Agreement used by AIFS:

1. (according to section 6.1) The DAO Advisory Group (Operational Governance) will be solely responsible for the interpretation of the Operating Agreement.&#x20;
2. All DAO State Update Proposals must be reviewed by the DAO Advisory Group (or their delegate) to ensure that the proposed changes do not violate the terms of the TUNAA, disqualify the DAO's UNA status or challenge the limitation of liability for its members. Proposals in violation of the above may be vetoed.
3. All changes to the operating agreement, including revocation, must originate from a [DAO State Update Proposal](../proposals/metagovernance.md) (via Community Governance).
4. Any proposed DAO State Update which includes changes to, or revocation of, the Operating Agreement must be approved by the DAO Advisory Group (Operational Governance).
5. (according to Section 6.3) All approved changes to the Operating Agreement must result in a corresponding update to, or revocation of, the [Ricardian NFT](https://docs.wrappr.wtf/get-started/what/), or will be considered invalid.
6. (according to section 5.4) If the Ricardian NFT is to be permanently revoked (thus dissolving the UNA) all treasury funds _must first_ be donated to a 501(c)(3) tax exempt organization.

#### DAO Purpose Statement

The DAO must maintain a Purpose Statement (summarized in a single sentence) for use in the Operating Agreement and Ricardian Mint interface. This purpose statement should be included prominently at the top of the "[Operating Agreement](../membership/operating-agreement.md)" page of the DAO state document.

Governance proposals which do not serve the DAO's purpose as defined above may (and should) be vetoed by the DAO Advisory Group in order to maintain compliance with the terms of the TUNAA.

#### Current Milestone

The DAO (via Community Governance) will agree upon a measure of progress (a "Milestone") related to the development and success of the core protocol. The period of work related to each Milestone will be known as an "Epoch". The Epoch will end once the stated Milestone (including its accompanying [Goals](state.md#operational-goals)) is reached.

For each Epoch, a proposal will be made to Community Governance acknowledging the completion of the current Epoch and describing the next proposed Milestone. If the aforementioned proposal passes, the current Epoch ends and the next Epoch will begin (pending satisfaction of current obligations as described below). A DAO State Update will be made to reflect changes to the Current Milestone and [Operational Goals](state.md#operational-goals).

All patronage capital, operational budgets or other treasury allocations related to previous Epochs must be disbursed prior to commencement of a new Epoch, if they have not been disbursed already. The new Epoch cannot commence (nor can any related DAO State Updates be made) until these obligations are satisfied.

#### Operational Goals

The DAO Advisory Group (via Operational Governance) will maintain a list of [goals ](../membership/operating-agreement.md#goals)which must be achieved in order to reach the current Milestone. These goals should be reflected within all project management interfaces and roadmaps, and in the "[Operating Agreement](../membership/operating-agreement.md#goals)" page of the DAO State.

Timely DAO State Updates must be made as changes to the Operational Goals are ratified by the DAO Advisory Group, which will determine its own process for managing goals.

## Archive Updates

Timely updates to the [Archives](broken-reference) directory should be made as new activities occur, and **do not require approval by community or operational governance**.

### Treasury Approvals

The [treasury approval archive](state.md#treasury-approvals) should be updated promptly when new transaction approvals are confirmed on-chain. The signer who initiates the transaction is responsible for updating the transaction registry and may delegate that task, on a per-case basis, to a member of the governance team with their consent.

Treasury approval records must contain all details specified on the "[Treasury Approvals](../../archive/approvals/)" page and should be formatted in a consistent and legible manner.

### DAO State Changes

The [DAO state changes archive](../../archive/updates.md) should be updated _within the same pull request / change request_ as the changes describes within the entry. The contributor who initiates a pull/change request is responsible for updating the state change registry. If a state change record isn't included with a DAO state update, one should be added later by the governance team.

State change records must contain all details specified on the "[DAO State Changes](../../archive/updates.md)" page and should be formatted in a consistent and legible manner.

### Governance Proposals

All proposals submitted for vote by Community Governance must be recorded in the [Proposal Archive](../../archive/proposals/). Proposals in the archive are sorted by Epoch. "[Epoch 0 proposals](../../archive/proposals/epoch-0/)" are those proposals which were submitted prior to the adoption of cryptographic consensus and this DAO state repository.

All proposals accepted into the DAO state must comply with this State Update Policy and accompanying [State Update Proposal Standard](../proposals/metagovernance.md), or should be considered invalid (even if passed by Community Governance vote). The DAO Advisory Group will determine whether a proposal is compliant, and will clearly state their rationale and issue recommendations for compliance should any proposal be considered non-compliant. Proposals should be optimistically considered compliant unless a dispute is made within Operational Governance.

Proposal archive pages must contain the full proposal text, the voting outcome, and a summary of any DAO state changes or other actions taken as a result of the proposal. The [proposal archive page template](../../archive/proposals/template.md) should be used to format archive pages in a consistent manner.

## Minor Changes & Fixes

Minor changes to the governance state which do not meaningfully alter its content may be committed by the governance team. Such changes include typo corrections, updating old links, fixing page titles or slugs, and similar one-line changes.

The governance team must notify the DAO of all minor changes to the governance state via its dedicated communication channel and must provide an opportunity to discuss and review all changes during the next governance meeting.

Should any DAO member make a reasonable objection to a minor change, the change must be immediately reverted until their objection is satisfied. If the objection cannot be satisfied, a DAO state update proposal must be made to commit the change.

## Omnibus Changes

Excepting the initial commit to the DAO state repository, all changes to the DAO state must be related to one single issue only. "Omnibus" changes to the DAO state are **not allowed** and should be rejected by the DAO Advisory Group if passed by community governance.

Changes should be limited to the contents of a single page unless those pages are related (for example, a governance policy and its related proposal standard).

Changes to pages across multiple categories are **not allowed**.
