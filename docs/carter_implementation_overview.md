# Carter Implementation Overview

## Role

Carter is the primary implemented runtime for Synthetic OS. It combines the general Carter console with specialized SIS and EAS workflows.

## Public Behavior

Carter supports:

- authenticated access to role-specific workflows
- model selection from an allowed set
- asynchronous job execution
- streaming or recoverable result handling
- governed context assembly before generation
- optional file-aware request handling for supported workflows
- selected persistence to conversation state, long-term memory, and operational logging

## Workflow Families

General Carter requests use the standard governed request path. SIS requests use structured scientist inputs to create an invention-vector prompt. EAS requests use a staged engineering workflow that can plan computation, invoke deterministic MCM, classify governance status, and generate a final advisory report.

## Persistence Boundary

The implementation distinguishes between internal intermediate stages and user-facing results. For example, the EAS first-stage planning output is not persisted as normal long-term conversation memory, while the final user-facing report can be persisted through the normal Carter memory and logging path.

## What Is Not Included

This document does not expose backend routes, function names, source filenames, private prompts, provider calls, API keys, session internals, job-store internals, raw reports, raw logs, or model-routing details.
