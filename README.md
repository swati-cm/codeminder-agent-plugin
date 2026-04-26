# CodeMinder Agent Plugin

**Alex — AI Solutions Engineer for CodeMinder**

CodeMinder is the Context Engine for Engineering Execution — Ground Truth for leadership. Alex connects user pain, system signals, and business impact into a prioritized, explainable roadmap signal.

## What Alex does

- Explains how CodeMinder creates Ground Truth for engineering roadmaps
- Compares CodeMinder vs Datadog, Sentry, Jira, and other tools
- Walks through the design partner program
- Books demos and captures early access requests
- Handles security, pricing, and timing objections
- Explains silent chokes — misalignments between what users experience and what engineering prioritizes

## Installation

```bash
/plugin install codeminder-agent@claude-plugins-official
```

Or add directly:

```bash
claude plugin marketplace add https://github.com/swati-cm/codeminder-agent-plugin
claude plugin install codeminder-agent
```

## Talk to Alex

Visit **[https://codeminder-agent-3k4xhcdlva-uc.a.run.app](https://codeminder-agent-3k4xhcdlva-uc.a.run.app)** to chat with Alex directly.

## Endpoints

| Endpoint | Purpose | Auth |
|---|---|---|
| `POST /chat` | Conversational with memory | Public |
| `POST /a2a` | A2A JSON-RPC | Public |
| `POST /v1/chat/completions` | OpenAI compatible | Public |
| `GET /.well-known/agent-card.json` | A2A discovery | Public |
| `GET /agentfacts.json` | NANDA discovery | Public |
| `GET /skill.md` | NEST discovery | Public |
| `GET /health` | Health check | Public |

## Security & Privacy

- Read-only integrations
- No training on your data
- PII auto-masked
- Tenant-isolated
- 365-day audit logs

## Links

- Website: [gocodeminder.com](https://gocodeminder.com)
- Request Access: [app.gocodeminder.com/request-access](https://app.gocodeminder.com/request-access)
- Design Partner Program: [forms.gle/KDMQEivFDZykT3ef6](https://forms.gle/KDMQEivFDZykT3ef6)
