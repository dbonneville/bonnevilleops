# Impeccable Commands — Quick Reference

> 18 skills installed globally from pbakaus/impeccable
> Use as `/command` in Claude Code. Scope with argument: `/audit header`, `/polish checkout-form`

---

## Setup

| Command | What it does |
|---------|-------------|
| `/teach-impeccable` | First run. Gathers your design context (brand, colors, fonts, preferences) and stores it for all future builds. **Do this first.** |

---

## Build & Create

| Command | What it does |
|---------|-------------|
| `/frontend-design` | The core skill. Create distinctive, production-grade frontend. Triggers design thinking phase before coding. |
| `/animate` | Add purposeful motion — easing curves, staggered reveals, scroll triggers. Not gratuitous. |
| `/colorize` | Strategic color introduction. OKLCH color space, tinted neutrals, accessibility-aware. |
| `/onboard` | Design an onboarding flow — first-run experience, progressive disclosure. |

---

## Refine & Improve

| Command | What it does |
|---------|-------------|
| `/polish` | **Pre-ship quality pass.** The final eye before delivery. Spacing, alignment, consistency, details. |
| `/bolder` | Amplify understated designs. Push contrast, scale, visual weight. When it's too quiet. |
| `/quieter` | Tone down excess. Reduce noise, calm the palette, simplify. When it's too loud. |
| `/delight` | Add moments of user joy — micro-interactions, easter eggs, satisfying feedback. |
| `/clarify` | Fix ambiguous UX copy — button labels, error messages, empty states. |
| `/distill` | Remove unnecessary complexity. Strip to essentials. Less but better. |

---

## Evaluate & QC

| Command | What it does |
|---------|-------------|
| `/audit` | **Technical checks** — accessibility (WCAG), performance, responsiveness, semantic HTML. |
| `/critique` | **UX design evaluation** — hierarchy, clarity, flow, resonance. Does it WORK for the user? |

---

## Systematize

| Command | What it does |
|---------|-------------|
| `/normalize` | Align with design system standards. Consistent tokens, spacing, components. |
| `/extract` | Pull code into reusable components. DRY up repeated patterns. |
| `/adapt` | Device-specific adaptations. Mobile, tablet, desktop, print. |

---

## Harden & Ship

| Command | What it does |
|---------|-------------|
| `/optimize` | Performance — bundle size, render speed, image optimization, lazy loading. |
| `/harden` | Error handling, internationalization, edge cases, defensive coding. |

---

## Suggested Workflow for Landing Page Rebuild

```
1. /teach-impeccable          → Set design context (brand, tone, constraints)
2. /frontend-design           → Build the page (with strong creative brief)
3. /critique                  → UX evaluation — does it work?
4. /bolder  or  /quieter      → Dial the intensity up or down
5. /colorize                  → Refine the palette
6. /animate                   → Add motion with purpose
7. /polish                    → Final quality pass
8. /audit                     → Technical checks (a11y, perf, responsive)
9. /optimize                  → Performance pass
10. /harden                   → Edge cases, error states
```

---

## First Test: Rebuild BonFX Landing Page

Use the existing BonFX copy (from `tms_output/01/`) as content source. New design direction TBD — but this is the tool to build it with.
