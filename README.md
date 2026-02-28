# Day1Global-Skills

Day1Global 投资分析 Skills 共享仓库。

---

## tech-earnings-deepdive：科技股财报深度分析 Skill

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
