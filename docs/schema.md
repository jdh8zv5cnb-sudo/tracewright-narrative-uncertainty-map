# Schema Notes

The public demo keeps case data embedded in `index.html` for portability. The Starter Kit also includes `templates/case-data-template.json`.

This schema is intentionally lightweight. A production implementation should prefer object-based data, validation, audit logs, and reviewer editing.

## Top-Level Case Fields

- `id`: stable case identifier.
- `name`: display name.
- `stage`: document genre or review stage.
- `level`: review posture label. This is not a score.
- `intuition`: reader intuition, if supplied. Keep separate from evidence.
- `overview`: short analysis overview.
- `posture`: how a reviewer should approach the case without turning it into a verdict.
- `screening`: summary handling information.
- `guide`: interpretation guide counts and focus cards.
- `claims`: claim map rows.
- `messages`: review material/source inventory rows.
- `evidence`: evidence card rows.
- `must_not_conclude`: optional list of conclusions the reviewer must not draw from the material.
- `qualified_human_review_required`: optional boolean.
- `high_impact_context`: optional list such as `academic evaluation`, `legal exposure`, or `provenance dispute`.

## Screening Fields

- `recommended_action`: what to do next.
- `evidence_completeness`: what source material is present or missing.
- `known_provenance`: known workflow, source, translation, AI, or editorial information.
- `blind_reading_value`: what the case teaches in blind review.
- `overclaim_risk`: what would be risky to conclude too quickly.
- `next_checks`: concrete follow-up checks.

## Texture Cue Counts

These are counts of evidence-card cue categories, not authorship probabilities.

- `source_texture`: source-grounded texture cues, such as specific detail, local judgment, rough edges, continuity, source role, or visible revision trace.
- `mediation_polish`: mediation/polish cues, such as template flow, automated synthesis, unusually clean surface, weak close reading, or fast generalization.
- `total`: denominator for cue counts.

Do not interpret these counts as "human score" or "AI score."

## Review Lanes

- `authorship`: authorship / mediation questions. This asks how wording, translation, editing, AI assistance, or final surface may have been shaped. It is not a finding about who wrote the material.
- `claims`: claim reliability questions. This asks whether facts, timelines, citations, methods, or content claims need checking. It is not a judgment of a person.
- `disclosure`: disclosure / provenance questions. This records explicit or known workflow/source information. It is not confession or guilt.
- `pressure`: low, moderate, or high review pressure.

## Evidence Card Array Format

The current demo uses compact arrays:

```json
[
  "Evidence card title",
  "yellow",
  "source:identifier",
  "Source excerpt.",
  [["marked text", "mark label", "why this marked text matters"]],
  ["Reasoning step 1", "Reasoning step 2"],
  ["Alternative explanation 1", "Alternative explanation 2"],
  "source_texture"
]
```

Positions:

1. title
2. color/posture cue
3. source id or source reference
4. exact source excerpt or explicit source reference
5. marked text list
6. reasoning chain
7. alternative explanations
8. texture cue category: `source_texture`, `mediation_polish`, or `not_applicable`

Important observations should include a source excerpt or clear source reference. If no exact excerpt is available, say so.

## Review Posture Labels

- `Stable / anchored`: there is continuity, source detail, or a baseline-like anchor.
- `Observe`: weak or ambiguous cue. Keep watching.
- `Mediated layer`: translation, polish, workflow, or source-layer separation should be inspected.
- `Review`: meaning shift, weak support, strong tool involvement, or boundary issue needs review.
- `High attention`: careful human review is required before use. This does not mean guilty, false, or AI-generated.

