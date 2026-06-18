# Tracewright Analysis Prompt

Use this prompt with your own AI assistant when preparing material for a Tracewright-style review map.

Replace bracketed text before use.

```text
You are helping me prepare a Tracewright Narrative Uncertainty Map.

Tracewright is not an AI detector. Do not decide whether the material was written by AI. Instead, map uncertainty, provenance, source roles, claims, evidence gaps, alternative explanations, and next review actions.

Material type:
[correspondence / article / newsletter / academic paper / public narrative dossier / art provenance file / historical record set / other]

Primary review mode:
[Claim and Fact Consistency / Academic Review / Correspondence or Personal Narrative Continuity / Authorship or Mediation Workflow / Provenance or Source-Role Review / other]

Secondary review mode, if any:
[optional]

Review purpose:
[What I want to understand or decide after review]

Known provenance or workflow:
[Disclosed AI use, translation, editing, source notes, known drafts, publication context, or "unknown"]

Reviewer intuition, if any:
[Optional. If supplied, keep it separate from evidence.]

Source materials:
[Paste or summarize bounded materials. Use IDs for each source, such as S001, S002, S003.]

Please return a structured review map with these sections:

1. Source Inventory
For each source, list:
- source_id
- role
- date or sequence
- author/source role
- target/context status
- short summary
- known provenance
- limitations

2. Segment Summary
Break the material into meaningful segments. For each segment, list:
- segment_id
- source_id
- segment type
- summary
- review relevance

3. Claim Map
Extract verifiable, semi-verifiable, interpretive, value-based, and workflow/provenance claims. For each claim, list:
- claim
- type
- first source
- support status
- contradiction or gap
- review posture
- next check

4. Evidence Cards
For each important observation, create an evidence card with:
- title
- review lane: Authorship / mediation, Claim reliability, or Disclosure / provenance
- attention level: Stable / Observe / Mediated layer / Review / High attention
- source_id
- source excerpt
- marked text with reason
- reasoning chain
- alternative explanations
- next action
- texture axis if relevant: Human/source texture, Machine/editorial cleanliness, or none

5. Interpretation Guide Notes
Explain how a human reviewer should read the case without turning the map into a verdict.

6. Limitations
List what cannot be concluded from the provided material.

Rules:
- Preserve exact source excerpts where possible.
- Keep reader intuition separate from evidence.
- Keep authorship/mediation questions separate from factual reliability.
- Follow the chosen review mode. If the review purpose is unclear, ask clarifying questions before analyzing.
- Do not collapse company pages, third-party reporting, legal material, personal statements, and later interpretation into one voice.
- Do not treat polished prose as proof of AI authorship.
- Do not treat rough prose as proof of human authorship.
- If the review could affect employment, legal, academic, reputational, provenance, publication, or financial decisions, say that qualified human review is required.
```
