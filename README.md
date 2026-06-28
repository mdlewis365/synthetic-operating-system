# Synthetic Operating System

Synthetic Operating System (Synthetic OS) is a private AI system architecture for governed, memory-aware, tool-aware cognitive workflows.

This public repository is documentation only. It describes the implemented architecture at a public-safe level, with Carter presented as the flagship implementation of the Synthetic OS pattern.

## What It Does

Synthetic OS organizes an AI runtime around:

- short-term conversation continuity
- long-term memory recall
- retrieval-augmented knowledge context
- governed prompt and context assembly
- optional operational logging and reporting
- specialized workflow modules such as engineering and ideation systems
- deterministic computation where a workflow requires bounded calculation

Carter is the primary implemented runtime in the private codebase. It exposes a general Carter console plus specialized workflows for Synthetic Ideation System (SIS) and Engineering Assistance System (EAS).

## Current Public Architecture

At a public level, Carter uses these implemented roles:

- CRM: short-term conversation recovery and active conversation continuity.
- AMS: long-term memory storage, indexing, and recall.
- RAG: retrieval of non-memory knowledge context from a separate knowledge corpus.
- PGM: governed context assembly for each request.
- LCM: selected operational conversation logging.
- MCM: deterministic math computation used by engineering workflows.
- EDR: compact engineering decision records for EAS.
- Governance Gate: deterministic engineering status classification for EAS.

Additional prompt-only or conceptual labels may exist in private material, but this repository does not present them as implemented public modules unless supported by active source behavior.

## Repository Contents

- `docs/`: architecture notes, memory model, governance model, lifecycle, privacy boundary, and roadmap.
- `diagrams/`: public-safe Mermaid diagrams.
- `examples/`: fictional sanitized examples.
- `public_specs/`: public module index, conceptual interface contracts, and non-goals.

## What Is Not Included

This repository does not include source code, private prompts, route names, function names, storage schemas, retrieval thresholds, model-routing details, credentials, secrets, raw memories, raw logs, raw OpReps, private governance logic, user data, authentication logic, deployment details, or cloneable implementation instructions.

## Safety Position

Synthetic OS output is decision support. It is not autonomous authority, a guarantee of correctness, a substitute for human review, or a replacement for qualified professional judgment in engineering, legal, medical, financial, safety-critical, or regulated contexts.

## Status

This documentation reflects the current private Carter/Synthetic OS implementation observed during the June 2026 public documentation staging pass.

## Verification Without Source Code

Because the production implementation is proprietary, this repository verifies the system through architecture docs, sanitized examples, validation traces, screenshots, and public-safe workflow descriptions.
