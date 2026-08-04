# Test Skill — EDS Project Context

## Project Overview
- **Authoring mode:** Universal Editor (UE)
- **AEM / Content URL:** TODO_REPLACE
- **Repo:** https://github.com/ssjdeep/test-skill
- **Preview:** https://main--test-skill--ssjdeep.aem.page
- **Live:** https://main--test-skill--ssjdeep.aem.live

## Architecture Decisions
- Authoring: UE — AEM Sites console, Universal Editor
- Boilerplate: adobe-rnd/aem-boilerplate-xwalk
- Block library approach: Block Collection first, custom only if not found

## Block Inventory
| Block | Status | Notes |
|---|---|---|

## Governance Rules
- Never hardcode API URLs — always use fetchConfigs()
- Always run npm run lint before committing
- Every PR requires AI code-review pass before human review
- Hallucinations logged in /spec/hallucination-log.md

## Active Decisions Log
<!-- Record key decisions and rejections here so next session starts ahead -->
