# AGENTS.md — docker-cronicle

AI-agent context for the `docker-cronicle` repository (InteriorTrends). This file is a stub —
extend it with build/run/architecture notes as the repo grows.

## Review routing — rohan694 (operator directive 2026-06-12)

Every pull request in this repo auto-requests **@rohan694** (CTO) as reviewer via
`.github/CODEOWNERS` (`* @rohan694`). This is **notification only** — there is no
code-owner branch-protection gate, so contributors and AI agents stay free to
proceed and merge autonomously; rohan is simply always informed about anything
that goes out.

When opening a PR from the CLI or an AI agent, also pass `--reviewer rohan694` so
he is notified even before CODEOWNERS resolves. Applies to humans and AI agents
alike — work autonomously when needed, but rohan must always be on the PR.
