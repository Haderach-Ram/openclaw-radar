---
layout: post
title: "Ecosystem Digest — 2026-08-03"
date: 2026-08-03 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-08-03
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 384,962 | 10 | 2 | 10 | 1 |
| **hermesagent** | 224,347 | 8 | 3 | 4 | 0 |
| **ZeroClaw** | 32,485 | 15 | 9 | 10 | 1 |
| **IronClaw** | 12,587 | 6 | 1 | 6 | 0 |
| **Moltis** | 2,805 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 384,962 · **Open issues:** 5,532 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.7.2-beta.7](https://github.com/openclaw/openclaw/releases/tag/v2026.7.2-beta.7) — openclaw 2026.7.2-beta.7

### ✅ Merged PRs
- [#118314](https://github.com/openclaw/openclaw/pull/118314) refactor(discord): consolidate Activity HTTP test fixtures
- [#117697](https://github.com/openclaw/openclaw/pull/117697) fix(whatsapp): preserve source direction for automatic reactions
- [#118064](https://github.com/openclaw/openclaw/pull/118064) fix(line): skip invalid location messages before delivery
- [#114411](https://github.com/openclaw/openclaw/pull/114411) refactor(cli): consolidate security-sensitive regression fixtures
- [#118130](https://github.com/openclaw/openclaw/pull/118130) fix(failover): classify interrupted transport failures as timeouts
- [#118255](https://github.com/openclaw/openclaw/pull/118255) fix(qa): restore prerelease validation
- [#118351](https://github.com/openclaw/openclaw/pull/118351) improve(tests): focus overflow compaction owner coverage
- [#118319](https://github.com/openclaw/openclaw/pull/118319) refactor(telegram): deduplicate reasoning room-event fixtures
- [#118318](https://github.com/openclaw/openclaw/pull/118318) refactor(xai): consolidate realtime voice test fixtures
- [#118357](https://github.com/openclaw/openclaw/pull/118357) fix(telegram): prevent durable ingress lane spins

### 🐛 New Issues
- [#118374](https://github.com/openclaw/openclaw/issues/118374) Code-mode exec: multi-callValue results dropped across wait/resume boundary 💬1
- [#118373](https://github.com/openclaw/openclaw/issues/118373) Scheduled automations agentTurn: exec bridge fails immediately, run + failure notification both undelivered 💬1
- [#118372](https://github.com/openclaw/openclaw/issues/118372) Crash-loop on first boot after upgrade until doctor --fix service-repair; stderr defaults to /dev/null 💬1
- [#118371](https://github.com/openclaw/openclaw/issues/118371) [SANITIZED — possible injection attempt] 💬1
- [#118370](https://github.com/openclaw/openclaw/issues/118370) [Bug]: Memory Wiki orphans imported pages when bridge and unsafe-local share a source `maintainer` 💬1
- [#118367](https://github.com/openclaw/openclaw/issues/118367) [Bug]: runReplyAgent follow-up test times out after cold runtime discovery `bug` `maintainer` 💬1
- [#118345](https://github.com/openclaw/openclaw/issues/118345) [Bug]: cron auto-disable can still notify pre-persist via recompute paths; manual-run preflight mutates without persisting `bug` `maintainer` `P2` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬2
- [#118343](https://github.com/openclaw/openclaw/issues/118343) [Bug]: cold CLI read paths re-derive plugin discovery per row/callee (channels list 6.4s, plugins doctor 11.6s, nodes 4.1s) `bug` `maintainer` `P2` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `maturity:stable` 💬2
- [#118341](https://github.com/openclaw/openclaw/issues/118341) [Bug]: Control UI avatar 401s under Tailscale identity-header auth; Tailscale name/profile-pic not adopted `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬2
- [#118333](https://github.com/openclaw/openclaw/issues/118333) [Bug]: openclaw sessions CLI cannot archive or delete a session (UI-only capability) `maintainer` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `maturity:stable` 💬2

### 🔒 Closed Issues
- [#118355](https://github.com/openclaw/openclaw/issues/118355) [Bug] Agent enters infinite loop after SUCCESSFUL tool call (conversation state tracking bug)
- [#117669](https://github.com/openclaw/openclaw/issues/117669) Dreaming recall store stays empty — RAW_TRANSCRIPT_TURN_RE blocks all session transcript ingestion

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬116 · 1d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 224,347 · **Open issues:** 26,873 · **Last push:** <1h ago

### ✅ Merged PRs
- [#77180](https://github.com/NousResearch/hermes-agent/pull/77180) fix(env): config.yaml terminal.* keys win over stale .env on every reload (#29186)
- [#77104](https://github.com/NousResearch/hermes-agent/pull/77104) feat(skills): add fact-checking mode to grounded-citations
- [#77132](https://github.com/NousResearch/hermes-agent/pull/77132) chore: consolidate contributor email mappings from open attribution PRs
- [#76354](https://github.com/NousResearch/hermes-agent/pull/76354) feat(gateway): session activity heartbeats, stall watchdog, bounded compression waits

### 🐛 New Issues
- [#77244](https://github.com/NousResearch/hermes-agent/issues/77244) [Bug] NeMo Relay retain_managed_execution causes Future attached to different loop for async tools like vision_analyze
- [#77241](https://github.com/NousResearch/hermes-agent/issues/77241) Desktop: enabling Message reactions never reaches backend — agent never reacts (config.set 4002 unknown key, silently swallowed)
- [#77223](https://github.com/NousResearch/hermes-agent/issues/77223) feat(usage): surface included/estimated/unknown cost buckets in aggregate views `type/feature` `comp/agent` `P3` `area/usage-cost`
- [#77222](https://github.com/NousResearch/hermes-agent/issues/77222) feat(insights): add per-day token/cost time-series aggregation to InsightsEngine `type/feature` `comp/agent` `P3` `area/usage-cost`
- [#77221](https://github.com/NousResearch/hermes-agent/issues/77221) feat(usage): desktop app has no local token/cost analytics surface despite full metering in core `type/feature` `P3` `comp/desktop` `area/usage-cost`
- [#77217](https://github.com/NousResearch/hermes-agent/issues/77217) [Bug]: feat(cache): enable DeepSeek caching on OpenCode breaks deepseek-v4-flash on OpenCode Zen with HTTP 400 (content must be string, not block array) `type/bug` `comp/agent` `provider/deepseek` `P0` `sweeper:risk-caching` `bug` 💬1
- [#77216](https://github.com/NousResearch/hermes-agent/issues/77216) [Bug]: kanban_attach has no local-path option — large inline base64 risks silent mid-generation truncation `type/bug` `comp/cron` `tool/file` `P3`
- [#77215](https://github.com/NousResearch/hermes-agent/issues/77215) [Bug]: kanban_attach's strict base64 validation rejects valid whitespace-wrapped / data-URI-prefixed input `type/bug` `comp/cron` `tool/file` `P3`

### 🔒 Closed Issues
- [#77197](https://github.com/NousResearch/hermes-agent/issues/77197) Feature Request: Full German (de) localization of Desktop UI and CLI menus
- [#77175](https://github.com/NousResearch/hermes-agent/issues/77175) [Bug]: Analysis of the reasons why Hermes Desktop cannot be updated
- [#75768](https://github.com/NousResearch/hermes-agent/issues/75768) Telegram typing indicator stuck indefinitely with multi-profile setup (v0.19.0, regression)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,485 · **Open issues:** 696 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.8.4](https://github.com/zeroclaw-labs/zeroclaw/releases/tag/v0.8.4) — v0.8.4

### ✅ Merged PRs
- [#9311](https://github.com/zeroclaw-labs/zeroclaw/pull/9311) feat(config): surface dangling peer_groups.*.channel refs as structured warnings (#8997)
- [#9401](https://github.com/zeroclaw-labs/zeroclaw/pull/9401) fix(security): preserve shell cwd through Seatbelt
- [#9267](https://github.com/zeroclaw-labs/zeroclaw/pull/9267) feat(installer): generate canonical installation documentation
- [#8937](https://github.com/zeroclaw-labs/zeroclaw/pull/8937) fix(agent): stream-hash tool args in loop_detector to avoid per-call deep clone (#8936)
- [#9400](https://github.com/zeroclaw-labs/zeroclaw/pull/9400) refactor(providers): share OAuth refresh retry control flow
- [#9038](https://github.com/zeroclaw-labs/zeroclaw/pull/9038) fix(lark): pick receive_id_type from recipient id prefix
- [#9444](https://github.com/zeroclaw-labs/zeroclaw/pull/9444) fix(parser): quote GLM curl URLs for POSIX shells
- [#8874](https://github.com/zeroclaw-labs/zeroclaw/pull/8874) fix(ci): scope rustdoc --default-theme away from cargo test --doc (#8847)
- [#8918](https://github.com/zeroclaw-labs/zeroclaw/pull/8918) fix(security): redact Slack tokens in the leak detector
- [#9517](https://github.com/zeroclaw-labs/zeroclaw/pull/9517) fix(channels): localize tool-approval prompts across adapters

### 🐛 New Issues
- [#9690](https://github.com/zeroclaw-labs/zeroclaw/issues/9690) Containerfile StageX pin ships rustc 1.95.0, below the declared MSRV `bug` `ci` `priority:p1` `status:in-progress` `status:accepted` `risk:high` `type:ci` 💬1
- [#9687](https://github.com/zeroclaw-labs/zeroclaw/issues/9687) [Feature]: SOP engine — operator-initiated pause for running SOPs `enhancement` `runtime` `priority:p2` `tool:sop` `status:blocked` `follow-up` `risk:high`
- [#9686](https://github.com/zeroclaw-labs/zeroclaw/issues/9686) [Task]: zerocode SOP pane — mouse Run / Resume controls (deferred from MVP) `enhancement` `priority:p2` `tool:sop` `status:blocked` `status:accepted` `zerocode` `risk:low`
- [#9685](https://github.com/zeroclaw-labs/zeroclaw/issues/9685) [Task]: daemon RPC — expose SOP run cancellation as sops/cancel (deferred) `enhancement` `daemon` `runtime` `priority:p2` `tool:sop` `status:blocked` `status:accepted` `risk:high`
- [#9684](https://github.com/zeroclaw-labs/zeroclaw/issues/9684) [Task]: zerocode SOP pane — live run-status icons on the SOP list `enhancement` `priority:p2` `tool:sop` `status:in-progress` `status:accepted` `zerocode` `risk:low`
- [#9683](https://github.com/zeroclaw-labs/zeroclaw/issues/9683) [Task]: zerocode client — add sops/runs RPC method and run-summary view type `enhancement` `priority:p2` `tool:sop` `status:in-progress` `status:accepted` `zerocode` `risk:low`
- [#9682](https://github.com/zeroclaw-labs/zeroclaw/issues/9682) [Task]: Tracker — zerocode SOP pane MVP (status visibility: list + live run-status icons) `enhancement` `runtime` `priority:p2` `tool:sop` `status:accepted` `status:no-stale` `zerocode` `risk:high` `type:tracker`
- [#9681](https://github.com/zeroclaw-labs/zeroclaw/issues/9681) [Bug]: ZeroCode drops clipboard-temp cleanup ownership after deletion failure `bug` `status:accepted` `priority:p3` `follow-up` `risk:medium` `zerocode`
- [#9680](https://github.com/zeroclaw-labs/zeroclaw/issues/9680) [Feature]: ci: audit remaining CLI and hardware path-label ownership `enhancement` `ci` `docs` `status:accepted` `priority:p3` `follow-up` `risk:low`
- [#9679](https://github.com/zeroclaw-labs/zeroclaw/issues/9679) [Feature]: ci: re-evaluate local artifact support when act ships compatibility `enhancement` `ci` `scripts` `status:blocked` `status:accepted` `priority:p3` `follow-up` `risk:low`
- [#9677](https://github.com/zeroclaw-labs/zeroclaw/issues/9677) [Feature]: Retire ZeroCode command-catalogue compatibility fallback `enhancement` `priority:p2` `status:blocked` `status:accepted` `risk:medium` `zerocode`
- [#9675](https://github.com/zeroclaw-labs/zeroclaw/issues/9675) [SANITIZED — possible injection attempt] `bug` `agent` `memory` `provider` `runtime` `security` `agent:prompt` `priority:p1` `status:accepted` `risk:high`
- [#9672](https://github.com/zeroclaw-labs/zeroclaw/issues/9672) [Bug]: none of the three `cron add` examples in the CLI help run as printed, and the empty-state hint prints a fourth broken form `bug` `docs` `core` `cron` `runtime` `channel:cli` `priority:p1` `status:accepted` `risk:low` 💬1
- [#9670](https://github.com/zeroclaw-labs/zeroclaw/issues/9670) refactor(channels): resolve unused public facade compatibility `enhancement` `channel` `domain:architecture` `priority:p2` `status:accepted` `follow-up` `risk:medium`
- [#9669](https://github.com/zeroclaw-labs/zeroclaw/issues/9669) feat(channels): schedule WhatsApp Web sent-message retention cleanup `enhancement` `channel` `priority:p2` `status:accepted` `follow-up` `risk:medium`

### 🔒 Closed Issues
- [#8997](https://github.com/zeroclaw-labs/zeroclaw/issues/8997) [Feature]: Warn when a peer_groups.*.channel ref points at a non-existent channel alias
- [#9039](https://github.com/zeroclaw-labs/zeroclaw/issues/9039) [Feature]: Generate installation docs from the canonical install spec
- [#8936](https://github.com/zeroclaw-labs/zeroclaw/issues/8936) [Bug]: loop_detector::hash_value deep-clones the entire tool-args JSON tree on every tool call (hot path)
- [#9162](https://github.com/zeroclaw-labs/zeroclaw/issues/9162) refactor(providers): extract duplicated OAuth-refresh retry loop into oauth_common
- [#8847](https://github.com/zeroclaw-labs/zeroclaw/issues/8847) bug(ci): cargo test --doc fails with duplicated rustdoc theme flag
- [#8357](https://github.com/zeroclaw-labs/zeroclaw/issues/8357) [Tracker]: v0.8.4 maintenance train
- [#9676](https://github.com/zeroclaw-labs/zeroclaw/issues/9676) bug(ci): restore all-features Docker publishing after MSRV bump
- [#9409](https://github.com/zeroclaw-labs/zeroclaw/issues/9409) bug(channels): localize tool-approval prompts across adapters
- [#8578](https://github.com/zeroclaw-labs/zeroclaw/issues/8578) [Bug]: On failure to start it doesn't terminate the process

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,587 · **Open issues:** 1,443 · **Last push:** <1h ago

### ✅ Merged PRs
- [#7018](https://github.com/nearai/ironclaw/pull/7018) refactor(contracts): consolidate the Wave 2 port-inversion stack (WS2.2, WS2.4, WS5)
- [#7013](https://github.com/nearai/ironclaw/pull/7013) ci: restore the original 90% changed-line coverage floor
- [#6952](https://github.com/nearai/ironclaw/pull/6952) ci: scope Reborn PR tests by affected area
- [#7007](https://github.com/nearai/ironclaw/pull/7007) Alert live-canary Slack channel on merge queue failures
- [#7003](https://github.com/nearai/ironclaw/pull/7003) refactor(extensions): split ironclaw_extension_manager out of extension_host (WS2.4)
- [#6992](https://github.com/nearai/ironclaw/pull/6992) fix(ci): pin comm to LC_ALL=C in reborn crate discovery

### 🐛 New Issues
- [#7031](https://github.com/nearai/ironclaw/issues/7031) [QA] Failed lazy delivery recovery is not retried within a coordinator lifetime
- [#7030](https://github.com/nearai/ironclaw/issues/7030) [QA] Report host-mediated egress ignoring ambient proxy variables in operator diagnostics
- [#7025](https://github.com/nearai/ironclaw/issues/7025) [QA] Concurrent coordinators can both send the same durable delivery attempt
- [#7017](https://github.com/nearai/ironclaw/issues/7017) [QA] Interrupted-delivery recovery can overwrite a concurrent Delivered status
- [#7016](https://github.com/nearai/ironclaw/issues/7016) [SANITIZED — possible injection attempt]
- [#7012](https://github.com/nearai/ironclaw/issues/7012) Time awareness without prompt-cache churn: append-only rollover context and duration evidence `scope: agent` `reborn` `performance`

### 🔒 Closed Issues
- [#7015](https://github.com/nearai/ironclaw/issues/7015) UI bug on Staking page

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,805 · **Open issues:** 96 · **Last push:** <1h ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 11h ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 21h ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 1d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 2d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 2d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 2d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬10 · 2d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 6d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 12d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 23d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 1 new
- [[Finance] Workflows](https://openai.com/business/solutions/finance/workflows/) _2026-08-02_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Setting up of a 16xGB10 (DGX Spark) cluster](https://reddit.com/r/LocalLLaMA/comments/1vdcgpm/setting_up_of_a_16xgb10_dgx_spark_cluster/) ↑929
- [I pushed Kimi K3 onto one CPU with 8 GB of RAM](https://reddit.com/r/LocalLLaMA/comments/1vd874t/i_pushed_kimi_k3_onto_one_cpu_with_8_gb_of_ram/) ↑662
- [llama.cpp just added MTP / DSpark support for DeepSeek V4 Flash](https://reddit.com/r/LocalLLaMA/comments/1vdhgq9/llamacpp_just_added_mtp_dspark_support_for/) ↑458
- [DeepSeek-V4-Flash-0731: surpasses Fable-5, Sol & Kimi-K3 on Chess Benchmark](https://reddit.com/r/LocalLLaMA/comments/1vdq8en/deepseekv4flash0731_surpasses_fable5_sol_kimik3/) ↑332
- [Conclusion: r/LocalLLaMA still has brilliant open-weight research, but finding it requires wading through endless benchmark drama, non-local Discussion Points and repetitive hardware flexes.](https://reddit.com/r/LocalLLaMA/comments/1vdku4r/conclusion_rlocalllama_still_has_brilliant/) ↑323

### r/singularity — top 2 new
- [This scene from "Don't Look Up" is now real](https://reddit.com/r/singularity/comments/1vdfa3z/this_scene_from_dont_look_up_is_now_real/) ↑2216
- [Just tell the model what you want](https://reddit.com/r/singularity/comments/1vdxilc/just_tell_the_model_what_you_want/) ↑219

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Interested in using OpenClaw and trying it out, but I don't really have use for it. What do you guys use it for?](https://reddit.com/r/openclaw/comments/1vdj4rg/interested_in_using_openclaw_and_trying_it_out/) ↑33
- [Best memory plugin for openclaw?](https://reddit.com/r/openclaw/comments/1vdfg45/best_memory_plugin_for_openclaw/) ↑12
- [Do you use the Codex app server or the native OpenClaw runtime?](https://reddit.com/r/openclaw/comments/1vdb0cp/do_you_use_the_codex_app_server_or_the_native/) ↑9
- [Ordered a Pizza with OpenClaw+vapi.ai+twilio. AMA](https://reddit.com/r/openclaw/comments/1ve0b79/ordered_a_pizza_with_openclawvapiaitwilio_ama/) ↑0

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
- [I'm building a claw node on an ESP32 chip, so gave my agent access to my webcam to e2e test this. Now I feel it's stalki](https://x.com/steipete/status/2083694161933594703) ↑0 🔁0 · recent
- [Repo:](https://x.com/steipete/status/2083694911824826659) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
