---
layout: post
title: "Ecosystem Digest — 2026-06-19"
date: 2026-06-19 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-19
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 379,414 | 6 | 6 | 2 | 0 |
| **hermesagent** | 197,032 | 4 | 3 | 7 | 0 |
| **ZeroClaw** | 31,945 | 10 | 1 | 10 | 1 |
| **IronClaw** | 12,459 | 8 | 9 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 379,414 · **Open issues:** 6,512 · **Last push:** <1h ago

### ✅ Merged PRs
- [#88581](https://github.com/openclaw/openclaw/pull/88581) feat(commands): add /name to rename the current session from chat
- [#88551](https://github.com/openclaw/openclaw/pull/88551) fix(agents): skip auth gate for CLI-owned transport

### 🐛 New Issues
- [#94750](https://github.com/openclaw/openclaw/issues/94750) [Bug]: Discord channel sessions lose recent conversation context after reset, breaking organic continuity `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `issue-rating: 🐚 platinum hermit` 💬1
- [#94748](https://github.com/openclaw/openclaw/issues/94748) Bug: fitCodexProjectedContextForTurnStart returns text exceeding maxChars when header + user request fill the turn limit (overflows Codex turn/start) `no-stale` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#94747](https://github.com/openclaw/openclaw/issues/94747) Discord channel mention can end as non_deliverable_terminal_turn with no message.send and no visible reply `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#94730](https://github.com/openclaw/openclaw/issues/94730) doctor: copy-sensitive paths get re-wrapped by clack note box, splitting file extensions `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#94727](https://github.com/openclaw/openclaw/issues/94727) skills/trello: requires.bins gates on jq but every body example also needs curl `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#94716](https://github.com/openclaw/openclaw/issues/94716) [Bug]: Anthropic claude-cli provider sends stale user-agent (claude-cli/2.1.75) — bearer auth fails with authentication_error `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#94675](https://github.com/openclaw/openclaw/issues/94675) [Feature]: Define a database abstraction layer for a dual-backend (SQLite + Postgres)
- [#85228](https://github.com/openclaw/openclaw/issues/85228) [Bug]:
- [#85065](https://github.com/openclaw/openclaw/issues/85065) [Bug]: claude-cli harness selection has no fallback path when registration races with session resume (2026.5.x)
- [#85043](https://github.com/openclaw/openclaw/issues/85043) Dashboard UI renders Chinese agent names as mojibake (UTF-8 displayed as Latin-1)
- [#83964](https://github.com/openclaw/openclaw/issues/83964) @openclaw/codex 2026.5.18 can fail with ERR_MODULE_NOT_FOUND for package 'openclaw' unless openclaw is installed locally
- [#83778](https://github.com/openclaw/openclaw/issues/83778) Cron jobs with tools enabled cause delivery failure and silent fallback to DM

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 1d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 197,032 · **Open issues:** 22,020 · **Last push:** <1h ago

### ✅ Merged PRs
- [#48699](https://github.com/NousResearch/hermes-agent/pull/48699) feat(cli): lock hermes worktrees so concurrent processes can't clobber them
- [#48688](https://github.com/NousResearch/hermes-agent/pull/48688) fix(state): survive SQLite builds without trigram tokenizer + warn on unavailable session store
- [#48724](https://github.com/NousResearch/hermes-agent/pull/48724) fix(relay): trigger self-provision on relay-config + NAS token, not is_managed()
- [#48541](https://github.com/NousResearch/hermes-agent/pull/48541) fix(docker): support WebUI installs from read-only sources
- [#48294](https://github.com/NousResearch/hermes-agent/pull/48294) feat(relay): WS-only inbound on the gateway adapter (Phase 3)
- [#48657](https://github.com/NousResearch/hermes-agent/pull/48657) fix(npm): lock react-simple-icons to 13.11.1
- [#37546](https://github.com/NousResearch/hermes-agent/pull/37546) fix(desktop): show Hindsight memory provider

### 🐛 New Issues
- [#48755](https://github.com/NousResearch/hermes-agent/issues/48755) [Feature]: A quick workaround to get CTranslate2 on Termux. `type/feature` `P3`
- [#48747](https://github.com/NousResearch/hermes-agent/issues/48747) After a scheduled task is completed, a prompt should be highlighted to inform the user that it has been executed `type/feature` `comp/cron` `P3`
- [#48746](https://github.com/NousResearch/hermes-agent/issues/48746) issue `type/bug` `duplicate` `comp/cli` `comp/gateway` `P1` 💬1
- [#48731](https://github.com/NousResearch/hermes-agent/issues/48731) /model switch to shared model name prefers native provider over current reseller `type/bug` `comp/cli` `area/auth` `P2` 💬1

### 🔒 Closed Issues
- [#41386](https://github.com/NousResearch/hermes-agent/issues/41386) Bug: CLI/Desktop prompts can run live-only when state.db is unavailable
- [#47002](https://github.com/NousResearch/hermes-agent/issues/47002) SessionDB.__init__ crashes on SQLite without trigram tokenizer (v0.16.0 regression)
- [#48198](https://github.com/NousResearch/hermes-agent/issues/48198) [Bug]: `nousresearch/hermes-agent` Docker image ships `/opt/hermes` as `555 root:root` with no LICENSE file — breaks multi-container Hermes WebUI installs

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,945 · **Open issues:** 408 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.8.1](https://github.com/zeroclaw-labs/zeroclaw/releases/tag/v0.8.1) — v0.8.1

### ✅ Merged PRs
- [#7938](https://github.com/zeroclaw-labs/zeroclaw/pull/7938) chore(release): bump version to 0.8.1
- [#7848](https://github.com/zeroclaw-labs/zeroclaw/pull/7848) fix(cli): flag configured channels missing from binary
- [#7933](https://github.com/zeroclaw-labs/zeroclaw/pull/7933) fix(provider): trace native tool delivery decisions
- [#7939](https://github.com/zeroclaw-labs/zeroclaw/pull/7939) docs(i18n): refresh fluent strings and mdbook catalogs for v0.8.1
- [#7934](https://github.com/zeroclaw-labs/zeroclaw/pull/7934) fix(runtime): route stdout diagnostics through logs
- [#7906](https://github.com/zeroclaw-labs/zeroclaw/pull/7906) fix(tests): cover Windows path and shell portability
- [#7547](https://github.com/zeroclaw-labs/zeroclaw/pull/7547) fix(runtime): auto-include discovered MCP tools in risk_profile allowed_tools
- [#7826](https://github.com/zeroclaw-labs/zeroclaw/pull/7826) fix(runtime/agent): move credential redaction to the rendering layer
- [#7834](https://github.com/zeroclaw-labs/zeroclaw/pull/7834) fix(zerocode): refresh agent picker on Code/Chat tab re-entry
- [#7492](https://github.com/zeroclaw-labs/zeroclaw/pull/7492) feat(cost): support cached input token pricing from OpenAI-compatible

### 🐛 New Issues
- [#7952](https://github.com/zeroclaw-labs/zeroclaw/issues/7952) feat(release): publish full-channel prebuilt assets alongside default prebuilts `enhancement` `ci` `risk: high` `channel` `priority:p2` `needs-maintainer-review`
- [#7951](https://github.com/zeroclaw-labs/zeroclaw/issues/7951) [Feature]: Effort-based local/cloud model routing `enhancement` `risk: high` `agent` `config` `provider` `runtime` `provider:ollama` `provider:router` `priority:p2` `status:accepted`
- [#7950](https://github.com/zeroclaw-labs/zeroclaw/issues/7950) [Feature]: Request for docker images to include zeroclaw docs `enhancement`
- [#7949](https://github.com/zeroclaw-labs/zeroclaw/issues/7949) [Bug]: [[embedding_routes]] silently degrades to NoopEmbedding (route feature effectively dead) `bug` `risk: medium` `config` `memory` `priority:p2` `status:accepted`
- [#7948](https://github.com/zeroclaw-labs/zeroclaw/issues/7948) [Feature]: Persist embedding identity and auto-migrate vectors when the embedding model changes `enhancement` `risk: medium` `config` `memory` `priority:p3`
- [#7947](https://github.com/zeroclaw-labs/zeroclaw/issues/7947) [SANITIZED — possible injection attempt] `bug` `risk: high` `config` `runtime` `security` `tool` `domain:security` `priority:p1` `status:accepted`
- [#7944](https://github.com/zeroclaw-labs/zeroclaw/issues/7944) [Feature]: Voice satellite (ESP32 / smartphone / browser PWA) + approval buttons over the realtime voice-host contract `enhancement` `risk: medium` `channel` `gateway` `priority:p3` 💬1
- [#7943](https://github.com/zeroclaw-labs/zeroclaw/issues/7943) [Feature]: Realtime voice-host channel (backend-agnostic WS client; CrispASR reference, Wyoming-aligned) `enhancement` `risk: medium` `channel` `config` `gateway` `priority:p2` 💬1
- [#7941](https://github.com/zeroclaw-labs/zeroclaw/issues/7941) [Bug]: agent delete can purge owned state before config persistence (mirror of #7907) `bug` `risk: high` `agent` `config` `gateway` `runtime` `priority:p1`
- [#7929](https://github.com/zeroclaw-labs/zeroclaw/issues/7929) [Feature]: Unify slash-command registries across web UI, zerocode TUI, and channel runtime

### 🔒 Closed Issues
- [#7799](https://github.com/zeroclaw-labs/zeroclaw/issues/7799) [Bug]: Resumed Code sessions reopen with a blank transcript

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,459 · **Open issues:** 1,189 · **Last push:** 1h ago

### ✅ Merged PRs
- [#5018](https://github.com/nearai/ironclaw/pull/5018) feat(reborn): Projects — WebChat v2 endpoints (4/5)
- [#5067](https://github.com/nearai/ironclaw/pull/5067) fix(reborn): keep OAuth auth gates visible without auth URL
- [#5074](https://github.com/nearai/ironclaw/pull/5074) perf(ci): seed Rust cache from merge queue and stabilize restore keys
- [#5047](https://github.com/nearai/ironclaw/pull/5047) fix(reborn): skills install validation clearing
- [#5053](https://github.com/nearai/ironclaw/pull/5053) fix(reborn): refresh OAuth runtime credentials on staging
- [#5048](https://github.com/nearai/ironclaw/pull/5048) [codex] Add GitHub authenticated user capability
- [#5017](https://github.com/nearai/ironclaw/pull/5017) feat(reborn): Projects — composition wiring (3/5)
- [#4924](https://github.com/nearai/ironclaw/pull/4924) refactor(webui): replace Logs/Docs icons with text labels
- [#5016](https://github.com/nearai/ironclaw/pull/5016) feat(reborn): Projects — ProjectService port + facade (2/5)
- [#5057](https://github.com/nearai/ironclaw/pull/5057) feat(reborn): read-only agent filesystem viewer in webui v2

### 🐛 New Issues
- [#5083](https://github.com/nearai/ironclaw/issues/5083) Triggers: active automations list scans unbounded completed-row prefix (state-unaware scoped index)
- [#5078](https://github.com/nearai/ironclaw/issues/5078) [Reborn] Approval modal becomes difficult to review when displaying large tool commands 💬1
- [#5077](https://github.com/nearai/ironclaw/issues/5077) [Reborn] Invalid chat URLs should redirect to new chat instead of erroring `bug` `scope: channel/web` `reborn` `UX / Onboarding`
- [#5076](https://github.com/nearai/ironclaw/issues/5076) [Reborn] Sidebar keeps chat thread highlighted on non-chat pages `bug` `scope: channel/web` `reborn` `UX / Onboarding`
- [#5071](https://github.com/nearai/ironclaw/issues/5071) [Reborn] Proactively refresh Google OAuth tokens before expiry `bug` `risk: high` `scope: worker` `scope: secrets` `reborn` `OAuth / Authorization`
- [#5069](https://github.com/nearai/ironclaw/issues/5069) [Reborn] Automation UX Redesign
- [#4992](https://github.com/nearai/ironclaw/issues/4992) [Reborn] Local-dev SSO access mismatch can make Railway automations fail before run/thread creation `bug` `risk: medium` `scope: channel/web` `scope: db/libsql` `scope: worker` `reborn` `OAuth / Authorization` 💬1
- [#4918](https://github.com/nearai/ironclaw/issues/4918) [Reborn] Automations Findings 06/15/2026 - 06/21/2026 💬1

### 🔒 Closed Issues
- [#5060](https://github.com/nearai/ironclaw/issues/5060) [Reborn] GitHub analysis workflows may enter repeated approval loops and never produce results
- [#4907](https://github.com/nearai/ironclaw/issues/4907) [Reborn] Run may fail after successful Google OAuth instead of resuming execution
- [#5070](https://github.com/nearai/ironclaw/issues/5070) Auth gate cancel after approval can replay OAuth prompt and leave activity running
- [#5066](https://github.com/nearai/ironclaw/issues/5066) Keep chat OAuth auth gates visible when authorization URL is unavailable
- [#4942](https://github.com/nearai/ironclaw/issues/4942) [Reborn WebUI] Tool calls failed won't appear until the re-fetch/reload
- [#5007](https://github.com/nearai/ironclaw/issues/5007) [Reborn] Skills validation error does not clear after required fields are filled
- [#4704](https://github.com/nearai/ironclaw/issues/4704) builtin.http approval loop repeats after invalid_input failure without actionable error details
- [#4810](https://github.com/nearai/ironclaw/issues/4810) [Reborn] Conversation Testing Findings 06/08/2026 - 06/14/2026
- [#4761](https://github.com/nearai/ironclaw/issues/4761) [Reborn] Agent stops after repeated tool failures instead of recovering

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 1h ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 5h ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 19h ago
- ⚫ [#93032](https://github.com/openclaw/openclaw/issues/93032) [Bug] v2026.6.6: Cron scheduler loads 0 jobs after upgrade — SQLite WAL not committed at first startup — 💬2 · 3d ago
- 🟢 [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 3d ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 3d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬5 · 3d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬1 · 3d ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬1 · 3d ago
- ⚫ [#92974](https://github.com/openclaw/openclaw/issues/92974) Bug: v2026.6.6 getAttributionHeaders() crashes on Bedrock models — baseUrl undefined (null-guard missing) — 💬1 · 4d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Research] Project Fetch Phase Two](https://www.anthropic.com/research/project-fetch-phase-two) _2026-06-18_

### OpenAI — 1 new
- [[Index] Diagnose Rare Childhood Diseases](https://openai.com/index/diagnose-rare-childhood-diseases/) _2026-06-18_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

_No new posts in the last 24h._

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw
_No new posts in the last 24h._

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
- [/usage got the full treatment 

Native full footers, default templates, fixed-decimal formatting, credential-aware limit](https://x.com/openclaw) ↑0 🔁0 · recent


### X — @steipete
- [Yup! There’s even a worktreeinclude to customize which files codex should copy when creating new trees.](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
