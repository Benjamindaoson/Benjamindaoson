# Repository Cleanup — 2026-09-22

This document is the account-level cleanup ledger for the Benjamindaoson GitHub
account. The goal is not to minimize repository count blindly; it is to keep one
canonical repository per durable project or research claim.

## DELETE SAFE NOW

These repositories have no remaining unique active-project role.

### Navigation Hubs — fully migrated into the Profile repository

All source top-level files were copied into
`Benjamindaoson/Benjamindaoson/labs/`, with exact source blob SHAs recorded in
`labs/MIGRATION_MANIFEST.md`. Their README files now point to the Profile copy.

- `Agent-Systems-Lab`
- `LLM-Systems-Lab`
- `Embodied-AI-Lab`
- `AI-Research-Lab`
- `Engineering-Tools-Lab`

### Empty duplicate

- `scientific-agent` — was empty; canonical implementation is
  `ai-scientist`. A DELETE SAFE README has been added.

### Private project-collection snapshots already preserved elsewhere

- `project-collection-crossborder-ops-agent-python` — verified empty.
- `project-collection-mini-claw` — verified effectively empty.
- `project-collection-handwrite-transformer` — snapshot preserved in
  `private-reference-archive`.
- `project-collection-kimi-agent-vscode-clone` — all 104 source blobs
  accounted for in `private-reference-archive`.
- `project-collection-langchain-learning-lab` — snapshot preserved privately;
  useful teaching content also lives in `ai-agent-engineering-lab`.
- `project-collection-qidian-research-phase1` — all 6 source blobs preserved.
- `project-collection-repeat-transformer` — all 58 source blobs preserved.
- `project-collection-tiai-v0` — preserved privately; canonical site is
  `TIAI_website`.
- `project-collection-tiai-website-v1` — preserved privately; canonical site
  is `TIAI_website`.
- `project-collection-tradingagents-main` — 74/74 blobs preserved with
  upstream license and attribution; not an authored portfolio project.

### Legacy sources already copied to a canonical successor/archive

- `crossborder-ops-agent-python` — 70/70 blob snapshot preserved in
  `private-reference-archive`; active successor: `enterprise-data-agent`.
- `data-ananlysis-demo` — 50/50 blob snapshot preserved in
  `private-reference-archive`; active successor: `enterprise-data-agent`.
- `pachongliepin` — source implementation preserved under
  `career-intelligence-os/legacy_imports/liepin/`.
- `pachongjobjd` — source implementation and fixtures preserved under
  `career-intelligence-os/legacy_imports/unitree-job-crawler/`.

### Superseded websites

- `Benjamindaoson_website` — superseded by `daoson_website`.
- `gitpagewebnote` — content consolidated into `daoson_website`.

Deleting all repositories in this section would reduce the account by **22
repositories** without removing an active canonical project.

## ARCHIVE / KEEP FOR PROVENANCE

- `financial-asset-qa-system` — core RAG capabilities have been consolidated
  into FinEvidence, but the old repository still carries product history and
  should remain archived until a later history-retention decision.
- `chinese-news-classification` — maintained legacy model-systems case study.
- `trajectory-level-alignment` — withdrawn research line; keep private until
  its useful artifacts are moved into the private archive.

## MERGE NEXT — DO NOT DELETE YET

These repositories overlap with a canonical destination but still contain
unique code that must be moved before deletion.

| Source | Canonical destination | Reason |
| --- | --- | --- |
| `scrapboss` | `career-intelligence-os` | Adds Greenhouse, Ashby, Lever, ByteDance, BOSS collectors, market analysis, evidence, labeling, and source registry |
| `agentic-delivery-os` | `ai-engineering-project-os` | Delivery/runtime/governance capabilities overlap with long-horizon engineering harness |
| `design-os` | `ai-engineering-project-os` or private reference archive | Product-design specification workflow supports engineering-agent intake but is not a separate flagship |
| `shopkeeper_brain` | `finevidence-financial-rag` | Financial internal-knowledge RAG overlaps with FinEvidence document/evidence pipeline |
| `financial-reward-agentic-rl` | future private post-training experiments repo | Same training/evaluation family as the two repositories below |
| `text2sql-agentic-rl` | future private post-training experiments repo | Agentic RL experiment |
| `multimodal-chart-gspo` | future private post-training experiments repo | Multimodal preference/post-training experiment |

## CANONICAL KEEP

### Public flagships / research flagships

- `enterprise-data-agent`
- `ai-engineering-project-os`
- `multimodal-content-creation-agent`
- `finevidence-financial-rag` (FinEvidence)
- `reward-modeling-lab`
- `RewardLens`
- `FitGround`
- `Embodied-DataOps`

### Public case studies / products

- `SalesBoost`
- `haole-mas`
- `api-test-platform`
- `SmartOrderingAgent`
- `stuck-to-ship`
- `huisen-ai-adaptive-algorithm-coach`
- `ai-investment-research-assistant`
- `ai-agent-engineering-lab`
- `ai-scientist`

### Public infrastructure

- `Benjamindaoson`
- `daoson_website`
- `TIAI_website`

### Private canonical / active research

- `career-intelligence-os`
- `private-reference-archive`
- `academic-agent`
- `StateLegacy-E0`
- `smolvla-libero-plus-micro-pilot`
- `bazi-core`

## Target

After deleting the 22 DELETE SAFE repositories, the account moves from roughly
58 repositories to roughly **36**.

The next merge wave is intended to reduce the remaining count into the
**high-20s / low-30s** while preserving distinct flagship, product, and research
boundaries.
