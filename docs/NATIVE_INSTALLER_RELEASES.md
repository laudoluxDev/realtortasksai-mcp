# Native Installer Releases

Do not add native installer fallback URLs to `agent-install.json` until
RealtorTasksAI has trusted, production-signed release assets.

The current customer setup path is the GitHub manifest plus the shared npm
installer:

```bash
npm exec --package=@tasksai/install --call 'tasksai-install realtor --source https://github.com/laudoluxDev/realtortasksai-mcp'
```

Before any future native fallback is advertised:

1. Build the native installer from the shared TasksAI installer/runtime release process.
2. Sign and notarize the macOS asset.
3. Sign the Windows asset.
4. Publish the assets from the official `laudoluxDev/realtortasksai-mcp` repo or official RealtorTasksAI domain.
5. Smoke-test each asset on a clean machine.
6. Add only the matching trusted URLs to `agent-install.json`.
