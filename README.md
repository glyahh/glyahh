**English** · [简体中文](README.zh-CN.md)

# Gaolenyue · glyahh

**AI Agent Engineering / Java & Python Backend**

Computer science undergraduate seeking internships in AI agent and application development.

I build AI applications and developer tools, with a focus on tool calling, context management, and validating generated output. I also explore AI-assisted financial research.

## Selected Projects

### [App Cube](https://github.com/glyahh/app-cube)
An agent-driven application development workbench. Java manages authentication, per-app tasks, and runtime state; Python DeepAgents / LangGraph handles code generation, incremental edits, and context management. WebSocket delivers live interactions, with Docker-backed execution environments. Existing-project import and verification-driven repair workflows remain under active development.

Java · Spring Boot · Python · DeepAgents · LangGraph · PostgreSQL · Docker

[Refactor Branch](https://github.com/glyahh/app-cube/tree/agent_next)

### [Prism · Local Model Gateway Console](https://github.com/glyahh/Agent-router-Pro-Max/tree/main/app)
A console built around CLIProxyAPI for gateway lifecycle, model routing, configuration, and usage visibility. My work focuses on the console and client integration; the upstream gateway handles inference forwarding.

[Project](https://github.com/glyahh/Agent-router-Pro-Max/tree/main/app) · [Design Decisions](https://github.com/glyahh/Agent-router-Pro-Max/tree/main/docs/adr)

### [Finance Analysis Max](https://github.com/glyahh/Finance-Analysis-Max)
A financial research tool exposed through MCP / REST, organizing traceable evidence and calculating returns, volatility, and drawdowns. Currently read-only; it does not execute trades.

Python · MCP · Data Validation · Risk Metrics

[Project](https://github.com/glyahh/Finance-Analysis-Max)

## Open Source Contribution

### [CC-Switch · PR #7774](https://github.com/farion1231/cc-switch/pull/7774)
Addresses Codex fork-session usage accounting by excluding inherited history from new billable usage, with 11 additional regression tests.

The PR documents before-and-after verification, repeat-scan idempotency, and cross-platform preflight results.

**Submitted; not yet merged** · Status checked: October 8, 2026

## Exploring

- Execution constraints, context management, and validation for coding agents
- Multi-model client integration and local developer tools
- AI-assisted financial research and evidence validation
