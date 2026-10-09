---
layout: post
title: "Ecosystem Digest — 2026-10-09"
date: 2026-10-09 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-09
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 391,481 | 3 | 8 | 10 | 1 |
| **hermesagent** | 252,054 | 3 | 1 | 3 | 1 |
| **ZeroClaw** | 32,943 | 11 | 0 | 7 | 0 |
| **IronClaw** | 12,645 | 2 | 0 | 0 | 0 |
| **Moltis** | 2,887 | 0 | 1 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 391,481 · **Open issues:** 9,557 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.9.9](https://github.com/openclaw/openclaw/releases/tag/v2026.9.9) — openclaw 2026.9.9

### ✅ Merged PRs
- [#167564](https://github.com/openclaw/openclaw/pull/167564) test(update): cover lease database loss shapes reported after temp cleanup
- [#160047](https://github.com/openclaw/openclaw/pull/160047) fix(agents): stop retrying retired Ollama models as timeouts
- [#167482](https://github.com/openclaw/openclaw/pull/167482) fix: avoid false Doctor budget failures on large upgrade fixtures
- [#167244](https://github.com/openclaw/openclaw/pull/167244) fix(mattermost): stop retrying permanent API refusals
- [#167542](https://github.com/openclaw/openclaw/pull/167542) refactor(doctor): simplify migration and update recovery paths
- [#167065](https://github.com/openclaw/openclaw/pull/167065) fix(portals): unknown and unauthorized portal WebSocket upgrades hang
- [#167520](https://github.com/openclaw/openclaw/pull/167520) refactor: reduce Gateway database work for profile labels and sharing
- [#167412](https://github.com/openclaw/openclaw/pull/167412) fix(browser): reject malformed JSON bytes before filling forms
- [#167124](https://github.com/openclaw/openclaw/pull/167124) fix: agent_end hook context is missing jobId for scheduled agent runs
- [#166843](https://github.com/openclaw/openclaw/pull/166843) fix(ui): hold-to-dictate stops as soon as the mic button is released

### 🐛 New Issues
- [#167557](https://github.com/openclaw/openclaw/issues/167557) [Bug]: Deferred plugin data/settings migration never converges (Linux/npm); package recovery reports "managed handoff lease database identity changed" `P0` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-release-blocker` 💬2
- [#167545](https://github.com/openclaw/openclaw/issues/167545) [Feature]: Which interface should support device provisioning before first start? `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `impact:security` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#167543](https://github.com/openclaw/openclaw/issues/167543) [Bug]: Retained final answer replaced by incomplete-turn warning after a reasoning-only follow-up `bug` `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬2

### 🔒 Closed Issues
- [#167562](https://github.com/openclaw/openclaw/issues/167562) Update failure: candidate-doctor (2026.9.8)
- [#167565](https://github.com/openclaw/openclaw/issues/167565) package-swap validation rejects every managed update: staged journal sqlite inherits group-read bits from default umask 022 (macOS npm-global)
- [#167496](https://github.com/openclaw/openclaw/issues/167496) [Bug]: auth-profiles migration replays its own .migrated-* archive over newer live credentials; passes are not idempotent
- [#167495](https://github.com/openclaw/openclaw/issues/167495) [Bug]: Config writer can persist schema-invalid documents (legacy keys re-emitted on rewrite/shutdown-save)
- [#164113](https://github.com/openclaw/openclaw/issues/164113) [Bug]: update fails at updater-runtime-retention with FICLONE EPERM inside an unprivileged LXC container (seccomp blocks ioctl)
- [#167555](https://github.com/openclaw/openclaw/issues/167555) Memory pressure: level=critical fires continuously with no warning tier; worker-retirement churn drives slow-SQLite log volume (WSL2)
- [#167475](https://github.com/openclaw/openclaw/issues/167475) Update failure: reconcile:abandoned (2026.9.8)
- [#167540](https://github.com/openclaw/openclaw/issues/167540) Upgrade 2026.9.8 → 2026.9.9 stuck at package-swap: "Package publication recovery permissions are unsafe" (5/5 attempts, deterministic)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 252,054 · **Open issues:** 47,837 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.21.6](https://github.com/NousResearch/hermes-agent/releases/tag/v0.21.6) — Hermes Agent v0.21.6

### ✅ Merged PRs
- [#135389](https://github.com/NousResearch/hermes-agent/pull/135389) Spotify moves out of core into the official spotify plugin, existing users migrated automatically
- [#135387](https://github.com/NousResearch/hermes-agent/pull/135387) Plugin catalog: spotify (official, NousResearch)
- [#135340](https://github.com/NousResearch/hermes-agent/pull/135340) A scratch or test home can no longer rewrite the real gateway service unit (salvage #133476)

### 🐛 New Issues
- [#135405](https://github.com/NousResearch/hermes-agent/issues/135405) [Bug]: Hermes Desktop Update Failure "exit code 2" `bug`
- [#135392](https://github.com/NousResearch/hermes-agent/issues/135392) [Bug]: Fresh Nous Cloud instance enters gateway ownership restart loop after environment update `type/bug` `comp/gateway` `provider/nous` `area/auth` `P2` `needs-repro` `sweeper:risk-security-boundary` `sweeper:risk-compatibility` `comp/portal`
- [#135376](https://github.com/NousResearch/hermes-agent/issues/135376) Console personal API keys (sk-ant-usr-) misclassified as OAuth: Claude Code identity injected, requests fail with "credit balance too low" `type/bug` `duplicate` `comp/agent` `provider/anthropic` `area/auth` `P1` `sweeper:risk-security-boundary` `area/billing` 💬1

### 🔒 Closed Issues
- [#135383](https://github.com/NousResearch/hermes-agent/issues/135383) Bundled provider plugin 'solstice' fails to load: pm-runtime venv lacks httpx (floods logs)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,943 · **Open issues:** 967 · **Last push:** 1h ago

### ✅ Merged PRs
- [#11349](https://github.com/zeroclaw-labs/zeroclaw/pull/11349) test(daemon): hold the broadcast-hook locks in the RPC drain reload test
- [#11395](https://github.com/zeroclaw-labs/zeroclaw/pull/11395) test(rpc): skip provider retries in prompt-against-500 dispatch tests
- [#11380](https://github.com/zeroclaw-labs/zeroclaw/pull/11380) test(skills): make creator cache timestamps deterministic
- [#11396](https://github.com/zeroclaw-labs/zeroclaw/pull/11396) test(hardware): time the pipe-holder test from the fixture's answer
- [#11305](https://github.com/zeroclaw-labs/zeroclaw/pull/11305) docs(tools): record tool tiers and the retained core set
- [#11090](https://github.com/zeroclaw-labs/zeroclaw/pull/11090) docs(runtime): propose the runtime composition contract
- [#11469](https://github.com/zeroclaw-labs/zeroclaw/pull/11469) fix(security): recognize the null device on every host

### 🐛 New Issues
- [#11626](https://github.com/zeroclaw-labs/zeroclaw/issues/11626) [Feature]: suppress repeated plugin egress refusal records per instance and host `enhancement` `observability:log` `follow-up` `topic:plugins`
- [#11623](https://github.com/zeroclaw-labs/zeroclaw/issues/11623) [Bug]: ZeroCode drops a pending ask_user prompt without replying, so the tool times out after 600 s and the question leaves no record
- [#11620](https://github.com/zeroclaw-labs/zeroclaw/issues/11620) [Feature]: Show message times in the ZeroCode transcript
- [#11618](https://github.com/zeroclaw-labs/zeroclaw/issues/11618) [Bug]: ZeroCode drops a queued message when the daemon refuses it as SESSION_BUSY `bug` `zerocode`
- [#11615](https://github.com/zeroclaw-labs/zeroclaw/issues/11615) [Bug]: Telegram send path ignores 429 retry_after — immediate retries compound flood-limiting and the reply can be lost entirely
- [#11614](https://github.com/zeroclaw-labs/zeroclaw/issues/11614) [Bug]: map_key_sections leaks schema paths on every call, growing daemon memory
- [#11613](https://github.com/zeroclaw-labs/zeroclaw/issues/11613) Cost ledger drops the provider's `total_tokens`, so models with hidden reasoning tokens (e.g. Gemini via an OpenAI-compatible provider) are under-counted
- [#11612](https://github.com/zeroclaw-labs/zeroclaw/issues/11612) [Bug]: Re-running an already-approved shell command in the same turn aborts the agent loop ("repeated prompt-required tool call 'shell' with identical arguments before approval") and ends the ACP sess
- [#11594](https://github.com/zeroclaw-labs/zeroclaw/issues/11594) [Bug]: firejail_args is advertised and reported but never applied to the firejail invocation `bug` `config` `runtime` `security` `tool` `security:policy` `domain:security` `priority:p1` `tool:shell` `status:accepted` `risk:high` 💬3
- [#11586](https://github.com/zeroclaw-labs/zeroclaw/issues/11586) [Bug]: ZeroCode sidebar turns failed sessions green after the daemon restarts `bug` `priority:p3` `zerocode` `risk:low` 💬3
- [#11545](https://github.com/zeroclaw-labs/zeroclaw/issues/11545) [Task]: remove obsolete StreamErrorWithUsage after image recovery lands `agent` `provider` `runtime` `priority:p2` `status:in-progress` `status:accepted` `follow-up` `risk:medium` `type:refactor` `topic:agent-loop` 💬2

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,645 · **Open issues:** 1,547 · **Last push:** 1d ago

### 🐛 New Issues
- [#8130](https://github.com/nearai/ironclaw/issues/8130) Proposal: optional Sendblue iMessage/SMS extension with host-owned credentials
- [#8129](https://github.com/nearai/ironclaw/issues/8129) Daily ironclaw failure taxonomy — 2026-10-08

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,887 · **Open issues:** 106 · **Last push:** 16d ago

### 🔒 Closed Issues
- [#1177](https://github.com/moltis-org/moltis/issues/1177) [SANITIZED — possible injection attempt]

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬1 · 9h ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 3d ago
- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 5d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 11d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 13d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 23d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 31d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 33d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 41d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 45d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 5 new
- [[News] 2026 Usage Policy Update](https://www.anthropic.com/news/2026-usage-policy-update) _2026-10-08_
- [[News] Anthropic Cyber Mission](https://www.anthropic.com/news/anthropic-cyber-mission) _2026-10-08_
- [[News] Genesis Mission Commitment](https://www.anthropic.com/news/genesis-mission-commitment) _2026-10-08_
- [[Research] Launching Opt In Vuln Finding Service For Open Source](https://www.anthropic.com/research/launching-opt-in-vuln-finding-service-for-open-source) _2026-10-08_
- [[Research] The Missing Map Of The Sky](https://www.anthropic.com/research/the-missing-map-of-the-sky) _2026-10-08_

### OpenAI — 3 new
- [[Index] Oracle](https://openai.com/index/oracle/) _2026-10-08_
- [[Index] Legalon Halves Codex Costs](https://openai.com/index/legalon-halves-codex-costs/) _2026-10-08_
- [[Index] Disrupting Ai Enabled False Front Operations](https://openai.com/index/disrupting-ai-enabled-false-front-operations/) _2026-10-09_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Last week some of South Korea's biggest banks were hit by a cyberattack. We now know the entire hack may have been done by a single person. He used a combined stack of an open-source AI penetration to](https://reddit.com/r/LocalLLaMA/comments/1x0n4pt/last_week_some_of_south_koreas_biggest_banks_were/) ↑791
- [Saluki 27B: "96% of Qwen 3.8’s performance at ~1/7 the size"](https://reddit.com/r/LocalLLaMA/comments/1x0mn7x/saluki_27b_96_of_qwen_38s_performance_at_17_the/) ↑273
- [Strata rewrote their Github history to wipe evidence of Claude-authoring](https://reddit.com/r/LocalLLaMA/comments/1x15a8w/strata_rewrote_their_github_history_to_wipe/) ↑247
- [$2800 rig with 8x Radeon Pro V620 (256 GB VRAM) + custom vLLM fork = Qwen3.8-Flash-Next at 60 to 100 t/s decode and 3000+ t/s prefill](https://reddit.com/r/LocalLLaMA/comments/1x0wnz1/2800_rig_with_8x_radeon_pro_v620_256_gb_vram/) ↑241
- [jevman: AI decision models play Pac-Man](https://reddit.com/r/LocalLLaMA/comments/1x0sm1b/jevman_ai_decision_models_play_pacman/) ↑197

### r/singularity — top 5 new
- [Glad we’re focusing on the important things](https://reddit.com/r/singularity/comments/1x0xkzm/glad_were_focusing_on_the_important_things/) ↑3170
- [Starting November 12th, 2026, abusive or cruel behavior towards Claude will be a violation of Anthropic's Usage Policy](https://reddit.com/r/singularity/comments/1x0x0o8/starting_november_12th_2026_abusive_or_cruel/) ↑1010
- [Mathematicians spent 40 years telling taxpayers that math matters because it benefits humanity. Now that AI is doing the math, suddenly it's about mathematicians.](https://reddit.com/r/singularity/comments/1x0q2ho/mathematicians_spent_40_years_telling_taxpayers/) ↑505
- [Tom was the first layoff due to AI](https://reddit.com/r/singularity/comments/1x0ypnz/tom_was_the_first_layoff_due_to_ai/) ↑421
- [Art.](https://reddit.com/r/singularity/comments/1x0xkcm/art/) ↑404

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw v2026.9.9 patch release is out: GPT-6.1 Sol, Haiku 5.5, and fixes for updates, replies, and scheduled jobs](https://reddit.com/r/openclaw/comments/1x0vt3s/openclaw_v202699_patch_release_is_out_gpt61_sol/) ↑32
- [Update 9.9 really worked](https://reddit.com/r/openclaw/comments/1x142gb/update_99_really_worked/) ↑10

### X — @openclaw
- [Just keep putting one claw in front of the other](https://x.com/openclaw/status/2108377842648330315) ↑0 🔁0 · recent
- [OpenClaw v2026.9.9 patch release is out 🦞 

🧠 GPT-6.1 Sol in Codex + Claude Haiku 5.5
🔧 Better failed-update recovery
💬 ](https://x.com/openclaw/status/2108232507649089799) ↑0 🔁0 · recent


### X — @steipete
- [WE GOT IT! .claw incoming!](https://x.com/steipete/status/2108374513931165759) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
