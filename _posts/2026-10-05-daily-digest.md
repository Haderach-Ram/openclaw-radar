---
layout: post
title: "Ecosystem Digest — 2026-10-05"
date: 2026-10-05 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-05
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 391,328 | 13 | 7 | 10 | 0 |
| **hermesagent** | 251,250 | 7 | 3 | 8 | 0 |
| **ZeroClaw** | 32,933 | 4 | 1 | 6 | 0 |
| **IronClaw** | 12,640 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,885 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 391,328 · **Open issues:** 9,338 · **Last push:** <1h ago

### ✅ Merged PRs
- [#165249](https://github.com/openclaw/openclaw/pull/165249) perf(worker): reduce retained task transport overhead
- [#165194](https://github.com/openclaw/openclaw/pull/165194) fix: queued chat turns report run start and tool events to another turn's client
- [#165156](https://github.com/openclaw/openclaw/pull/165156) fix(ci): startup-recovery WebChat test fails when the host is loaded
- [#165258](https://github.com/openclaw/openclaw/pull/165258) fix: X entrypoint fails the bundled channel guard
- [#165259](https://github.com/openclaw/openclaw/pull/165259) fix: label X channel changes
- [#165221](https://github.com/openclaw/openclaw/pull/165221) perf(sessions): bound transcript source reads
- [#165250](https://github.com/openclaw/openclaw/pull/165250) fix: stabilize queued followup idle-bound tests
- [#165251](https://github.com/openclaw/openclaw/pull/165251) fix: classify X runtime API in plugin guardrails
- [#165254](https://github.com/openclaw/openclaw/pull/165254) perf(sessions): page lifecycle artifact cleanup planning
- [#165212](https://github.com/openclaw/openclaw/pull/165212) fix(agents): Code Mode and computer calls fail when providers reuse tool call ids across steps

### 🐛 New Issues
- [#165270](https://github.com/openclaw/openclaw/issues/165270) [Bug]: xAI OAuth refresh exceeds 120000 ms hard timeout although endpoints respond in ~100 ms; 1 ms expiry sentinel forces refresh on every use 💬1
- [#165269](https://github.com/openclaw/openclaw/issues/165269) [Feature]: Azure Speech dictation in the dashboard 💬1
- [#165268](https://github.com/openclaw/openclaw/issues/165268) [Bug]: OpenClaw workspace name is clipped in a 258px sidebar `no-stale` `P3` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬3
- [#165266](https://github.com/openclaw/openclaw/issues/165266) [Bug]: Linux chat-triggered update rollback waits the full 30-minute drain on an already-stopped Gateway `no-stale` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:crash-loop` `P0` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-release-blocker` 💬3
- [#165264](https://github.com/openclaw/openclaw/issues/165264) Upgrade failure artifacts hide the failed step behind successful Doctor output `no-stale` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#165260](https://github.com/openclaw/openclaw/issues/165260) [Bug]: legacy upgrade fixture selects unused bundled plugins `bug` `no-stale` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#165253](https://github.com/openclaw/openclaw/issues/165253) [Bug]: gateway OOMs at boot once openclaw-agent.sqlite outgrows the heap — trajectory retention default (512 MiB) plus an unbounded StatementSync.all() on startup `clawsweeper:needs-info` `impact:crash-loop` `P0` `issue-rating: 🦐 gold shrimp` 💬1
- [#165245](https://github.com/openclaw/openclaw/issues/165245) memory.promotion.applied event should record droppedDates/budgetChars (budget compaction is unobservable) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `impact:session-state` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#165234](https://github.com/openclaw/openclaw/issues/165234) [Feature]: Stop committing Control UI translation memory (*.tm.jsonl) to main history `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:other` 💬1
- [#165226](https://github.com/openclaw/openclaw/issues/165226) Bug: isolated scheduled agent turns fail on extended-stable 2026.8.35 `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#165214](https://github.com/openclaw/openclaw/issues/165214) [Bug]: Doctor refuses maintenance on a stale Gateway lock left by an exited container instead of waiting and reclaiming like Gateway startup `bug` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `P0` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-release-blocker` 💬1
- [#165208](https://github.com/openclaw/openclaw/issues/165208) feat(memory): durable recovery for asynchronous embedding batches `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `impact:session-state` `issue-rating: 🌊 off-meta tidepool` 💬2
- [#165206](https://github.com/openclaw/openclaw/issues/165206) FaceTime plugin: two blockers on macOS 27 (driver build fails with Xcode 27; helper dlopen rejected by FaceTime) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` 💬1

### 🔒 Closed Issues
- [#165252](https://github.com/openclaw/openclaw/issues/165252) X entrypoint fails the bundled channel import guard
- [#165262](https://github.com/openclaw/openclaw/issues/165262) Update failure: clean-check (2026.9.6)
- [#165256](https://github.com/openclaw/openclaw/issues/165256) [Bug]: X channel is missing label routing and fails extension coverage
- [#165246](https://github.com/openclaw/openclaw/issues/165246) [Bug]: queued followup idle-bound E2E test fails before terminal work settles
- [#165255](https://github.com/openclaw/openclaw/issues/165255) [Bug]: declaration fixture omits a required runtime postbuild module
- [#165229](https://github.com/openclaw/openclaw/issues/165229) [Bug]: identical-package update rejects admitted legacy config
- [#157657](https://github.com/openclaw/openclaw/issues/157657) [Bug]: Plugin reinstall churn invalidates an unrelated provider plugin, leaving reply dispatch unpublished for ~20 min and dropping a subagent completion

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 251,250 · **Open issues:** 47,987 · **Last push:** <1h ago

### ✅ Merged PRs
- [#132922](https://github.com/NousResearch/hermes-agent/pull/132922) fix(anthropic): Opus 5.5 keeps thinking on, Sonnet 5.5 turns it off with between_tools
- [#133012](https://github.com/NousResearch/hermes-agent/pull/133012) fix(plugins): a user-installed model provider reports enabled, as the loader treats it
- [#132773](https://github.com/NousResearch/hermes-agent/pull/132773) Desktop no longer paints the same reply twice in one bubble after a housekeeping tool
- [#132995](https://github.com/NousResearch/hermes-agent/pull/132995) docs(image-routing): stop claiming the reverted provider-wide supports_vision probe
- [#132996](https://github.com/NousResearch/hermes-agent/pull/132996) fix(plugins): desktop admission lint must scan repo-root plugin.js too
- [#133004](https://github.com/NousResearch/hermes-agent/pull/133004) fix(auth): find the Claude CLI outside PATH in external-process and setup-token checks
- [#132997](https://github.com/NousResearch/hermes-agent/pull/132997) fix(agent): don't promote Anthropic summarized thinking to the final answer
- [#132927](https://github.com/NousResearch/hermes-agent/pull/132927) fix(update): hermes update no longer stalls on a 20-minute git repack

### 🐛 New Issues
- [#133037](https://github.com/NousResearch/hermes-agent/issues/133037) [local-runtime] mmproj/audio-codec GGUFs are offered as servable models: staged_in() has no companion-asset filter
- [#133036](https://github.com/NousResearch/hermes-agent/issues/133036) [Feature]: sessions list: column selection, sort order and JSON output
- [#133028](https://github.com/NousResearch/hermes-agent/issues/133028) [Bug]: memory: lowering memory_char_limit / user_char_limit locks USER.md/MEMORY.md, every remove is refused as 'external drift' `type/bug` `tool/memory` `P2` `sweeper:risk-session-state` `sweeper:risk-compatibility` `area/memory`
- [#133026](https://github.com/NousResearch/hermes-agent/issues/133026) [SANITIZED — possible injection attempt] `type/bug` `comp/cli` `area/config` `P2` `sweeper:risk-compatibility`
- [#133025](https://github.com/NousResearch/hermes-agent/issues/133025) [Feature]: Optional Feed, Ideas, and Goals views over shared durable records `type/feature` `innovation` `comp/cli` `comp/plugins` `P3` `needs-decision` `comp/desktop` `comp/dashboard`
- [#133017](https://github.com/NousResearch/hermes-agent/issues/133017) [Bug]: one out-of-contract counter row aborts shared-metrics packaging for every metric in the period `type/bug` `comp/cli` `comp/plugins` `P3` `needs-repro` `telemetry`
- [#133013](https://github.com/NousResearch/hermes-agent/issues/133013) [Feature]: sessions CLI: show the values you filter on (preview + list columns, sort, absolute date) `type/feature` `comp/cli` `P3` `sweeper:risk-session-state` `area/sessions` 💬4

### 🔒 Closed Issues
- [#120069](https://github.com/NousResearch/hermes-agent/issues/120069) Anthropic adapter: claude-opus-5-5 rejects thinking.type=disabled, so title generation and /reasoning none fail with HTTP 400
- [#128870](https://github.com/NousResearch/hermes-agent/issues/128870) Desktop: duplicate assistant reply — frame-level evidence (single socket, one message.complete) points at the streaming bubble not being replaced
- [#130396](https://github.com/NousResearch/hermes-agent/issues/130396) Desktop chat: assistant reply with markdown table renders twice after a tool call

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,933 · **Open issues:** 925 · **Last push:** 2h ago

### ✅ Merged PRs
- [#11521](https://github.com/zeroclaw-labs/zeroclaw/pull/11521) docs(runtime): record the Core Team approval of the composition exception
- [#11518](https://github.com/zeroclaw-labs/zeroclaw/pull/11518) fix(approval): preserve CLI input failure provenance
- [#11524](https://github.com/zeroclaw-labs/zeroclaw/pull/11524) docs(runtime): propose a bounded exception for startup recovery of abandoned session turns
- [#11496](https://github.com/zeroclaw-labs/zeroclaw/pull/11496) fix(runtime): localize iMessage and generic chat guidance
- [#11483](https://github.com/zeroclaw-labs/zeroclaw/pull/11483) test(mcp): launch stdio fixtures through shell interpreter
- [#11495](https://github.com/zeroclaw-labs/zeroclaw/pull/11495) test(tools): reuse installed executable in budget fixture

### 🐛 New Issues
- [#11525](https://github.com/zeroclaw-labs/zeroclaw/issues/11525) [Bug]: quickstart fails on Android/Termux `bug` `config` `security:secrets` `domain:security` `priority:p1` `quickstart` `risk:high` 💬3
- [#11519](https://github.com/zeroclaw-labs/zeroclaw/issues/11519) [Bug]: resumed workspace split hides installed plugins from recovery `bug` `config` `priority:p1` `status:in-progress` `risk:medium` `release:v0.8.6` `plugins`
- [#11517](https://github.com/zeroclaw-labs/zeroclaw/issues/11517) [Bug]: Web chat: reloading mid-turn drops the user's prompt (screen and localStorage) because hydration replaces local state with a snapshot that predates the running turn `bug` `gateway` `priority:p2` `risk:medium` `web` 💬1
- [#11515](https://github.com/zeroclaw-labs/zeroclaw/issues/11515) [Bug]: cost ledger drops torn-write records from all rollups (WARN only, no quarantine, totals look complete) `bug` `config` `observability` `priority:p2` `risk:medium` 💬1

### 🔒 Closed Issues
- [#11335](https://github.com/zeroclaw-labs/zeroclaw/issues/11335) [Bug]: CLI approval prompt with no terminal and stdin at EOF reports the runtime's fail-closed denial as `Denied by user`

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,640 · **Open issues:** 1,539 · **Last push:** 5h ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,885 · **Open issues:** 102 · **Last push:** 12d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 1d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 7d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 8d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 9d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 19d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 27d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 29d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 37d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 41d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 53d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [From 1x3090 to 20 DGX Sparks: my house fuses were the first bottleneck](https://reddit.com/r/LocalLLaMA/comments/1wxgm0h/from_1x3090_to_20_dgx_sparks_my_house_fuses_were/) ↑633
- [[SANITIZED — possible injection attempt]](https://reddit.com/r/LocalLLaMA/comments/1wx8ruy/metas_muse_agent_1_in_the_app_store_system_prompt/) ↑619
- [Micron CEO Says Memory Supply Will Be Much Tighter in 2027 and 2028 Than in 2026](https://reddit.com/r/LocalLLaMA/comments/1wxma3a/micron_ceo_says_memory_supply_will_be_much/) ↑424
- [Qwen3.5 arch implementation in FPGA fabric for 9B/27B INT4 models on relatively cheap eBay mining hardware](https://reddit.com/r/LocalLLaMA/comments/1wxken1/qwen35_arch_implementation_in_fpga_fabric_for/) ↑243
- [Local text to speech with Breeze is truly incredible](https://reddit.com/r/LocalLLaMA/comments/1wxd404/local_text_to_speech_with_breeze_is_truly/) ↑129

### r/singularity — top 5 new
- [Claude Opus 5.5 created this in 18 hours](https://reddit.com/r/singularity/comments/1wx73vr/claude_opus_55_created_this_in_18_hours/) ↑2220
- [Dario probably thinking "finish this sh!t I have to work on ASI"](https://reddit.com/r/singularity/comments/1wtzekf/dario_probably_thinking_finish_this_sht_i_have_to/) ↑1577
- [It's over, guys. This repo turns ONE photo into a full explorable 3D world in 5 minutes. Physics, splats, audio!](https://reddit.com/r/singularity/comments/1wx6cri/its_over_guys_this_repo_turns_one_photo_into_a/) ↑1041
- [Crab Rave: "I built a little crab robot Jumper people seemed to love and I open-souced it"](https://reddit.com/r/singularity/comments/1wx7ow5/crab_rave_i_built_a_little_crab_robot_jumper/) ↑900
- [Early warning signs are mounting that AI is already impacting the job market in NYC. This is coming fast and we are doing almost nothing about it.](https://reddit.com/r/singularity/comments/1wxhome/early_warning_signs_are_mounting_that_ai_is/) ↑525

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Migrated from 2026.9.3 to 9.8 with no issues](https://reddit.com/r/openclaw/comments/1wxkt02/migrated_from_202693_to_98_with_no_issues/) ↑13
- [Free Plaud Download & Transcription](https://reddit.com/r/openclaw/comments/1wx6brx/free_plaud_download_transcription/) ↑8
- [why can't you just have text conversations on Apple Watch with a direct connection?](https://reddit.com/r/openclaw/comments/1wxrud5/why_cant_you_just_have_text_conversations_on/) ↑4
- [What are your Openclaw tips / best practices?](https://reddit.com/r/openclaw/comments/1wwejgv/what_are_your_openclaw_tips_best_practices/) ↑4
- [Notes from moving a custom client from 2026.9.1 to 2026.9.6: the replace:true chunk, a retired config key that bricks the CLI, and strict session model picks](https://reddit.com/r/openclaw/comments/1wwmne3/notes_from_moving_a_custom_client_from_202691_to/) ↑3

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [OpenClaw v2026.9.8 is out, and this one's a fun-sized lobster 🦞

🧠 GPT-6.1 Sol support
💬 Agent replies find their way ba](https://x.com/openclaw/status/2106247624634531889)

### X — @steipete
- [bug fixes & performance improvements](https://x.com/steipete/status/2106796559400882209) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
