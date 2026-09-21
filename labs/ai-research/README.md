# AI Research Lab

A cross-cutting hub for **research questions, benchmarks, controlled experiments, and paper-oriented artifacts**.

This Lab does not duplicate project code. It organizes research by claim, evidence, and evaluation design across Agent Systems, LLM Systems, and Physical AI.

## Research themes

1. **Reliable long-horizon agents** — state, recovery, tool safety, trajectory evaluation, and learning from failures.
2. **Reward and judge evaluation** — whether identical static accuracy can hide different evidence dependence.
3. **Embodied adaptation** — whether behaviorally matched checkpoints prefer the same parameter-efficient adaptation family under the same OOD shift.
4. **Evidence-grounded reasoning** — claim–evidence alignment, independent coverage, and abstention.
5. **Scientific agents** — adaptive experiment selection under hierarchical evidence and fixed budgets.

## Featured research artifacts

| Project | Research contribution | Canonical repository |
| --- | --- | --- |
| RewardLens | Controlled intervention profiles for multimodal judges | [RewardLens](https://github.com/Benjamindaoson/RewardLens) |
| Reward Modeling Lab | Reward-model training plus shortcut and robustness audits | [reward-modeling-lab](https://github.com/Benjamindaoson/reward-modeling-lab) |
| FitGround | Decision-making from physical measurements and simulation evidence | [FitGround](https://github.com/Benjamindaoson/FitGround) |
| Enterprise Data Agent | Agent reliability, governed analytics, and evidence verification | [enterprise-data-agent](https://github.com/Benjamindaoson/enterprise-data-agent) |

See the [research index](./research-index.md) for maturity labels and evidence gates.

## Research lifecycle

```text
Problem
  → Falsifiable hypothesis
  → Frozen protocol
  → Baselines and controls
  → Main result
  → Diagnostic interventions
  → Uncertainty and limitations
  → Reproducible artifact
```

## Maturity labels

- **Released** — public artifact with a stable protocol and measured results.
- **Active research** — the question and protocol exist; experiments are incomplete.
- **Incubator** — exploratory work without a frozen public claim.
- **Archived** — preserved for provenance but no longer an active research line.

## Research integrity

The Lab does not treat a roadmap, synthetic illustration, or planned experiment as a result. Public claims must be traceable to code, data, or a clearly documented evaluation artifact.


## Governance

This Hub follows the shared status taxonomy, link-only policy, private-research boundary, and release/archive synchronization checklist in [GOVERNANCE.md](GOVERNANCE.md).
