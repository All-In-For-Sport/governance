---
description: Standards for proposals to update the All In For Sport DAO state
---

# 🏗 State Update Proposals

{% hint style="info" %}
The State Update Proposal Standard is currently in development and will be included in the first draft of the DAO state repository.

Once finished, this proposal standard can be replicated in Clarity using a **snippet** to aid proposal development.
{% endhint %}

This is a specialized standard governing the content of proposals submitted to AIFS governance requesting changes or additions to the DAO's policies, permissions roster or governance procedures.

### Proposal Requirements <a href="#requirements" id="requirements"></a>

In addition to the [standard proposal requirements](./), DAO state update proposals must meet the following requirements.&#x20;

If your proposal does not comply with these requirements, you'll be asked to update your proposal to ensure compliance before submitting for consideration by the DAO.&#x20;

*   #### Pull Request or Change Request Link (`changeRequestUrl`)

    \
    A link to the GitHub Pull Request or GitBook Change Request containing the proposed changes. This is used by the governance team to commit your changes if the proposal passes.\

* **Amendment Text (`amendmentText`)**\
  \
  The full text of the proposed change, including any text replaced or removed. \
  \
  You can include any removed text using a quote (`> removed text`) for full paragraphs, or a strikethrough (`~~removed text~~`) for inline text like words and sentences.\

* **Author's Intention (`amendmentIntention`)**\
  \
  Describe your intention for making the change request, including the outcome you hope to achieve. This helps to others to better interpret the DAO state language.\


## Proposal Formatting <a href="#format" id="format"></a>

Proposals should be formatted in an organized manner in order to provide easy reading and comprehension for your fellow DAO members. It is recommended that you use the following format to present your proposal to DAO governance:

<details>

<summary>Proposal Model</summary>

## proposalNumber: proposalTitle <a href="#proposalnumber-proposaltitle" id="proposalnumber-proposaltitle"></a>

proposalDescription

Proposed by: proposalAuthor

[**Change Request Link**](https://markdownlivepreview.com/changeRequestUrl)

### Summary <a href="#summary" id="summary"></a>

proposalSummary

### Proposed Changes <a href="#proposed-changes" id="proposed-changes"></a>

amendmentText

### Intention <a href="#intention" id="intention"></a>

amendmentIntention

</details>

<details>

<summary>Example Proposal</summary>

<mark style="color:yellow;">TBD - First state update proposal to be used as example</mark>

</details>

### Proposal Templates <a href="#templates" id="templates"></a>

Preformatted templates are available for DAO members who wish to author their own proposals. Alternatively, you can contact the governance team for assistance with the creation and submission of your proposal.

Most governance tooling (such as Snapshot, Discourse, Station, etc.) uses Markdown for text input. Markdown can be edited in any text editor, or you can use an advanced editor like [VS Code](https://code.visualstudio.com/) to check for spelling and formatting errors before publication.

{% tabs %}
{% tab title="Markdown" %}
{% code title="Generic Markdown" lineNumbers="true" %}
```markdown
# proposalNumber: proposalTitle

proposalDescription

Proposed by: proposalAuthor

**[Change Request Link](changeRequestUrl)**

## Summary

proposalSummary

## Proposed Changes

amendmentText

## Intention

amendmentIntention
```
{% endcode %}
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

**[Change Request Link](changeRequestUrl)**

## Summary

proposalSummary

## Proposed Changes

amendmentText

## Intention

amendmentIntention
```
{% endcode %}
{% endtab %}

{% tab title="Clarity" %}
[**Proposal Development Task Template**](https://app.clarity.so/allinforsport/template/c0643ca1-0460-4648-99fb-1aa36c6d04ac)**:**\
Use this template to create a new task for proposal development\
[https://app.clarity.so/allinforsport/template/c0643ca1-0460-4648-99fb-1aa36c6d04ac](https://app.clarity.so/allinforsport/template/c0643ca1-0460-4648-99fb-1aa36c6d04ac)

[**Proposal Format Snippet**](https://app.clarity.so/allinforsport/snippet/3c658c30-395e-4a1a-9f7a-b058d8fa15e4)**:**\
Use this snippet to populate an existing document with the proposal format\
[https://app.clarity.so/allinforsport/snippet/3c658c30-395e-4a1a-9f7a-b058d8fa15e4](https://app.clarity.so/allinforsport/snippet/3c658c30-395e-4a1a-9f7a-b058d8fa15e4)
{% endtab %}
{% endtabs %}

#### How to Use Proposal Templates

You can use these templates to create your own proposals using this format by following the instructions below.

1. Prepare your proposal content using the [requirements](metagovernance.md#proposal-requirements) listed above.
2. Copy the relevant proposal template and paste the into your preferred text editor (VS Code, Notion, Snapshot, Station, etc).
3. Replace the element placeholders (such as `proposalTitle`) with your proposal content.
4. Copy and paste the completed proposal into your destination (Snapshot, Station, Discord, Notion, etc).

You can use [this snippet](https://app.clarity.so/allinforsport/snippet/3c658c30-395e-4a1a-9f7a-b058d8fa15e4) to draft your proposal in [Clarity](https://app.clarity.so/allinforsport). If you're creating a proposal as part of a task or project, you can use [this template](https://app.clarity.so/allinforsport/template/c0643ca1-0460-4648-99fb-1aa36c6d04ac) instead.
