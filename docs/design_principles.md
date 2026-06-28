# Design Principles

## Public Principles

- Governed context before generation: requests are interpreted through memory, retrieval, and workflow constraints.
- Retrieval separation: long-term memory and knowledge retrieval are distinct sources.
- Selective persistence: internal planning artifacts are not automatically durable memories.
- Public/private boundary: architecture can be described without publishing cloneable internals.
- Deterministic support where needed: EAS uses MCM for bounded engineering calculation rather than relying only on free-form language output.
- Human review: advisory output remains subject to domain expert review.
- Evidence discipline: engineering reports distinguish uploaded source evidence, computed values, assumptions, and missing information.

## Anti-Goals

Synthetic OS is not presented as consciousness, AGI, perfect recall, guaranteed correctness, autonomous authority, or a replacement for human expertise.

## What Is Not Included

The design principles do not include private governance prompts, exact policy text, scoring rules, storage layouts, model-routing logic, or implementation instructions.
