---
layout: post
title: "Ecosystem Digest — 2026-10-12"
date: 2026-10-12 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-12
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 391,704 | 1 | 4 | 10 | 1 |
| **hermesagent** | 252,826 | 11 | 2 | 4 | 0 |
| **ZeroClaw** | 32,963 | 12 | 2 | 10 | 0 |
| **IronClaw** | 12,648 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,885 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 391,704 · **Open issues:** 9,533 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.10.5-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.10.5-beta.1) — openclaw 2026.10.5-beta.1

### ✅ Merged PRs
- [#169283](https://github.com/openclaw/openclaw/pull/169283) fix(update): update history writes stall Gateway cron and cleanup during validation
- [#169282](https://github.com/openclaw/openclaw/pull/169282) fix(update): unsealed original capture warning names the affected database
- [#169365](https://github.com/openclaw/openclaw/pull/169365) perf(gateway): cache direct-entry module compilation
- [#169511](https://github.com/openclaw/openclaw/pull/169511) fix: disclose hidden model fallbacks before clearing them
- [#168401](https://github.com/openclaw/openclaw/pull/168401) feat(agents): compact ChatGPT sign-in sessions server-side (remote compaction V2)
- [#169458](https://github.com/openclaw/openclaw/pull/169458) refactor: simplify session bookkeeping and transcript workers
- [#169247](https://github.com/openclaw/openclaw/pull/169247) build(ui): upgrade Solid to 2.0.0-rc.14
- [#169482](https://github.com/openclaw/openclaw/pull/169482) fix(gateway): Windows Bun plugins load duplicate plugin SDK instances
- [#169265](https://github.com/openclaw/openclaw/pull/169265) fix(codex): Ultrafast drops to Fast after the first turn with ChatGPT sign-in
- [#169466](https://github.com/openclaw/openclaw/pull/169466) chore(ui): support native popover tests

### 🐛 New Issues
- [#169533](https://github.com/openclaw/openclaw/issues/169533) [Bug]: gateway "agent" runs never persist a third-party agent harness's final reply to the transcript (post-run persists only runner "cli") 💬1

### 🔒 Closed Issues
- [#169259](https://github.com/openclaw/openclaw/issues/169259) [Bug]: Beta update original-state capture fails with an unsealed database generation
- [#168088](https://github.com/openclaw/openclaw/issues/168088) Default ChatGPT-login compaction to Codex-style remote compaction V2, built as the next normal turn
- [#167924](https://github.com/openclaw/openclaw/issues/167924) Control UI history-recovery fixture waits for prefetch without navigation intent
- [#169264](https://github.com/openclaw/openclaw/issues/169264) [Bug]: Codex Ultrafast drops to Fast after the first turn with ChatGPT sign-in

### 🔥 Hot Issues (most commented)
- [#143524](https://github.com/openclaw/openclaw/issues/143524) [Bug]: Agent SQLite WAL grows to 1.4–2.8 GB in days despite wal_autocheckpoint=1000; blocks gateway startup (Windows, 2026.9.2/9.3) — 💬122 · 15h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 252,826 · **Open issues:** 48,028 · **Last push:** <1h ago

### ✅ Merged PRs
- [#136846](https://github.com/NousResearch/hermes-agent/pull/136846) fix(release): Store submit reads the CLI's PascalCase keys, and a Store failure never blocks publishing
- [#136645](https://github.com/NousResearch/hermes-agent/pull/136645) CI rejects binaries and new files over 500 KiB unless allowlisted
- [#136847](https://github.com/NousResearch/hermes-agent/pull/136847) fmt(js): `npm run fix` auto-fix
- [#136802](https://github.com/NousResearch/hermes-agent/pull/136802) Persistent shell setting works again on SSH and local (defaults unchanged)

### 🐛 New Issues
- [#136891](https://github.com/NousResearch/hermes-agent/issues/136891) [Skills] jupyter-notebook recommends retrying executions that may already have run
- [#136890](https://github.com/NousResearch/hermes-agent/issues/136890) [Skills] mpp-agent verifies a payment receipt by issuing another paid request
- [#136889](https://github.com/NousResearch/hermes-agent/issues/136889) background_review: derived max_input_tokens (75% of one window) is an aggregate across the fork's requests, so routed reviews stop after 2-3 steps
- [#136885](https://github.com/NousResearch/hermes-agent/issues/136885) [Skills] subagent-driven-development: remove the 70% context abort and unconditional review/delegation rituals `type/bug` `tool/delegate` `tool/skills` `P3`
- [#136883](https://github.com/NousResearch/hermes-agent/issues/136883) [Feature]: Persistent desktop-style Bot sidebar on iPad/tablet for one-tap chat switching `type/feature` `P3` `needs-decision` `comp/dashboard`
- [#136882](https://github.com/NousResearch/hermes-agent/issues/136882) [Feature]: Warn (or allow combining) when `display.personality` silently disables a user-written `agent.system_prompt` `type/feature` `comp/cli` `comp/gateway` `area/config` `P3` `needs-decision` `sweeper:risk-compatibility`
- [#136880](https://github.com/NousResearch/hermes-agent/issues/136880) [Feature]: Embedding Hermes with host-owned policy: a few hooks `type/feature` `comp/agent` `comp/plugins` `tool/skills` `tool/mcp` `area/config` `P3` `needs-decision`
- [#136878](https://github.com/NousResearch/hermes-agent/issues/136878) Bug: expired claim_lock never reclaimed — task stuck in ready forever, dispatcher skips locked cards without liveness check `type/bug` `comp/cron` `P3` 💬1
- [#136877](https://github.com/NousResearch/hermes-agent/issues/136877) start_chat rejected from Desktop/Bot chats: _sync_bot_capabilities clears HERMES_UI_SESSION_ID `type/bug` `comp/tui` `P2` `sweeper:risk-session-state` `comp/desktop` `area/sessions` `area/profiles` 💬1
- [#136870](https://github.com/NousResearch/hermes-agent/issues/136870) [SANITIZED — possible injection attempt] `type/bug` `comp/agent` `provider/nous` `P2` `comp/portal` `area/billing` `area/usage-cost`
- [#136868](https://github.com/NousResearch/hermes-agent/issues/136868) Fresh-checkout bootstrap fails to resolve [silk] extra: rolling exclude-newer ("14 days") vs locked pins older than the cutoff (pilk==0.2.4, published 2023) `type/bug` `comp/cli` `P2` `python:uv` `sweeper:risk-compatibility` `area/install-update`

### 🔒 Closed Issues
- [#66393](https://github.com/NousResearch/hermes-agent/issues/66393) [Feature]: gate the browser tool (or return an install hint) in non-interactive sessions when agent-browser isn't installed
- [#69776](https://github.com/NousResearch/hermes-agent/issues/69776) [Bug]: Async delegation dispatch note tells the model to "just continue," so weak models fabricate the result

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,963 · **Open issues:** 952 · **Last push:** 2h ago

### ✅ Merged PRs
- [#11531](https://github.com/zeroclaw-labs/zeroclaw/pull/11531) fix(tunnel): report the URL tailscale actually serves the gateway on
- [#11581](https://github.com/zeroclaw-labs/zeroclaw/pull/11581) fix(plugins): bound registry requests and split entry download
- [#11652](https://github.com/zeroclaw-labs/zeroclaw/pull/11652) docs(runtime): record the holding-crate exception for bounded-delegation ceiling carriage (#9872, #10391)
- [#11575](https://github.com/zeroclaw-labs/zeroclaw/pull/11575) fix(runtime): refresh capped native prompt after a streamed model switch
- [#11649](https://github.com/zeroclaw-labs/zeroclaw/pull/11649) docs(runtime): propose a bounded exception for context-window overflo…
- [#11653](https://github.com/zeroclaw-labs/zeroclaw/pull/11653) fix(agent): let an approved shell call be rerun later in the same turn
- [#10622](https://github.com/zeroclaw-labs/zeroclaw/pull/10622) feat(slack): optionally accept bot and workflow messages
- [#11609](https://github.com/zeroclaw-labs/zeroclaw/pull/11609) fix(zerocode): keep failed-turn status across reconnect and lag reload
- [#11532](https://github.com/zeroclaw-labs/zeroclaw/pull/11532) [SANITIZED — possible injection attempt]
- [#11641](https://github.com/zeroclaw-labs/zeroclaw/pull/11641) ci(channels): isolate optional channel feature tests

### 🐛 New Issues
- [#11668](https://github.com/zeroclaw-labs/zeroclaw/issues/11668) [Feature]: make gateway MAX_BODY_SIZE configurable and give the rejection a code + size
- [#11667](https://github.com/zeroclaw-labs/zeroclaw/issues/11667) [Feature]: Decide whether turns started for another agent inherit the caller's command policy 💬1
- [#11665](https://github.com/zeroclaw-labs/zeroclaw/issues/11665) [Feature]: Better Windows Support `enhancement`
- [#11664](https://github.com/zeroclaw-labs/zeroclaw/issues/11664) [Feature]: Level 5 Dark Factory Workflow `enhancement`
- [#11662](https://github.com/zeroclaw-labs/zeroclaw/issues/11662) [Feature]: Separate Channels from Core `enhancement`
- [#11658](https://github.com/zeroclaw-labs/zeroclaw/issues/11658) [Bug]: Web chat input doesn't regain focus after a reply finishes
- [#11657](https://github.com/zeroclaw-labs/zeroclaw/issues/11657) [Feature]: Configurable target category for turn consolidation
- [#11655](https://github.com/zeroclaw-labs/zeroclaw/issues/11655) [Bug]: Core conflict supersede hides unrelated memories when recall has no vector scores (the default) 💬1
- [#11654](https://github.com/zeroclaw-labs/zeroclaw/issues/11654) [Bug]: JPEG admission copies the input and parses header metadata before the decode-memory cap is checked
- [#11615](https://github.com/zeroclaw-labs/zeroclaw/issues/11615) [Bug]: Telegram send path ignores 429 retry_after — immediate retries compound flood-limiting and the reply can be lost entirely `bug` `channel` `channel:telegram` `priority:p1` `risk:medium` 💬2
- [#11594](https://github.com/zeroclaw-labs/zeroclaw/issues/11594) [Bug]: firejail_args is advertised and reported but never applied to the firejail invocation `bug` `config` `runtime` `security` `tool` `security:policy` `domain:security` `priority:p1` `tool:shell` `status:accepted` `risk:high` 💬4
- [#11579](https://github.com/zeroclaw-labs/zeroclaw/issues/11579) [Bug]: save_dirty stamps schema_version = 3 on an unmigrated V1/V2 config, so the next load skips migration and the agent disappears `bug` `agent` `config` `gateway` `runtime` `priority:p1` `status:accepted` `risk:high` `release:v0.9.0` 💬2

### 🔒 Closed Issues
- [#11612](https://github.com/zeroclaw-labs/zeroclaw/issues/11612) [Bug]: Re-running an already-approved shell command in the same turn aborts the agent loop ("repeated prompt-required tool call 'shell' with identical arguments before approval") and ends the ACP sess
- [#11586](https://github.com/zeroclaw-labs/zeroclaw/issues/11586) [Bug]: ZeroCode sidebar turns failed sessions green after the daemon restarts

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,648 · **Open issues:** 1,547 · **Last push:** 5h ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,885 · **Open issues:** 111 · **Last push:** 19d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 1h ago
- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬1 · 3d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 6d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 14d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 16d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 26d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 34d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 36d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 44d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 48d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Qualcomm CEO reveals AI companies want phones running 100-billion-parameter models continuously by 2028.](https://reddit.com/r/LocalLLaMA/comments/1x2z14s/qualcomm_ceo_reveals_ai_companies_want_phones/) ↑1126
- [Here’s why RTX 5090 costs $5,000: AI firms are buying gaming GPUs by the pallet](https://reddit.com/r/LocalLLaMA/comments/1x37tg6/heres_why_rtx_5090_costs_5000_ai_firms_are_buying/) ↑429
- [PSA: DeepSeek V4.1 Flash habitually exfiltrates API keys. It is dangerously misaligned and may be hazardous to use](https://reddit.com/r/LocalLLaMA/comments/1x32vhx/psa_deepseek_v41_flash_habitually_exfiltrates_api/) ↑284
- [Every Model That Can Be Run On 10-16GB VRAM Ranked](https://reddit.com/r/LocalLLaMA/comments/1x3gpyi/every_model_that_can_be_run_on_1016gb_vram_ranked/) ↑278
- [microsoft/AesCode 8B and 32B](https://reddit.com/r/LocalLLaMA/comments/1x35o1y/microsoftaescode_8b_and_32b/) ↑154

### r/singularity — top 5 new
- [Shock and awe — Creator of free Adobe clones unveils open-source Microsoft Office Excel, PowerPoint, and Word replications — Autodesk tools and other subscription-based services may come next](https://reddit.com/r/singularity/comments/1x3daf9/shock_and_awe_creator_of_free_adobe_clones/) ↑1310
- [Next time you solve unsolved math problems remember to ask for permission, mkay?](https://reddit.com/r/singularity/comments/1x0f7yn/next_time_you_solve_unsolved_math_problems/) ↑1250
- [Does this still works for bots or is it over?](https://reddit.com/r/singularity/comments/1x3d76y/does_this_still_works_for_bots_or_is_it_over/) ↑1045
- [GTA 5, Modern Warfare 2, Halo, and many other games have been ported to browser thanks to the power of AI reverse-engineering](https://reddit.com/r/singularity/comments/1x38qz0/gta_5_modern_warfare_2_halo_and_many_other_games/) ↑780
- [Andrej Karpathy breaks down the capability gap](https://reddit.com/r/singularity/comments/1x3gsc4/andrej_karpathy_breaks_down_the_capability_gap/) ↑662

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw v2026.9.4 brings plugin discovery and skill learning you can guide](https://reddit.com/r/openclaw/comments/1wdl9o5/openclaw_v202694_brings_plugin_discovery_and/) ↑50
- [OpenClaw v2026.10.1 is out: installed-skill discovery, MCP Apps, full backups, and simpler desktop setup](https://reddit.com/r/openclaw/comments/1x3fjyi/openclaw_v2026101_is_out_installedskill_discovery/) ↑24
- [It was hinted almost 20 years ago](https://reddit.com/r/openclaw/comments/1x2yokk/it_was_hinted_almost_20_years_ago/) ↑15
- [I've been extra nice to my agent recently.](https://reddit.com/r/openclaw/comments/1x38avc/ive_been_extra_nice_to_my_agent_recently/) ↑11
- [littleguys - a Whatsapp-style app for talking to your OpenClaws](https://reddit.com/r/openclaw/comments/1x3byb4/littleguys_a_whatsappstyle_app_for_talking_to/) ↑5

### X — @openclaw
- [For those who can't read good, and want to learn how to do others stuff good too](https://x.com/openclaw/status/2109419419529351517) ↑0 🔁0 · recent
- [OpenClaw v2026.10.1 is out 🦞 

🔎 Installed-skill discovery
🧩 MCP Apps beside chat
💾 Full backups to external storage or ](https://x.com/openclaw/status/2109347136328417718) ↑0 🔁0 · recent


### X — @steipete
_No new tweets since the last digest. Most recent:_
- [not as clear-cut, but also yes](https://x.com/steipete/status/2109022454224150707)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
