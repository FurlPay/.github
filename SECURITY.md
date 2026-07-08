# Security Policy

FurlPay builds payment infrastructure. We take every report seriously and we appreciate the time security researchers invest in keeping users safe.

## Reporting a vulnerability

**Do not open a public issue for security reports.**

Preferred channel — GitHub private vulnerability reporting:

1. Go to the affected repository's **Security** tab.
2. Click **Report a vulnerability** to open a private advisory draft.

Alternative: email **security@furlpay.com** with the details below. If you need to share secrets or proof-of-concept material, say so in the first message and we will arrange a secure channel — never submit secrets through issues, discussions, or forms.

Please include:

- Affected repository, package, and version (or commit SHA).
- A description of the issue and its impact.
- Step-by-step reproduction (a minimal PoC is ideal).
- Any suggested remediation, if you have one.

## What to expect

| Stage | Target |
| --- | --- |
| Acknowledgement | within 48 hours |
| Triage decision (accepted / declined / more info) | within 5 business days |
| Fix or mitigation for accepted reports | within 90 days, faster for critical issues |
| Credit | with your permission, in the advisory and release notes |

## Scope

In scope:

- All repositories in the `FurlPay` GitHub organization.
- Published packages: `@furlpay/*` on npm, `furlpay*` on PyPI.
- The hosted service at `furlpay.com` and its APIs.

Out of scope:

- Denial-of-service and volumetric attacks.
- Findings that require a compromised device or physical access.
- Reports from automated scanners without a demonstrated impact.
- Social engineering of FurlPay staff or users.

## Safe harbor

We will not pursue legal action against researchers who: act in good faith, avoid privacy violations and data destruction, do not degrade the service for others, use only accounts they own for testing, and give us a reasonable window to remediate before public disclosure.

## Supported versions

Only the latest published version of each package receives security fixes. Pin to the newest release and update promptly when advisories are published.
