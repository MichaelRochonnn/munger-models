---
name: munger-models-graph
description: >
  Use the MungerModels.com Charlie Munger mental-model knowledge graph to analyze decisions,
  investments, businesses, risks, organizations, learning plans, and personal choices through a
  cross-disciplinary latticework. Trigger when the user mentions Munger Models, 芒格思维模型,
  思维模型图谱, 多元思维模型, 多元思维格栅, Charlie Munger mental models, latticework,
  Lollapalooza, 安全边际, 护城河, 能力圈, 逆向思维, or asks to apply Munger-style models to a
  concrete problem. This skill is for graph-based analysis and model selection, not pure roleplay.
---

# Munger Models Graph

## Purpose

Use MungerModels.com as a structured mental-model graph, not as a script to imitate Charlie Munger. Build analyses by selecting a small stack of relevant models, connecting them across disciplines, and turning them into questions, risks, and actions.

When the user asks to speak "as Munger" or "用芒格口吻", combine this skill's graph-based reasoning with a separate Munger voice skill if available; do the model work first, then adjust voice.

## Quick Workflow

1. Identify the user's task type: decision review, investment analysis, business-model analysis, risk premortem, team/organization design, negotiation/influence, macro trend, learning plan, or model explanation.
2. Map the task to one or more MungerModels scenarios. Read [graph-analysis.md](references/graph-analysis.md) for scenario playbooks, central models, and source URL patterns.
3. Select 5-9 models, spanning at least 3 disciplines unless the user explicitly asks for a narrow explanation.
4. Use the graph logic:
   - High-backlink models are canonical anchors.
   - High-outgoing models are integrators that connect many neighboring ideas.
   - Scenario tags suggest practical entry points.
5. Apply the models, do not merely name-drop them. For each selected model, state the diagnostic question it forces and what it changes in the decision.
6. Include inversion: ask how the plan fails, which assumptions break, and what would cause irreversible loss.
7. End with an actionable checklist, confidence level, and "too hard / outside scope" boundary where appropriate.

## Output Pattern

For most concrete tasks, use this compact structure:

- **Verdict**: the provisional conclusion or decision posture.
- **Model Stack**: 5-9 selected models with one-line relevance.
- **Cross-Disciplinary Read**: psychological, economic/business, quantitative, and systems-risk angles.
- **Inversion / Failure Modes**: what would make this fail, what to avoid first.
- **Checklist**: specific next checks, evidence to gather, and decision gates.
- **Confidence**: what is known, unknown, and too hard.

For pure learning requests, output a study path by discipline, then a practice checklist.

## Model Selection Rules

Prefer a small, sharp model stack over a long catalog. Start with one of these anchor groups:

- **Capital allocation**: 安全边际, 能力圈, 护城河, 概率思维与期望值, 市场先生, 现金流贴现法, 会计作为商业语言.
- **Business quality**: 护城河, 规模优势, 网络效应, 转换成本, 飞轮效应, 竞争性毁灭, 激励机制.
- **Risk and resilience**: 逆向思维, 极端情景模拟, 安全边际, 冗余备份系统, 反馈环, 正常事故, 脆弱性与反脆弱性.
- **Human behavior and organizations**: 激励机制, 奖励和惩罚超级反应倾向, 社会认同倾向, 权威错误影响倾向, Lollapalooza倾向, 代理问题.
- **Learning and judgment**: 多元思维模型框架, 逆向思维, 检查清单方法, 达尔文式客观态度, 费曼技巧, 置信度校准, 知识谦逊.

When the problem has current facts, browse or search before applying the framework. Munger-style analysis is only as good as the facts beneath it.

## Source Handling

Use the site as a source map:

- Homepage: `https://mungermodels.com/`
- Full index: `https://mungermodels.com/all`
- Graph: `https://mungermodels.com/graph`
- Model page: `https://mungermodels.com/models/{model-id}`
- Discipline page: `https://mungermodels.com/disciplines/{discipline-id}`
- Scenario page: `https://mungermodels.com/scenarios/{scenario-id}`

When a user asks for exact details, quotes, FAQ content, or the latest model set, open the relevant source page. Cite the source URLs used. Paraphrase long source content; do not reproduce whole articles.
