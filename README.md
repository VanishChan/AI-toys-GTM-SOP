# SKU GTM Asset Skill for Codex

Public Codex skill for ecommerce SKU GTM material production with:
- 72-hour SLA workflow
- platform-spec-first execution
- three-layer QA (AI/Human/Ops)
- transparent scoring and release gates

## Repository Structure

```text
codex-sku-gtm-skill/
├── sku-gtm-asset/
│   ├── SKILL.md
│   ├── SKU GTM资产产出SKILL.md
│   └── agents/
│       └── openai.yaml
├── templates/
│   ├── SKU-GTM-BRIEF-template.md
│   ├── tri-qa-scorecard-template-zh.csv
│   └── tri-qa-score-dictionary-zh.md
├── examples/
│   ├── SKU-GTM-BRIEF-simulation-v1.md
│   └── sku-gtm-comic-playbook.md
└── LICENSE
```

## Install (for any Codex user)

```bash
mkdir -p ~/.codex/skills
cp -R ./sku-gtm-asset ~/.codex/skills/sku-gtm-asset
```

Then refresh/restart Codex and check the Skills panel.

## How to Use

In Codex, run with prompt:

```text
按 SKU GTM资产产出SKILL 跑这个SKU。以下是Brief与平台要求，请输出完整交付包。
```

Recommended input artifacts:
- `templates/SKU-GTM-BRIEF-template.md`
- SKU info, target platforms, and required assets

Expected outputs:
1. Brief validation report
2. Platform specification matrix
3. AI asset execution pack (KV/main images/detail/video keyframes + prompts)
4. Challenge-ready decision cards (per key asset)
5. Three-layer QA scorecards and release verdict
6. 48h remediation plan if rejected

## Optional: Publish to GitHub

```bash
git init
git add .
git commit -m "Publish SKU GTM Codex skill"
git branch -M main
git remote add origin https://github.com/<your-account>/codex-sku-gtm-skill.git
git push -u origin main
```

## License
MIT
