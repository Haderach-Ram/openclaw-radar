---
layout: post
title: "Ecosystem Digest — 2026-10-01"
date: 2026-10-01 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-01
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 390,998 | 4 | 4 | 10 | 1 |
| **hermesagent** | 250,364 | 5 | 4 | 6 | 0 |
| **ZeroClaw** | 32,921 | 8 | 5 | 8 | 0 |
| **IronClaw** | 12,638 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,880 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 390,998 · **Open issues:** 9,197 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.9.7](https://github.com/openclaw/openclaw/releases/tag/v2026.9.7) — openclaw 2026.9.7

### ✅ Merged PRs
- [#162273](https://github.com/openclaw/openclaw/pull/162273) refactor(channels): reuse Telegram draft admission and reset flow
- [#162264](https://github.com/openclaw/openclaw/pull/162264) test(telegram): pin fragment debounce clock while holding gap timers
- [#159873](https://github.com/openclaw/openclaw/pull/159873) fix(cron): prevent duplicate one-shot delivery after restart
- [#162231](https://github.com/openclaw/openclaw/pull/162231) fix(update): recover from transient Windows package backup locks
- [#162261](https://github.com/openclaw/openclaw/pull/162261) fix(test): fake-timer drains abort after remote skills tests leak file watchers
- [#162250](https://github.com/openclaw/openclaw/pull/162250) fix(ui): Control UI e2e draft-editing and shortcut-tooltip tests fail on macOS hosts
- [#162265](https://github.com/openclaw/openclaw/pull/162265) chore(i18n): refresh native locales
- [#160167](https://github.com/openclaw/openclaw/pull/160167) fix(update): refuse automatic restore after unattributed Doctor-time database writes
- [#162212](https://github.com/openclaw/openclaw/pull/162212) fix(sessions): Gateway shutdown waits on throwaway session maintenance workers
- [#162233](https://github.com/openclaw/openclaw/pull/162233) fix(crabbox): macOS cloud workers reject their own live node on CPU-starved hosts

### 🐛 New Issues
- [#162281](https://github.com/openclaw/openclaw/issues/162281) [Bug]: 2026.9.6 auto-engages Code Mode for Anthropic models on upgrade; nested shell exec returns "running", doubling turns and saturating the Gateway `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#162276](https://github.com/openclaw/openclaw/issues/162276) 2026.9.7: every agent turn fails with WorkerTaskError: DataCloneError (all channels) `impact:message-loss` `P0` `impact:ux-release-blocker` 💬1
- [#162267](https://github.com/openclaw/openclaw/issues/162267) Terminal sub-agent runs with suspended delivery keep ancestors counted as active for 7 days (maxChildrenPerAgent slot leak) `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬2
- [#162259](https://github.com/openclaw/openclaw/issues/162259) [Bug]: 2026.9.7 Docker activation conflicts with OPENCLAW_CONFIG_READONLY `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `impact:session-state` `impact:crash-loop` `P0` `issue-rating: 🦞 diamond lobster` `impact:ux-release-blocker` 💬1

### 🔒 Closed Issues
- [#162243](https://github.com/openclaw/openclaw/issues/162243) [Bug]:
- [#162217](https://github.com/openclaw/openclaw/issues/162217) Codex harness: message(final: false) progress send drops the final answer in automatic source-reply delivery
- [#161828](https://github.com/openclaw/openclaw/issues/161828) [Bug]: Windows chat.send/heartbeat turns still fail with DataCloneError via nested input.request.env Proxy (session-store-target path) — beyond the top-level readExactEntries fix in #161654
- [#162242](https://github.com/openclaw/openclaw/issues/162242) WebChat turns fail with WorkerTaskError: DataCloneError in worker task input (2026.9.7)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 250,364 · **Open issues:** 47,750 · **Last push:** <1h ago

### ✅ Merged PRs
- [#129322](https://github.com/NousResearch/hermes-agent/pull/129322) fix: prevent global-flag regex backtracking in the lifecycle guard and approval rules
- [#128957](https://github.com/NousResearch/hermes-agent/pull/128957) [SANITIZED — possible injection attempt]
- [#129748](https://github.com/NousResearch/hermes-agent/pull/129748) fix(cron): surface acknowledged worker failures and release stale claims
- [#129747](https://github.com/NousResearch/hermes-agent/pull/129747) fix(gateway): authored platforms.<plat>.extra wins over the top-level platform block (salvage #118598)
- [#129727](https://github.com/NousResearch/hermes-agent/pull/129727) fmt(js): `npm run fix` auto-fix
- [#126535](https://github.com/NousResearch/hermes-agent/pull/126535) feat(desktop): star models into a Favorites section of the model picker

### 🐛 New Issues
- [#129888](https://github.com/NousResearch/hermes-agent/issues/129888) [Bug]: Deleting or reading UTF-16 files fails for filenames containing non-BMP characters
- [#129886](https://github.com/NousResearch/hermes-agent/issues/129886) [Bug]: Routed restart confirmation selects the runtime bot instead of the receiving bot
- [#129884](https://github.com/NousResearch/hermes-agent/issues/129884) [Bug]: One Telegram bot’s restart marker suppresses another bot’s fresh restart
- [#129880](https://github.com/NousResearch/hermes-agent/issues/129880) [Bug]: skill_view returns an unchanged stub for a different same-named skill before loading it
- [#129878](https://github.com/NousResearch/hermes-agent/issues/129878) [Bug]: Gemini native streaming silently accepts embedded API errors as successful replies

### 🔒 Closed Issues
- [#95529](https://github.com/NousResearch/hermes-agent/issues/95529) Plugin-registered toolsets falsely warned as 'Unknown toolsets' — cli.py validation runs before plugin discovery
- [#129281](https://github.com/NousResearch/hermes-agent/issues/129281) cron/lifecycle_guard: catastrophic backtracking in _PROFILE_FLAG_LIFECYCLE_PATTERN freezes the entire gateway process
- [#129813](https://github.com/NousResearch/hermes-agent/issues/129813) [Feature]: User-configurable URL scheme allowlist for desktop links (obsidian:// etc.)
- [#46260](https://github.com/NousResearch/hermes-agent/issues/46260) [Bug]: INSTALL DIDN'T FINISH. Hermes installer fails at "desktop" stage — npm install exit code 1 on Windows 10

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,921 · **Open issues:** 778 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11293](https://github.com/zeroclaw-labs/zeroclaw/pull/11293) fix(ci): ignore unread labels in the PR risk report's stale-metadata check
- [#11284](https://github.com/zeroclaw-labs/zeroclaw/pull/11284) docs(book): correct stale plugin name-conflict and lean-build guidance
- [#11290](https://github.com/zeroclaw-labs/zeroclaw/pull/11290) fix(zerocode): preserve undo history when adding chat context
- [#11287](https://github.com/zeroclaw-labs/zeroclaw/pull/11287) fix(cost): count a revisited alias's spend once in delegation-chain ceilings
- [#11045](https://github.com/zeroclaw-labs/zeroclaw/pull/11045) feat(runtime): persist peer-agent inbox turns
- [#10246](https://github.com/zeroclaw-labs/zeroclaw/pull/10246) fix(rpc): fence remote local-capability session resumes
- [#10621](https://github.com/zeroclaw-labs/zeroclaw/pull/10621) feat(runtime): coordinate agent lifecycle mutations
- [#11171](https://github.com/zeroclaw-labs/zeroclaw/pull/11171) feat(rpc): bound the local transport and add chunked uploads

### 🐛 New Issues
- [#11336](https://github.com/zeroclaw-labs/zeroclaw/issues/11336) [Bug]: `plugin info` and `plugin list --verify` report `[loads]` for a plugin the runtime refuses to register (configured values without a `config_schema`) `bug`
- [#11335](https://github.com/zeroclaw-labs/zeroclaw/issues/11335) [Bug]: CLI approval prompt with no terminal and stdin at EOF reports the runtime's fail-closed denial as `Denied by user` `bug`
- [#11333](https://github.com/zeroclaw-labs/zeroclaw/issues/11333) [Bug]: Skill review tools can't see skills assigned through skill_bundles
- [#11332](https://github.com/zeroclaw-labs/zeroclaw/issues/11332) [Bug]: Skill review and skill creation never run for channel, webhook, or gateway (web UI) turns
- [#11327](https://github.com/zeroclaw-labs/zeroclaw/issues/11327) [Bug]: plugin tool name gate only sees tools registered before plugins, so a plugin can pre-empt tool_search, MCP, peripheral, and skill tools `bug` `tool` `runtime:wasm` `topic:plugins`
- [#11325](https://github.com/zeroclaw-labs/zeroclaw/issues/11325) [Feature]: verify the named-pipe server so CLI authorization edits apply live on Windows `enhancement` `domain:security` `follow-up` `cli` `topic:identity-access`
- [#11324](https://github.com/zeroclaw-labs/zeroclaw/issues/11324) [Feature]: verify the daemon's identity in call_local and share one CLI daemon client `enhancement` `runtime` `domain:security` `follow-up` `cli` `topic:identity-access`
- [#11323](https://github.com/zeroclaw-labs/zeroclaw/issues/11323) [Feature]: decide whether config set should save an authorization edit the daemon refused `enhancement` `domain:security` `follow-up` `cli` `topic:identity-access`

### 🔒 Closed Issues
- [#10975](https://github.com/zeroclaw-labs/zeroclaw/issues/10975) WhatsApp Web (channel): inbound images not downloaded - agent receives literal "[Image]" text, vision unusable
- [#10230](https://github.com/zeroclaw-labs/zeroclaw/issues/10230) [Bug]: Daemon startup or reload can overflow during agent initialization
- [#10366](https://github.com/zeroclaw-labs/zeroclaw/issues/10366) RFC: Clarify PR review evidence, freshness warnings, and author-action boundaries
- [#10165](https://github.com/zeroclaw-labs/zeroclaw/issues/10165) [SANITIZED — possible injection attempt]
- [#10249](https://github.com/zeroclaw-labs/zeroclaw/issues/10249) [Bug]: Duplicate webhook handling logs raw caller-controlled idempotency keys

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,638 · **Open issues:** 1,537 · **Last push:** 23h ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,880 · **Open issues:** 100 · **Last push:** 8d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 3d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 4d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 5d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 15d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 23d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 25d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 33d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 37d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 49d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 52d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Research] What Work Can Robots Do](https://www.anthropic.com/research/what-work-can-robots-do) _2026-09-30_

### OpenAI — 1 new
- [[Index] Helping Small Businesses Put Ai To Work](https://openai.com/index/helping-small-businesses-put-ai-to-work/) _2026-09-30_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [We just open-sourced the world's fastest WebGPU kernels for local AI on Hugging Face](https://reddit.com/r/LocalLLaMA/comments/1wu8tpg/we_just_opensourced_the_worlds_fastest_webgpu/) ↑328
- [add GLM-5.3-Flash (GLM5-Next) support by timkhronos · Pull Request #27773 · ggml-org/llama.cpp](https://reddit.com/r/LocalLLaMA/comments/1wu0bdf/add_glm53flash_glm5next_support_by_timkhronos/) ↑195
- [Oído: speech recognition that beats Whisper-tiny, running on a $5 microcontroller (open source)](https://reddit.com/r/LocalLLaMA/comments/1wu2jjy/oído_speech_recognition_that_beats_whispertiny/) ↑169
- [Preorder for new AMD Ryzen™ AI Max 400 Series 192GB from framework just started](https://reddit.com/r/LocalLLaMA/comments/1wue339/preorder_for_new_amd_ryzen_ai_max_400_series/) ↑102
- [Least to most expensive (Somewhat modern) GPU's with 32gb of vram (Under $1600) Based on ebay listings](https://reddit.com/r/LocalLLaMA/comments/1wuk9so/least_to_most_expensive_somewhat_modern_gpus_with/) ↑69

### r/singularity — top 2 new
- [Gemini 4 from straight from the horses mouth](https://reddit.com/r/singularity/comments/1wufaxm/gemini_4_from_straight_from_the_horses_mouth/) ↑763
- [, Gemini 4 Argon Benchmarks](https://reddit.com/r/singularity/comments/1wufha8/gemini_4_argon_benchmarks/) ↑607

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [ChatGPT Dots is basically an upgraded OpenClaw?](https://reddit.com/r/openclaw/comments/1wty9zj/chatgpt_dots_is_basically_an_upgraded_openclaw/) ↑49
- [OpenClaw v2026.9.7 — snappier under load, smoother long chats, OpenAI Agents API, and more](https://reddit.com/r/openclaw/comments/1wubyey/openclaw_v202697_snappier_under_load_smoother/) ↑28
- [Openclaw + Local PrismML's Bonsai 2 (Qwen 3.8 27B) is Incredible](https://reddit.com/r/openclaw/comments/1wu7xwn/openclaw_local_prismmls_bonsai_2_qwen_38_27b_is/) ↑15
- [I am curious how many people here work in AI professionally.](https://reddit.com/r/openclaw/comments/1wujxh7/i_am_curious_how_many_people_here_work_in_ai/) ↑4
- [ChatGPT Plus, Sol and Openclaw](https://reddit.com/r/openclaw/comments/1wudikp/chatgpt_plus_sol_and_openclaw/) ↑3

### X — @openclaw
- [Jev & OpenClaw Enterprise


@hrudolph
 and 
@Pat_Erichsen
 talk decision models with 
@allietheicon
 from 
@typesafeai
 ](https://x.com/openclaw/status/2105475400797413578) ↑0 🔁0 · recent
- [The ClawCast — Jev & OpenClaw Enterprise (Episode 12)](https://x.com/openclaw/status/2105364577731182750) ↑0 🔁0 · recent
- [OpenClaw v2026.9.7 🦞

⚡ Snappier under load + smoother long chats
🛟 Update backups/rollback + 9.5 upgrade fixes
🤖 OpenAI](https://x.com/openclaw/status/2105356656846786748) ↑0 🔁0 · recent
- [Today on Clawcast we're talking all things Jev with 
@allietheicon
 and OpenClaw Enterprise with 
@kevins8
 & 
@jlehman_](https://x.com/openclaw/status/2105349910136799335) ↑0 🔁0 · recent


### X — @steipete
- [I'm finding inter-agent communication in the chat stream increasingly irritating. Changed the visibility in the OC harne](https://x.com/steipete/status/2105362785534361996) ↑0 🔁0 · recent
- [It’s a fierce fight between CI and GitHub on what slows me down. Time to rethink how we work. (love GH tho and fully see](https://x.com/steipete/status/2105341288958869952) ↑0 🔁0 · recent
- [This is not only silly, it’s also incredibly easy to work around. Why would Figma do this?](https://x.com/steipete/status/2105325370602135768) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
