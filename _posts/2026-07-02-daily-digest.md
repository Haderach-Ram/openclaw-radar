---
layout: post
title: "Ecosystem Digest — 2026-07-02"
date: 2026-07-02 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-07-02
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 381,348 | 6 | 3 | 10 | 0 |
| **hermesagent** | 207,327 | 6 | 5 | 7 | 1 |
| **ZeroClaw** | 32,112 | 10 | 3 | 10 | 0 |
| **IronClaw** | 12,493 | 15 | 5 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 381,348 · **Open issues:** 6,748 · **Last push:** <1h ago

### ✅ Merged PRs
- [#98843](https://github.com/openclaw/openclaw/pull/98843) docs: update mobile app release messaging
- [#98093](https://github.com/openclaw/openclaw/pull/98093) fix(core): propagate caller env PATHEXT through isExecutableFile on Windows
- [#98811](https://github.com/openclaw/openclaw/pull/98811) feat(ios): modernize navigation and settings
- [#98818](https://github.com/openclaw/openclaw/pull/98818) fix(ci): recover incomplete Swift build caches
- [#98787](https://github.com/openclaw/openclaw/pull/98787) fix(memory-wiki): retry transient existing-page reads in wiki_apply and chatgpt import
- [#98720](https://github.com/openclaw/openclaw/pull/98720) fix(nostr): clear per-relay publish timeout timer to prevent dangling handles
- [#98689](https://github.com/openclaw/openclaw/pull/98689) fix(wizard): reject loose gateway port input
- [#97889](https://github.com/openclaw/openclaw/pull/97889) fix(discord): guard JSON.parse against malformed API response bodies
- [#98812](https://github.com/openclaw/openclaw/pull/98812) fix(codex): preserve plugin app approvals in side conversations
- [#92283](https://github.com/openclaw/openclaw/pull/92283) fix(agents): don't inject A2A turns into isolated-cron sessions_send (#92257)

### 🐛 New Issues
- [#98842](https://github.com/openclaw/openclaw/issues/98842) Externalized plugins lose non-gateway-auth public artifacts (doctor/secret/message-tool/thread-binding/media/health) on packaged installs `maintainer` 💬1
- [#98825](https://github.com/openclaw/openclaw/issues/98825) bug(llm): tool-result replay can drop non-array output content `P2` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#98814](https://github.com/openclaw/openclaw/issues/98814) [Bug]: Direct-session compaction inherits OpenAI OAuth profile and fails OpenAI Responses API-key auth `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:session-state` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#98807](https://github.com/openclaw/openclaw/issues/98807) [Feature]: Show which model was used in each reply `enhancement` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `impact:auth-provider` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#98805](https://github.com/openclaw/openclaw/issues/98805) [Feature]: Refresh Workboard from live change events `enhancement` `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `impact:session-state` `issue-rating: 🌊 off-meta tidepool` `maturity:stable` 💬1
- [#98799](https://github.com/openclaw/openclaw/issues/98799) [Bug]: install.sh: config set channels --json overwrites existing channel configs (missing --merge) `bug` `bug:crash` `P2` `impact:data-loss` `impact:message-loss` `maturity:stable` 💬1

### 🔒 Closed Issues
- [#98803](https://github.com/openclaw/openclaw/issues/98803) [Feature]: Modernize iOS navigation and settings hierarchy
- [#98827](https://github.com/openclaw/openclaw/issues/98827) Gateway 2026.6.1 OOM crash-loop from .usage-cost-cache.json bloat during Android Realtime Talk (repro of #95379)
- [#98820](https://github.com/openclaw/openclaw/issues/98820) Bug: Official iOS app — messages delivered but no response (session routing + client ID collision)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 207,327 · **Open issues:** 24,749 · **Last push:** 1h ago

### 🚀 New Releases
- [v2026.7.1](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.7.1) — Hermes Agent v0.18.0 (2026.7.1) — The Judgment Release

### ✅ Merged PRs
- [#56714](https://github.com/NousResearch/hermes-agent/pull/56714) fix(moa): lift hidden Anthropic aux output cap
- [#56713](https://github.com/NousResearch/hermes-agent/pull/56713) fix(streaming): handle completed responses with empty/None choices (#55933)
- [#56582](https://github.com/NousResearch/hermes-agent/pull/56582) security(terminal): strip VERTEX_CREDENTIALS_PATH/GOOGLE_APPLICATION_CREDENTIALS from subprocess env
- [#56680](https://github.com/NousResearch/hermes-agent/pull/56680) security(vertex): route credential/project/region resolution through the profile secret scope
- [#56605](https://github.com/NousResearch/hermes-agent/pull/56605) fix(discord): ignore reply-ping-only mentions for bot-authored messages
- [#56664](https://github.com/NousResearch/hermes-agent/pull/56664) fix(browser): apply private-page guard to raw CDP calls
- [#56681](https://github.com/NousResearch/hermes-agent/pull/56681) fix(agent): honor custom CA certs for custom_providers HTTPS endpoints (main + aux)

### 🐛 New Issues
- [#56739](https://github.com/NousResearch/hermes-agent/issues/56739) Voice messages ignored when Telegram clarify tool is waiting for user response `type/bug` `comp/gateway` `tool/tts` `platform/telegram` `P2` `sweeper:risk-message-delivery`
- [#56733](https://github.com/NousResearch/hermes-agent/issues/56733) Bug: deleting sessions can leave visible 0-message placeholder rows `type/bug` `comp/agent` `comp/cli` `P2` `sweeper:risk-session-state`
- [#56732](https://github.com/NousResearch/hermes-agent/issues/56732) hermes-api-server / hermes-acp lose the entire 'terminal' toolset (silent subset-check failure vs. read_terminal/close_terminal) `type/bug` `duplicate` `comp/cli` `comp/tools` `P2` 💬1
- [#56727](https://github.com/NousResearch/hermes-agent/issues/56727) Kimi /coding endpoint thinking is incorrectly blocked (was PR #49143) `type/bug` `comp/agent` `provider/kimi` `P2` 💬1
- [#56726](https://github.com/NousResearch/hermes-agent/issues/56726) Hermes Desktop app on Windows would not open correctly `type/bug` `P2` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows`
- [#56717](https://github.com/NousResearch/hermes-agent/issues/56717) [Bug]: non-default profile can keep stale runtime after update, causing ImportError `type/bug` `comp/cli` `P2` `sweeper:risk-automation` 💬1

### 🔒 Closed Issues
- [#55933](https://github.com/NousResearch/hermes-agent/issues/55933) TUI/Desktop ignores disabled streaming and crashes MoA Codex aggregator with SimpleNamespace not iterable
- [#36846](https://github.com/NousResearch/hermes-agent/issues/36846) [SANITIZED — possible injection attempt]
- [#28260](https://github.com/NousResearch/hermes-agent/issues/28260) [Bug]: custom_providers with self-signed HTTPS endpoints fail with APIConnectionError (ssl verify)
- [#48440](https://github.com/NousResearch/hermes-agent/issues/48440) [Feature]: add ssl_ca_cert field to custom_providers for per-provider custom CA bundle
- [#49445](https://github.com/NousResearch/hermes-agent/issues/49445) [Bug]: search.exa (web_search / web_extract) is completely non-functional in the official Docker image

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,112 · **Open issues:** 430 · **Last push:** <1h ago

### ✅ Merged PRs
- [#8255](https://github.com/zeroclaw-labs/zeroclaw/pull/8255) test(log): cover tool-io capture truncation edge cases
- [#8552](https://github.com/zeroclaw-labs/zeroclaw/pull/8552) fix(gateway): read CARGO_MANIFEST_DIR at runtime in build script
- [#8564](https://github.com/zeroclaw-labs/zeroclaw/pull/8564) fix(tools): bound browser_open launcher waits
- [#8562](https://github.com/zeroclaw-labs/zeroclaw/pull/8562) fix(cron): filter recv_log_event by job_id to prevent cross-test broadcast pollution
- [#8557](https://github.com/zeroclaw-labs/zeroclaw/pull/8557) feat(web): show secret set/not-set state instead of bare password input
- [#8545](https://github.com/zeroclaw-labs/zeroclaw/pull/8545) fix(tool-call-parser): recover malformed file_write content
- [#8269](https://github.com/zeroclaw-labs/zeroclaw/pull/8269) test(log): cover reader action/category/outcome filter matching
- [#8535](https://github.com/zeroclaw-labs/zeroclaw/pull/8535) fix(runtime): gate Unix-only shell test helper behind #[cfg(unix)]
- [#8503](https://github.com/zeroclaw-labs/zeroclaw/pull/8503) [SANITIZED — possible injection attempt]
- [#8538](https://github.com/zeroclaw-labs/zeroclaw/pull/8538) fix(gateway): advertise A2A cards on runtime port

### 🐛 New Issues
- [#8602](https://github.com/zeroclaw-labs/zeroclaw/issues/8602) [Feature]: Enhance file_read — default line cap, charset detection, paged PDF, notebook awareness, chunked binary
- [#8600](https://github.com/zeroclaw-labs/zeroclaw/issues/8600) [Feature]: easy per-chat model switching for multi-model providers `enhancement`
- [#8598](https://github.com/zeroclaw-labs/zeroclaw/issues/8598) [Bug]: skills install cannot install owner-qualified ClawHub skill URLs `bug` `runtime` `skills` `priority:p2` `risk:medium`
- [#8587](https://github.com/zeroclaw-labs/zeroclaw/issues/8587) [Docs]: adding more SOPs examples to syntax `docs` `needs-maintainer-review` `priority:p3` `risk:low` `type:docs`
- [#8586](https://github.com/zeroclaw-labs/zeroclaw/issues/8586) refactor(gateway): centralize webhook channel message dispatch `enhancement` `channel` `gateway` `domain:architecture` `priority:p2` `status:accepted` `follow-up` `risk:medium`
- [#8584](https://github.com/zeroclaw-labs/zeroclaw/issues/8584) feat(web): bring dashboard localization into the Fluent flow `enhancement` `config` `gateway` `priority:p2` `status:accepted` `follow-up` `risk:medium` `web`
- [#8583](https://github.com/zeroclaw-labs/zeroclaw/issues/8583) [Tracker]: channel/source shared-boundary cleanup and orchestrator line-culling `enhancement` `channel` `gateway` `runtime` `domain:architecture` `priority:p2` `status:accepted` `status:no-stale` `follow-up` `risk:medium`
- [#8581](https://github.com/zeroclaw-labs/zeroclaw/issues/8581) feat(sop): centralize SOP ingress adapters for fan-in sources `enhancement` `channel` `runtime` `domain:architecture` `priority:p2` `status:accepted` `follow-up` `risk:medium` 💬1
- [#8578](https://github.com/zeroclaw-labs/zeroclaw/issues/8578) [Bug]: On failure to start it doesn't terminate the process `bug` `runtime` `priority:p2` `status:in-progress` `risk:medium` `zerocode`
- [#8568](https://github.com/zeroclaw-labs/zeroclaw/issues/8568) [Feature]: Mixture-of-Agents (MoA) virtual model provider `enhancement` `config` `gateway` `observability` `provider` `runtime` `domain:architecture` `priority:p2` `type:rfc` `status:accepted` `risk:high` 💬1

### 🔒 Closed Issues
- [#8556](https://github.com/zeroclaw-labs/zeroclaw/issues/8556) [Feature]: secret fields should show set/not-set state instead of a bare password input
- [#8528](https://github.com/zeroclaw-labs/zeroclaw/issues/8528) [Feature]: Recover malformed file_write tool calls safely
- [#8530](https://github.com/zeroclaw-labs/zeroclaw/issues/8530) [SANITIZED — possible injection attempt]

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,493 · **Open issues:** 1,271 · **Last push:** <1h ago

### ✅ Merged PRs
- [#5434](https://github.com/nearai/ironclaw/pull/5434) test(reborn): add memory_search/memory_tree int-tier scenarios (T0-MEMQ)
- [#5482](https://github.com/nearai/ironclaw/pull/5482) test(reborn): int-tier coverage for trigger-management verbs (T0-TRIGGERS)
- [#5483](https://github.com/nearai/ironclaw/pull/5483) test(reborn): prove credential injection reaches the wire (T0-SECRET-INJECT)
- [#5481](https://github.com/nearai/ironclaw/pull/5481) test(reborn): system-prompt capture seam for model-visible prompt asserts
- [#5484](https://github.com/nearai/ironclaw/pull/5484) test(reborn): error/deny-path coverage for http/shell/mcp tools (T0-ERRPATHS)
- [#5440](https://github.com/nearai/ironclaw/pull/5440) test(reborn): PR-E1 seam constructors for integration coverage
- [#5498](https://github.com/nearai/ironclaw/pull/5498) fix(webui): avoid thread list refetch on send
- [#5441](https://github.com/nearai/ironclaw/pull/5441) fix(reborn): add header notifications for automation approvals
- [#5491](https://github.com/nearai/ironclaw/pull/5491) fix(webui-v2): remove duplicate chat logs header
- [#5430](https://github.com/nearai/ironclaw/pull/5430) ci(reborn): add cargo-llvm-cov integration-tier coverage job (T0-COV)

### 🐛 New Issues
- [#5512](https://github.com/nearai/ironclaw/issues/5512) WASM credential provider re-derives injection eligibility from manifest instead of consulting authorizer's Decision.obligations `reborn`
- [#5510](https://github.com/nearai/ironclaw/issues/5510) [QA] Cannot delete old routines `bug_bash_P3`
- [#5509](https://github.com/nearai/ironclaw/issues/5509) [QA] Chat creation latency scales with accumulated conversation history `bug_bash_P2`
- [#5508](https://github.com/nearai/ironclaw/issues/5508) [QA] Slack delivery target not found despite active Slack connection `bug_bash_P2`
- [#5507](https://github.com/nearai/ironclaw/issues/5507) [QA] Failed routine run shows "No thread attached" and blocks debugging `bug_bash_P2` 💬1
- [#5506](https://github.com/nearai/ironclaw/issues/5506) [QA] Slack bot redirects to WebUI instead of delivering result `bug_bash_P2`
- [#5505](https://github.com/nearai/ironclaw/issues/5505) [QA] Routine creation prompt is embedded inside the created routine `bug_bash_P1`
- [#5504](https://github.com/nearai/ironclaw/issues/5504) [QA] Routine creation hangs without returning result or error `bug_bash_P1`
- [#5500](https://github.com/nearai/ironclaw/issues/5500) Stabilize Reborn Playwright channel-connect tests in nightly workflow
- [#5495](https://github.com/nearai/ironclaw/issues/5495) Daily ironclaw failure taxonomy — 2026-07-01
- [#5479](https://github.com/nearai/ironclaw/issues/5479) Reborn one-runtime group harness: second thread with a distinct actor fails (driver_unavailable / unknown thread) — blocks E-MULTIUSER/C-MULTIUSER
- [#5477](https://github.com/nearai/ironclaw/issues/5477) ci(reborn): unify Reborn crate-family allowlist across reborn-tests.yml and reborn-coverage-summary.sh
- [#5476](https://github.com/nearai/ironclaw/issues/5476) [QA] Reborn runs fail with "could not start agent runtime" / "runner lease expired" under turn-state CAS contention + model latency
- [#5460](https://github.com/nearai/ironclaw/issues/5460) [QA] Memories in the WebUI workspace are visible to every user in the workspace
- [#5459](https://github.com/nearai/ironclaw/issues/5459) Configurable skills and tools 💬1

### 🔒 Closed Issues
- [#5443](https://github.com/nearai/ironclaw/issues/5443) Add header notifications for newly triggered automation tasks
- [#5458](https://github.com/nearai/ironclaw/issues/5458) [QA] Double header displayed on Logs page
- [#5457](https://github.com/nearai/ironclaw/issues/5457) [QA] Logs page remains empty and never loads log entries
- [#5289](https://github.com/nearai/ironclaw/issues/5289) [Reborn] Run ends with generic "driver protocol error" after builtin.json invalid_input failure
- [#5246](https://github.com/nearai/ironclaw/issues/5246) [Reborn] Add global auto-approve shortcut text under approval checkbox

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬2 · 1d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 2d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 2d ago
- ⚫ [#94780](https://github.com/openclaw/openclaw/issues/94780) [Feature]: Per-cron model selection independent of agent default — run cheap/free models on automation jobs while keeping main agent on premium LLM — 💬1 · 6d ago
- ⚫ [#93032](https://github.com/openclaw/openclaw/issues/93032) [Bug] v2026.6.6: Cron scheduler loads 0 jobs after upgrade — SQLite WAL not committed at first startup — 💬2 · 6d ago
- ⚫ [#92974](https://github.com/openclaw/openclaw/issues/92974) Bug: v2026.6.6 getAttributionHeaders() crashes on Bedrock models — baseUrl undefined (null-guard missing) — 💬1 · 6d ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬4 · 8d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬7 · 9d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 10d ago
- 🟢 [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬1 · 10d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Redeploying Fable 5](https://www.anthropic.com/news/redeploying-fable-5) _2026-07-01_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [We're probably going to need that soon.](https://reddit.com/r/LocalLLaMA/comments/1uht2m0/were_probably_going_to_need_that_soon/) ↑3582
- [on Dario’s statement](https://reddit.com/r/LocalLLaMA/comments/1uj2yym/on_darios_statement/) ↑3269
- [Effect of GLM 5.2 !!](https://reddit.com/r/LocalLLaMA/comments/1uiv8e4/effect_of_glm_52/) ↑3251
- [The number 1 public enemy of open-source.](https://reddit.com/r/LocalLLaMA/comments/1ui241x/the_number_1_public_enemy_of_opensource/) ↑2698
- [NPC Engine Using Local Models](https://reddit.com/r/LocalLLaMA/comments/1uibt9o/npc_engine_using_local_models/) ↑1744

### r/singularity — top 5 new
- [Anthropic is on a mission rn to make AGI team](https://reddit.com/r/singularity/comments/1ukuahd/anthropic_is_on_a_mission_rn_to_make_agi_team/) ↑832
- [Scientists say they have built a cell from scratch for the first time that can feed, grow and replicate like a natural cell](https://reddit.com/r/singularity/comments/1ukr5zv/scientists_say_they_have_built_a_cell_from/) ↑475
- [Fable 5 will divert coding to Opus 4.8 according to Anthropic](https://reddit.com/r/singularity/comments/1ukbtjm/fable_5_will_divert_coding_to_opus_48_according/) ↑469
- [Claude Sonnet 5 is both more expensive and less intelligent than Opus 4.8, on Artificial Analysis Index](https://reddit.com/r/singularity/comments/1uk22hk/claude_sonnet_5_is_both_more_expensive_and_less/) ↑441
- [Fable 5 when it sees a for loop](https://reddit.com/r/singularity/comments/1ukgv60/fable_5_when_it_sees_a_for_loop/) ↑341

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [used openclaw to untangle my finances before my wife started asking questions - it caught a sketchy script i almost ran](https://reddit.com/r/openclaw/comments/1uky47d/used_openclaw_to_untangle_my_finances_before_my/) ↑7
- [OpenClaw vs Hermes Agent... what's actually different?](https://reddit.com/r/openclaw/comments/1ul2g9v/openclaw_vs_hermes_agent_whats_actually_different/) ↑3
- [has anyone agents used rentahuman?](https://reddit.com/r/openclaw/comments/1ukqy61/has_anyone_agents_used_rentahuman/) ↑3
- [The OpenClaw Podcast - The Clawcast - Episode 2](https://reddit.com/r/openclaw/comments/1ukyie1/the_openclaw_podcast_the_clawcast_episode_2/) ↑2
- [Weeks chewing glass dialing in local models, can someone give me tips or share your experiences?](https://reddit.com/r/openclaw/comments/1ukrhww/weeks_chewing_glass_dialing_in_local_models_can/) ↑2

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
- [Just going to leave this here for the haters.](https://x.com/openclaw) ↑0 🔁0 · recent
- [Episode 2 of  OpenClaw’s official podcast


@steipete
 and 
@somalley108
 join 
@hrudolph
 and 
@Pat_Erichsen
 to discus](https://x.com/openclaw) ↑0 🔁0 · recent
- [Well this is happening..](https://x.com/openclaw) ↑0 🔁0 · recent


### X — @steipete
- [the finest crab sludge!](https://x.com/steipete) ↑0 🔁0 · recent
- [Pointed codex at some Twitter feedback on the OpenClaw iOS app and it did a first improvement pass. It's still not good,](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
