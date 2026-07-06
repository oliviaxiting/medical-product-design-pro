# Task Analysis

## Purpose

This document defines how to analyze clinical tasks according to IEC 62366-1.

The objective is to understand every action required to complete a clinical workflow and identify opportunities to improve safety, efficiency, and usability.

Task analysis should always precede interface design.

---

## Human Factors Principle

Interfaces should support clinical tasks rather than software functions.

Every interaction should correspond to a real clinical objective.

---

## Task Structure

Each task should include:

- Goal
- Trigger
- Preconditions
- User actions
- System responses
- Possible use errors
- Completion criteria

---

## Task Decomposition

Break every workflow into sequential steps.

Example:

Open Patient

↓

Review Status

↓

Identify Problem

↓

Take Action

↓

Confirm Result

↓

Complete Task

Each step should have a clear purpose.

---

## Task Characteristics

Evaluate each task for:

- Frequency
- Criticality
- Complexity
- Duration
- Cognitive workload
- Error likelihood

High-risk tasks require additional usability consideration.

---

## Console Application

Typical tasks:

- Monitor multiple patients
- Review alarms
- Configure devices
- Analyze trends
- Document findings

---

## PAD Application

Typical tasks:

- Review patient status
- Confirm alarms
- Adjust parameters
- Perform bedside verification

---

## AI Thinking Rules

Before generating any interface:

Identify the user's goal.

Break the goal into individual tasks.

Evaluate each task separately.

Identify where use errors may occur.

Reduce unnecessary interaction steps.

Support task completion rather than feature discovery.

---

## References

IEC 62366-1

ANSI/AAMI HE75

ISO 14971
