# Security Policy

## Repository Security Scope

This repository is a public architecture disclosure and documentation repository for **Synthetic OS** and **Carter**, the flagship implementation developed by **Synthetic OS Labs**.

It does **not** contain the production implementation of Synthetic OS, Carter, SIS, EAS, or related proprietary systems.

The following are intentionally excluded from this repository:

* Production source code
* API keys
* Credentials
* Environment files
* Deployment configuration
* Private prompts
* Model routing logic
* Internal orchestration logic
* Memory databases
* Vector stores
* Raw operational logs
* User conversation data
* Private governance logic
* Backend infrastructure details
* Cloud tunnel or access configuration
* Local machine paths or private system identifiers

If any of the above materials are discovered in this repository, they should be treated as a security issue and reported immediately.

---

## Supported Content

Because this repository is documentation-focused, the supported public content includes:

* High-level architecture descriptions
* Public diagrams
* Sanitized examples
* Public design principles
* Conceptual module descriptions
* Non-sensitive technical summaries
* Portfolio-oriented documentation

Security review for this repository focuses primarily on preventing accidental disclosure of proprietary, sensitive, private, or operationally dangerous information.

---

## Reporting a Security Issue

If you discover a security issue, accidental disclosure, exposed secret, private system detail, sensitive data, or other concern, please report it responsibly.

Preferred reporting methods:

1. Open a private security advisory through GitHub, if available.
2. Contact the repository maintainer directly through the maintainer’s public GitHub or professional contact channel.
3. If no private channel is available, open a minimal public issue that does **not** include the sensitive details. State only that a potential security disclosure has been identified and request maintainer contact.

Please do **not** publicly post:

* API keys
* Credentials
* Tokens
* Private prompts
* Raw logs
* Memory records
* User data
* Deployment details
* Exploit steps
* Sensitive file contents
* Internal system paths
* Proprietary implementation details

---

## Responsible Disclosure Expectations

When reporting a potential issue, please include only the minimum information needed to identify the concern safely.

Helpful information may include:

* The affected file name
* The affected section or line number
* A brief description of the concern
* Whether the issue appears to involve secrets, private data, proprietary logic, or operational infrastructure
* Suggested remediation, if applicable

Do not include copied secrets, private logs, memory data, credentials, or other sensitive contents in the report unless a secure private channel has been established.

---

## Types of Issues to Report

Please report any of the following:

* Accidental exposure of credentials, tokens, or API keys
* Accidental inclusion of `.env` or configuration files
* Accidental disclosure of production source code
* Raw Carter, SOS, SIS, or EAS logs
* Private operational reports
* Memory database contents
* Vector database contents
* User conversation data
* Local file paths containing private environment details
* Deployment or tunnel configuration
* Proprietary prompt chains
* Proprietary governance logic
* Proprietary orchestration logic
* Security-sensitive diagrams or implementation details
* Any content that could enable unauthorized access or replication of private systems

---

## Public Documentation Boundary

This repository is intended to describe Synthetic OS at a high level. Public documentation should remain conceptual and should avoid exposing implementation details that would compromise security, privacy, or intellectual property.

Acceptable public disclosure includes:

* General architecture diagrams
* Public-facing descriptions
* Sanitized examples
* Conceptual module summaries
* High-level design principles
* Non-sensitive workflow descriptions

Unacceptable public disclosure includes:

* Working production code
* Private backend logic
* Internal prompt templates
* Full governance directives
* Authentication details
* API integration secrets
* Model-provider credentials
* Operational logs
* Real user data
* Internal memory contents
* Private validation traces
* Infrastructure access details

---

## Secret Handling

Secrets must never be committed to this repository.

Examples of secrets include:

* API keys
* OAuth tokens
* Session tokens
* Login credentials
* Private certificates
* SSH keys
* Cloudflare tunnel credentials
* Database credentials
* Service account files
* Local environment files
* Model provider keys

If a secret is accidentally committed:

1. Remove it from the repository immediately.
2. Rotate or revoke the exposed secret.
3. Review commit history for additional exposure.
4. Consider rewriting repository history if appropriate.
5. Document the remediation privately.

Removing a secret from the latest commit is not sufficient if the secret remains available in commit history.

---

## Sanitization Requirements

All examples, diagrams, reports, traces, and screenshots must be sanitized before publication.

Sanitized materials must remove or fictionalize:

* User names, unless intentionally public
* Private conversations
* Email addresses
* Phone numbers
* Physical addresses
* Local file paths
* Machine names
* IP addresses
* Tokens
* API keys
* Database identifiers
* Internal job IDs
* Raw logs
* Private memory records
* Proprietary prompts
* Non-public model-routing details
* Any sensitive operational metadata

When in doubt, do not publish the material.

---

## Screenshots

Screenshots may be included only if they are reviewed and sanitized.

Before publishing screenshots, verify that they do not show:

* Login tokens
* Browser address bars containing private URLs
* API keys
* Localhost ports tied to private infrastructure
* File paths
* User data
* Internal logs
* Debug traces
* Private model names, if not intended for disclosure
* Operational identifiers
* Unreleased source code
* Proprietary prompts

If a screenshot cannot be safely sanitized, it should not be included.

---

## Dependency and Code Security

This repository is primarily documentation-oriented and is not intended to contain executable production code.

If example code is ever added, it must follow these rules:

* Example code must be non-production and clearly labeled as illustrative.
* Example code must not contain secrets.
* Example code must not connect to private infrastructure.
* Example code must not expose proprietary orchestration logic.
* Example code must not include private prompt templates.
* Example code must not include real memory data, logs, or user content.
* Dependencies should be minimal and reviewed before inclusion.

---

## AI Safety and Governance Disclosure

Synthetic OS includes governance-oriented design concepts. However, this repository does not disclose the full internal governance logic of the production system.

The following should not be published:

* Complete governance prompts
* Full directive sets
* Internal policy chains
* Safety bypass analysis
* Exploit-oriented testing details
* Private evaluation prompts
* Internal failure-mode catalogs
* Model-specific routing rules
* Production validation harnesses

Public documentation may discuss governance at a high level, including safety boundaries, human review, traceability, and response discipline.

---

## Intellectual Property Boundary

Synthetic OS, Carter, SIS, EAS, and related systems contain proprietary intellectual property developed by Synthetic OS Labs.

This repository is intended to disclose enough public architecture to support technical review, portfolio evaluation, and professional discussion while protecting the proprietary implementation.

Contributors and reviewers should not request or submit private implementation details, production prompts, internal logs, memory data, or other protected materials.

---

## Maintainer Review Checklist

Before publishing new content, maintainers should verify:

* [ ] No secrets are included.
* [ ] No `.env` files are included.
* [ ] No credentials are included.
* [ ] No production source code is included.
* [ ] No private prompts are included.
* [ ] No raw logs are included.
* [ ] No memory database contents are included.
* [ ] No vector store contents are included.
* [ ] No user conversation data is included.
* [ ] No private operational reports are included.
* [ ] No sensitive screenshots are included.
* [ ] No internal deployment details are included.
* [ ] No proprietary orchestration logic is included.
* [ ] All examples are sanitized.
* [ ] All diagrams are high-level and non-sensitive.
* [ ] The public/private boundary remains clear.

---

## Security Philosophy

Synthetic OS is designed around the belief that advanced AI systems should be governed, traceable, privacy-conscious, and human-centered.

Security for this public repository means protecting:

* Users
* Private data
* Operational infrastructure
* Proprietary system design
* Authentication boundaries
* Long-term research value
* Public trust in Synthetic OS Labs

Public transparency is valuable, but it must not compromise privacy, safety, or intellectual property.

---

## Final Note

If there is uncertainty about whether something is safe to publish, do not publish it.

When in doubt, sanitize further, summarize at a higher level, or keep the material private.
