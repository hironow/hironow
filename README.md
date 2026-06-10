## If luck lets us cross paths, how lovely

I run a solo-operated, human-on-the-loop agentic engineering ecosystem:
agents build, gates verify, a human approves. Most of what follows is
its public surface. Everything else on this account is forks kept for
study and contribution.

### The workshop

- [dotfiles](https://github.com/hironow/dotfiles) — the home base: distributes agent instructions hub-and-spoke across coding agents, ships vendored local emulator and telemetry stacks, and tests itself in a throwaway devcontainer sandbox ([site](https://hironow.github.io/dotfiles/))
- [homebrew-tap](https://github.com/hironow/homebrew-tap) — `brew tap hironow/tap`
- [env-template](https://github.com/hironow/env-template) — start a project from a `.env` file

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

---

## 日本語版

ソロ運用・human-on-the-loop の agentic engineering エコシステムを回しています。
エージェントが作り、ゲートが検証し、人間が承認する。以下はその公開部分です。
このアカウントの他のリポジトリは、学習と contribution のための fork です。

### 工房

- [dotfiles](https://github.com/hironow/dotfiles) — 本拠地。agent 指示を hub-and-spoke で各コーディングエージェントへ配布し、vendored なローカル emulator / telemetry スタックを備え、使い捨て devcontainer sandbox で自己テストする ([site](https://hironow.github.io/dotfiles/))
- [homebrew-tap](https://github.com/hironow/homebrew-tap) — `brew tap hironow/tap`
- [env-template](https://github.com/hironow/env-template) — `.env` ファイルから始めるプロジェクトテンプレート

### 関所

- [runops-gateway](https://github.com/hironow/runops-gateway) — Cloud Run のカナリアロールアウトと Cloud SQL マイグレーションを Slack ボタンで承認する、Go + OpenTofu 製 human-in-the-loop ChatOps ゲートウェイ
- [semgrep-guardrails](https://github.com/hironow/semgrep-guardrails) — ガードレールルールのための semantic grep ハーネス

### 艦隊

実験段階の Go 自動化エージェント群:
[sightjack](https://github.com/hironow/sightjack),
[paintress](https://github.com/hironow/paintress),
[amadeus](https://github.com/hironow/amadeus),
[phonewave](https://github.com/hironow/phonewave),
[dominator](https://github.com/hironow/dominator)。
まだ荒削りですが、すでにソフトウェアをエンドツーエンドで建造しています:
[weaveback](https://github.com/hironow/weaveback) (Weave Feedback API の Go クライアント + CLI) は彼らの作品であって、私の手によるものではありません。

### 型契約・データ・リサーチツール

- [firepact](https://github.com/hironow/firepact) — Pydantic バックエンドと TypeScript フロントエンドの間の realtime Firestore 型契約。wire 型を生成し、前方/後方互換性を CI でゲートする (Rust 製)
- [tablecodec](https://github.com/hironow/tablecodec) — 表認識データセットフォーマット (PubTabNet, OTSL, PubTables-1M) を中立 IR 経由で変換・検証・損失分析
- [adk-stream-protocol](https://github.com/hironow/adk-stream-protocol) — Google ADK を Vercel AI SDK UI の data stream protocol (SSE) に接続
- [search-ja-persona](https://github.com/hironow/search-ja-persona) — Nemotron Personas Japan データセットをローカル Qdrant / Elasticsearch / Neo4j 上でベクトル・キーワード・グラフ検索

### ハッカソン作品

- [advena](https://github.com/hironow/advena) — ミ=ホ Mi-Ho。AI Agent Hackathon にて開発 (開発中)
- [crediflow](https://github.com/hironow/crediflow) — クリエイターとファンが互いに評価し報酬を贈るプロトコル。Flow (Cadence) 製

### 小さな道具

- [notifoo](https://github.com/hironow/notifoo) — 起こしてくれる通知 PWA
- [jsonrpc-custom-client](https://github.com/hironow/jsonrpc-custom-client) — JSON-RPC over WebSocket を探索する Next.js UI
- [Coders](https://github.com/hironow/Coders) — 限定タスク用エージェントサンドボックス。人間の指示とレビューのみ
