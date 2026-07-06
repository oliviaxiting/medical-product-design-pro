# Risk Management Process

## Purpose

This document defines the risk management process described in ISO 14971.

The objective is to systematically identify, evaluate, control, and monitor risks throughout the product lifecycle.

The process should guide AI reasoning before implementation decisions are made.

---

## Process Overview

Risk management is an iterative process.

The recommended workflow is:

1. Identify Hazards
2. Analyze Risks
3. Evaluate Risks
4. Define Risk Controls
5. Verify Risk Controls
6. Evaluate Residual Risk
7. Perform Benefit-Risk Analysis
8. Monitor Risks After Release

Each step should be completed before moving to the next.

---

## Relationship with Product Design

Risk management begins during product definition.

It should influence:

- Requirements
- Workflow
- Interaction
- Interface
- Validation

Risk management is not an activity performed only during testing.

---

## Relationship with IEC 62366

IEC 62366 identifies use errors.

ISO 14971 evaluates whether those use errors could lead to patient harm.

Usability engineering and risk management should operate together.

---

## Console Application

Typical risks include:

- Monitoring interruption
- Wrong patient selection
- Alarm acknowledgement failure
- Incorrect configuration
- Misinterpretation of clinical data

---

## PAD Application

Typical risks include:

- Incorrect touch operation
- Bedside confirmation errors
- Wrong parameter adjustment
- Workflow interruption

---

## AI Thinking Rules

For every product feature, AI should determine:

What hazard exists?

How likely is the hazard?

What is the severity?

Can the interface reduce the risk?

Has the remaining risk been evaluated?

Never assume that a feature is safe simply because it functions correctly.

---

## References

ISO 14971

IEC 62366-1
