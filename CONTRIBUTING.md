# Contributing

This repository accepts documentation improvements only.

## Contribution Rules

- Keep all content public-safe.
- Describe architecture conceptually unless a detail is already intentionally public.
- Do not add source code, prompt text, credentials, logs, raw user data, schemas, route names, private function names, or model-routing internals.
- Do not claim modules or workflows as current unless they are supported by the implemented codebase.
- Mark uncertain implementation details as "publicly described at a conceptual level" or omit them.
- Preserve the distinction between Carter, Synthetic OS, SIS, and EAS.

## Review Checklist

Before proposing changes, check that:

- claims are supported by current implementation evidence
- deprecated or legacy paths are not described as the primary current architecture
- DIM is not described as active unless the implementation actually shows an active module
- examples are fictional and sanitized
- safety limitations and human-review requirements remain visible

## What Is Not Included

Contributions must not include private source code, private prompts, secrets, credentials, operational logs, raw user content, database schemas, authentication details, deployment configuration, or proprietary governance logic.
