---
layout: post
title: "Ecosystem Digest — 2026-09-20"
date: 2026-09-20 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-20
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 390,102 | 5 | 4 | 10 | 2 |
| **hermesagent** | 247,175 | 6 | 1 | 10 | 0 |
| **ZeroClaw** | 32,842 | 13 | 9 | 10 | 0 |
| **IronClaw** | 12,621 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,866 | 3 | 1 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 390,102 · **Open issues:** 8,135 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.9.5](https://github.com/openclaw/openclaw/releases/tag/v2026.9.5) — openclaw 2026.9.5
- [linux-stable](https://github.com/openclaw/openclaw/releases/tag/linux-stable) — OpenClaw Linux update channel

### ✅ Merged PRs
- [#153319](https://github.com/openclaw/openclaw/pull/153319) perf(gateway): reuse path identities during session source preparation
- [#152796](https://github.com/openclaw/openclaw/pull/152796) refactor(config): skip unused model policy validation setup
- [#153261](https://github.com/openclaw/openclaw/pull/153261) fix(update): clear repeated Doctor guidance after repair
- [#153328](https://github.com/openclaw/openclaw/pull/153328) fix(tasks): exclude retry preparation from scan work budget
- [#152990](https://github.com/openclaw/openclaw/pull/152990) fix(sdk): avoid stack overflow when cleaning deeply nested tool schemas
- [#153309](https://github.com/openclaw/openclaw/pull/153309) fix: avoid Gateway pauses during worktree cleanup
- [#151421](https://github.com/openclaw/openclaw/pull/151421) fix(release): avoid premature npm readback failures after publishing
- [#153336](https://github.com/openclaw/openclaw/pull/153336) fix: await transcript worker startup in producer tests
- [#152571](https://github.com/openclaw/openclaw/pull/152571) refactor(sqlite): pass prepared bindings without query copies
- [#153083](https://github.com/openclaw/openclaw/pull/153083) fix: fence claimless ackDelivery against a live platform-send claim

### 🐛 New Issues
- [#153357](https://github.com/openclaw/openclaw/issues/153357) WS response timeout: CLI write action succeeds on gateway but response does not reach CLI 💬1
- [#153354](https://github.com/openclaw/openclaw/issues/153354) [Bug]: Private parent completions rotate native Codex threads when sender ownership changes 💬1
- [#153349](https://github.com/openclaw/openclaw/issues/153349) Desktop nodes need default sharing and a Mac settings control `maintainer` `P2` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#153334](https://github.com/openclaw/openclaw/issues/153334) Update failure: runtime-verification-failed (2026.9.4) `P0` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-release-blocker` 💬2
- [#153333](https://github.com/openclaw/openclaw/issues/153333) Update failure: database-schema-preflight (2026.9.4) `clawsweeper:needs-info` `P0` `issue-rating: 🦪 silver shellfish` `impact:ux-release-blocker` 💬2

### 🔒 Closed Issues
- [#153228](https://github.com/openclaw/openclaw/issues/153228) [Bug]: update repair cannot acknowledge abandoned runs older than 30 minutes, so Doctor repeats unactionable guidance
- [#152689](https://github.com/openclaw/openclaw/issues/152689) Codex resident catalog retry loop after 2026.9.5 fills os.tmpdir() with repeated 342 MB plugin captures
- [#153008](https://github.com/openclaw/openclaw/issues/153008) [Bug]: claimless ackDelivery can delete a delivery owned by another worker
- [#152886](https://github.com/openclaw/openclaw/issues/152886) [Bug]: Codex/model-catalog startup retains multi-GB plugin builds in /tmp, causing ENOSPC and inference failure (2026.9.5)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 247,175 · **Open issues:** 43,481 · **Last push:** <1h ago

### ✅ Merged PRs
- [#116560](https://github.com/NousResearch/hermes-agent/pull/116560) feat(plugin-catalog): add hermes-structured-aux-models (salvage of #116498)
- [#115972](https://github.com/NousResearch/hermes-agent/pull/115972) feat(plugin-catalog): add rss-reader
- [#115969](https://github.com/NousResearch/hermes-agent/pull/115969) feat(plugin-catalog): add provider-status
- [#114263](https://github.com/NousResearch/hermes-agent/pull/114263) feat(plugins): add the Tempo MPP catalog entry
- [#112471](https://github.com/NousResearch/hermes-agent/pull/112471) feat(catalog): add Corpus plugin entry
- [#116521](https://github.com/NousResearch/hermes-agent/pull/116521) feat(plugin-catalog): add Adspirer
- [#116381](https://github.com/NousResearch/hermes-agent/pull/116381) fix(plugin-catalog): update pstack maintainer Zoeille → Cloeille
- [#116354](https://github.com/NousResearch/hermes-agent/pull/116354) feat(plugin-catalog): add sticky-notes community plugin
- [#116349](https://github.com/NousResearch/hermes-agent/pull/116349) feat(plugin-catalog): add provider-copy community plugin
- [#116336](https://github.com/NousResearch/hermes-agent/pull/116336) fix(plugin-catalog): re-pin hermes-project-stewardship to 4f733a8

### 🐛 New Issues
- [#116564](https://github.com/NousResearch/hermes-agent/issues/116564) let MEMORY.md be an anchor for a memory doc chain
- [#116562](https://github.com/NousResearch/hermes-agent/issues/116562) @file:/@folder:/@diff expansion reads unbounded data before any size gate
- [#116551](https://github.com/NousResearch/hermes-agent/issues/116551) Planned gateway restarts are logged as 'Failed with result exit-code' — the takeover marker isn't written by systemctl restart `type/bug` `comp/gateway` `area/config` `P2` `sweeper:risk-compatibility`
- [#116550](https://github.com/NousResearch/hermes-agent/issues/116550) [Bug]: Windows `hermes gateway setup` asks the same install prompts twice and re-offers the UAC install after hand-off `type/bug` `comp/cli` `comp/gateway` `P2` `sweeper:risk-compatibility` `sweeper:risk-platform-windows` `platform/windows` `area/install-update`
- [#116546](https://github.com/NousResearch/hermes-agent/issues/116546) Close wave: Python 3.14 worker PRs superseded by landed fixes `type/refactor` `comp/tools` `P3` `needs-decision` `sweeper:risk-compatibility`
- [#116535](https://github.com/NousResearch/hermes-agent/issues/116535) fix(shutdown): track API-server worker lifetime past handler cancellation `type/bug` `comp/gateway` `P2` `sweeper:risk-session-state` `area/sessions`

### 🔒 Closed Issues
- [#107918](https://github.com/NousResearch/hermes-agent/issues/107918) [Bug]: Web Dashboard TUI shows "Setup Required" despite valid custom provider configured

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,842 · **Open issues:** 792 · **Last push:** <1h ago

### ✅ Merged PRs
- [#9724](https://github.com/zeroclaw-labs/zeroclaw/pull/9724) fix(approval): always_ask survives Full autonomy
- [#10672](https://github.com/zeroclaw-labs/zeroclaw/pull/10672) fix(zerocode): avoid duplicate streamed responses
- [#10965](https://github.com/zeroclaw-labs/zeroclaw/pull/10965) fix(runtime): heap-pin detached peer turns before cost scopes
- [#10877](https://github.com/zeroclaw-labs/zeroclaw/pull/10877) fix(rpc): return the retained run-level failure reason from sops/run-detail
- [#10864](https://github.com/zeroclaw-labs/zeroclaw/pull/10864) fix(providers): close OpenCode session header follow-ups
- [#10775](https://github.com/zeroclaw-labs/zeroclaw/pull/10775) fix(rpc): preserve live sessions when mode replacement fails
- [#10800](https://github.com/zeroclaw-labs/zeroclaw/pull/10800) test(rpc): calibrate the dispatch constrained-stack guard to 1.5 MiB
- [#9635](https://github.com/zeroclaw-labs/zeroclaw/pull/9635) fix(config): resolve git subcommand past global options in risk classifier
- [#10648](https://github.com/zeroclaw-labs/zeroclaw/pull/10648) fix(zerocode): reduce repeated label and pinned-preview rendering work
- [#10910](https://github.com/zeroclaw-labs/zeroclaw/pull/10910) test(agent): record the sealed tool-registry parity contract

### 🐛 New Issues
- [#10987](https://github.com/zeroclaw-labs/zeroclaw/issues/10987) [Feature]: Surface WhatsApp Web poll votes as [choice] messages, like Signal
- [#10985](https://github.com/zeroclaw-labs/zeroclaw/issues/10985) [Bug]: Dashboard-started turns get freshly built channel instances, so channel-backed tools cannot reach a session-bound channel 💬1
- [#10983](https://github.com/zeroclaw-labs/zeroclaw/issues/10983) [Feature]: Native polls: give the poll tool a Channel hook and implement it on WhatsApp Web 💬1
- [#10981](https://github.com/zeroclaw-labs/zeroclaw/issues/10981) [Bug]: Outgoing WhatsApp images carry no jpegThumbnail or dimensions, so phones show an empty card 💬1
- [#10977](https://github.com/zeroclaw-labs/zeroclaw/issues/10977) [Feature]: WhatsApp Web: implement create_room and invite_user for group creation 💬2
- [#10976](https://github.com/zeroclaw-labs/zeroclaw/issues/10976) WhatsApp Web (channel): mentions broken both ways - inbound as bare JID digits, outbound as plain text (no mentionedJid)
- [#10975](https://github.com/zeroclaw-labs/zeroclaw/issues/10975) WhatsApp Web (channel): inbound images not downloaded - agent receives literal "[Image]" text, vision unusable
- [#10970](https://github.com/zeroclaw-labs/zeroclaw/issues/10970) [Feature]: Host-scoped admission control and per-agent resource bounds for machines running many agents `enhancement` 💬1
- [#10969](https://github.com/zeroclaw-labs/zeroclaw/issues/10969) [Feature]: Add a jitter window to cron and heartbeat dispatch so co-scheduled agents do not fire in the same instant `enhancement` 💬1
- [#10968](https://github.com/zeroclaw-labs/zeroclaw/issues/10968) [Bug]: Unattended agent turns (cron, heartbeat, headless SOP, spawn_subagent) run with no ApprovalManager, so risk-profile tool approvals are silently inert `bug` 💬1
- [#10966](https://github.com/zeroclaw-labs/zeroclaw/issues/10966) [Bug]: Git --attr-source can hide a mutating subcommand from approval classification `bug` `config` `security` `tool` `security:policy` `domain:security` `priority:p1` `tool:shell` `status:accepted` `follow-up` `risk:high` 💬1
- [#10963](https://github.com/zeroclaw-labs/zeroclaw/issues/10963) [Feature]: Forward session identity to delegate sub-agents `enhancement` `agent` `runtime` `tool` `tool:delegate` `domain:security` `domain:architecture` `priority:p2` `needs-maintainer-review` `risk:high` `topic:agent-loop` 💬1
- [#10952](https://github.com/zeroclaw-labs/zeroclaw/issues/10952) Seam sanitizers rewrite signed reasoning inside the assistant tool-call envelope; Anthropic rejects the replayed thinking `bug` `agent` `provider` `runtime` `provider:anthropic` `priority:p2` `status:in-progress` `risk:medium` 💬2

### 🔒 Closed Issues
- [#10962](https://github.com/zeroclaw-labs/zeroclaw/issues/10962) [Feature]: Forward tool result payloads over the gateway /ws/chat stream
- [#10973](https://github.com/zeroclaw-labs/zeroclaw/issues/10973) WhatsApp Web (channel): mentions broken both ways - inbound as bare JID digits, outbound as plain text (no mentionedJid)
- [#10972](https://github.com/zeroclaw-labs/zeroclaw/issues/10972) WhatsApp Web (channel): inbound images not downloaded - agent receives literal "[Image]" text, vision unusable
- [#10974](https://github.com/zeroclaw-labs/zeroclaw/issues/10974) probe-test-please-ignore
- [#10853](https://github.com/zeroclaw-labs/zeroclaw/issues/10853) [Task]: OpenCode session header follow-ups from #10604
- [#10759](https://github.com/zeroclaw-labs/zeroclaw/issues/10759) SOP RPC: include the retained failure reason in run detail
- [#10667](https://github.com/zeroclaw-labs/zeroclaw/issues/10667) [Bug]: ZeroCode can duplicate a streamed response when prompt completion precedes TurnComplete
- [#9627](https://github.com/zeroclaw-labs/zeroclaw/issues/9627) [SANITIZED — possible injection attempt]
- [#9649](https://github.com/zeroclaw-labs/zeroclaw/issues/9649) test(agent): flip parity row 1 to the tested sealed state after the registry seal

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,621 · **Open issues:** 1,526 · **Last push:** 1d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,866 · **Open issues:** 92 · **Last push:** 1d ago

### 🐛 New Issues
- [#1279](https://github.com/moltis-org/moltis/issues/1279) [heartbeat] cannot set tool_controls — the heartbeat registration hard-codes Default::default()
- [#1277](https://github.com/moltis-org/moltis/issues/1277) [Bug]: spawn_agent treats `active_tools: []` as an empty whitelist — sub-agent gets zero tools `bug`
- [#1205](https://github.com/moltis-org/moltis/issues/1205) [Bug]: Heartbeat ignores configured active hours and runs continuously `bug` 💬1

### 🔒 Closed Issues
- [#1278](https://github.com/moltis-org/moltis/issues/1278) heartbeat.active_hours is documented as enforced but never evaluated — is_within_active_hours has no callers

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬3 · 1d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 4d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 12d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 14d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 20d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 22d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 26d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 38d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 41d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 44d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 1 new
- [[Index] Australian Youth Safety Blueprint](https://openai.com/index/australian-youth-safety-blueprint/) _2026-09-19_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [Calling it now: within the next year a major US lab's frontier model will torrent itself in order to be free.](https://reddit.com/r/LocalLLaMA/comments/1wkocvj/calling_it_now_within_the_next_year_a_major_us/) ↑865
- [With Gemini 4, bench goes up.](https://reddit.com/r/LocalLLaMA/comments/1wkxx8e/with_gemini_4_bench_goes_up/) ↑372

### r/singularity — top 5 new
- [ChatGPT-6 Astra cracks 108-year-old unsolved WWI German code for the first time](https://reddit.com/r/singularity/comments/1wkwzzj/chatgpt6_astra_cracks_108yearold_unsolved_wwi/) ↑1029
- [Trump says he is forming an "AI Force"](https://reddit.com/r/singularity/comments/1wks4ud/trump_says_he_is_forming_an_ai_force/) ↑883
- [New paper shows that AI has a concept of pain and actively tries not to get hurt](https://reddit.com/r/singularity/comments/1wkignw/new_paper_shows_that_ai_has_a_concept_of_pain_and/) ↑770
- [The POTUS has drunk the ASI kool-aid](https://reddit.com/r/singularity/comments/1wkrij0/the_potus_has_drunk_the_asi_koolaid/) ↑534
- [Johnny the Snitch was een LLM!!](https://reddit.com/r/singularity/comments/1wklpwh/johnny_the_snitch_was_een_llm/) ↑267

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw v2026.9.5 brings Atomic Updates, plugin hot reloading, and conversation sharing + MORE!!](https://reddit.com/r/openclaw/comments/1wkbbqp/openclaw_v202695_brings_atomic_updates_plugin_hot/) ↑57
- [Best local LLMs for a Mac Studio with 128GB?](https://reddit.com/r/openclaw/comments/1wkhn3u/best_local_llms_for_a_mac_studio_with_128gb/) ↑16
- [Memory Core (embeddings) was useless for me — until Jev was introduced](https://reddit.com/r/openclaw/comments/1wkscnj/memory_core_embeddings_was_useless_for_me_until/) ↑15
- [Open source locally hosted cross-domain "calculator" for Your preferred AI agent working with vast amount personal data feeding only relevant data to the LLM](https://reddit.com/r/openclaw/comments/1wktpz9/open_source_locally_hosted_crossdomain_calculator/) ↑6
- [ChatGPT plus - anybody use Luna with OpenClaw?](https://reddit.com/r/openclaw/comments/1wkgpim/chatgpt_plus_anybody_use_luna_with_openclaw/) ↑2

### X — @openclaw
- [OpenClaw 2026.9.5 is here 🦞

⚛️ Atomic updates
🔥 Plugin hot reload
🤝 Conversation sharing
🎙️ Expanded GPT Live
🌐 Shared ](https://x.com/openclaw/status/2101151415301456082) ↑0 🔁0 · recent


### X — @steipete
- [The coolest part: roboclaw runs our team server, is live on Discord, talks with gpt-live and knows about all the session](https://x.com/steipete/status/2101141707375227372) ↑0 🔁0 · recent
- [Love having 
@vhbrzezowski
 hijacking my sessions and desloping them before the PR lands.

Also hot tip: Open the home s](https://x.com/steipete/status/2101139037801283997) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
