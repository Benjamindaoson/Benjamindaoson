# Lab Hub Migration Manifest

Migration target: `Benjamindaoson/Benjamindaoson`  
Migration branch: `chore/consolidate-lab-hubs`  
Date: 2026-09-22

The source Hub repositories contained navigation/documentation only. Their
complete top-level content was copied into `labs/` before the source
repositories were marked superseded.

## Agent-Systems-Lab

| Source file | Git blob SHA | Destination |
| --- | --- | --- |
| README.md | 5539bfa100386b6d1a08a7dc9c13f6e5454f69a8 | labs/agent-systems/README.md |
| project-index.md | 1237aaaae58bb1011ca68af7a74639bb33e71cb0 | labs/agent-systems/project-index.md |
| GOVERNANCE.md | 66fc860daee92f351be76f2340cd78f92ec1f151 | labs/agent-systems/GOVERNANCE.md |

## LLM-Systems-Lab

| Source file | Git blob SHA | Destination |
| --- | --- | --- |
| README.md | 06f881b5136e857221d3abe4f1ec8eaef1fdef65 | labs/llm-systems/README.md |
| project-index.md | 585abb4b6aa7ec8eb0b27c5cabc9c2b1619523b5 | labs/llm-systems/project-index.md |
| GOVERNANCE.md | b9e54618c903f665ae9721059b9eaf9b7de35376 | labs/llm-systems/GOVERNANCE.md |

## Embodied-AI-Lab

| Source file | Git blob SHA | Destination |
| --- | --- | --- |
| README.md | 5f743d3108cdea86063d56a1a57e2ba9054241fa | labs/embodied-ai/README.md |
| project-index.md | f5b44e58204afc016581f57e0de43ebf1c6c296c | labs/embodied-ai/project-index.md |
| GOVERNANCE.md | fd66e8a915f5e5807d4980951998476100d815c3 | labs/embodied-ai/GOVERNANCE.md |

## AI-Research-Lab

| Source file | Git blob SHA | Destination |
| --- | --- | --- |
| README.md | f94b0b124b402082e20c095cd029ae02ba5143f3 | labs/ai-research/README.md |
| research-index.md | 9cfdb28dfcfe8ec8c885cd1c63ecd9440bed1fa9 | labs/ai-research/research-index.md |
| GOVERNANCE.md | 5fa46f35426991f7eee57410cc037e20b295f7a0 | labs/ai-research/GOVERNANCE.md |

## Engineering-Tools-Lab

| Source file | Git blob SHA | Destination |
| --- | --- | --- |
| README.md | 046f47be6c6e308baccfef342b56b50e8f4ec31c | labs/engineering-tools/README.md |
| project-index.md | 4d7a36d56ce278f9357eaf71d88d35def9c77ca0 | labs/engineering-tools/project-index.md |
| GOVERNANCE.md | cf270d9e86f131fbee28b8af8e11c3e328e18604 | labs/engineering-tools/GOVERNANCE.md |

## Deletion safety

For these five Hub repositories, all files present at the repository root at
migration time are represented above. They contain navigation/governance
documents rather than independent project source code.

After the Profile PR is merged and the source README redirects are merged, these
five Hub repositories are **DELETE SAFE** from a content-preservation
perspective. Repository deletion remains a user-performed GitHub Settings action.
