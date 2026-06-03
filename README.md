# nomos-receipts

Replayable evidence receipts for AI agent actions and decisions.

## Overview

NOMOS Receipts produces cryptographically verifiable records for:
- Cross-border preflight decisions
- Agent action authorizations
- x402 payment quotes
- Compliance evidence bundles

## Receipt Format

```json
{
  "operation": "crossborder_preflight",
  "verdict": "ALLOW",
  "evidence_hash": "sha256:...",
  "timestamp": "2026-06-03T...",
  "policy": {"autonomous_outreach": false, "settlement": false}
}
```

