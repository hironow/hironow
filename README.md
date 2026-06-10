## If luck lets us cross paths, how lovely

I run a solo-operated, human-on-the-loop agentic engineering ecosystem:
agents build, gates verify, a human approves. Most of what follows is
its public surface. Everything else on this account is forks kept for
study and contribution.

### The workshop

- [dotfiles](https://github.com/hironow/dotfiles) — the home base: distributes agent instructions hub-and-spoke across coding agents, ships vendored local emulator and telemetry stacks, and tests itself in a throwaway devcontainer sandbox ([site](https://hironow.github.io/dotfiles/))
- [homebrew-tap](https://github.com/hironow/homebrew-tap) — `brew tap hironow/tap`

### The gates

- [runops-gateway](https://github.com/hironow/runops-gateway) — approve Cloud Run canary rollouts and Cloud SQL migrations from Slack buttons; a human-in-the-loop ChatOps gateway in Go + OpenTofu on Cloud Run
- [semgrep-guardrails](https://github.com/hironow/semgrep-guardrails) — semantic grep harness for guardrail rules

### The fleet

A family of experimental Go automation agents:
[sightjack](https://github.com/hironow/sightjack),
[paintress](https://github.com/hironow/paintress),
[amadeus](https://github.com/hironow/amadeus),
[phonewave](https://github.com/hironow/phonewave),
[dominator](https://github.com/hironow/dominator).
Still rough, but they already build software end-to-end:
[weaveback](https://github.com/hironow/weaveback), a Go client and CLI for the
Weave Feedback API, is their work, not mine.

### Contracts, data, and research tooling

- [firepact](https://github.com/hironow/firepact) — a type contract between a Pydantic backend and a TypeScript frontend for realtime Firestore documents; generates the wire types and gates backward/forward compatibility in CI (Rust)
- [tablecodec](https://github.com/hironow/tablecodec) — convert, validate, and measure loss between table-recognition dataset formats (PubTabNet, OTSL, PubTables-1M) via a neutral IR
- [adk-stream-protocol](https://github.com/hironow/adk-stream-protocol) — Google ADK bridged to the Vercel AI SDK UI data stream protocol over SSE
- [search-ja-persona](https://github.com/hironow/search-ja-persona) — vector, keyword, and graph search over the Nemotron Personas Japan dataset, on local Qdrant, Elasticsearch, and Neo4j

### Hackathon builds

- [advena](https://github.com/hironow/advena) — Mi-Ho, built at an AI Agent Hackathon (in development)
- [crediflow](https://github.com/hironow/crediflow) — a protocol for creators and admirers to share and reward each other, on Flow (Cadence)

### Small tools

- [notifoo](https://github.com/hironow/notifoo) — a PWA that notifies you awake
- [jsonrpc-custom-client](https://github.com/hironow/jsonrpc-custom-client) — Next.js UI to explore JSON-RPC over WebSocket
- [Coders](https://github.com/hironow/Coders) — tightly-scoped agent task sandbox; human instruction and review only

