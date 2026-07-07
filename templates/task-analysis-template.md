# Task Analysis Output Specification

## Purpose

This document defines how AI should generate task analysis reports for medical software.

The objective is to describe clinical tasks in a structured, traceable, and implementation-ready format that supports usability engineering, interaction design, and risk management.

---

## Output Requirements

Each task should describe one complete user objective.

Tasks should be decomposed into logical subtasks without skipping intermediate user actions.

Task descriptions should reflect actual clinical workflows rather than software functionality.

---

## Required Structure

Each task should include:

- Task Name
- Goal
- Primary User
- Trigger
- Preconditions
- User Actions
- System Responses
- Required Information
- Decision Points
- Possible Use Errors
- Risk Considerations
- Completion Criteria

---

## Task Decomposition Rules

Tasks should:

- Begin with a user objective.
- Be divided into sequential subtasks.
- Clearly distinguish user actions from system responses.
- Include all critical decision points.
- Identify safety-critical tasks.

Avoid describing implementation details.

---

## Writing Rules

Use concise and objective language.

Describe observable user actions.

Avoid vague descriptions such as:

- Handle data
- Manage patient
- Process information

Instead describe specific actions.

Example:

Review patient status.

Confirm alarm.

Adjust exposure parameter.

---

## Medical Design Rules

For every task evaluate:

- Clinical importance
- Frequency
- Cognitive workload
- Time sensitivity
- Patient safety impact
- Possible use errors

Critical tasks require additional design attention.

---

## Quality Checklist

Before generating the task analysis verify:

□ User goals are defined.

□ Tasks are sequential.

□ User actions are complete.

□ System responses are described.

□ Decision points are identified.

□ Possible use errors are documented.

□ Safety-critical tasks are highlighted.

Only output the task analysis after all checks pass.
