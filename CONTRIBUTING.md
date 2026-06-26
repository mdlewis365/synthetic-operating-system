# Contributing to Synthetic OS

Thank you for your interest in contributing to the public Synthetic OS repository.

This repository provides a public architecture overview of **Synthetic OS** and **Carter**, the flagship implementation developed by **Synthetic OS Labs**. It is intended for technical review, documentation, portfolio evaluation, and high-level system discussion.

This repository is **not** the production source-code repository for Synthetic OS, Carter, SIS, EAS, or related proprietary systems.

---

## Contribution Scope

Contributions are welcome when they improve the clarity, quality, accuracy, or usefulness of the public documentation.

Appropriate contributions include:

* Documentation improvements
* Typo and grammar fixes
* Diagram improvements
* Clarifications to public architecture descriptions
* Better explanations of design principles
* Sanitized example improvements
* Public glossary additions
* Repository organization improvements
* Suggestions for clearer public/private boundaries
* Accessibility and readability improvements

Contributions should remain conceptual, sanitized, and non-sensitive.

---

## What Not to Contribute

Please do **not** submit:

* Production source code
* Private prompts
* Internal prompt chains
* Model routing logic
* Proprietary orchestration logic
* API keys
* Credentials
* `.env` files
* Local configuration files
* Memory databases
* Vector stores
* Raw operational logs
* Real user conversation data
* Private Carter, SOS, SIS, or EAS traces
* Internal validation harnesses
* Deployment details
* Cloud tunnel configuration
* Private governance logic
* Security-sensitive implementation details
* Screenshots containing private or sensitive information

If you are unsure whether something is safe to contribute, do not include it in a pull request.

---

## Public Documentation Boundary

This repository should describe Synthetic OS at the architectural level.

Acceptable public content includes:

* High-level system descriptions
* Public-facing architecture diagrams
* Conceptual module summaries
* Sanitized examples
* Non-sensitive design explanations
* Portfolio-oriented technical documentation

Unacceptable public content includes:

* Reproducible production internals
* Full implementation details
* Private system prompts
* Raw logs
* Internal memory records
* Real operational reports
* Sensitive configuration details
* Authentication or deployment information

The purpose of this repository is to communicate the engineering direction and design philosophy of Synthetic OS while protecting the proprietary implementation.

---

## Contribution Workflow

To contribute:

1. Fork the repository.
2. Create a new branch for your change.
3. Make your edits.
4. Review your changes for security and privacy issues.
5. Open a pull request with a clear description of what changed and why.

Suggested branch names:

```text
docs/improve-architecture-overview
docs/fix-readme-typos
docs/add-glossary-terms
diagrams/update-request-lifecycle
examples/improve-sanitized-oprep
```

---

## Pull Request Guidelines

Pull requests should:

* Have a clear title.
* Explain the purpose of the change.
* Identify which file or section was changed.
* Avoid unnecessary scope expansion.
* Preserve the public/private boundary.
* Avoid introducing sensitive or proprietary details.
* Keep examples sanitized.
* Keep language professional and precise.

A good pull request description should answer:

```text
What changed?
Why was the change needed?
Does this change introduce any sensitive or proprietary information?
Were examples, screenshots, or diagrams reviewed for sanitization?
```

---

## Documentation Style

Documentation should be:

* Clear
* Professional
* Concise
* Technically credible
* Accessible to engineers, recruiters, and technical reviewers
* Honest about what is public and what remains private

Avoid exaggerated claims, hype language, or unsupported statements.

Preferred language:

```text
Synthetic OS is an experimental AI systems architecture...
Carter is the flagship implementation...
This repository provides a public architecture overview...
Production implementation details are intentionally excluded...
```

Avoid language such as:

```text
Fully autonomous artificial general intelligence
Conscious AI system
Complete replacement for human engineers
Unbreakable safety system
Guaranteed reliable reasoning
```

Synthetic OS should be presented as a serious engineering and R&D project.

---

## Diagrams

Diagrams are welcome when they improve understanding.

Preferred diagram format:

```text
Mermaid markdown diagrams
```

Diagrams should remain high-level and should not expose:

* Internal routing logic
* Exact production workflows
* Private authentication boundaries
* Deployment infrastructure
* Secret names
* Internal hostnames
* Private APIs
* Sensitive module internals

Good diagram topics include:

* High-level architecture
* Request lifecycle
* Memory and retrieval flow
* Governance flow
* Operational reporting flow
* Public module relationships

---

## Sanitized Examples

Examples are welcome if they are clearly sanitized.

Sanitized examples may include:

* Fictional user requests
* Fictional operational summaries
* Generalized governance traces
* Simplified request lifecycles
* Mock memory-retrieval summaries
* Non-sensitive advisory outputs

Sanitized examples must not include:

* Real user conversations
* Real private memories
* Raw Carter output logs
* Production file paths
* Local machine names
* Internal job IDs
* API traces
* Private prompts
* Full internal validation traces
* Proprietary engineering logic

When creating examples, use fictionalized data and clearly mark the example as sanitized.

---

## Security Review Before Submitting

Before opening a pull request, review your changes using this checklist:

* [ ] No secrets are included.
* [ ] No credentials are included.
* [ ] No `.env` files are included.
* [ ] No private prompts are included.
* [ ] No production source code is included.
* [ ] No raw logs are included.
* [ ] No memory database content is included.
* [ ] No vector store content is included.
* [ ] No user conversation data is included.
* [ ] No sensitive screenshots are included.
* [ ] No deployment configuration is included.
* [ ] No proprietary orchestration logic is included.
* [ ] Examples are fictionalized or sanitized.
* [ ] Diagrams remain high-level.
* [ ] The public/private boundary remains clear.

See `SECURITY.md` for additional guidance.

---

## Issues

Issues may be opened for:

* Documentation corrections
* Clarification requests
* Suggested public architecture improvements
* Broken links
* Typographical errors
* Diagram improvements
* Requests for additional public explanations
* Security concerns, if reported safely

Do not use public issues to post sensitive information.

If an issue involves a possible security disclosure, follow the guidance in `SECURITY.md`.

---

## Code Contributions

This repository is primarily documentation-oriented.

Executable code contributions are generally out of scope unless the maintainer explicitly requests them.

If illustrative code is ever added, it must be:

* Non-production
* Clearly labeled as example code
* Free of secrets
* Free of private prompts
* Free of proprietary orchestration logic
* Unable to connect to private Synthetic OS infrastructure
* Safe for public review

---

## Intellectual Property Notice

Synthetic OS, Carter, SIS, EAS, and related systems contain proprietary intellectual property developed by Synthetic OS Labs.

By contributing to this public repository, you agree that your contribution is intended for public documentation, review, and discussion. You should not submit confidential, proprietary, or third-party restricted material.

The production implementation remains private unless explicitly released by Synthetic OS Labs.

---

## Maintainer Review Priorities

Maintainers will review contributions for:

* Technical clarity
* Documentation quality
* Accuracy
* Professional tone
* Security
* Privacy
* Public/private boundary compliance
* Consistency with the purpose of the repository

Pull requests may be declined if they expose sensitive information, overstate system capabilities, introduce unclear claims, or conflict with the repository’s documentation-only purpose.

---

## Final Guidance

Contributions should help make the public Synthetic OS repository more understandable, professional, and trustworthy.

When in doubt:

* Keep it high-level.
* Keep it sanitized.
* Keep it honest.
* Keep proprietary details private.
