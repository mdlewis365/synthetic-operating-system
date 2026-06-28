# Sanitized Memory Lifecycle

## Example

1. A user gives Carter a public documentation task.
2. CRM stores active conversation context for the session.
3. AMS retrieves prior relevant public-documentation context, if available.
4. RAG retrieves separate project knowledge, if available.
5. PGM uses all context under governance.
6. Carter produces a final public-safe response.
7. The final user-facing result may be written to CRM, AMS, and LCM depending on workflow settings.

## Public Safety Notes

Memory recall is contextual support. It does not prove that a recalled claim is true, current, or complete.

## What Is Not Included

This example excludes real memory records, database details, recall thresholds, embedding details, raw conversation history, and private prompt content.
