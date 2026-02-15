---
name: "asset-factory-v1"
description: "Use when the task is to run GTM material production for ecommerce SKUs with a 72-hour SLA, role-based SOP, platform-spec-first workflow, and three-layer QA (AI/Human/Ops) with transparent scoring that prioritizes GTM expression accuracy."
---

# Asset Factory v1

## When to use
- New SKU launch, campaign refresh, or material overhaul for ecommerce channels.
- Need standardized output across CN platforms (Tmall/JD/Douyin/Xiaohongshu/Dewu) and global platforms (Amazon/Shopify/TikTok Shop).
- Need dual QA (AI + Human) with challenge mechanism and traceable scoring.
- Need three-layer QA (AI + Human + Ops/agency) with challenge mechanism and traceable scoring.

## Required inputs
- Brief card (must include ICP, scenario, pain point, value proposition, and claim-evidence mapping)
- Budget guardrail card (can be non-precise at SKU start)
- Platform scope (selected channels)

## Workflow (strict order)
1. Intake brief and validate completeness.
2. Generate platform requirement matrix before any asset production.
3. Generate AI asset production pack for KV/main images/detail scenes/video keyframes:
   - Visual description
   - Layout instruction
   - Copy placement map
   - Claim-evidence mapping
   - Ready-to-run image prompts
4. Integrate design and export platform-adapted packages.
5. Run AI QA scoring first.
6. Run Human QA decision second.
7. Run Ops QA decision third (operability gate).
8. If disagreement exists, run one challenge round only.
9. Archive scores, disagreements, and final decision for retrospective.

## Challenge-ready decision card (required for each key asset)
For each key asset (KV/main image/detail page/video keyframe), always provide a decision card that can be challenged by GTM-PM:
- Why this asset exists (funnel role and objective)
- Strategic role in the set (hook/proof/trust/conversion)
- Copy logic (title/subtitle/order rationale)
- Evidence source mapping (claim -> verifiable evidence)
- Platform adaptation rationale (ratio/information density/layout)
- Risk forecast (misalignment/overclaim/return risk)
- Alternative option (at least one fallback direction)
- Challenge response guide (editable vs non-editable vs impact)

## Roles and responsibilities
- GTM-PM (Human A): owns scope, timeline, final sign-off.
- GTM-AI Co-PM (AI B): monitors scope drift and timeline risk.
- Platform Spec AI: outputs per-platform requirements and required asset list.
- Asset Producer: photo/video/raw assets and first-pass copy.
- Design Integrator: final layouts and ratio-compliant exports.
- AI QA: scores with transparent rules.
- Human QA: business and brand decision.
- Ops QA: operability and campaign handoff decision.

## Guardrails
- No platform matrix -> do not start production.
- No AI QA report -> do not enter Human QA.
- No Human QA pass -> do not enter Ops QA.
- No Ops QA pass -> cannot release.
- Redline issue present -> cannot release.
- Maximum one challenge loop to preserve speed.

## SLA and exit criteria
- End-to-end SLA: <=72h
- AI QA score >=85 and no redline
- Human QA approves
- Ops QA score >=80

## Scoring policy (summary)
- Use two layers: Asset-level first, then SKU-level aggregation.
- AI QA total = 100
- Dimensions: GTM expression accuracy (40), platform compliance/adaptation (25), visual consistency (15), conversion orientation (10), asset completeness (10)
- Ops QA must include truth-in-claims checks (product-description consistency and return-risk signals).
- All deductions and bonuses must be explicit and logged with evidence.

## Deliverables
- Platform requirement matrix
- AI asset production pack (with image prompts)
- Challenge-ready decision cards (one per key asset)
- Platform-ready asset package
- Product one-pager (CN+EN when required)
- Product manual (CN+EN when required)
- KOL/KOC brief
- AI QA score report
- Human QA decision note
- Ops QA decision note
- Retrospective entry with top defects and rule updates
