# Architecture Overview

## Purpose

Synthetic OS is an architecture for governed AI workflows that need continuity, retrieval, operational traceability, and task-specific modules. Carter is the flagship implementation in the current private codebase.

## High-Level Shape

The current implemented system can be publicly described as:

1. An authenticated application host presents Carter and specialized modules.
2. A user submits a request through the Carter console, SIS, or EAS.
3. Carter assembles context from short-term conversation state, long-term memory, retrieved knowledge, and the current request.
4. A model response is generated through a selected allowed model.
5. Selected workflows persist user-facing results to conversation state, long-term memory, and operational logs.
6. EAS can additionally run deterministic computation, governance classification, evidence mapping, and an engineering advisory report workflow.

## Implemented Public Modules

- CRM: active conversation continuity.
- AMS: long-term memory recall and selected memory writes.
- RAG: separate knowledge retrieval.
- PGM: governed context assembly.
- LCM: selected operational logging.
- MCM: deterministic math computation for engineering workflows.
- EDR: compact decision-record summary for EAS.
- Governance Gate: bounded status classification for EAS reports.

## Current Specialized Systems

- SIS: a governed invention-vector workflow built around a Scientist Input Module.
- EAS: a staged engineering assistance workflow with optional deterministic computation and human-review gating.

## What Is Not Included

This overview does not include private prompts, implementation paths, route names, function names, authentication logic, model-routing internals, storage schemas, retrieval thresholds, raw logs, raw memories, raw OpReps, or deployment details.
