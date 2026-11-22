# Module 3: SSR HTML Architecture, Python QA & Daily Cron / Local-GPU 3D (Unverified Candidate)

*Source: Edward Sturm Ep. 1,224 feat. Mike Hawley (`ULvVvU0fWj8`, Nov 12, 2026). Single-source, directional, unverified benchmarks.*

---

## 3.1 Server-Side Rendered (SSR) Crawlability First
1. **Immediate Render-Queue-Free Content Parity:** Every microsite directory listing, interactive calculator answers/content/metadata block, and schema payload MUST render as clean **server-side rendered (SSR) HTML** (interactive widget UI JS may hydrate progressively, while all text answers, documentation, and metadata exist directly in SSR HTML) so `Googlebot`, `Screaming Frog`, `OAI-SearchBot`, and `PerplexityBot` can ingest full page content directly from the HTML without relying on a deferred client-side render queue.
2. **Pre-Upload Automated Python QA Checklist:**
   - Before pushing any build to Spaceship/Cloudflare, run an automated Python validation check locally verifying:
     - Clean SSR HTML presence (`<h1>`, `<title>`, meta description, canonical tag, clean semantic hierarchy).
     - Zero broken internal links, zero missing images/OG tags, and valid metadata (no leftover `TODO` or placeholder tokens).
3. **Agent/Human Browser Staging Check:**
   - Run live verification via `Chrome` MCP on staging (`noindex`) before opening indexation.

---

## 3.2 Permitted API/RSS Daily Cron Automation & Local-GPU Playwright 3D (Unverified Candidate)
1. **Automated Daily Content Refresh via Official APIs / Public Feeds:**
   - Use lightweight Python updaters that inspect **official APIs or public RSS/Atom feeds where the source's terms allow**, respecting `robots.txt`, Terms of Service, rate limits, and attribution, to regenerate static/SSR microsite pages automatically (`SEO-TV.com` auto-sync pattern, directional single-source).
2. **Overnight Headless Playwright Local-GPU Rendering (unverified candidate route, not active; per `06_local_applications.md` it needs a dated verified entry before use):**
   - For high-craft interactive visual directories (`150+`-page product/3D showcase sites, single-source), once verified, run a local Python + headless Playwright browser script overnight harnessing the workstation's **local GPU** to capture deterministic 3D/DOM renders directly to local storage (respecting intellectual-property and copyright rules; never rip copyrighted third-party brand assets).
   - For local audio/video asset generation on the same workstation, route media rendering to [`kirby-coded-motion-studio`](../../kirby-coded-motion-studio/SKILL.md) ([`06_local_applications.md`](../../kirby-coded-motion-studio/references/06_local_applications.md)).
