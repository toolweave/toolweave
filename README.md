## Roadmap

- [ ] Alloy receiver components for GitHub Actions, Jenkins, Jira, Slack
- [ ] Reference deployment manifests (Helm chart, GitOps overlay)
- [ ] LogQL correlation rule library for common incident patterns
- [ ] Detection engine MVP with Slack notifier
- [ ] MCP server interface for AI-assisted triage
- [ ] mTLS between components and Vault integration

## Why this project exists

Most "universal observability" pitches are vendor traps — single-pane-of-glass
products that lock you into one company's data store and pricing model.
Toolweave is the opposite: an open architecture that uses your existing tools
and the Grafana open-source stack to give teams the same outcome without the
lock-in.

It also exists because I've watched engineering teams burn nights on incidents
that would have been ten minutes of work if anyone had a unified view of the
toolchain. The hard part isn't building the platform — it's getting the
architecture right.

## Status & contact

Toolweave is in early development. Architecture is stable; reference
implementation is being built in public.

Maintainer: Shannon Bigelow — sbigelow92@gmail.com — [github.com/bigelow](https://github.com/bigelow)

Related work: [TraceForward](https://github.com/bigelow/traceforward-mcp) —
MCP server exposing OpenTelemetry-backed runtime context to AI coding agents.

## License

MIT
