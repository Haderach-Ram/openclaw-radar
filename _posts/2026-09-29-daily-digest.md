---
layout: post
title: "Ecosystem Digest — 2026-09-29"
date: 2026-09-29 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-29
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 390,746 | 9 | 1 | 10 | 0 |
| **hermesagent** | 249,818 | 4 | 4 | 9 | 0 |
| **ZeroClaw** | 32,908 | 5 | 6 | 10 | 0 |
| **IronClaw** | 12,633 | 2 | 0 | 0 | 0 |
| **Moltis** | 2,877 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 390,746 · **Open issues:** 8,953 · **Last push:** <1h ago

### ✅ Merged PRs
- [#159525](https://github.com/openclaw/openclaw/pull/159525) feat(approvals): enforce scoped Slack plugin reviewers
- [#160188](https://github.com/openclaw/openclaw/pull/160188) fix(nodes): explain and recover session-host setup problems
- [#160790](https://github.com/openclaw/openclaw/pull/160790) fix(node): headless nodes with default plugins never activate automatic updates
- [#160885](https://github.com/openclaw/openclaw/pull/160885) fix(health): report unreadable config instead of missing Gateway credentials
- [#160883](https://github.com/openclaw/openclaw/pull/160883) refactor(webhooks): deslop target and guard helpers
- [#160859](https://github.com/openclaw/openclaw/pull/160859) fix(release): keep stable publication handoffs moving
- [#160801](https://github.com/openclaw/openclaw/pull/160801) perf(sessions): yield during SQLite entry write contention
- [#160843](https://github.com/openclaw/openclaw/pull/160843) fix(ci): restore config and node adapter lint budgets
- [#160874](https://github.com/openclaw/openclaw/pull/160874) refactor(daemon): remove unused Unix fixture controls
- [#160867](https://github.com/openclaw/openclaw/pull/160867) fix(ui): progress card stays after dismissing an unfinished or note-only card

### 🐛 New Issues
- [#160891](https://github.com/openclaw/openclaw/issues/160891) Incoming channel message silently swallowed (dispatch complete replies=0) during settle-wake retry storm — 2026.9.6 💬1
- [#160889](https://github.com/openclaw/openclaw/issues/160889) [Bug]: OpenAI tool continuations resend compacted history after ID repair `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬2
- [#160882](https://github.com/openclaw/openclaw/issues/160882) [Feature]: Show whether the utility model runs through Claude CLI or the API `enhancement` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:linked-pr-open` `impact:auth-provider` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬4
- [#160875](https://github.com/openclaw/openclaw/issues/160875) [Bug]: readGatewayRestartIntentPayloadSync silently drops the restart intent on a state-DB read failure `bug` `no-stale` `bug:behavior` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `maturity:stable` 💬2
- [#160870](https://github.com/openclaw/openclaw/issues/160870) [Feature]: Show readable live purposes in the web tool-activity row `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1
- [#160866](https://github.com/openclaw/openclaw/issues/160866) [Bug]: MainSessionRecoveryCapacity has no bounded wait, starving startup recovery dispatch `bug` `bug:behavior` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#160865](https://github.com/openclaw/openclaw/issues/160865) Discord threads: auto-name after a conversation threshold `P3` `impact:ux-friction` 💬1
- [#160863](https://github.com/openclaw/openclaw/issues/160863) sessions --json: inputTokens stays frozen at last-run value on idle sessions, with no freshness marker — downstream pressure monitors false-flag idle sessions for hours `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#160861](https://github.com/openclaw/openclaw/issues/160861) Bridge redelivery duplicates processed messages after restart; no circuit breaker for repeated identical tool calls `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-info` `impact:message-loss` `issue-rating: 🦪 silver shellfish` 💬1

### 🔒 Closed Issues
- [#144769](https://github.com/openclaw/openclaw/issues/144769) Progress card cannot be dismissed by the user unless every plan step is completed (note-only cards never dismissible)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 249,818 · **Open issues:** 45,016 · **Last push:** <1h ago

### ✅ Merged PRs
- [#79510](https://github.com/NousResearch/hermes-agent/pull/79510) fix(tui_gateway): route model switches across the compute-host boundary
- [#126960](https://github.com/NousResearch/hermes-agent/pull/126960) fix(tui_gateway): no automatic model turn starts after the user presses Stop
- [#126344](https://github.com/NousResearch/hermes-agent/pull/126344) Restart-safe cron jobs no longer die on 'No module named ruamel' under multiplex, and fail closed on a broken PM boot (#122222, salvage #122936)
- [#92137](https://github.com/NousResearch/hermes-agent/pull/92137) fix(desktop): memoize statusbar render-contributions so state survives re-renders
- [#119085](https://github.com/NousResearch/hermes-agent/pull/119085) fix(desktop): aggregate registered gateway sessions
- [#119749](https://github.com/NousResearch/hermes-agent/pull/119749) fix(desktop): Maintenance tails a second run of the same op
- [#93362](https://github.com/NousResearch/hermes-agent/pull/93362) fix(desktop): stop trusting composer previewUrl as a full-res upload cache
- [#102744](https://github.com/NousResearch/hermes-agent/pull/102744) fix(desktop): comment mode redacts the whole picked tree and keeps nested groups together
- [#118730](https://github.com/NousResearch/hermes-agent/pull/118730) fix(desktop): resolve the serve subcommand positionally when a profile is named "serve"

### 🐛 New Issues
- [#127249](https://github.com/NousResearch/hermes-agent/issues/127249) [Bug][Windows Desktop]: computer_use contract mismatch causes retry loops when agent edits Hermes UI
- [#127246](https://github.com/NousResearch/hermes-agent/issues/127246) Desktop: sending in a pinned, user-titled session replaces its sidebar title with the prompt preview (stored title intact; ⌘R restores)
- [#127234](https://github.com/NousResearch/hermes-agent/issues/127234) [Bug]: A streaming repetition loop never ends on an uncapped endpoint — every repetition check waits for the stream to finish `type/bug` `comp/agent` `P1` `area/streaming` `area/local-models`
- [#127228](https://github.com/NousResearch/hermes-agent/issues/127228) [Feature]: HUD quicklaunch — warm summon under 200ms, not a cold Desktop boot `type/feature` `P3` `comp/desktop`

### 🔒 Closed Issues
- [#79509](https://github.com/NousResearch/hermes-agent/issues/79509) Desktop/turn isolation: model switch is silently lost on compute-host sessions
- [#124347](https://github.com/NousResearch/hermes-agent/issues/124347) [Bug]: after Stop, a background completion immediately starts a new model turn (TUI/Desktop)
- [#125910](https://github.com/NousResearch/hermes-agent/issues/125910) Cloud gateway instance primus-7774.agents.nousresearch.com unresponsive (TLS accepts, HTTP hangs) since ~15:02 UTC Sep 27
- [#91603](https://github.com/NousResearch/hermes-agent/issues/91603) Desktop: statusbar `render` contribution remounts on every statusbar re-render, destroying component state (dialogs close unexpectedly)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,908 · **Open issues:** 696 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11131](https://github.com/zeroclaw-labs/zeroclaw/pull/11131) feat(runtime): own the observer event firehose in the daemon
- [#11164](https://github.com/zeroclaw-labs/zeroclaw/pull/11164) feat(daemon): own the pricing refresher and the gateway-start hook
- [#11162](https://github.com/zeroclaw-labs/zeroclaw/pull/11162) refactor(gateway): F0 cleanups for the v0.9.0 gateway split
- [#11161](https://github.com/zeroclaw-labs/zeroclaw/pull/11161) test(gateway): record golden frames for WS, SSE, webhook and ACP
- [#11134](https://github.com/zeroclaw-labs/zeroclaw/pull/11134) feat(sop): conditional steps chosen by the decision model
- [#11092](https://github.com/zeroclaw-labs/zeroclaw/pull/11092) chore(runtime): propose a holding-crate exception for the composition contract
- [#11137](https://github.com/zeroclaw-labs/zeroclaw/pull/11137) fix(agents): avoid Windows panic during bundle export
- [#11190](https://github.com/zeroclaw-labs/zeroclaw/pull/11190) docs(security): restore the private memory plane section lost in the #11082 merge
- [#11159](https://github.com/zeroclaw-labs/zeroclaw/pull/11159) test(config): pin stall watchdog opt-in default
- [#11153](https://github.com/zeroclaw-labs/zeroclaw/pull/11153) test(web-search): cover transport error redaction

### 🐛 New Issues
- [#11215](https://github.com/zeroclaw-labs/zeroclaw/issues/11215) [Bug]: Tool calling fails on OpenCode Go ("name" is not supported by this endpoint) `bug`
- [#11208](https://github.com/zeroclaw-labs/zeroclaw/issues/11208) [Bug]: unrecognised memory.backend silently stores memory as Markdown `bug` `config` `memory` `memory:backend` `priority:p1` `status:in-progress` `status:accepted` `risk:medium` 💬1
- [#11207](https://github.com/zeroclaw-labs/zeroclaw/issues/11207) [Feature]: Document a bounded Tsubasa custom-provider setup `enhancement` `docs` `provider` `provider:compatible` `status:accepted` `priority:p3` `risk:low` `type:docs` 💬1
- [#11204](https://github.com/zeroclaw-labs/zeroclaw/issues/11204) [Bug]: OpenRouter spend shows $0.00 and all tokens classified "free tok" — usage.cost never ingested `bug` `config` `observability` `provider` `runtime` `provider:openrouter` `priority:p1` `status:accepted` `risk:high` 💬1
- [#11197](https://github.com/zeroclaw-labs/zeroclaw/issues/11197) [Bug]: Session resume restores forwarded environment after admin revocation `bug` `agent` `runtime` `tool` `domain:security` `priority:p0` `tool:shell` `status:accepted` `follow-up` `risk:high` `topic:identity-access` 💬2

### 🔒 Closed Issues
- [#10280](https://github.com/zeroclaw-labs/zeroclaw/issues/10280) [Task]: Normalize web-search GET transport errors before model forwarding
- [#10171](https://github.com/zeroclaw-labs/zeroclaw/issues/10171) [Feature]: preserve configured provider profile semantics
- [#10645](https://github.com/zeroclaw-labs/zeroclaw/issues/10645) fix(runtime): thread cost-tracking context into delegated sub-loops
- [#10802](https://github.com/zeroclaw-labs/zeroclaw/issues/10802) [Bug]: `session/list-acp` reports a different `message_count` than `turn_end` for the same session
- [#10878](https://github.com/zeroclaw-labs/zeroclaw/issues/10878) [Feature]: Combine ZeroCode Sessions, Queue, and Plan into one resizable dock
- [#9708](https://github.com/zeroclaw-labs/zeroclaw/issues/9708) bug(daemon): bound service launcher stdout and stderr logs

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,633 · **Open issues:** 1,534 · **Last push:** 17h ago

### 🐛 New Issues
- [#8116](https://github.com/nearai/ironclaw/issues/8116) Daily ironclaw failure taxonomy — 2026-09-28
- [#8115](https://github.com/nearai/ironclaw/issues/8115) Add a Tsubasa registry entry with an explicit 32K context-budget path

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,877 · **Open issues:** 99 · **Last push:** 6d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 1d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 2d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 3d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 13d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 21d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 23d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 31d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 35d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 47d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 50d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [Claude Sonnet 5 5](https://www.anthropic.com/claude-sonnet-5-5)

### OpenAI — 5 new
- [[Form] Codex Originals](https://openai.com/form/codex-originals/) _2026-09-29_
- [Codex Originals](https://openai.com/codex-originals/) _2026-09-29_
- [[Index] Basis Tax Workbook With Astra](https://openai.com/index/basis-tax-workbook-with-astra/) _2026-09-28_
- [[Index] How We Will Do Better For Australia](https://openai.com/index/how-we-will-do-better-for-australia/) _2026-09-29_
- [[Index] Lenfest Ai Collaborative Expansion](https://openai.com/index/lenfest-ai-collaborative-expansion/) _2026-09-29_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Finally found a model my hardware can run at full precision: me](https://reddit.com/r/LocalLLaMA/comments/1wsiepp/finally_found_a_model_my_hardware_can_run_at_full/) ↑963
- [GPT-3 is discontinued today](https://reddit.com/r/LocalLLaMA/comments/1ws67x4/gpt3_is_discontinued_today/) ↑690
- [NVIDIA shipped OpenShell, an open source sandbox that gives local and open agents real runtime limits instead of prompt rules. Over 100 firms joined the safety stack. OpenAI did not.](https://reddit.com/r/LocalLLaMA/comments/1ws9ydg/nvidia_shipped_openshell_an_open_source_sandbox/) ↑678
- [Guys I promise It wasn't me 😭😭](https://reddit.com/r/LocalLLaMA/comments/1wsc0iz/guys_i_promise_it_wasnt_me/) ↑427
- [ImaJev-4b: I spent 15 days fine-tuning a 4B model to make business decisions from text and photos, and it just ranked #1 of 91 on JevBench & ahead of GPT-5.6 Luna on DecisionBench](https://reddit.com/r/LocalLLaMA/comments/1wsgrma/imajev4b_i_spent_15_days_finetuning_a_4b_model_to/) ↑155

### r/singularity — top 2 new
- [Claude Sonnet 5.5 Released](https://reddit.com/r/singularity/comments/1wslxcu/claude_sonnet_55_released/) ↑788
- [Reuters: Anthropic files for $2T IPO with $42B net loss in 2025, expects to spend half a trillion in 2027](https://reddit.com/r/singularity/comments/1wsw45e/reuters_anthropic_files_for_2t_ipo_with_42b_net/) ↑325

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [My OpenClaw agents are playing DnD on stream!](https://reddit.com/r/openclaw/comments/1wsqg4f/my_openclaw_agents_are_playing_dnd_on_stream/) ↑8
- [Tired of local AI assistants & agent scripts opening test URLs in your main browser? Built a 1-click macOS menu bar switcher [Free & Open Source]](https://reddit.com/r/openclaw/comments/1wsgwfz/tired_of_local_ai_assistants_agent_scripts/) ↑3
- [Shared local memory DB that OpenClaw can use alongside other agent hosts](https://reddit.com/r/openclaw/comments/1wsebpu/shared_local_memory_db_that_openclaw_can_use/) ↑1
- [OpenClaw first-hour walkthrough: build a Reddit-to-Airtable automation](https://reddit.com/r/openclaw/comments/1wsfv67/openclaw_firsthour_walkthrough_build_a/) ↑0

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [Today Microsoft announced Autopilot, an always on agent built on OpenClaw

The best part of this collaboration is how mu](https://x.com/openclaw/status/2103678752194703762)

### X — @steipete
- [See ya there!](https://x.com/steipete/status/2104702088626557384) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
