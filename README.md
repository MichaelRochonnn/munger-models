# Munger Models Graph Skill

A Codex Skill for applying the [MungerModels.com](https://mungermodels.com/) Charlie Munger mental-model knowledge graph to decisions, investments, business analysis, risk reviews, organization design, and learning plans.

This is a graph-based analysis skill, not a pure roleplay prompt. It helps Codex select and combine relevant mental models across disciplines, then turn them into diagnostic questions, failure modes, and practical checklists.

## What It Contains

- `SKILL.md` - skill trigger metadata and operating workflow.
- `references/graph-analysis.md` - parsed graph structure, central models, scenario playbooks, and source URL patterns.
- `agents/openai.yaml` - UI metadata for Codex skill discovery.

## Core Coverage

The skill is based on the public Munger Models knowledge graph:

- 232 mental models
- 14 disciplines
- 9 application scenarios
- 1,757 graph edges on the graph page

It highlights central models such as 安全边际, 护城河, 逆向思维, 能力圈, 社会认同倾向, Lollapalooza倾向, 复利效应, and 概率思维与期望值.

## Installation

Clone this repository into your Codex skills directory:

```bash
git clone https://github.com/MichaelRochonnn/munger-models.git ~/.codex/skills/munger-models-graph
```

Then start a new Codex session so the skill index can refresh.

## Usage

Example prompts:

```text
Use $munger-models-graph to analyze whether this business has a durable moat.
```

```text
用 $munger-models-graph 帮我复盘这个投资决策，重点看安全边际、能力圈和失败模式。
```

```text
用芒格思维模型图谱分析这个组织激励设计有没有代理问题。
```

## Output Style

For concrete decisions, the skill typically produces:

- Verdict
- Model Stack
- Cross-Disciplinary Read
- Inversion / Failure Modes
- Checklist
- Confidence / Too-hard boundary

## Sources

Primary source map:

- Homepage: <https://mungermodels.com/>
- Full index: <https://mungermodels.com/all>
- Graph: <https://mungermodels.com/graph>
- Model detail pages: `https://mungermodels.com/models/{model-id}`
- Scenario pages: `https://mungermodels.com/scenarios/{scenario-id}`

When exact model details or quotes matter, open and cite the relevant source page instead of relying only on the bundled summary.

## Validation

If you have the Codex skill-creator validation script available, run:

```bash
python3 ~/.codex/skills/.system/skill-creator/scripts/quick_validate.py ~/.codex/skills/munger-models-graph
```

Expected result:

```text
Skill is valid!
```
