# Changelog

All notable **Chill SSL** releases are documented here — SSL monitoring, SSL reminders, and SSL notification improvements shipping to [app.chillssl.com](https://app.chillssl.com).

- Product: [www.chillssl.com](https://www.chillssl.com)
- SSL Guides: [www.chillssl.com/guides](https://www.chillssl.com/guides/)
- SSL Glossary: [www.chillssl.com/ssl-glossary](https://www.chillssl.com/ssl-glossary/)
- Blog: [www.chillssl.com/blog](https://www.chillssl.com/blog/)
- Built by [Peter Knight Digital](https://www.peterknight.digital)

Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Planned
- Ongoing launch offer (replacing seasonal campaign messaging)

---

## [1.0.1] - 2026-07-14

First patch release for **Chill SSL V1**.

### Fixed
- Post-signup auto-login no longer keeps a previously logged-in session — new customers land on the correct account after email verification and password setup.
- Expiry threshold eligibility counts now update immediately after adding or editing a custom threshold — no page reload required.
- Certificate scan results for IPv6 addresses are accepted correctly (previously some IPv6 hostnames were rejected during ingestion).
- Let's Encrypt Generation Y intermediates (YE1–YE3, YR1–YR3) now correctly display as "Let's Encrypt" rather than the raw intermediate code.
- Notification thresholds that share the same day value (for example 1 day before and 1 day after) no longer cause list rendering glitches.
- App footer shows the product version; the Chill SSL marketing link points to [www.chillssl.com](https://www.chillssl.com).

### Added
- Improved IPv6 certificate monitoring on a regular schedule.

---

## [1.0.0] - 2026

Initial production release of **Chill SSL V1**: SSL monitor dashboard at [app.chillssl.com](https://app.chillssl.com), product site at [www.chillssl.com](https://www.chillssl.com), account signup with email verification, billing, SSL reminders, and notification alerts.

### Added
- Dedicated app experience at [app.chillssl.com](https://app.chillssl.com) with smart home redirect (signed-in users go to the SSL monitor dashboard; signed-out users go to sign-in). Marketing and docs stay on [www.chillssl.com](https://www.chillssl.com).
- SSL reminder thresholds that work with short-lived certificates, including 6-day lifespans.
- Core plan and Glacier (Launch Edition) pricing for SSL monitoring.

### Fixed
- Mobile checkout completes in the same browser window (no dependency on popup blockers).
- Checkout with multiple SSL Monitor packs no longer fails with a duplicate-price error.
- Checkout that includes add-ons correctly assigns the purchased plan after payment.
- Dashboard content no longer went blank due to a layout rendering bug.
- After a manual certificate check, status no longer stayed on “Unknown” until a full page refresh.
- Clicking the “Failing” status card correctly filters the certificate list.
- Account owners can open certificate details for their own monitored sites.
- In-app glossary links open the [SSL Glossary](https://www.chillssl.com/ssl-glossary/) on www in a new tab.
- Sidebar SSL usage counter and plan card colours display correctly in light and dark themes.
- Hardened the public support contact form against abusive input.

### Changed
- Sign-in uses a minimal logo-only header (no full marketing navigation).
- SSL reminder and change-alert emails use updated branding, personalized greetings, and show the actual certificate expiration date.
- Core plan copy clarifies that Chill SSL provides certificate monitoring (not “free certificates”).

[1.0.1]: https://github.com/PeterKnightDigital/ChillSSL-Issues/releases/tag/v1.0.1
[1.0.0]: https://github.com/PeterKnightDigital/ChillSSL-Issues/releases/tag/v1.0.0
