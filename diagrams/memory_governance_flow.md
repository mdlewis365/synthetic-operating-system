# Memory Governance Flow

```mermaid
flowchart LR
    Request[Current Request]
    CRM[Short-Term Conversation State]
    AMS[Long-Term Memory Recall]
    RAG[Knowledge Retrieval]
    Classify[Context and Evidence Calibration]
    PGM[Governed Context Assembly]
    Response[Response]
    Persist[Selective Persistence]

    Request --> PGM
    CRM --> PGM
    AMS --> Classify
    RAG --> Classify
    Classify --> PGM
    PGM --> Response
    Response --> Persist
```

## Public Interpretation

Memory is treated as retrieved context. It is not automatic proof, current truth, or authority over the user's latest instruction.

## What Is Not Included

This flow omits private governance prompts, recall scoring, database details, and raw memories.
