---
layout: post
title: "Ecosystem Digest — 2026-10-15"
date: 2026-10-15 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-15
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 392,035 | 4 | 3 | 10 | 0 |
| **hermesagent** | 253,820 | 6 | 2 | 10 | 2 |
| **ZeroClaw** | 32,980 | 7 | 5 | 10 | 0 |
| **IronClaw** | 12,656 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,889 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 392,035 · **Open issues:** 9,611 · **Last push:** <1h ago

### ✅ Merged PRs
- [#172717](https://github.com/openclaw/openclaw/pull/172717) fix(cron): preserve native CLI inference authority
- [#172702](https://github.com/openclaw/openclaw/pull/172702) perf(sessions): retain bounded transcript facts between turns
- [#172711](https://github.com/openclaw/openclaw/pull/172711) fix(google): keep runtime context from replacing the user request
- [#172710](https://github.com/openclaw/openclaw/pull/172710) fix: keep the Gateway responsive during reply-tagged streams (2026.9.33 backport of #166782)
- [#172698](https://github.com/openclaw/openclaw/pull/172698) fix(google): keep visible output room when Gemini thinking shares the token cap
- [#172608](https://github.com/openclaw/openclaw/pull/172608) fix(ui): keep the Models page stable while it loads
- [#172607](https://github.com/openclaw/openclaw/pull/172607) feat(agents): remember native runtime consent per agent
- [#172693](https://github.com/openclaw/openclaw/pull/172693) fix: 2026.9.33 backports — blocked-turn logging (#167595), MCP test isolation, and flake fixes from main
- [#172672](https://github.com/openclaw/openclaw/pull/172672) perf(subagents): reuse maintenance protection facts
- [#172691](https://github.com/openclaw/openclaw/pull/172691) fix(ios): retry stalled App Store screenshot processing

### 🐛 New Issues
- [#172723](https://github.com/openclaw/openclaw/issues/172723) [Bug]: Stop reports command cleanup failure during managed sandbox checkpoint 💬1
- [#172713](https://github.com/openclaw/openclaw/issues/172713) /pair qr shows "Scan this QR code" prompt but no QR code image renders in the web UI `bug` `bug:behavior` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#172708](https://github.com/openclaw/openclaw/issues/172708) [Bug]: WhatsApp status reaction ends on ❌ for a message that arrives during an active run, though the next run succeeds `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#172688](https://github.com/openclaw/openclaw/issues/172688) memory-core: prune short-term recall entries atomically when source files move or archive `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-info` `impact:session-state` `issue-rating: 🦐 gold shrimp` 💬1

### 🔒 Closed Issues
- [#172721](https://github.com/openclaw/openclaw/issues/172721) [Feature]: trajectory runtime events
- [#172712](https://github.com/openclaw/openclaw/issues/172712) [Bug]: `openclaw memory …` CLI commands spend 35–60 s capturing plugin sources on every invocation (even `--help`) on 2026.10.3
- [#172699](https://github.com/openclaw/openclaw/issues/172699) Mobile app: browser control unavailable with manual setup; /pair qr generates unreachable URL

### 🔥 Hot Issues (most commented)
- [#143524](https://github.com/openclaw/openclaw/issues/143524) [Bug]: Agent SQLite WAL grows to 1.4–2.8 GB in days despite wal_autocheckpoint=1000; blocks gateway startup (Windows, 2026.9.2/9.3) — 💬125 · 11h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 253,820 · **Open issues:** 48,881 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.22.1](https://github.com/NousResearch/hermes-agent/releases/tag/v0.22.1) — Hermes Agent v0.22.1
- [v0.22.0](https://github.com/NousResearch/hermes-agent/releases/tag/v0.22.0) — Hermes Agent v0.22.0 — The Threshold Release

### ✅ Merged PRs
- [#138668](https://github.com/NousResearch/hermes-agent/pull/138668) fix(cli): answer gateway-owned state from the gateway in classic CLI commands
- [#138667](https://github.com/NousResearch/hermes-agent/pull/138667) fix(gateway): route the Ink and Desktop requests the shared gateway refused
- [#138666](https://github.com/NousResearch/hermes-agent/pull/138666) fix(acp): restore session metadata, commands and usage on GatewayACPAgent
- [#138665](https://github.com/NousResearch/hermes-agent/pull/138665) fix(gateway): resolve local paths against the session's folder, not the daemon's
- [#138664](https://github.com/NousResearch/hermes-agent/pull/138664) fix(security): honour allowlist removals and the plugin gate on the shared gateway
- [#138624](https://github.com/NousResearch/hermes-agent/pull/138624) fix(gateway): bring the gateway and its local clients back cleanly after a restart
- [#138650](https://github.com/NousResearch/hermes-agent/pull/138650) fix(catalog): deliver the approved official plugin fixes
- [#138560](https://github.com/NousResearch/hermes-agent/pull/138560) fix(local): keep long local-model turns alive on laptops
- [#138594](https://github.com/NousResearch/hermes-agent/pull/138594) fix(gateway): a recycled PID after reboot no longer wedges the supervised gateway (#133744, salvage #138565)
- [#138428](https://github.com/NousResearch/hermes-agent/pull/138428) Small and slash-loaded skills keep a reload marker across compaction (salvage #136551)

### 🐛 New Issues
- [#138741](https://github.com/NousResearch/hermes-agent/issues/138741) [Bug]: execute_code sandbox drops the container's TZ - runs on system local time (UTC in the image), silently 8h behind terminal/cron
- [#138740](https://github.com/NousResearch/hermes-agent/issues/138740) [Feature]: session.control setters: heartbeat.set, loop.set, goal.set, goal.wait_time
- [#138738](https://github.com/NousResearch/hermes-agent/issues/138738) [Feature]: Opt-in fail-closed for plugin hooks and middleware (pre_llm_call, execution middleware)
- [#138729](https://github.com/NousResearch/hermes-agent/issues/138729) [Feature]: Kanban: a worker cannot end a turn "paused at a checkpoint" — the stop-nudge pushes it to complete/block/review `type/feature` `comp/agent` `comp/cron` `P3` `needs-decision`
- [#138727](https://github.com/NousResearch/hermes-agent/issues/138727) [Feature]: Support the OpenRouter Batch API as a transport for offline agent swarms `type/feature` `comp/agent` `provider/openrouter` `P3` `needs-decision`
- [#138716](https://github.com/NousResearch/hermes-agent/issues/138716) [Bug]: update failed, must new install `type/bug` `comp/cli` `P2` `sweeper:risk-compatibility` `bug` `area/install-update` 💬5

### 🔒 Closed Issues
- [#30649](https://github.com/NousResearch/hermes-agent/issues/30649) [Feature]: Proton Pass AI Access Tokens support (secret source backend)
- [#138632](https://github.com/NousResearch/hermes-agent/issues/138632) [Bug]: Desktop gateway file download passes a bare filename as save-dialog defaultPath; on macOS the save can land on read-only / (EROFS)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,980 · **Open issues:** 976 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11630](https://github.com/zeroclaw-labs/zeroclaw/pull/11630) test(runtime/tools): fix three tests that misread Windows path spellings
- [#11362](https://github.com/zeroclaw-labs/zeroclaw/pull/11362) fix(sop): replace SOP files that a reader holds open on Windows
- [#11361](https://github.com/zeroclaw-labs/zeroclaw/pull/11361) fix(rpc): refuse a directory attachment by type on Windows
- [#11363](https://github.com/zeroclaw-labs/zeroclaw/pull/11363) fix(sop): match directory filesystem triggers against Windows paths
- [#11365](https://github.com/zeroclaw-labs/zeroclaw/pull/11365) fix(agents): drop skill-bundle directories rooted without a drive
- [#11366](https://github.com/zeroclaw-labs/zeroclaw/pull/11366) test(multimodal): name rejected markers by platform-absolute paths
- [#11719](https://github.com/zeroclaw-labs/zeroclaw/pull/11719) feat(theme): add Oxocarbon dark theme
- [#11695](https://github.com/zeroclaw-labs/zeroclaw/pull/11695) fix(zerocode): count the dashboard's By Period costs in UTC like the tracker
- [#11452](https://github.com/zeroclaw-labs/zeroclaw/pull/11452) fix(rpc): register live channels for every session tool
- [#11462](https://github.com/zeroclaw-labs/zeroclaw/pull/11462) feat(delegate): route independent child approvals to the target operator

### 🐛 New Issues
- [#11751](https://github.com/zeroclaw-labs/zeroclaw/issues/11751) [Feature]: Email channel: trust an extra CA for IMAP and SMTP (tls_ca_cert_path)
- [#11749](https://github.com/zeroclaw-labs/zeroclaw/issues/11749) [Bug]: Email channel answers automatic mail (auto-replies, bounces, lists), risking mail loops
- [#11747](https://github.com/zeroclaw-labs/zeroclaw/issues/11747) [Feature]: Email channel: send over SMTP with STARTTLS (Office 365, port 587)
- [#11745](https://github.com/zeroclaw-labs/zeroclaw/issues/11745) [Bug]: Email channel does not store inbound attachments as the docs say
- [#11743](https://github.com/zeroclaw-labs/zeroclaw/issues/11743) [Feature]: Show the model's reasoning in Telegram and Slack streaming drafts
- [#11742](https://github.com/zeroclaw-labs/zeroclaw/issues/11742) Custom (OpenAI-compatible) providers default to text-fallback, and DSML tool markup is neither parsed nor stripped
- [#11735](https://github.com/zeroclaw-labs/zeroclaw/issues/11735) [RFC]: Bounded tool and delegate results at the turn boundary

### 🔒 Closed Issues
- [#11694](https://github.com/zeroclaw-labs/zeroclaw/issues/11694) [Bug]: ZeroCode Cost tab mixes UTC and local-day totals without saying which
- [#10225](https://github.com/zeroclaw-labs/zeroclaw/issues/10225) [Bug]: ZeroCode RPC sessions cannot reach configured channels through channel-backed tools
- [#11481](https://github.com/zeroclaw-labs/zeroclaw/issues/11481) [Bug]: ZeroCode spins at 100% CPU after terminal disconnection
- [#5808](https://github.com/zeroclaw-labs/zeroclaw/issues/5808) [Feature]: defer built-in tool schemas to reduce the fixed prompt floor
- [#11618](https://github.com/zeroclaw-labs/zeroclaw/issues/11618) [Bug]: ZeroCode drops a queued message when the daemon refuses it as SESSION_BUSY

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,656 · **Open issues:** 1,550 · **Last push:** 1d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,889 · **Open issues:** 114 · **Last push:** 22d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 6h ago
- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬1 · 6d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 9d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 17d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 19d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 29d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 37d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 39d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 47d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 51d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 2 new
- [[News] 2026 Us Midterms](https://www.anthropic.com/news/2026-us-midterms) _2026-10-14_
- [[News] Singapore Office Opening](https://www.anthropic.com/news/singapore-office-opening) _2026-10-14_

### OpenAI — 3 new
- [[Index] Sentinelone](https://openai.com/index/sentinelone/) _2026-10-14_
- [[Index] Block Ai Powered Security](https://openai.com/index/block-ai-powered-security/) _2026-10-14_
- [[Index] The Eus Next Chapter In Ai Is Agentic](https://openai.com/index/the-eus-next-chapter-in-ai-is-agentic/) _2026-10-14_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [NVIDIA Nemotron Bolt 3.5 74B A9B releases Oct. 15th](https://reddit.com/r/LocalLLaMA/comments/1x5t1tm/nvidia_nemotron_bolt_35_74b_a9b_releases_oct_15th/) ↑568
- [The AI race: China's open-weight models trail US closed models by just 7 months](https://reddit.com/r/LocalLLaMA/comments/1x5pjv7/the_ai_race_chinas_openweight_models_trail_us/) ↑373

### r/singularity — top 2 new
- [this line was written in 1960s btw, felt like he time travelled.](https://reddit.com/r/singularity/comments/1x5ty7c/this_line_was_written_in_1960s_btw_felt_like_he/) ↑2757
- [GPT-6 Astra autonomously solves 49 out of 50 unpublished theoretical physics research problems, scoring 98% at under $3 per problem. Researchers initially marked several answers wrong, only to discove](https://reddit.com/r/singularity/comments/1x5y9ue/gpt6_astra_autonomously_solves_49_out_of_50/) ↑1068

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [What are openclaw killer features that Grok Bot/Muse/dots do not have?](https://reddit.com/r/openclaw/comments/1x5q7m6/what_are_openclaw_killer_features_that_grok/) ↑15
- [How to Use OpenClaw in Your Small Business](https://reddit.com/r/openclaw/comments/1x687z4/how_to_use_openclaw_in_your_small_business/) ↑2
- [I run my AI agents 24/7 on two $26-a-month VPSes: how they're set up, and the CPU limit I had to solve first](https://reddit.com/r/openclaw/comments/1x5w00w/i_run_my_ai_agents_247_on_two_26amonth_vpses_how/) ↑1
- [Built an open source runtime firewall for autonomous agents (works with OpenClaw)](https://reddit.com/r/openclaw/comments/1x5t34s/built_an_open_source_runtime_firewall_for/) ↑1
- [Million of CMD windows](https://reddit.com/r/openclaw/comments/1x5lk4i/million_of_cmd_windows/) ↑0

### X — @openclaw
- [How to Use OpenClaw in Your Small Business


@hrudolph
 and 
@Pat_Erichsen
 talk proposals, leads and reusable skills wi](https://x.com/openclaw/status/2110534370167865792) ↑0 🔁0 · recent
- [Join us and the 
@huggingface
 team this Friday for the Open Together: AI builders unite event! 


https://
luma.com/Ope](https://x.com/openclaw/status/2110467388701597725) ↑0 🔁0 · recent
- [Live Q&A with Patrick and Hannes | The ClawCast Episode 13](https://x.com/openclaw/status/2110437902547357955) ↑0 🔁0 · recent


### X — @steipete
_No new tweets since the last digest. Most recent:_
- [6.1 Sol ultrafast >>> 6 Astra

~ same cost but whole different game with 250 tpm](https://x.com/steipete/status/2109730774593487009)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
