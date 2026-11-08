# Error Log & Prompt Comparison Findings

## Summary of Key Failures in Prompt A (Unstructured Baseline)
1. **Buried Action Items:** Critical safety steps (e.g., checking pulse daily before Bisoprolol in Letter 1) were embedded inside dense narrative paragraphs rather than emphasized.
2. **Omitted Tapering Rules:** In Letter 2, Prompt A mentioned lowering the Prednisolone dose but failed to explicitly outline the 5mg/7 days step-down cadence clearly.
3. **Complex Medical Terms Retained:** Unstructured prompts allowed terms like "HbA1c", "CRP", and "ESR" to remain unexplained in the text.
4. **High Readability Variance:** Prompt A outputs averaged a Flesch-Kincaid Grade Level of 7.3 (Reading Age ~12-13 years), exceeding the target 11-year-old threshold.

## Strengths of Prompt B (Structured & Guardrailed)
1. **Zero Hallucinations:** Strict grounding instructions prevented invented clinical steps.
2. **Clear Information Hierarchy:** Dedicated visual sections (Main Update, Medications, Next Steps, Warning Signs) drastically reduced cognitive load.
3. **Lower Reading Age:** Prompt B outputs consistently achieved Flesch Reading Ease >= 75.0 and Grade Levels <= 5.8 (Reading Age 10-11 years).
