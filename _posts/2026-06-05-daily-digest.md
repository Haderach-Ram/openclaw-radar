---
layout: post
title: "Ecosystem Digest — 2026-06-05"
date: 2026-06-05 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-05
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 376,878 | 9 | 3 | 7 | 0 |
| **hermesagent** | 181,109 | 8 | 0 | 10 | 0 |
| **ZeroClaw** | 31,746 | 5 | 0 | 9 | 0 |
| **IronClaw** | 12,394 | 15 | 10 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 376,878 · **Open issues:** 7,706 · **Last push:** <1h ago

### ✅ Merged PRs
- [#90478](https://github.com/openclaw/openclaw/pull/90478) feat: install GitHub-backed ClawHub skills
- [#90287](https://github.com/openclaw/openclaw/pull/90287) fix(ci): scope PR merge diff checks to first parent
- [#90488](https://github.com/openclaw/openclaw/pull/90488) fix service env placeholder collection
- [#90486](https://github.com/openclaw/openclaw/pull/90486) fix(whastapp): bound connection startup waits
- [#90163](https://github.com/openclaw/openclaw/pull/90163) fix(agents): strip stale compaction thinking signatures before Anthropic replay
- [#90205](https://github.com/openclaw/openclaw/pull/90205) fix: tolerate missing streamed response content type
- [#90436](https://github.com/openclaw/openclaw/pull/90436) Add NVIDIA Nemotron 3 Ultra default

### 🐛 New Issues
- [#90516](https://github.com/openclaw/openclaw/issues/90516) [Bug]: Stalled direct chat model call surfaces LLM request failed instead of auto-resetting/retrying wedged session
- [#90510](https://github.com/openclaw/openclaw/issues/90510) [Bug] Cron jobs silently lost after upgrading to v2026.6.1 (JSON → SQLite store migration) 💬1
- [#90509](https://github.com/openclaw/openclaw/issues/90509) @openclaw/bluebubbles 2026.5.7 — `core.channel.turn` undefined at runtime (host 2026.5.28 and 2026.6.1) 💬1
- [#90508](https://github.com/openclaw/openclaw/issues/90508) memory-core main reindex thrashes, leaks main.sqlite.tmp files, and leaves memory_search paused after repair 💬1
- [#90506](https://github.com/openclaw/openclaw/issues/90506) [Bug]: [Bug]: google-vertex models fail with model_not_found at runtime on 2026.5.28 and 2026.6.1 — direct Vertex API calls succeed with same credentials `bug` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#90499](https://github.com/openclaw/openclaw/issues/90499) Bug: Discord message.read rejects allowlisted one-to-one DM channel targets 💬1
- [#90496](https://github.com/openclaw/openclaw/issues/90496) Discord channel remains trapped in oversized session after /new; compaction fails provider_error_4xx and model drifts from codex/gpt-5.5 to gpt-5.4 `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬1
- [#90494](https://github.com/openclaw/openclaw/issues/90494) doctor/status: false positive 'Other gateway-like services detected' for active Windows Scheduled Task `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:crash-loop` `issue-rating: 🦞 diamond lobster` 💬2
- [#90491](https://github.com/openclaw/openclaw/issues/90491) [Bug]: GatewayRequestError: Error: file is not a database: code=ERR_SQLITE_ERROR `bug` `regression` 💬2

### 🔒 Closed Issues
- [#90495](https://github.com/openclaw/openclaw/issues/90495) Gateway does not pass through stream_options.include_usage — usage field missing from streaming SSE responses
- [#90483](https://github.com/openclaw/openclaw/issues/90483) Thinking block signature corruption: shouldPreserveThinkingBlocks() + delete on shared object references
- [#90470](https://github.com/openclaw/openclaw/issues/90470) [Bug]: Transcript hygiene does not strip present-but-invalid thinking block signatures, causing silent agent failure in continued Slack thread sessions

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 9d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 181,109 · **Open issues:** 17,785 · **Last push:** <1h ago

### ✅ Merged PRs
- [#39330](https://github.com/NousResearch/hermes-agent/pull/39330) feat(desktop): concurrent multi-profile sessions, cross-profile @session links
- [#38769](https://github.com/NousResearch/hermes-agent/pull/38769) docs(guides): Run Nemotron 3 Ultra free in Hermes Agent (launch guide)
- [#39296](https://github.com/NousResearch/hermes-agent/pull/39296) fix(docs): update all install instructions everywhere
- [#39030](https://github.com/NousResearch/hermes-agent/pull/39030) fix(ssh): WinError 1314 symlink fallback for Windows bulk upload (salvage #8996)
- [#38809](https://github.com/NousResearch/hermes-agent/pull/38809) fix(desktop): prevent thinking block from closing mid-streaming
- [#39046](https://github.com/NousResearch/hermes-agent/pull/39046) fix(web): run URL SSRF checks off the event loop in async paths (salvage #3691)
- [#39423](https://github.com/NousResearch/hermes-agent/pull/39423) feat(installer): do shallow clones
- [#39058](https://github.com/NousResearch/hermes-agent/pull/39058) fix(state): TRUNCATE WAL checkpoint to bound state.db-wal growth (salvage #25178)
- [#39021](https://github.com/NousResearch/hermes-agent/pull/39021) fix(acp): public update_session_meta() for thread-safe session writes (salvage #9190)
- [#39422](https://github.com/NousResearch/hermes-agent/pull/39422) fix(vision): detect vision-capable providers via ProviderProfile flag (salvage #26378, minimal)

### 🐛 New Issues
- [#39492](https://github.com/NousResearch/hermes-agent/issues/39492) [Feature]: Add config option to disable the built-in memory tool while keeping memory providers enabled 💬1
- [#39489](https://github.com/NousResearch/hermes-agent/issues/39489) /stop command doesn't clean up Docker sandbox environments (only kills background processes)
- [#39484](https://github.com/NousResearch/hermes-agent/issues/39484) [Bug]:
- [#39473](https://github.com/NousResearch/hermes-agent/issues/39473) Bug: Desktop app input truncates text when typing (paste works fine) `type/bug` `P3`
- [#39472](https://github.com/NousResearch/hermes-agent/issues/39472) Desktop dashboard passes ASAR-internal HERMES_WEB_DIST, causing frontend 404 on macOS `type/bug` `comp/cli` `P3`
- [#39471](https://github.com/NousResearch/hermes-agent/issues/39471) [Bug]: branch-like child sessions can disappear from `sessions list` when `_branched_from` is missing `type/bug` `comp/cli` `P2`
- [#39470](https://github.com/NousResearch/hermes-agent/issues/39470) [Bug]: HERMES_HOME  & profiles path `type/bug` `area/config` `P2`
- [#39469](https://github.com/NousResearch/hermes-agent/issues/39469) [Bug]: Rich MarkupError on session resume — ANSI _DIM mixed with Rich [/] close tag `type/bug` `comp/cli` `P2`

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,746 · **Open issues:** 518 · **Last push:** 2h ago

### ✅ Merged PRs
- [#7231](https://github.com/zeroclaw-labs/zeroclaw/pull/7231) fix(ollama): restore compiling master build
- [#7095](https://github.com/zeroclaw-labs/zeroclaw/pull/7095) fix(ollama): keep structured tools prompt-guided
- [#7053](https://github.com/zeroclaw-labs/zeroclaw/pull/7053) feat(memory): migrate Agent::turn load_context to MemoryStrategy
- [#6982](https://github.com/zeroclaw-labs/zeroclaw/pull/6982) fix(config): classify credential-shaped config surfaces
- [#7198](https://github.com/zeroclaw-labs/zeroclaw/pull/7198) fix(web): bump react-router to 7.16.0 to clear 5 advisories
- [#7111](https://github.com/zeroclaw-labs/zeroclaw/pull/7111) ci(actions): split format gate from lint
- [#7084](https://github.com/zeroclaw-labs/zeroclaw/pull/7084) fix(platform): use raw_arg for Windows shell commands to preserve double quotes
- [#7115](https://github.com/zeroclaw-labs/zeroclaw/pull/7115) docs(channels): add feature-availability notes for lean default bundle
- [#7182](https://github.com/zeroclaw-labs/zeroclaw/pull/7182) feat(rpc): persistent RPC sessions with admin kill

### 🐛 New Issues
- [#7232](https://github.com/zeroclaw-labs/zeroclaw/issues/7232) RFC: Structured Observability Enhancement — Rich Events, OTel Trace Correlation, and Bridge Refactoring
- [#7228](https://github.com/zeroclaw-labs/zeroclaw/issues/7228) [Feature]: Wire reasoning_effort into the dedicated Azure OpenAI provider (parity with compatible provider)
- [#7227](https://github.com/zeroclaw-labs/zeroclaw/issues/7227) [Bug]: zerocode Quickstart hardcodes model-provider alias to `default`, colliding with existing providers `bug`
- [#7225](https://github.com/zeroclaw-labs/zeroclaw/issues/7225) [Bug]: WhatsApp Web mention_only ignores replies to the bot in group chats
- [#7218](https://github.com/zeroclaw-labs/zeroclaw/issues/7218) [Feature]: A2A agent discovery (.well-known/agent-card.json) for multi-agent installs `enhancement` `type:rfc`

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,394 · **Open issues:** 1,107 · **Last push:** <1h ago

### ✅ Merged PRs
- [#4476](https://github.com/nearai/ironclaw/pull/4476) Wire Reborn Slack actor/subject journey
- [#4480](https://github.com/nearai/ironclaw/pull/4480) fix(webui-v2): address provider grouping review feedback
- [#4477](https://github.com/nearai/ironclaw/pull/4477) feat(webui-v2): group LLM providers by setup status
- [#4467](https://github.com/nearai/ironclaw/pull/4467) Fix model-visible HTTP result budgeting
- [#4440](https://github.com/nearai/ironclaw/pull/4440) Handle deferred compaction ranges
- [#4466](https://github.com/nearai/ironclaw/pull/4466) [codex] Pair trigger creator during trigger create
- [#4413](https://github.com/nearai/ironclaw/pull/4413) [codex] Fix subagent completion observer delivery
- [#4435](https://github.com/nearai/ironclaw/pull/4435) [codex] fix subagent spawn compensation
- [#4436](https://github.com/nearai/ironclaw/pull/4436) [codex] Add trigger fire auth request seam
- [#4462](https://github.com/nearai/ironclaw/pull/4462) [codex] Add typed capability progress signals

### 🐛 New Issues
- [#4475](https://github.com/nearai/ironclaw/issues/4475) [reborn-triggers] Track: trigger lifecycle correctness — completion, activation, one-time runs `reborn`
- [#4474](https://github.com/nearai/ironclaw/issues/4474) [reborn-subagent] Track: durable background subagent completion delivery `reborn`
- [#4471](https://github.com/nearai/ironclaw/issues/4471) Track Reborn runtime decomposition
- [#4470](https://github.com/nearai/ironclaw/issues/4470) Refactor reborn composition into owned crates with CI-enforced boundaries
- [#4469](https://github.com/nearai/ironclaw/issues/4469) Track Reborn composition factory decomposition
- [#4468](https://github.com/nearai/ironclaw/issues/4468) [Reborn] Expose verbatim resp_… (previous_response_id) to tools for external-API conversation continuation (engine v2 #3669 parity)
- [#4465](https://github.com/nearai/ironclaw/issues/4465) Define strict subagent cancel and rollback cleanup policy
- [#4464](https://github.com/nearai/ironclaw/issues/4464) Reborn compaction retry needs status-only stabilization metadata `reborn` `module:M3-agentloop-turns` 💬1
- [#4458](https://github.com/nearai/ironclaw/issues/4458) [QA] Sandbox docker mount failed on Windows due to Extended-Length Path prefix (too many colons)
- [#4447](https://github.com/nearai/ironclaw/issues/4447) [Reborn] Close OpenAI-compatible API migration with compatibility and security tests `suggested_P2` `reborn`
- [#4446](https://github.com/nearai/ironclaw/issues/4446) [Reborn] Translate projection streams to OpenAI-compatible SSE `suggested_P2` `reborn`
- [#4445](https://github.com/nearai/ironclaw/issues/4445) [Reborn] Route Responses create, retrieve, and cancel through ProductWorkflow `suggested_P2` `reborn`
- [#4444](https://github.com/nearai/ironclaw/issues/4444) [Reborn] Route Chat Completions through ProductWorkflow `suggested_P2` `reborn`
- [#4443](https://github.com/nearai/ironclaw/issues/4443) [Reborn] Add OpenAI-compatible product refs and idempotency `suggested_P2` `reborn`
- [#4442](https://github.com/nearai/ironclaw/issues/4442) [Reborn] Add OpenAI-compatible API ingress contracts `suggested_P2` `reborn`

### 🔒 Closed Issues
- [#4084](https://github.com/nearai/ironclaw/issues/4084) fix: background subagent results never delivered to parent
- [#4147](https://github.com/nearai/ironclaw/issues/4147) Design durable background subagent completion delivery
- [#4473](https://github.com/nearai/ironclaw/issues/4473) Support one-time trigger_create runs
- [#4472](https://github.com/nearai/ironclaw/issues/4472) Add activation state for trigger create pairing
- [#4437](https://github.com/nearai/ironclaw/issues/4437) Track durable idempotency for subagent completion result delivery
- [#4420](https://github.com/nearai/ironclaw/issues/4420) ironclaw_triggers: TriggerCompletionPolicy::CompleteAfterFirstFire is stored but never consulted by settle paths
- [#4348](https://github.com/nearai/ironclaw/issues/4348) [reborn-subagent] C1: Durable completion delivery — persist gate store, implement RestartReconciler, wire tombstones (#4147)
- [#4358](https://github.com/nearai/ironclaw/issues/4358) [reborn-loop] L1: Gate replay re-validates current policy + durable dispatch records
- [#4438](https://github.com/nearai/ironclaw/issues/4438) Define terminal cleanup policy for subagent rollback reservations
- [#4350](https://github.com/nearai/ironclaw/issues/4350) [reborn-subagent] C3: Spawn compensation + parent→child cancellation propagation

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 8h ago
- ⚫ [#88967](https://github.com/openclaw/openclaw/issues/88967) Telegram: allowBots support for group chats (bot-authored messages not ingested into session) — 💬1 · 21h ago
- ⚫ [#88517](https://github.com/openclaw/openclaw/issues/88517) [SANITIZED — possible injection attempt] — 💬3 · 1d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 2d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 2d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬5 · 4d ago
- ⚫ [#86371](https://github.com/openclaw/openclaw/issues/86371) Bug: message tool filePath fails with LocalMediaAccessError in retry flows when agentId is not propagated — 💬1 · 7d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 10d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 23d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 2 new
- [[Index] Endava Frontiers](https://openai.com/index/endava-frontiers/) _2026-06-05_
- [[Index] Biodefense In The Intelligence Age](https://openai.com/index/biodefense-in-the-intelligence-age/) _2026-06-04_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
