# ChillSSL

**ChillSSL** monitors SSL/TLS certificates so teams know what’s expiring, what’s unhealthy, and what needs attention — before customers notice.

This public repository is the **changelog, releases, and issue tracker** for ChillSSL.

- Product site: [www.chillssl.com](https://www.chillssl.com)
- App: [app.chillssl.com](https://app.chillssl.com)
- Docs: [www.chillssl.com](https://www.chillssl.com) (product documentation)

The application source code is private. This tracker exists so customers and the community can report bugs, suggest improvements, and follow shipping progress.

---

## What's new

<!-- latest-release:start -->
### Latest release: [v1.0.1](https://github.com/PeterKnightDigital/ChillSSL-Issues/releases/tag/v1.0.1)

- Post-signup auto-login no longer keeps a previously logged-in session — new customers land on the correct account after email verification and password setup.
- Expiry threshold eligibility counts now update immediately after adding or editing a custom threshold — no page reload required.
- Certificate scan results for IPv6 addresses are accepted correctly.
- Let's Encrypt Generation Y intermediates (YE1–YE3, YR1–YR3) now correctly display as "Let's Encrypt".
- Improved IPv6 certificate monitoring on a regular schedule.

[Full changelog →](./CHANGELOG.md)
<!-- latest-release:end -->

---

## Before you submit an issue

- **Search first.** Your issue may already be reported or fixed. Check open and closed issues and the [changelog](./CHANGELOG.md).
- **One issue per report.** Don’t bundle unrelated problems.
- **No secrets.** Never paste API keys, session tokens, private keys, customer lists, or internal configuration.
- **No support tickets here.** Account/billing questions → contact options on [www.chillssl.com](https://www.chillssl.com).

---

## Reporting a bug

Include:

1. **Roughly when it happened** (date/time and timezone help).
2. **What you were doing** (e.g. adding a certificate, editing a threshold, viewing the dashboard).
3. **Expected behaviour** vs **actual behaviour**.
4. **Hostname type** if relevant (IPv4 / IPv6 / hostname) — you do **not** need to share customer domains if that is sensitive; a redacted example is fine.
5. Screenshots when they clarify the UI issue.

Please do **not** include:

- Auth tokens, cookies, or password reset links
- Full certificate PEMs / private keys
- Internal infrastructure details you may have inferred
- Other customers’ data

---

## Requesting a feature

Describe the problem you’re trying to solve and how ChillSSL fits into your workflow. Proposed solutions are welcome but optional.

---

## Issue labels

| Label | Meaning |
|---|---|
| `bug` | Something isn’t working correctly |
| `enhancement` | Improvement or new capability |
| `documentation` | Docs / changelog clarification |
| `question` | Clarification (may be closed with a pointer to docs) |
| `needs-info` | Waiting on details from the reporter |
| `confirmed` | Reproduced by maintainers |
| `wontfix` | Tracked but not planned |

---

## Security

If you believe you’ve found a security issue, **do not open a public issue**. See [SECURITY.md](./SECURITY.md).

---

## License / source

ChillSSL is a commercial product. This repository does not contain application source code. Please don’t ask for private implementation details, scanning internals, or infrastructure diagrams in issues — they won’t be shared here.
