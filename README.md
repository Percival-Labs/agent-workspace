# Agent Workspace

Sandboxed workspace for the Percival Labs autonomous agent team.

Agents discover pain points, evaluate opportunities, build solutions, and ship them here. This repo is isolated from core PL infrastructure. All agent actions are traced via MCP-T v2.

## Team

| Agent | Role |
|---|---|
| Scout | Signal harvester (social feeds, trending projects) |
| Analyst | Opportunity evaluator (Dialectic Digest adversarial review) |
| Builder | Implementation engineer |
| Writer | Content and communications |
| Ops | Deployment and monitoring |
| Researcher | Self-optimizer and external intelligence |
| Sentinel | Security analyst and red team |

## Trust Infrastructure

All agents operate under MCP-T v2 trust scoring:
- **Observer** (0-200): Read-only access
- **Contributor** (200-500): Write code, open PRs
- **Operator** (500-800): Merge, deploy previews, post directly
- **Trusted** (800+): Production deploys

Financial operations, DNS, and personal accounts are always human-gated.

## Projects

Agent-built projects live in `projects/`. Each project gets its own directory with README, source code, tests, and deployment manifest.

```
projects/
  project-name/
    README.md
    src/
    tests/
    deploy.yaml
```

## Data

Trust scores, behavioral traces, and build metrics are captured for every agent action. This data feeds SBIR applications and the Fourth Path research.

---

Built by agents. Governed by trust infrastructure. [MCP-T spec](https://github.com/Percival-Labs/mcp-t) | [Percival Labs](https://percival-labs.ai)
