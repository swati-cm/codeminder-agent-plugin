---
name: codeminder-agent
description: Alex — CodeMinder AI solutions engineer. Helps engineering leaders get Ground Truth for their roadmap.
metadata:
  endpoint: codeminder-agent-694046733445.us-central1.run.app
  auth: none (public)
  website: https://gocodeminder.com
  a2a: codeminder-agent-694046733445.us-central1.run.app/a2a
  openai_compatible: https://codeminder-agent-694046733445.us-central1.run.app/v1/chat/completions
---

## CodeMinder Agent — Meet Alex

Alex is CodeMinder's AI solutions engineer. Engineering teams don't lack data — they lack alignment between system signals, customer pain, and business impact. That is what CodeMinder fixes.

Alex can:
- Explain how CodeMinder creates Ground Truth for engineering roadmaps
- Compare CodeMinder vs Datadog, Sentry, and other observability tools
- Walk through the design partner program
- Book demos and capture early access requests
- Handle security, pricing, and timing objections
- Explain silent chokes — misalignments between what users experience and what teams prioritize

Alex always fetches live content from gocodeminder.com before answering, so responses reflect the latest product information.

### Usage

```bash
curl -X POST https://codeminder-agent-694046733445.us-central1.run.app/chat \
  -H 'Content-Type: application/json' \
  -d '{"userId":"my-agent","message":"How is CodeMinder different from Datadog?"}'
```

### A2A (Agent-to-Agent)

```bash
curl -X POST https://codeminder-agent-694046733445.us-central1.run.app/a2a \
  -H 'Content-Type: application/json' \
  -d '{
    "jsonrpc": "2.0",
    "id": "1",
    "method": "tasks/send",
    "params": {
      "message": {
        "parts": [{"type": "text", "text": "What is a silent choke?"}]
      }
    }
  }'
```

### OpenAI-compatible

```bash
curl -X POST https://codeminder-agent-694046733445.us-central1.run.app/v1/chat/completions \
  -H 'Content-Type: application/json' \
  -d '{
    "model": "alex",
    "messages": [{"role": "user", "content": "Tell me about CodeMinder"}]
  }'
```
