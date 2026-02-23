**Section 08 Form — Package Selector**
- Foundation → **Startup** — "Digital foundation, branding & content marketing"
- Growth → **Accelerated** — "Everything in Startup + email & telemarketing ★"
- Domination → **Growth** — "Everything in Accelerated + ORM, PR & AI tools"

**Ops Campaign Modal Dropdown** — same three renames with updated descriptions.

**PKG_DEFAULTS (Ops deliverables engine)**
- *Startup*: Domain, email, website, logo/branding, graphics, content marketing, social media, SEO content
- *Accelerated*: Everything in Startup + email marketing campaigns, telemarketing & outbound calls, lead nurturing/CRM
- *Growth*: Everything in Accelerated + ORM, PR & media outreach, press placement, AI toolsuite, AI chat, predictive analytics

**Proposal Output (Section 08 — Investment)**
- Startup shows the actual fee entered in the form (nominal pricing)
- Accelerated & Growth display **"Contact us for your custom quote"** — no price shown
- The deliverables table dynamically shows the correct rows per package (email/tele rows only for Accelerated+, ORM/PR/AI rows only for Growth)

**All fallback/default references** updated from `'Growth'` → `'Accelerated'` across `readData()`, `loadJNS()`, and `sendDirectToOps()`.
