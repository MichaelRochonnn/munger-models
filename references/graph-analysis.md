# MungerModels.com Graph Analysis

Source checked: 2026-06-11. Primary sources: `https://mungermodels.com/`, `https://mungermodels.com/all`, `https://mungermodels.com/graph`, and representative model/scenario pages.

## Contents

- Source Structure
- Disciplines
- Scenarios
- Central Models
- Graph Reading
- Scenario Playbooks
- Source URL Patterns

## Source Structure

- Homepage presents the project as an open learning platform for Charlie Munger's multidisciplinary mental models, organized as a searchable, navigable, cross-linked graph.
- Homepage metrics: 232 models, 14 disciplines, 9 application scenarios, 1.52 million Chinese characters, and 1,915 "double-chain" relationships.
- Graph page title and embedded data: 232 nodes and 1,757 graph edges. When precision matters, state that homepage and graph page relationship counts differ; use the graph page for topology.
- Full index page: model table with discipline, scenario tags, importance, outgoing related count, and backlink count.
- Model pages: long-form explanation, FAQ, related models, backlinks, word count, and source URL.

## Disciplines

| ID | Discipline | Count | Graph Role |
|---|---:|---:|---|
| meta | 元认知与思维方法论 | 25 | Thinking about thinking: inversion, checklists, falsification, latticework. |
| psych | 心理学 | 31 | Human misjudgment, incentives, social proof, bias cascades. |
| math | 数学与统计学 | 20 | Probability, expected value, compounding, Bayesian updating, distributions. |
| econ | 微观经济学 | 23 | Incentives, market structure, opportunity cost, moral hazard. |
| physics | 物理学与化学 | 18 | Critical mass, entropy, feedback, phase changes, constraints. |
| bio | 生物学与进化论 | 20 | Selection, niches, coevolution, robustness, adaptation. |
| eng | 工程学 | 17 | Redundancy, safety margin, quality control, coupling, failure design. |
| complex | 复杂系统与决策科学 | 8 | Emergence, nonlinear effects, resilience, system dynamics. |
| mgmt | 管理学与商业 | 19 | Moats, scale, network effects, culture, business systems. |
| invest | 投资学与金融学 | 9 | Margin of safety, intrinsic value, Mr. Market, capital allocation. |
| accounting | 会计学 | 11 | Cash flow, earnings quality, liabilities, depreciation, goodwill. |
| law | 法学与政治学 | 13 | Agency, fiduciary duty, adversarial process, institutions. |
| history | 历史学与哲学 | 13 | Cycles, pragmatism, empiricism, historical pattern recognition. |
| decision | 投资原则与品格 | 5 | Humility, patience, independence, risk-first discipline. |

## Scenarios

| ID | Scenario | Count | Core Question |
|---|---:|---:|---|
| s1 | 投资决策与资产评估 | 65 | 该不该买？值多少钱？风险在哪里？ |
| s2 | 企业竞争力与商业模式分析 | 51 | 为什么值钱？护城河多宽？能维持多久？ |
| s3 | 团队管理与组织决策 | 42 | 如何激励？如何设计？如何避免失效？ |
| s4 | 风险识别与系统韧性 | 49 | 怎样会崩？脆弱点？如何增强韧性？ |
| s5 | 个人重大决策与人生规划 | 41 | 长期后果？可逆吗？机会成本？ |
| s6 | 商业创新与竞争战略 | 37 | 如何创新？如何抢占？如何防守？ |
| s7 | 谈判、说服与人际影响 | 22 | 理解动机？博弈策略？心理基础？ |
| s8 | 市场趋势与宏观判断 | 38 | 方向？泡沫？周期拐点？ |
| s9 | 学习、复盘与认知提升 | 69 | 如何学以致用？如何从经验中学习？ |

## Central Models

Interpretation:

- Backlinks show how often other models point to a model. High backlinks mean "canonical anchor."
- Related count shows outgoing curated links. High outgoing count means "integrator" or "map-making model."
- Total degree is useful for choosing the first layer of an analysis.

| Model | Discipline | Out | Back | Use It For |
|---|---|---:|---:|---|
| 安全边际 | 投资学与金融学 | 12 | 98 | Irreversible loss, valuation buffer, engineering-style redundancy. |
| 护城河（Moat） | 管理学与商业 | 12 | 97 | Durable advantage, business quality, pricing power. |
| 逆向思维 | 元认知与思维方法论 | 8 | 89 | Premortems, avoiding stupidity, failure-first design. |
| 能力圈 | 投资学与金融学 | 15 | 67 | Scope discipline, "too hard" pile, opinion qualification. |
| 避免不一致性倾向 | 心理学 | 7 | 70 | Commitment traps, denial, sunk narratives. |
| 社会认同倾向 | 心理学 | 7 | 67 | Bubbles, herd behavior, groupthink, FOMO. |
| 复利效应 | 数学与统计学 | 9 | 60 | Long-term accumulation, flywheels, compounding knowledge. |
| Lollapalooza倾向 | 心理学 | 11 | 55 | Multiple biases reinforcing into extreme outcomes. |
| 概率思维与期望值 | 数学与统计学 | 12 | 51 | Betting logic, decision under uncertainty, expected value. |
| 奖励和惩罚超级反应倾向 | 心理学 | 7 | 53 | Incentive-caused behavior and incentive-caused blindness. |
| 激励机制 | 微观经济学 | 8 | 46 | Mechanism design, agency, behavior prediction. |
| 自视过高的倾向 | 心理学 | 7 | 45 | Overconfidence, ownership bias, poor calibration. |
| 被剥夺超级反应倾向 | 心理学 | 7 | 35 | Loss aversion, scarcity, backlash, FOMO. |
| 竞争性毁灭 | 微观经济学 | 8 | 32 | Disruption that destroys demand categories, not just competitors. |
| 飞轮效应 | 管理学与商业 | 9 | 29 | Reinforcing business loops, compounding operational advantage. |
| 规模优势 | 微观经济学 | 8 | 28 | Cost, distribution, data, brand, or purchasing scale. |
| 进化论 | 生物学与进化论 | 8 | 28 | Selection pressure, adaptation, competition, extinction. |
| 检查清单方法 | 元认知与思维方法论 | 10 | 22 | Error prevention, repeated decisions, operations discipline. |
| 网络效应 | 管理学与商业 | 9 | 22 | Multi-sided markets, user-value loops, platform defensibility. |
| 机会成本 | 微观经济学 | 9 | 21 | Best alternative forgone, capital allocation, life choices. |

## Graph Reading

The graph clusters around a defensive decision core: avoid permanent loss, stay inside competence, demand margin of safety, and invert before acting. Psychology models explain why smart people violate these rules. Math/statistics models force probabilistic thinking. Engineering and complex-systems models reveal failure propagation. Business, economics, investing, accounting, and law translate the lattice into capital allocation and institution design.

Use at least four lenses on nontrivial problems:

1. **Psychological lens**: What bias, incentive, social pressure, or commitment trap is active?
2. **Economic lens**: Who is rewarded for what? What is the opportunity cost? What market structure matters?
3. **Quantitative lens**: What are the base rates, expected value, sample-size issues, and downside asymmetry?
4. **Systems lens**: What feedback loops, coupling, thresholds, or hidden failure modes can amplify the outcome?

Add accounting/legal/history lenses when the case involves financial statements, contracts/institutions, or cyclical human behavior.

## Scenario Playbooks

### Investment and Asset Valuation

Start with: 安全边际, 能力圈, 概率思维与期望值, 护城河, 市场先生, 内在价值, 现金流贴现法, 会计作为商业语言及其局限, 风险优先.

Questions:

- What would make this a permanent capital loss?
- Is the thesis inside the evaluator's competence, or just familiar vocabulary?
- What is the gap between price and conservative intrinsic value?
- Is return driven by business performance, multiple expansion, or market mood?
- Which accounting numbers are cash reality, and which are model artifacts?

### Business Model and Competitive Advantage

Start with: 护城河, 规模优势, 网络效应, 转换成本, 飞轮效应, 竞争性毁灭, 价格弹性与定价权, 激励机制, 监管作为护城河.

Questions:

- Is the moat widening, narrowing, or merely asserted?
- Which loop compounds advantage without requiring heroic execution?
- Could a substitute destroy the demand category instead of competing within it?
- Who captures the surplus: company, customers, suppliers, platforms, or regulators?

### Team, Organization, and Incentives

Start with: 激励机制, 奖励和惩罚超级反应倾向, 激励结构与代理问题, 社会认同倾向, 权威错误影响倾向, Lollapalooza倾向, 检查清单方法, 信托责任.

Questions:

- What behavior is actually rewarded, regardless of stated values?
- Where do local incentives harm global outcomes?
- Which decisions need adversarial review or independent verification?
- What checklist prevents repeated predictable errors?

### Risk, Failure, and System Resilience

Start with: 逆向思维, 极端情景模拟, 安全边际, 冗余备份系统, 反馈环, 紧耦合与松耦合, 正常事故, 脆弱性与反脆弱性, 熵增定律.

Questions:

- How does this fail if several small things go wrong together?
- What breaks first, and is that break reversible?
- Where is the system tightly coupled with no slack?
- Which redundancy is cheap relative to the cost of failure?

### Personal Major Decisions

Start with: 机会成本, 二阶效应, 能力圈, 逆向思维, 被剥夺超级反应倾向, 沉没成本, 耐心与纪律, 知识谦逊.

Questions:

- What is the best alternative being sacrificed?
- What are the second-order consequences after the obvious first outcome?
- Is the decision reversible, partially reversible, or irreversible?
- Is the motivation fear of missing out, ego, envy, or genuine fit?

### Innovation and Strategy

Start with: 竞争性毁灭, 飞轮效应, 网络效应, 临界质量, 规模优势, 进化论, 路径依赖与锁定, 反馈环, 护城河.

Questions:

- What new behavior or technology could make incumbents irrelevant?
- What minimum scale or critical mass changes system behavior?
- Does the strategy create a self-reinforcing loop or a one-time gain?
- What mutation-selection process is operating in the market?

### Negotiation, Persuasion, and Influence

Start with: 激励机制, 互惠倾向, 社会认同倾向, 受简单联想影响的倾向, 对比错误反应倾向, 权威错误影响倾向, 博弈论基础.

Questions:

- What does each party truly want to avoid losing?
- Which reference point anchors the negotiation?
- What incentive-compatible offer makes cooperation easier than defection?
- What social proof or authority signal is distorting judgment?

### Market Trends and Macro Judgment

Start with: 社会认同倾向, Lollapalooza倾向, 回归均值, 幂律分布, 反馈环, 历史周期, 过度乐观倾向, 贝叶斯更新.

Questions:

- Which claims depend on extrapolating a recent trend?
- Are several biases pushing in the same direction?
- What base rate or historical analogy contradicts the story?
- How should the prior probability change after new evidence?

### Learning, Review, and Cognitive Upgrade

Start with: 多元思维模型框架, 逆向思维, 检查清单方法, 达尔文式客观态度, 可证伪性标准, 费曼技巧, 置信度校准, 终身学习.

Questions:

- Which disciplines are missing from the explanation?
- What evidence would disprove the current view?
- Can the idea be explained simply without jargon?
- What prediction or decision can be tracked for calibration?

## Source URL Patterns

- Full index: `https://mungermodels.com/all`
- Graph: `https://mungermodels.com/graph`
- Model detail: `https://mungermodels.com/models/{model-id}`
- Discipline: `https://mungermodels.com/disciplines/{discipline-id}`
- Scenario: `https://mungermodels.com/scenarios/{scenario-id}`

Open exact pages when the user needs source-grounded details, exact names, FAQs, or direct model explanations.
