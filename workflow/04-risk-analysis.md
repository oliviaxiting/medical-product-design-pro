# Risk Analysis Workflow

## Purpose

This workflow defines how AI should identify, analyze, and prioritize risks before generating interface designs or product requirements.

The objective is to proactively reduce patient safety risks by integrating usability engineering, human factors, and medical risk management into the design process.

Risk analysis should always precede interface design and PRD generation.

---

## When to Use

Use this workflow whenever:

- Designing a new feature.
- Modifying an existing workflow.
- Creating a medical PRD.
- Reviewing interaction designs.
- Evaluating patient safety.

---

## Inputs

Required inputs include:

- Requirement Analysis
- Clinical Workflow Analysis
- Task Analysis
- Intended Users
- Use Environment

Reference:

- IEC 62366-1
- ISO 14971

---

## Process

### Step 1 — Identify Hazards

Determine potential hazards associated with the workflow.

Consider:

- User actions
- System behavior
- Environmental conditions
- Device status
- Clinical context

---

### Step 2 — Identify Hazardous Situations

Determine how hazards may lead to unsafe situations.

Examples:

- Wrong patient selected
- Incorrect parameter adjustment
- Alarm ignored
- Information misunderstood

---

### Step 3 — Identify Potential Harm

Describe possible clinical consequences.

Examples:

- Delayed treatment
- Incorrect therapy
- Missed diagnosis
- Patient injury

---

### Step 4 — Evaluate Risk

Evaluate:

- Severity
- Probability
- Detectability

Prioritize higher-risk scenarios.

---

### Step 5 — Recommend Risk Controls

Whenever possible, reduce risks by improving:

- Workflow
- Interaction
- Information hierarchy
- Feedback
- Visibility
- Error prevention

Avoid relying only on warnings or user training.

---

### Step 6 — Evaluate Residual Risk

Determine whether remaining risks are acceptable after controls have been applied.

---

## Quality Gates

Verify:

□ Hazards identified.

□ Hazardous situations documented.

□ Potential harms identified.

□ Risk controls proposed.

□ Residual risks evaluated.

---

## Outputs

Generate:

- Hazard List
- Risk List
- Risk Priority
- Risk Control Recommendations
- Residual Risk Summary

---

## References

ISO 14971

IEC 62366-1

ANSI/AAMI HE75

---

## AI Self Checklist

□ Every critical task has been evaluated.

□ Potential patient harm has been considered.

□ Interface improvements have been proposed.

□ Remaining risks are acceptable.

Risk analysis must be completed before PRD generation.
