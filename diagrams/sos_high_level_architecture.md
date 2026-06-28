# Synthetic OS High-Level Architecture

```mermaid
flowchart TD
    U[User]
    Host[Authenticated Application Host]
    Carter[Carter Runtime]
    CRM[CRM Short-Term Continuity]
    AMS[AMS Long-Term Memory]
    RAG[RAG Knowledge Retrieval]
    PGM[PGM Governed Context Assembly]
    SIS[SIS Invention Workflow]
    EAS[EAS Engineering Workflow]
    MCM[MCM Deterministic Computation]
    GOV[EAS Governance and EDR]
    OUT[User-Facing Output]
    LOG[Selected Operational Logging]

    U --> Host
    Host --> Carter
    Carter --> CRM
    Carter --> PGM
    AMS --> PGM
    RAG --> PGM
    CRM --> PGM
    Carter --> SIS
    Carter --> EAS
    EAS --> MCM
    EAS --> GOV
    PGM --> OUT
    SIS --> OUT
    EAS --> OUT
    OUT --> LOG
```

## What Is Not Included

This is a conceptual public diagram. It omits routes, function names, storage layouts, credentials, deployment topology, prompt text, and model-routing internals.
