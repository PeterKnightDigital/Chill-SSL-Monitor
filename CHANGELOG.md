# Changelog

All notable **Chill SSL** releases are documented here — SSL monitoring, SSL reminders, and SSL notification improvements shipping to [app.chillssl.com](https://app.chillssl.com).

- Product: [www.chillssl.com](https://www.chillssl.com)
- SSL Guides: [www.chillssl.com/guides](https://www.chillssl.com/guides/)
- SSL Glossary: [www.chillssl.com/ssl-glossary](https://www.chillssl.com/ssl-glossary/)
- Blog: [www.chillssl.com/blog](https://www.chillssl.com/blog/)
- Built by [Peter Knight Digital](https://www.peterknight.digital)

Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/). Notes are written for customers — benefit first, plain language.

## [Unreleased]

### Planned
- Ongoing launch offer (replacing seasonal campaign messaging)

---

## [1.0.1] - 2026-07-14

First patch release for **Chill SSL V1**.

### Improved
- Clearer SSL reminder setup — eligibility counts (“how many certificates qualify”) update as soon as you save a custom threshold, with no page reload.
- Cleaner issuer labels — Let's Encrypt Generation Y intermediates (YE1–YE3, YR1–YR3) show as “Let's Encrypt” instead of raw intermediate codes.
- Steadier notification-threshold lists when you use the same day value twice (for example 1 day before and 1 day after).
- Handy product version in the app footer, with a direct link to [www.chillssl.com](https://www.chillssl.com).
- Broader IPv6 certificate monitoring on a regular schedule — more of your IPv6 hosts stay covered automatically.

### Fixed
- Smoother signup hand-off — new customers land on the correct account after email verification and password setup (avoids staying on a previously signed-in session).
- More reliable IPv6 monitoring — certificate scan results for IPv6 addresses are accepted correctly so those hosts keep updating in your SSL monitor.

---

## [1.0.0] - 2026

Formal **Chill SSL V1** marketing release: SSL monitor dashboard at [app.chillssl.com](https://app.chillssl.com), product site at [www.chillssl.com](https://www.chillssl.com), account signup with email verification, billing, SSL reminders, and notification alerts.

### Added
- Dedicated app experience at [app.chillssl.com](https://app.chillssl.com) with smart home redirect (signed-in → SSL monitor dashboard; signed-out → sign-in). Marketing, [SSL Guides](https://www.chillssl.com/guides/), [SSL Glossary](https://www.chillssl.com/ssl-glossary/), and [blog](https://www.chillssl.com/blog/) stay on www.
- SSL reminder thresholds that understand short-lived certificates, including 6-day lifespans.
- Core plan and Glacier (Launch Edition) pricing for SSL monitoring.

### Improved
- Faster mobile checkout — completes in the same browser window (no popup dance).
- Clearer plan purchase flow when you add multiple SSL Monitor packs or checkout add-ons — the plan you paid for is what you get.
- Quicker feedback after a manual certificate check — status updates without a full page refresh.
- One-click filtering from the “Failing” status card straight into the matching certificates.
- Useful in-app links to the [SSL Glossary](https://www.chillssl.com/ssl-glossary/) (open on www in a new tab).
- Polished light and dark themes for the sidebar SSL usage counter and plan card colours.
- Clearer SSL reminder and change-alert emails — updated branding, personalized greetings, and the actual expiration date.
- Clearer Core plan copy: Chill SSL is certificate monitoring (not “free certificates”).
- Calmer sign-in screen — logo-only header so you can focus on getting in.

### Fixed
- More reliable SSL monitor layout — main dashboard content stays visible while you work.
- Account owners can open certificate details for their own monitored sites without friction.
- Stronger public support contact form against abusive input.

---

## [0.9.0] - 2025-07 (Public launch era)

**Chill SSL** launched publicly around **July 2025**. Before formal V1 versioning (`1.0.0`), the product shipped a large stream of improvements — far more than we list here. This section is a **thematic summary** of that launch era, not an exhaustive bug list.

### Improved
- **SSL monitor UX** — dashboard clarity, status at a glance, filtering, and day-to-day certificate management that feels faster and less noisy.
- **SSL reminders** — more useful expiry reminder workflows and notification preferences so alerts arrive when they help, not when they overwhelm.
- **SSL notifications** — clearer status-change and digest-style messaging as the notification system matured.
- **Checkout & billing** — smoother path from pricing to a working subscription and SSL monitor access.
- **Short-lived certificate readiness** — product direction toward 6-day / automated renewals, not only year-long certs.
- **Light & dark experience** — ongoing UI polish so the SSL monitor is comfortable in either theme.
- **Reliability & trust** — thousands of under-the-hood fixes and refinements across monitoring, accounts, and alerts that made the launch-era product progressively more dependable.

### Added
- Public product presence at [www.chillssl.com](https://www.chillssl.com) with growing [SSL Guides](https://www.chillssl.com/guides/), [SSL Glossary](https://www.chillssl.com/ssl-glossary/), and [blog](https://www.chillssl.com/blog/) content.
- Customer SSL monitoring app experience leading into the formal V1 app at [app.chillssl.com](https://app.chillssl.com).

> Tip for readers: from `1.0.0` onward we publish numbered releases with concrete, customer-facing notes. Pre-1.0.0 work is summarised here so the story of Chill SSL doesn’t look like it started in 2026.

[1.0.1]: https://github.com/PeterKnightDigital/ChillSSL-Issues/releases/tag/v1.0.1
[1.0.0]: https://github.com/PeterKnightDigital/ChillSSL-Issues/releases/tag/v1.0.0
[0.9.0]: https://github.com/PeterKnightDigital/ChillSSL-Issues/releases/tag/v0.9.0
