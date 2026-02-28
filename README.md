# Day1Global-Skills

Day1Global 投资分析 Skills 共享仓库 | Day1Global Investment Analysis Skills Repository

[中文](#tech-earnings-deepdive科技股财报深度分析-skill) | [English](#tech-earnings-deepdive-tech-stock-earnings-deep-dive-skill)

---

## tech-earnings-deepdive：科技股财报深度分析 Skill

Author: [Ruby](https://x.com/Rubywang), [Star](https://x.com/starzq)

一个为 Claude 打造的科技股财报深度分析与多视角投资备忘录系统（v3.0），覆盖 **16 大分析模块**、**6 大投资哲学视角**、**多方法估值矩阵**、**反偏见框架**和**可执行决策体系**。

### 这个 Skill 能做什么？

当你向 Claude 提出科技公司财报相关问题时，该 Skill 会自动触发，提供机构级的深度分析报告，包括：

- **Key Forces 识别** — 锚定 1-3 个决定公司未来价值的决定性力量
- **16 大分析模块（A-P）** — 收入质量、盈利能力、现金流、前瞻指引、竞争格局、核心 KPI、产品与新业务、合作伙伴生态、高管团队、宏观政策、估值模型、筹码分布、长期监控变量、研发效率、会计质量、ESG 筛查
- **6 大投资哲学视角** — 质量复利（巴菲特/芒格）、想象力成长（Baillie Gifford/ARK）、基本面多空（Tiger Cubs）、深度价值（Klarman/Marks）、催化剂驱动（Tepper/Ackman）、宏观战术（Druckenmiller）
- **多方法估值矩阵** — Owner Earnings、PEG、反向 DCF、魔法公式、EV/EBITDA 行业对标、EV/Revenue + Rule of 40
- **Variant View（变异视角）** — 找出市场共识的盲点
- **反偏见框架** — 6 大认知陷阱自检、7 大财务红旗、5 大科技股盲区、Pre-Mortem 事前尸检
- **可执行决策** — Action Price、建仓节奏、加仓/减仓/清仓触发条件、长期监控清单

### 适用场景

以下类型的问题都会触发此 Skill：

| 场景 | 示例提问 |
|------|---------|
| 财报分析 | "帮我看看 NVDA 最新财报" |
| 季报解读 | "META 这季度表现如何？" |
| 持仓决策 | "该不该继续持有 MSFT？" |
| 深度研究 | "帮我做个 AAPL 的 deep dive" |
| 估值判断 | "GOOGL 现在贵不贵？" |
| 多角度分析 | "投资大师怎么看 AMZN？" |

### 安装方法

#### 方法一：通过 URL 安装（推荐）

在 Claude 对话中输入以下命令：

```
/install-skill https://github.com/Day1Global/Day1Global-Skills/raw/main/tech-earnings-deepdive.skill
```

#### 方法二：手动下载安装

1. 从本仓库下载 `tech-earnings-deepdive.skill` 文件
2. 在 Claude 对话中使用 `/install-skill` 命令并上传该文件

### 使用方法

安装后无需额外配置。直接用自然语言向 Claude 提问即可，Skill 会在识别到相关话题时自动激活。

**基本用法：**

```
帮我深度分析一下 NVDA 最新一季的财报
```

```
TSLA 这季度财报出来了，帮我做个全面的 deep dive
```

```
从多个投资大师的视角帮我看看 MSFT，现在值得买入吗？
```

**进阶用法：**

```
对比分析 GOOGL 和 META 最新财报，哪个更值得持有？
```

```
帮我建立一个 AMZN 的长期监控变量清单和 Action Trigger
```

### 分析报告结构

Skill 生成的完整报告包含以下部分：

```
1. 执行摘要与 TL;DR
2. Key Forces（决定性力量）
3. 16 大模块分析（A-P）
4. 估值矩阵（多方法 + 敏感性 + 概率加权情景）
5. 筹码分布
6. Variant View（变异视角）
7. 6 大投资哲学视角汇总
8. Pre-Mortem 与反偏见检查
9. 长期监控变量与 Action Trigger
10. 决策框架（持仓分类 / Action Price / 建仓节奏 / 仓位建议）
```

### 证据标准

该 Skill 采用三层证据体系，确保分析质量：

| 层级 | 类型 | 举例 |
|------|------|------|
| 第一层 | 一手来源 | CEO 原话、员工评价、客户评价、GitHub 活跃度、专利、招聘动向 |
| 第二层 | 事实来源 | SEC 文件（10-K/10-Q/8-K）、财报数据、法庭文件 |
| 第三层 | 观点来源 | 卖方研报、新闻分析、价格目标汇总 |

### 与其他 Skill 的协同

| Skill | 协同方式 |
|-------|---------|
| `us-value-investing` | 完成财报分析后，运行四维价值评分做交叉验证 |
| `us-market-sentiment` | 模块 J 涉及宏观情绪时联动 |
| `macro-liquidity` | 流动性环境是 Key Force 时联动 |

### 免责声明

此 Skill 生成的分析基于公开信息和模型推算，仅供研究参考，不构成投资建议。投资有风险，决策需谨慎。

---

## tech-earnings-deepdive: Tech Stock Earnings Deep Dive Skill

A comprehensive tech stock earnings analysis and multi-perspective investment memo system built for Claude (v3.0), covering **16 analysis modules**, **6 investment philosophy perspectives**, **multi-method valuation matrix**, **anti-bias framework**, and **actionable decision system**.

### What Does This Skill Do?

When you ask Claude about tech company earnings, this Skill automatically activates and generates an institutional-grade deep analysis report, including:

- **Key Forces Identification** — Pinpoint 1-3 decisive forces that determine the company's future value
- **16 Analysis Modules (A-P)** — Revenue quality, profitability, cash flow, forward guidance, competitive landscape, core KPIs, products & new businesses, partner ecosystem, executive team, macro & policy impact, valuation models, ownership distribution, long-term monitoring variables, R&D efficiency, accounting quality, ESG screening
- **6 Investment Philosophy Perspectives** — Quality Compounder (Buffett/Munger), Imaginative Growth (Baillie Gifford/ARK), Fundamental Long-Short (Tiger Cubs), Deep Value (Klarman/Marks), Catalyst-Driven (Tepper/Ackman), Macro Tactical (Druckenmiller)
- **Multi-Method Valuation Matrix** — Owner Earnings, PEG, Reverse DCF, Magic Formula, EV/EBITDA industry benchmarking, EV/Revenue + Rule of 40
- **Variant View** — Identify blind spots in market consensus
- **Anti-Bias Framework** — 6 cognitive trap self-checks, 7 financial red flags, 5 tech-specific blind spots, Pre-Mortem analysis
- **Actionable Decisions** — Action Price, position sizing cadence, add/trim/exit triggers, long-term monitoring checklist

### Use Cases

The following types of questions will trigger this Skill:

| Scenario | Example Prompt |
|----------|---------------|
| Earnings Analysis | "Analyze NVDA's latest earnings report" |
| Quarterly Review | "How did META perform this quarter?" |
| Position Decision | "Should I keep holding MSFT?" |
| Deep Research | "Give me a deep dive on AAPL" |
| Valuation Check | "Is GOOGL overvalued right now?" |
| Multi-Angle Analysis | "How would the great investors view AMZN?" |

### Installation

#### Option 1: Install via URL (Recommended)

Enter the following command in a Claude conversation:

```
/install-skill https://github.com/Day1Global/Day1Global-Skills/raw/main/tech-earnings-deepdive.skill
```

#### Option 2: Manual Download

1. Download the `tech-earnings-deepdive.skill` file from this repository
2. Use the `/install-skill` command in a Claude conversation and upload the file

### Usage

No additional configuration needed after installation. Simply ask Claude questions in natural language — the Skill activates automatically when it detects relevant topics.

**Basic Usage:**

```
Give me a deep analysis of NVDA's latest quarterly earnings
```

```
TSLA just reported earnings — do a comprehensive deep dive for me
```

```
Analyze MSFT from multiple legendary investors' perspectives. Is it a buy right now?
```

**Advanced Usage:**

```
Compare GOOGL and META's latest earnings — which one is a better hold?
```

```
Build me a long-term monitoring variable checklist and Action Triggers for AMZN
```

### Report Structure

A complete report generated by this Skill includes:

```
1.  Executive Summary & TL;DR
2.  Key Forces
3.  16-Module Analysis (A-P)
4.  Valuation Matrix (multi-method + sensitivity + probability-weighted scenarios)
5.  Ownership Distribution
6.  Variant View
7.  6 Investment Philosophy Perspectives Summary
8.  Pre-Mortem & Anti-Bias Check
9.  Long-Term Monitoring Variables & Action Triggers
10. Decision Framework (position type / Action Price / sizing cadence / allocation)
```

### Evidence Standards

The Skill enforces a three-tier evidence hierarchy to ensure analytical rigor:

| Tier | Type | Examples |
|------|------|---------|
| Tier 1 | Primary Sources | CEO quotes, employee reviews, customer feedback, GitHub activity, patents, hiring trends |
| Tier 2 | Factual Sources | SEC filings (10-K/10-Q/8-K), financial data, court documents |
| Tier 3 | Opinion Sources | Sell-side research, news analysis, price target consensus |

### Synergy with Other Skills

| Skill | How They Work Together |
|-------|----------------------|
| `us-value-investing` | Run the 4-dimension value score for cross-validation after completing earnings analysis |
| `us-market-sentiment` | Integrates when Module J involves macro sentiment |
| `macro-liquidity` | Integrates when liquidity conditions are a Key Force |

### Disclaimer

All analyses generated by this Skill are based on publicly available information and model estimates. They are for research purposes only and do not constitute investment advice. Investing involves risk — please exercise caution in your decisions.
