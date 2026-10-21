# Security policy

## Supported versions

Only the latest release of each public repository is supported.

## Reporting a vulnerability

Do not open a public issue for a suspected vulnerability.

Use GitHub's private vulnerability reporting on the affected repository: **Security** → **Advisories** → **Report a vulnerability**. If that is unavailable, email [engineering@brainforge.ai](mailto:engineering@brainforge.ai).

Include:

- The repository and version.
- Steps to reproduce, or a minimal proof of concept.
- The impact you believe it has.

We aim to acknowledge a report within two business days and to agree a disclosure timeline with you.

## Scope

Our public accelerators are read-only by design. Reports that a tool writes to a customer system, exfiltrates data, exceeds its documented permissions, or sends data to an undeclared endpoint are in scope.

Out of scope: findings in vendored third-party code that are already public upstream, and issues that require a modified local build.
