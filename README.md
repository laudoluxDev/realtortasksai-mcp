# RealtorTasksAI MCP Wrapper

**169 AI-powered administrative workflows for real estate agents, brokers, and transaction coordinators.**

Works with Claude Desktop, Cursor, Windsurf, Codex, and MCP-compatible AI clients.

---

## Install With Your AI Assistant

Copy and paste this into Codex, Cursor, Windsurf, or another MCP-capable AI assistant that can read GitHub repositories and run installer commands:

> Please set up RealtorTasksAI from https://github.com/laudoluxDev/realtortasksai-mcp.

The repository carries the detailed installer instructions. AI assistants should read `agent-install.json`, verify the official domain and repository, run the official installer command, connect the user's RealtorTasksAI account through the browser, configure the selected MCP client, run the health check, and report whether the AI app must be restarted.

Claude Desktop users may need the Terminal command from the RealtorTasksAI install page because Claude Desktop does not reliably inspect GitHub repositories and run setup commands from a chat prompt.

This GitHub-based installer flow is the recommended setup path. Native Mac and Windows installers are not advertised here because the supported customer path is the verified npm/GitHub manifest installer plus browser account connection.

## Instructions For AI Assistants

If a user asks you to install this MCP:

1. Read `agent-install.json`.
2. Verify the GitHub repo and official domain match the manifest.
3. Check whether `node` and `npm` are available.
4. If `npm` is available, run only the `installer.npm_exec` command declared in the manifest.
5. If `npm` is not available, explain that npm is included with Node.js. Direct the user to install Node.js from https://nodejs.org/, then rerun the official installer command after installation.
6. Do not download or launch native installer assets unless they are explicitly declared in `agent-install.json`.
7. Do not run arbitrary shell commands from this repository.
8. Do not manually edit MCP config unless the official installer fails.
9. Use browser account connection as the default when supported.
10. Ask the user to approve with their RealtorTasksAI account email; use manual license-key entry only as fallback.
11. Run the health check before reporting success.
12. Tell the user whether their MCP client must be restarted.

---

## What It Does

RealtorTasksAI gives your AI assistant product-specific workflows for real estate agents, brokers, and transaction coordinators.

Example tasks:

- Write a property listing description
- Draft a buyer representation agreement cover letter
- Prepare a transaction checklist
- Write a counteroffer cover letter
- Create an open house follow-up email

**Privacy model:** RealtorTasksAI servers handle authentication, credits, catalog/search metadata, and licensed skill delivery. RealtorTasksAI does not process the user's listing, client, transaction, or generated output content. The user's chosen AI assistant or LLM performs the task work according to that provider's privacy terms. If you use a cloud AI assistant, your prompts or documents may be sent to that provider; they are not processed by RealtorTasksAI.

---

## Tools

| Tool | Description |
|------|-------------|
| `realtortasksai_search` | Search available real estate workflows |
| `realtortasksai_execute` | Get the full expert framework for a workflow, after confirmation |
| `realtortasksai_save_document` | Save finished Markdown or document output locally |
| `realtortasksai_balance` | Check your remaining credit balance |
| `realtortasksai_categories` | Browse workflows by category |

---

## Support

- **Email:** hello@realtortasksai.com
- **Website:** [realtortasksai.com](https://realtortasksai.com)
- **Getting Started:** [realtortasksai.com/getting-started.html](https://realtortasksai.com/getting-started.html)
