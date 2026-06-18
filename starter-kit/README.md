# Tracewright Narrative Uncertainty Map Starter Kit

This starter kit lets you try the Tracewright review method locally with your own AI assistant and your own source materials.

Tracewright is not designed to expose people. It is designed to slow down premature judgment.

## What Is Included

- `dashboard/index.html`  
  A static dashboard demo that opens in a browser.

- `prompts/tracewright-analysis-prompt.md`  
  A reusable prompt for asking your own AI assistant to prepare a Tracewright-style review map.

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
2. Ask your preferred AI assistant to analyze a bounded document set using the prompt in `prompts/tracewright-analysis-prompt.md`.
3. Review the AI output yourself. Correct source excerpts, claims, evidence cards, and uncertainty labels.
4. Adapt the structured output into the shape shown in `templates/case-data-template.json`.
5. Use the dashboard as a review map, not as a verdict.

## What This Kit Does Not Do

- It does not upload documents.
- It does not connect to an AI API.
- It does not store your private materials.
- It does not detect whether a text was written by AI.
- It does not replace legal, academic, editorial, provenance, or professional review.

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
