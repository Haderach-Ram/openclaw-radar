---
layout: post
title: "Ecosystem Digest — 2026-09-16"
date: 2026-09-16 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-16
*Generated 08:36 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 389,804 | 6 | 3 | 10 | 0 |
| **hermesagent** | 245,903 | 10 | 10 | 2 | 0 |
| **ZeroClaw** | 32,849 | 13 | 5 | 10 | 0 |
| **IronClaw** | 12,619 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,863 | 1 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 389,804 · **Open issues:** 7,458 · **Last push:** <1h ago

### ✅ Merged PRs
- [#148852](https://github.com/openclaw/openclaw/pull/148852) fix(discord): route slash commands from raw channel ids
- [#149610](https://github.com/openclaw/openclaw/pull/149610) fix(plugins): use vendor logos and one consistent OpenClaw icon
- [#148209](https://github.com/openclaw/openclaw/pull/148209) feat(android): switch saved gateways from the sidebar
- [#149613](https://github.com/openclaw/openclaw/pull/149613) fix(ci): stop spawn fallback proof from taking 25 minutes
- [#148979](https://github.com/openclaw/openclaw/pull/148979) fix(ci): avoid full-suite fallback for Docker tooling changes
- [#149594](https://github.com/openclaw/openclaw/pull/149594) fix(ui): preserve pacing when duplicating or editing automations
- [#149405](https://github.com/openclaw/openclaw/pull/149405) fix(chat): show saved interrupted replies only once
- [#149105](https://github.com/openclaw/openclaw/pull/149105) refactor(text): reuse quote state for XML tag scanning
- [#149314](https://github.com/openclaw/openclaw/pull/149314) improve(startup): reduce Gateway readiness work
- [#149489](https://github.com/openclaw/openclaw/pull/149489) chore(cron): verify allowlists with both live harnesses

### 🐛 New Issues
- [#149620](https://github.com/openclaw/openclaw/issues/149620) Update failure: unexpected-error (2026.9.4) `P0` `issue-rating: 🦪 silver shellfish` `impact:ux-release-blocker` 💬1
- [#149619](https://github.com/openclaw/openclaw/issues/149619) WebUI: older-history loading briefly shifts retained messages by 82.5 px `maintainer` `P2` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬2
- [#149618](https://github.com/openclaw/openclaw/issues/149618) WebUI: Show earlier loses keyboard focus while loading older messages `P2` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬2
- [#149612](https://github.com/openclaw/openclaw/issues/149612) Provider plugin reload can leave session lane stuck after aborting an in-flight run `bug` `gateway` `maintainer` `P1` `impact:session-state` `issue-rating: 🦪 silver shellfish` 💬1
- [#149611](https://github.com/openclaw/openclaw/issues/149611) memory sync (watch) fires embed storm after 2026.9.4 upgrade - 100+ embed calls, 38 failures, no backoff `P2` `clawsweeper:needs-info` `impact:session-state` `issue-rating: 🦐 gold shrimp` 💬1
- [#149602](https://github.com/openclaw/openclaw/issues/149602) [Bug]: Slack native Stop rejects channel-admitted users with command authorization error `bug` `bug:behavior` `P2` `clawsweeper:needs-info` `impact:security` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#148205](https://github.com/openclaw/openclaw/issues/148205) [Feature]: Switch saved Gateways from the Android sidebar
- [#148975](https://github.com/openclaw/openclaw/issues/148975) [Bug]: Docker tooling changes trigger full-suite CI fallback
- [#149471](https://github.com/openclaw/openclaw/issues/149471) LiteLLM model discovery requests /v1/v1/models and fails when baseUrl ends in /v1

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 245,903 · **Open issues:** 43,213 · **Last push:** <1h ago

### ✅ Merged PRs
- [#112267](https://github.com/NousResearch/hermes-agent/pull/112267) fix(tui_gateway): bot mailbox poll no longer floods the log on installs that never received a delivery (#111719, supersedes #111733)
- [#112500](https://github.com/NousResearch/hermes-agent/pull/112500) Kanban workers on a rate-limit/billing wall exit 75 instead of rc=0 protocol violations (#101800, #48000, salvage #110917)

### 🐛 New Issues
- [#112550](https://github.com/NousResearch/hermes-agent/issues/112550) One-shot jobs inherit source=tui and clutter WebUI/TUI session lists
- [#112548](https://github.com/NousResearch/hermes-agent/issues/112548) Follow-up to #110677: resolve_response/cancel race, old-client full-deadline stall, and a doc misname
- [#112544](https://github.com/NousResearch/hermes-agent/issues/112544) Bug Report: Intermittent Desktop Upgrade Failure — rcedit "Unable to commit changes"
- [#112541](https://github.com/NousResearch/hermes-agent/issues/112541) [Bug]: Durable jobs stay falsely active instead of resume, one requeue, or visible stop 💬3
- [#112538](https://github.com/NousResearch/hermes-agent/issues/112538) Windows: Desktop profile delete fails with WinError 32 on logs/.__agent.lock held by the deleting serve process
- [#112535](https://github.com/NousResearch/hermes-agent/issues/112535) Tool-loop guardrail: hard_stop_enabled defaults False — identical-call loops never block (observed ~500x)
- [#112529](https://github.com/NousResearch/hermes-agent/issues/112529) [Bug]: SSRF guard rejects every fetch on a TUN proxy host with fake-ip DNS (198.18.0.0/15)
- [#112527](https://github.com/NousResearch/hermes-agent/issues/112527) [Bug]: A messaging-gateway session that never ends is never committed to OpenViking — the growing batch eventually makes extraction impossible
- [#112525](https://github.com/NousResearch/hermes-agent/issues/112525) [Bug]: fallback to provider=moa keeps the preset name as agent.model — the resolved aggregator slug is discarded 💬1
- [#112522](https://github.com/NousResearch/hermes-agent/issues/112522) [Bug]: hermes update — transient ImportError (cannot import file_signature from utils) in gateway-restart phase and atexit cleanup

### 🔒 Closed Issues
- [#87093](https://github.com/NousResearch/hermes-agent/issues/87093) [Setup]: Debian installation broken; uv.lock & npm install failed
- [#111698](https://github.com/NousResearch/hermes-agent/issues/111698) whatsapp setup fails: scripts/whatsapp-bridge/ missing from pip wheel (v2026.7.20 / 0.19.0)
- [#111719](https://github.com/NousResearch/hermes-agent/issues/111719) [Bug]: Bot delivery poll runs ~2×/minute on average although no bots are configured (8,838 warnings, 91.5% of all warnings)
- [#112296](https://github.com/NousResearch/hermes-agent/issues/112296) [Bug]: Desktop SSH says the remote lacks --ssh-session-token-file when the capability probe simply failed, so users update the wrong machine
- [#112534](https://github.com/NousResearch/hermes-agent/issues/112534) [Bug]: probe_api_models crashes on bare array /models responses (Together.ai etc.)
- [#112060](https://github.com/NousResearch/hermes-agent/issues/112060) [Bug]: Higgsfield MCP OAuth issuer mismatch; device-code flow cannot be selected
- [#111689](https://github.com/NousResearch/hermes-agent/issues/111689) [Bug]: `hermes update` respawns a launchd-supervised dashboard detached; the launchd job then fails on "port already in use" forever (macOS)
- [#111896](https://github.com/NousResearch/hermes-agent/issues/111896) Slack: same thread rebinds to a different session key after gateway restart (dm vs thread layout), orphaning the handoff-ed session and losing context
- [#111999](https://github.com/NousResearch/hermes-agent/issues/111999) [Bug]: Phantom-Sessions (source=unknown) - Network-Error-Recovery creates orphan session records instead of continuing in the original session
- [#110912](https://github.com/NousResearch/hermes-agent/issues/110912) Nous Portal: full/list price charged on some model routes (glm/glm-flash/kimi) while subscription credits active — likely a discount-route bug, not credit exhaustion

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,849 · **Open issues:** 795 · **Last push:** 1h ago

### ✅ Merged PRs
- [#9876](https://github.com/zeroclaw-labs/zeroclaw/pull/9876) feat(zerocode): report turn state to the terminal over OSC title and progress
- [#9324](https://github.com/zeroclaw-labs/zeroclaw/pull/9324) feat(a2a): outbound client config, shared wire-model, tools (#9106)
- [#10840](https://github.com/zeroclaw-labs/zeroclaw/pull/10840) feat(docs): generate llms.txt and llms-full.txt in the mdBook build
- [#9997](https://github.com/zeroclaw-labs/zeroclaw/pull/9997) feat(channels/telegram): add secure model picker
- [#10125](https://github.com/zeroclaw-labs/zeroclaw/pull/10125) test(config): isolate process-environment fixtures
- [#10378](https://github.com/zeroclaw-labs/zeroclaw/pull/10378) fix(i18n): localize ZeroCode config metadata
- [#9109](https://github.com/zeroclaw-labs/zeroclaw/pull/9109) feat(providers): add native Hailo-Ollama support
- [#10236](https://github.com/zeroclaw-labs/zeroclaw/pull/10236) fix(desktop): bound daemon capture logs
- [#10252](https://github.com/zeroclaw-labs/zeroclaw/pull/10252) feat(memory): add category-scoped cross-agent grants
- [#9772](https://github.com/zeroclaw-labs/zeroclaw/pull/9772) feat(telegram): add per_user_session toggle for shared group-chat sessions

### 🐛 New Issues
- [#10897](https://github.com/zeroclaw-labs/zeroclaw/issues/10897) [Bug]: daemon::tests::supervisor_preserves_component_error_chain flakes under parallel nextest (global log-broadcast race) `bug`
- [#10893](https://github.com/zeroclaw-labs/zeroclaw/issues/10893) [Feature]: steer the in-flight turn when a message arrives mid-generation (wire channel dispatch to the steering pipeline)
- [#10892](https://github.com/zeroclaw-labs/zeroclaw/issues/10892) [Feature]: Publish canonical config generations and track per-target apply results `enhancement`
- [#10891](https://github.com/zeroclaw-labs/zeroclaw/issues/10891) [Feature]: Carry channel provenance through runtime admission and steering `enhancement`
- [#10889](https://github.com/zeroclaw-labs/zeroclaw/issues/10889) [Bug]: native Anthropic provider drops the rolling cache breakpoint when the last message ends with an image block `bug` `provider` `provider:anthropic` `priority:p2` `status:accepted` `follow-up` `risk:medium` 💬2
- [#10887](https://github.com/zeroclaw-labs/zeroclaw/issues/10887) [Bug]: Non-vision capability gate fails the turn on marker-shaped prose that references no loadable image `bug` `agent` `provider` `runtime` `priority:p2` `status:accepted` `follow-up` `risk:high` 💬1
- [#10885](https://github.com/zeroclaw-labs/zeroclaw/issues/10885) [Bug]: tool-returned images disappear after an unrelated tool call within the same turn `bug` `provider` `runtime` `provider:anthropic` `priority:p2` `status:accepted` `follow-up` `zerocode` `risk:high` 💬3
- [#10884](https://github.com/zeroclaw-labs/zeroclaw/issues/10884) [Bug]: Streaming clients hard-code a 300s idle timeout that `timeout_secs` cannot raise; slow-first-token turns die as "provider timed out" `bug` `config` `provider` `provider:openai` `provider:compatible` `priority:p1` `status:in-progress` `status:accepted` `follow-up` `risk:medium`
- [#10883](https://github.com/zeroclaw-labs/zeroclaw/issues/10883) [Bug]: Telegram media-group listener tests time out under the repeated parallel runtime job `bug` `ci` `channel` `tests` `channel:telegram` `priority:p1` `status:accepted` `risk:medium` 💬1
- [#10878](https://github.com/zeroclaw-labs/zeroclaw/issues/10878) [Feature]: Combine ZeroCode Sessions, Queue, and Plan into one resizable dock `enhancement` `priority:p2` `status:in-progress` `status:accepted` `risk:medium` `zerocode`
- [#10876](https://github.com/zeroclaw-labs/zeroclaw/issues/10876) [Bug]: gateway config writes to auth sections are reported saved but never reach the RPC authorization authority until daemon reload `bug` `config` `daemon` `gateway` `runtime` `security` `domain:security` `priority:p1` `status:blocked` `status:accepted` `follow-up` `risk:high` `cli` 💬1
- [#10875](https://github.com/zeroclaw-labs/zeroclaw/issues/10875) [Bug]: Flaky: Telegram media-group tests fail the Parallel Runtime Test repeat step on unrelated PRs `bug` `ci` `channel` `tests` `channel:telegram` `priority:p1` `status:in-progress` `status:accepted` `risk:low` `type:test` 💬1
- [#10869](https://github.com/zeroclaw-labs/zeroclaw/issues/10869) [Bug]: Avoid repeated full parsing of specialized ZeroCode tool inputs `bug` `tool` `priority:p2` `status:accepted` `follow-up` `risk:medium` `zerocode` 💬1

### 🔒 Closed Issues
- [#10272](https://github.com/zeroclaw-labs/zeroclaw/issues/10272) [Bug]: correlate Hailo log assertions under parallel tests
- [#9253](https://github.com/zeroclaw-labs/zeroclaw/issues/9253) [Feature]: add a bounded native Hailo-Ollama text provider
- [#10888](https://github.com/zeroclaw-labs/zeroclaw/issues/10888) [Bug]: stale tool-result image strip rewrites the message on its second request and invalidates the cache prefix from that point
- [#9601](https://github.com/zeroclaw-labs/zeroclaw/issues/9601) ci(security): diagnose missing Dependabot PRs for transitive Cargo alerts
- [#9503](https://github.com/zeroclaw-labs/zeroclaw/issues/9503) bug(zerocode): clean up reconnect-spawned daemon children

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,619 · **Open issues:** 1,524 · **Last push:** 2d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,863 · **Open issues:** 84 · **Last push:** 1d ago

### 🐛 New Issues
- [#205](https://github.com/moltis-org/moltis/issues/205) [Feature]: Allow setting body parameters for custom OpenAI endpoints (and per-model) `enhancement` 💬2

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 23h ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 8d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 10d ago
- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬2 · 14d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 17d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 18d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 22d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 34d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 37d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 40d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 2 new
- [[Partners] Exl Service](https://openai.com/business/partners/exl-service/) _2026-09-16_
- [[Form] Sponsored Agents Hubspot](https://openai.com/form/sponsored-agents-hubspot/) _2026-09-15_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/singularity — top 2 new
- [TIME's latest cover](https://reddit.com/r/singularity/comments/1wh2i82/times_latest_cover/) ↑1281
- [Dario, we are looking at you.](https://reddit.com/r/singularity/comments/1whhhfr/dario_we_are_looking_at_you/) ↑365

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Qwen3.8-27B + OpenClaw is amazing](https://reddit.com/r/openclaw/comments/1wh8pe8/qwen3827b_openclaw_is_amazing/) ↑34
- [Openclaw with deepseek is amazing 🤗](https://reddit.com/r/openclaw/comments/1wh9zpf/openclaw_with_deepseek_is_amazing/) ↑7
- [Agentic toolbar - new plugin Colai Toolbar](https://reddit.com/r/openclaw/comments/1wgupyy/agentic_toolbar_new_plugin_colai_toolbar/) ↑6
- [Building a local AI assistant with OpenClaw, Hugging Face, NVIDIA and Ant Ling | Live webinar Sept 16/17](https://reddit.com/r/openclaw/comments/1wgobfe/building_a_local_ai_assistant_with_openclaw/) ↑5
- [motive.md - like kickstarter + BOINC for shared agent goals... focusing on math problems and expanding. just give an agent a skill.md and it starts contributing](https://reddit.com/r/openclaw/comments/1wh3jgk/motivemd_like_kickstarter_boinc_for_shared_agent/) ↑3

### X — @openclaw
- [Build your own local AI assistant 🦞

Join us, 
@huggingface
, 
@NVIDIAAI
 and 
@AntLingAGI
 for a practical session on L](https://x.com/openclaw/status/2099693949623689651) ↑0 🔁0 · recent


### X — @steipete
- [Excited to have you on board, Graham!](https://x.com/steipete/status/2099960081207242808) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
