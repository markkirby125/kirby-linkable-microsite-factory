# Module 3: SSR HTML Architecture, Python QA & Daily Cron / Local-GPU 3D Automation

*Source: Edward Sturm Ep. 1,224 feat. Mike Hawley (`ULvVvU0fWj8`, Nov 12, 2026).*

---

## 3.1 Server-Side Rendered (SSR) Crawlability First
1. **Zero Client-Side JS Content Hiding:** Every microsite, directory listing, interactive calculator documentation block, and schema payload MUST render as clean **server-side rendered (SSR) HTML** so `Googlebot`, `Screaming Frog`, `OAI-SearchBot`, and `PerplexityBot` ingest full page content immediately without executing client-side JavaScript bundles.
2. **Pre-Upload Automated Python QA Checklist:**
   - Before pushing any build to Spaceship/Cloudflare, run an automated Python validation check locally verifying:
     - Clean SSR HTML presence (`<h1>`, `<title>`, meta description, canonical tag, clean semantic hierarchy).
     - Zero broken internal links, zero missing images/OG tags, and valid metadata (`no placeholder tokens`).
     - Live verification via `Chrome` MCP on staging (`noindex`) before opening indexation.

---

## 3.2 Zero-API Daily Cron Automation & Local-GPU Playwright 3D
1. **Automated Daily Content Refresh Without Paid APIs:**
   - Write lightweight Python scrapers/cron updaters that inspect public feeds (e.g., hourly/daily YouTube channel feeds without burning paid API quotas) and regenerate static/SSR microsite pages automatically (`SEO-TV.com` auto-sync pattern).
2. **Overnight Headless Playwright Local-GPU Rendering:**
   - For high-craft interactive visual directories (`150+`-page product/3D showcase sites), run a local Python + headless Playwright browser script overnight harnessing the workstation's **local GPU** to capture deterministic 3D/DOM renders directly to local storage (respecting intellectual-property and copyright rules; never rip copyrighted third-party brand assets).
   - For local audio/video asset generation on the same workstation, route media rendering to `../../kirby-coded-motion-studio/SKILL.md` (`references/06_local_applications.md`).
