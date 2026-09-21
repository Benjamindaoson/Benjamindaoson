# Agent Systems Lab

A portfolio hub for building **reliable, long-horizon AI agent systems**.

This repository is an organizational layer: it explains the technical program, connects related projects, and provides a home for small verified demos. Flagship systems remain independent repositories with their own history, releases, tests, and documentation.

## Technical focus

- Agent runtime and harness design
- Planning, replanning, and task-state management
- Tool calling, MCP, and governed business actions
- Context, memory, checkpointing, and resume
- Failure recovery and human-in-the-loop control
- Evaluation, tracing, evidence, and regression gates
- Enterprise RAG and knowledge-grounded execution

## Featured systems

| Project | Role | Focus |
| --- | --- | --- |
| [Enterprise Data Agent](https://github.com/Benjamindaoson/enterprise-data-agent) | Flagship · independent repo | Supervisor–Executor orchestration, Semantic Layer, governed SQL, durable state, evidence verification |
| [AI Engineering Project OS](https://github.com/Benjamindaoson/ai-engineering-project-os) | Flagship · independent repo | Long-horizon repository engineering harness, verification, recovery, evidence, and re-audit |
| [Multimodal Content Creation Agent](https://github.com/Benjamindaoson/multimodal-content-creation-agent) | Flagship · independent repo | Recoverable multimodal runtime for planning, tool orchestration, evaluation, human approval, publishing, and feedback |

## Case studies

- [SalesBoost](https://github.com/Benjamindaoson/SalesBoost) — enterprise sales Agent with Hybrid RAG, workflows, evaluation, and observability.
- [SmartOrderingAgent](https://github.com/Benjamindaoson/SmartOrderingAgent) — approval-gated reservation workflow with deterministic writes.
- [API Test Platform](https://github.com/Benjamindaoson/api-test-platform) — change analysis, test generation, execution evidence, and release gates.
- [StuckToShip](https://github.com/Benjamindaoson/stuck-to-ship) — evidence-grounded learning workflow for RAG, LangGraph, and MCP.
- [haole-mas](https://github.com/Benjamindaoson/haole-mas) — event-driven multi-agent workspace with MCP and HITL.
- [Financial Asset QA System](https://github.com/Benjamindaoson/financial-asset-qa-system) — deterministic financial QA pipeline with guarded synthesis.

See the [project index](./project-index.md) for scope, status, and migration rules.

## Runtime model

```text
User / Business Goal
        |
Production Coordinator
        |
Agent Runtime
├── Planning and Replanning
├── Context, State, and Memory
├── Governed Tools
├── Checkpoint and Recovery
├── Evaluation and Tracing
└── Human Approval
        |
Domain Agent / Business System
```

## Evidence standard

Projects linked from this Hub distinguish:

- implemented behavior from roadmap items;
- measured results from illustrative examples;
- production-shaped architecture from verified production deployment;
- model output from deterministic validation;
- successful completion from evidence-backed completion.

## Repository policy

- Flagship systems stay independent.
- Small demos may be consolidated under `projects/` only after source and history review.
- A migrated repository receives a provenance note and redirect before archival.
- No repository is deleted until unique content and history are preserved.

## Status

The Hub structure and project index are active. Demo consolidation is handled as a separate migration phase.


## Governance

This Hub follows the shared status taxonomy, link-only policy, private-research boundary, and release/archive synchronization checklist in [GOVERNANCE.md](GOVERNANCE.md).
