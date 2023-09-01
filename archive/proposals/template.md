---
description: >-
  Template for creating standardized proposal archive pages within the AIFS DAO
  State Repository
---

# Proposal Archive Page Template

This template can be used to quickly create archive pages for proposals submitted to AIFS governance.

### Required Fields

Copy the following fields from the proposal content and/or voting platform data to populate the archive page.

<table><thead><tr><th width="162">Element</th><th width="187" align="center">Placeholder</th><th align="right">Description</th></tr></thead><tbody><tr><td>Title</td><td align="center"><code>proposalTitle</code></td><td align="right">The title of the proposal (including # + Standard)</td></tr><tr><td>Description</td><td align="center"><code>description</code></td><td align="right">Sentence-length summary of the proposal</td></tr><tr><td>Author(s)</td><td align="center"><code>proposalAuthor</code></td><td align="right">The author(s) of the document</td></tr><tr><td>Discussion</td><td align="center"><code>discussionUrl</code></td><td align="right">Link to the discussion forum or workspace</td></tr><tr><td>Voting Page</td><td align="center"><code>voteUrl</code></td><td align="right">Link to the voting platform URL</td></tr><tr><td>Publish Date</td><td align="center"><code>pubDate</code></td><td align="right">Date of proposal submission to voting space</td></tr><tr><td>Proposal Content</td><td align="center"><code>proposalContent</code></td><td align="right">The body text of the document</td></tr><tr><td>Votes</td><td align="center"><code>voteTally</code></td><td align="right">The number of votes per result (% or count)</td></tr><tr><td>Vote Result</td><td align="center"><code>voteResult</code></td><td align="right">The result of the vote (Passed or Failed)</td></tr><tr><td>State Changes</td><td align="center"><code>stateChange</code></td><td align="right">DAO State changes resulting from the proposal</td></tr></tbody></table>

### Field Definitions

*   #### Title (`proposalTitle`) <a href="#title" id="title"></a>

    The title of your document as a level-1 heading.

    If your document type has requirements related to the structure of its title (such as a proposal), specify them here.
*   #### Description (`proposalDescription)`

    A single-sentence summary of your document, often displayed in the header as a subtitle.
*   #### Author (`proposalAuthor)`

    The author or co-authors of the document. This can be appended to the description for a shorter page header or omitted if not relevant to your document type.
* **Discussion Page (`discussionUrl`)**\
  A link to the proposal's discussion forum thread or RFC post. \
  Display as a pretty link (`[🗣️`` `**`Discussion`**`](discussionUrl)`)
* **Voting Page (`voteUrl`)**\
  A link to the proposal's voting page on Snapshot or similar (or link to Discord post, etc. if voting page isn't available).\
  Display as a pretty link (`[⚡️`` `**`Snapshot`**`](voteUrl)`)
*   #### Submission Date (`pubDate)`

    The date on which the proposal was submitted to the voting space.
* **Vote Result (`voteResult`)**\
  The result of the vote (Passed, Failed, Etc.)\
  You may want to add an emoji to help indicate the result at a glance.
*   #### Proposal Content (`proposalContent`)

    The full text content of the original proposal. Be sure to omit any fields already included in the archive page to avoid redundancy.
* **Votes (`voteTally`)**\
  The number or percent or votes for each option. Be sure to boldly label each option (e.g. **Yes:** 100%), separate with commas and omit options with "0" value for legibility.
* **State Changes (`stateChange`)**\
  Describe the governance state changes made as a result of the proposal. Provide a link to the relevant entry in the GitHub commit history if possible.

### Proposal Archive Format

<details>

<summary>Document Model</summary>

## `proposalTitle`

`description`

Proposed by: `proposalAuthor`

🗣️ Discussion\
🌡️⚡⛓️ Snapshot

**Submitted:** `pubDate`\
**Result:** `voteResult` ✅ ❌

`proposalContent`

### 🗳️ Voting Result

**Votes:** `voteTally`\
**Result:** `voteResult`

### 🏗️ Governance State Changes

`stateChange`

</details>

#### Proposal Archive Templates

{% tabs %}
{% tab title="Markdown" %}
{% code title="Generic Markdown Template" lineNumbers="true" %}
```markdown
# proposalTitle

description

Proposed by: proposalAuthor

[🗣️ Discussion](discussionUrl)  
[🌡️⚡⛓️ Snapshot](voteURL)

**Submitted:** pubDate  
**Result:** voteResult ✅ ❌

proposalContent

## 🗳️ Voting Result

**Votes:**  voteTally  
**Result:**  voteResult

## 🏗️ Governance State Changes

```
{% endcode %}
{% endtab %}
{% endtabs %}

#### How to Use Archive Templates

1. Copy the relevant template above.
2. Paste the template into your preferred text editor (i.e. VS Code or Notepad).
3. Replace the element placeholders (such as `docTitle`) with your written content.
4. Copy and paste the completed document into your destination (Snapshot, Station, Discord, Notion, etc).
