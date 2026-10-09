# Security policy

## Reporting a vulnerability

Please report security problems privately, not in a public issue. Open the affected repository's
**Security** tab and choose **Report a vulnerability**. Only the maintainers can see the report.

Include the project and version, what an attacker could do, and the steps to reproduce it. We're a
small volunteer team; we aim to acknowledge a report within a week and will keep you updated until
it's resolved. We'll credit you in the release notes unless you'd rather we didn't.

## In scope

- Create Companion, OpenFlow, and the tools and scripts in our repositories.
- The integrity of firmware downloads: anything that could make OpenFlow fetch, accept or write an
  image other than the one its catalogue pins by hash.
- Secrets or personal data exposed in our repositories, releases or installers.

## Out of scope

- Vulnerabilities in Naya's own firmware, bootloader or NayaFlow. Naya can no longer ship fixes,
  and we don't publish ways to extract keys from a keyboard or bypass its protections. If you've
  found something that puts owners at risk, report it privately as above and we'll work out with
  you what can safely be said in public.
