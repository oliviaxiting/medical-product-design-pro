# Tables Review

## Purpose

This document defines review rules for data tables used in medical Console applications.

The objective is to improve scanning efficiency, reduce reading errors, and support rapid clinical decision-making.

---

## Human Factors Principle

Tables should support rapid comparison rather than detailed reading.

Users should quickly identify abnormal values, trends, and patient status.

---

## HE75 Recommendations

### Information Hierarchy

Display the most important columns first.

Avoid unnecessary information.

---

### Row Height

Rows should remain readable during prolonged monitoring.

Avoid excessively compact layouts.

---

### Column Alignment

Align numbers consistently.

Maintain predictable column positions.

---

### Sorting

Support sorting when clinically meaningful.

Current sorting status should remain visible.

---

### Status Display

Status should combine:

- Text
- Icon
- Color

Avoid color-only indication.

---

### Scanning

Support horizontal and vertical scanning.

Maintain consistent spacing.

---

## Console Application

Recommendations:

- Optimize for large displays.
- Support filtering.
- Support multi-column sorting when appropriate.
- Freeze key columns if necessary.

---

## PAD Application

Recommendations:

- Avoid large tables.
- Replace with cards when appropriate.
- Reduce visible columns.
- Prioritize essential information.

---

## Common Risks

- Dense tables.
- Narrow columns.
- Excessive scrolling.
- Color-only status.
- Misaligned numbers.

---

## Design Review Checklist

Before approving the design, verify:

□ Important columns appear first.

□ Tables support rapid scanning.

□ Row height is readable.

□ Numeric alignment is consistent.

□ Status is understandable.

□ Console supports prolonged monitoring.

□ PAD avoids unnecessary tables.

---

## AI Review Rules

Always evaluate:

- Scan efficiency
- Information density
- Comparison efficiency
- Status clarity

Never recommend tables when cards provide better usability.

---

## References

ANSI/AAMI HE75

ISO 9241
