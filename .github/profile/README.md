# Kodetis

Open-source AI security tooling. Detect, control, and audit AI interactions at scale.

## Ecosystem

```text
┌───────────────────────────────────────────┐
│          nova-framework (OSS)             │
│    .nov rule format + parser + SDK        │
│    Based on Nova by @fr0gger             │
└─────┬──────────┬──────────────┬───────────┘
      │          │              │
      ▼          ▼              ▼
┌──────────┐ ┌────────────┐ ┌──────────────────┐
│nova-rules│ │nova-       │ │atlas-litellm-    │
│  (OSS)   │ │proximity   │ │guardrail (OSS)   │
│Detection │ │(OSS)       │ │LiteLLM plugin    │
│rule packs│ │MCP scanner │ │                  │
└──────────┘ └────────────┘ └──────────────────┘
                    │                │
                    ▼                ▼
            ┌──────────────────────────────┐
            │      ATLAS-AI (Pro)          │
            │  AI security platform        │
            │  kodetis.com                 │
            └──────────────────────────────┘
```

> nova-framework and nova-rules are forks of the [Nova](https://github.com/Nova-Hunting) project by [@fr0gger](https://github.com/fr0gger).

## Repositories

| Repository | Description | License |
|------------|-------------|---------|
| nova-framework | .nov rule format, parser, scan engine, Python SDK | MIT |
| nova-rules | Community-maintained detection rule packs | MIT |
| nova-proximity | MCP server & AI agent posture scanner | MIT |
| atlas-litellm-guardrail | Real-time AI guardrail plugin for LiteLLM Proxy | MIT |

## Get started

- Documentation: [kodetis.com](https://kodetis.com)
- Issues & discussions: on each repository

## Contributing

Contributions welcome. Open an issue first for anything non-trivial. See each repo's CONTRIBUTING.md for details.

## About Kodetis

Kodetis is a cybersecurity company based in La Reunion, France. We build sovereign AI security tooling for organizations that need to detect, control, and audit AI interactions — on-premise, no external calls.

[kodetis.com](https://kodetis.com) | [LinkedIn](https://www.linkedin.com/company/kodetis)

---

*Francophone ? Bienvenue. Les issues et discussions en francais sont les bienvenues sur tous nos repos.*
