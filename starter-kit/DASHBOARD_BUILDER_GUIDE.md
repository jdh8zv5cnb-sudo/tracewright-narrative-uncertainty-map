# Dashboard Builder Guide

Use this guide if you are comfortable working with Codex, local files, HTML, JSON, or another AI-assisted development environment and you want to adapt the dashboard itself.

If you only want your AI assistant to review documents and produce a Markdown review map, use `USE_THIS_WITH_YOUR_AI.md` instead.

## What This Kit Provides

- `dashboard/index.html`  
  A static dashboard demo that opens in a browser.

- `templates/case-data-template.json`  
  A structured case-data template showing the fields used by the dashboard.

- `prompts/tracewright-analysis-prompt.md`  
  A reusable prompt for asking an AI assistant to prepare a Tracewright-style review map.

- `prompts/review-intake-worksheet.md`  
  A worksheet for defining the review mode, purpose, limits, and known context.

- `prompts/mode-specific-prompt-snippets.md`  
  Short prompt additions for common review modes.

- `prompts/refinement-feedback-prompt.md`  
  A follow-up prompt for improving the first AI output.

- `docs/ai-analysis-instructions.md`  
  Review instructions for correspondence, articles, newsletters, academic papers, provenance files, and other narrative materials.

- `docs/methodology.md`  
  The core Tracewright method.

- `docs/ethics.md`  
  Privacy, consent, and misuse boundaries.

## Builder Workflow

1. Keep private source materials outside the public repository.
2. Open `dashboard/index.html` once so you understand the review surface.
3. Use `prompts/review-intake-worksheet.md` to define the review task.
4. Ask your AI assistant to analyze a bounded document set using `prompts/tracewright-analysis-prompt.md` plus the relevant mode snippet.
5. Challenge the first output with `prompts/refinement-feedback-prompt.md`.
6. Review and correct the AI output manually.
7. Convert the result into structured data using `templates/case-data-template.json`.
8. Adapt `dashboard/index.html` or build your own interface around the same concepts.

## What To Preserve In A Custom Dashboard

Preserve these separations:

- source material versus analysis
- user-provided context versus document text
- authorship/mediation signals versus factual reliability
- disclosed workflow versus inferred workflow
- evidence cards versus summary posture
- review posture versus verdict

The dashboard should make it easy to trace any summary statement back to source excerpts, claims, evidence cards, and alternative explanations.

## What This Kit Does Not Do

- It does not upload documents.
- It does not connect to an AI API.
- It does not store private materials.
- It does not detect whether a text was written by AI.
- It does not replace legal, academic, editorial, provenance, or professional review.

## Safe Use

Use synthetic, anonymized, consent-safe, or private-local materials unless you have permission to publish the source text.

Do not use Tracewright to accuse, shame, expose, or rank people based on suspected AI use. The purpose is to document uncertainty, preserve alternative explanations, and decide what should be checked next.
