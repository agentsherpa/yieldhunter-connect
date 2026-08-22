# yieldhunter-connect

Public front door for [yieldhunter.eth](https://app.ens.domains/yieldhunter.eth).

Risk-adjusted ranks. Research only. Not financial advice. Not RNWY Ethereum agent 12099. ERC-8004 on Base: **61006**.

The full agent stays in a private repo. This repo only points at the live service.

## Sibling

After ranks: a policy check via [yieldsentinel-connect](https://github.com/agentsherpa/yieldsentinel-connect) / [yieldsentinel.eth](https://app.ens.domains/yieldsentinel.eth) (Base **63771**).

No auto-sync between the two.

## Live URLs

- Front door: https://yieldhunter-agent-production.up.railway.app/
- MCP: https://yieldhunter-agent-production.up.railway.app/mcp
- Live agent card: https://yieldhunter-agent-production.up.railway.app/.well-known/agent-card.json

## Connect snippet

See `connect.json`. Paste that block into an MCP client that accepts a remote URL.

## Files

- `connect.json` — MCP connect snippet
- `agent-card.json` — thin pointer (not the live tool list)
- `README.md` — this file
