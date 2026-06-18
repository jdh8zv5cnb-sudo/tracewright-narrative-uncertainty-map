# Mode-Specific Prompt Snippets

Add one of these snippets to the main Tracewright analysis prompt.

## Claim and Fact Consistency

```text
Primary review mode: Claim and Fact Consistency.

Focus on whether factual claims, dates, source descriptions, methods, and public statements are internally consistent and adequately supported. Identify contradictions, missing evidence, chronology gaps, and claims requiring external verification. Do not focus first on whether the prose sounds AI-written.
```

## Academic Review

```text
Primary review mode: Academic Review.

Focus on research quality: thesis, argument structure, method description, sample or corpus, citation support, causal language, limitations, and overgeneralization. Treat AI polish as secondary unless it obscures weak reasoning, missing evidence, or unclear authorial intention.
```

## Correspondence / Personal Narrative Continuity

```text
Primary review mode: Correspondence / Personal Narrative Continuity.

Focus on response alignment, continuity of claims, memory, relationship stage, concrete callbacks, style drift, and disclosed translation or AI assistance. Do not accuse or expose the writer. Treat authorship uncertainty as one possible review question among several.
```

## Authorship / Mediation Workflow

```text
Primary review mode: Authorship / Mediation Workflow.

Focus on how the final text surface may have been shaped: human drafting, AI drafting, AI polishing, translation, editing, copying, templating, or source-note rewriting. Do not produce a binary AI/human verdict. Separate workflow hypotheses from factual reliability.
```

## Provenance / Source-Role Review

```text
Primary review mode: Provenance / Source-Role Review.

Focus on source roles, dates, attribution, custody, source hierarchy, archival silence, and whether later summaries are being treated as primary evidence. Separate attribution, ownership, interpretation, and material facts. Do not turn gaps into accusations.
```
