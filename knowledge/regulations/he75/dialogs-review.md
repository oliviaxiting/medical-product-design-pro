# Dialogs Review

## Purpose

This document defines review rules for dialogs based on ANSI/AAMI HE75 and IEC 62366-1.

The objective is to ensure dialogs communicate important information without unnecessarily interrupting clinical workflows.

---

## Human Factors Principle

Dialogs should be used only when user attention or confirmation is genuinely required.

Avoid unnecessary interruptions.

---

## HE75 Recommendations

### Necessity

Display dialogs only for:

- Critical confirmation
- Safety warnings
- Irreversible actions
- Important system messages

Avoid dialogs for routine information.

---

### Message Clarity

Messages should explain:

- What happened.
- Why it happened.
- What the user should do next.

Avoid vague wording.

---

### Actions

Provide clear action labels.

Examples:

- Save Changes
- Cancel
- Retry
- Continue Monitoring

Avoid generic labels such as OK.

---

### Modal Usage

Use modal dialogs only when the current task must pause.

Avoid unnecessary blocking interactions.

---

### Error Dialogs

Errors should provide recovery guidance.

Users should know how to resolve the issue.

---

## Console Application

Recommendations:

- Reduce interruptions during monitoring.
- Keep alarm dialogs distinguishable.
- Preserve workflow context.

---

## PAD Application

Recommendations:

- Use full-screen dialogs only when necessary.
- Keep dialogs simple.
- Support quick dismissal when appropriate.

---

## Common Risks

- Too many dialogs.
- Generic wording.
- Blocking workflows.
- Missing recovery guidance.
- Confirmation fatigue.

---

## Design Review Checklist

Before approving the design, verify:

□ Dialog is necessary.

□ Message is understandable.

□ Actions are clear.

□ Workflow interruption is justified.

□ Error recovery is supported.

□ Console minimizes interruption.

□ PAD supports rapid decision-making.

---

## AI Review Rules

Always evaluate:

- Necessity
- Workflow interruption
- Recovery guidance
- Action clarity

Never recommend confirmation dialogs for every operation.

---

## References

ANSI/AAMI HE75

IEC 62366-1

ISO 9241
