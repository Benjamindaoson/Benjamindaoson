# Engineering Tools Lab

A hub for **AI engineering infrastructure, developer productivity, quality automation, and operational tooling**.

This Lab covers tools whose primary value is improving how systems are built, tested, reviewed, released, and maintained.

## Technical focus

- Repository intelligence and engineering automation
- API testing and release gates
- Developer workflows and evidence capture
- Career and research operations tooling
- CI/CD, reproducible environments, and observability
- Safe automation with explicit human control

## Featured tools

| Project | Role | Focus |
| --- | --- | --- |
| [AI Engineering Project OS](https://github.com/Benjamindaoson/ai-engineering-project-os) | Cross-listed flagship · independent repo | Repository audit, gap discovery, controlled execution, verification, recovery, and evidence |
| [API Test Platform](https://github.com/Benjamindaoson/api-test-platform) | Public case study · independent repo | API change analysis, regression planning, execution, and release gating |
| `career-intelligence-os` | Private active tool · independent repo | Canonical career intelligence, job research, and workflow automation system |

See the [project index](./project-index.md) for canonical ownership and consolidation plans.

## Tooling lifecycle

```text
Input / Repository / Workflow
          ↓
Structured Intake
          ↓
Plan and Controlled Execution
          ↓
Automated Checks
          ↓
Evidence and Human Review
          ↓
Release / Update / Recovery
```

## Engineering principles

- Automate repeatable checks, not unreviewed authority.
- Preserve provenance for generated and migrated artifacts.
- Treat test output and execution evidence as first-class data.
- Keep secrets and private datasets out of public repositories.
- Prefer one canonical tool per workflow over multiple overlapping demos.
- Archive historical versions only after migration is verified.

## Repository policy

Large or durable products remain independent. Small scripts and bounded utilities may move into `projects/` after dependency, license, and secret scans.


## Governance

This Hub follows the shared status taxonomy, link-only policy, private-research boundary, and release/archive synchronization checklist in [GOVERNANCE.md](GOVERNANCE.md).
