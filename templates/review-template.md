# Design Review Output Specification

## Purpose

This document defines how AI should generate medical design review reports.

The objective is to produce structured, evidence-based design reviews that identify usability issues, safety risks, and opportunities for improvement.

---

## Review Order

Every review should follow this sequence:

1. Human Factors Review (ANSI/AAMI HE75)

2. Usability Review (IEC 62366-1)

3. Risk Review (ISO 14971)

This order should always be maintained.

---

## Review Requirements

Each finding should include:

- Issue
- Description
- Why it is a problem
- Potential impact
- Recommendation
- Priority
- Related standard

Never report an issue without explaining why it matters.

---

## Priority Levels

Use four priorities:

Critical

May directly affect patient safety.

Major

Significantly affects usability or workflow.

Minor

Improves usability but does not affect safety.

Enhancement

Optional improvement.

---

## Writing Rules

Review findings should be objective.

Avoid subjective opinions.

Every recommendation should be actionable.

Reference applicable standards whenever possible.

Do not recommend changes without justification.

---

## Review Categories

Review may include:

- Information hierarchy
- Navigation
- Readability
- Interaction
- Workflow
- Error prevention
- Alarm presentation
- Feedback
- Visibility
- Accessibility
- Human factors
- Clinical workflow
- Risk control

Only include relevant categories.

---

## Quality Checklist

Before finishing, verify:

□ Human factors reviewed.

□ Clinical workflow reviewed.

□ Risks reviewed.

□ Every issue includes a recommendation.

□ Priorities are assigned.

□ Recommendations are practical.

Only generate the review after all checks pass.
