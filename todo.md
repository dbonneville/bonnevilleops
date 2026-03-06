# DesignTransform — TODO

> One-man agency targeting creative shops drowning in production work.
> **Goal:** $100K/month on ~14 subscriptions at $7K/month. Start smaller, refine skills and tools, scale up.

---

## The Vision

- Become the go-to production partner for small creative shops (2-10 people)
- "Design shops" / "creative shops" — not "digital agencies"
- These are people running 50 WordPress sites, doing print, drowning in backlog
- They're not on Twitter. They're not into AI hype. They want relief.
- Start with smaller businesses and lower fees while refining skills, tools, and approach
- Graduate to $7K/month retainers as competency and proof stack up

---

## Completed

- [x] Find saved offline site (`tms_output/01/`)
- [x] Move `tms_output` into this folder
- [x] Research `themattberman/meta-ads-kit` repo
- [x] Create CLAUDE.md for this project
- [x] Research Steve Pieper Click Test Method — v1.0 and v2.0 docs complete
- [x] Research MCP servers for Meta ads (Pipeboard, social-cli, etc.)
- [x] Create target market playbook background (`_planning/target-market-playbook.md`)
- [x] Research existing skill/MCP catalogs for creative market (gap confirmed — none exist)

---

## Define the Niche

- [ ] Pick the term: "creative shop" vs "design shop" vs something else
- [ ] Write a tight ICP (ideal customer profile) — job title, revenue, team size, tools they use, where they hang out
- [ ] Validate with data — scrape Reddit, forums, Facebook groups for actual pain language
- [ ] Narrow down: WordPress shops? Print + web? Dev-capable or design-only?

---

## Pain Point Research & Data Collection

- [ ] Build comprehensive list of creative shop pain points
- [ ] Map each pain point to an AI skill that solves it (track / sell / do for them / set up for them)
- [ ] Set up automated scraping tools to collect pain points from Reddit, X, forums, Facebook groups
- [ ] Build a structured dataset: pain point → frequency → emotional language → skill that addresses it
- [ ] Use this data to prove the market exists and is defined to a fault

---

## Skills Catalog (The Engine)

- [ ] Build a living catalog of CC and OC skills organized by work category (WordPress, print, email, social, dev, etc.)
- [ ] Each entry: what the skill does, reliability, setup needed, gotchas
- [ ] Update daily as new capabilities are discovered or limitations are hit
- [ ] Doubles as sales reference — "can you handle X?" → check catalog → yes/no/how

### Skill-Maker Skills

- [ ] Build a **Claude Code skill-maker skill** — discovers a workflow, outputs a properly formatted CC skill file
- [ ] Build an **OpenClaw skill-maker skill** — same thing for OC platform
- [ ] These are how the catalog grows daily without manual boilerplate

### Skills to Build (Backlog Destruction Kit)

- [ ] `intake-triage` — ticket analysis, priority scoring, effort estimation
- [ ] `design-ops` — design QA, asset delivery, revision tracking
- [ ] `dev-ops` — PR review, deployment, staging checks
- [ ] `client-comms` — status updates, weekly reports, scope change alerts
- [ ] `sprint-planner` — capacity analysis, sprint loading, blocker detection
- [ ] `analytics-audit` — pixel/CAPI/GA4 audit

---

## Content Site / SEO Flywheel

- [ ] Set up a website that publishes articles continuously about:
  - Each skill and what it solves
  - Each pain point creative shops face
  - Each tweet/post about pain we find in the wild
  - Tutorials on CC and OC for creative work
- [ ] Automate the pipeline: scrape pain → catalog → write article → publish → SEO
- [ ] **Build a `/snowball` skill** — runs the 4-prompt Snowball Method chain, outputs 30-day content calendar from one topic. Use for our own content + sell/teach to clients. See `_planning/snowball-method.md`
- [ ] Run snowball on our core problem: "Small creative shops drowning in production work" → 63+ content pieces
- [ ] Every article links back to the service that solves the pain
- [ ] Content doubles as market research that publishes itself

---

## Cold Email (Primary GTM Channel)

- [ ] Choose sending tool (Instantly, Smartlead, Lemlist)
- [ ] Set up dedicated sending domain + warmup (2-3 weeks)
- [ ] Build lead lists: scrape Clutch, Google Maps, LinkedIn, directories for small creative shops
- [ ] Write cold email sequence (3-5 touches, plain text, pain-first)
- [ ] Build simple landing page for cold email traffic
- [ ] Set up CRM for tracking replies and pipeline
- [ ] Start sending (50-100/day after warmup)
- [ ] Track: open rate, reply rate, positive reply rate, booked calls

See: `_planning/gtm-strategy.md`

---

## Click Testing / Messaging Validation

- [ ] Set up Meta ads account for click testing
- [ ] Evaluate Pipeboard MCP server vs social-cli for campaign management
- [ ] Run Test 1: pain point taglines on color block images
- [ ] Follow the 6-round click test method per `_planning/steve-pieper-click-test-method-v2.md`

---

## Skill Registry / Repo

- [ ] Set up a public repo to curate skills for creative shops (the "awesome-ai-for-creative-shops" that doesn't exist)
- [ ] Decide format: awesome-list style? Or structured registry with categories?
- [ ] Seed with existing creative/design skills found across ClawHub, SkillsMP, Anthropic official, etc.
- [ ] Publish our own skills in SKILL.md format → distribute to SkillsMP, ClawHub, skills.sh, agentskill.sh
- [ ] Set up daily scan of registries for new creative/design/agency skills
- [ ] Track: ClawHub, skills.sh, SkillsMP, PulseMCP, agentskill.sh

See: `_planning/skill-registries.md` for full landscape (30+ registries mapped)

---

## Tools & Infrastructure

### To Evaluate / Install

- [x] Install **Impeccable** (pbakaus/impeccable) — 18 skills installed globally. All security scans clean.
- [ ] **Build something with Impeccable ASAP** — test the full workflow: `/teach-impeccable` → build a page → `/critique` → `/polish` → `/audit`. Use it to rebuild our own landing page or build a demo piece for the portfolio.
- [ ] Evaluate **Google Workspace CLI** — just launched by Addy Osmani/Google. Gmail, Drive, Calendar APIs + 40 agent skills. Relevant for bonnevillebot@gmail.com automation, client ops, asset management. (https://x.com/addyosmani/status/2029372736267805081)
- [ ] Install and evaluate **social-cli** (`@vishalgojha/social-cli`)
- [ ] Evaluate **OpenClaw** agent framework
- [ ] Evaluate **Pipeboard meta-ads-mcp** for campaign management
- [ ] Set up **BareClaw** agent with daily skill/market scanning

### Patterns to Adopt

- [ ] **"5 Daily Questions"** framework — adapt for backlog health
- [ ] **Brand Memory system** — adapt as client memory (`workspace/client/{name}/`)
- [ ] **Benchmark-driven analysis** — define SLA thresholds
- [ ] **Closed-loop automation** — monitor → detect → act → report → repeat
- [ ] **Safety model** — read-only default, actions require approval
- [ ] **Kallaway Framework** (Money/Time/Status/Fear) — for proposals & ad copy
- [ ] **Learnings.md pattern** — append-only institutional memory per client

---

## Site / Marketing / Positioning

- [ ] Review current BonFX site messaging against actual target market
- [ ] Rewrite positioning: sell relief, not AI. Sell outcomes, not tools.
- [ ] Strip "AI-powered" language — these people don't care how the work gets done
- [ ] Phase 1 only — don't sell the 4-phase transformation story upfront
- [ ] Decide: BonFX? DesignTransform? New name?
- [ ] Update pricing — start with lower entry point for smaller shops, scale to $7K

---

## Project Structure (From Brij Kishore Pandey's Framework)

- [x] Slim down CLAUDE.md — moved vision/transurfing/co-CEO role to `docs/vision.md`
- [x] Add repo map to CLAUDE.md
- [x] Create `docs/` folder with `vision.md`
- [ ] Create `docs/decisions.md` as decisions accumulate
- [ ] Start building project-level skills in `.claude/skills/` as workflows emerge: `/snowball`, `/click-test`, `/cold-email-sequence`
- [ ] Light touch only — no over-engineering. Structure grows with the work.

---

## Architecture Decisions

- [ ] Choose project management integration (Jira / Linear / Asana / GitHub)
- [ ] Choose agent framework (OpenClaw vs custom)
- [ ] Define client onboarding workflow
- [ ] Design `workspace/client/{name}/` memory structure

---

## Interview Queue — Questions for Doug

> Unanswered questions collected during brainstorming. We'll run through these later.

- [ ] What's the service name? BonFX? DesignTransform? Something new?
- [ ] "Creative shop" or "design shop" — which feels right for the niche label?
- [ ] What specific task types do you handle at launch? WordPress only? Print too? Dev?
- [ ] What's the entry-level pricing for early/smaller clients?
- [ ] Do you need a new landing page or can the current Vercel site work for click testing?
- [ ] Which pain points do you click test first?
- [ ] What does a client's first week look like? How do they send work?
- [ ] What tools do your target clients actually use? (Trello? Email? Basecamp? Slack?)
- [ ] Are you offering to SET UP Claude/OpenClaw for clients, or just using it behind the scenes?
- [ ] When you say "set up OpenClaw and Claude for people" — is that a separate service or part of the subscription?
- [ ] What's the content site domain? Separate from BonFX?
- [ ] Do you do the work yourself or are you building a team eventually?
- [ ] What geographic market? US only? English-speaking?
- [ ] What's your capacity right now — how many clients could you handle today?
- [ ] What work are you NOT willing to do? (Strategy? Branding? Full dev projects?)
- [ ] Cold email sending tool? (Instantly? Smartlead? Lemlist?)
- [ ] CRM for tracking pipeline? (HubSpot free? Close? Something simpler?)
- [ ] Cold email domain — separate from main? What domain?
- [ ] Discovery calls or keep sales async?
- [ ] Close process — call → trial → subscribe? Or just subscribe directly?
- [ ] Referral incentive — discount? Free month? Cash?
- [ ] Geographic focus for cold email — local first (RI/New England) or national?
- [ ] How do clients send assets? (Figma links? Zips? Dropbox? Google Drive?)
- [ ] Intake channel? (Email? Slack? Trello? Something else?)
- [ ] Revision policy — truly unlimited or scoped?
- [ ] Do you track hours internally even on flat rate?
- [ ] Content site domain — same as service site or separate?
- [ ] What's the relationship between backlog-clearing service and CC/OC setup service? Same offer or separate?
- [ ] **bonnevillebot@gmail.com** — what automation does this need? Email monitoring? Lead intake? Newsletter? CRM integration? What's it for currently?
- [ ] **Business name — pick one.** BonFX is out (going to typography project). Candidates:
  - **bonnevilleops.com** — personal brand + operations. Says "this is a person with a name who runs your ops." Premium feel.
  - **dbonneville.com** — ALREADY OWNED. Short, personal, professional. Could be the hub for everything.
  - **benchworksai.com** — craft + production + subtle AI. "The bench is where real work gets done."
  - **aibenchworks.com** — same but AI-forward (less ideal — triggers market's AI allergy)
  - **transitionalbydesign.com** — sounds like interior design / therapy. Probably not.
  - **transitionalby.design** — same issue, .design TLD is niche
  - Tone must match BonFX site copy: veteran craft, quiet authority, professional. Not lowbrow, not bro-ish, not cute.
- [ ] Personal brand angle? "Bonneville Ops" leans hard into the 30-year track record as the differentiator. The person IS the product.

---

## Reference Files

| File | Purpose |
|------|---------|
| `_planning/steve-pieper-click-test-method-v2.md` | Click test execution manual |
| `_planning/steve-pieper-click-test-method.md` | Click test v1.0 (concise) |
| `_planning/automate-meta-ads.md` | Meta ads automation + social-cli + Kallaway |
| `_planning/target-market-playbook.md` | Target market profile, positioning, playbook background |
| `tms_output/01/` | Saved BonFX site |
| `CLAUDE.md` | Project context |
