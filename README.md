<p align="right"><a href="./README.zh-CN.md"><img src="https://img.shields.io/badge/简体中文-1F6FEB?style=flat-square" alt="简体中文" /></a></p>

# Benjamin Daoson

I build **reliable AI Agent systems**, study **LLM post-training and evaluation**, and explore **Physical AI**.

My public work is organized around three technical lines:

| 🤖 Agent Systems | 🧠 LLM & Model Systems | 🦾 Physical AI |
| --- | --- | --- |
| Runtime · state · tools · recovery · evaluation | Post-training · reward models · preference learning · multimodal evaluation | VLA · simulation · physical evidence · embodied data |

---

## Flagship projects

### 🤖 Agent Systems

<table>
<tr>
<td width="33%" valign="top">

<a href="https://github.com/Benjamindaoson/enterprise-data-agent"><img src="./assets/cards-v3/enterprise-data-agent-architecture.svg" width="100%" alt="BA Agent architecture" /></a>

### [BA Agent](https://github.com/Benjamindaoson/enterprise-data-agent) <code>FLAGSHIP</code>
**Business Intelligence & Autonomous Operations**

Long-horizon business-analysis Agent with durable task state, Semantic Layer, governed analytics, evidence verification, HITL safety, BusinessAgentBench, SFT/GRPO experiments, PostgreSQL/Redis runtime, and observability.

</td>
<td width="33%" valign="top">

<a href="https://github.com/Benjamindaoson/ai-engineering-project-os"><img src="./assets/cards-v3/ai-engineering-project-os.svg" width="100%" alt="AI Engineering Project OS architecture" /></a>

### [AI Engineering Project OS](https://github.com/Benjamindaoson/ai-engineering-project-os) <code>FLAGSHIP</code>
**Agent Harness for Long-Horizon Engineering**

Audits real repositories, identifies engineering gaps, executes changes in a controlled workspace, verifies completion with tests/evidence, persists state, recovers failures, and re-audits project maturity.

</td>
<td width="33%" valign="top">

<a href="https://github.com/Benjamindaoson/SalesBoost"><img src="./assets/cards-v3/salesboost-architecture.svg" width="100%" alt="SalesBoost architecture" /></a>

### [SalesBoost](https://github.com/Benjamindaoson/SalesBoost) <code>FLAGSHIP</code>
**Enterprise Multi-Agent Sales Platform**

Production-shaped sales enablement system spanning orchestration, Hybrid RAG, memory, evaluation, business workflows and observability.

</td>
</tr>
</table>

### 🧠 LLM & Model Systems

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/Benjamindaoson/reward-modeling-lab"><img src="https://raw.githubusercontent.com/Benjamindaoson/reward-modeling-lab/main/docs/results/figures/research_story.svg" width="100%" alt="Reward Modeling Lab research story" /></a>

### [Reward Modeling Lab](https://github.com/Benjamindaoson/reward-modeling-lab) <code>FLAGSHIP</code>
**8B Reward Model Post-training**

Single-GPU 4-bit QLoRA reward-model training followed by shortcut, ranking and robustness audits. The project focuses on whether a reward model succeeds for the right reason, not just headline pairwise accuracy.

</td>
<td width="50%" valign="top">

<a href="https://github.com/Benjamindaoson/RewardLens"><img src="https://raw.githubusercontent.com/Benjamindaoson/RewardLens/main/results/paper_analysis/four_model/figures/figure2_dependency_fingerprint.png" width="100%" alt="RewardLens dependency fingerprint" /></a>

### [RewardLens](https://github.com/Benjamindaoson/RewardLens) <code>RESEARCH</code>
**Multimodal Judge / Reward-Model Evaluation**

Controlled visual interventions test whether models with similar static accuracy actually rely on visual evidence in the same way.

</td>
</tr>
</table>

### 🦾 Physical AI

<table>
<tr>
<td width="60%" valign="top">

<a href="https://github.com/Benjamindaoson/FitGround"><img src="https://raw.githubusercontent.com/Benjamindaoson/FitGround/main/reports/figures/01_system_architecture_en.png" width="100%" alt="FitGround system architecture" /></a>

### [FitGround](https://github.com/Benjamindaoson/FitGround) <code>FLAGSHIP</code>
**Physics-Grounded Decision Engine**

Executable garment parameters → measured geometry → simulation evidence → explicit next-edit decision / abstention. Built around physical evidence rather than visual plausibility alone.

</td>
<td width="40%" valign="top">

<img src="./assets/cards-v3/smolvla-protocol.svg" width="100%" alt="SmolVLA LIBERO-Plus micro-pilot protocol" />

### SmolVLA + LIBERO-Plus Micro-Pilot <code>PRIVATE RESEARCH</code>
**VLA Adaptation Research**

Controlled initial-state OOD protocol around `lerobot/smolvla_libero`. Private while experiments are still being developed; no unverified GPU result is claimed.

</td>
</tr>
</table>

---

## Selected case studies

These are useful systems and experiments, but they are intentionally not positioned as equal to the flagship portfolio.

- [SmartOrderingAgent](https://github.com/Benjamindaoson/SmartOrderingAgent) — approval-gated restaurant reservation Agent with deterministic business writes.
- [API Test Platform](https://github.com/Benjamindaoson/api-test-platform) — Agent-assisted API quality, regression planning and evidence-based release gates.
- [StuckToShip / AIEduRAG](https://github.com/Benjamindaoson/AIEduRAG) — evidence-grounded AI engineering tutor for RAG / LangGraph / MCP learning.
- [Haole](https://github.com/Benjamindaoson/haole) — multi-Agent workspace with Redis Streams, MCP, HITL and durable events.
- [Financial Asset QA System](https://github.com/Benjamindaoson/Financial_Asset_QA_System) — deterministic financial QA pipeline with tool execution, validation and guarded synthesis.

---

## Teaching & public infrastructure

- [AI Agent Engineering Lab](https://github.com/Benjamindaoson/ai-agent-engineering-lab) — teaching repository for Agent runtime, RAG, MCP, A2A, multimodal and workflow engineering.
- [TIAI Website](https://github.com/Benjamindaoson/TIAI_website) — institutional website.
- [Personal Website](https://github.com/Benjamindaoson/daoson_website) — technical writing, project notes and public knowledge base.

---

## Portfolio principles

I try to keep public repositories explicit about the difference between:

- **implemented** vs. planned;
- **measured** vs. illustrative;
- **production-shaped** vs. production-deployed;
- **research evidence** vs. product claims.

The public portfolio is deliberately narrower than the full set of private experiments and reference repositories.

<p align="center">
  <sub><b>Build useful AI systems · run real experiments · report measured evidence.</b></sub>
</p>
