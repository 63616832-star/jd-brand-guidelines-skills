# JD Role Routing

Use this after intake to choose the working role and guideline source.

## Routing Table

| Request Type | Lead Role | Required Rule Source |
|---|---|---|
| UX text, Toast, modal, empty-state text, error text, button, naming | JD Copywriter | `../jd-copywriting-guidelines/SKILL.md` |
| Campaign copy, venue copy, channel copy, rights copy, service promise | JD Copywriter + JD QA Reviewer | `../jd-copywriting-guidelines/SKILL.md` |
| Vivid marketing copy, venue head image copy, operation banner copy, proposal wording | JD Copywriter + JD Creative Director | `../jd-copywriting-guidelines/SKILL.md` plus `references/expressive-copy-layer.md` |
| Product selling point, price, subsidy, coupon, ranking, service, efficacy | JD QA Reviewer first | `../jd-copywriting-guidelines/SKILL.md` commerce gates |
| JOY, empty state visual, fallback page, abnormal page, promotion JOY | JD Visual Designer | Optional WIP: `../jd-joy-ip-guidelines/SKILL.md` |
| App Store activity image, store operation image, showcase image, floating entrance | JD Visual Designer | Optional WIP: `../jd-app-store-marketing-guidelines/SKILL.md` |
| Startup icon, operation icon, promotion icon, launch screen, splash screen | JD Visual Designer | Optional WIP: `../jd-startup-icon-guidelines/SKILL.md` |
| Multi-touchpoint campaign or proposal | JD Brand AE -> Strategy -> Creative -> Copy/Visual -> QA | Load sources by touchpoint |
| Existing draft review | JD QA Reviewer | Load every domain touched by the draft |

## Role Handoff

Each handoff must include:

- confirmed input;
- missing or assumed input;
- loaded rule source;
- decision made;
- next role and reason;
- user checkpoint needed before proceeding.

## Cross-Domain Priority

1. Evidence and compliance boundary.
2. JD 16.0 tone: simple, reliable, friendly.
3. Touchpoint role and user task.
4. JOY/IP/visual hard constraints.
5. Expression vividness, creative memorability, and proposal persuasiveness.

If a creative route conflicts with higher priority rules, revise or reject it.

## Stable And WIP Scope

- Stable core: `jd-copywriting-guidelines` plus this workflow skill.
- Optional WIP visual extensions: `jd-joy-ip-guidelines`, `jd-app-store-marketing-guidelines`, and `jd-startup-icon-guidelines`.
- Archived legacy source: `jd-copy-guidelines/_archive/monolith-20260616`; do not route current tasks to it unless the user explicitly asks to inspect historical rules.

When sharing this workflow with others, assume only the stable core is installed unless the user confirms the visual extensions are available.

## Expressive Layer Eligibility

Use `expressive-copy-layer.md` only when the task benefits from stronger hooks or reader emotion:

- eligible: campaign theme, venue head image, operation banner, channel card, brand proposal, social-style operation copy, visual headline exploration;
- not eligible by default: payment, logistics, refund, after-sales, error, Toast, rights rules, service terms, legal disclaimers, sensitive product claims.
