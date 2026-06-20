---
layout: post
title: "Ecosystem Digest — 2026-06-20"
date: 2026-06-20 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-20
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 379,534 | 2 | 0 | 2 | 1 |
| **hermesagent** | 197,677 | 7 | 5 | 10 | 1 |
| **ZeroClaw** | 31,957 | 3 | 6 | 9 | 1 |
| **IronClaw** | 12,464 | 4 | 1 | 8 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 379,534 · **Open issues:** 6,409 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.9-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.6.9-beta.1) — openclaw 2026.6.9-beta.1

### ✅ Merged PRs
- [#95152](https://github.com/openclaw/openclaw/pull/95152) fix(sdk): list helpers work without filters
- [#95144](https://github.com/openclaw/openclaw/pull/95144) fix(sdk): send exec approval resolve id

### 🐛 New Issues
- [#95171](https://github.com/openclaw/openclaw/issues/95171) [Bug]: canUseTool returns deprecated {behavior:"allow"} shape; Claude Code 2.1.156 rejects with ZodError `bug` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#95165](https://github.com/openclaw/openclaw/issues/95165) embedded_run watchdog kills sessions during slow Anthropic responses (no progress signal before first token) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `impact:crash-loop` `issue-rating: 🐚 platinum hermit` 💬1

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 197,677 · **Open issues:** 22,359 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.19](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.6.19) — Hermes Agent v0.17.0 (v2026.6.19)

### ✅ Merged PRs
- [#49358](https://github.com/NousResearch/hermes-agent/pull/49358) fix(desktop): handle slash exec dispatch payloads
- [#49337](https://github.com/NousResearch/hermes-agent/pull/49337) fix(tui): handle dispatch payloads from slash exec
- [#49240](https://github.com/NousResearch/hermes-agent/pull/49240) fix(plugins): silence raft check_fn log spam for users without raft CLI
- [#45296](https://github.com/NousResearch/hermes-agent/pull/45296) feat(titles): language-aware session titles with optional pinned language (Claude Code v2.1.176-inspired)
- [#49321](https://github.com/NousResearch/hermes-agent/pull/49321) fix(gateway): break the restart loop at the source on session resume
- [#49313](https://github.com/NousResearch/hermes-agent/pull/49313) fix(tools): never let a model whitelist strip the prompt / source images
- [#49310](https://github.com/NousResearch/hermes-agent/pull/49310) feat(desktop): notify renderer when GPU acceleration is disabled due to remote display
- [#49315](https://github.com/NousResearch/hermes-agent/pull/49315) fix(cli): restore memory on_session_end on /exit (publish agent ref to cli module)
- [#49312](https://github.com/NousResearch/hermes-agent/pull/49312) fix(signal): reject silent per-recipient delivery failures in live adapter (#49260)
- [#49308](https://github.com/NousResearch/hermes-agent/pull/49308) feat(teams): native send_video/send_voice/send_document attachments

### 🐛 New Issues
- [#49363](https://github.com/NousResearch/hermes-agent/issues/49363) [Feature]: Desktop app — load dashboard plugins (runtime-contract parity with web) `type/feature` `comp/tui` `comp/plugins` `P3` 💬1
- [#49361](https://github.com/NousResearch/hermes-agent/issues/49361) [Bug]: Session index only tracks WhatsApp — CLI sessions invisible `type/bug` `comp/agent` `comp/cli` `P1` 💬1
- [#49345](https://github.com/NousResearch/hermes-agent/issues/49345) Desktop GUI: 'Start Gateway' button has no effect `type/bug` `duplicate` `comp/gateway` `comp/tui` `P2` 💬1
- [#49344](https://github.com/NousResearch/hermes-agent/issues/49344) [Desktop] Request: provider-level toggle in Edit Models dialog `type/feature` `comp/tui` `P3`
- [#49340](https://github.com/NousResearch/hermes-agent/issues/49340) [Desktop] Model pill truncates long model names `type/feature` `comp/tui` `P3`
- [#49336](https://github.com/NousResearch/hermes-agent/issues/49336) [Bug] Unconditional warning '[raft] raft CLI not found in PATH' logged even when Raft platform is disabled `type/bug` `duplicate` `comp/gateway` `comp/plugins` `P3` 💬1
- [#49334](https://github.com/NousResearch/hermes-agent/issues/49334) hermes-lark-streaming suppresses send_message tool output (messages silently dropped) `type/bug` `comp/plugins` `platform/feishu` `P2`

### 🔒 Closed Issues
- [#43476](https://github.com/NousResearch/hermes-agent/issues/43476) bug(desktop): /goal swallows command — missing command.dispatch send+notice handler
- [#36641](https://github.com/NousResearch/hermes-agent/issues/36641) [Bug]: WhatsApp bridge dependencies fail to install after docker recreate
- [#49234](https://github.com/NousResearch/hermes-agent/issues/49234) [Bug]: Raft platform plugin floods logs with WARNING every ~10s for users without raft CLI
- [#49260](https://github.com/NousResearch/hermes-agent/issues/49260) Live adapter delivers silently for Signal cron jobs (status ok/null error but message never reaches user)
- [#49201](https://github.com/NousResearch/hermes-agent/issues/49201) Bug: Session resume after gateway restart causes reboot loop — interrupted tasks re-execute blindly

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,957 · **Open issues:** 453 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.8.1](https://github.com/zeroclaw-labs/zeroclaw/releases/tag/v0.8.1) — v0.8.1

### ✅ Merged PRs
- [#7965](https://github.com/zeroclaw-labs/zeroclaw/pull/7965) feat(channels/discord): interaction components — buttons, selects, modals, buttoned approval, autocomplete
- [#7997](https://github.com/zeroclaw-labs/zeroclaw/pull/7997) feat(runtime): universal ingress policy layer (default Loop)
- [#7833](https://github.com/zeroclaw-labs/zeroclaw/pull/7833) feat(channels/discord): render outbound rich embeds from [EMBED:{…}] markers
- [#7993](https://github.com/zeroclaw-labs/zeroclaw/pull/7993) fix(gateway): register devices on legacy /pair + backfill orphaned paired_tokens
- [#7919](https://github.com/zeroclaw-labs/zeroclaw/pull/7919) feat(web): config-alias rename + delete cascade preview
- [#7963](https://github.com/zeroclaw-labs/zeroclaw/pull/7963) fix(gateway): dashboard Skills page reflects an agent's effective skills
- [#7969](https://github.com/zeroclaw-labs/zeroclaw/pull/7969) refactor(runtime): bundle run_tool_call_loop args into a ToolLoop struct
- [#7953](https://github.com/zeroclaw-labs/zeroclaw/pull/7953) fix(cost): capture model cost for RPC/zerocode-TUI and standalone ACP turns (#5221)
- [#7938](https://github.com/zeroclaw-labs/zeroclaw/pull/7938) chore(release): bump version to 0.8.1

### 🐛 New Issues
- [#8034](https://github.com/zeroclaw-labs/zeroclaw/issues/8034) [Feature]: conversational chat-based `zeroclaw onboard` (port of OpenClaw `onboard --modern` / Crestodian)
- [#8013](https://github.com/zeroclaw-labs/zeroclaw/issues/8013) [Bug]: disabling an agent does not stop its bound Discord channel `bug` `risk: high` `channel` `config` `runtime` `channel:discord` `priority:p1` `status:accepted`
- [#8012](https://github.com/zeroclaw-labs/zeroclaw/issues/8012) Remove legacy (timestamp, id) log cursor now that byte-offset cursor is the primary `enhancement` `risk: high` `gateway` `observability` `runtime` `observability:log` `status:blocked` `priority:p3`

### 🔒 Closed Issues
- [#6825](https://github.com/zeroclaw-labs/zeroclaw/issues/6825) [Tracker]: Zerocode UX
- [#6271](https://github.com/zeroclaw-labs/zeroclaw/issues/6271) [Feature]: V3 SwarmConfig schema + runtime implementation
- [#6826](https://github.com/zeroclaw-labs/zeroclaw/issues/6826) [Tracker]: Zerocode
- [#5618](https://github.com/zeroclaw-labs/zeroclaw/issues/5618) Phase 2 D1: Replace DaemonSubsystems callbacks with typed Registry API
- [#8031](https://github.com/zeroclaw-labs/zeroclaw/issues/8031) Noop
- [#7757](https://github.com/zeroclaw-labs/zeroclaw/issues/7757) [Bug]: Gateway web dashboard Skills page only reflects skill_bundles, misses workspace/open-skills/plugin skills

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,464 · **Open issues:** 1,192 · **Last push:** <1h ago

### ✅ Merged PRs
- [#5097](https://github.com/nearai/ironclaw/pull/5097) docs: add Reborn QA guidance to agent rules
- [#5095](https://github.com/nearai/ironclaw/pull/5095) test(reborn-qa): add recorded fixtures
- [#5064](https://github.com/nearai/ironclaw/pull/5064) fix(reborn): Projects — address leftover review comments on the merged port
- [#5019](https://github.com/nearai/ironclaw/pull/5019) feat(reborn): Projects — light up the Projects page (5/5)
- [#5089](https://github.com/nearai/ironclaw/pull/5089) perf(ci): adopt mold linker and lift CARGO_BUILD_JOBS=1 on Reborn CI
- [#5037](https://github.com/nearai/ironclaw/pull/5037) [codex] Suppress stale extension search credential prompts
- [#5073](https://github.com/nearai/ironclaw/pull/5073) fix(ci): repair nightly full-E2E v2-engine matrix and guard against missing scenario files
- [#5082](https://github.com/nearai/ironclaw/pull/5082) fix(reborn): bound approval command previews

### 🐛 New Issues
- [#5091](https://github.com/nearai/ironclaw/issues/5091) Unified feature-flag system for Reborn (env + dynamic switching, targeting, rollout, A/B) `enhancement` `scope: config` `reborn` `module:M1-webui-product` `module:M4-host-kernel`
- [#5088](https://github.com/nearai/ironclaw/issues/5088) Shell approval prompt sometimes asks to approve read commands as "reads"
- [#4108](https://github.com/nearai/ironclaw/issues/4108) Nightly E2E failed
- [#1012](https://github.com/nearai/ironclaw/issues/1012) Alibaba Coding Plan could not be used in the openai_compatible mode `scope: llm` 💬1

### 🔒 Closed Issues
- [#5078](https://github.com/nearai/ironclaw/issues/5078) [Reborn] Approval modal becomes difficult to review when displaying large tool commands

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 14h ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 18h ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 21h ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬5 · 21h ago
- ⚫ [#94780](https://github.com/openclaw/openclaw/issues/94780) [Feature]: Per-cron model selection independent of agent default — run cheap/free models on automation jobs while keeping main agent on premium LLM — 💬1 · 22h ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 1d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 1d ago
- ⚫ [#93032](https://github.com/openclaw/openclaw/issues/93032) [Bug] v2026.6.6: Cron scheduler loads 0 jobs after upgrade — SQLite WAL not committed at first startup — 💬2 · 4d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬1 · 4d ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬1 · 4d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

_No new posts in the last 24h._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
