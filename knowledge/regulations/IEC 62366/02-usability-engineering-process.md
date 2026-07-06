# Usability Engineering Process

## Purpose

This document defines the usability engineering process described in IEC 62366-1.

The purpose is to integrate usability engineering into medical device development in order to reduce use-related risk.

This process should guide AI reasoning before interface design begins.

---

## Process Overview

Usability engineering is a continuous process rather than a single design activity.

The recommended process is:

1. Define Use Specification
2. Identify Intended Users
3. Identify Use Environment
4. Identify Use Scenarios
5. Perform Task Analysis
6. Identify Use Errors
7. Analyze Hazard-Related Use Scenarios
8. Define UI Risk Controls
9. Design the User Interface
10. Perform Usability Validation

Each step builds upon the previous one.

Skipping any step increases the probability of unsafe design.

---

## AI Design Workflow

Whenever AI receives a product design request, it should internally follow the same process:

Context

↓

User

↓

Environment

↓

Workflow

↓

Task

↓

Risk

↓

Interface

↓

Review

↓

Validation

The interface should never be generated before understanding the clinical context.

---

## Human Factors Integration

Human factors should be considered throughout the entire process.

Usability engineering is not an evaluation activity performed after design.

It is an integral part of product definition, interaction design, implementation, and verification.

---

## Relationship with Risk Management

The usability engineering process should exchange information continuously with ISO 14971 risk management activities.

Every identified use error should be evaluated for potential patient harm.

Every identified risk should influence interface design decisions.

---

## Application to Console

Typical Console process:

User

↓

Monitoring

↓

Alarm

↓

Decision

↓

Documentation

↓

Follow-up

Design should minimize interruptions while supporting continuous awareness.

---

## Application to PAD

Typical PAD process:

Patient

↓

Review

↓

Adjustment

↓

Confirmation

↓

Completion

Design should reduce interaction steps and improve bedside efficiency.

---

## AI Thinking Rules

Never begin interface generation before understanding:

- User
- Environment
- Workflow
- Task
- Risk

Always perform reasoning before visual design.

---

## References

IEC 62366-1

ISO 14971

ANSI/AAMI HE75
