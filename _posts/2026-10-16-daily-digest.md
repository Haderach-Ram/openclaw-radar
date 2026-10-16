---
layout: post
title: "Ecosystem Digest — 2026-10-16"
date: 2026-10-16 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-16
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 392,130 | 3 | 2 | 10 | 4 |
| **hermesagent** | 254,142 | 14 | 3 | 2 | 1 |
| **ZeroClaw** | 32,984 | 13 | 0 | 1 | 0 |
| **IronClaw** | 12,657 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,889 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 392,130 · **Open issues:** 9,476 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.10.10-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.10.10-beta.1) — openclaw 2026.10.10-beta.1
- [v2026.10.5-beta.4](https://github.com/openclaw/openclaw/releases/tag/v2026.10.5-beta.4) — openclaw 2026.10.5-beta.4
- [v2026.10.4](https://github.com/openclaw/openclaw/releases/tag/v2026.10.4) — openclaw 2026.10.4
- [v2026.9.33](https://github.com/openclaw/openclaw/releases/tag/v2026.9.33) — openclaw 2026.9.33

### ✅ Merged PRs
- [#171675](https://github.com/openclaw/openclaw/pull/171675) fix(memory-wiki): reject malformed UTF-8 source imports
- [#173643](https://github.com/openclaw/openclaw/pull/173643) fix(sqlite): release caller memory after worker opening
- [#173575](https://github.com/openclaw/openclaw/pull/173575) test(ui): finish native chat transcript fixtures
- [#173628](https://github.com/openclaw/openclaw/pull/173628) fix(test): reduce serial tails in local full-suite runs
- [#171621](https://github.com/openclaw/openclaw/pull/171621) fix(memory-wiki): reject malformed ChatGPT export encoding
- [#173452](https://github.com/openclaw/openclaw/pull/173452) refactor(auto-reply): simplify runtime bookkeeping
- [#173637](https://github.com/openclaw/openclaw/pull/173637) refactor(tests): simplify legacy session-group fixture
- [#173572](https://github.com/openclaw/openclaw/pull/173572) fix(cron): ignore rate-limit cooldowns when Doctor records an automation account
- [#173624](https://github.com/openclaw/openclaw/pull/173624) refactor(tests): consolidate iMessage discovery checks
- [#173622](https://github.com/openclaw/openclaw/pull/173622) fix(memory): avoid rebuilding initially empty indexes after restart

### 🐛 New Issues
- [#173650](https://github.com/openclaw/openclaw/issues/173650) [Bug]: subagent completion with completionTarget=parent commits the relay to the transcript without channel delivery and without a signal that it was not sent 💬1
- [#173631](https://github.com/openclaw/openclaw/issues/173631) cron show crashes when a job row omits its state object `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬3
- [#173621](https://github.com/openclaw/openclaw/issues/173621) Update failure: candidate-gateway-startup (2026.10.2) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#110915](https://github.com/openclaw/openclaw/issues/110915) Add LLMTR provider (Turkey-hosted OpenAI-compatible AI gateway)
- [#106009](https://github.com/openclaw/openclaw/issues/106009) Effort/thinking level clamps are silent across all providers (no warning when xhigh/max is reduced)

### 🔥 Hot Issues (most commented)
- [#143524](https://github.com/openclaw/openclaw/issues/143524) [Bug]: Agent SQLite WAL grows to 1.4–2.8 GB in days despite wal_autocheckpoint=1000; blocks gateway startup (Windows, 2026.9.2/9.3) — 💬128 · 1h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 254,142 · **Open issues:** 49,387 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.22.2](https://github.com/NousResearch/hermes-agent/releases/tag/v0.22.2) — Hermes Agent v0.22.2

### ✅ Merged PRs
- [#139466](https://github.com/NousResearch/hermes-agent/pull/139466) fix(solstice): offer Gemini 4 Argon
- [#139222](https://github.com/NousResearch/hermes-agent/pull/139222) fix: 27 race / coarse-timestamp / lost-update bugs

### 🐛 New Issues
- [#139556](https://github.com/NousResearch/hermes-agent/issues/139556) [Bug]: Dashboard Chat PTY dies instantly under pm2 — inherited NODE_CHANNEL_FD aborts node child processes (libuv EEXIST) `bug`
- [#139554](https://github.com/NousResearch/hermes-agent/issues/139554) WeCom: heartbeat ack frames flood agent.log with "Unrouted websocket payload dropped" INFO every 30s (still present in v0.22.2) `type/bug` `comp/plugins` `platform/wecom` `P3`
- [#139552](https://github.com/NousResearch/hermes-agent/issues/139552) profile alias: no list command (stale aliases accumulate unseen) `type/feature` `comp/cli` `P3` `area/profiles`
- [#139551](https://github.com/NousResearch/hermes-agent/issues/139551) doctor probes static provider rows unconditionally (false key demands) `invalid` `comp/cli` `P3`
- [#139550](https://github.com/NousResearch/hermes-agent/issues/139550) desktop Repair install restarts backend on attempts 1-3, no venv integrity probe `type/bug` `P2` `comp/desktop` `area/install-update`
- [#139549](https://github.com/NousResearch/hermes-agent/issues/139549) doctor: no gateway liveness check (dead gateway, all green) `type/bug` `comp/cli` `P3`
- [#139548](https://github.com/NousResearch/hermes-agent/issues/139548) [Bug]: Desktop Edit profile shows an empty Description for bots on a remote gateway (roster drops profile description) `type/bug` `P3` `comp/desktop` `area/profiles`
- [#139542](https://github.com/NousResearch/hermes-agent/issues/139542) [Bug]: Linux Desktop renderer crash loop survives clean fallback markers — setuid-sandbox lane cannot create /dev/shm (ESRCH); --disable-setuid-sandbox dies with "No usable sandbox" `type/bug` `P2` `needs-repro` `sweeper:risk-security-boundary` `comp/desktop`
- [#139540](https://github.com/NousResearch/hermes-agent/issues/139540) [Bug]: Desktop install/update writes incorrect volume path case, causing "dependency environment is missing or outside this install" on case-insensitive APFS** `type/bug` `comp/cli` `P2` `sweeper:risk-compatibility` `comp/desktop` `bug` `area/install-update`
- [#139538](https://github.com/NousResearch/hermes-agent/issues/139538) [Bug]: Compaction accepted a meta-summary before a malformed completed reply `type/bug` `comp/agent` `P2` `needs-repro` `sweeper:risk-session-state` `area/compression`
- [#139536](https://github.com/NousResearch/hermes-agent/issues/139536) [Bug]: TUI active-session switcher close never works on a canonical gateway — reports "session was already closed" `type/bug` `comp/gateway` `comp/tui` `P2` `sweeper:risk-session-state` `area/sessions` 💬1
- [#139533](https://github.com/NousResearch/hermes-agent/issues/139533) plugins install crashes on Windows when the destination directory does not exist (FileNotFoundError in pm/filesystem.is_junction) `type/bug` `duplicate` `comp/cli` `comp/plugins` `P3` `sweeper:risk-platform-windows` `platform/windows` `area/install-update` `Plugin Catalog` 💬1
- [#139532](https://github.com/NousResearch/hermes-agent/issues/139532) [Bug]: a gateway restart mid-turn fences the turn 'unknown' and silently blocks the whole session - the next user message queues forever, and there is no in-app way to resolve it `type/bug` `comp/gateway` `P2` `sweeper:risk-session-state` `comp/desktop` `area/sessions`
- [#139526](https://github.com/NousResearch/hermes-agent/issues/139526) [Bug]: opencode-go gemini-4-argon-contributor routed to /v1/chat/completions → HTTP 400 ModelProtocolUnsupported (Go Gemini needs the native wire) `type/bug` `comp/agent` `comp/plugins` `provider/gemini` `P3`

### 🔒 Closed Issues
- [#138908](https://github.com/NousResearch/hermes-agent/issues/138908) [Bug]: groups.log violates its wire contract — RoomActor is missing profile/display_name/connection_id
- [#137646](https://github.com/NousResearch/hermes-agent/issues/137646) [Bug]: `hermes update` refuses the stable channel when the release commit is not local (10 s ancestry probe times out)
- [#139514](https://github.com/NousResearch/hermes-agent/issues/139514) __release_date__ is frozen at "2026.9.24", so --version and the startup banner disclose a stale date

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,984 · **Open issues:** 996 · **Last push:** 2h ago

### ✅ Merged PRs
- [#11755](https://github.com/zeroclaw-labs/zeroclaw/pull/11755) fix(deps): patch Wasmtime and Rustls security advisories

### 🐛 New Issues
- [#11773](https://github.com/zeroclaw-labs/zeroclaw/issues/11773) [Bug]: Regional OS locales (fr_FR, es_ES, ja_JP) fall back to English
- [#11771](https://github.com/zeroclaw-labs/zeroclaw/issues/11771) Bootstrap file cap differs between gateway turns (20,000) and channel/agent-loop turns (6,000 with compact_context); doctor reports one
- [#11769](https://github.com/zeroclaw-labs/zeroclaw/issues/11769) [Bug]: Voice-drop and model-fallback channel tests depend on the operator locale
- [#11768](https://github.com/zeroclaw-labs/zeroclaw/issues/11768) Honor the HTTP Retry-After response header for provider 429s
- [#11764](https://github.com/zeroclaw-labs/zeroclaw/issues/11764) [Bug]: WhatsApp Web drops an untranscribed voice note without telling the sender
- [#11761](https://github.com/zeroclaw-labs/zeroclaw/issues/11761) [Bug]: Email channel misses mail that lands during a fetch until the IMAP IDLE timeout
- [#11760](https://github.com/zeroclaw-labs/zeroclaw/issues/11760) [Bug]: Email channel answers live mail again after a restart (active mode never sets \Seen)
- [#11758](https://github.com/zeroclaw-labs/zeroclaw/issues/11758) [Bug]: WhatsApp Web keeps printing pairing QR codes after its listener stops
- [#11753](https://github.com/zeroclaw-labs/zeroclaw/issues/11753) [Feature]: Configurable acknowledgement reactions (in-progress / done / error emoji) 💬1
- [#11751](https://github.com/zeroclaw-labs/zeroclaw/issues/11751) [Feature]: Email channel: trust an extra CA for IMAP and SMTP (tls_ca_cert_path) 💬1
- [#11749](https://github.com/zeroclaw-labs/zeroclaw/issues/11749) [Bug]: Email channel answers automatic mail (auto-replies, bounces, lists), risking mail loops 💬1
- [#11747](https://github.com/zeroclaw-labs/zeroclaw/issues/11747) [Feature]: Email channel: send over SMTP with STARTTLS (Office 365, port 587) 💬1
- [#11745](https://github.com/zeroclaw-labs/zeroclaw/issues/11745) [Bug]: Email channel does not store inbound attachments as the docs say 💬1

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,657 · **Open issues:** 1,551 · **Last push:** 2d ago

### 🐛 New Issues
- [#8138](https://github.com/nearai/ironclaw/issues/8138) Daily ironclaw failure taxonomy — 2026-10-15

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,889 · **Open issues:** 114 · **Last push:** 23d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 1d ago
- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬1 · 7d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 10d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 18d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 20d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 30d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 38d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 40d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 48d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 52d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] An Update On Independent Evaluators](https://www.anthropic.com/news/an-update-on-independent-evaluators) _2026-10-15_

### OpenAI — 7 new
- [[Learn] Gpt Live 1 Webinar](https://openai.com/business/learn/gpt-live-1-webinar/) _2026-10-16_
- [[Policies] Brazil Advertising Terms](https://openai.com/policies/brazil-advertising-terms/) _2026-10-16_
- [[Index] Sullivan Cromwell](https://openai.com/index/sullivan-cromwell/) _2026-10-16_
- [[Partners] Specterops](https://openai.com/business/partners/specterops/) _2026-10-15_
- [[Partners] Trustedsec](https://openai.com/business/partners/trustedsec/) _2026-10-15_
- [[Partners] Bishop Fox](https://openai.com/business/partners/bishop-fox/) _2026-10-15_
- [[Index] Teaching Students To Think And Learn Through Questions](https://openai.com/index/teaching-students-to-think-and-learn-through-questions/) _2026-10-15_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Someone is running Qwen 27B at ~20 tok/s on a jailbroken PS5's GPU](https://reddit.com/r/LocalLLaMA/comments/1x5ak2n/someone_is_running_qwen_27b_at_20_toks_on_a/) ↑1082
- [Introducing Muse Spark Open: the most capable US open-weight model to date](https://reddit.com/r/LocalLLaMA/comments/1x6r9pz/introducing_muse_spark_open_the_most_capable_us/) ↑1027
- [nvidia/NVIDIA-Nemotron-3.5-Bolt-74B-A9B-24GB · Hugging Face](https://reddit.com/r/LocalLLaMA/comments/1x6o31q/nvidianvidianemotron35bolt74ba9b24gb_hugging_face/) ↑424
- [NVIDIA AI: So many models launching this week! And we have one of our own coming...](https://reddit.com/r/LocalLLaMA/comments/1x6ijlk/nvidia_ai_so_many_models_launching_this_week_and/) ↑319
- [nvidia/NVIDIA-Nemotron-3.5-Super-VL-120B-A12B model family released (base, NVFP4, BF16, and LiLiCorr speculative decoding)](https://reddit.com/r/LocalLLaMA/comments/1x6nl8m/nvidianvidianemotron35supervl120ba12b_model/) ↑224

### r/singularity — top 5 new
- [Interpretability might have been solved by an Open AI guy: "Neural Networks Are Already Clean"](https://reddit.com/r/singularity/comments/1x6pc0o/interpretability_might_have_been_solved_by_an/) ↑706
- [GPT-6.1 Sol examined nearly 800 mathematics papers, finding major errors in 6% and minor mistakes in another 30%. Researchers estimate 90% of its major findings are correct. As AI adoption surged, the](https://reddit.com/r/singularity/comments/1x6qczp/gpt61_sol_examined_nearly_800_mathematics_papers/) ↑478
- [Gemini 4 Argon scores 165 on the Epoch Capabilities Index (ECI), on par with Fable 5.1 (165) but behind Opus 5.5 (167) and GPT-6 Astra (166).](https://reddit.com/r/singularity/comments/1x6j76i/gemini_4_argon_scores_165_on_the_epoch/) ↑245
- [Gemini 4 argon scoring close to gpt 6 astra with less cost in arc agi](https://reddit.com/r/singularity/comments/1x6rcox/gemini_4_argon_scoring_close_to_gpt_6_astra_with/) ↑168
- [I’m really shocked that all of this progress is still happening on LLM wrappers](https://reddit.com/r/singularity/comments/1x6oh29/im_really_shocked_that_all_of_this_progress_is/) ↑165

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Babysitting continues: now you can't do openclaw gateway start/restart/stop from an SSH session?](https://reddit.com/r/openclaw/comments/1x6j7dg/babysitting_continues_now_you_cant_do_openclaw/) ↑16
- [Anyone running OpenClaw for a whole team or company? How’s it going?](https://reddit.com/r/openclaw/comments/1x6r3ra/anyone_running_openclaw_for_a_whole_team_or/) ↑2
- [How do you catch carrier overcharges you already negotiated away?](https://reddit.com/r/openclaw/comments/1x72iep/how_do_you_catch_carrier_overcharges_you_already/) ↑1
- [Saw someone burn $200 in a day when their OpenClaw loop got stuck. What's your worst agent API bill?](https://reddit.com/r/openclaw/comments/1x6wiji/saw_someone_burn_200_in_a_day_when_their_openclaw/) ↑0

### X — @openclaw
- [The world of personal agents keeps growing

Keep track of it here](https://x.com/openclaw/status/2110828915866628236) ↑0 🔁0 · recent


### X — @steipete
- [crabbox is underrated](https://x.com/steipete/status/2110795475075084471) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
