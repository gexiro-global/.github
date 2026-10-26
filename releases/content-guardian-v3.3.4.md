# Content Guardian v3.3.4 — Release Notes (Free & Pro Editions)

**Publisher:** Gexiro Global Enterprises Ltd (`@gexiro`, Gibraltar)  
**Version:** `3.3.4`  
**Compatibility:** WordPress `6.2 – 7.1.3` | PHP `8.2+`  
**Product Page & Live WP-Admin Sandbox:** [https://gexiro.com/en/products/content-guardian-pro](https://gexiro.com/en/products/content-guardian-pro)

---

## Overview

**Content Guardian v3.3.4** delivers hardened commercial license enforcement, atomic server-side revocation & seat-ledger resilience, and refined Free-to-Pro edition handover across WordPress `6.2 – 7.1.3`.

Unlike legacy browser-only copy-protection scripts that leave `/wp-json/wp/v2/`, RSS/Atom feeds, oEmbed endpoints, and automated AI crawlers completely open, Content Guardian enforces layered controls across browser DOM boundaries, unauthenticated WordPress API endpoints, W3C machine-readable policy headers, and Cold-Vault Ed25519 signed updates.

---

## Key Highlights in v3.3.4

- **Server-Authoritative CGP2 Seat Enforcement:** Initial `CGP2.` token activations require live seat registration against `api.gexiro.com` (`1` / `5` / `25` domains), preventing offline multi-domain seat bypass while preserving cached resilience for already-bound production sites.
- **Deterministic Plan-Change & Subscription Continuity:** Supports scheduled `cancel_at_period_end` and deferred billing transitions without premature seat revocation during an active paid billing cycle, plus deterministic oldest-first seat retention upon tier downgrades.
- **Fail-Closed Revocation & Atomic Ledger Integrity:** Hardened `LOCK_EX` atomic state persistence and initialization sentinels across license issuance, seat release, and revocation checks.
- **Local Protection Continuity (Pro Annual Plans):** If an annual subscription ends naturally, all **21 local protection layers** on the installed version remain active on bound domains; an active subscription is required only for signed OTA updates and priority support.
- **Seamless Free-to-Pro Handover:** Installing Content Guardian Pro automatically migrates existing Content Guardian Free settings and cleanly deactivates the standalone Free plugin without database conflicts.

---

## Editions & Direct Verification

### 1. Content Guardian — Free Edition (`GPL-2.0-or-later`, $0)

4-module client-side content & media protection (`Right-Click`, `Text Selection`, `Clipboard Copy/Cut`, `Image Drag Shield`) with form/input safety (`INPUT`, `TEXTAREA`, `contenteditable` exclusions), logged-in administrator bypass, anonymized local-only telemetry (zero visitor IPs stored, zero external HTTP requests), and WordPress Core Privacy Guide integration.

- **Direct Download (v3.3.4):** [https://gexiro.com/content-guardian/content-guardian-free-latest.zip](https://gexiro.com/content-guardian/content-guardian-free-latest.zip)
- **SHA-256 Checksum:** `7625800b9f35f8d9195a24bd4291f6ef3f34801eadc9d85e8e66d979f575f4ba`

### 2. Content Guardian Pro (`v3.3.4` — Full 21-Layer Suite)

Adds server-side unauthenticated REST API (`/wp-json/wp/v2/`), RSS/Atom, oEmbed, and XML-RPC full-text truncation, W3C `TDM-Reservation: 1` + `/llms.txt` + `/.well-known/tdmrep.json` policy headers, opt-in 64-bit HMAC-SHA256 Zero-Width Forensic Canary v2 attribution, `[guardian_vault]` Closed Shadow-DOM isolation, HTML5 Canvas pixel watermarking, Cloudflare Edge-WAF auto-ban, runtime CVE-2026-109619 guard, and air-gapped Cold-Vault Ed25519 signed OTA updates.

| Plan | Domain Seats | Billing | Self-Service Seat Management |
| :--- | :---: | :---: | :---: |
| **PRO Personal** | `1` domain | `$39 / year` | Included (`#manage` portal) |
| **PRO Business** | `5` domains | `$79 / year` | Included (`#manage` portal) |
| **PRO Agency** | `25` domains | `$149 / year` | Included (`#manage` portal) |

- **Purchase, Free Download & Interactive WP-Admin Sandbox:** [https://gexiro.com/en/products/content-guardian-pro](https://gexiro.com/en/products/content-guardian-pro)
- **Self-Service License & Seat Portal:** [https://gexiro.com/en/products/content-guardian-pro#manage](https://gexiro.com/en/products/content-guardian-pro#manage)
- **External Attack-Surface & Compliance Visibility:** Pairs with [ChimeraScope](https://chimerascope.com) (`CRA`, `NIS2`, `DORA`, `ISO 27001`, `GDPR`).

---

© Gexiro Global Enterprises Ltd (Gibraltar) • `support@gexiro.com`
