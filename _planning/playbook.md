# DesignTransform — Operational Playbook

> How we deliver the work. Living document.

---

## Service Model

**What we are:** A one-man production partner for small creative shops. We clear their backlog so they can focus on clients and new business.

**What we are not:** A strategy agency. A branding shop. A consulting firm (yet). We execute.

---

## Delivery Workflow

### Intake

- Client sends work via [TBD — email? Slack? shared board?]
- Each request gets logged with: task type, deadline, assets provided, notes
- We triage: effort estimate, priority, dependencies

### Production

- One deliverable at a time per client (subscription model)
- AI-accelerated where possible, human QC on everything
- Doug reviews every deliverable before delivery

### Delivery

- Deliver via [TBD — same channel as intake?]
- Unlimited revisions within scope
- Client ships to their end customer

### Communication

- Async by default
- Status updates at [TBD — daily? every delivery? weekly summary?]
- No meetings unless client requests

---

## Task Types We Handle

> Needs narrowing — see Interview Queue

### Likely Yes (Launch)

- WordPress updates, fixes, plugin issues
- Banner ads, social graphics, resize batches
- Email templates (HTML or platform-specific)
- Landing pages (WordPress, Webflow, static)
- PDF layouts, print-ready files
- Figma to code
- UI components
- Presentation decks
- Brand collateral (business cards, letterhead, one-pagers)
- HTML/CSS fixes, responsive debugging

### Likely No (For Now)

- Full brand identity / logo design
- Strategy / consulting
- Full application development
- Video production / motion graphics
- Copywriting (unless paired with design)

### Maybe (Depends on Skill Development)

- SEO audits and fixes
- Analytics setup (GA4, pixels, CAPI)
- Ad campaign management
- Social media management

---

## Pricing Tiers

> Starting lower, scaling to $7K as proof stacks up

### Phase 1 — Early Clients (Proving Ground)

| Tier | Price | Turnaround | For |
|------|-------|-----------|-----|
| **Starter** | $500-750/mo | 7-10 days | Solopreneurs, very small shops |
| **Standard** | $995/mo | 5-7 days | Small creative shops |
| **Pro** | $1,995/mo | 3-4 days | Busier shops, faster cycles |

### Phase 2 — Established (After 6-12 Months)

| Tier | Price | Turnaround | For |
|------|-------|-----------|-----|
| **Standard** | $2,500/mo | 5-7 days | Established shops |
| **Pro** | $4,500/mo | 2-3 days | High volume |
| **Premium** | $7,000/mo | 1-2 days | Dedicated capacity |

### Add-On Services

- Claude/OpenClaw setup for client's own workflows — [TBD pricing]
- Click test campaign (messaging validation) — [TBD pricing]
- Tracking audit (pixels, CAPI, GA4) — [TBD pricing]

---

## Quality Control

- Every deliverable reviewed by Doug before sending
- Checklist per task type [TBD — build these]
- Client feedback logged in learnings.md per client
- Patterns tracked: what gets revised most, what ships clean

---

## Client Memory Structure

```
workspace/client/{name}/
├── stack.md          # Their tools, CMS, hosting, accounts
├── brand.md          # Colors, fonts, tone, assets location
├── learnings.md      # Append-only: what worked, what got revised, preferences
├── active.md         # Current tasks in progress
└── history.md        # Completed work log
```

---

## Tools (Internal)

| Purpose | Tool |
|---------|------|
| Production | Claude Code, OpenClaw, Figma, Canva |
| Code | VS Code / Cursor, GitHub |
| CMS work | WordPress (local dev), Webflow |
| Communication | [TBD — email? Slack?] |
| Task tracking | [TBD] |
| Ad management | social-cli, Pipeboard MCP, Meta Ads Manager |
| Client files | [TBD — Dropbox? Google Drive?] |

---

## Key Skills to Master & Teach

### frontend-design (Claude Code Skill)

**What it is:** The most popular CC skill for building production-grade frontend interfaces. Anti-AI-slop by design. Installed globally on our machine.

**Location:** `~/.claude/plugins/cache/claude-code-plugins/frontend-design/1.0.0/skills/frontend-design/SKILL.md`

**How it works:** Design philosophy engine, not a framework selector. Infers tech stack from prompt. Pushes for bold aesthetic direction and distinctive output.

**Tech stack matters for output quality:**
- **React** — highest ceiling. Motion library, JS transitions, dynamic interactions, programmatic layout
- **Plain HTML/CSS** — CSS-only animations, hover states, scroll triggers. Clean but lower complexity ceiling.
- **Same either way** — typography, color, spatial composition, fonts

**The prompt is everything.** Good results require:
1. Bold aesthetic direction (editorial, brutalist, luxury, retro-futuristic, etc.)
2. One memorable anchor ("what's the one thing someone will remember?")
3. Audience context
4. Tech stack stated explicitly
5. Font/color guidance if you have preferences

**Bad prompt:** "Build me a landing page for my design service"
**Good prompt:** "Build a landing page for a veteran design ops service targeting small creative shops. Editorial magazine aesthetic. Dark background, warm accents. The one thing people remember: it feels like a person, not a platform. Distinctive serif display font. Plain HTML and CSS."

**Forbidden patterns (built into skill):**
- Inter, Roboto, Arial, system fonts
- Purple gradients on white
- Predictable layouts
- Cookie-cutter components
- Same design across generations

**Teachable to clients:** Yes — this is a perfect example of "here's how to get 10x results from AI by writing a better brief." The skill itself is free. The knowledge of how to prompt it is the value.

### Impeccable (frontend-design Upgrade)

**What:** Upgrade layer on top of Anthropic's frontend-design skill by Paul Bakaus (creator of jQuery UI, ex-Chrome DevTools PM at Google).
**Repo:** github.com/pbakaus/impeccable | **Site:** impeccable.style
**License:** Apache 2.0 | **Cost:** Free

**Adds over base skill:**
- 7 reference docs: typography, color/contrast (OKLCH), spatial design, motion, interaction, responsive, UX writing
- 17 steering commands: `/audit`, `/critique`, `/polish`, `/distill`, `/bolder`, `/quieter`, `/animate`, `/colorize`, `/delight`, `/clarify`, `/normalize`, `/optimize`, `/harden`, `/extract`, `/adapt`, `/onboard`, `/teach-impeccable`
- Explicit anti-patterns: Inter, Arial, gray-on-color, nested cards, bounce easing, pure black tints
- Design context persistence via `/teach-impeccable`

**Works with:** Claude Code, Cursor, Gemini CLI, Codex CLI, VS Code Copilot, Antigravity, Kiro

**How we use it:**
1. Install and use for all production work — `/polish` and `/audit` before every client delivery
2. Teach clients the command vocabulary as part of technology transfer
3. Study as architecture model for building our own skills (7 reference docs + commands + anti-patterns)

**Key insight:** Still tech-stack agnostic like base skill. Specify HTML vs React in your prompt. Impeccable improves the design regardless of framework.

**Strategic note:** Impeccable is proof of concept for our core business model. Paul Bakaus did exactly what we want to do — took a base skill, added deep domain expertise on top, packaged it with commands and reference docs, and gave it away to build authority. He blew past the idea of just tracking skills — he MADE one that elevates everyone's output. Our playbook: track skills across the ecosystem, build our own for creative shop workflows (WordPress, print, email, client ops), then offer to help people use them. The skill IS the product. Teaching it IS the service.

---

## Open Questions (→ Interview Queue)

- What's the intake channel? (Email, Slack, Trello, something else?)
- What's the delivery channel?
- How do you handle assets? (Client sends Figma links? Zips? Dropbox?)
- What's the revision policy? Truly unlimited or scoped?
- Do you track hours internally even though billing is flat rate?
