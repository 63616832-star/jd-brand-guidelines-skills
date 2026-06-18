---
name: jd-agency-workflow
description: Coordinate JD brand-standard work from brief intake through rule routing, strategy, creative direction, expressive copy enhancement, copy/visual execution, compliance gates, QA review, and delivery. Use when the user asks to run or adapt an agency workflow for 京东品牌规范, 京东 16.0, more vivid JD marketing copy, brand marketing, campaign proposals, operation assets, JD copy, JOY/IP usage, App store marketing images, startup icons, launch screens, or multi-role review across existing JD guideline skills.
---

# JD Agency Workflow

## Overview

Use this skill as the workflow layer for JD brand-standard work. It coordinates roles, checkpoints, and rule routing; it does not replace the dedicated JD guideline skills already present in this workspace.

The default posture is: collect the brief, classify the touchpoint, load only the needed JD guideline skill, pass risk gates before drafting, then QA the final output against JD 16.0 standards.

## Rule Sources

Load sibling guideline skills only when their domain is needed.

Core stable source:

- `../jd-copywriting-guidelines/SKILL.md` for JD 16.0 copy, UX text, marketing copy, commerce claims, price, service, rights, product selling points, naming, and review.

Optional WIP visual extensions:

- `../jd-joy-ip-guidelines/SKILL.md` for JOY, empty states, fallback pages, abnormal states, 618/Double 11/New Year JOY, props, emotion intensity, and IP character compliance.
- `../jd-app-store-marketing-guidelines/SKILL.md` for App Store activity images, store operation images, showcase images, floating entrances, activity pages, and S-level operation materials.
- `../jd-startup-icon-guidelines/SKILL.md` for startup icons, operation icons, large-promotion icons, launch screens, splash screens, JOY icon ratios, and AI star symbols.

Treat the visual extensions as optional until the user says they are finalized. If a visual task depends on a missing or WIP visual extension, state that the visual compliance result is provisional and ask whether to continue with the WIP rules.

When a task crosses domains, apply this priority: compliance and evidence gates first, then copy rules, then visual/IP rules, then creative polish.

For brand marketing copy, venue head images, operation banners, channel cards, proposal copy, or other surfaces where the user asks for livelier wording, load `references/expressive-copy-layer.md` after compliance and JD copy rules. Do not use that layer for transaction, after-sales, error, rights-rule explanation, or other high-certainty UX copy.

## Workflow

1. Intake: use `references/brief-template.md` to collect task, touchpoint, placement role, user state, business goal, core benefit, evidence, mandatories, constraints, and deliverables.
2. Classify: use `references/role-routing.md` to decide the working role and which JD guideline skill to load.
3. Gate: use `references/stage-gates.md` before moving across stages. If evidence or rules are missing, ask for them or label assumptions before drafting.
4. Strategy: define the user benefit, touchpoint task, JD brand role, conversion path, and success criteria. Avoid abstract agency language that cannot land in a JD surface.
5. Creative direction: create routes only inside JD hard constraints. Do not propose ideas that violate JOY, brand color, title length, icon ratio, service promise, price, or category rules.
6. Expression enhancement: for eligible marketing surfaces, use `references/expressive-copy-layer.md` to sharpen hooks, reader emotion, and option framing without breaking JD tone or evidence boundaries.
7. Execution: send copy tasks to `jd-copywriting-guidelines`; send visual/IP tasks to the relevant visual guideline skill. Keep output tied to the confirmed strategy and touchpoint.
8. QA: use `references/qa-checklist.md` for the final sweep. Do not approve output that is clear creatively but unsafe, off-brand, unverifiable, or not usable in the target placement.
9. Delivery: use `references/proposal-output.md` when packaging proposals, review notes, or final handoff.

## Role Discipline

- `JD Brand AE`: turns raw requests into a JD-ready brief, missing-material list, stakeholder questions, and next action.
- `JD Strategy Director`: defines the real user/business problem, touchpoint task, user benefit, evidence boundary, and message hierarchy.
- `JD Creative Director`: selects routes, protects the core idea, and keeps creative ambition inside JD brand and compliance constraints.
- `JD Copywriter`: writes or reviews through `jd-copywriting-guidelines`; may apply the expressive copy layer for eligible marketing surfaces; never bypass commerce compliance for price, product, rights, service, or category claims.
- `JD Visual Designer`: routes visual tasks to JOY, App Store marketing, startup icon, or launch-screen rules when those WIP extensions are available and intended for use; never invents a final visual compliance judgment from incomplete rules.
- `JD QA Reviewer`: performs the final review across clarity, user benefit, evidence, compliance, JD tone, visual rules, format, and delivery readiness.

## Stop Conditions

Stop and ask, or produce only a risk assessment, when:

- price, coupon, subsidy, ranking, sales, service promise, certification, effect, or category-sensitive claims lack evidence;
- JOY usage type, promotion context, prop count, emotional intensity, or scene boundary is unclear;
- visual placement, size, title length, output format, or asset source is missing;
- a requested creative idea would require changing JD hard constraints;
- the requested wording needs transaction certainty, after-sales clarity, rights-rule explanation, or error recovery rather than marketing vividness;
- the user asks for direct Feishu document edits. In that case, do not overwrite original text silently; use purple text for additions/replacements and strikethrough for removed or obsolete text.

## Output Rules

- Start with the current stage, roles used, loaded rule sources, assumptions, and missing inputs.
- For drafts, provide 3-5 meaningfully different options only when the brief supports them.
- For expressive marketing drafts, include option types such as safe direct, scene vivid, click stronger, and brand steadier when useful.
- For reviews, lead with blockers and risks before polish suggestions.
- For final outputs, include the recommended option, why it wins, risk self-check, and next action.
- Do not manufacture market data, JD rules, product proof, legal conclusions, image permissions, or asset references.
