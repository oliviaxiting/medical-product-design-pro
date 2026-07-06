# Forms Review

## Purpose

This document defines review rules for forms based on ANSI/AAMI HE75 and IEC 62366-1.

The objective is to reduce input errors, improve completion efficiency, and support safe clinical documentation.

---

## Human Factors Principle

Forms should minimize cognitive effort and reduce the possibility of incorrect data entry.

Users should understand what information is required and how to complete it.

---

## HE75 Recommendations

### Logical Order

Arrange fields according to clinical workflow.

Avoid arbitrary field order.

---

### Required Fields

Clearly distinguish required and optional fields.

Avoid unnecessary mandatory inputs.

---

### Labels

Use persistent labels.

Avoid placeholder-only labels.

Labels should remain visible during editing.

---

### Validation

Provide immediate validation.

Explain errors clearly.

Do not simply display "Invalid Input."

---

### Default Values

Use defaults only when clinically appropriate.

Never assume patient-specific values.

---

### Error Recovery

Allow users to easily correct mistakes.

Avoid forcing complete re-entry.

---

## Console Application

Recommendations:

- Support keyboard navigation.
- Reduce repetitive typing.
- Support batch editing where appropriate.

---

## PAD Application

Recommendations:

- Minimize text input.
- Prefer selection controls.
- Reduce keyboard usage.
- Increase touch spacing.

---

## Common Risks

- Missing labels.
- Confusing validation.
- Excessive mandatory fields.
- Difficult correction.
- Long forms.

---

## Design Review Checklist

Before approving the design, verify:

□ Field order matches workflow.

□ Labels remain visible.

□ Validation is understandable.

□ Required fields are obvious.

□ Console supports efficient input.

□ PAD minimizes typing.

---

## AI Review Rules

Always evaluate:

- Workflow consistency
- Error prevention
- Input efficiency
- Validation quality

Never increase documentation burden without clinical value.

---

## References

ANSI/AAMI HE75

IEC 62366-1

ISO 9241
