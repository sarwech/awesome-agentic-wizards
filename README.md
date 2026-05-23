# awesome-agentic-wizards

> A curated list of agentic CLI wizards that install themselves into your existing codebase. No docs required.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

---

## What's a setup wizard?

A setup wizard is a CLI that reads your existing project, understands your stack, and wires up a service automatically. You point it at your codebase and it handles the rest — SDK install, config files, routes, even UI. This is different from scaffolders like `create-react-app`, which build from scratch. You just run one command against code that already exists.

## Why this list?

I ran `npx @posthog/wizard` not really expecting anything other than a standard CLI scaffolder and it just… did it. No docs, no copy-pasting API keys, no guessing which SDK to install. And no debugging why events weren't working. I was blown away and wanted to find more like it. But when I looked and couldn't find a list, I decided to build this. So here it is.

## Legend

- 🤖 AI-powered
- 📹 Demo video available

## The Wizards

| Name | Command | Category | What it does | Links |
|------|---------|----------|--------------|-------|
| PostHog | `npx @posthog/wizard` | Analytics | Scans codebase, installs SDK, creates events and dashboards, optionally adds MCP server | [GitHub](https://github.com/PostHog/wizard) 🤖 📹 |
| Sentry | `npx @sentry/wizard@latest` | Error monitoring | Detects framework, installs SDK, configures source maps and releases | [GitHub](https://github.com/getsentry/sentry-wizard) |
| Amplitude | `npx @amplitude/wizard` | Analytics | Detects stack, proposes custom events, wires up SDK and first dashboard | [Docs](https://amplitude.com/docs/get-started/setup-wizard-cli) 🤖 |
| WorkOS | `npx workos@latest install` | Auth | Reads project, detects framework, writes full auth integration including routes, middleware and UI | [Docs](https://workos.com) 🤖 📹 |
| Grafana GCX | `gcx` | Observability | Gives agents structured access to dashboards, alerts, SLOs, metrics and logs | [GitHub](https://github.com/grafana/gcx) 🤖 📹 |
| Elsikora | `npx @elsikora/setup-wizard` | DX / Tooling | Sets up ESLint, Prettier, Commitlint, Husky, Semantic Release and CI/CD for JS/TS projects | [GitHub](https://github.com/ElsiKora) |

## Contributing

Know a wizard that belongs here? Open a PR. To qualify, it must:

1. Run against an existing codebase, not create from scratch
2. Auto-detect your stack
3. Make actual code changes or config on your behalf

See [CONTRIBUTING.md](CONTRIBUTING.md) for the full guide.

## License

[MIT](LICENSE)
