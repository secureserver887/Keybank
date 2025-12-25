# Security Policy

## Supported Versions

This project follows a policy of providing security fixes for the latest minor release of each supported major version.

| Version | Supported |
| ------- | --------- |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x: |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x: |

If you are using an unsupported version, upgrade to a supported release as soon as possible. If you need long-term support for a specific release, contact the maintainers to discuss options.

## Reporting a Vulnerability

Please report suspected vulnerabilities privately so we can investigate and coordinate a fix before public disclosure.

Preferred contact methods (in order):
1. Email: security@YOUR_DOMAIN (replace with your preferred security email)
2. GitHub: Open a private security advisory for this repository (recommended)
3. PGP: If you prefer encrypted reports, use the project's PGP key:
   - PGP Key: <replace-with-key-or-fingerprint>

When reporting, please include:
- A clear summary of the issue.
- Affected versions and environments.
- Steps to reproduce (minimal reproducer, PoC, logs, or sample code).
- Impact (what an attacker can do).
- Any suggested mitigation or fix, if known.

Do not include sensitive data (passwords, private keys, personal data) in initial reports.

## Response and Triage

We aim to acknowledge reports within 72 hours of receipt. Triage and initial classification (severity, exploitability, affected components) will typically occur within 7 days. Timeline for remediation depends on severity and complexity, but typical targets are:
- Critical (remote code execution, large-scale data exposure): patch and advisory within 30 days, or coordinated timeline if a public fix cannot be provided faster.
- High: patch within 60 days or coordinated timeline.
- Medium/Low: patch in the normal release cycle; we'll provide updates as we make progress.

If we need more information, we will request it from the reporter. If a fix will take longer, we will propose a mitigation or temporary workaround.

## Disclosure Policy

We follow coordinated disclosure. The reporter and maintainers will agree on:
- An embargo period (time between fix availability and public disclosure).
- The content of the advisory.
- Credit for the reporter (unless they request anonymity).

We will request CVE assignment for confirmed vulnerabilities that meet the criteria. Public advisories will include affected versions, fixed versions, CVE IDs (when available), severity rating, and mitigation steps.

## Security Fix Process

1. Verify and reproduce the issue.
2. Develop and test a fix on a private branch.
3. Prepare a release containing the fix and any migration notes.
4. Publish the fixed release and a security advisory with details and CVE (as applicable).
5. Coordinate public disclosure with the reporter if under embargo.

## Safe Harbor

We welcome responsible security research. Security researchers acting in good faith to report vulnerabilities following this policy will not be prosecuted or sanctioned. Do not probe or access data you do not own; avoid disruptive testing on production systems without prior consent.

## Reporting Badges & Acknowledgements

We appreciate responsible disclosure. Unless you request anonymity, we will credit contributors in security advisories and release notes.

## Additional Resources & Contact

- Preferred contact email: security@YOUR_DOMAIN (replace with the actual contact)
- GitHub Security Advisories: https://github.com/secureserver887/Keybank/security/advisories
- PGP key (optional): <insert fingerprint>

If you're unsure how to report or need help preparing a reproducible test case, open an issue titled "SECURITY: request for help" and mark it private / contact via the security email above.

---

Thank you for helping keep Keybank secure. If you found a problem, please report it privately so we can address it quickly.
