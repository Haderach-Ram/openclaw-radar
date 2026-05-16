---
layout: post
title: "OpenClaw Radar — 2026-05-15"
date: 2026-05-15 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-15
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 371,912 | 15 | 10 | 10 | 4 |
| **hermesagent** | 150,479 | 9 | 2 | 4 | 0 |
| **ZeroClaw** | 31,340 | 15 | 2 | 7 | 0 |
| **IronClaw** | 12,250 | 1 | 1 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 371,912 · **Open issues:** 7,132 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.14-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.5.14-beta.1) — openclaw 2026.5.14-beta.1
- [v2026.5.12](https://github.com/openclaw/openclaw/releases/tag/v2026.5.12) — openclaw 2026.5.12
- [v2026.5.12-beta.8](https://github.com/openclaw/openclaw/releases/tag/v2026.5.12-beta.8) — openclaw 2026.5.12-beta.8
- [v2026.5.12-beta.7](https://github.com/openclaw/openclaw/releases/tag/v2026.5.12-beta.7) — openclaw 2026.5.12-beta.7

### ✅ Merged PRs
- [#81950](https://github.com/openclaw/openclaw/pull/81950) fix(ui): remove duplicate Usage heading
- [#50696](https://github.com/openclaw/openclaw/pull/50696) fix(ui/src/ui/views/overview-cards.ts): incorrect data prioritization / misleading display text
- [#81966](https://github.com/openclaw/openclaw/pull/81966) fix(codex): remove spurious migration warnings
- [#81741](https://github.com/openclaw/openclaw/pull/81741) fix(codex): hide empty rate-limit buckets
- [#70900](https://github.com/openclaw/openclaw/pull/70900) fix(runner): gate surface_error throw on failoverFailure
- [#81937](https://github.com/openclaw/openclaw/pull/81937) fix(plugins): expose effective context budget in hooks
- [#79550](https://github.com/openclaw/openclaw/pull/79550) fix(sessions): report ACP-runtime metadata for ACP-keyed sessions
- [#81906](https://github.com/openclaw/openclaw/pull/81906) fix: use Codex context windows for OpenAI runtime
- [#81943](https://github.com/openclaw/openclaw/pull/81943) docs: restore 2026.5.12 changelog section
- [#53916](https://github.com/openclaw/openclaw/pull/53916) fix: make log stream height responsive to viewport

### 🐛 New Issues
- [#81991](https://github.com/openclaw/openclaw/issues/81991) HTTP SSE (/v1/chat/completions) drops leading '<' from streamed content and closes connection before final chunk
- [#81990](https://github.com/openclaw/openclaw/issues/81990) Bug: Xiaomi MiMo reasoning_content stripped from assistant history on replay (blocks all multi-turn tool calls) 💬1
- [#81989](https://github.com/openclaw/openclaw/issues/81989) Windows: In-app update restart button does not respond 💬1
- [#81988](https://github.com/openclaw/openclaw/issues/81988) `opencode-go/kimi-k2.6` (and other openai-completions models): `reasoning` field leaks through passthrough replay policy, rejected as "Extra inputs are not permitted" on multi-turn 💬1
- [#81987](https://github.com/openclaw/openclaw/issues/81987) [Bug](gateway): LLM calls continue after API key is unbound — no user-visible stop signal `bug` `regression` 💬1
- [#81985](https://github.com/openclaw/openclaw/issues/81985) [Bug]: Telegram forum topics serialize one-at-a-time despite agents.defaults.maxConcurrent=4 `bug` 💬1
- [#81984](https://github.com/openclaw/openclaw/issues/81984) /stop followed by /new silently fails to archive transcript content 💬1
- [#81983](https://github.com/openclaw/openclaw/issues/81983) [Bug]: TypeError: LRUCache is not a constructor `bug` `regression` 💬1
- [#81982](https://github.com/openclaw/openclaw/issues/81982) Fallback chain becomes empty during deferred config reload, causing session interruption on 429 💬1
- [#81980](https://github.com/openclaw/openclaw/issues/81980) [Bug]: unknown requestId during device.pair.approve `bug` `regression` 💬1
- [#81978](https://github.com/openclaw/openclaw/issues/81978) Bug: routed non-main Discord session remains processing,q=1 after run:completed, delaying typing 💬2
- [#81976](https://github.com/openclaw/openclaw/issues/81976) Gateway can deadlock on nested openclaw sessions tool call; diagnostics report recovery=none 💬1
- [#81973](https://github.com/openclaw/openclaw/issues/81973) [Bug]: Isolated polling ingress never calls bot.init() — Telegram channel halts with "Bot not initialized" 💬3
- [#81963](https://github.com/openclaw/openclaw/issues/81963) test(plugin-sdk): track origin-trust SSRF edge coverage and docs 💬1
- [#81962](https://github.com/openclaw/openclaw/issues/81962) [Question] Where does documentation feedback go? Testing feedback workflow 💬1

### 🔒 Closed Issues
- [#77009](https://github.com/openclaw/openclaw/issues/77009) feat(bluebubbles): per-DM systemPrompt — follow-up to #60665 (#69198 only addressed groups)
- [#81986](https://github.com/openclaw/openclaw/issues/81986) [Feature Request] Message Interruption & Context Merging
- [#81977](https://github.com/openclaw/openclaw/issues/81977) [Feature]: Gateway should stop eating client tools
- [#81624](https://github.com/openclaw/openclaw/issues/81624) [Bug]: WebSocket multi-account mode — only first account can send group replies (replies=0 for others)
- [#81969](https://github.com/openclaw/openclaw/issues/81969) [Bug]: 5.12 strict tool schema injection breaks Xiaomi MiMo custom provider (400 Param Incorrect)
- [#81698](https://github.com/openclaw/openclaw/issues/81698) channel-health-monitor doesn't detect connected-but-frozen Telegram state (sustained getMe fetch-timeouts)
- [#41330](https://github.com/openclaw/openclaw/issues/41330) iMessage channel duplicate message loop - messages sent by agent are re-ingested as inbound
- [#41195](https://github.com/openclaw/openclaw/issues/41195) Bug: Feishu WebSocket reconnect causes duplicate message processing (dedup cache not restored on restart)
- [#81432](https://github.com/openclaw/openclaw/issues/81432) [Bug]: plugin-skills readlinkSync EINVAL on non-symlink directories
- [#81323](https://github.com/openclaw/openclaw/issues/81323) [Bug]: channels.openclaw-weixin only enabled:true causes invalid channels.start channel error

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 150,479 · **Open issues:** 11,323 · **Last push:** <1h ago

### ✅ Merged PRs
- [#25988](https://github.com/NousResearch/hermes-agent/pull/25988) [SANITIZED — possible injection attempt]
- [#25957](https://github.com/NousResearch/hermes-agent/pull/25957) fix(ci): stabilize shared test state after 21012
- [#25985](https://github.com/NousResearch/hermes-agent/pull/25985) feat: update cron modals
- [#25986](https://github.com/NousResearch/hermes-agent/pull/25986) fix(cli): wire /sessions slash command in the classic CLI

### 🐛 New Issues
- [#26046](https://github.com/NousResearch/hermes-agent/issues/26046) kanban: boards rm --delete ineffective when gateway is running (board auto-resurrects)
- [#26045](https://github.com/NousResearch/hermes-agent/issues/26045) memory(action=replace) silently clobbers external writes to MEMORY.md (data-loss race with patch tool / shell appends / concurrent sessions) 💬1
- [#26044](https://github.com/NousResearch/hermes-agent/issues/26044) [Bug]: Tirith security scanner fails to      install on Windows (MSYS/git-bash) -      "unsupported_platform"
- [#26042](https://github.com/NousResearch/hermes-agent/issues/26042) MCP servers unavailable in cron sessions — ECONNREFUSED when accessing MCP tools from scheduled jobs `type/bug` `comp/cron` `tool/mcp` `P2` 💬1
- [#26041](https://github.com/NousResearch/hermes-agent/issues/26041) QQBot send_message cannot deliver local screenshot media from Windows paths `type/bug` `comp/gateway` `comp/tools` `platform/qqbot` `P3`
- [#26037](https://github.com/NousResearch/hermes-agent/issues/26037) Feishu: reply-to-image messages lose parent context (`_fetch_message_text` returns empty for non-text msgs) `type/bug` `comp/gateway` `platform/feishu` `P2` 💬1
- [#26035](https://github.com/NousResearch/hermes-agent/issues/26035) [SANITIZED — possible injection attempt] `type/bug` `comp/agent` `provider/openai` `P2`
- [#26027](https://github.com/NousResearch/hermes-agent/issues/26027) feat: Model routing — use different models for chat vs. tool-use tasks `type/feature` `comp/agent` `area/config` `P3`
- [#26024](https://github.com/NousResearch/hermes-agent/issues/26024) feat(gateway): make busy acknowledgement messages configurable `type/feature` `comp/gateway` `area/config` `P3`

### 🔒 Closed Issues
- [#22951](https://github.com/NousResearch/hermes-agent/issues/22951) fix(cli): /sessions unknown command in classic REPL mode
- [#21677](https://github.com/NousResearch/hermes-agent/issues/21677) Dashboard/TUI slash path reports Unknown command for /sessions

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,340 · **Open issues:** 459 · **Last push:** <1h ago

### ✅ Merged PRs
- [#6286](https://github.com/zeroclaw-labs/zeroclaw/pull/6286) fix(channels/telegram): apply mention_only gate to photo, document, and voice updates
- [#6635](https://github.com/zeroclaw-labs/zeroclaw/pull/6635) fix(cron,channels): carry thread_id through cron announce delivery
- [#6580](https://github.com/zeroclaw-labs/zeroclaw/pull/6580) fix(provider): honor LM Studio compatible runtime options
- [#6620](https://github.com/zeroclaw-labs/zeroclaw/pull/6620) fix(tool-call-parser): omit assistant history when no parsed tool calls (#6298)
- [#6631](https://github.com/zeroclaw-labs/zeroclaw/pull/6631) fix(provider): restrict compatible reasoning effort models
- [#6629](https://github.com/zeroclaw-labs/zeroclaw/pull/6629) fix(providers): stop replaying stale tool-result images
- [#6598](https://github.com/zeroclaw-labs/zeroclaw/pull/6598) fix(providers): defensively omit Anthropic temperature for Opus 4.7 (#6147)

### 🐛 New Issues
- [#6663](https://github.com/zeroclaw-labs/zeroclaw/issues/6663) feat(telegram): show tool-call progress during partial streaming `enhancement` `risk: medium` `channel` `channel:telegram` `priority:p2` `status:accepted` `status:no-stale`
- [#6661](https://github.com/zeroclaw-labs/zeroclaw/issues/6661) [Feature]: preserve committed streamed output during websocket steering `enhancement` `risk: high` `agent` `gateway` `runtime`
- [#6659](https://github.com/zeroclaw-labs/zeroclaw/issues/6659) No API for pushing notifications into an operator's gateway session (zeroclaw 0.7.4) `bug` `enhancement` `risk: high` `gateway` `tool` `gateway: api` `gateway: ws` `priority:p1` `needs-maintainer-review` 💬3
- [#6658](https://github.com/zeroclaw-labs/zeroclaw/issues/6658) [Feature]: Install script support musl aarch64 linux with --prebuilt `bug` `enhancement` `risk: medium` `scripts` `priority:p2` `status:accepted`
- [#6657](https://github.com/zeroclaw-labs/zeroclaw/issues/6657) ci: Advisory scan failed — 2026-05-14 `bug` `type: dependencies` `risk: high` `dependencies` `security` `priority:p1` `status:in-progress` `status:no-stale` 💬1
- [#6654](https://github.com/zeroclaw-labs/zeroclaw/issues/6654) [Bug]: Cron read-only queries still hit the writable schema-ensure path `bug` `risk: high` `cron` `runtime` `cron:store` `status:in-progress` `status:no-stale` `priority:p3`
- [#6653](https://github.com/zeroclaw-labs/zeroclaw/issues/6653) feat(update): define host-architecture policy for emulated installs `enhancement` `risk: medium` `core` `needs-maintainer-review` `priority:p3`
- [#6651](https://github.com/zeroclaw-labs/zeroclaw/issues/6651) [Bug]: matrix channel leaks ~1 MB Pss per /admin/reload due to upstream Arc cycle in matrix-sdk 0.17 (matrix-rust-sdk#6573) `bug` `risk: medium` `dependencies` `channel` `runtime` `channel:matrix` `priority:p2` `status:blocked` `status:no-stale`
- [#6648](https://github.com/zeroclaw-labs/zeroclaw/issues/6648) [Bug]: cron session_target=main still runs in an isolated cron session `bug` `risk: high` `cron` `runtime` `cron:scheduler` `tool: cron_add` `priority:p2` `status:accepted`
- [#6647](https://github.com/zeroclaw-labs/zeroclaw/issues/6647) [Bug]: Title: Cron job output not routed to configured channels `bug` `risk: high` `channel` `cron` `runtime` `channel:telegram` `tool: cron_add` `priority:p1` `status:accepted` `status:no-stale` 💬4
- [#6646](https://github.com/zeroclaw-labs/zeroclaw/issues/6646) [Bug]: Title: web_search_tool and web_fetch not firing via Telegram channel in v0.7.5 `bug` `risk: high` `channel` `provider` `runtime` `tool` `channel:telegram` `provider:compatible` `tool: web_search_tool` `tool: web_fetch` `priority:p1` `needs-maintainer-review` `status:accepted` 💬1
- [#6645](https://github.com/zeroclaw-labs/zeroclaw/issues/6645) SkillImprover + skill_manage only handle `SKILL.toml`, not `manifest.toml` `bug` `risk: high` `runtime` `skills` `tool` `priority:p2` `status:accepted` 💬1
- [#6644](https://github.com/zeroclaw-labs/zeroclaw/issues/6644) Skill review fork: `💾` summary parser misses tool receipts `bug` `risk: low` `runtime` `skills` `tool` `status:blocked` `status:no-stale` `priority:p3` 💬1
- [#6642](https://github.com/zeroclaw-labs/zeroclaw/issues/6642) [Feature]: Capture full prompt/completion on llm.call spans via gen_ai.input.messages / gen_ai.output.messages `enhancement` `risk: medium` `observability` `runtime` `observability: otel` `observability: runtime_trace` `priority:p2` `status:blocked` `status:no-stale` 💬1
- [#6641](https://github.com/zeroclaw-labs/zeroclaw/issues/6641) [Feature]: Turn-level OTel trace correlation — nest llm.call / tool.call / memory.* spans under a single turn trace `enhancement` `risk: medium` `observability` `runtime` `observability: otel` `observability: runtime_trace` `priority:p2` `status:blocked` `status:no-stale` 💬1

### 🔒 Closed Issues
- [#6229](https://github.com/zeroclaw-labs/zeroclaw/issues/6229) [Bug]: mention_only=true does not suppress responses to photo/media messages in Telegram groups
- [#6634](https://github.com/zeroclaw-labs/zeroclaw/issues/6634) [Bug]: cron-scheduled webhook callbacks drop thread_id

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,250 · **Open issues:** 934 · **Last push:** <1h ago

### ✅ Merged PRs
- [#3556](https://github.com/nearai/ironclaw/pull/3556) arch(ws-5): default strategies - Default* impls for all nine traits
- [#3643](https://github.com/nearai/ironclaw/pull/3643) arch(ws-3.5): add loop family registry
- [#3553](https://github.com/nearai/ironclaw/pull/3553) arch(ws-3): strategy traits gamma - stop, drain, budget
- [#3552](https://github.com/nearai/ironclaw/pull/3552) arch(ws-2): strategy traits beta - batch, gate, recovery
- [#3551](https://github.com/nearai/ironclaw/pull/3551) arch(ws-1): strategy traits alpha - context, capability, model
- [#3550](https://github.com/nearai/ironclaw/pull/3550) arch(ws-0): state, checkpoints, BoundedRing, CapabilityCallSignature, NoProgressDetected
- [#3642](https://github.com/nearai/ironclaw/pull/3642) feat(product-workflow): add WebUI inbound DTO contract
- [#3655](https://github.com/nearai/ironclaw/pull/3655) fix(reborn): redact loop response output
- [#3656](https://github.com/nearai/ironclaw/pull/3656) fix(reborn): flag in-memory durable logs
- [#3657](https://github.com/nearai/ironclaw/pull/3657) chore(crates): enable unreachable_pub on tier-2 crates

### 🐛 New Issues
- [#3673](https://github.com/nearai/ironclaw/issues/3673) [QA] openai_compatible provider drops reasoning_content on outgoing requests, breaks DeepSeek v4-pro multi-turn tool calls

### 🔒 Closed Issues
- [#3624](https://github.com/nearai/ironclaw/issues/3624) [Reborn WebUI Beta] Define WebUI inbound DTO contract

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬2 · 15h ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 2d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 5d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 3 new
- [[News] Gates Foundation Partnership](https://www.anthropic.com/news/gates-foundation-partnership) _2026-05-14_
- [[News] Pwc Expanded Partnership](https://www.anthropic.com/news/pwc-expanded-partnership) _2026-05-15_
- [[Research] 2028 Ai Leadership](https://www.anthropic.com/research/2028-ai-leadership) _2026-05-14_

### OpenAI — 5 new
- [[Policies] Conversion Terms](https://openai.com/policies/conversion-terms/) _2026-05-15_
- [[Policies] Conversion Dpa](https://openai.com/policies/conversion-dpa/) _2026-05-15_
- [[Policies] Conversion Subprocessors](https://openai.com/policies/conversion-subprocessors/) _2026-05-14_
- [[Codex] For Work](https://openai.com/codex/for-work/) _2026-05-14_
- [[Index] Our Response To The Tanstack Npm Supply Chain Attack](https://openai.com/index/our-response-to-the-tanstack-npm-supply-chain-attack/) _2026-05-15_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
