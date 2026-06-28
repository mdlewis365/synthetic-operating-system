# Security and Privacy Boundary

## Public Boundary

This repository documents architecture without exposing the private implementation.

Safe to describe:

- module roles at a high level
- request lifecycle at a conceptual level
- public limitations and human-review requirements
- sanitized fictional examples
- conceptual diagrams

Not safe to disclose:

- source code
- prompt text
- route names and private function names
- credentials, secrets, and environment variables
- authentication/session logic
- model-routing internals
- raw logs, raw memories, raw OpReps, and raw job artifacts
- database schemas and storage details
- proprietary governance logic
- cloneable implementation details

## Data Handling Position

Public examples must be fictional. They must not derive from private user requests, operational logs, uploaded files, job-store payloads, or memory records.

## Human Review Boundary

Carter and Synthetic OS produce decision support. Their outputs remain subject to human review, especially for engineering, safety, legal, medical, financial, regulated, or operationally consequential work.
