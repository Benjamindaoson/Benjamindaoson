# Repository Cleanup — Revised 2026-09-22

This ledger distinguishes **preserved elsewhere** from **should be deleted**.
Migration safety is not the same as deletion value.

## KEEP — independent public/navigation value

- `Agent-Systems-Lab` — public landing page for Agent systems.
- `LLM-Systems-Lab` — public landing page for post-training/model systems.
- `Embodied-AI-Lab` — public landing page for Physical AI.
- `AI-Research-Lab` — cross-cutting research map and protocol index.
- `Engineering-Tools-Lab` — developer/engineering tooling map.
- `scientific-agent` — canonical public-name destination for the AI Scientist consolidation.
- `Benjamindaoson_website` — archived public website history; deleting can break old public URLs.
- `gitpagewebnote` — archived public notes/history and redirect surface; deleting can break old URLs.

The Profile repository also mirrors the five Lab pages for account-level navigation.
Those mirrors are convenience copies, not replacement reasons to delete the Labs.

## KEEP ARCHIVED / HISTORICAL — useful provenance

- `scrapboss` — focused multi-source job-market research tool; full snapshot also preserved in `career-intelligence-os`.
- `crossborder-ops-agent-python` — production-shaped FastAPI business-Agent backend and evolution provenance for `enterprise-data-agent`.
- `data-ananlysis-demo` — UI/data-analysis prototype and Figma-origin design history.
- `pachongliepin` — source-specific crawler prototype; implementation also preserved in Career Intelligence OS.
- `pachongjobjd` — source-specific position-catalog crawler and fixtures; also preserved in Career Intelligence OS.
- `project-collection-qidian-research-phase1` — bounded real crawler/research artifact; keep archived unless the entire research line is intentionally retired.
- `project-collection-repeat-transformer` — substantial handwritten Transformer / LLM teaching course; potential future standalone educational asset.
- `project-collection-tiai-v0` — optional historical website snapshot.
- `project-collection-tiai-website-v1` — optional historical website snapshot.

## DELETE CANDIDATES — genuinely redundant or empty

These are the strongest deletion candidates because the standalone repository adds little beyond an already verified preserved copy.

1. `project-collection-crossborder-ops-agent-python`
   - verified empty / 0 blobs.

2. `project-collection-mini-claw`
   - verified effectively empty / 0 project blobs.

3. `project-collection-handwrite-transformer`
   - tiny placeholder, not the real Transformer implementation;
   - exact placeholder snapshot preserved privately.

4. `project-collection-kimi-agent-vscode-clone`
   - private reference snapshot;
   - all 104 original blobs accounted for in `private-reference-archive`.

5. `project-collection-langchain-learning-lab`
   - learning snapshot already preserved privately;
   - useful teaching material is also consolidated into `ai-agent-engineering-lab`.

6. `project-collection-tradingagents-main`
   - third-party reference snapshot rather than authored project;
   - 74/74 blobs preserved with upstream license and attribution in `private-reference-archive`.

These six are the only repositories in the reviewed set that I currently recommend deleting without a strong reason to retain the standalone repository.

## OPTIONAL DELETE AFTER PERSONAL PREFERENCE CHECK

- `project-collection-tiai-v0`
- `project-collection-tiai-website-v1`

Both are preserved and superseded by `TIAI_website`, but old website versions can still be useful design/provenance references. Archive is a reasonable final state.

## CONSOLIDATE NEXT — not deletion-ready

- `ai-scientist` → `scientific-agent` as one Scientific Agent project.
- `agentic-delivery-os` + selected `design-os` capabilities → `ai-engineering-project-os`.
- `shopkeeper_brain` → evaluate against FinEvidence before any merge.
- `financial-reward-agentic-rl`, `text2sql-agentic-rl`, and `multimodal-chart-gspo` → decide whether they form one post-training experiments repository or remain separate research protocols.

## Principle

Use four states, not two:

```text
KEEP ACTIVE
KEEP ARCHIVED
MERGE THEN ARCHIVE
DELETE ONLY WHEN TRULY REDUNDANT
```

The objective is a legible GitHub portfolio without destroying useful technical history.
