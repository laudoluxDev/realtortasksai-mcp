# AGENTS.md

This repo lives under the canonical TasksAI repo folder:

`/Users/clio/clio_obsidian_vault/tasksai-repos`

Do not use `/Users/clio/dev-do not use-delete` or the old Google Drive `clio-workspace` as source of truth.

## Role

RealtorTasksAI public MCP wrapper repo and install doorway.

## Working Rules

- Keep implementation docs in this repo's `README.md` or `docs/` folder.
- Put cross-project architecture, operating rules, and durable decisions in `/Users/clio/clio_obsidian_vault/Reference`.
- Put project planning and marketing notes in `/Users/clio/clio_obsidian_vault/Projects`.
- Never commit live keys, tokens, credentials, `.env` contents, recovery codes, or license keys.
- Store secrets in `/Users/clio/secrets/tasksai`; only non-secret pointers belong in Obsidian.
- For vertical wrapper repos, keep public metadata safe and inspectable: product name, domain, repo URL, tool prefix, install flow, support path, examples, security notes, and troubleshooting.
- Proprietary prompts, private skill content, billing enforcement, and account secrets belong in the API/private infrastructure, not public wrapper repos.

## Useful Canonical References

- `/Users/clio/clio_obsidian_vault/Reference/Source of Truth Map.md`
- `/Users/clio/clio_obsidian_vault/Reference/TasksAI Operating Guidelines.md`
- `/Users/clio/clio_obsidian_vault/Projects/Feature Development/mcp_installation_source_of_truth.md`
- `/Users/clio/clio_obsidian_vault/Projects/TasksAI-Verticals/verticals_source_of_truth.md`
- `/Users/clio/clio_obsidian_vault/tasksai-repos/tasksai-mcp/docs/manifest-schema.md`
