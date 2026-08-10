---
layout: post
title: "Ecosystem Digest — 2026-08-10"
date: 2026-08-10 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-08-10
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 385,706 | 4 | 0 | 10 | 0 |
| **hermesagent** | 227,967 | 10 | 3 | 9 | 0 |
| **ZeroClaw** | 32,545 | 12 | 7 | 10 | 0 |
| **IronClaw** | 12,596 | 10 | 7 | 3 | 0 |
| **Moltis** | 2,813 | 2 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 385,706 · **Open issues:** 5,651 · **Last push:** <1h ago

### ✅ Merged PRs
- [#121146](https://github.com/openclaw/openclaw/pull/121146) fix(agents): pair reset tool results within retained session history
- [#121253](https://github.com/openclaw/openclaw/pull/121253) fix(qa): reuse one immutable Docker candidate
- [#121346](https://github.com/openclaw/openclaw/pull/121346) fix: preserve GPT-5 personality through doctor migration
- [#121322](https://github.com/openclaw/openclaw/pull/121322) fix(ui): restore Desktop panel launchers
- [#121323](https://github.com/openclaw/openclaw/pull/121323) fix(scripts): fall back to local check:changed lanes on full Crabbox provider outage
- [#121331](https://github.com/openclaw/openclaw/pull/121331) refactor(core): canonicalize record guards on normalization-core
- [#121347](https://github.com/openclaw/openclaw/pull/121347) fix(slack): backport Grid reaction and pin event listeners
- [#121338](https://github.com/openclaw/openclaw/pull/121338) refactor(extensions): remove unused compatibility exports
- [#121334](https://github.com/openclaw/openclaw/pull/121334) fix(protocol): align fallback reason schemas
- [#121014](https://github.com/openclaw/openclaw/pull/121014) feat(slack): add workspace routing for Enterprise Grid actions and events

### 🐛 New Issues
- [#121351](https://github.com/openclaw/openclaw/issues/121351) [Bug]: `stripFormattedReasoningMessage` trims substantive answer body whitespace `bug` `bug:behavior`
- [#121326](https://github.com/openclaw/openclaw/issues/121326) [Bug]: Cannot enable computer use `bug` `regression` 💬2
- [#121319](https://github.com/openclaw/openclaw/issues/121319) [Bug]: dev-channel auto-update campaigns self-terminate after one apply (detached HEAD vs @{upstream} checker) `bug` `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `maturity:stable` 💬1
- [#121317](https://github.com/openclaw/openclaw/issues/121317) [Bug]: Rotating another device's token ends with nothing on screen `bug` `maintainer`

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 227,967 · **Open issues:** 30,190 · **Last push:** <1h ago

### ✅ Merged PRs
- [#77992](https://github.com/NousResearch/hermes-agent/pull/77992) test: gate OS-specific tests by real host, add macOS + Windows CI lanes
- [#82795](https://github.com/NousResearch/hermes-agent/pull/82795) fix(desktop): make un-highlighted code readable while streaming in light theme
- [#82771](https://github.com/NousResearch/hermes-agent/pull/82771) fmt(js): `npm run fix` auto-fix
- [#82741](https://github.com/NousResearch/hermes-agent/pull/82741) fix(desktop-ssh): stop resolving exec-wrappers to python in locateHermes
- [#82743](https://github.com/NousResearch/hermes-agent/pull/82743) fix(gateway): session recovery honors reset boundaries and real idle time (#68617 + #78618 salvage)
- [#82744](https://github.com/NousResearch/hermes-agent/pull/82744) fix(gateway): distinguish durable cached transcript rows (#77895 salvage, fixes #71999)
- [#82742](https://github.com/NousResearch/hermes-agent/pull/82742) fix(gateway): /branch children carry full routing identity at creation (#62278 salvage)
- [#82698](https://github.com/NousResearch/hermes-agent/pull/82698) fix(desktop): send full tool args to desktop so expanded rows show the whole command
- [#80892](https://github.com/NousResearch/hermes-agent/pull/80892) feat(skills): add ast-grep structural search/codemod optional skill (port from oh-my-openagent)

### 🐛 New Issues
- [#82878](https://github.com/NousResearch/hermes-agent/issues/82878) gateway/run: unrecognized busy_input_mode silently falls back to interrupt with no log
- [#82877](https://github.com/NousResearch/hermes-agent/issues/82877) agent/system_prompt: steer-channel note taught to cron sessions that can never receive a real steer
- [#82876](https://github.com/NousResearch/hermes-agent/issues/82876) tool_search: hyphenated MCP server names break tool_describe/tool_call (registry lookup uses unsanitized name)
- [#82875](https://github.com/NousResearch/hermes-agent/issues/82875) reasoning_effort is silently dropped for named `providers:` endpoints — resolved, never sent `type/bug` `duplicate` `comp/agent` `provider/openai` `area/config` `P2` 💬1
- [#82874](https://github.com/NousResearch/hermes-agent/issues/82874) gateway: blocking future.result(timeout=15) in shutdown_mcp_servers() freezes the event loop on SIGTERM; clean-exit marker never written `type/bug` `comp/gateway` `tool/mcp` `area/docker` `P2` `sweeper:risk-session-state` `sweeper:risk-message-delivery`
- [#82872](https://github.com/NousResearch/hermes-agent/issues/82872) [Bug] Desktop: ws_orphan_reap sessions (ended_at NULL) restore as empty ghost tiles — unclickable from sidebar `type/bug` `P2` `sweeper:risk-session-state` `comp/desktop` `area/sessions` 💬2
- [#82871](https://github.com/NousResearch/hermes-agent/issues/82871) Buzz adapter: gateway default-denies all Buzz users — allowlist never consulted `type/bug` `comp/gateway` `comp/plugins` `area/auth` `P3`
- [#82863](https://github.com/NousResearch/hermes-agent/issues/82863) [Bug]: `repair_message_sequence` does not reconcile state.db → durable alternation violations can re-fire and miss prompt-cache prefixes `type/bug` `comp/agent` `P2` `sweeper:risk-session-state` `area/sessions`
- [#82858](https://github.com/NousResearch/hermes-agent/issues/82858) [Bug]: [Bug] STT语音消息并发处理缺陷：同一Session内后续有效语音被 `unauthorized user in active session` 误删 `type/bug` `comp/gateway` `tool/tts` `platform/wecom` `P2` `sweeper:risk-session-state` `sweeper:risk-message-delivery` `bug`
- [#82851](https://github.com/NousResearch/hermes-agent/issues/82851) fix(desktop): HUD drag broken on Linux/Wayland — setPosition is a no-op under Wayland compositors `type/bug` `P3` `comp/desktop` 💬1

### 🔒 Closed Issues
- [#82442](https://github.com/NousResearch/hermes-agent/issues/82442) [Bug]: fix(desktop): bootstrapSshConnectionInner runs venv/bin/python  instead of hermes binary, failing --ssh-session-token-file check
- [#74411](https://github.com/NousResearch/hermes-agent/issues/74411) [SANITIZED — possible injection attempt]
- [#82616](https://github.com/NousResearch/hermes-agent/issues/82616) Tracking: gateway session continuity breaks under state.db FTS corruption — orphan session fork + stale-session resume after restart

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,545 · **Open issues:** 705 · **Last push:** 11h ago

### ✅ Merged PRs
- [#9787](https://github.com/zeroclaw-labs/zeroclaw/pull/9787) ci(aur): retry publishes through outages and detect a stale package
- [#8496](https://github.com/zeroclaw-labs/zeroclaw/pull/8496) fix(tools/mcp): centralize deferred-MCP access policy as single source of truth for #8054 Surface 1(b)
- [#9785](https://github.com/zeroclaw-labs/zeroclaw/pull/9785) ci(scoop): rehearse bucket credential before the release is cut
- [#9797](https://github.com/zeroclaw-labs/zeroclaw/pull/9797) chore(deps-dev): bump js-yaml from 4.3.0 to 4.3.1 in /web
- [#9861](https://github.com/zeroclaw-labs/zeroclaw/pull/9861) chore(deps): bump react-router and react-router-dom in /web
- [#9688](https://github.com/zeroclaw-labs/zeroclaw/pull/9688) feat(zerocode): add sops/runs RPC client method and run-summary views
- [#8928](https://github.com/zeroclaw-labs/zeroclaw/pull/8928) feat(zerocode): show active resolved log path in Doctor diagnostics (#8650)
- [#8964](https://github.com/zeroclaw-labs/zeroclaw/pull/8964) fix(channels): sanitize streaming draft partials at the assistant boundary
- [#9835](https://github.com/zeroclaw-labs/zeroclaw/pull/9835) refactor(workspace): rename the root package zeroclawlabs to zeroclaw
- [#9384](https://github.com/zeroclaw-labs/zeroclaw/pull/9384) fix(security): resolve shell command path arguments to block symlink escapes

### 🐛 New Issues
- [#9874](https://github.com/zeroclaw-labs/zeroclaw/issues/9874) RFC: Rewrite ZeroClaw in Python and retire the Rust codebase `type:rfc`
- [#9872](https://github.com/zeroclaw-labs/zeroclaw/issues/9872) [Bug]: Bounded delegate target resolves filesystem to delegator's workspace instead of own workspace `bug`
- [#9859](https://github.com/zeroclaw-labs/zeroclaw/issues/9859) [Bug]: distroless release image missing sh breaks webhook (runtime.shell) `bug` `config` `gateway` `runtime` `priority:p1` `status:accepted` `risk:high` 💬1
- [#9858](https://github.com/zeroclaw-labs/zeroclaw/issues/9858) [Bug]: memory-postgres NoTls fails against managed Postgres (TLS required) `bug` `dependencies` `config` `memory` `security` `memory:backend` `domain:security` `priority:p1` `status:accepted` `risk:high` 💬1
- [#9857](https://github.com/zeroclaw-labs/zeroclaw/issues/9857) [Bug]: JSONL session operations disagree on valid file types `bug` `runtime` `tests` `priority:p2` `status:accepted` `risk:medium`
- [#9855](https://github.com/zeroclaw-labs/zeroclaw/issues/9855) [Bug]: Matrix channel fails to resolve homeserver via `.well-known/matrix/client` delegation `bug` `docs` `channel` `config` `integration` `runtime` `channel:matrix` `priority:p2` `status:accepted` `risk:high` 💬2
- [#9852](https://github.com/zeroclaw-labs/zeroclaw/issues/9852) Remove aardvark-sys and zeroclaw-robot-kit from the workspace `enhancement` `dependencies` `domain:architecture` `priority:p2` `status:in-progress` `status:accepted` `status:no-stale` `risk:medium` `hardware` 💬1
- [#9851](https://github.com/zeroclaw-labs/zeroclaw/issues/9851) [Bug]: delegate await_sessions timeout status JSON is discarded by the dispatcher (success=false drops output) `bug` `docs` `runtime` `tool` `tool:delegate` `priority:p2` `status:accepted` `follow-up` `risk:high`
- [#9850](https://github.com/zeroclaw-labs/zeroclaw/issues/9850) [Bug]: llm_task builds its provider via the legacy factory, losing alias-specific config (Azure/OAuth/requires_openai_auth) `bug` `config` `provider` `runtime` `tool` `priority:p1` `status:accepted` `follow-up` `risk:high`
- [#9849](https://github.com/zeroclaw-labs/zeroclaw/issues/9849) [Bug]: RateLimitedTool budget check is non-atomic under parallel dispatch (check-before, record-after) `bug` `config` `runtime` `security` `tool` `security:policy` `domain:security` `priority:p2` `status:accepted` `follow-up` `risk:high` 💬1
- [#9845](https://github.com/zeroclaw-labs/zeroclaw/issues/9845) [Feature]: Support non-ASCII characters in agent aliases (e.g. [agents."审核助手"]) `enhancement` `agent` `config` `domain:architecture` `priority:p2` `status:accepted` `risk:high` 💬1
- [#9840](https://github.com/zeroclaw-labs/zeroclaw/issues/9840) [Bug]: daemon steals daemon.sock on start and unlinks it on exit, stranding a live daemon `bug` `daemon` `runtime` `service` `priority:p1` `status:in-progress` `status:accepted` `desktop` `zerocode` `risk:high` 💬1

### 🔒 Closed Issues
- [#8054](https://github.com/zeroclaw-labs/zeroclaw/issues/8054) [SANITIZED — possible injection attempt]
- [#9683](https://github.com/zeroclaw-labs/zeroclaw/issues/9683) [Task]: zerocode client — add sops/runs RPC method and run-summary view type
- [#9860](https://github.com/zeroclaw-labs/zeroclaw/issues/9860) [Bug]: web ui frozen after trigering filesystem channel "created" event
- [#8681](https://github.com/zeroclaw-labs/zeroclaw/issues/8681) [Tracker]: Goal mode implementation split stack
- [#8647](https://github.com/zeroclaw-labs/zeroclaw/issues/8647) [Bug]: ZeroCode Doctor timeout hides which diagnostic is stuck
- [#8598](https://github.com/zeroclaw-labs/zeroclaw/issues/8598) [Bug]: skills install cannot install owner-qualified ClawHub skill URLs
- [#8560](https://github.com/zeroclaw-labs/zeroclaw/issues/8560) [Bug]: browser_open hangs the agent turn when the launcher cannot open a window (unbounded subprocess wait, also affects robot-kit TTS and channels ffmpeg)

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,596 · **Open issues:** 1,492 · **Last push:** <1h ago

### ✅ Merged PRs
- [#7171](https://github.com/nearai/ironclaw/pull/7171) fix(skills): one DB-backed tree for every skill mount, and make a skill's own commands runnable (closes #7168)
- [#7323](https://github.com/nearai/ironclaw/pull/7323) ci(nightly): grant actions: read to the reborn-tests call contract
- [#7399](https://github.com/nearai/ironclaw/pull/7399) chore(agents): refresh codebase knowledge graph

### 🐛 New Issues
- [#7407](https://github.com/nearai/ironclaw/issues/7407) Execute BatchPolicy::Parallel capability batches concurrently in invoke_capability_batch 💬2
- [#7405](https://github.com/nearai/ironclaw/issues/7405) Improve deferred tool discovery with complete signatures and namespace-aware catalog previews `enhancement` `scope: tool` `scope: evaluation` `performance` 💬2
- [#7400](https://github.com/nearai/ironclaw/issues/7400) Bug: `stream: true` + caller `tools[]` on `/api/v1/responses` fails mid-stream and leaves a permanently undeletable ("zombie") thread 💬2
- [#7392](https://github.com/nearai/ironclaw/issues/7392) Experiment: Replace first-party coding tools with the pinned omp tool surface `epic`
- [#7360](https://github.com/nearai/ironclaw/issues/7360) Expand stress coverage across built-in and durable write paths `enhancement` `scope: tool/builtin` `scope: ci` `e2e-coverage` `performance` 💬2
- [#7349](https://github.com/nearai/ironclaw/issues/7349) Refreshing the chat causes part of the run history and Activity timeline to disappear `bug_bash_P2` `qa-bug` 💬2
- [#7348](https://github.com/nearai/ironclaw/issues/7348) Activity tool calls and assistant progress messages are displayed in the wrong chronological order `bug_bash_P2` `qa-bug` 💬2
- [#7346](https://github.com/nearai/ironclaw/issues/7346) Emoji shortcodes are displayed as plain text in assistant messages `bug_bash_P2` `qa-bug` 💬2
- [#7345](https://github.com/nearai/ironclaw/issues/7345) Agent reports 61 automations while UI shows only 50 `bug_bash_P2` `qa-bug` 💬2
- [#7166](https://github.com/nearai/ironclaw/issues/7166) Tool disclosure follow-up `epic` `v1.2.0` 💬1

### 🔒 Closed Issues
- [#7292](https://github.com/nearai/ironclaw/issues/7292) Installed tool cannot be used and run fails with runner heartbeat error
- [#5552](https://github.com/nearai/ironclaw/issues/5552) Run fails with generic "invalid result" after multiple tool failures
- [#5522](https://github.com/nearai/ironclaw/issues/5522) [QA] Reborn routine fails (status=Failed) when task requires reading Slack DMs — no Slack read capability + capability_info retry loop
- [#5510](https://github.com/nearai/ironclaw/issues/5510) [QA] Cannot delete old routines
- [#5509](https://github.com/nearai/ironclaw/issues/5509) [QA] Chat creation latency scales with accumulated conversation history
- [#4344](https://github.com/nearai/ironclaw/issues/4344) [QA] Agent mirrors user message as its own response while loading (Qwen3.6-35B-A3B-FP8)
- [#4341](https://github.com/nearai/ironclaw/issues/4341) [QA] Agent THINKING chain-of-thought exposed to user and stuck in thinking state (Qwen3.6-35B-A3B-FP8)

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,813 · **Open issues:** 98 · **Last push:** 1d ago

### 🐛 New Issues
- [#1187](https://github.com/moltis-org/moltis/issues/1187) [Bug]: Heartbeat settings UI silently resets fields not represented by the form `bug`
- [#1185](https://github.com/moltis-org/moltis/issues/1185) [Bug]: Apple Container 1.x sandbox starts but Moltis treats it as not running

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 18h ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 22h ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 3d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 3d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 5d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 7d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 7d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 9d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 9d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 13d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [The Gemma team will host a special event on August 20](https://reddit.com/r/LocalLLaMA/comments/1vk0o98/the_gemma_team_will_host_a_special_event_on/) ↑272
- [Lophius: A workbench for language model research, from the creator of Heretic](https://reddit.com/r/LocalLLaMA/comments/1vjt4vi/lophius_a_workbench_for_language_model_research/) ↑254
- [DeepSeek V4 Flash 0731 hits 82.7% on Terminal-Bench 2.1 in an independent public-harness run (445 trials)](https://reddit.com/r/LocalLLaMA/comments/1vjklwo/deepseek_v4_flash_0731_hits_827_on_terminalbench/) ↑234
- [Speculative decoding in a tools call](https://reddit.com/r/LocalLLaMA/comments/1vjxhof/speculative_decoding_in_a_tools_call/) ↑200
- [Open Model: Google Weather Next 2](https://reddit.com/r/LocalLLaMA/comments/1vjwwrs/open_model_google_weather_next_2/) ↑97

### r/singularity — top 5 new
- [Google needs to up their game](https://reddit.com/r/singularity/comments/1vjwcke/google_needs_to_up_their_game/) ↑1626
- [Demis Hassabis Expects All Diseases To Be Cured Within 20 Years](https://reddit.com/r/singularity/comments/1vjgmqi/demis_hassabis_expects_all_diseases_to_be_cured/) ↑759
- [More info about upcoming models Astra and Doug](https://reddit.com/r/singularity/comments/1vjxnaq/more_info_about_upcoming_models_astra_and_doug/) ↑203
- [AiBattle (@AiBattle_) on X: "Potential new GPT-Image model has appeared on the Arena under the name "Mona-lisa-1""](https://reddit.com/r/singularity/comments/1vjq7z2/aibattle_aibattle_on_x_potential_new_gptimage/) ↑199
- [Does anyone remember lk-99?](https://reddit.com/r/singularity/comments/1vjozv4/does_anyone_remember_lk99/) ↑147

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Openclaw 2026.4.24 vs 2026.5.7 vs 2026.7.1 real work loop regresion](https://reddit.com/r/openclaw/comments/1vjjanr/openclaw_2026424_vs_202657_vs_202671_real_work/) ↑12
- [[P] Building a Persistent Artificial Scientist: Independent Validation of Cross-Domain Concept Transfer](https://reddit.com/r/openclaw/comments/1vk23od/p_building_a_persistent_artificial_scientist/) ↑3
- [How has your OpenClaw setup and workflow evolved in the last few months?](https://reddit.com/r/openclaw/comments/1vjm8qq/how_has_your_openclaw_setup_and_workflow_evolved/) ↑3
- [Openclaw is so unreliable..](https://reddit.com/r/openclaw/comments/1vjyrkv/openclaw_is_so_unreliable/) ↑2
- [Best budget setup?](https://reddit.com/r/openclaw/comments/1vk7ywv/best_budget_setup/) ↑1

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
- [I’ll totally use this in my next presentation.](https://x.com/steipete/status/2085074976290505090) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
