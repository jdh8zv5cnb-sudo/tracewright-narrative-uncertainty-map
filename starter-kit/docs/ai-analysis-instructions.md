# AI Analysis Instructions

Use these instructions when asking an AI assistant to prepare material for a Tracewright-style dashboard.

## Before Analysis

The reviewer should state the review mode before providing or analyzing materials. If the review purpose is unclear, the AI assistant should ask clarifying questions rather than producing a generic analysis.

If documents are uploaded before the review purpose is clear, do not analyze immediately. First give the privacy reminder, ask the review mode and review purpose, ask what must not be concluded, and ask whether the user wants to proceed with the uploaded materials.

Common review modes:

- Claim and Fact Consistency
- Academic Review
- Correspondence / Personal Narrative Continuity
- Authorship / Mediation Workflow
- Provenance / Source-Role Review

The same document set may need different treatment depending on the selected mode. For example, an academic paper can be reviewed for publication quality, citation support, argument structure, or AI-mediated prose; these are related but not identical tasks.

## General Instruction

Analyze the provided document or bounded document sequence as review material. Do not decide whether it is AI-generated. Instead, create a structured uncertainty map for human review.

Return:

- source material inventory
- segment summaries
- claim map
- evidence cards with source excerpts
- alternative explanations
- review lanes
- next checks
- limitations of the analysis

Every important observation must quote or reference a source excerpt. If no exact excerpt was provided, say so. If the analysis relies on a user summary rather than source text, label that clearly. Do not invent excerpts, and do not paraphrase as if it were quoted source material.

Always separate:

- authorship or mediation signals
- disclosed or known provenance
- factual or claim reliability
- reviewer intuition, if supplied

## Correspondence Review

Emphasize:

- response alignment with prior messages
- continuity of memory, claims, tone, and relationship stage
- style drift across multiple messages
- concrete personal details
- grammar errors or local writing habits
- cross-language influence
- AI/editorial polish
- disclosed translation or AI use

Do not treat polish alone as AI authorship.

## Newsletter or Article Review

Emphasize:

- source-backed details
- public-facing claims
- editorial polish
- institutional templates
- translation or editorial workflow possibilities
- archive, object, date, name, and citation details
- claims that require external verification

Separate factual reliability from authorship or mediation.

## Academic Paper Review

Emphasize:

- central research claims
- method and sample description
- data source and inclusion/exclusion criteria
- quantitative claims
- causal language
- citation support
- definitions and operational terms
- limitations
- generalization beyond evidence

For academic papers, do not focus first on whether the prose sounds AI-polished. A polished paper can still have weak methods, unsupported citations, or overextended conclusions.

## Required Caution

The quality of the result depends on the AI model, prompt, extraction quality, and reviewer calibration. Treat the output as a draft review map. A human reviewer must inspect source excerpts and correct the analysis before relying on it.

## High-Impact Use Warning

If the review could affect a person's job, academic status, publication, legal position, reputation, insurance, financial interests, provenance claim, or institutional standing, do not rely on AI output alone. Tracewright can organize review questions, but qualified human review is required.
