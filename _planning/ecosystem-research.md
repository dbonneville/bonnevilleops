# AI Skills & Tools Ecosystem — Research Notes

> Dump from Grok research session, March 2026. Needs verification on some claims.

---

## Key Repos to Track

### Agent Skills (Our Primary Interest)

| Repo | Stars | What | Relevance |
|------|-------|------|-----------|
| **VoltAgent/awesome-openclaw-skills** | 5,400+ skills | Filtered/categorized OC skills | Creative automation, ad mgmt, content gen, design workflows |
| **VoltAgent/awesome-agent-skills** | 500+ skills | CC, OC, Codex compatible | Official skills from Anthropic, Google. Coding, cloud, creative production. |
| **anthropics/skills** | ~37.5k | Official Anthropic skills repo | Reference implementations |
| **sickn33/antigravity-awesome-skills** | ~18.9k | 900+ skills for CC/Antigravity/Cursor | Has "Marketing & Growth" bundle |
| **travisvn/awesome-claude-skills** | ~7.6k | Claude skills specifically | `frontend-design`, `canvas-design`, `brand-guidelines`, `web-artifacts-builder` |
| **hesreallyhim/awesome-claude-code** | ~23.7k | Skills, hooks, slash-commands, orchestrators | General dev but comprehensive |

### Design & Creative Resources

| Repo | What | Relevance |
|------|------|-----------|
| **j0hnm4r5/awesome-creative-technology** | Groups, studios, collectives in creative tech | Inspiration, networking, understanding the landscape |
| **awesomelistsio/awesome-web-design** | Web design resources, inspiration, UI guidelines | Reference for what our clients care about |
| **hqasmei/awesome-design-resources** | UI components, AI design tools, palettes, icons | Tools we might use or recommend |
| **bradtraversy/design-resources-for-developers** | UI resources, stock photos, templates, CSS frameworks | Practical, updated daily |

### MCP Servers

| Repo | Stars | What |
|------|-------|------|
| **punkpeye/awesome-mcp-servers** | ~81.4k | The definitive MCP list |
| **panktishah62/MCP-Stack-for-UI-UX-Designers** | Small | Design-specific MCP stack |
| **redf0x1/ui-ux-pro-mcp** | Small | 1,519+ curated design resources via MCP |
| **pipeboard-co/meta-ads-mcp** | 564 | Meta ads campaign management |

---

## The Three Pillars (OpenClaw / Claude Skills / MCP)

### OpenClaw

- Open-source AI agent framework
- Originally Clawdbot → Moltbot → OpenClaw (renamed late Jan 2026, trademark issues)
- Runs autonomously on your machine
- Executes code, manages schedules, uses modular "skills"
- Core repo: github.com/openclaw/openclaw
- ClawHub registry: 13,729+ skills with vector search
- Skills cover: ad monitoring, copy generation, website editing, content publishing
- Positioning as open alternative to proprietary tools

### Claude Code Skills

- Reusable capabilities in SKILL.md format
- Claude Code = coding-focused interface where Claude executes workflows
- Skills make Claude more agent-like
- Compatible with OpenClaw and other agent frameworks
- Shared via GitHub, growing daily
- Key creative skills found: `frontend-design`, `creative-director-skill`, `taste-skill`, `canvas-design`

### MCP (Model Context Protocol)

- Standard protocol for bridging AI models to external tools/data
- Handles auth, configuration, integration
- Major adoption by Claude and ChatGPT in early 2026
- Enables: connecting agents to APIs, databases, design tools, ad platforms
- Key for building robust creative workflows
- Design-relevant MCP servers: Figma, Adobe, Canva, Webflow, Meta Ads

---

## What This Means for Us

### Opportunity Confirmed

**Nobody is curating this ecosystem specifically for creative shops.** The repos exist but they're organized by tool type (skills, MCP servers) not by end-user need (WordPress shop owner, print studio, small agency).

### What We Could Build

A curated, daily-updated catalog that answers:
> "I run a small design shop. What AI skills, MCP servers, and agent workflows exist RIGHT NOW that can help me with [specific task]?"

Organized by **work category** (WordPress, print, email, social, dev) not by tool type.

### Skills We Should Be Tracking Daily

| Category | What to Watch |
|----------|--------------|
| **WordPress** | Any CC/OC skill for WP management, plugin updates, content edits, theme fixes |
| **Design Production** | Figma MCP, Canva MCP, asset generation, batch resize, template filling |
| **Email** | HTML email skills, template builders, platform integrations |
| **Print** | PDF generation, layout automation, prepress checks |
| **Ads** | Meta ads MCP, click test automation, creative generation |
| **Content** | Blog publishing, SEO, social media scheduling |
| **Client Ops** | Intake, triage, status updates, reporting |
| **Dev** | CSS fixes, responsive debugging, deployment, staging |

### Daily Scan Sources

| Source | URL | What to Watch |
|--------|-----|--------------|
| PulseMCP | pulsemcp.com | 8,600+ MCP servers, updated daily |
| ClawHub | github.com/openclaw/clawhub | 13,729+ skills, searchable |
| awesome-claude-code | github.com/hesreallyhim/awesome-claude-code | New skills/hooks/plugins |
| awesome-mcp-servers | github.com/punkpeye/awesome-mcp-servers | New MCP servers |
| awesome-openclaw-skills | VoltAgent | New OC skills |
| X / Twitter | Search "claude code skill" + "design" | Community discoveries |
| Reddit r/ClaudeAI | | New workflows, skill shares |
| Hacker News | Search "claude skills" / "MCP" | Trends, new tools |

---

## Claims to Verify

> Some of the Grok dump may be inaccurate. Flag these for checking:

- [ ] OpenClaw "surpassed React as most-starred software project on GitHub" — seems inflated, verify
- [ ] ClawHub has 13,729+ skills — verify current count
- [ ] awesome-openclaw-skills has 5,400+ filtered skills — verify
- [ ] "MCP major adoption by Claude and ChatGPT in early 2026" — ChatGPT adopted MCP? Verify
- [ ] Repo star counts — verify all, Grok may have hallucinated numbers
- [ ] Some repos listed may not exist or may have been renamed — verify URLs before relying on them

---

## Related Files

| File | Purpose |
|------|---------|
| `target-market-playbook.md` | Who we're selling to |
| `gtm-strategy.md` | How we reach them |
| `playbook.md` | How we deliver |
| `todo.md` | Master task tracker |
