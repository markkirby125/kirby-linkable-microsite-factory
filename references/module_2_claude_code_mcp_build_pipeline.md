# Module 2: `Claude Code` MCP Build Pipeline, `notes.md` Continuity & UI Craftsmanship

*Source: Edward Sturm Ep. 1,224 feat. Mike Hawley (`ULvVvU0fWj8`, Nov 12, 2026).*

---

## 2.1 Local `Claude Code` + MCP Environment & Security Gate
1. **Desktop/Terminal Local Execution (`$20` Tier Baseline):** Run local `Claude Code` (never ephemeral web chat sessions) paired with Python and wired MCP connectors:
   - **`Chrome` MCP:** Live rendered browser verification and DOM/visual inspection.
   - **`Spaceship` MCP:** Domain/hosting/file deployment management.
   - **`Cloudflare` MCP:** DNS, caching, and staging/edge security checks.
   - **Mandatory Pre-Install Security Gate:** Verify all three connectors via `../../kirby-agent-security/SKILL.md` (`references/00_dispatcher.md` §5 and `references/module_2_autonomous_deployment_mcp_verification.md`) before enabling write tools.
2. **Permission Escalation Discipline (`Ask` → `Auto`):** Start every new project in `"Ask"` permission mode so file mutations, DNS updates, and deployment commands require explicit human review; switch to `"Auto"` only after staging behavior and local QA scripts are proven. Never execute unattended production DNS changes.

---

## 2.2 Persistent `notes.md` State & Skill Distillation Loop
1. **Maintain `notes.md` in Every Project Folder:** Record prior architectural state, active plans, layout decisions, bug discoveries, and pending tasks in a persistent `notes.md` file inside each microsite workspace so every new `Claude Code` session resumes cleanly without context amnesia.
2. **Distill Lessons into Reusable Skills (`notes.md` → `SKILL.md`):** Periodically promote validated fixes from project `notes.md` logs into modular reusable skills (Hawley's library grew to `811` rules across `59` skills; keep project `CLAUDE.md`/`AGENTS.md` lean via `../../kirby-agentmd-generation/SKILL.md`).

---

## 2.3 The 4-Layout Gate & Authentic Craftsmanship Standards
*(Framed strictly for **UI quality, typographic clarity, and brand authenticity**, never for detection evasion.)*
1. **The 4-Layout Pre-Build Requirement:** Before writing final build code, instruct the agent to generate **4 distinct homepage design prototypes** in different layouts and palettes; review visually and discard weak outputs bluntly. Feed reference screenshots/URLs for reverse-engineering layout proportions rather than relying on generic prompts.
2. **Hawley Craftsmanship Checklist (Ban Generic Boilerplate Visuals):**
   - **Zero Generic Slop Artifacts:** Reject em-dash (`—`) overuse in UI copy, uniform rounded card/pill stacks, generic AI placeholder slogans, and synthetic AI portraits/avatars.
   - **Authentic Media & Real Logos:** Use real operational photography, grotesque/bold display typography, custom favicons/OpenGraph assets, and verified vector/SVG marks (`Hawley` asset pattern: `1,400+` real brand logos in local library, zero unverified stock placeholders).
   - **Multi-Model Asset Generation & CSS Hygiene:** Pair `GitHub` skill modules with verified visual design tokens (`Hallmark`-grade UI polish, `../../kirby-accessible-contrast/SKILL.md` WCAG 2.1 AA contrast checks).
