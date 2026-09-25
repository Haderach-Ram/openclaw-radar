---
layout: post
title: "Ecosystem Digest — 2026-09-25"
date: 2026-09-25 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-25
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 390,426 | 14 | 4 | 10 | 0 |
| **hermesagent** | 248,744 | 6 | 3 | 10 | 1 |
| **ZeroClaw** | 32,877 | 8 | 3 | 10 | 0 |
| **IronClaw** | 12,633 | 1 | 0 | 0 | 1 |
| **Moltis** | 2,870 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 390,426 · **Open issues:** 8,658 · **Last push:** <1h ago

### ✅ Merged PRs
- [#157776](https://github.com/openclaw/openclaw/pull/157776) fix(sessions): release PR caches when pending viewers leave
- [#157787](https://github.com/openclaw/openclaw/pull/157787) refactor(twitch): reuse setup account selection
- [#157767](https://github.com/openclaw/openclaw/pull/157767) test: skip empty task ledger resets in cron fixtures
- [#157711](https://github.com/openclaw/openclaw/pull/157711) perf: reduce gateway and state test startup
- [#157696](https://github.com/openclaw/openclaw/pull/157696) fix: preserve maintenance leases during slow heartbeat renewal
- [#156633](https://github.com/openclaw/openclaw/pull/156633) fix: keep failed update report uploads in the CLI
- [#157551](https://github.com/openclaw/openclaw/pull/157551) fix: channels add non-TTY advice names unregistered --use-env
- [#157731](https://github.com/openclaw/openclaw/pull/157731) fix: preserve rejected settings reason when opening config
- [#157652](https://github.com/openclaw/openclaw/pull/157652) fix(ci): prevent Security Review checkout retry collisions
- [#157651](https://github.com/openclaw/openclaw/pull/157651) fix(ci): recover interrupted Security Review response bodies

### 🐛 New Issues
- [#157817](https://github.com/openclaw/openclaw/issues/157817) [Windows] `exec` spawns visible PowerShell console windows (flashing) — add a hidden-window option
- [#157816](https://github.com/openclaw/openclaw/issues/157816) `openclaw` setup turn fails after an update: could not reach working inference — `prepared model runtime plugin generation was superseded`
- [#157815](https://github.com/openclaw/openclaw/issues/157815) [Bug]: OpenClaw 2026.9.6: ~138 s Gateway startup, ~1.5 GiB main-process PSS, and 20–60+ s health CLI latency in a arm64 small machine `bug`
- [#157814](https://github.com/openclaw/openclaw/issues/157814) Replies are lost when the gateway restarts mid-turn: `prepared reply dispatch runtime owner was not published for main`
- [#157813](https://github.com/openclaw/openclaw/issues/157813) `secrets` action=request fails with `credential-request prompt delivery failed` on a Telegram direct chat
- [#157812](https://github.com/openclaw/openclaw/issues/157812) Windows: auto-update fails repeatedly — managed-service-preflight inside gateway tree, snapshot path with unexpanded `$OPENCLAW_STATE_DIR`, `reconcile:abandoned` after restart
- [#157811](https://github.com/openclaw/openclaw/issues/157811) `automations` tool returns a result violating its own outputSchema (`state.scheduleErrorCount`), making update/get unusable
- [#157802](https://github.com/openclaw/openclaw/issues/157802) [Bug]: chat.send after a reconnect is rejected with "unexpected property '__controlUiReconnectResume'" for first-party app clients `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:message-loss` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬1
- [#157798](https://github.com/openclaw/openclaw/issues/157798) [Bug]: A value-identical config.apply invalidates every projected session row, stalling sessions.list `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:linked-pr-open` `clawsweeper:current-main-repro` `issue-rating: 🦀 challenger crab` `impact:other` `maturity:stable` 💬1
- [#157795](https://github.com/openclaw/openclaw/issues/157795) Update failure: runtime-verification-failed (2026.9.3) `clawsweeper:needs-info` `P0` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-release-blocker` 💬2
- [#157791](https://github.com/openclaw/openclaw/issues/157791) [Bug]: OpenClaw 2026.9.6: ~138 s Gateway startup, high steady RSS, and 20–60+ s health CLI latency in a Raspberry Pi style small machine `bug` `bug:behavior` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `issue-rating: 🦐 gold shrimp` `impact:ux-friction` 💬1
- [#157790](https://github.com/openclaw/openclaw/issues/157790) [Bug]: no supported way to make one channel tool-free — tools.deny: ["*"] hard-fails every turn, tools.allow: [] is ignored (2026.9.4) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#157788](https://github.com/openclaw/openclaw/issues/157788) Smaller channel plugins: consolidate duplicate flows and fix MMS cleanup and IPv6 origins `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#157786](https://github.com/openclaw/openclaw/issues/157786) Update failure: managed-service-preflight (2026.9.5) `clawsweeper:needs-info` `P0` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-release-blocker` 💬1

### 🔒 Closed Issues
- [#153067](https://github.com/openclaw/openclaw/issues/153067) Gateway in steady state re-copies the entire state DB every ~5 s per instance (~170 MB per read, ~5.9 TB/day of staging writes)
- [#151050](https://github.com/openclaw/openclaw/issues/151050) Update failure: unexpected-error (2026.9.4)
- [#157546](https://github.com/openclaw/openclaw/issues/157546) channels add non-TTY advice points at `--use-env`, which 13 bundled channels never register
- [#157714](https://github.com/openclaw/openclaw/issues/157714) [Bug]: Opening the configuration file removes the rejected draft reason

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 248,744 · **Open issues:** 43,382 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.9.24](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.9.24) — Hermes Agent v0.21.5 (v2026.9.24)

### ✅ Merged PRs
- [#122098](https://github.com/NousResearch/hermes-agent/pull/122098) fix(pm): name virtual workspace members by their unique key
- [#122101](https://github.com/NousResearch/hermes-agent/pull/122101) fix(release): Windows release builds no longer fail recording the executable version
- [#121823](https://github.com/NousResearch/hermes-agent/pull/121823) fix(desktop): open markdown preview links inside the app
- [#121532](https://github.com/NousResearch/hermes-agent/pull/121532) fix(desktop): settle a silent live turn and offer retry
- [#121474](https://github.com/NousResearch/hermes-agent/pull/121474) fix(desktop): route omitted-profile messaging approvals to the list server
- [#121525](https://github.com/NousResearch/hermes-agent/pull/121525) fix(desktop): Enter on a focused clarify choice reaches activateActive
- [#121563](https://github.com/NousResearch/hermes-agent/pull/121563) fix(desktop): stamp packaged app.asar and adopt a published session token
- [#121416](https://github.com/NousResearch/hermes-agent/pull/121416) fix(desktop): scope the config-record cache to the active gateway
- [#122095](https://github.com/NousResearch/hermes-agent/pull/122095) fix(desktop): isMain returns false when there is no entry script
- [#121565](https://github.com/NousResearch/hermes-agent/pull/121565) fix(desktop): defer tray hide and log main-process stalls

### 🐛 New Issues
- [#122121](https://github.com/NousResearch/hermes-agent/issues/122121) Failed plugin removal disables toolsets while leaving the plugin installed
- [#122120](https://github.com/NousResearch/hermes-agent/issues/122120) Managed uploads can overwrite concurrent files despite overwrite=false
- [#122119](https://github.com/NousResearch/hermes-agent/issues/122119) [Bug]: Anti-stall guards miss ordinary English/non-English continuations and lose the ack fallback after tool use
- [#122112](https://github.com/NousResearch/hermes-agent/issues/122112) [Bug]: pm runtime provisioning hard-fails on pip.conf-mirrored hosts — bridged UV_INDEX_URL mismatches the committed uv.lock registry (--locked) `type/bug` `comp/cli` `area/config` `P2` `python:uv` `sweeper:risk-compatibility` `area/install-update`
- [#122109](https://github.com/NousResearch/hermes-agent/issues/122109) Concurrent first-time execute_code on one remote kernel key spawns two runners and orphans one `type/bug` `backend/ssh` `backend/modal` `comp/tools` `tool/code-exec` `backend/docker` `P2` `sweeper:risk-session-state`
- [#122100](https://github.com/NousResearch/hermes-agent/issues/122100) Desktop: a media attachment renders on top of the following text block (first line of the paragraph is hidden behind the image) `type/bug` `P3` `comp/desktop`

### 🔒 Closed Issues
- [#81055](https://github.com/NousResearch/hermes-agent/issues/81055) [Bug]: A note's own table-of-contents links do nothing in the Desktop markdown preview (no heading ids, no href on #fragment links)
- [#119252](https://github.com/NousResearch/hermes-agent/issues/119252) [Bug]: Windows desktop — Hermes.exe stops responding (OS AppHangB1) after minimize-to-tray use, and the app's own logs capture nothing because every hang affordance is renderer-scoped
- [#118856](https://github.com/NousResearch/hermes-agent/issues/118856) [Bug][Desktop] WebSocket dial/teardown churn on a ~30 s cadence survives the #94769 fix (v0.21.4, Linux/Wayland, 2 connections x 4 profiles)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,877 · **Open issues:** 756 · **Last push:** <1h ago

### ✅ Merged PRs
- [#10259](https://github.com/zeroclaw-labs/zeroclaw/pull/10259) feat(security): enforce authenticated principals on RPC with native+peercred (#8289 stage 3, supersedes #8672 in part)
- [#10538](https://github.com/zeroclaw-labs/zeroclaw/pull/10538) fix(gateway): keep the agent turn running when the chat WebSocket disconnects
- [#11063](https://github.com/zeroclaw-labs/zeroclaw/pull/11063) ci(codeql): pin the Rust scan runner label and retire CI_USE_BLACKSMITH
- [#11069](https://github.com/zeroclaw-labs/zeroclaw/pull/11069) perf(ci): give colliding Rust matrix legs distinct cache keys
- [#11073](https://github.com/zeroclaw-labs/zeroclaw/pull/11073) perf(ci): run CodeQL on master pushes only when analyzed code changes
- [#11070](https://github.com/zeroclaw-labs/zeroclaw/pull/11070) perf(ci): skip Docker source builds when only the release workflow changed
- [#11064](https://github.com/zeroclaw-labs/zeroclaw/pull/11064) perf(ci): run the Windows task-owner recovery tests as a parallel job
- [#11083](https://github.com/zeroclaw-labs/zeroclaw/pull/11083) fix(gateway): drive webhook-started SOP agent steps
- [#10527](https://github.com/zeroclaw-labs/zeroclaw/pull/10527) feat(sop): rename a SOP from the web editor, and unblock the zerocode pane behind its read-only gate
- [#10834](https://github.com/zeroclaw-labs/zeroclaw/pull/10834) docs(adr): record runtime security provenance boundaries

### 🐛 New Issues
- [#11103](https://github.com/zeroclaw-labs/zeroclaw/issues/11103) feat(providers): add Cheaper Inference as a typed OpenAI-compatible provider `enhancement`
- [#11100](https://github.com/zeroclaw-labs/zeroclaw/issues/11100) [Feature]: Preserve configured provider aliases in cost-rate catalog prefill `enhancement`
- [#11097](https://github.com/zeroclaw-labs/zeroclaw/issues/11097) [Bug]: Plugin egress remedy commands do not escape apostrophes in existing grants `bug`
- [#11096](https://github.com/zeroclaw-labs/zeroclaw/issues/11096) RFC: Risk-based merge-result freshness `type:rfc`
- [#11094](https://github.com/zeroclaw-labs/zeroclaw/issues/11094) [Bug]: Apple preflight tests can fail when the retry sleep mock intercepts subprocess polling `bug`
- [#11093](https://github.com/zeroclaw-labs/zeroclaw/issues/11093) [Bug]: Stable docs promotion leaves root llms files out of sync `bug`
- [#11088](https://github.com/zeroclaw-labs/zeroclaw/issues/11088) [Docs]: Move multi-agent setup guide from Contributing to Agents `docs` `type:docs`
- [#11087](https://github.com/zeroclaw-labs/zeroclaw/issues/11087) [Bug]: Windows — after closing the window the app can be neither reopened nor quit `bug`

### 🔒 Closed Issues
- [#8559](https://github.com/zeroclaw-labs/zeroclaw/issues/8559) [Bug]: Agents stop their work when exiting the chat window in web dashboard
- [#9805](https://github.com/zeroclaw-labs/zeroclaw/issues/9805) SOP: auto-mode runs from channel/cron triggers are never executed and rot as 'running' forever
- [#9899](https://github.com/zeroclaw-labs/zeroclaw/issues/9899) [Tracker]: remove the matrix-sdk -> imbl advisory waivers (RUSTSEC-2026-0247 bitmaps, RUSTSEC-2026-0292 imbl-sized-chunks)

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,633 · **Open issues:** 1,531 · **Last push:** 13h ago

### 🚀 New Releases
- [ironclaw-v1.4.1-rc.2](https://github.com/nearai/ironclaw/releases/tag/ironclaw-v1.4.1-rc.2) — 1.4.1-rc.2 - 2026-09-24

### 🐛 New Issues
- [#8111](https://github.com/nearai/ironclaw/issues/8111) Daily ironclaw failure taxonomy — 2026-09-24

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,870 · **Open issues:** 95 · **Last push:** 2d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 2d ago
- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬3 · 6d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 9d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 17d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 19d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 27d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 31d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 43d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 46d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 49d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 2 new
- [[Features] Ebola Response](https://www.anthropic.com/features/ebola-response)
- [[Research] Project Swap](https://www.anthropic.com/research/project-swap) _2026-09-24_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Qwen-3.8-27B is good enough that I stopped using API](https://reddit.com/r/LocalLLaMA/comments/1wp0z3i/qwen3827b_is_good_enough_that_i_stopped_using_api/) ↑435
- [JEV almost dead: CLM vs JEV](https://reddit.com/r/LocalLLaMA/comments/1wouby6/jev_almost_dead_clm_vs_jev/) ↑372
- [Folks, have you purchased the Mac M5 Ultra with 256GB yet? We need serious benchmarks, because we only get YouTube clowns influencers results](https://reddit.com/r/LocalLLaMA/comments/1wovkw5/folks_have_you_purchased_the_mac_m5_ultra_with/) ↑263
- [UkisAI Swift Series / 27B, Flash Next and Bonsai 2 + GSQ-RCO / -63.4% thinking, x1.95 speed with xhigh accuracy](https://reddit.com/r/LocalLLaMA/comments/1wp6gal/ukisai_swift_series_27b_flash_next_and_bonsai_2/) ↑214
- [Qwen3.8-Flash-Next on 12GB VRAM - 65 tokens per second](https://reddit.com/r/LocalLLaMA/comments/1wp7zyb/qwen38flashnext_on_12gb_vram_65_tokens_per_second/) ↑142

### r/singularity — top 5 new
- [GPT-6 Astra conquered KSP’s rocket simulator by landing on every surface world, and even mined fuel on Moho to make the trip home](https://reddit.com/r/singularity/comments/1wp2ldw/gpt6_astra_conquered_ksps_rocket_simulator_by/) ↑686
- [Claude Opus 5.5 tops SimpleBench with its 88.4% score.](https://reddit.com/r/singularity/comments/1wp7jks/claude_opus_55_tops_simplebench_with_its_884_score/) ↑600
- [China ranks #1 for AI optimism in new poll while the US ranks amongst bottom 5 countries in pessimism](https://reddit.com/r/singularity/comments/1wp1itv/china_ranks_1_for_ai_optimism_in_new_poll_while/) ↑480
- [Opus 5.5 recreated an AI video output into a playable 90s fantasy walking simulator](https://reddit.com/r/singularity/comments/1wpgntb/opus_55_recreated_an_ai_video_output_into_a/) ↑400
- [I asked GPT-6 Astra for a video about "time". It made the whole thing in javascript, from the big bang to itself writing the code for this video](https://reddit.com/r/singularity/comments/1wpbrxa/i_asked_gpt6_astra_for_a_video_about_time_it_made/) ↑327

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw v2026.9.6 | Claude Opus 5.5, GPT-6 Sol and Luna, Grok 4.7, live meeting notes, and more](https://reddit.com/r/openclaw/comments/1woqbls/openclaw_v202696_claude_opus_55_gpt6_sol_and_luna/) ↑31
- [Stop babysitting self-hosters who know exactly what they're doing](https://reddit.com/r/openclaw/comments/1wpa99h/stop_babysitting_selfhosters_who_know_exactly/) ↑23
- [My experience launching a startup with Openclaw](https://reddit.com/r/openclaw/comments/1wp7axk/my_experience_launching_a_startup_with_openclaw/) ↑16
- [Someone tell me how OpenClaw is better or worse then Hermes](https://reddit.com/r/openclaw/comments/1wp08q8/someone_tell_me_how_openclaw_is_better_or_worse/) ↑15
- [I’ve spent the last year building an AI agent architecture. I want someone more experienced than me to tell me where I’m wrong](https://reddit.com/r/openclaw/comments/1wpfmwc/ive_spent_the_last_year_building_an_ai_agent/) ↑4

### X — @openclaw
- [OpenClaw 2026.9.6 🦞

🤖 Opus 5.5, GPT-6 Sol/Luna, Grok 4.7
🔧 Managed updates
🧵 Restart recovery
📊 30d Usage
🐙 GitHub read](https://x.com/openclaw/status/2102955928693989413) ↑0 🔁0 · recent
- [1/8 🤖 Claude Opus 5.5, GPT-6 Sol and Luna, and Grok 4.7 now have supported routes in OpenClaw. What you can select depen](https://x.com/openclaw/status/2102955962349072478) ↑0 🔁0 · recent


### X — @steipete
- [Afghanistan is more excited about AI than we are?](https://x.com/steipete/status/2103150483062014436) ↑0 🔁0 · recent
- [OpenClaw deleted around 400k LOC of its own tests without much change in code coverage. Modern models just love writing ](https://x.com/steipete/status/2103147927313199260) ↑0 🔁0 · recent
- [If you just tell the agent to clean up, it will stop far too early. Give it an ambitious goal. Try "remove 20% of the le](https://x.com/steipete/status/2103148444701610233) ↑0 🔁0 · recent
- [Astra is crushing it.](https://x.com/steipete/status/2103001790069526564) ↑0 🔁0 · recent
- [Who needs VNC when there's browsers.](https://x.com/steipete/status/2102990776439636089) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
