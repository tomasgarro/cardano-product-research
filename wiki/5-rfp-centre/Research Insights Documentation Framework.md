---
title: Research Insights Documentation Framework
type: overview
section: 5
created: 2026-05-05
updated: 2026-05-05
tags: [rfp, m2, research-outputs, documentation, insights]
status: publication-draft
sources: [Product Research RFP package]
---

# Research Insights Documentation Framework

Awarded research should produce outputs that can be used after the grant closes. This framework defines the minimum structure for final research outputs so findings can be reviewed, published, cited, and handed off across the Product Research Initiative portfolio.

## Required Output Set

Each awarded project should deliver:

| Output | Purpose |
|---|---|
| Executive decision memo | Short answer to what Cardano stakeholders should do differently |
| Full research report | Complete evidence, method, findings, limitations, and recommendations |
| Evidence register | Source table showing where factual claims come from |
| Decision-gate response table | Direct answer to each RFP decision gate |
| Public summary | Non-confidential version suitable for publication |
| Confidential appendix, if needed | Sensitive respondent, commercial, or strategic detail for CPC review only |
| Cross-RFP handoff memo | Findings that belong to another RFP or workstream |

## Executive Decision Memo

The memo should be short enough to read without the full report. It should state:

- the decision the research answers;
- top findings;
- recommended action;
- no-go, defer, or stop recommendations where relevant;
- confidence level;
- key risks or limitations;
- next steps for CPC and relevant ecosystem stakeholders.

## Evidence Register

Every factual claim should be traceable. The evidence register should include:

| Claim / Finding | Evidence source | Source type | Public or confidential | Confidence | Limitation |
|---|---|---|---|---|---|
| [Finding] | [Interview/source/data] | [Type] | [Public/confidential] | [High/Medium/Low] | [Limit] |

## Decision-Gate Response Table

Each final report should include:

| Decision Gate | Answer | Evidence basis | Confidence | Action unlocked | Handoff |
|---|---|---|---|---|---|
| [Gate] | [Yes/No/Conditional/Mixed] | [Evidence] | [Level] | [Action] | [RFP/workstream] |

## Public and Confidential Outputs

Research outputs should separate:

- public findings that can be shared with the Cardano community;
- confidential findings for CPC or designated reviewers;
- raw data that should not be published;
- proprietary data that can be inspected but not republished;
- vendor judgment where evidence cannot be disclosed.

Public summaries should preserve useful insight without exposing respondent identities, commercially sensitive information, confidential strategy, or raw personal data.

## Cross-RFP Handoffs

Handoffs should be explicit. A handoff memo should state:

- the finding;
- the source RFP;
- the receiving RFP or workstream;
- why it is a handoff rather than part of the current scope;
- whether the finding is public, confidential, or uncertain;
- recommended next action.

## Suggested Metadata

Each final output should include:

```yaml
title: [Research Output Title]
rfp: [RFP number and title]
vendor: [Vendor/team]
date: [Date]
version: [Version]
public_status: public | confidential | redacted
sources: [source categories]
decision_gates: [list]
tags: [product-research, rfp-number, topic]
```

## Where to Go Next

- [[RFP Index]]
- [[Evaluation Criteria]]
- [[Submission Pack]]
