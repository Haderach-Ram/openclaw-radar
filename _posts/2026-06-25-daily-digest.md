---
layout: post
title: "Ecosystem Digest — 2026-06-25"
date: 2026-06-25 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-25
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 380,318 | 7 | 5 | 6 | 2 |
| **hermesagent** | 202,123 | 6 | 1 | 10 | 0 |
| **ZeroClaw** | 32,022 | 7 | 2 | 10 | 0 |
| **IronClaw** | 12,477 | 15 | 2 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 380,318 · **Open issues:** 6,589 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.11-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.6.11-beta.1) — openclaw 2026.6.11-beta.1
- [v2026.6.10](https://github.com/openclaw/openclaw/releases/tag/v2026.6.10) — openclaw 2026.6.10

### ✅ Merged PRs
- [#96615](https://github.com/openclaw/openclaw/pull/96615) fix(cron): preserve enabled-with-defaults failure alert through store roundtrip (fixes #96589) (AI-assisted)
- [#96152](https://github.com/openclaw/openclaw/pull/96152) fix(agent): emit model.usage diagnostic for HTTP ingress traffic
- [#96595](https://github.com/openclaw/openclaw/pull/96595) ci: default maturity evidence to all profile
- [#96594](https://github.com/openclaw/openclaw/pull/96594) docs: clarify maturity scorecard scoring
- [#96599](https://github.com/openclaw/openclaw/pull/96599) fix: surface provider authentication failures in channels
- [#96100](https://github.com/openclaw/openclaw/pull/96100) fix(agent): replace self-wait with deferred release in retained-lock abort cleanup

### 🐛 New Issues
- [#96611](https://github.com/openclaw/openclaw/issues/96611) [Feature]: Session archive filenames should use local timezone, not UTC `enhancement` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `issue-rating: 🐚 platinum hermit` 💬1
- [#96600](https://github.com/openclaw/openclaw/issues/96600) [SANITIZED — possible injection attempt] `bug` `bug:behavior` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:auth-provider` `issue-rating: 🦐 gold shrimp` 💬1
- [#96597](https://github.com/openclaw/openclaw/issues/96597) [SANITIZED — possible injection attempt] `enhancement` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#96593](https://github.com/openclaw/openclaw/issues/96593) WebChat: 音频附件渲染后滚动位置重置 `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#96588](https://github.com/openclaw/openclaw/issues/96588) model resolution: alias selects older version via lexicographic ordering once a family reaches double-digit minor versions `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#96586](https://github.com/openclaw/openclaw/issues/96586) [voice-call] get_status returns found:false for completed calls once evicted from in-memory manager — no fallback to persisted call store `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#96585](https://github.com/openclaw/openclaw/issues/96585) Crash: A FileHandle object was closed during garbage collection (Node.js v25) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:crash-loop` `issue-rating: 🦪 silver shellfish` 💬1

### 🔒 Closed Issues
- [#96622](https://github.com/openclaw/openclaw/issues/96622) Gateway event-loop starvation delays/drops WS response delivery to the CLI
- [#96623](https://github.com/openclaw/openclaw/issues/96623) Build pipeline bug: Feishu extension excluded from npm tarball despite fix commit in tag
- [#79274](https://github.com/openclaw/openclaw/issues/79274) Performance: openclaw security audit --deep can stall silently ~9min due to serial skills/plugins code-safety scans
- [#96617](https://github.com/openclaw/openclaw/issues/96617) [Bug] Cron jobs silently lost across multiple upgrades — fix for #90510 did not prevent recurrence
- [#96589](https://github.com/openclaw/openclaw/issues/96589) cron: failure alerts enabled with defaults (--failure-alert) silently stop firing after gateway restart

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 202,123 · **Open issues:** 23,439 · **Last push:** <1h ago

### ✅ Merged PRs
- [#52246](https://github.com/NousResearch/hermes-agent/pull/52246) fix(soul): installers seed real default persona, upgrade legacy empty SOUL.md
- [#52232](https://github.com/NousResearch/hermes-agent/pull/52232) fix(tui): route /learn through command.dispatch so the prompt fires (#51829)
- [#52243](https://github.com/NousResearch/hermes-agent/pull/52243) feat(gateway): scale-to-zero idle detection + dormant-quiesce (Phase 0)
- [#52229](https://github.com/NousResearch/hermes-agent/pull/52229) fix(desktop): stop refText crash on undefined composer attachment holes
- [#52088](https://github.com/NousResearch/hermes-agent/pull/52088) fix(telegram): gate rich draft previews separately
- [#52210](https://github.com/NousResearch/hermes-agent/pull/52210) fix(desktop): surface update progress lines
- [#47959](https://github.com/NousResearch/hermes-agent/pull/47959) Pet generation: frame-perfect hatch flow, backend picker, CPU-safe chroma, and CI-hardening
- [#52201](https://github.com/NousResearch/hermes-agent/pull/52201) fix(desktop): don't report a bogus update count for a shallow checkout
- [#52208](https://github.com/NousResearch/hermes-agent/pull/52208) fix(desktop): stop the update overlay looking frozen while it works
- [#52205](https://github.com/NousResearch/hermes-agent/pull/52205) fix(desktop): route gateway restart / status / update to the active profile

### 🐛 New Issues
- [#52255](https://github.com/NousResearch/hermes-agent/issues/52255) Desktop remote mode fails against authenticated remote gateway: backend ready, but WebSocket/API auth rejected
- [#52253](https://github.com/NousResearch/hermes-agent/issues/52253) [Feature]: [Bug]: 为什么飞书机器人和CLI展示内容不一致 `type/bug` `comp/gateway` `platform/feishu` `P2` `needs-repro`
- [#52252](https://github.com/NousResearch/hermes-agent/issues/52252) feat(gateway/telegram): generic inline action buttons on agent/scheduled messages `type/feature` `comp/gateway` `platform/telegram` `P3`
- [#52244](https://github.com/NousResearch/hermes-agent/issues/52244) Bug: Hermes Desktop / Hermes One on Windows truncates agent output messages (UTF-8 encoding issue) `type/bug` `P2` `needs-repro` `sweeper:risk-message-delivery` `comp/desktop` `platform/windows` 💬1
- [#52235](https://github.com/NousResearch/hermes-agent/issues/52235) Win桌面端最新版0.17.0（通过软件升级）在对话框中有内容的情况下按pagedown出现的问题 `type/bug` `P3` `needs-repro` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows`
- [#52228](https://github.com/NousResearch/hermes-agent/issues/52228) [SANITIZED — possible injection attempt] `type/bug` `comp/agent` `P2`

### 🔒 Closed Issues
- [#51829](https://github.com/NousResearch/hermes-agent/issues/51829) /learn slash command shows ack message but does not trigger LLM in Desktop GUI

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,022 · **Open issues:** 506 · **Last push:** 1h ago

### ✅ Merged PRs
- [#8066](https://github.com/zeroclaw-labs/zeroclaw/pull/8066) feat(observability): opt-in LLM request payload capture (default off)
- [#8065](https://github.com/zeroclaw-labs/zeroclaw/pull/8065) feat(observability): correlate logs by trace_id + record per-call cost_usd
- [#8098](https://github.com/zeroclaw-labs/zeroclaw/pull/8098) fix(config): reject creating the reserved `default` agent across all operator surfaces
- [#8214](https://github.com/zeroclaw-labs/zeroclaw/pull/8214) fix(zerocode): pause the queue when a turn is cancelled
- [#8153](https://github.com/zeroclaw-labs/zeroclaw/pull/8153) fix(channels): preserve re-loadable media refs in cached history
- [#8266](https://github.com/zeroclaw-labs/zeroclaw/pull/8266) test(memory): cover jaccard dedup and conflict filtering edge cases
- [#8262](https://github.com/zeroclaw-labs/zeroclaw/pull/8262) fix(skills): correct "ClawhHub" typo in skill installer messages
- [#8117](https://github.com/zeroclaw-labs/zeroclaw/pull/8117) test(runtime): cover whole-turn trim tool_call_id envelopes
- [#7901](https://github.com/zeroclaw-labs/zeroclaw/pull/7901) fix(runtime): bound repeated shell approval loops
- [#7931](https://github.com/zeroclaw-labs/zeroclaw/pull/7931) fix(providers): coalesce stripped compatible history roles

### 🐛 New Issues
- [#8310](https://github.com/zeroclaw-labs/zeroclaw/issues/8310) [Feature]: Remove deprecated skills prompt_injection_mode / full mode `enhancement` `skills`
- [#8309](https://github.com/zeroclaw-labs/zeroclaw/issues/8309) [Feature]: SkillForge (#144) is orphaned — wire up with safe defaults or remove? `enhancement` `skillforge`
- [#8303](https://github.com/zeroclaw-labs/zeroclaw/issues/8303) RFC: Goal mode for bounded autonomous session work
- [#8302](https://github.com/zeroclaw-labs/zeroclaw/issues/8302) [Bug]: configured mcp servers tools are not shown in the tools list `bug`
- [#8290](https://github.com/zeroclaw-labs/zeroclaw/issues/8290) [Tracker]: multi-user milestone: per-principal isolation + per-sender authz
- [#8289](https://github.com/zeroclaw-labs/zeroclaw/issues/8289) [Tracker]: OIDC milestone: pluggable AuthProvider + uniform Principal
- [#8288](https://github.com/zeroclaw-labs/zeroclaw/issues/8288) [Tracker]: sop milestone: daemon-owned SOP control plane to 5/5

### 🔒 Closed Issues
- [#8151](https://github.com/zeroclaw-labs/zeroclaw/issues/8151) [Bug]: deferred image attachment loses its re-loadable reference in cached history; bot later denies seeing it
- [#7820](https://github.com/zeroclaw-labs/zeroclaw/issues/7820) Zeroclaw repeats identical shell approval loops before bounding

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,477 · **Open issues:** 1,218 · **Last push:** <1h ago

### ✅ Merged PRs
- [#5163](https://github.com/nearai/ironclaw/pull/5163) feat(memory): model memory as a userland extension (#3537)
- [#5193](https://github.com/nearai/ironclaw/pull/5193) fix(ci): restore green main — duplicate workflow key + missed spawn_subagent test ignore
- [#5194](https://github.com/nearai/ironclaw/pull/5194) fix(reborn): recover SSE turn-event stream from rebase on reconnect
- [#5186](https://github.com/nearai/ironclaw/pull/5186) fix(reborn): localize settings labels and adjust automation filters
- [#5185](https://github.com/nearai/ironclaw/pull/5185) Fix Slack admin setup visibility for WebUI operator tokens
- [#5181](https://github.com/nearai/ironclaw/pull/5181) [SANITIZED — possible injection attempt]
- [#5143](https://github.com/nearai/ironclaw/pull/5143) Pin Telegram host-ingress verifier fail-closed
- [#5178](https://github.com/nearai/ironclaw/pull/5178) fix(reborn): skip NEAR AI MCP without durable auth storage
- [#5161](https://github.com/nearai/ironclaw/pull/5161) fix(reborn): remove legacy Slack fields from hosted config
- [#5171](https://github.com/nearai/ironclaw/pull/5171) fix: correct Reborn GitHub API requests

### 🐛 New Issues
- [#5201](https://github.com/nearai/ironclaw/issues/5201) Reborn memory: remaining #3537 milestones after the M2 lift (#5163)
- [#5200](https://github.com/nearai/ironclaw/issues/5200) Follow-up: tighten activity identity edge cases after gate lifecycle refactor
- [#5198](https://github.com/nearai/ironclaw/issues/5198) [Reborn] Approve Findings 06/22/2026 - 06/28/2026
- [#5197](https://github.com/nearai/ironclaw/issues/5197) [Reborn] Disabled tool may cause the assistant to invoke unrelated tools instead of reporting the tool is unavailable
- [#5196](https://github.com/nearai/ironclaw/issues/5196) [Reborn] "Ask each time" tool permission may fail with authorization error and trigger duplicate approval flow
- [#5192](https://github.com/nearai/ironclaw/issues/5192) [Reborn] Denying a tool approval can still lead to additional tool approval requests
- [#5191](https://github.com/nearai/ironclaw/issues/5191) [Reborn] Internal skill activation / context budget messages are exposed in chat UI
- [#5190](https://github.com/nearai/ironclaw/issues/5190) [Reborn WebUI] Invalid UI bearer token enters app but later actions do not respond `bug` `reborn` `module:M1-webui-product` `module:M4-host-kernel`
- [#5189](https://github.com/nearai/ironclaw/issues/5189) [Reborn WebUI] Successful tool runs do not show activity details while running `bug` `reborn` `module:M1-webui-product` `module:M5-events-streaming`
- [#5188](https://github.com/nearai/ironclaw/issues/5188) Improve Reborn WebUI v2 responsive sidebar behavior
- [#5184](https://github.com/nearai/ironclaw/issues/5184) Reborn startup fails when NEAR AI MCP product-auth lookup is unavailable
- [#5182](https://github.com/nearai/ironclaw/issues/5182) Reborn hosted observability: meaningful logs + failure diagnostics out of the binary `enhancement` `scope: channel/cli` 💬1
- [#5179](https://github.com/nearai/ironclaw/issues/5179) Web UI logs are not available for multi-tenancy users
- [#5173](https://github.com/nearai/ironclaw/issues/5173) Daily ironclaw failure taxonomy — 2026-06-23 (deepseek-v4-flash)
- [#5169](https://github.com/nearai/ironclaw/issues/5169) Bundled skills trip the prompt-safety vocabulary denylist → turn dies as a misleading "temporary system issue" (clean-setup repro) 💬2

### 🔒 Closed Issues
- [#5187](https://github.com/nearai/ironclaw/issues/5187) Localize Reborn settings labels and improve automation filter label responsiveness
- [#5139](https://github.com/nearai/ironclaw/issues/5139) reborn regression: web/research tasks hang at init (0 LLM calls) on main HEAD (2b2ccc55→704fcd43)

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬4 · 1d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬7 · 2d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 3d ago
- 🟢 [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬1 · 3d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬2 · 3d ago
- 🟢 [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 3d ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 3d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 3d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 5d ago
- ⚫ [#94780](https://github.com/openclaw/openclaw/issues/94780) [Feature]: Per-cron model selection independent of agent default — run cheap/free models on automation jobs while keeping main agent on premium LLM — 💬1 · 5d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 1 new
- [[Index] Openai Broadcom Jalapeno Inference Chip](https://openai.com/index/openai-broadcom-jalapeno-inference-chip/) _2026-06-25_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [My suitcase robot gets high now off a real gas sensor wired straight into the LLM sampler. Smoke raises temperature/top_p/top_k live, so his speech genuinely gets loopier and never repeats.](https://reddit.com/r/LocalLLaMA/comments/1u9a17y/my_suitcase_robot_gets_high_now_off_a_real_gas/) ↑1729
- [GLM's founder says GLM-fable before the end of the year?!](https://reddit.com/r/LocalLLaMA/comments/1u96jof/glms_founder_says_glmfable_before_the_end_of_the/) ↑1442
- [DeepSeek raises $7.4B USD at $60B valuation. Remarkably, Liang Wenfeng invests $3B in DeepSeek himself.](https://reddit.com/r/LocalLLaMA/comments/1ucwyes/deepseek_raises_74b_usd_at_60b_valuation/) ↑1201
- [Tokenomics](https://reddit.com/r/LocalLLaMA/comments/1ubrcwj/tokenomics/) ↑1190
- [z.AI as the number 2 gives praise to the number 1 open source model](https://reddit.com/r/LocalLLaMA/comments/1uaxktf/zai_as_the_number_2_gives_praise_to_the_number_1/) ↑1070

### r/singularity — top 5 new
- [Drones enforcing traffics rules in Shenzhen](https://reddit.com/r/singularity/comments/1tuqvhr/drones_enforcing_traffics_rules_in_shenzhen/) ↑2509
- [Japanese animator using Seedance to render anime from simple 3D models](https://reddit.com/r/singularity/comments/1ue6yoh/japanese_animator_using_seedance_to_render_anime/) ↑2181
- [President Trump orders a national effort to build a quantum computer capable of performing important scientific calculations](https://reddit.com/r/singularity/comments/1ucy9oj/president_trump_orders_a_national_effort_to_build/) ↑2092
- [NSA says Mythos broke into almost all of their classified systems in hours, per The Economist](https://reddit.com/r/singularity/comments/1ubets2/nsa_says_mythos_broke_into_almost_all_of_their/) ↑1821
- [Data center noise irks Virginia neighbors: ‘You just want to curse’, Neighbors have put mattresses and plexiglass up in their windows to block the noise from this data center in Virginia. It's a high ](https://reddit.com/r/singularity/comments/1ue6sio/data_center_noise_irks_virginia_neighbors_you/) ↑1805

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Unit 42 found 5 malicious skills that passed ClawScan + VirusTotal](https://reddit.com/r/openclaw/comments/1ue5ln7/unit_42_found_5_malicious_skills_that_passed/) ↑24
- [openclaw pulled together my health data from 3 different sources for a doctor appointment i almost forgot about - pretty impressed](https://reddit.com/r/openclaw/comments/1uec85y/openclaw_pulled_together_my_health_data_from_3/) ↑6
- [People who write specs for AI coding agents?](https://reddit.com/r/openclaw/comments/1ue6f6h/people_who_write_specs_for_ai_coding_agents/) ↑3
- [Slack and Openclaw and Codex](https://reddit.com/r/openclaw/comments/1ue28kq/slack_and_openclaw_and_codex/) ↑3
- [Markdown files for ToDo list?](https://reddit.com/r/openclaw/comments/1ueo4mm/markdown_files_for_todo_list/) ↑2

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
- [OpenClaw 2026.6.10 just dropped.

Just a small release to keep things brewing:
 Automatic fast mode for short talks
 Muc](https://x.com/openclaw) ↑0 🔁0 · recent


### X — @steipete
- [*smells like AI slop reply*](https://x.com/steipete) ↑0 🔁0 · recent
- [Absolutely. Working hard to get cost per task down as low as possible. Feeling pretty good about things.](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
