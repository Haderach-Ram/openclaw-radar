---
layout: post
title: "Ecosystem Digest — 2026-10-13"
date: 2026-10-13 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-13
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 391,809 | 7 | 2 | 10 | 2 |
| **hermesagent** | 253,159 | 9 | 6 | 1 | 1 |
| **ZeroClaw** | 32,966 | 9 | 4 | 8 | 0 |
| **IronClaw** | 12,650 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,888 | 1 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 391,809 · **Open issues:** 9,612 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.10.5-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.10.5-beta.2) — openclaw 2026.10.5-beta.2
- [v2026.10.2](https://github.com/openclaw/openclaw/releases/tag/v2026.10.2) — openclaw 2026.10.2

### ✅ Merged PRs
- [#141752](https://github.com/openclaw/openclaw/pull/141752) fix(googlechat): render Markdown in conversational replies
- [#170441](https://github.com/openclaw/openclaw/pull/170441) fix(node): restore retained service runtimes safely
- [#170498](https://github.com/openclaw/openclaw/pull/170498) fix(cron): retain app access when owners replace allowed tools
- [#170499](https://github.com/openclaw/openclaw/pull/170499) fix(ci): repair worker entry roots and retired exports
- [#170491](https://github.com/openclaw/openclaw/pull/170491) fix(ui): Inbox update action looks ready before its freshness check starts
- [#170504](https://github.com/openclaw/openclaw/pull/170504) refactor(searxng): remove obsolete URL fixture branch
- [#170368](https://github.com/openclaw/openclaw/pull/170368) test(acp,agents,config,gateway,ui,whatsapp): remove low-value tests (batch d073)
- [#170364](https://github.com/openclaw/openclaw/pull/170364) chore(database): correct worker-only and test-only inventory
- [#170350](https://github.com/openclaw/openclaw/pull/170350) chore(ui): refresh control ui locales
- [#170318](https://github.com/openclaw/openclaw/pull/170318) improve(boards): avoid duplicate target reads in cross-store writes

### 🐛 New Issues
- [#170525](https://github.com/openclaw/openclaw/issues/170525) [Bug]: macOS lid-close sleep expires state-owner heartbeat and forces Gateway restart on wake (2026.10.2) 💬1
- [#170522](https://github.com/openclaw/openclaw/issues/170522) [Bug]: Malformed tool call is not continued when an earlier tool in the same turn failed 💬1
- [#170503](https://github.com/openclaw/openclaw/issues/170503) [Bug]: Claude CLI auth login falsely reports unauthenticated when 3s probe times out (WSL2, 2026.10.2) `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#170501](https://github.com/openclaw/openclaw/issues/170501) [Feature]: Let plugins install refuse artifacts that differ from an operator digest `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:linked-pr-open` `impact:security` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#170496](https://github.com/openclaw/openclaw/issues/170496) Read-only state-DB snapshot copied per read; cron timer maintenance triggers it every tick (no reuse)
- [#170483](https://github.com/openclaw/openclaw/issues/170483) [Bug]: Zalo cuts message-tool sends and photo captions at 2000 characters and drops the rest `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#170474](https://github.com/openclaw/openclaw/issues/170474) [Bug]: sessions.cleanup (all agents) takes ~27s since 2026.10.1 (under 1s on 2026.9.9); `openclaw sessions cleanup --all-agents` now always hits the fixed 10s CLI wait `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#141625](https://github.com/openclaw/openclaw/issues/141625) [SANITIZED — possible injection attempt]
- [#170298](https://github.com/openclaw/openclaw/issues/170298) [Bug]: Native app access remains unavailable after successful automation updates

### 🔥 Hot Issues (most commented)
- [#143524](https://github.com/openclaw/openclaw/issues/143524) [Bug]: Agent SQLite WAL grows to 1.4–2.8 GB in days despite wal_autocheckpoint=1000; blocks gateway startup (Windows, 2026.9.2/9.3) — 💬122 · 1d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 253,159 · **Open issues:** 48,152 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.21.7](https://github.com/NousResearch/hermes-agent/releases/tag/v0.21.7) — Hermes Agent v0.21.7

### ✅ Merged PRs
- [#137539](https://github.com/NousResearch/hermes-agent/pull/137539) fmt(js): `npm run fix` auto-fix

### 🐛 New Issues
- [#137546](https://github.com/NousResearch/hermes-agent/issues/137546) [Bug]: /goal shows judge rejection in UI but omits it from the agent continuation `type/bug` `comp/cli` `P2`
- [#137545](https://github.com/NousResearch/hermes-agent/issues/137545) [Bug]: Telegram: a message sent while /stop is being acknowledged replays the /stop; the replay cancels the next turn and leaves the session permanently busy `type/bug` `comp/gateway` `platform/telegram` `P1` `sweeper:risk-session-state` `sweeper:risk-message-delivery`
- [#137544](https://github.com/NousResearch/hermes-agent/issues/137544) [Bug]: Billing Plans shows "Downgrade" on higher tiers while on the Free plan `type/bug` `P2` `comp/desktop` `area/billing` 💬2
- [#137541](https://github.com/NousResearch/hermes-agent/issues/137541) Catalog admission: enforce the 3-day release age on plugin Python deps (design question on exact pins vs core-locked packages) `type/feature` `P3` `needs-decision` `Plugin Catalog`
- [#137540](https://github.com/NousResearch/hermes-agent/issues/137540) Compaction summary is shown to the user as an assistant message on the live desktop transcript; each compaction also re-stores the full history `type/bug` `comp/agent` `comp/gateway` `P2` `sweeper:risk-session-state` `comp/desktop` `area/sessions` `area/compression`
- [#137529](https://github.com/NousResearch/hermes-agent/issues/137529) [Bug]: hermes doctor reports a setup warning for toolsets the user has explicitly disabled (image_gen) — contradicts 'hermes tools list' `type/bug` `comp/cli` `P3`
- [#137519](https://github.com/NousResearch/hermes-agent/issues/137519) [Bug]: A Desktop/TUI /loop whose prompt starts with "/" is silently discarded — the tick fires, no turn is ever injected, and self-paced backoff stretches to 15 min `type/bug` `comp/tui` `P2` `sweeper:risk-session-state`
- [#137518](https://github.com/NousResearch/hermes-agent/issues/137518) [Feature][Desktop] Let sidebar sections share height (or resize): collapsing Conversations leaves a dead gap, messaging sections keep capped internal scroll `type/feature` `P3` `comp/desktop`
- [#137516](https://github.com/NousResearch/hermes-agent/issues/137516) Startup tip and docs advertise Ctrl+X Ctrl+E for the external editor, but the binding is not implemented `type/bug` `comp/cli` `comp/tui` `P3`

### 🔒 Closed Issues
- [#110053](https://github.com/NousResearch/hermes-agent/issues/110053) Langfuse SDK plugin: placeholder API key silent failure
- [#98631](https://github.com/NousResearch/hermes-agent/issues/98631) Langfuse SDK plugin: placeholder API key silent failure
- [#95057](https://github.com/NousResearch/hermes-agent/issues/95057) Langfuse plugin: 'Failed to detach context' OTel errors (token created in a different Context)
- [#94710](https://github.com/NousResearch/hermes-agent/issues/94710) [Bug]: Langfuse plugin targets SDK v3 but setup installs latest v4
- [#89221](https://github.com/NousResearch/hermes-agent/issues/89221) Langfuse SDK plugin: placeholder API key silent failure
- [#88502](https://github.com/NousResearch/hermes-agent/issues/88502) [Feature]: Langfuse plugin — tag traces with cron vs. interactive trigger type

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,966 · **Open issues:** 966 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11635](https://github.com/zeroclaw-labs/zeroclaw/pull/11635) test(runtime): reuse immutable Docker executable fixtures
- [#11684](https://github.com/zeroclaw-labs/zeroclaw/pull/11684) docs(runtime): propose roster-bound pairing token placement exception
- [#11450](https://github.com/zeroclaw-labs/zeroclaw/pull/11450) fix(runtime): recover delegate settlements after worker exit
- [#11188](https://github.com/zeroclaw-labs/zeroclaw/pull/11188) fix(parser): preserve browser and search tool semantics
- [#11302](https://github.com/zeroclaw-labs/zeroclaw/pull/11302) feat(plugins): bind channel instances and seed their grants at install
- [#11114](https://github.com/zeroclaw-labs/zeroclaw/pull/11114) docs(agents): move multi-agent setup guide to Agents
- [#11666](https://github.com/zeroclaw-labs/zeroclaw/pull/11666) docs(runtime): propose a bounded exception for embedded tool-protocol leak rejection
- [#11678](https://github.com/zeroclaw-labs/zeroclaw/pull/11678) fix(deps): bump quinn-proto to 0.11.19 for RUSTSEC-2026-0338..0342

### 🐛 New Issues
- [#11696](https://github.com/zeroclaw-labs/zeroclaw/issues/11696) [SANITIZED — possible injection attempt] `bug` `runtime` `agent:prompt`
- [#11694](https://github.com/zeroclaw-labs/zeroclaw/issues/11694) [Bug]: ZeroCode Cost tab mixes UTC and local-day totals without saying which `bug` `zerocode`
- [#11691](https://github.com/zeroclaw-labs/zeroclaw/issues/11691) [Bug]: ZeroCode's paused-queue hint names ⌥P, which types π in macOS Terminal `bug` `zerocode`
- [#11679](https://github.com/zeroclaw-labs/zeroclaw/issues/11679) [Feature]: zerocode obtains and stores its own bearer over the mTLS plane (auth parity with the gateway) `enhancement` `gateway` `runtime` `security` `security:pairing` `domain:security` `priority:p2` `zerocode` `risk:high` `topic:identity-access`
- [#11677](https://github.com/zeroclaw-labs/zeroclaw/issues/11677) [Feature]: a SOP run resumed after an external approval has no record of the starting turn's tool authority
- [#11675](https://github.com/zeroclaw-labs/zeroclaw/issues/11675) [Bug]: ACP session store re-stamps created_at of every acp_messages and acp_tool_calls row when a trimmed transcript is replaced
- [#11668](https://github.com/zeroclaw-labs/zeroclaw/issues/11668) [Feature]: make gateway MAX_BODY_SIZE configurable and give the rejection a code + size 💬1
- [#11664](https://github.com/zeroclaw-labs/zeroclaw/issues/11664) [Feature]: Level 5 Dark Factory Workflow `enhancement` 💬2
- [#11662](https://github.com/zeroclaw-labs/zeroclaw/issues/11662) [Feature]: Separate Channels from Core `enhancement` 💬2

### 🔒 Closed Issues
- [#10331](https://github.com/zeroclaw-labs/zeroclaw/issues/10331) bug(runtime): recover terminal settlement intents abandoned by a dead worker
- [#11108](https://github.com/zeroclaw-labs/zeroclaw/issues/11108) [Bug]: Preserve browser and search tool semantics instead of rewriting calls to shell
- [#10996](https://github.com/zeroclaw-labs/zeroclaw/issues/10996) [Feature]: Seed channel instance configuration and grants during plugin installation
- [#11088](https://github.com/zeroclaw-labs/zeroclaw/issues/11088) [Docs]: Move multi-agent setup guide from Contributing to Agents

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,650 · **Open issues:** 1,548 · **Last push:** 1d ago

### 🐛 New Issues
- [#8135](https://github.com/nearai/ironclaw/issues/8135) Daily ironclaw failure taxonomy — 2026-10-12

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,888 · **Open issues:** 114 · **Last push:** 20d ago

### 🐛 New Issues
- [#1303](https://github.com/moltis-org/moltis/issues/1303) [SANITIZED — possible injection attempt]

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 18h ago
- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬1 · 4d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 7d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 15d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 17d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 27d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 35d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 37d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 45d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 49d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 2 new
- [[Research] Distillation Defenses](https://www.anthropic.com/research/distillation-defenses) _2026-10-12_
- [[Research] Self Replicating Ai](https://www.anthropic.com/research/self-replicating-ai) _2026-10-13_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Decision 3.0: open, multimodal decision models from 0.6B to 27B. Ranks #1 on both Jev Decision Index boards](https://reddit.com/r/LocalLLaMA/comments/1x3th4p/decision_30_open_multimodal_decision_models_from/) ↑510
- [It's been 2 months](https://reddit.com/r/LocalLLaMA/comments/1x4akj7/its_been_2_months/) ↑481
- [Once again anthropic doing free marketing for open weight models](https://reddit.com/r/LocalLLaMA/comments/1x4cm73/once_again_anthropic_doing_free_marketing_for/) ↑425
- [Qwen released QwenGyre - RL framework for training AI agents on extremely long complex tasks](https://reddit.com/r/LocalLLaMA/comments/1x41myz/qwen_released_qwengyre_rl_framework_for_training/) ↑421
- [openbmb/MiniCPM-V-4.7-35B-A3B](https://reddit.com/r/LocalLLaMA/comments/1x47taj/openbmbminicpmv4735ba3b/) ↑191

### r/singularity — top 5 new
- [Linus Torvalds Used AI To Make Code Decipherable & Uncovered More Bugs](https://reddit.com/r/singularity/comments/1x3yeti/linus_torvalds_used_ai_to_make_code_decipherable/) ↑955
- [Linus Torvalds Working On A Hefty Linux Kernel Improvement With Claude Code](https://reddit.com/r/singularity/comments/1x3vgi7/linus_torvalds_working_on_a_hefty_linux_kernel/) ↑685
- [What if we get Claude to Rewrite HP PRINTER firmware to let us print with 3rd party ink](https://reddit.com/r/singularity/comments/1x472ch/what_if_we_get_claude_to_rewrite_hp_printer/) ↑441
- [Introducing Muse Wonder](https://reddit.com/r/singularity/comments/1x47oxn/introducing_muse_wonder/) ↑419
- [I don’t think we’re going to see an era of abundance.](https://reddit.com/r/singularity/comments/1x3y1z4/i_dont_think_were_going_to_see_an_era_of_abundance/) ↑398

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw v2026.10.2 patch release is out: fixes for upgrades, missing replies, and long conversations](https://reddit.com/r/openclaw/comments/1x47o57/openclaw_v2026102_patch_release_is_out_fixes_for/) ↑17
- [3 weeks into OpenClaw and still struggling to build a useful personal assistant.](https://reddit.com/r/openclaw/comments/1x40o2g/3_weeks_into_openclaw_and_still_struggling_to/) ↑9
- [Updates still fragile!](https://reddit.com/r/openclaw/comments/1x3w2h7/updates_still_fragile/) ↑9
- [I gave my OpenClaw agent a face and a voice on iPhone — 3D character, lip-sync, hands-free, 20 languages (free)](https://reddit.com/r/openclaw/comments/1x3wyq9/i_gave_my_openclaw_agent_a_face_and_a_voice_on/) ↑5
- [Running openclaw for desktop application](https://reddit.com/r/openclaw/comments/1x41o5i/running_openclaw_for_desktop_application/) ↑3

### X — @openclaw
- [OpenClaw v2026.10.2 patch release is out 🦞

🔧 Upgrade and Doctor fixes
💬 Missing and duplicate reply fixes
🧠 Long-conver](https://x.com/openclaw/status/2109692710126821482) ↑0 🔁0 · recent


### X — @steipete
- [6.1 Sol ultrafast >>> 6 Astra

~ same cost but whole different game with 250 tpm](https://x.com/steipete/status/2109730774593487009) ↑0 🔁0 · recent
- [said that last year, saying it again.
vibes coding is a slur.](https://x.com/steipete/status/2109724776168300631) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
