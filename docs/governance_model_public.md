# Governance Model

## Purpose

Synthetic OS governance keeps generated output aligned with current instructions, retrieved context, workflow constraints, evidence boundaries, and human-review requirements.

## Public Governance Roles

PGM governs request interpretation and context assembly. It is the public-level place where current user input, memory, retrieved knowledge, and prior conversation are combined before generation.

EAS has an additional deterministic Governance Gate. It classifies engineering decision status from MCM run state, run-health signals, risk classification, mode, and decision-record summaries.

## EAS Governance Status Families

Publicly described status families include:

- deterministic computation not required
- computed and criteria passed
- computed selected solution passed
- computed with failed criteria
- computed with unknowns
- computed screening pass
- computed screening found no viable option
- computed diagnostic result
- partial result
- needs human review
- unsupported deterministic computation
- system error
- unknown

## Human Review

High-risk engineering categories require human review. Partial, unsupported, needs-review, and error states must not be presented as certified results.

## What Is Not Included

This document does not publish private governance prompts, exact decision logic, keyword lists, scoring internals, model instructions, route names, source code, or raw governance payloads.
