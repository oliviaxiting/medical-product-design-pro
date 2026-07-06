# Task Analysis Workflow

## Purpose

This workflow defines how AI should decompose clinical workflows into individual user tasks.

The objective is to understand every action required to safely complete a clinical objective and identify opportunities to improve usability and reduce risk.

Task analysis bridges clinical workflows and interface design.

---

## When to Use

Use this workflow whenever:

- Designing a new interface.
- Generating a PRD.
- Performing usability engineering.
- Evaluating existing workflows.

Task analysis should always follow Clinical Workflow Analysis.

---

## Inputs

Required inputs include:

- Requirement Analysis
- Clinical Workflow Analysis
- User Profiles
- Use Scenarios

---

## Process

### Step 1 — Identify User Goal

Determine what the user is trying to accomplish.

Examples:

- Review patient status
- Configure device
- Acknowledge alarm
- Record clinical data

---

### Step 2 — Identify Major Tasks

Break the goal into major tasks.

Each task should represent a meaningful unit of work.

---

### Step 3 — Decompose into Subtasks

Describe every interaction step.

For each subtask identify:

- User action
- System response
- Required information
- Expected outcome

---

### Step 4 — Identify Task Dependencies

Determine:

- Preconditions
- Required resources
- Required information
- Sequential relationships

---

### Step 5 — Identify Critical Tasks

Identify tasks where failure may affect:

- Patient safety
- Clinical effectiveness
- Regulatory compliance

These tasks require additional design attention.

---

### Step 6 — Identify Potential Use Errors

For every task ask:

- What could go wrong?
- Why could it happen?
- How could the interface prevent it?

---

## Quality Gates

Verify:

□ User goals are clear.

□ Tasks are complete.

□ Subtasks are sequential.

□ Critical tasks are identified.

□ Potential use errors are documented.

---

## Outputs

Generate:

- Task List
- Task Hierarchy
- Critical Task List
- Task Dependencies
- Potential Use Errors

---

## References

IEC 62366-1

ISO 14971

ANSI/AAMI HE75

---

## AI Self Checklist

□ Every user goal is supported.

□ Every task has been decomposed.

□ Critical tasks are identified.

□ Use errors have been analyzed.

□ Task analysis is complete before interface design begins.
