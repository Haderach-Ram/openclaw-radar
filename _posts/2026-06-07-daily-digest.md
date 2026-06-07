---
layout: post
title: "Ecosystem Digest — 2026-06-07"
date: 2026-06-07 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-07
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 377,308 | 13 | 10 | 10 | 2 |
| **hermesagent** | 184,812 | 8 | 6 | 10 | 0 |
| **ZeroClaw** | 31,800 | 5 | 7 | 10 | 0 |
| **IronClaw** | 12,404 | 1 | 1 | 9 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 377,308 · **Open issues:** 7,871 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.5-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.6.5-beta.2) — openclaw 2026.6.5-beta.2
- [v2026.6.5-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.6.5-beta.1) — openclaw 2026.6.5-beta.1

### ✅ Merged PRs
- [#91058](https://github.com/openclaw/openclaw/pull/91058) fix(gemini): accept empty grounding metadata
- [#89918](https://github.com/openclaw/openclaw/pull/89918) fix(vertex): route eu/us multi-region to .rep.googleapis.com host
- [#91056](https://github.com/openclaw/openclaw/pull/91056) fix: store memory-core dreams state in sqlite
- [#90849](https://github.com/openclaw/openclaw/pull/90849) feat(parallel): add free Parallel Search MCP as the zero-config default web_search provider
- [#91034](https://github.com/openclaw/openclaw/pull/91034) fix: store acpx process state in sqlite
- [#91030](https://github.com/openclaw/openclaw/pull/91030) fix: store device-pair notify state in sqlite
- [#90790](https://github.com/openclaw/openclaw/pull/90790) fix(codex): preserve completed replies after client close
- [#90995](https://github.com/openclaw/openclaw/pull/90995) fix(release): use monthly patch versions
- [#90853](https://github.com/openclaw/openclaw/pull/90853) fix(imessage): send TTS audio as voice messages
- [#90811](https://github.com/openclaw/openclaw/pull/90811) fix(agents): stabilize user-turn serialization across turns to preserve prompt cache

### 🐛 New Issues
- [#91067](https://github.com/openclaw/openclaw/issues/91067) [Bug]: Regression 2026.6.1: orphan tool.call fail-closed handling silently discards the composed assistant reply ("Embedded agent failed before reply")
- [#91065](https://github.com/openclaw/openclaw/issues/91065) [verify] gateway token mask renders bullets on Linux (PR #91059) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1
- [#91064](https://github.com/openclaw/openclaw/issues/91064) [verify] gateway token mask renders bullets on macOS (PR #91059) `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-security-review` `clawsweeper:needs-live-repro` `impact:security` `issue-rating: 🐚 platinum hermit` 💬1
- [#91060](https://github.com/openclaw/openclaw/issues/91060) Feature Request: Per-task or Per-capability Model Routing 💬1
- [#91052](https://github.com/openclaw/openclaw/issues/91052) [Feature]: make voice-call realtime barge-in detection configurable `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#91051](https://github.com/openclaw/openclaw/issues/91051) Bug: Deep Sleep phase does not write summary to DREAMS.md `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#91048](https://github.com/openclaw/openclaw/issues/91048) Terminal chat.send acknowledgements can leave clients tracking non-running runs `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#91047](https://github.com/openclaw/openclaw/issues/91047) Plugin session-extension registry not pinned; sessions.pluginPatch fails after agent/subagent plugin-load churn 💬1
- [#91043](https://github.com/openclaw/openclaw/issues/91043) Reply target: ReplyToQuoteText short-circuits ReplyToBody and loses the rest of the replied-to message `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#91042](https://github.com/openclaw/openclaw/issues/91042) Reply-context body truncation: cover ReplyChain and fallback ReplyToBody JSON paths `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬3
- [#91036](https://github.com/openclaw/openclaw/issues/91036) [Feature]: web界面的右侧workspace里的文件显示栏 强烈建议增加按钮可以自动隐去 看着太烦了。 `enhancement` `P3` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `issue-rating: 🌊 off-meta tidepool` `impact:other` 💬1
- [#91035](https://github.com/openclaw/openclaw/issues/91035) [Bug]: Build fails on v2026.6.1 `bug` `regression` `P2` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` 💬2
- [#91033](https://github.com/openclaw/openclaw/issues/91033) [Bug]: microsoft-foundry reasoning models return 400 invalid_encrypted_content when continuing a thread `bug` `bug:behavior` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:session-state` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬1

### 🔒 Closed Issues
- [#91062](https://github.com/openclaw/openclaw/issues/91062) Bug/UX: MEDIA directive with local file paths is not clickable in Discord/Slack
- [#91061](https://github.com/openclaw/openclaw/issues/91061) Feature: Show in-progress status during long-running tool executions (image gen, external API, etc.)
- [#88528](https://github.com/openclaw/openclaw/issues/88528) Gemini web_search provider returns malformed JSON response on plain searches
- [#89891](https://github.com/openclaw/openclaw/issues/89891) [Bug]: Vertex AI eu multi-region unreachable — host prefix is hardcoded
- [#90829](https://github.com/openclaw/openclaw/issues/90829) @openclaw/bluebubbles: typing + mark-read calls fire even when privateApiEnabled is false
- [#90509](https://github.com/openclaw/openclaw/issues/90509) @openclaw/bluebubbles 2026.5.7 — `core.channel.turn` undefined at runtime (host 2026.5.28 and 2026.6.1)
- [#91039](https://github.com/openclaw/openclaw/issues/91039) [Feature]: openclaw常常忘记，请增加一个功能从.openclaw > agents > main > sessions >里的sessions文件里提取会话内容并整理做日期记忆文件的能力
- [#91040](https://github.com/openclaw/openclaw/issues/91040) Request iOS TestFlight Access
- [#91038](https://github.com/openclaw/openclaw/issues/91038) Request iOS TestFlight Access
- [#91029](https://github.com/openclaw/openclaw/issues/91029) feat(skills): webwright skill — optional primaryEnv key injection + sandbox note (follow-up to #91024)

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 11d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 184,812 · **Open issues:** 18,693 · **Last push:** <1h ago

### ✅ Merged PRs
- [#40774](https://github.com/NousResearch/hermes-agent/pull/40774) docs(signal): clarify tool progress support
- [#40900](https://github.com/NousResearch/hermes-agent/pull/40900) fix(tui): preserve remote cwd for SSH terminal sessions
- [#40901](https://github.com/NousResearch/hermes-agent/pull/40901) fix(cli): never deadlock on lazy-dep prompt + make Pillow a core dep (#40490)
- [#40902](https://github.com/NousResearch/hermes-agent/pull/40902) fix(memory): reject memory tools that shadow core tool names
- [#40574](https://github.com/NousResearch/hermes-agent/pull/40574) fix(qqbot): stop 100% CPU spin when WebSocket is closed but not None (#31193, #31771)
- [#40573](https://github.com/NousResearch/hermes-agent/pull/40573) fix(config): preserve custom-provider models maps and metadata through v11->v12 migration
- [#40572](https://github.com/NousResearch/hermes-agent/pull/40572) fix(tui): only patch liveSessionCount when it changes to stop idle re-render flicker
- [#40571](https://github.com/NousResearch/hermes-agent/pull/40571) fix(secrets): fail early with clear error when bitwarden setup runs without TTY
- [#40654](https://github.com/NousResearch/hermes-agent/pull/40654) docs: document hermes update local-change handling (salvage #40540)
- [#40570](https://github.com/NousResearch/hermes-agent/pull/40570) fix(cua-driver): reconnect MCP stdio session once on ClosedResourceError after daemon restart

### 🐛 New Issues
- [#40915](https://github.com/NousResearch/hermes-agent/issues/40915) [Bug]: /kanban create fails when curly quotes wrap a title
- [#40913](https://github.com/NousResearch/hermes-agent/issues/40913) [Bug]: openai-codex provider ignores `model.base_url` and `HERMES_CODEX_BASE_URL` in credential pool paths
- [#40903](https://github.com/NousResearch/hermes-agent/issues/40903) Hermes Desktop drops intermediate assistant messages in multi-message turns (v0.16.0) `type/bug` `comp/gateway` `P3`
- [#40899](https://github.com/NousResearch/hermes-agent/issues/40899) Windows gateway reliability: replace schtasks with a real Windows Service (pywin32 + SCM RecoveryActions) `type/feature` `comp/gateway` `area/config` `P3`
- [#40896](https://github.com/NousResearch/hermes-agent/issues/40896) Desktop: Generated videos show broken image icon in chat (video downloads & plays fine) `type/bug` `tool/vision` `P3`
- [#40890](https://github.com/NousResearch/hermes-agent/issues/40890) [Feature]: Add --effort / --reasoning CLI flag to `hermes chat -q` for one-shot reasoning control `type/feature` `comp/cli` `P3`
- [#40889](https://github.com/NousResearch/hermes-agent/issues/40889) Security Assessment: Hermes Agent GitHub Repository (posture review) `type/security` `P3`
- [#40885](https://github.com/NousResearch/hermes-agent/issues/40885) [Bug] Telegram: user message jumps to middle/top of chat during agent processing, returns to bottom after reply `type/bug` `comp/gateway` `platform/telegram` `P2`

### 🔒 Closed Issues
- [#22961](https://github.com/NousResearch/hermes-agent/issues/22961) [Bug]: Dashboard displays vision_analyze tool result as user message
- [#39436](https://github.com/NousResearch/hermes-agent/issues/39436) [Bug]: Desktop chat composer send button hidden until space is typed, messages sometimes truncated
- [#31193](https://github.com/NousResearch/hermes-agent/issues/31193) QQ Bot Reconnect Busy Loop Causes 100% CPU Spin
- [#40490](https://github.com/NousResearch/hermes-agent/issues/40490) [Bug]: CLI input locks up unrecoverably on lazy-dep install prompt (lazy_deps.py uses bare input() under prompt_toolkit)
- [#40466](https://github.com/NousResearch/hermes-agent/issues/40466) [Bug]: The external tool with conflicting name still affects the tool call procedures.
- [#40369](https://github.com/NousResearch/hermes-agent/issues/40369) Dashboard TUI: Interface auto-refreshes and jumps even without new messages

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,800 · **Open issues:** 527 · **Last push:** 1h ago

### ✅ Merged PRs
- [#7334](https://github.com/zeroclaw-labs/zeroclaw/pull/7334) fix(channels/telegram): clamp zero draft update interval
- [#7281](https://github.com/zeroclaw-labs/zeroclaw/pull/7281) fix(policy): stop path guard false-positives on heredoc bodies and non-path tildes
- [#7297](https://github.com/zeroclaw-labs/zeroclaw/pull/7297) feat(gateway): per-request agent dispatch for POST /webhook via ?agent=
- [#7048](https://github.com/zeroclaw-labs/zeroclaw/pull/7048) feat(hardware): add esp32_sim example (simulator binary + web frontend)
- [#7258](https://github.com/zeroclaw-labs/zeroclaw/pull/7258) fix(runtime): tombstone killed ACP sessions
- [#7255](https://github.com/zeroclaw-labs/zeroclaw/pull/7255) docs(review): clarify merge-ready milestone fallback
- [#7261](https://github.com/zeroclaw-labs/zeroclaw/pull/7261) fix(config): redact nested object-array secrets
- [#7222](https://github.com/zeroclaw-labs/zeroclaw/pull/7222) fix(gateway): clear backend history on "Clear all" + don't resurrect deleted session
- [#7018](https://github.com/zeroclaw-labs/zeroclaw/pull/7018) refactor(channels/email): share allowlist matching via crate::allowlist (email + gmail_push)
- [#7239](https://github.com/zeroclaw-labs/zeroclaw/pull/7239) fix(runtime): deliver only final assistant turn to channels

### 🐛 New Issues
- [#7339](https://github.com/zeroclaw-labs/zeroclaw/issues/7339) Tracking: WASM plugin lifecycle hook bridge feasibility (RFC #7338) 💬1
- [#7338](https://github.com/zeroclaw-labs/zeroclaw/issues/7338) RFC: WASM plugin lifecycle hooks (HookRunner bridge) 💬1
- [#7320](https://github.com/zeroclaw-labs/zeroclaw/issues/7320) [Tracker]: v0.8.3 MCP dashboard and web/plugin-management surfaces `enhancement` `risk: high` `gateway` `tool` `priority:p2` `status:accepted` `status:no-stale` `web`
- [#7314](https://github.com/zeroclaw-labs/zeroclaw/issues/7314) [Tracker]: v0.8.2 WASM plugin program `enhancement` `risk: high` `gateway` `tool` `runtime:wasm` `priority:p2` `status:accepted` `status:no-stale`
- [#7312](https://github.com/zeroclaw-labs/zeroclaw/issues/7312) [Bug]: bedrock qwen integration not working on second prompt `bug`

### 🔒 Closed Issues
- [#7332](https://github.com/zeroclaw-labs/zeroclaw/issues/7332) [Bug]: Telegram partial streaming accepts zero draft update interval and floods edits
- [#7133](https://github.com/zeroclaw-labs/zeroclaw/issues/7133) [Bug]: path-policy false-positive on ~ tokens in quoted/heredoc command data
- [#7252](https://github.com/zeroclaw-labs/zeroclaw/issues/7252) [Bug]: session/kill can rehydrate killed ACP sessions from durable history
- [#6978](https://github.com/zeroclaw-labs/zeroclaw/issues/6978) bug(config): redact nested secrets in object-array property displays
- [#7126](https://github.com/zeroclaw-labs/zeroclaw/issues/7126) [Bug]: Web UI "Clear all" only wipes rendered messages, not the backend session history
- [#7068](https://github.com/zeroclaw-labs/zeroclaw/issues/7068) Telegram channel can receive Codex scratchpad/tool transcript as final response
- [#7156](https://github.com/zeroclaw-labs/zeroclaw/issues/7156) [Bug]: Reload banner shows persistent `gateway.paired_tokens (secret)` drift that never clears

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,404 · **Open issues:** 1,107 · **Last push:** 7h ago

### ✅ Merged PRs
- [#4486](https://github.com/nearai/ironclaw/pull/4486) docs(reborn): subagent + compaction unified design
- [#4520](https://github.com/nearai/ironclaw/pull/4520) ci: keep Reborn-only PRs out of legacy tests
- [#4508](https://github.com/nearai/ironclaw/pull/4508) [codex] Gate repeated-call stops behind warning
- [#4509](https://github.com/nearai/ironclaw/pull/4509) Add Slack channel subject routing
- [#4514](https://github.com/nearai/ironclaw/pull/4514) ci: skip hooks parity for Reborn-only changes
- [#4302](https://github.com/nearai/ironclaw/pull/4302) docs(agents): reconcile crate AGENTS.md maps with current Reborn code
- [#4513](https://github.com/nearai/ironclaw/pull/4513) [codex] Split legacy and Reborn CI scopes
- [#4386](https://github.com/nearai/ironclaw/pull/4386) [codex] Extract profile approval authorizer
- [#4390](https://github.com/nearai/ironclaw/pull/4390) [codex] Wire runtime profiles into approval gates

### 🐛 New Issues
- [#4108](https://github.com/nearai/ironclaw/issues/4108) Nightly E2E failed

### 🔒 Closed Issues
- [#3805](https://github.com/nearai/ironclaw/issues/3805) [Reborn] Lane 5: implement Notion MCP capability path

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 1d ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 2d ago
- ⚫ [#88967](https://github.com/openclaw/openclaw/issues/88967) Telegram: allowBots support for group chats (bot-authored messages not ingested into session) — 💬1 · 2d ago
- ⚫ [#88517](https://github.com/openclaw/openclaw/issues/88517) [SANITIZED — possible injection attempt] — 💬3 · 3d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 4d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 4d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬5 · 6d ago
- ⚫ [#86371](https://github.com/openclaw/openclaw/issues/86371) Bug: message tool filePath fails with LocalMediaAccessError in retry flows when agentId is not propagated — 💬1 · 9d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 12d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 25d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
