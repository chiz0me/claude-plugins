# chiz0me/claude-plugins

A Claude Code plugin marketplace.

## Available plugins

- **[actions-warden](https://github.com/chiz0me/actions-warden)** — audit, pin,
  and upgrade GitHub Actions workflows. Safe-by-default CLI with LLM-friendly
  TOON output. Catches unpinned actions, broad `permissions`, secrets exposed
  via env, script injection in `run:`, and the `pull_request_target` pwn-request
  pattern.
- **[express-recon](https://github.com/chiz0me/express-recon)** — inventory and
  audit Express 4/5 route surfaces. Statically enumerates routes and middleware
  chains, flags unauthenticated endpoints and per-verb auth gaps, no app boot
  required.

## Install

```text
/plugin marketplace add chiz0me/claude-plugins
/plugin install actions-warden@chiz0me
/plugin install express-recon@chiz0me
```

After installation, prompts like *"audit my workflows"*, *"pin my actions to
SHAs"*, or *"upgrade my actions"* will route through the plugin automatically.
