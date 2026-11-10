---
layout: post
title: "Ecosystem Digest — 2026-11-10"
date: 2026-11-10 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-10
*Generated 07:47 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 394,259 | 3 | 3 | 10 | 0 |
| **hermesagent** | 262,096 | 6 | 8 | 10 | 1 |
| **ZeroClaw** | 33,302 | 15 | 6 | 10 | 0 |
| **IronClaw** | 12,716 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,952 | 1 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 394,259 · **Open issues:** 8,084 · **Last push:** <1h ago

### ✅ Merged PRs
- [#196298](https://github.com/openclaw/openclaw/pull/196298) fix(worktrees): avoid minute-long ignored-file provisioning
- [#196097](https://github.com/openclaw/openclaw/pull/196097) fix(feishu): preserve quoted attachment filenames containing semicolons
- [#196355](https://github.com/openclaw/openclaw/pull/196355) docs: check hotfix ledger completeness at release closeout
- [#196229](https://github.com/openclaw/openclaw/pull/196229) fix(gateway): avoid repeated session-source scans during watch bursts
- [#196373](https://github.com/openclaw/openclaw/pull/196373) fix(release): allow large recovery Docker archive transfers
- [#196337](https://github.com/openclaw/openclaw/pull/196337) fix: let input policy hooks inspect prepared images
- [#196168](https://github.com/openclaw/openclaw/pull/196168) fix: preserve conversation workspace during local publication
- [#196313](https://github.com/openclaw/openclaw/pull/196313) improve(ui): show completed work as one "Worked for" line with a visible chevron
- [#195730](https://github.com/openclaw/openclaw/pull/195730) feat: create templates directly from chat
- [#195027](https://github.com/openclaw/openclaw/pull/195027) fix(knowledge): exclude image-alt links from navigation

### 🐛 New Issues
- [#196381](https://github.com/openclaw/openclaw/issues/196381) Isolated cron sessions fail with MCP_AUTHORIZATION_RETIRED after secrets migration — auth-profile assertion, not MCP `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `impact:auth-provider` `issue-rating: 🦪 silver shellfish` 💬2
- [#196358](https://github.com/openclaw/openclaw/issues/196358) Human corrections wait until the active task finishes instead of steering it `P1` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#196350](https://github.com/openclaw/openclaw/issues/196350) [Bug]: openclaw doctor early-returns with "controlled by another owner" on installationDrift when a systemd ExecStart drop-in is present, masking the drop-in diagnostic `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#196075](https://github.com/openclaw/openclaw/issues/196075) [Bug]: Feishu attachment downloads truncate quoted filenames containing semicolons
- [#195013](https://github.com/openclaw/openclaw/issues/195013) [Bug]: Knowledge counts inert image-alt wikilinks as navigation edges
- [#195060](https://github.com/openclaw/openclaw/issues/195060) [Bug]: Knowledge records returns a continuation offset rejected by its own input schema

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬80 · 3d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 262,096 · **Open issues:** 53,934 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.23.1](https://github.com/NousResearch/hermes-agent/releases/tag/v0.23.1) — Hermes Agent v0.23.1

### ✅ Merged PRs
- [#152310](https://github.com/NousResearch/hermes-agent/pull/152310) fix(gateway): slash confirms and clarify questions answer only to their requester (salvage #72008)
- [#152305](https://github.com/NousResearch/hermes-agent/pull/152305) Telegram group replies no longer lose their opening when the final edit is refused (typing stops holding the send slot)
- [#151801](https://github.com/NousResearch/hermes-agent/pull/151801) fix(telegram): fallback IPs keep the seeds and retired adapters edit/delete through their own profile's replacement (#75416, #143364, #98228, salvage #76685, #147977)
- [#151772](https://github.com/NousResearch/hermes-agent/pull/151772) fix(telegram): forum topics run independently, gate drops are logged, /handoff keeps its topic (#145641, #52635, #45295, #78770, #78772)
- [#151956](https://github.com/NousResearch/hermes-agent/pull/151956) fix(tui,cli): resumed chats with no saved provider keep their custom provider
- [#152125](https://github.com/NousResearch/hermes-agent/pull/152125) fix(approvals): approvers: [] binds to the real sender and one admin scope on every surface
- [#152262](https://github.com/NousResearch/hermes-agent/pull/152262) fix(hosted-room): Group Chat turns queued behind a busy profile keep their room lease and settle
- [#151851](https://github.com/NousResearch/hermes-agent/pull/151851) fix(telegram): webhook boot retries, held replay order, home topic, HTML send and e2e SDK guard hold (#141397, #138793, #58299, #142568, #147239)
- [#151741](https://github.com/NousResearch/hermes-agent/pull/151741) fix(telegram): topics take the restored/switched session's name and binding; /topic stops minting a pinned System topic (#36992, #98066, #58850)
- [#151863](https://github.com/NousResearch/hermes-agent/pull/151863) fix(telegram): a split long paste stays one turn, drafts and deletes respect the flood window (#74752, #107612, salvage #111162)

### 🐛 New Issues
- [#152367](https://github.com/NousResearch/hermes-agent/issues/152367) [Bug]: Real-profile browser snapshot marks every Web Store extension as corrupted (Extensions dropped, extension prefs kept)
- [#152365](https://github.com/NousResearch/hermes-agent/issues/152365) [Bug]: Weixin voice message (text='', audio/silk) leaves session_admissions row stuck at 'started' — session reports running forever and later messages are silently dropped
- [#152364](https://github.com/NousResearch/hermes-agent/issues/152364) Windows gateway: event-loop stalls under concurrent Kanban workers, misleading worker-loss reason, stale env probe cache, empty completion notices
- [#152347](https://github.com/NousResearch/hermes-agent/issues/152347) [Bug]: pm/environment.py silently strips UV_INDEX_URL for pinned runtime, breaking mirror usage while error hint tells users to set it `bug` 💬1
- [#152345](https://github.com/NousResearch/hermes-agent/issues/152345) [Bug]: Desktop GPT-Live: the reply is appended to the voice while it is still streaming, pre-tool narration included 💬1
- [#152344](https://github.com/NousResearch/hermes-agent/issues/152344) Desktop: `/new` in a remote gateway's Bot Chat opens a new session on the local device instead of compacting on the remote 💬1

### 🔒 Closed Issues
- [#151856](https://github.com/NousResearch/hermes-agent/issues/151856) [Bug]: the live plugin-catalog.json is now over the client's 2 MiB cap, so clients fall back to the in-tree catalog
- [#140667](https://github.com/NousResearch/hermes-agent/issues/140667) [Bug]: Desktop: session.control.read times out at 30s - one slow read-only handler (session.context_breakdown) starves every queued RPC on the same WS
- [#18165](https://github.com/NousResearch/hermes-agent/issues/18165) Unify MCP HTTP recovery around connection lifecycle and error classification
- [#100855](https://github.com/NousResearch/hermes-agent/issues/100855) [Bug]: agent-browser daemons from the browser_exec / real-profile lanes have no AGENT_BROWSER_SOCKET_DIR — invisible to the orphan reaper; wedged daemon + headless Chrome survived 47h across two gatew
- [#136412](https://github.com/NousResearch/hermes-agent/issues/136412) [Bug]: Telegram gateway — per-path connect budget ≥ whole-send deadline + connect-phase timeout classified non-retryable → silent delivery loss
- [#143364](https://github.com/NousResearch/hermes-agent/issues/143364) Multiplexed secondary profile's mid-turn progress + background-review notices deliver via the primary (launch-profile) bot
- [#147346](https://github.com/NousResearch/hermes-agent/issues/147346) [Bug]: Telegram adapter fallback walk drops SEED_FALLBACK_IPS when DoH returns single IP; blackholed IP leaves no alternate route
- [#98228](https://github.com/NousResearch/hermes-agent/issues/98228) [Bug]: Telegram in-flight progress and cleanup use retired adapter after replacement reconnect

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,302 · **Open issues:** 1,188 · **Last push:** 3h ago

### ✅ Merged PRs
- [#12342](https://github.com/zeroclaw-labs/zeroclaw/pull/12342) docs(runtime): record bounded zerocode OIDC placement exception
- [#11933](https://github.com/zeroclaw-labs/zeroclaw/pull/11933) fix(web): keep the chat header on screen in narrow layouts
- [#11920](https://github.com/zeroclaw-labs/zeroclaw/pull/11920) feat(web): add a toggle to keep the live Thinking box collapsed
- [#12068](https://github.com/zeroclaw-labs/zeroclaw/pull/12068) fix(security): stop treating a bare semicolon or pipe as command injection
- [#12321](https://github.com/zeroclaw-labs/zeroclaw/pull/12321) chore(security): ignore RUSTSEC-2026-0459 (libsqlite3-sys bundled SQLite)
- [#12297](https://github.com/zeroclaw-labs/zeroclaw/pull/12297) docs(runtime): clarify scoped chat principal binding
- [#12172](https://github.com/zeroclaw-labs/zeroclaw/pull/12172) fix(config): prefix dash-leading lifecycle remedy paths with ./
- [#12100](https://github.com/zeroclaw-labs/zeroclaw/pull/12100) fix(web): keep FieldForm draft in sync after entity enable toggle
- [#12065](https://github.com/zeroclaw-labs/zeroclaw/pull/12065) fix(channels): keep allowlisted Discord bots from answering approvals
- [#11687](https://github.com/zeroclaw-labs/zeroclaw/pull/11687) test(rpc): cover a workspace and allowed root configured through a link

### 🐛 New Issues
- [#12353](https://github.com/zeroclaw-labs/zeroclaw/issues/12353) [Feature]: Show the running estimated cost of each conversation `enhancement`
- [#12351](https://github.com/zeroclaw-labs/zeroclaw/issues/12351) [Bug]: ordinary_failure_then_real_anthropic_server_fallback_keeps_original_request_visible fails intermittently in CI `bug` 💬1
- [#12350](https://github.com/zeroclaw-labs/zeroclaw/issues/12350) [Bug]: Telegram channel tests hang in CI's Parallel Runtime Test until the 30-minute job timeout `bug`
- [#12347](https://github.com/zeroclaw-labs/zeroclaw/issues/12347) [Bug]: zerocode config writers can drop a concurrent update to zerocode-config.toml `bug`
- [#12340](https://github.com/zeroclaw-labs/zeroclaw/issues/12340) [Docs]: Say that every zerocode device grant now sends PKCE, and scope the legacy connection-credential sentence to the selected URL `docs` `type:docs`
- [#12339](https://github.com/zeroclaw-labs/zeroclaw/issues/12339) [Task]: Prune zerocode OIDC credential generations that no saved login references `security` `zerocode`
- [#12338](https://github.com/zeroclaw-labs/zeroclaw/issues/12338) [Task]: Decide and pin what a zerocode client certificate without a CA means after the public-roots default `zerocode`
- [#12337](https://github.com/zeroclaw-labs/zeroclaw/issues/12337) [Feature]: Operator opt-in, default off, for OIDC self-service device certificate bootstrap `enhancement` `gateway` `security` `domain:security` `zerocode`
- [#12334](https://github.com/zeroclaw-labs/zeroclaw/issues/12334) [Task]: Make the zerocode OIDC bootstrap smoke test wait for the ledger table
- [#12333](https://github.com/zeroclaw-labs/zeroclaw/issues/12333) [Task]: Record the OIDC certificate ledger actor without the doubled oidc: prefix
- [#12332](https://github.com/zeroclaw-labs/zeroclaw/issues/12332) [Docs]: Explain how a zerocode OIDC device certificate ends, and how azp attributes a client `docs` `type:docs`
- [#12331](https://github.com/zeroclaw-labs/zeroclaw/issues/12331) [Task]: Pin the OIDC client_id/azp conflict refusal with tests that fail without it
- [#12330](https://github.com/zeroclaw-labs/zeroclaw/issues/12330) [Bug]: zerocode drops its saved remote connection and falls back to a local daemon when zerocode-config.toml can't be parsed or read `bug`
- [#12326](https://github.com/zeroclaw-labs/zeroclaw/issues/12326) [Bug]: links to pruned docs versions end on GitHub Pages' generic 404 `bug`
- [#12325](https://github.com/zeroclaw-labs/zeroclaw/issues/12325) [Bug]: docs canonical URLs name the release dir, so every stable release moves all of them `bug`

### 🔒 Closed Issues
- [#11919](https://github.com/zeroclaw-labs/zeroclaw/issues/11919) [Feature]: Web chat toggle to keep the live Thinking box collapsed
- [#10359](https://github.com/zeroclaw-labs/zeroclaw/issues/10359) AuditLogger advances hash-chain state before the write, poisoning verification after one failed write
- [#11009](https://github.com/zeroclaw-labs/zeroclaw/issues/11009) [Bug]: Agent alias rename does not cascade permission-profile selectors
- [#12087](https://github.com/zeroclaw-labs/zeroclaw/issues/12087) [Bug]: Tool enable/disable buttons auto-save while at the same time enabling save button
- [#12064](https://github.com/zeroclaw-labs/zeroclaw/issues/12064) [Bug]: Discord plaintext approvals can be answered by an allowlisted peer bot
- [#11952](https://github.com/zeroclaw-labs/zeroclaw/issues/11952) [Task]: make lifecycle-directory repair commands work for a relative data directory that starts with `-`

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,716 · **Open issues:** 1,571 · **Last push:** 8h ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,952 · **Open issues:** 123 · **Last push:** 17d ago

### 🐛 New Issues
- [#1322](https://github.com/moltis-org/moltis/issues/1322) [Bug]: Desktop app model picker lists every reasoning effort as a separate model

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬3 · 1d ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 7d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 16d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 35d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 43d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 45d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 55d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 63d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 65d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 73d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 2 new
- [Claude Fable And Mythos 5 2](https://www.anthropic.com/claude-fable-and-mythos-5-2) _2026-11-09_
- [[Research] Claude Electronics Design](https://www.anthropic.com/research/claude-electronics-design) _2026-11-09_

### OpenAI — 8 new
- [[Index] Kuken](https://openai.com/index/kuken/) _2026-11-09_
- [[Product] Theresetcompany Hoodie](https://openai.com/supply/product/theresetcompany-hoodie/)
- [[Product] Dots Tee](https://openai.com/supply/product/dots-tee/)
- [[Product] Blossom Tee Gray](https://openai.com/supply/product/blossom-tee-gray/)
- [[Product] Dots Tote](https://openai.com/supply/product/dots-tote/)
- [[Product] Gpt 6 Longsleeve](https://openai.com/supply/product/gpt-6-longsleeve/)
- [[Product] Modretro Codex Cartridge](https://openai.com/supply/product/modretro-codex-cartridge/)
- [[Product] Modretro Chromatic Case Codex Edition](https://openai.com/supply/product/modretro-chromatic-case-codex-edition/)

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Qwen3.8-27B has become unuseable recently](https://reddit.com/r/LocalLLaMA/comments/1xoeeyf/qwen3827b_has_become_unuseable_recently/) ↑1555
- [Kimi-K3.1-Pro is now open-weights](https://reddit.com/r/LocalLLaMA/comments/1xnrhvb/kimik31pro_is_now_openweights/) ↑1482
- [More interesting and unusual Qwen3.5-4B neurons](https://reddit.com/r/LocalLLaMA/comments/1xrydgx/more_interesting_and_unusual_qwen354b_neurons/) ↑280
- [L11 N8147 is a neuron that will make Qwen-3.5-4B get things confidently wrong while being weirdly snarky... But also makes it write interesting poetry](https://reddit.com/r/LocalLLaMA/comments/1xrkomn/l11_n8147_is_a_neuron_that_will_make_qwen354b_get/) ↑279
- [From the finest minds of our age to the dumbest monkeys on the planet](https://reddit.com/r/LocalLLaMA/comments/1xs0izk/from_the_finest_minds_of_our_age_to_the_dumbest/) ↑183

### r/singularity — top 5 new
- [Jensen does not run his personal life in single thread](https://reddit.com/r/singularity/comments/1xrr40n/jensen_does_not_run_his_personal_life_in_single/) ↑1648
- [Skyrim modder uses AI to help reverse-engineer the game's 15-year-old engine, adding real-time terrain editing, modular construction, and NPC navigation to player-built structures.](https://reddit.com/r/singularity/comments/1xrvqoo/skyrim_modder_uses_ai_to_help_reverseengineer_the/) ↑844
- [Claude Fable 5.2 built a playable Gears of War clone in Unreal Engine from a 3-line prompt, complete with enemy AI, cover mechanics and active reloading. After testing it with over 100 billion tokens,](https://reddit.com/r/singularity/comments/1xs1y29/claude_fable_52_built_a_playable_gears_of_war/) ↑827
- [Boston Dynamics demos Atlas over wheels](https://reddit.com/r/singularity/comments/1xrxbul/boston_dynamics_demos_atlas_over_wheels/) ↑539
- [Introducing Fable 5.2 and Mythos 5.2](https://reddit.com/r/singularity/comments/1xs0d1i/introducing_fable_52_and_mythos_52/) ↑520

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [My Openclaw now calls my phone when it needs me. No Twilio, no phone number, free](https://reddit.com/r/openclaw/comments/1xru5k2/my_openclaw_now_calls_my_phone_when_it_needs_me/) ↑49
- [OpenClaw v2026.11.2 patch fixes update trouble, missing reminders and duplicate chat widgets](https://reddit.com/r/openclaw/comments/1xrjej1/openclaw_v2026112_patch_fixes_update_trouble/) ↑15
- [Openclaw Broke Fallback Models across providers](https://reddit.com/r/openclaw/comments/1xrvr49/openclaw_broke_fallback_models_across_providers/) ↑6
- [The OpenClaw Android app is awful, so I rebuilt it myself](https://reddit.com/r/openclaw/comments/1xrtu21/the_openclaw_android_app_is_awful_so_i_rebuilt_it/) ↑4
- [Heartbeat spamming me](https://reddit.com/r/openclaw/comments/1xrkrj2/heartbeat_spamming_me/) ↑1

### X — @openclaw
- [More conversations like this on The ClawCast, the OpenClaw podcast.

Listen to the full episode

https://
openclaw.ai/po](https://x.com/openclaw/status/2119935567869735171) ↑0 🔁0 · recent
- [OpenClaw v2026.11.2 patch is out! 🦞
🔧 Fixes update repair trouble
⏰ Fixes missing reminders
🧩 Fixes duplicate chat widge](https://x.com/openclaw/status/2119654699284779170) ↑0 🔁0 · recent


### X — @steipete
_No new tweets since the last digest. Most recent:_
- [The Asahi project was all about taking something closed and restricted and opening it up.

Adding new restrictions that ](https://x.com/steipete/status/2119264334627090514)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
