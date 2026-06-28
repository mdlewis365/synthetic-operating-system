# Public Interface Contracts

## Carter Request Contract

Publicly, a Carter request contains:

- authenticated access context
- a user prompt
- optional selected model from an allowed set
- optional supporting files for workflows that support files

Publicly, a Carter result contains:

- job status
- user-facing output or error state
- selected workflow metadata when applicable

## SIS Contract

SIS accepts required invention-vector fields, optional invention-control fields, selected invention mode, and selected allowed model. It returns a job and later a structured concept output for human review.

## EAS Contract

EAS accepts an engineering problem, optional supporting files, and a help mode. It returns a staged engineering advisory result that may include deterministic computation status, governance status, evidence basis, and human-review requirements.

## MCM Contract

MCM is publicly described as receiving a bounded computation plan and returning structured computation status, outputs, diagnostics, constraints, and run-health summary.

## What Is Not Included

This document does not expose exact JSON schemas, route names, request fields beyond public concepts, function names, validation logic, prompt text, raw payloads, or implementation contracts sufficient to clone the private runtime.
