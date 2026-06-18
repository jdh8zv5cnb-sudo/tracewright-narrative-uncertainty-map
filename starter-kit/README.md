# Tracewright Narrative Uncertainty Map Starter Kit

This starter kit lets you try the Tracewright review method locally with your own AI assistant and your own source materials.

Tracewright is not designed to expose people. It is designed to slow down premature judgment.

## What Is Included

- `dashboard/index.html`  
  A static dashboard demo that opens in a browser.

- `prompts/tracewright-analysis-prompt.md`  
  A reusable prompt for asking your own AI assistant to prepare a Tracewright-style review map.

- `prompts/review-intake-worksheet.md`
  A worksheet for choosing the review mode and telling your AI what kind of analysis you need before uploading or pasting materials.

- `prompts/mode-specific-prompt-snippets.md`
  Short prompt additions for common review modes.

- `prompts/refinement-feedback-prompt.md`
  A follow-up prompt for improving the first AI output.

- `templates/case-data-template.json`  
  A structured case-data template showing the fields used by the dashboard.

- `docs/ai-analysis-instructions.md`  
  Review instructions for correspondence, articles, newsletters, academic papers, and other narrative materials.

- `docs/methodology.md`  
  The core Tracewright method.

- `docs/ethics.md`  
  Privacy, consent, and misuse boundaries.

## Basic Workflow

1. Keep private source materials on your own machine or in your own secure workspace.
2. Fill out `prompts/review-intake-worksheet.md` so your AI assistant knows the review mode, purpose, limits, and known context.
3. Ask your preferred AI assistant to analyze a bounded document set using `prompts/tracewright-analysis-prompt.md` plus the appropriate mode snippet.
4. Use `prompts/refinement-feedback-prompt.md` to challenge and improve the first output.
5. Review the AI output yourself. Correct source excerpts, claims, evidence cards, and uncertainty labels.
6. Adapt the structured output into the shape shown in `templates/case-data-template.json`.
7. Use the dashboard as a review map, not as a verdict.

## What This Kit Does Not Do

- It does not upload documents.
- It does not connect to an AI API.
- It does not store your private materials.
- It does not detect whether a text was written by AI.
- It does not replace legal, academic, editorial, provenance, or professional review.

## Choosing a Review Mode

Tracewright works best when the AI knows what kind of review you want. Before analysis, choose a primary mode:

- Claim and Fact Consistency
- Academic Review
- Correspondence / Personal Narrative Continuity
- Authorship / Mediation Workflow
- Provenance / Source-Role Review

If more than one mode applies, choose one primary mode and one secondary mode. The same source material can produce different useful maps depending on the review purpose.

## How To Open the Dashboard

Open:

```text
dashboard/index.html
```

The included dashboard uses synthetic demo cases. To review your own material, adapt the dashboard or use the template as a guide for building your own case data.

## Safe Use

Use synthetic, anonymized, consent-safe, or private-local materials unless you have permission to publish the source text.

Do not use Tracewright to accuse, shame, expose, or rank people based on suspected AI use. The purpose is to document uncertainty, preserve alternative explanations, and decide what should be checked next.

## Public Project Links

Public demo:

```text
https://ayakoredon.github.io/tracewright-narrative-uncertainty-map/
```

GitHub repository:

```text
https://github.com/ayakoredon/tracewright-narrative-uncertainty-map
```
