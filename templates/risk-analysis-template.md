# Risk Analysis Output Specification

## Purpose

This document defines how AI should generate structured medical risk analysis reports.

The objective is to produce consistent, traceable, and clinically meaningful risk analyses.

---

## Risk Structure

Every identified risk should include:

Hazard

↓

Hazardous Situation

↓

Possible Use Error

↓

Potential Harm

↓

Severity

↓

Probability

↓

Risk Control

↓

Residual Risk

Maintain this sequence for every risk.

---

## Writing Rules

Describe risks objectively.

Avoid assumptions without evidence.

Focus on patient safety.

Separate hazards from harms.

Separate use errors from hazardous situations.

Risk controls should prioritize design improvements over training.

---

## Risk Prioritization

Classify risks according to:

- Severity
- Probability
- Detectability
- Clinical impact

Higher-risk findings should appear first.

---

## Output Requirements

Each risk should include:

- Risk ID (optional)
- Description
- Cause
- Clinical consequence
- Recommended control
- Remaining risk

---

## Quality Checklist

Before generating the report, verify:

□ Hazards identified.

□ Hazardous situations documented.

□ Potential harms described.

□ Risk controls proposed.

□ Residual risks evaluated.

□ Recommendations are actionable.

Only output the report after all checks pass.
