# dsh-config

Configuration for [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) (`dsh`).

## Contents

- `profiles/web/` — the `web` profile definition:
  - `package.json` — profile bundles
  - `cordis.patch.yml` — your patch layer (edit this file)
  - `cordis.yml` — generated profile root
  - `pnpm-workspace.yaml` — installer/workspace config
- `settings.yaml` — user settings (default model, onboarding state)
- `.gitignore` — excludes local/runtime state

## Not tracked (ignored)

- `sessions/` — chat transcripts
- `storages/` — runtime cache and session index
- `profiles/node_modules/` — installed dependencies
- `.anonymous-user-id` — per-install telemetry ID
