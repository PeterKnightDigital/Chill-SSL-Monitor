# Changelog

All notable ChillSSL releases are documented here.

Product: [www.chillssl.com](https://www.chillssl.com) · App: [app.chillssl.com](https://app.chillssl.com)

Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Planned
- Ongoing launch offer (replacing seasonal campaign messaging)

---

## [1.0.1] - 2026-07-14

First patch release for **ChillSSL V1**.

### Fixed
- Post-signup auto-login no longer keeps a previously logged-in session — new customers land on the correct account after email verification and password setup.
- Expiry threshold eligibility counts now update immediately after adding or editing a custom threshold — no page reload required.
- Certificate scan results for IPv6 addresses are accepted correctly (previously some IPv6 hostnames were rejected during ingestion).
- Let's Encrypt Generation Y intermediates (YE1–YE3, YR1–YR3) now correctly display as "Let's Encrypt" rather than the raw intermediate code.

### Added
- Improved IPv6 certificate monitoring on a regular schedule.

---

## [1.0.0] - 2026

Initial production release of **ChillSSL V1**: certificate monitoring at [app.chillssl.com](https://app.chillssl.com), product site at [www.chillssl.com](https://www.chillssl.com), account signup with email verification, billing, and dashboard alerts.

[1.0.1]: https://github.com/PeterKnightDigital/ChillSSL-Issues/releases/tag/v1.0.1
[1.0.0]: https://github.com/PeterKnightDigital/ChillSSL-Issues/releases/tag/v1.0.0
