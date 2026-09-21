<p align="right"><a href="./README.md"><img src="https://img.shields.io/badge/English-1F6FEB?style=flat-square" alt="English" /></a></p>

# 赖建铭 · Benjamin Daoson

我主要构建 **可靠智能体系统**，研究 **LLM 后训练与评估**，并探索 **Physical AI**。

作品集只突出三条技术主线：**智能体系统、大模型与模型系统、Physical AI**。5 个 Hub 负责导航与研究地图，6 个代表项目继续保留独立仓库。

## AI Systems Lab

| Hub | 技术范围 |
| --- | --- |
| [Agent Systems Lab](https://github.com/Benjamindaoson/Agent-Systems-Lab) | Agent Runtime、Harness、规划、工具、记忆、恢复、评测与企业级 RAG |
| [LLM Systems Lab](https://github.com/Benjamindaoson/LLM-Systems-Lab) | 后训练、奖励模型、偏好优化、鲁棒性与多模态 Judge |
| [Embodied AI Lab](https://github.com/Benjamindaoson/Embodied-AI-Lab) | VLA、机器人学习、具身数据、遥操作、仿真与真机评测 |
| [AI Research Lab](https://github.com/Benjamindaoson/AI-Research-Lab) | 研究问题、Benchmark、受控实验与论文型研究产物 |
| [Engineering Tools Lab](https://github.com/Benjamindaoson/Engineering-Tools-Lab) | AI 工程基础设施、开发者效率、Release Gate 与自动化 |

Hub 只负责组织和解释，不吸收独立旗舰仓库。

---

## 6 个代表项目

### 🤖 智能体系统

<table>
<tr>
<td width="33%" valign="top">

<a href="https://github.com/Benjamindaoson/enterprise-data-agent"><img src="./assets/cards-v3/enterprise-data-agent-architecture.svg" width="100%" alt="Enterprise Data Agent 架构" /></a>

### [Enterprise Data Agent](https://github.com/Benjamindaoson/enterprise-data-agent) <code>旗舰项目</code>
**企业数据分析与自主运营**

长程商业分析 Agent：持久任务状态、Semantic Layer、受治理分析、证据验证、HITL 安全、BusinessAgentBench、PostgreSQL/Redis Runtime 与可观测性。

</td>
<td width="33%" valign="top">

<a href="https://github.com/Benjamindaoson/ai-engineering-project-os"><img src="./assets/cards-v3/ai-engineering-project-os.svg" width="100%" alt="AI Engineering Project OS 架构" /></a>

### [AI Engineering Project OS](https://github.com/Benjamindaoson/ai-engineering-project-os) <code>旗舰项目</code>
**长程工程 Agent Harness**

读取真实代码仓库，识别工程缺口，在受控工作区执行修改，通过测试与证据验证完成状态，支持持久化、失败恢复和重新审计。

</td>
<td width="33%" valign="top">

<a href="https://github.com/Benjamindaoson/multimodal-content-creation-agent"><img src="./assets/cards-v3/multimodal-content-agent.svg" width="100%" alt="多模态内容生产智能体架构" /></a>

### [多模态内容生产智能体](https://github.com/Benjamindaoson/multimodal-content-creation-agent) <code>旗舰项目</code>
**可恢复的多模态生产 Runtime**

完成脚本与分镜规划，编排文本、图像、语音和视频工具，持久化长程任务，评估生成结果，通过人工审核门，并记录发布反馈。

</td>
</tr>
</table>

### 🧠 大模型与模型系统

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/Benjamindaoson/reward-modeling-lab"><img src="https://raw.githubusercontent.com/Benjamindaoson/reward-modeling-lab/main/docs/results/figures/research_story.svg" width="100%" alt="Reward Modeling Lab 实验故事图" /></a>

### [Reward Modeling Lab](https://github.com/Benjamindaoson/reward-modeling-lab) <code>旗舰项目</code>
**8B 奖励模型后训练**

单卡 4-bit QLoRA 奖励模型训练，并继续进行 shortcut、ranking 与 robustness 审计，重点判断模型是否“因为正确的原因”取得高分。

</td>
<td width="50%" valign="top">

<a href="https://github.com/Benjamindaoson/RewardLens"><img src="https://raw.githubusercontent.com/Benjamindaoson/RewardLens/main/results/paper_analysis/four_model/figures/figure2_dependency_fingerprint.png" width="100%" alt="RewardLens dependency fingerprint" /></a>

### [RewardLens](https://github.com/Benjamindaoson/RewardLens) <code>研究旗舰</code>
**多模态 Judge / Reward Model 评估**

通过受控视觉干预研究：静态准确率相同的模型，是否真的以相同方式依赖视觉证据。

</td>
</tr>
</table>

### 🦾 Physical AI

<table>
<tr>
<td width="100%" valign="top">

<a href="https://github.com/Benjamindaoson/FitGround"><img src="https://raw.githubusercontent.com/Benjamindaoson/FitGround/main/reports/figures/01_system_architecture_en.png" width="100%" alt="FitGround 系统架构" /></a>

### [FitGround](https://github.com/Benjamindaoson/FitGround) <code>旗舰项目</code>
**基于物理证据的决策引擎**

可执行纸样参数 → 实测几何 → 仿真证据 → 显式下一版修改决策或拒答。

</td>
</tr>
</table>

当前 Physical AI 建设项目：[Embodied-DataOps](https://github.com/Benjamindaoson/Embodied-DataOps) 以 **Active Build** 身份收录于 [Embodied AI Lab](https://github.com/Benjamindaoson/Embodied-AI-Lab)。私有研究只描述方向，不提供不可访问链接。

---

## 精选案例项目

这些项目有独立价值，但不会和旗舰项目放在同一层级竞争注意力。

- [SalesBoost](https://github.com/Benjamindaoson/SalesBoost) — 覆盖 Hybrid RAG、业务流程、评估与可观测性的企业级多智能体销售平台。
- [SmartOrderingAgent](https://github.com/Benjamindaoson/SmartOrderingAgent) — 显式确认、事务安全、受控写操作的餐厅订位 Agent。
- [API Test Platform](https://github.com/Benjamindaoson/api-test-platform) — 面向 API 质量的变更影响分析、测试生成、执行和 Release Gate。
- [StuckToShip](https://github.com/Benjamindaoson/stuck-to-ship) — 面向 RAG、LangGraph 与 MCP 学习过程的证据驱动 AI 工程导师。
- [haole-mas](https://github.com/Benjamindaoson/haole-mas) — Redis Streams、MCP、HITL 与耐久事件驱动的多智能体工作台。
- [Financial Asset QA System](https://github.com/Benjamindaoson/financial-asset-qa-system) — 金融 QA 的确定性流水线、工具执行、数据校验与受控生成。

## 教学与公开基础设施

- [AI Agent Engineering Lab](https://github.com/Benjamindaoson/ai-agent-engineering-lab) — Agent Runtime、RAG、MCP、A2A、多模态与工作流工程教学仓。
- [TIAI Website](https://github.com/Benjamindaoson/TIAI_website) — 机构网站。
- [个人网站](https://github.com/Benjamindaoson/daoson_website) — 技术文章、项目记录与公开知识库。

## 作品集原则

公开仓库明确区分：

- **已实现** 与计划；
- **已测量** 与示意值；
- **生产形态** 与真实生产部署；
- **研究证据** 与产品宣传。

<p align="center">
  <sub><b>构建有用的 AI 系统 · 做真实实验 · 只报告可验证结果。</b></sub>
</p>
