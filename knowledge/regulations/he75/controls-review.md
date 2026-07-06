# Controls Review

## Purpose

This document defines review rules for interactive controls based on ANSI/AAMI HE75 and IEC 62366-1.

The objective is to ensure that controls are recognizable, predictable, and safe under clinical conditions.

This document reviews interaction quality rather than visual style.

---

## Human Factors Principle

Interactive controls should clearly communicate what actions are available, what state they are in, and what will happen after activation.

Users should never need to guess how a control behaves.

---

## HE75 Recommendations

### Recognition

Controls should be immediately recognizable.

Avoid interactive elements that appear as plain text.

---

### Consistency

Use the same control style for the same function throughout the product.

Do not change interaction behavior between pages.

---

### Feedback

Every interaction should provide immediate visual feedback.

Examples:

- Button pressed
- Loading
- Success
- Failure
- Disabled

---

### Disabled State

Disabled controls should clearly indicate that they are unavailable.

Avoid hiding important actions without explanation.

---

### Critical Actions

Critical operations should be clearly distinguished from routine operations.

Use confirmation dialogs only when necessary.

---

### Labels

Action labels should describe the outcome.

Prefer:

- Save
- Confirm
- Start Monitoring

Avoid:

- OK
- Submit
- Execute

---

## Console Application

Recommendations:

- Support mouse and keyboard interaction.
- Maintain predictable control placement.
- Reduce unnecessary confirmations.
- Optimize for repeated operation.

---

## PAD Application

Recommendations:

- Support finger operation.
- Increase spacing between controls.
- Reduce accidental activation.
- Keep primary actions easy to reach.

---

## Common Risks

- Hidden controls.
- Ambiguous labels.
- Inconsistent interaction.
- Missing feedback.
- Accidental activation.

---

## Design Review Checklist

Before approving the design, verify:

□ Controls are recognizable.

□ Labels describe the action.

□ Interaction feedback is immediate.

□ Critical actions are protected.

□ Disabled state is understandable.

□ Console supports efficient operation.

□ PAD supports touch interaction.

---

## AI Review Rules

Always evaluate:

- Discoverability
- Feedback
- Consistency
- Safety
- Error prevention

Never recommend decorative controls that reduce usability.

---

## References

ANSI/AAMI HE75

IEC 62366-1

ISO 9241
