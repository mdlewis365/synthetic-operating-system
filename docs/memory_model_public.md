# Public Memory Model

## Purpose

Carter uses memory to support continuity across long-running work. Memory is context, not automatic truth.

## Implemented Layers

CRM provides short-term conversation recovery. It loads, saves, trims, backs up, and resets active conversation state.

AMS provides long-term memory recall and selected memory writes. It builds or refreshes an internal recall index, retrieves relevant prior interactions, and limits retrieved content according to context budget.

RAG retrieves non-memory knowledge context from a separate knowledge corpus.

PGM assembles the current request, CRM context, AMS memory, and RAG knowledge into a governed generation context.

LCM writes selected operational conversation records when workflow settings call for logging.

## Memory Trust Boundary

Retrieved memory means a record was stored and retrieved. It does not prove that the recalled claim is externally verified, current, complete, or more authoritative than the user's latest instruction.

## Hygiene Behavior

The implementation shows bounded conversation trimming, backup behavior, recall-index hygiene, context-budget limits, and selective persistence. These are behaviors, not a separate public memory-ingestion module.

## OpRep Relationship

OpRep is publicly described as operational-report terminology around selected workflows. No standalone OpRep memory store is documented as current implementation.

## What Is Not Included

This document does not disclose database schemas, table names, vector collection names, embedding configuration, retrieval thresholds, similarity scores, storage paths, raw memories, private prompts, logs, or user data.
