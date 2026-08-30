---
layout: post
title: "Ecosystem Digest — 2026-08-30"
date: 2026-08-30 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-08-30
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 388,018 | 9 | 1 | 10 | 0 |
| **hermesagent** | 238,153 | 4 | 5 | 10 | 0 |
| **ZeroClaw** | 32,675 | 5 | 3 | 10 | 0 |
| **IronClaw** | 12,602 | 2 | 1 | 1 | 0 |
| **Moltis** | 2,841 | 1 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 388,018 · **Open issues:** 5,745 · **Last push:** <1h ago

### ✅ Merged PRs
- [#132975](https://github.com/openclaw/openclaw/pull/132975) test: verify automatic migration during stable upgrades
- [#132995](https://github.com/openclaw/openclaw/pull/132995) improve(test): speed up Teams parent-context tests
- [#132986](https://github.com/openclaw/openclaw/pull/132986) refactor: keep internal wakes out of message channels
- [#132964](https://github.com/openclaw/openclaw/pull/132964) fix(android): keep offline history current after reconnect
- [#132990](https://github.com/openclaw/openclaw/pull/132990) perf(web): reuse published config cache keys
- [#132980](https://github.com/openclaw/openclaw/pull/132980) chore: update pnpm to 12.1.0
- [#132987](https://github.com/openclaw/openclaw/pull/132987) improve(test): reduce sandbox fixture startup work
- [#132988](https://github.com/openclaw/openclaw/pull/132988) test: avoid cold CLI fixture catalog discovery
- [#132981](https://github.com/openclaw/openclaw/pull/132981) perf(time): reuse explicit timezone formatters
- [#132985](https://github.com/openclaw/openclaw/pull/132985) test(qa): observe lease heartbeat event order

### 🐛 New Issues
- [#133004](https://github.com/openclaw/openclaw/issues/133004) [Bug]: agent JSON failures discard Gateway run IDs `bug` `maintainer`
- [#132996](https://github.com/openclaw/openclaw/issues/132996) [Bug]: extractShellWrapperInlineCommand drops an explicit empty -c payload `bug` `bug:behavior` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` 💬1
- [#132994](https://github.com/openclaw/openclaw/issues/132994) [Bug]: Realtime browser smoke succeeds with a failed media connection `bug` `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#132993](https://github.com/openclaw/openclaw/issues/132993) [Bug]: Closed browser Talk sessions can still admit provider delegations `bug` `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#132992](https://github.com/openclaw/openclaw/issues/132992) [Bug]: Realtime phone bridge receives no carrier audio format `bug` `maintainer` `P1` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#132984](https://github.com/openclaw/openclaw/issues/132984) [Bug]: Model Setup activation strands auth status and chat recovery `bug` `maintainer` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#132979](https://github.com/openclaw/openclaw/issues/132979) Doctor mistakes main-agent auth order for unfinished shared-auth relocation `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` `maturity:stable` 💬1
- [#132978](https://github.com/openclaw/openclaw/issues/132978) [Bug]: doctor reports every OpenRouter model as "not in the local model catalog" `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬3
- [#132969](https://github.com/openclaw/openclaw/issues/132969) [Bug]: Attributed p and div tags lose block boundaries during plain-text sanitization `bug` `no-stale` `bug:behavior` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬2

### 🔒 Closed Issues
- [#132963](https://github.com/openclaw/openclaw/issues/132963) [Bug]: Android offline history can revert after a delayed reconnect

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 238,153 · **Open issues:** 37,456 · **Last push:** <1h ago

### ✅ Merged PRs
- [#98271](https://github.com/NousResearch/hermes-agent/pull/98271) fix(cron): Desktop's advertised natural schedules now parse (#51975, salvage #51598 #52504)
- [#98280](https://github.com/NousResearch/hermes-agent/pull/98280) fix(telegram): pinned skill commands survive the menu cap (salvage #82516)
- [#98272](https://github.com/NousResearch/hermes-agent/pull/98272) feat: /plan survives the platform command-menu caps as a built-in command (closes #67264, #36821, salvage #67292)
- [#98266](https://github.com/NousResearch/hermes-agent/pull/98266) docs(computer-use): browser-route and grant references match the shipped tool (salvage #96156)
- [#98270](https://github.com/NousResearch/hermes-agent/pull/98270) [SANITIZED — possible injection attempt]
- [#98268](https://github.com/NousResearch/hermes-agent/pull/98268) fix(runtime): provider switch, fallback, and recovery keep request settings in sync (#75091, salvage #75139 #60062)
- [#98277](https://github.com/NousResearch/hermes-agent/pull/98277) fix(gateway): custom-provider extra_body survives gateway turns and /model switches (#54922, salvage #39429 #52432 #53765)
- [#98258](https://github.com/NousResearch/hermes-agent/pull/98258) fix(cron): scheduled jobs no longer lose custom-provider request settings (salvage #56876)
- [#98282](https://github.com/NousResearch/hermes-agent/pull/98282) feat(tui): status rule shows cache-hit %, latency, and t/s with shared field toggles (extends #98250)
- [#98267](https://github.com/NousResearch/hermes-agent/pull/98267) Qwen Cloud picker gains qwen3.8-max + 4 more missing models (salvage #87808)

### 🐛 New Issues
- [#98273](https://github.com/NousResearch/hermes-agent/issues/98273) [Bug]: Desktop terminal viewport is blank while xterm buffer still contains output on Windows `type/bug` `tool/terminal` `P2` `needs-repro` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows`
- [#98255](https://github.com/NousResearch/hermes-agent/issues/98255) False truncation-continuation loop: _has_natural_response_ending rejects every unpunctuated reply (esp. chat-style agents), and misses dingbat emoji `type/bug` `comp/agent` `provider/ollama` `P2` `sweeper:risk-session-state`
- [#98243](https://github.com/NousResearch/hermes-agent/issues/98243) Desktop model picker omits models present in the Ollama Cloud cache (e.g. deepseek-v4-flash:0731) `type/bug` `provider/ollama` `P2` `comp/desktop`
- [#98242](https://github.com/NousResearch/hermes-agent/issues/98242) Desktop: re-adding a remote gateway flashes 'Signed in' and skips login — connection still fails `type/bug` `area/auth` `area/config` `P2` `sweeper:risk-compatibility` `comp/desktop`

### 🔒 Closed Issues
- [#51975](https://github.com/NousResearch/hermes-agent/issues/51975) fix(cron): Desktop advertises natural schedules that parse_schedule rejects
- [#75091](https://github.com/NousResearch/hermes-agent/issues/75091) [Bug]: provider-scoped `extra_body` from the primary is not re-resolved on failover and leaks onto the fallback provider
- [#54922](https://github.com/NousResearch/hermes-agent/issues/54922) [Bug]: custom_providers[].extra_body silently dropped on gateway/messaging paths (CLI works)
- [#67264](https://github.com/NousResearch/hermes-agent/issues/67264) [Feature]: Add /plan Command to the Hermes CLI
- [#36821](https://github.com/NousResearch/hermes-agent/issues/36821) Feature: Add /plan slash command to view current todo list

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,675 · **Open issues:** 795 · **Last push:** <1h ago

### ✅ Merged PRs
- [#10445](https://github.com/zeroclaw-labs/zeroclaw/pull/10445) fix(runtime): convert missed test call sites to ScopedToolRegistry
- [#10428](https://github.com/zeroclaw-labs/zeroclaw/pull/10428) fix(deps): update chacha20 to 0.10.2
- [#10431](https://github.com/zeroclaw-labs/zeroclaw/pull/10431) fix(channels): forward transcription language hints
- [#10098](https://github.com/zeroclaw-labs/zeroclaw/pull/10098) fix(security): grant Landlock access to DNS and TLS configuration
- [#9319](https://github.com/zeroclaw-labs/zeroclaw/pull/9319) refactor(runtime): seal the engine tool registry as ScopedToolRegistry
- [#9935](https://github.com/zeroclaw-labs/zeroclaw/pull/9935) feat(vi): preserve unknown constraint types and read the strictness mode
- [#10256](https://github.com/zeroclaw-labs/zeroclaw/pull/10256) fix(gateway): redact duplicate idempotency keys from logs
- [#10309](https://github.com/zeroclaw-labs/zeroclaw/pull/10309) chore(skillforge): remove the orphaned SkillForge engine
- [#10314](https://github.com/zeroclaw-labs/zeroclaw/pull/10314) fix(providers): bound the successful /models response body
- [#10399](https://github.com/zeroclaw-labs/zeroclaw/pull/10399) fix(ci): typecheck generated dashboard contract

### 🐛 New Issues
- [#10447](https://github.com/zeroclaw-labs/zeroclaw/issues/10447) ci: Advisory scan failed — 2026-08-29 `security` `risk:high`
- [#10437](https://github.com/zeroclaw-labs/zeroclaw/issues/10437) [Bug]: ZeroCode inserts SGR mouse-wheel reports into the composer while scrolling `bug` `priority:p2` `status:in-progress` `risk:medium` `zerocode`
- [#10436](https://github.com/zeroclaw-labs/zeroclaw/issues/10436) [Bug]: Native OpenRouter streaming uses a total request timeout and cuts off active responses `bug` `provider` `provider:openrouter` `priority:p2` `risk:medium`
- [#10432](https://github.com/zeroclaw-labs/zeroclaw/issues/10432) [Bug]: Mark ElevenLabs TTS API key header as sensitive `bug` `channel` `domain:security` `priority:p2` `status:accepted` `follow-up` `risk:high` 💬1
- [#10419](https://github.com/zeroclaw-labs/zeroclaw/issues/10419) [Feature]: Stream agent-loop tokens from POST /webhook (SSE) `enhancement` `gateway` `runtime` `priority:p2` `risk:high` 💬3

### 🔒 Closed Issues
- [#10427](https://github.com/zeroclaw-labs/zeroclaw/issues/10427) ci: Advisory scan failed — 2026-08-28
- [#10429](https://github.com/zeroclaw-labs/zeroclaw/issues/10429) [Bug]: Deepgram and OpenAI transcription providers silently drop the configured language hint — non-English voice notes return empty transcripts and are skipped
- [#8309](https://github.com/zeroclaw-labs/zeroclaw/issues/8309) [Task]: Remove orphaned SkillForge engine while preserving manifest provenance compatibility

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,602 · **Open issues:** 1,480 · **Last push:** 21h ago

### ✅ Merged PRs
- [#7899](https://github.com/nearai/ironclaw/pull/7899) feat(notifications): publish automation pre-run failures

### 🐛 New Issues
- [#7824](https://github.com/nearai/ironclaw/issues/7824) Context projection: Pi-style compaction barrier, structured summaries, overflow recovery 💬5
- [#7770](https://github.com/nearai/ironclaw/issues/7770) Epic: hook the agent lifecycle — after-turn, before-turn, compaction, and tool-result seams (phased) `enhancement` `epic` 💬4

### 🔒 Closed Issues
- [#7873](https://github.com/nearai/ironclaw/issues/7873) Publish automation pre-run failure notifications

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,841 · **Open issues:** 82 · **Last push:** 2d ago

### 🐛 New Issues
- [#1246](https://github.com/moltis-org/moltis/issues/1246) [Bug]: can't run on sandbox after a node is added `bug`

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 1d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 1d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 5d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 17d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 20d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 23d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 25d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 27d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 29d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 29d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Tencent compressed Hy4-preview from 1.5TB to about 200GB GGUF and kept about 98% performance.](https://reddit.com/r/LocalLLaMA/comments/1w1o324/tencent_compressed_hy4preview_from_15tb_to_about/) ↑682
- [I always wonder how much more speed and/or context they'd be getting..](https://reddit.com/r/LocalLLaMA/comments/1w1gec7/i_always_wonder_how_much_more_speed_andor_context/) ↑533
- [Terminal Bench 4.0 just dropped, GLM-5.3 is at the same level as Fable 5, accounting for margin of error](https://reddit.com/r/LocalLLaMA/comments/1w1fpxi/terminal_bench_40_just_dropped_glm53_is_at_the/) ↑500
- [Qwen 3.8 27B at 50 tok/s with 100k Context on a 16GB GPU! (beellama.cpp)](https://reddit.com/r/LocalLLaMA/comments/1w1lq7u/qwen_38_27b_at_50_toks_with_100k_context_on_a/) ↑466
- [Saved my fiances phone with qwen 3.8 27b](https://reddit.com/r/LocalLLaMA/comments/1w1cbb0/saved_my_fiances_phone_with_qwen_38_27b/) ↑319

### r/singularity — top 5 new
- [Delivery robots using humans to cross the street](https://reddit.com/r/singularity/comments/1w1fbvc/delivery_robots_using_humans_to_cross_the_street/) ↑1374
- [An unusual parade was held in Kyiv. It featured ground-based robotic systems, maritime drones, and aerial drones](https://reddit.com/r/singularity/comments/1vx443u/an_unusual_parade_was_held_in_kyiv_it_featured/) ↑1099
- [Apparently you can get Minimax H3 Max to run faster than real time, someone made a Rick and Morty interdimensional cable stream (but it keeps getting taken down)](https://reddit.com/r/singularity/comments/1w1lddy/apparently_you_can_get_minimax_h3_max_to_run/) ↑824
- [A startup found a drug to make your blood young. People close to the company are already taking the drug weekly.  Benefits include improved vision in a 64-year-old female, longer landscaping sessions ](https://reddit.com/r/singularity/comments/1w1e3h5/a_startup_found_a_drug_to_make_your_blood_young/) ↑658
- [Our decision on Cursor following its acquisition by SpaceX](https://reddit.com/r/singularity/comments/1w1a5li/our_decision_on_cursor_following_its_acquisition/) ↑537

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Longest running tasks with openclaw ?](https://reddit.com/r/openclaw/comments/1w1c2zm/longest_running_tasks_with_openclaw/) ↑4
- [OpenClaw browser control](https://reddit.com/r/openclaw/comments/1w1s156/openclaw_browser_control/) ↑2

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
_No new tweets in the last 7 days._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
