<div align="center">

# LLM Algorithms × Agent Systems

**Model training, alignment and evaluation — plus production-grade agent systems.**

I build across both sides of modern AI engineering: **training and evaluating models**, and **turning them into reliable agent systems**.

[Portfolio](https://benjamindaoson.github.io/) · [Repositories](https://github.com/Benjamindaoson?tab=repositories)

</div>

---

## LLM Algorithms

<table>
<tr>
<td width="33.33%" valign="top">

### [01 · Reward Modeling Lab](https://github.com/Benjamindaoson/reward-modeling-lab)

**Reward Modeling · Preference Learning**

Real 8B reward-model post-training on a single NVIDIA A10 with 4-bit QLoRA.

**50.42% → 91.35%** held-out pairwise accuracy, followed by length-shortcut, ranking, truncation and checkpoint audits.

`QLoRA` `Pairwise Loss` `Ranking Eval` `Reward Audit`

</td>
<td width="33.33%" valign="top">

### 02 · Policy Optimization Lab

**SFT · Preference Optimization · RL**

Research track for the policy side of post-training: supervised adaptation, preference optimization and reinforcement-learning-based improvement.

Focus: **DPO / GRPO, reward design, policy evaluation and reward-hacking diagnostics**.

`SFT` `DPO` `GRPO` `Policy Eval`

<sub>ACTIVE RESEARCH · public release after reproducible results</sub>

</td>
<td width="33.33%" valign="top">

### 03 · Verifier & Multimodal RL

**Verifier Learning · Reasoning · Multimodal RL**

Research track for learning signals beyond a single scalar reward: verifier-based evaluation, reasoning quality and multimodal policy learning.

Focus: **process / outcome verification, hard negatives, controlled evaluation and multimodal reward signals**.

`Verifier` `Reasoning` `Multimodal` `RL`

<sub>ACTIVE RESEARCH · public release after reproducible results</sub>

</td>
</tr>
</table>

**LLM coverage:** data → SFT / LoRA → preference learning → reward modeling → policy optimization → verifier → robustness evaluation.

---

## Agent Systems

<table>
<tr>
<td width="33.33%" valign="top">

### [01 · SalesBoost](https://github.com/Benjamindaoson/SalesBoost)

**Enterprise Agent Application**

End-to-end multi-agent sales intelligence platform spanning training, battle preparation, live assistance and evaluation.

`LangGraph` `Hybrid RAG` `Memory` `Evaluation` `Observability`

**Proves:** business workflow design, orchestration, retrieval, memory and production-shaped AI application engineering.

</td>
<td width="33.33%" valign="top">

### [02 · Haole](https://github.com/Benjamindaoson/haole)

**Agent Runtime & Workspace**

Durable multi-agent workspace built around explicit task contracts, skills, MCP tools, HITL and replayable events.

`MCP` `Skills` `Redis Streams` `SSE` `PostgreSQL`

**Proves:** runtime design, durable execution, tool infrastructure and human-controlled agent workflows.

</td>
<td width="33.33%" valign="top">

### [03 · Enterprise Data Agent](https://github.com/Benjamindaoson/enterprise-data-agent)

**Data Intelligence Agent**

Turns business questions into governed execution, observations, claims, evidence and validated reports.

`Semantic Layer` `DuckDB` `Evidence` `Validation` `FastAPI`

**Proves:** structured investigation, data reasoning, evidence lineage and trustworthy agent execution.

</td>
</tr>
</table>

**Agent coverage:** intent → planning → retrieval / tools → state / memory → durable execution → evidence → evaluation → recovery.

---

## More Engineering

<table>
<tr>
<td width="33.33%" valign="top">

### [Huisen AI](https://github.com/Benjamindaoson/huisen-ai-adaptive-algorithm-coach)
**Adaptive AI Learning System**

Mentor agent + code execution + transfer verification + longitudinal learning evidence.

</td>
<td width="33.33%" valign="top">

### [Financial Asset QA](https://github.com/Benjamindaoson/Financial_Asset_QA_System)
**Trustworthy Financial AI**

Deterministic data pipeline with grounded numerical generation and response guardrails.

</td>
<td width="33.33%" valign="top">

### [AI Agent Engineering Lab](https://github.com/Benjamindaoson/ai-agent-engineering-lab)
**Agent Engineering Lab**

Runnable projects covering ReAct, deep research, MCP, A2A, workflows and agent application patterns.

</td>
</tr>
</table>

---

## Technical Coverage

| LLM Algorithms | Agent Engineering | Systems |
|---|---|---|
| SFT · LoRA / QLoRA | LangGraph · Multi-Agent | Python · FastAPI |
| Reward Modeling | Tool Use · MCP · Skills | PostgreSQL · Redis |
| Preference Learning | Memory · Context · HITL | Qdrant · DuckDB |
| DPO / GRPO | Hybrid RAG · Reranking | Docker · Nginx |
| Verifier / Evaluation | Durable Execution | OpenTelemetry · Prometheus |
| Robustness / Shortcut Audit | Agent Evaluation · Recovery | React · Next.js · Vue |

---

## Research

**How should models and agents learn from failure rather than merely avoid it?**

- How should corrective supervision change a model, and **where** should that update happen?
- How should an agent **attribute a failure before choosing a recovery strategy**?
- How should embodied policies learn from **unsuccessful trajectories and action-level feedback**?

---

## Evidence Standard

```text
Build → Run → Measure → Attack → Diagnose → Improve
```

Public claims on this profile are intended to be traceable to **code, experiments, tests, artifacts or execution evidence**. Research tracks remain labeled as research until reproducible results are ready for public release.

---

<div align="center">

**LLM Algorithms · Agent Systems · Reliable AI Engineering**

[Portfolio](https://benjamindaoson.github.io/) · [All Projects](https://github.com/Benjamindaoson?tab=repositories)

</div>
