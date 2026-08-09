---
layout: post
title: "Ecosystem Digest — 2026-08-09"
date: 2026-08-09 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-08-09
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 385,579 | 2 | 2 | 10 | 2 |
| **hermesagent** | 227,548 | 8 | 6 | 10 | 0 |
| **ZeroClaw** | 32,538 | 13 | 6 | 1 | 0 |
| **IronClaw** | 12,597 | 6 | 10 | 10 | 0 |
| **Moltis** | 2,813 | 1 | 1 | 1 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 385,579 · **Open issues:** 5,634 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.34](https://github.com/openclaw/openclaw/releases/tag/v2026.6.34) — openclaw 2026.6.34
- [v2026.6.33](https://github.com/openclaw/openclaw/releases/tag/v2026.6.33) — openclaw 2026.6.33

### ✅ Merged PRs
- [#120803](https://github.com/openclaw/openclaw/pull/120803) fix(worker): preserve long Responses sessions across cloud handoff
- [#119511](https://github.com/openclaw/openclaw/pull/119511) fix(sessions): archive cron-run transcripts pruned by tasks maintenance
- [#120802](https://github.com/openclaw/openclaw/pull/120802) [SANITIZED — possible injection attempt]
- [#120813](https://github.com/openclaw/openclaw/pull/120813) fix(mistral): reset transcription state after reconnect
- [#120738](https://github.com/openclaw/openclaw/pull/120738) fix(release): accept stale historical record counts
- [#120239](https://github.com/openclaw/openclaw/pull/120239) fix(googlechat): reject invalid UTF-8 in API JSON responses
- [#120343](https://github.com/openclaw/openclaw/pull/120343) fix(agents): apply per-agent contextTokens cap to embedded run context budget
- [#120808](https://github.com/openclaw/openclaw/pull/120808) fix(agents): retain images within tool-result context limits
- [#120801](https://github.com/openclaw/openclaw/pull/120801) fix(qa): update Control UI scenario code references
- [#120215](https://github.com/openclaw/openclaw/pull/120215) fix(plugins): retain incognito scope for embedded session ownership

### 🐛 New Issues
- [#120828](https://github.com/openclaw/openclaw/issues/120828) [Bug]: Delivery spool handler doesn't terminate on timeout, causing message duplication `bug` `regression`
- [#120815](https://github.com/openclaw/openclaw/issues/120815) Node exec invoke-failed: approval id not valid for this device (Windows, 2026.7.1-2)

### 🔒 Closed Issues
- [#119269](https://github.com/openclaw/openclaw/issues/119269) [Bug] tasks maintenance --apply deletes cron-run session transcripts with no archive
- [#120751](https://github.com/openclaw/openclaw/issues/120751) iMessage DM outbound messages mis-attributed to peer, breaking ACP conversation bindings

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 227,548 · **Open issues:** 29,758 · **Last push:** <1h ago

### ✅ Merged PRs
- [#82158](https://github.com/NousResearch/hermes-agent/pull/82158) fix(update): venv-blocker scan truncated cmdlines, breaking the gateway exemption and dead-ending Desktop updates
- [#82144](https://github.com/NousResearch/hermes-agent/pull/82144) fix(model-switch): list candidates on ambiguous alias instead of auto-picking (supersedes #67571)
- [#78911](https://github.com/NousResearch/hermes-agent/pull/78911) fix(otlp): span exporter now inherits configured resource_attributes
- [#82116](https://github.com/NousResearch/hermes-agent/pull/82116) fix(compression): charge stale thinking to the tail budget only on the newest assistant turn (#73624)
- [#82113](https://github.com/NousResearch/hermes-agent/pull/82113) fix(desktop): keep tool rows and notices out of the HUD band
- [#82109](https://github.com/NousResearch/hermes-agent/pull/82109) fix(state,cli,tui-gateway): keep reasoning fields intact across forks and branches (#57240)
- [#82106](https://github.com/NousResearch/hermes-agent/pull/82106) feat(desktop): support multiple cron delivery targets (salvage #73886)
- [#82104](https://github.com/NousResearch/hermes-agent/pull/82104) fix(desktop): keep earlier HUD windows in scope for the turn
- [#82101](https://github.com/NousResearch/hermes-agent/pull/82101) fix(desktop): make the slash list usable in HUD mode
- [#82102](https://github.com/NousResearch/hermes-agent/pull/82102) docs(telegram): explain rich streaming transports

### 🐛 New Issues
- [#82168](https://github.com/NousResearch/hermes-agent/issues/82168) [Setup]: Both updating and reinstalling `type/bug` `P2` `needs-repro` `sweeper:risk-compatibility` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows` `area/install-update`
- [#82167](https://github.com/NousResearch/hermes-agent/issues/82167) [Bug]: Desktop sessions ignore config.yaml model.provider — new sessions keep previously-selected provider and bill the old endpoint `type/bug` `duplicate` `area/config` `P2` `sweeper:risk-session-state` `sweeper:risk-compatibility` `comp/desktop` `area/billing` 💬1
- [#82166](https://github.com/NousResearch/hermes-agent/issues/82166) Update-check endpoint reports "up to date" for multiple consecutive days while a real release is available (inverse of the known stale-cache issue in #11007 / #1620) `type/bug` `comp/cli` `P3` `needs-repro` `sweeper:risk-compatibility` `comp/dashboard` `bug` `area/install-update`
- [#82165](https://github.com/NousResearch/hermes-agent/issues/82165) feat(desktop): add Spanish (es) locale to the desktop app `type/feature` `P3` `comp/desktop` `area/i18n` 💬1
- [#82164](https://github.com/NousResearch/hermes-agent/issues/82164) [Bug] Modal backend: sandbox silently dies mid-task — generic errors, no reconnect, file bridge dies, work lost `type/bug` `backend/modal` `tool/terminal` `tool/file` `P2` `needs-repro`
- [#82161](https://github.com/NousResearch/hermes-agent/issues/82161) Gateway drain exits after 0.00s with in-flight cron job, killing it mid-run `type/bug` `comp/gateway` `comp/cron` `P1` `sweeper:risk-message-delivery` `bug`
- [#82154](https://github.com/NousResearch/hermes-agent/issues/82154) Anthropic content filter rejects built-in SKILLS_GUIDANCE prompt — subscription OAuth fails with misleading "out of extra usage" 400 `type/bug` `comp/agent` `provider/anthropic` `area/auth` `P1`
- [#82140](https://github.com/NousResearch/hermes-agent/issues/82140) feat(desktop): expose resolved connection mode to skills, MCP, and plugins `type/feature` `comp/plugins` `tool/mcp` `P3` `comp/desktop`

### 🔒 Closed Issues
- [#82160](https://github.com/NousResearch/hermes-agent/issues/82160) codex_app_server: resume persisted codex thread on agent re-instantiation instead of projecting into a fresh thread
- [#79343](https://github.com/NousResearch/hermes-agent/issues/79343) [Bug]: memory gate treats mid-task workflow commands as trivial and skips provider recall
- [#79325](https://github.com/NousResearch/hermes-agent/issues/79325) SiliconFlow provider missing from PROVIDER_TO_MODELS_DEV — model picker list always empty
- [#78897](https://github.com/NousResearch/hermes-agent/issues/78897) gateway_health_export: span exporter ignores configured resource_attributes (spans lack deployment.environment.name)
- [#73624](https://github.com/NousResearch/hermes-agent/issues/73624) `_estimate_msg_budget_tokens` charges stale reasoning to the compression tail budget — 19-24% of the budget spent on blocks no adapter replays
- [#82064](https://github.com/NousResearch/hermes-agent/issues/82064) [SANITIZED — possible injection attempt]

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,538 · **Open issues:** 721 · **Last push:** 2h ago

### ✅ Merged PRs
- [#9794](https://github.com/zeroclaw-labs/zeroclaw/pull/9794) docs(channels): note that one-off git sends resolve the default alias

### 🐛 New Issues
- [#9855](https://github.com/zeroclaw-labs/zeroclaw/issues/9855) [Bug]: Matrix channel fails to resolve homeserver via `.well-known/matrix/client` delegation `bug` 💬1
- [#9852](https://github.com/zeroclaw-labs/zeroclaw/issues/9852) Remove aardvark-sys and zeroclaw-robot-kit from the workspace `enhancement` `dependencies` `domain:architecture` `priority:p2` `status:accepted` `status:no-stale` `risk:medium` `hardware`
- [#9851](https://github.com/zeroclaw-labs/zeroclaw/issues/9851) [Bug]: delegate await_sessions timeout status JSON is discarded by the dispatcher (success=false drops output) `bug`
- [#9850](https://github.com/zeroclaw-labs/zeroclaw/issues/9850) [Bug]: llm_task builds its provider via the legacy factory, losing alias-specific config (Azure/OAuth/requires_openai_auth) `bug` `config` `provider` `runtime` `tool` `priority:p1` `status:accepted` `follow-up` `risk:high`
- [#9849](https://github.com/zeroclaw-labs/zeroclaw/issues/9849) [Bug]: RateLimitedTool budget check is non-atomic under parallel dispatch (check-before, record-after) `bug` `config` `runtime` `security` `tool` `security:policy` `domain:security` `priority:p2` `status:accepted` `follow-up` `risk:high`
- [#9845](https://github.com/zeroclaw-labs/zeroclaw/issues/9845) [Feature]: Support non-ASCII characters in agent aliases (e.g. [agents."审核助手"]) `enhancement` `agent` `config` `domain:architecture` `priority:p2` `status:accepted` `risk:high` 💬1
- [#9844](https://github.com/zeroclaw-labs/zeroclaw/issues/9844) bug(zerocode): dashboard CPU metric does not identify the measured process `bug` `observability` `status:accepted` `priority:p3` `zerocode` `risk:low`
- [#9840](https://github.com/zeroclaw-labs/zeroclaw/issues/9840) [Bug]: daemon steals daemon.sock on start and unlinks it on exit, stranding a live daemon `bug` `daemon` `runtime` `service` `priority:p1` `status:accepted` `desktop` `zerocode` `risk:high`
- [#9834](https://github.com/zeroclaw-labs/zeroclaw/issues/9834) [Bug]: intermittent zeroclaw-runtime test failures from shared process-global state (turn_streamed receipts + model_switch) `bug` `ci` `runtime` `tests` `domain:ci` `priority:p1` `status:accepted` `risk:high` `type:test` 💬1
- [#9832](https://github.com/zeroclaw-labs/zeroclaw/issues/9832) zeroclaw-hardware fails to compile with --features hardware: unresolved import aardvark_sys::AardvarkHandle `bug` `ci` `dependencies` `priority:p1` `status:accepted` `risk:medium` `hardware`
- [#9825](https://github.com/zeroclaw-labs/zeroclaw/issues/9825) [Bug]: Leak detection controls do not prevent channel redaction of public blockchain addresses `bug` `channel` `observability` `runtime` `security` `domain:security` `priority:p1` `status:accepted` `risk:high` `security:leak-detector` 💬3
- [#9824](https://github.com/zeroclaw-labs/zeroclaw/issues/9824) [Feature]: Simplify the default web-tool surface to web_fetch + web_research + http_request `enhancement` `agent` `config` `runtime` `security` `tool` `tool:browser` `domain:security` `domain:architecture` `priority:p1` `tool:web` `status:in-progress` `status:no-stale` `risk:high` `type:tracker` 💬2
- [#9820](https://github.com/zeroclaw-labs/zeroclaw/issues/9820) calculator tool: model emits literal <TOOLCALL> pseudo-syntax instead of a real function call `bug` `agent` `provider` `runtime` `tool` `provider:compatible` `priority:p2` `status:accepted` `risk:high`

### 🔒 Closed Issues
- [#9847](https://github.com/zeroclaw-labs/zeroclaw/issues/9847) permission probe
- [#8043](https://github.com/zeroclaw-labs/zeroclaw/issues/8043) RFC: Retire the standalone aardvark-sys crate (fold into zeroclaw-hardware)
- [#9843](https://github.com/zeroclaw-labs/zeroclaw/issues/9843) bug(zerocode): long-lived client can enter sustained CPU spin alongside daemon
- [#5561](https://github.com/zeroclaw-labs/zeroclaw/issues/5561) [Feature]: Unified SOP Webhook Dispatcher and Notification Bridge
- [#9821](https://github.com/zeroclaw-labs/zeroclaw/issues/9821) cron tool: agent never invokes it, always falls back to shell "crontab" (blocked by policy)
- [#9813](https://github.com/zeroclaw-labs/zeroclaw/issues/9813) API key written to logs in plaintext on provider connection errors

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,597 · **Open issues:** 1,494 · **Last push:** 1h ago

### ✅ Merged PRs
- [#7377](https://github.com/nearai/ironclaw/pull/7377) feat!: a run acts as its invoker — remove shared-route subject binding (#7157 follow-ups)
- [#7382](https://github.com/nearai/ironclaw/pull/7382) feat(stress): scripted tool-call workload with durable write read-back (#7360)
- [#6938](https://github.com/nearai/ironclaw/pull/6938) fix(skills): the model chooses the skill, not a keyword scorer
- [#7280](https://github.com/nearai/ironclaw/pull/7280) test(inspector): add browser, security, and operator coverage
- [#7393](https://github.com/nearai/ironclaw/pull/7393) test(disclosure): measure the Core delivery pair in the wide-catalog benchmark
- [#7389](https://github.com/nearai/ironclaw/pull/7389) fix(live-qa): verify triggered Slack delivery through the two-lane contract
- [#7364](https://github.com/nearai/ironclaw/pull/7364) test(telegram): pin reply anchoring and overlap busy-notice feedback (#6643, #6644)
- [#7390](https://github.com/nearai/ironclaw/pull/7390) fix(loop): make routine delivery steering deterministic under progressive disclosure
- [#7228](https://github.com/nearai/ironclaw/pull/7228) feat(webui): add audited admin thread scraping
- [#7371](https://github.com/nearai/ironclaw/pull/7371) fix(ci): recapture extension_host coverage floor + run goldens on prompt-surface PRs

### 🐛 New Issues
- [#7392](https://github.com/nearai/ironclaw/issues/7392) Replace first-party coding tools with the pinned omp tool surface `epic`
- [#7391](https://github.com/nearai/ironclaw/issues/7391) SafetyLayer::validate_input / scan_inbound_for_secrets have no caller on the live Reborn turn path
- [#7360](https://github.com/nearai/ironclaw/issues/7360) Expand stress coverage across built-in and durable write paths `enhancement` `scope: tool/builtin` `scope: ci` `e2e-coverage` `performance` 💬2
- [#7218](https://github.com/nearai/ironclaw/issues/7218) Epic: Add the Web Debug Inspector `epic` `v1.1.0`
- [#6989](https://github.com/nearai/ironclaw/issues/6989) Token accounting: hybrid provider-usage + tail estimates; fix ModelWorkRequest estimating from the content reference string `bug` `scope: estimation` `reborn` `p1` 💬5
- [#6939](https://github.com/nearai/ironclaw/issues/6939) Feature: Migration tool to port legacy agent setup and memory to IronClaw `p2` `feedback` `feature` 💬2

### 🔒 Closed Issues
- [#7226](https://github.com/nearai/ironclaw/issues/7226) [Inspector] Add browser, security, and documentation coverage
- [#4539](https://github.com/nearai/ironclaw/issues/4539) Epic: Reborn approvals parity
- [#4470](https://github.com/nearai/ironclaw/issues/4470) Refactor reborn composition into owned crates with CI-enforced boundaries
- [#4389](https://github.com/nearai/ironclaw/issues/4389) Follow up: split behavior-changing auth and MCP review items from PR #4354
- [#4382](https://github.com/nearai/ironclaw/issues/4382) Product auth: default OAuth account per provider (set once, gate never re-fires)
- [#4120](https://github.com/nearai/ironclaw/issues/4120) Declarative Reborn capability policy for local-dev grants
- [#4118](https://github.com/nearai/ironclaw/issues/4118) Reborn CLI provider add/login parity
- [#4091](https://github.com/nearai/ironclaw/issues/4091) Track production and multi-tenant extension lifecycle wiring
- [#4088](https://github.com/nearai/ironclaw/issues/4088) Track decomposition of oversized Reborn integration files
- [#4059](https://github.com/nearai/ironclaw/issues/4059) [Reborn] Enrich model-visible Reborn runtime errors with safe recovery context

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,813 · **Open issues:** 96 · **Last push:** 7h ago

### ✅ Merged PRs
- [#1105](https://github.com/moltis-org/moltis/pull/1105) Fix Docker sandbox filesystem tool fallback

### 🐛 New Issues
- [#1185](https://github.com/moltis-org/moltis/issues/1185) [Bug]: Apple Container 1.x sandbox starts but Moltis treats it as not running

### 🔒 Closed Issues
- [#1096](https://github.com/moltis-org/moltis/issues/1096) [Bug]: `Read`/`Write`/`Edit` tools don't work in Docker

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 1d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 2d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 2d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 4d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 6d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 6d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 8d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 8d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 12d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 18d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [2027 Memory Capacity Is Reportedly Sold Out](https://reddit.com/r/LocalLLaMA/comments/1viqtgm/2027_memory_capacity_is_reportedly_sold_out/) ↑778
- [DeepSeek V4 Flash 0731 appreciation post](https://reddit.com/r/LocalLLaMA/comments/1vio0x6/deepseek_v4_flash_0731_appreciation_post/) ↑409
- [Showoff Saturday: Local 4x 6000 Pro (multi-year progression)](https://reddit.com/r/LocalLLaMA/comments/1vj18h4/showoff_saturday_local_4x_6000_pro_multiyear/) ↑158
- [Kimi K3 (Unsloth) IQ2-XXS from 711GB down to 478GB!!! Only Multi-language was removed to trim the size](https://reddit.com/r/LocalLLaMA/comments/1vjanps/kimi_k3_unsloth_iq2xxs_from_711gb_down_to_478gb/) ↑78
- [RTX 5090 96GB spotted on Alibaba?](https://reddit.com/r/LocalLLaMA/comments/1vjcljq/rtx_5090_96gb_spotted_on_alibaba/) ↑73

### r/singularity — top 5 new
- [This is why the vast majority aren't taking any "this new model is dangerous" messages seriously. They've cried wolf FAR too many times. They could literally announce that a nuclear war caused by AI i](https://reddit.com/r/singularity/comments/1vivgeq/this_is_why_the_vast_majority_arent_taking_any/) ↑908
- [AI Model Trained In DNA Invents 16 New Viruses Not Found In Nature](https://reddit.com/r/singularity/comments/1vioml5/ai_model_trained_in_dna_invents_16_new_viruses/) ↑489
- [GPT 5.6 Sol and Fable 5 settle a 25 year old problem in wireless communication theory](https://reddit.com/r/singularity/comments/1vj5d09/gpt_56_sol_and_fable_5_settle_a_25_year_old/) ↑420
- [What YouTube videos Dario was watching to calm down after fighting with Sam? Right answers only](https://reddit.com/r/singularity/comments/1viugai/what_youtube_videos_dario_was_watching_to_calm/) ↑220
- [ChatGPT Sol 5.6 high found a normalization error in two recently published Riemann Hypothesis papers. The author confirmed it.](https://reddit.com/r/singularity/comments/1vj3rck/chatgpt_sol_56_high_found_a_normalization_error/) ↑191

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw is not dead](https://reddit.com/r/openclaw/comments/1vizunz/openclaw_is_not_dead/) ↑41
- [I built an Open WebUI integration for OpenClaw so I could run my agents from my phone](https://reddit.com/r/openclaw/comments/1vja98t/i_built_an_open_webui_integration_for_openclaw_so/) ↑11
- [[SANITIZED — possible injection attempt]](https://reddit.com/r/openclaw/comments/1vj5yvh/guardrails_and_system_prompts/) ↑1
- [for about 2-3 weeks, openclaw agent has his entire reasoning in the messages](https://reddit.com/r/openclaw/comments/1vj4o5o/for_about_23_weeks_openclaw_agent_has_his_entire/) ↑1

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
_No new tweets in the last 7 days._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
