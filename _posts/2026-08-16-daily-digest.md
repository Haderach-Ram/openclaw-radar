---
layout: post
title: "Ecosystem Digest — 2026-08-16"
date: 2026-08-16 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-08-16
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 386,407 | 9 | 6 | 10 | 1 |
| **hermesagent** | 231,108 | 7 | 4 | 10 | 0 |
| **ZeroClaw** | 32,592 | 10 | 4 | 4 | 0 |
| **IronClaw** | 12,603 | 6 | 10 | 5 | 0 |
| **Moltis** | 2,820 | 0 | 2 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 386,407 · **Open issues:** 5,541 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.8.1-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.8.1-beta.2) — OpenClaw 2026.8.1-beta.2

### ✅ Merged PRs
- [#123575](https://github.com/openclaw/openclaw/pull/123575) fix(doctor): report missing managed local embedding setup
- [#124350](https://github.com/openclaw/openclaw/pull/124350) perf(test): shorten Vault timeout regression
- [#124264](https://github.com/openclaw/openclaw/pull/124264) fix(ui): reject blank required strings in Control UI update readers
- [#124277](https://github.com/openclaw/openclaw/pull/124277) fix(ui): sidebar sort selection is forgotten after a reload
- [#123987](https://github.com/openclaw/openclaw/pull/123987) feat(sessions): preserve recent session history during maintenance
- [#124261](https://github.com/openclaw/openclaw/pull/124261) fix(ui): use native placement for the lobster dismiss menu
- [#120900](https://github.com/openclaw/openclaw/pull/120900) feat(ui): review install policy warnings
- [#124282](https://github.com/openclaw/openclaw/pull/124282) fix(state): doctor --fix loops on "migration required" for older state databases
- [#123912](https://github.com/openclaw/openclaw/pull/123912) feat(ui): open links in Control UI browser
- [#124336](https://github.com/openclaw/openclaw/pull/124336) fix(audit): show valid values for rejected filters

### 🐛 New Issues
- [#124349](https://github.com/openclaw/openclaw/issues/124349) [Bug]: exec rejects host:"auto" under host=gateway with no sandbox, and the suggested fix widens execution to node hosts 💬1
- [#124346](https://github.com/openclaw/openclaw/issues/124346) [Bug]: workspace retain coordinator warns ~1/min forever for nodes without the worker runtime 💬1
- [#124345](https://github.com/openclaw/openclaw/issues/124345) [Bug]: Setup inference probe's 32-token cap starves reasoning models, reporting healthy local models as broken inference 💬1
- [#124343](https://github.com/openclaw/openclaw/issues/124343) [Bug]: yield-owned settle-wake parks a completed subagent forever — no delivery, no retry, no recorded reason `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬2
- [#124332](https://github.com/openclaw/openclaw/issues/124332) Tool-loop block messages don't reach model context; no hard abort for repeated critical loop detections 💬1
- [#124324](https://github.com/openclaw/openclaw/issues/124324) [Bug]: Ollama requests never reach server in --local embedded TUI mode `bug` `bug:behavior` `P2` `impact:auth-provider` `issue-rating: 🦪 silver shellfish` 💬2
- [#124316](https://github.com/openclaw/openclaw/issues/124316) [Bug]: Growing the chat composer pushes the transcript off the end and raises the jump-to-latest arrow `bug` `maintainer` `bug:behavior` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬2
- [#124314](https://github.com/openclaw/openclaw/issues/124314) [SANITIZED — possible injection attempt] `P1` `impact:security` `maturity:stable` 💬1
- [#124307](https://github.com/openclaw/openclaw/issues/124307) [Bug]: chat pane rename seeds from the rendered title, persisting the account suffix into stored labels `bug` `maintainer` `bug:behavior` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬2

### 🔒 Closed Issues
- [#124227](https://github.com/openclaw/openclaw/issues/124227) Abort stale destructive session confirmations on reconnect
- [#124273](https://github.com/openclaw/openclaw/issues/124273) [Bug]: Control UI sidebar sort selection does not persist across reloads
- [#124230](https://github.com/openclaw/openclaw/issues/124230) Make Markdown file-link label disambiguation linear
- [#124234](https://github.com/openclaw/openclaw/issues/124234) Stop inferring session-sharing identity kind from ID strings
- [#123881](https://github.com/openclaw/openclaw/issues/123881) [Feature]: Open links in Control UI browser
- [#95441](https://github.com/openclaw/openclaw/issues/95441) github-copilot/gpt-5.5 still persists/replays thinkingSignature encrypted_content after #84367/#90682/#92941, causing channel/direct LLM request failed

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 231,108 · **Open issues:** 32,248 · **Last push:** <1h ago

### ✅ Merged PRs
- [#87333](https://github.com/NousResearch/hermes-agent/pull/87333) fix(computer-use): placeholder-id targeting + macOS zero-display diagnosis (salvage #81340, #52949, #67259)
- [#87352](https://github.com/NousResearch/hermes-agent/pull/87352) feat: session picker lifecycle status + delete
- [#87346](https://github.com/NousResearch/hermes-agent/pull/87346) feat: per-terminal --continue via terminal breadcrumbs
- [#87345](https://github.com/NousResearch/hermes-agent/pull/87345) feat: import and resume Claude Code / Codex CLI sessions
- [#87337](https://github.com/NousResearch/hermes-agent/pull/87337) test(tool-executor): deterministic worker start kills sequential-timeout flake
- [#87317](https://github.com/NousResearch/hermes-agent/pull/87317) feat(desktop): Skills tab hub browser + full-skill detail pane; drop Browse Hub tab; SkillsView SDK export
- [#87316](https://github.com/NousResearch/hermes-agent/pull/87316) fix(computer-use): diagnose empty window discovery; fail fast on dead-daemon CLI fallback
- [#87312](https://github.com/NousResearch/hermes-agent/pull/87312) feat(desktop): Capabilities-wide profile scoping + one-click hub installs on the Skills tab
- [#87299](https://github.com/NousResearch/hermes-agent/pull/87299) fix(computer-use): merge refs+content_refs in _ref_map for cua-driver 0.17+ (salvage #79515)
- [#87296](https://github.com/NousResearch/hermes-agent/pull/87296) fmt(js): `npm run fix` auto-fix

### 🐛 New Issues
- [#87377](https://github.com/NousResearch/hermes-agent/issues/87377) [Feature]: Add native support for MAIA Router (maiarouter.ai) `type/feature` `comp/cli` `area/config` `P3`
- [#87373](https://github.com/NousResearch/hermes-agent/issues/87373) The window for switching models should display the currently selected model `type/bug` `P3` `needs-repro` `comp/desktop`
- [#87368](https://github.com/NousResearch/hermes-agent/issues/87368) Background review drops gateway ephemeral session context and breaks prompt-cache prefix parity `type/bug` `duplicate` `comp/agent` `comp/gateway` `P0` `sweeper:risk-caching`
- [#87364](https://github.com/NousResearch/hermes-agent/issues/87364) ...hermes bot issue `type/bug` `P2` `needs-repro` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows`
- [#87359](https://github.com/NousResearch/hermes-agent/issues/87359) Hermes Desktop shows spurious 'boot failed' when dashboard service restarts during `hermes update` `type/bug` `P3` `sweeper:risk-compatibility` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows` `area/install-update`
- [#87357](https://github.com/NousResearch/hermes-agent/issues/87357) [Feature]: Desktop — render attached images above the user text (currently below-left, squeezing the gap to the previous reply) `type/feature` `P3` `comp/desktop`
- [#87356](https://github.com/NousResearch/hermes-agent/issues/87356) cronjob update schema omits model/provider (drift-guard remediation is unreachable for agents) `type/bug` `comp/cron` `P2` `needs-decision` `area/billing` 💬1

### 🔒 Closed Issues
- [#87320](https://github.com/NousResearch/hermes-agent/issues/87320) [Bug]: Install scripts gets stuck on Playwrite on Arch
- [#67165](https://github.com/NousResearch/hermes-agent/issues/67165) [Bug]:cua-driver macOS: ScreenCaptureKit display_count=0 despite TCC permissions OK (macOS 26.5.2 arm64)
- [#81333](https://github.com/NousResearch/hermes-agent/issues/81333) [Bug]: computer_use silently discards app= and fails every app-scoped capture when a model emits placeholder pid=0 / window_id=0
- [#83683](https://github.com/NousResearch/hermes-agent/issues/83683) Desktop restart reaps the live gateway but never relaunches it (WeChat/QQ go silent) — regression

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,592 · **Open issues:** 711 · **Last push:** 2h ago

### ✅ Merged PRs
- [#9962](https://github.com/zeroclaw-labs/zeroclaw/pull/9962) ci(cache): route rust-cache through a provider-aware composite action
- [#10001](https://github.com/zeroclaw-labs/zeroclaw/pull/10001) fix(tests): gate non-UTF-8 browser path fixtures to Linux
- [#9523](https://github.com/zeroclaw-labs/zeroclaw/pull/9523) fix(email): honor Reply-To and emit a bracketed RFC 5322 References chain
- [#8877](https://github.com/zeroclaw-labs/zeroclaw/pull/8877) fix(web): portal-render sidebar rail tooltip to escape nav clipping for #8791

### 🐛 New Issues
- [#10023](https://github.com/zeroclaw-labs/zeroclaw/issues/10023) Failure logs claim the requested model, not the pinned fallback model
- [#10022](https://github.com/zeroclaw-labs/zeroclaw/issues/10022) [Bug]: Can't copy text from the ZeroCode chat `bug`
- [#10020](https://github.com/zeroclaw-labs/zeroclaw/issues/10020) [Bug]: Agentic independent delegates ignore the target thinking policy
- [#10019](https://github.com/zeroclaw-labs/zeroclaw/issues/10019) [Docs]: Align the prompt-injection deprecation deadline after Schema V4 `docs` `type:docs`
- [#10018](https://github.com/zeroclaw-labs/zeroclaw/issues/10018) [Bug]: ACP graceful-summary text is silently dropped on max-iteration exit `bug`
- [#10013](https://github.com/zeroclaw-labs/zeroclaw/issues/10013) [Bug]: Edge TTS cancellation test can miss fake child startup under parallel load `bug` `channel` `priority:p1` `status:accepted` `follow-up` `risk:medium` `type:test`
- [#10011](https://github.com/zeroclaw-labs/zeroclaw/issues/10011) [Task]: avoid runtime-written executable in daemon heartbeat test `help wanted` `daemon` `runtime` `priority:p2` `status:accepted` `risk:high` `type:test` 💬1
- [#10008](https://github.com/zeroclaw-labs/zeroclaw/issues/10008) [Task]: prove the plugin wasi:http hook dials the pinned address set (re-resolve mutation is invisible to the egress e2es) `bug` `runtime` `tests` `runtime:wasm` `domain:security` `priority:p1` `tool:web` `status:accepted` `risk:high` `type:test`
- [#10006](https://github.com/zeroclaw-labs/zeroclaw/issues/10006) [Task]: endpoint_lock_is_held_through_guard_cleanup flakes under the Parallel Runtime Test gate on unrelated PRs `bug` `runtime` `tests` `priority:p1` `status:accepted` `risk:high` `type:test` 💬1
- [#9998](https://github.com/zeroclaw-labs/zeroclaw/issues/9998) RFC: Session-scoped persistent prompt attachments `agent` `channel` `config` `gateway` `memory` `runtime` `agent:prompt` `domain:security` `domain:architecture` `priority:p2` `needs-maintainer-review` `type:rfc` `status:no-stale` `zerocode` `risk:high` `channel:acp`

### 🔒 Closed Issues
- [#7527](https://github.com/zeroclaw-labs/zeroclaw/issues/7527) [Bug]: macOS desktop app can reopen blank or without a window
- [#4760](https://github.com/zeroclaw-labs/zeroclaw/issues/4760) [Feature]: use schema-validated tool calls for memory consolidation
- [#8791](https://github.com/zeroclaw-labs/zeroclaw/issues/8791) [Bug]: Left sidebar has incorrect width causing horizontal scrollbar
- [#9955](https://github.com/zeroclaw-labs/zeroclaw/issues/9955) bug(tests): make non-UTF-8 browser path fixtures portable to macOS

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,603 · **Open issues:** 1,496 · **Last push:** <1h ago

### ✅ Merged PRs
- [#7676](https://github.com/nearai/ironclaw/pull/7676) perf(threads): coalesce thread index touches
- [#7629](https://github.com/nearai/ironclaw/pull/7629) perf: reduce trigger and outbound state writes
- [#7628](https://github.com/nearai/ironclaw/pull/7628) perf(processes): remove heartbeat journal churn
- [#7670](https://github.com/nearai/ironclaw/pull/7670) chore(agents): refresh codebase knowledge graph
- [#7634](https://github.com/nearai/ironclaw/pull/7634) feat(unbound-turns): complete the switchover to prepared-context turns

### 🐛 New Issues
- [#7675](https://github.com/nearai/ironclaw/issues/7675) E2E: qa_6c gmail-to-sheet flake cascades across the whole provider-contracts session
- [#7674](https://github.com/nearai/ironclaw/issues/7674) Architecture tests: symbol-level allowlist for the openai-compat → threads edge
- [#7673](https://github.com/nearai/ironclaw/issues/7673) BudgetLedger accounting refinements: truncated-launch reconciliation and charge durability
- [#7672](https://github.com/nearai/ironclaw/issues/7672) Typed ToolChoice: retire the overloaded tool_choice string across providers
- [#7671](https://github.com/nearai/ironclaw/issues/7671) Capability dispatch stack pressure: kernel sandbox path still near the test-stack edge
- [#467](https://github.com/nearai/ironclaw/issues/467) Trajectory benchmark system for agent quality evaluation `scope: evaluation` 💬4

### 🔒 Closed Issues
- [#6821](https://github.com/nearai/ironclaw/issues/6821) IronHub search: free-text matches read as a complete catalog listing
- [#7595](https://github.com/nearai/ironclaw/issues/7595) [Tier 1] Gate prune_run_history instead of running it on every run-history write
- [#6835](https://github.com/nearai/ironclaw/issues/6835) MCP auth failures never raise a re-auth gate (classified as Client, not AuthRequired)
- [#7597](https://github.com/nearai/ironclaw/issues/7597) [Tier 1] Remove dead advance_subscription_cursor durable-offset API
- [#6829](https://github.com/nearai/ironclaw/issues/6829) Telegram forum-topic delivery has no whole-path coverage
- [#6726](https://github.com/nearai/ironclaw/issues/6726) extension host: register_generic_channel_outbound_targets can be a no-op with every test tier green
- [#5672](https://github.com/nearai/ironclaw/issues/5672) perf(webui_v2): replace SSE stream_events drain-and-poll with a real subscription API
- [#4775](https://github.com/nearai/ironclaw/issues/4775) Epic: Automated QA for the Reborn binary (hermetic + fixture + e2e + live)
- [#4629](https://github.com/nearai/ironclaw/issues/4629) Reborn/Crabshack closeout: delete obsolete legacy paths and config
- [#5588](https://github.com/nearai/ironclaw/issues/5588) reborn: track QA-discovered production follow-ups removed from PR #5380

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,820 · **Open issues:** 95 · **Last push:** 1h ago

### ✅ Merged PRs
- [#1200](https://github.com/moltis-org/moltis/pull/1200) chore(deps): bump the npm_and_yarn group across 2 directories with 2 updates
- [#1180](https://github.com/moltis-org/moltis/pull/1180)  fix(security): harden model and zip paths
- [#1158](https://github.com/moltis-org/moltis/pull/1158) feat(memory): add zvec vector database memory backend
- [#1179](https://github.com/moltis-org/moltis/pull/1179) fix(gateway): verify node pairing signatures
- [#1191](https://github.com/moltis-org/moltis/pull/1191) fix(sandbox): point gogcli module path at the openclaw org
- [#1192](https://github.com/moltis-org/moltis/pull/1192) fix(skills): point wacrawl install metadata at the openclaw org
- [#1182](https://github.com/moltis-org/moltis/pull/1182) fix(sessions): allow deleting and archiving the main session
- [#1184](https://github.com/moltis-org/moltis/pull/1184) chore(deps-dev): bump undici from 7.28.0 to 7.29.0 in /website in the npm_and_yarn group across 1 directory
- [#1190](https://github.com/moltis-org/moltis/pull/1190) Add durable calendar, channel, and email connectors
- [#1194](https://github.com/moltis-org/moltis/pull/1194) fix(scripts): guard empty bash array expansions for macOS bash 3.2

### 🔒 Closed Issues
- [#1189](https://github.com/moltis-org/moltis/issues/1189) [Bug]: Sandbox build failing due to wrong gogcli github URL
- [#1132](https://github.com/moltis-org/moltis/issues/1132) [Bug]: "main" session can't be deleted/archived

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 12h ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 3d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 6d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 9d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 9d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 11d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 13d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 13d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 15d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 15d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [Aged like fine wine](https://reddit.com/r/LocalLLaMA/comments/1vp2nmi/aged_like_fine_wine/) ↑925
- [Qwen3.8-27B vs Qwen3.6-27B writing ray-tracers in BASIC](https://reddit.com/r/LocalLLaMA/comments/1vpiyj9/qwen3827b_vs_qwen3627b_writing_raytracers_in_basic/) ↑109

### r/singularity — top 5 new
- [ChatGPT upcoming speed improvements summarized by OpenAI employee](https://reddit.com/r/singularity/comments/1vp3eh6/chatgpt_upcoming_speed_improvements_summarized_by/) ↑402
- [git clone](https://reddit.com/r/singularity/comments/1voue9r/git_clone/) ↑268
- [Alibaba AI Models Hit 3 Billion Downloads, Passing Meta, Google](https://reddit.com/r/singularity/comments/1vp77op/alibaba_ai_models_hit_3_billion_downloads_passing/) ↑226
- [I don’t think we’re psychologically prepared for how alien the world after ASI is going to be](https://reddit.com/r/singularity/comments/1vphdpw/i_dont_think_were_psychologically_prepared_for/) ↑180
- [33 years ago, Vernor Vinge (1944-2024) coined the term "Singularity" in reference to the point at which technological progress, driven by superhumanly intelligent machines, would be so great as to ren](https://reddit.com/r/singularity/comments/1vp5j8u/33_years_ago_vernor_vinge_19442024_coined_the/) ↑176

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Lossless Claw keeps compacting (Codex specific?) -- Anyone else?](https://reddit.com/r/openclaw/comments/1vpdv77/lossless_claw_keeps_compacting_codex_specific/) ↑4
- [too much context leads to LLM slang](https://reddit.com/r/openclaw/comments/1vp0lsr/too_much_context_leads_to_llm_slang/) ↑4
- [OpenClaw on Android, on Any Phone or Computer](https://reddit.com/r/openclaw/comments/1vnw8ue/openclaw_on_android_on_any_phone_or_computer/) ↑4
- [Using my claw on my home network results in lots of captchas](https://reddit.com/r/openclaw/comments/1vp2b5e/using_my_claw_on_my_home_network_results_in_lots/) ↑3
- [OpenClaw + n8n: Scraping and Anti-Bot Challenges](https://reddit.com/r/openclaw/comments/1vo7u58/openclaw_n8n_scraping_and_antibot_challenges/) ↑2

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
_No new tweets in the last 7 days._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
