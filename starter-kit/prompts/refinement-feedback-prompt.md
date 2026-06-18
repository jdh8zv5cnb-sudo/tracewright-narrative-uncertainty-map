# Refinement Feedback Prompt

Use this after your AI assistant returns an initial Tracewright analysis.

The first output should be treated as a draft review map. Use this prompt to make the AI improve the analysis, expose weak reasoning, and separate different kinds of uncertainty.

```text
Please refine the Tracewright analysis you just produced.

Before revising, check your own output for these problems:

1. Did you mix authorship/mediation questions with factual reliability questions?
2. Did you imply a verdict where only a review cue is justified?
3. Did you rely on polish, fluency, or roughness as stronger evidence than it deserves?
4. Did you preserve exact source excerpts for each important observation?
5. Did you distinguish primary sources, secondary sources, institutional sources, personal statements, third-party reporting, and later interpretation?
6. Did you list alternative explanations for each flagged issue?
7. Did you clearly state what cannot be concluded from the available material?

Now revise the output with these changes:

- Make the top review flags more specific.
- For each flag, show the exact source excerpt or say that no exact excerpt was provided.
- Add alternative explanations.
- Add next checks.
- Mark weak signals as weak.
- Remove any detector-like or verdict-like wording.
- Identify where qualified human review is required.

Also answer these questions:

- What is the most important thing a human reviewer should inspect first?
- What is the easiest thing to overclaim?
- What evidence would reduce uncertainty the most?
- Which parts of the analysis depend most on the AI model's judgment rather than direct source evidence?
```

