# Validation and Observability

## Validation Layers

The current implementation includes several validation behaviors:

- required user-input checks for SIS and EAS submissions
- allowed-model validation for user-selected models
- strict structured-plan parsing and validation in EAS
- deterministic MCM request validation before computation
- MCM run-health summaries for executed calculations
- Engineering Decision Record validation
- final report sanitation to remove internal payloads and overclaiming

## Observability

Publicly described observability includes:

- asynchronous job status
- progress-stage labels
- final result retrieval
- compact MCM run-health summaries
- governance summaries
- evidence-basis summaries
- selected operational logging

## OpRep

OpRep is public-safe operational-report terminology. Public examples show sanitized operational summaries only, not raw logs or raw job artifacts.

## What Is Not Included

This document does not publish raw operational logs, raw job files, debug payloads, internal JSON schemas, route names, function names, local paths, model identifiers, or provider telemetry.
