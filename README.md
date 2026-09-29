# Hi, I'm Marvin Palencia 👋

**Python & web developer in Miramichi, New Brunswick, Canada.** I build websites, Stripe payment integrations and Python automations for small businesses, and I run my own product, [DeMark Studio](https://demarkstudio.ca).

- 🌐 Portfolio: **[marvin.demarkstudio.ca](https://marvin.demarkstudio.ca)** ([en español](https://marvin.demarkstudio.ca/es/))
- 💼 Hire me: [Upwork](https://www.upwork.com/freelancers/~012519d03b23b2c426) · [Fiverr](https://www.fiverr.com/marvin_pal) · [LinkedIn](https://www.linkedin.com/in/marvin-palencia-09129643b/)
- 🗣️ English & Spanish

### Open source

72 small, tested tools. Each one was run against my own live sites before publishing; the README shows that real output.

**SEO and crawling**

| Project | What it does |
|---|---|
| [site-seo-crawler](https://github.com/dreadmoreeee/site-seo-crawler) | Crawls your own site and reports technical SEO problems: broken links, redirects, titles, canonicals, hreflang, sitemap gaps, JSON-LD. 51 tests. |
| [sitemap-diff](https://github.com/dreadmoreeee/sitemap-diff) | Audit XML sitemaps (status, noindex, canonical, robots.txt conflicts, orphan pages) and diff them across a site migration |
| [hreflang-check](https://github.com/dreadmoreeee/hreflang-check) | Validate hreflang for multilingual sites: codes, return links, x-default, canonical conflicts, html lang |
| [indexability-check](https://github.com/dreadmoreeee/indexability-check) | Is each page indexable, and should it be? Robots, noindex, canonicals, sitemaps and their conflicts |
| [redirect-checker](https://github.com/dreadmoreeee/redirect-checker) | Verify redirect maps and canonical hosts: chains, loops, 302 vs 301, https downgrades, www and trailing slashes |
| [robots9309](https://github.com/dreadmoreeee/robots9309) | robots.txt matching per RFC 9309 (most specific rule wins, * and $ wildcards); fixes urllib.robotparser's first-match bug. 15 tests. |
| [local-business-schema](https://github.com/dreadmoreeee/local-business-schema) | Generate LocalBusiness JSON-LD and check structured data and NAP consistency across a site's pages |
| [og-card-check](https://github.com/dreadmoreeee/og-card-check) | See how your links look when shared: Open Graph, X cards and image checks with rendered card previews |
| [og-image-gen](https://github.com/dreadmoreeee/og-image-gen) | Generate 1200x630 social share images from templates with text fitting and a WCAG contrast check |
| [untranslated-check](https://github.com/dreadmoreeee/untranslated-check) | Find untranslated or mixed-language text on multilingual sites, and links that switch language |
| [readability-check](https://github.com/dreadmoreeee/readability-check) | Readability of web copy in English, French and Spanish with per-language formulas and the hardest sentences |
| [website-health-audit](https://github.com/dreadmoreeee/website-health-audit) | Ranks small-business websites from worst to best: expired or parked domains, spam takeovers, no HTTPS, not mobile-friendly, no online booking. Standard library only. |
| [soft-404-check](https://github.com/dreadmoreeee/soft-404-check) | Check how a site handles missing pages: real 404s vs soft 404s and redirects to home |
| [sitemap-gen](https://github.com/dreadmoreeee/sitemap-gen) | Generate XML sitemaps from a build folder (lastmod from git) or a polite crawl, with hreflang |
| [schema-lint](https://github.com/dreadmoreeee/schema-lint) | Validate structured data against the real schema.org vocabulary and Google rich-result requirements |
| [landing-page-check](https://github.com/dreadmoreeee/landing-page-check) | Check an ads landing page like paid traffic sees it: tracking kept, message match, CTA, speed, consent |
| [i18n-diff](https://github.com/dreadmoreeee/i18n-diff) | Compare translation files: missing keys, untranslated text, placeholder mismatches, French typography |

**Performance**

| Project | What it does |
|---|---|
| [web-vitals-lite](https://github.com/dreadmoreeee/web-vitals-lite) | Lab Core Web Vitals without Lighthouse: LCP, CLS, TBT, FCP, TTFB on throttled mobile and desktop, with CI budgets |
| [image-audit](https://github.com/dreadmoreeee/image-audit) | Find image bytes to save: oversized images, WebP/AVIF savings, lazy loading and LCP issues per device |
| [unused-code-audit](https://github.com/dreadmoreeee/unused-code-audit) | Measure unused JavaScript and CSS per page with Chromium coverage, render-blocking files and CI budgets |
| [cache-header-audit](https://github.com/dreadmoreeee/cache-header-audit) | Audit HTTP caching and compression of a page and its assets, with exact Caddy, nginx and Apache fixes |
| [visual-diff](https://github.com/dreadmoreeee/visual-diff) | Visual regression for websites: frozen-animation screenshots, masks, pixel diffs and an HTML report |
| [web-font-audit](https://github.com/dreadmoreeee/web-font-audit) | Audit web fonts: formats, font-display, preloads, unused @font-face and real subsetting savings |
| [http-protocol-check](https://github.com/dreadmoreeee/http-protocol-check) | Check HTTP/2, HTTP/3, accepted TLS versions, certificate chain, HSTS, compression and IPv6 |
| [image-optimizer](https://github.com/dreadmoreeee/image-optimizer) | Batch-optimize images: responsive widths, WebP/AVIF at the lowest quality above an SSIM threshold, srcset snippets |
| [font-subsetter](https://github.com/dreadmoreeee/font-subsetter) | Subset web fonts to the characters pages use, convert to WOFF2 and write @font-face with unicode-range |
| [critical-css](https://github.com/dreadmoreeee/critical-css) | Extract and inline above-the-fold CSS, load the rest without blocking, verified by pixel comparison |

**Security and privacy**

| Project | What it does |
|---|---|
| [security-headers-audit](https://github.com/dreadmoreeee/security-headers-audit) | Grade a site's HTTP security A-F (HSTS, CSP, framing, cookies, TLS) with the exact header to fix each finding |
| [csp-builder](https://github.com/dreadmoreeee/csp-builder) | Build a tight Content-Security-Policy from what pages really load, with hashes and a diff against your current policy |
| [script-inventory](https://github.com/dreadmoreeee/script-inventory) | Inventory every script a page runs: SRI verified, library versions with known advisories, mixed content, CSP hints |
| [consent-tracker-scan](https://github.com/dreadmoreeee/consent-tracker-scan) | Shows the cookies, storage and third-party trackers a website loads before the visitor consents (Quebec Law 25 / PIPEDA context). 110 tests. |
| [consent-banner-lite](https://github.com/dreadmoreeee/consent-banner-lite) | Dependency-free cookie consent banner (4.8 KB gzipped): equal Reject button, script blocking, Consent Mode v2, EN/FR/ES |
| [cookie-policy-gen](https://github.com/dreadmoreeee/cookie-policy-gen) | Generate an English/French cookie disclosure page from a real tracker scan, with a diff to keep it true |
| [security-txt](https://github.com/dreadmoreeee/security-txt) | Check and generate RFC 9116 security.txt files, with expiry watch and CI exit codes |
| [dns-health](https://github.com/dreadmoreeee/dns-health) | DNS health: nameservers, SOA, lame delegation, DNSSEC, CAA vs the real certificate, dangling CNAMEs |
| [email-dns-check](https://github.com/dreadmoreeee/email-dns-check) | Check SPF, DKIM, DMARC, MX, MTA-STS and TLS-RPT for a domain and get the exact DNS record to publish |
| [domain-ssl-watch](https://github.com/dreadmoreeee/domain-ssl-watch) | Watch TLS certificate expiry, domain registration (RDAP), DNS and HTTP for your domains, with cron exit codes and optional email/Telegram alerts |
| [form-spam-guard](https://github.com/dreadmoreeee/form-spam-guard) | Stop form spam without CAPTCHAs: honeypot, signed single-use time tokens, script and link filters, rate limiting |
| [contact-form-backend](https://github.com/dreadmoreeee/contact-form-backend) | Self-hosted contact form backend with CAPTCHA-free spam protection and SMTP delivery |
| [secret-scan-web](https://github.com/dreadmoreeee/secret-scan-web) | Find secrets leaked into what a site serves: JS bundles, source maps, exposed .env or .git files |
| [cors-check](https://github.com/dreadmoreeee/cors-check) | Test CORS with real requests: reflected origins, null, wildcard with credentials, look-alike origins |
| [log-redact](https://github.com/dreadmoreeee/log-redact) | Redact personal data and secrets from logs: emails, phones, cards, SIN, IPs, tokens, with pseudonyms |
| [compose-audit](https://github.com/dreadmoreeee/compose-audit) | Security audit of docker-compose files: privileged, docker.sock, open ports, secrets, root, limits |

**Accessibility and front-end quality**

| Project | What it does |
|---|---|
| [a11y-audit](https://github.com/dreadmoreeee/a11y-audit) | Accessibility audit: axe-core plus keyboard focus, 200% zoom and reduced-motion checks, grouped by WCAG criterion |
| [contrast-palette](https://github.com/dreadmoreeee/contrast-palette) | WCAG and APCA contrast, nearest passing colour in OKLCH, 50-950 palettes and a check of every text colour on a page |
| [form-audit](https://github.com/dreadmoreeee/form-audit) | Audit web forms read-only: labels, autocomplete, mobile input types, error wiring, touch targets |
| [html-lint](https://github.com/dreadmoreeee/html-lint) | Lint served HTML: duplicate ids, bad nesting, missing labels and alt, heading order, SARIF output for GitHub |
| [webmanifest-check](https://github.com/dreadmoreeee/webmanifest-check) | Check the web app manifest and real icon sizes, and generate the missing icons |
| [a11y-statement-gen](https://github.com/dreadmoreeee/a11y-statement-gen) | Honest English/French accessibility statements from an a11y-audit report, and progress between audits |

**Email**

| Project | What it does |
|---|---|
| [html-email-lint](https://github.com/dreadmoreeee/html-email-lint) | Lint HTML emails before sending: Gmail clipping, CSS support per client, links, dark mode, contrast, screenshots |
| [email-css-inliner](https://github.com/dreadmoreeee/email-css-inliner) | Dependency-free CSS inliner for HTML emails: real cascade, keeps @media and Outlook MSO comments |

**APIs, payments and business**

| Project | What it does |
|---|---|
| [site-api-mapper](https://github.com/dreadmoreeee/site-api-mapper) | Maps the HTTP/JSON API a website uses into an OpenAPI 3 spec + Markdown, from a HAR file, a passive headless capture or its JavaScript. Redacts secrets by default. 133 tests. |
| [openapi-lint](https://github.com/dreadmoreeee/openapi-lint) | Lint OpenAPI documents: operationIds, error responses, security, examples, pagination, rate-limit headers |
| [webhook-sender](https://github.com/dreadmoreeee/webhook-sender) | Reliable outgoing webhooks: HMAC signatures, retries with backoff, circuit breaker, outbox and replay |
| [api-diff](https://github.com/dreadmoreeee/api-diff) | Compares two OpenAPI specs and flags breaking changes, with CI exit codes. 50 tests. |
| [openapi-client-gen](https://github.com/dreadmoreeee/openapi-client-gen) | Generates a small, typed Python client (httpx + dataclasses) from an OpenAPI spec. 106 tests. |
| [webhook-inspector](https://github.com/dreadmoreeee/webhook-inspector) | Self-hosted webhook receiver and debugger: verifies Stripe, GitHub and Shopify signatures, stores, replays and exports requests. 60 tests. |
| [stripe-fastapi-webhooks](https://github.com/dreadmoreeee/stripe-fastapi-webhooks) | Stripe Checkout with a verified, idempotent webhook in FastAPI. Signature check without the SDK, replay protection, a late "failed" never overwrites "paid". 16 tests. |
| [stripe-subscriptions-starter](https://github.com/dreadmoreeee/stripe-subscriptions-starter) | FastAPI + Stripe subscriptions: Checkout, Customer Portal, verified idempotent webhooks that survive out-of-order delivery. 33 tests. |
| [canada-sales-tax](https://github.com/dreadmoreeee/canada-sales-tax) | Canadian GST/HST/PST/QST by province and date, exact cents, tax-included prices that add up, EN/FR invoice lines. No dependencies. |
| [invoice-pdf-canada](https://github.com/dreadmoreeee/invoice-pdf-canada) | One-page Canadian PDF invoices from JSON, with GST/HST/PST/QST by province and date, in English or French. 37 tests. |
| [overdue-invoice-reminders](https://github.com/dreadmoreeee/overdue-invoice-reminders) | Finds overdue invoices in a CSV export and sends tiered email reminders. Dry-run by default. |
| [stripe-tax-report-ca](https://github.com/dreadmoreeee/stripe-tax-report-ca) | GST/HST/PST/QST report from Stripe CSV exports: collected vs expected per province and period |
| [ics-lint](https://github.com/dreadmoreeee/ics-lint) | Validate and generate iCalendar files: folding, UIDs, time zones, iTIP REQUEST/CANCEL rules, client quirks |
| [sms-segments](https://github.com/dreadmoreeee/sms-segments) | SMS length and cost: GSM-7 vs UCS-2, segments, the characters that double the cost, safe replacements |
| [email-list-hygiene](https://github.com/dreadmoreeee/email-list-hygiene) | Clean a mailing list without sending anything: duplicates, typos, disposable domains, MX, consent |
| [opening-hours](https://github.com/dreadmoreeee/opening-hours) | Parse English/French opening hours into schema.org JSON-LD, OSM syntax and a DST-safe 'open now' widget |

**Monitoring and CI**

| Project | What it does |
|---|---|
| [website-report-card](https://github.com/dreadmoreeee/website-report-card) | One client-friendly report from eight website checks: grade, traffic lights, top fixes in plain language, PDF |
| [status-page-gen](https://github.com/dreadmoreeee/status-page-gen) | Static status page from cron checks: HTTP, TCP, TLS, 90-day uptime bars, incidents in Markdown, Atom feed |
| [page-change-watch](https://github.com/dreadmoreeee/page-change-watch) | Watch pages for meaningful changes with noise filters, snapshots, readable diffs and cron exit codes |
| [website-ci-checks](https://github.com/dreadmoreeee/website-ci-checks) | GitHub Action that runs my website checks in CI with a job summary and SARIF upload |
| [sqlite-backup-check](https://github.com/dreadmoreeee/sqlite-backup-check) | Safe SQLite backups: online backup while writing, rotation, checksums, encryption and a restore test |

### What I work with

Python · FastAPI · Stripe (Checkout, Billing, webhooks) · SQLite · Docker · Caddy · Cloudflare · HTML/CSS/JavaScript · Local SEO
