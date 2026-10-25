# Security Policy

## Scope

This repository enforces a strict security posture for all code, workflows, and contributions.

## Supported Versions

Security fixes are applied to the default branch.

## Prohibited Content

The following are not allowed in this repository:
- Malware, viruses, worms, trojans, ransomware, spyware, cryptominers, or backdoors
- Obfuscated or intentionally hidden payloads
- Unauthorized remote-execution logic or data exfiltration behavior
- Suspicious encoded payloads (including QR/encoded content intended to hide executable or malicious behavior)

Any contribution containing prohibited content will be rejected and may be reported.

## Secure Contribution Requirements

All contributions should:
- Use minimal required permissions and least-privilege defaults
- Avoid committing secrets, tokens, credentials, or private keys
- Keep dependencies pinned and sourced from trusted registries
- Include security rationale for workflow or permission changes

## Reporting a Vulnerability

Do not open public issues for security vulnerabilities.

Report privately using a GitHub private security advisory for this repository. Include:
- A clear description of the issue
- Steps to reproduce
- Potential impact
- Affected files/components
- Suggested mitigation or patch

Please allow reasonable time for investigation and remediation before public disclosure.
