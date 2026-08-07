---
layout: post
title: "Ecosystem Digest — 2026-08-07"
date: 2026-08-07 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-08-07
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 385,392 | 5 | 3 | 10 | 0 |
| **hermesagent** | 226,630 | 2 | 2 | 4 | 0 |
| **ZeroClaw** | 32,525 | 12 | 9 | 10 | 0 |
| **IronClaw** | 12,594 | 13 | 10 | 10 | 1 |
| **Moltis** | 2,810 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 385,392 · **Open issues:** 5,546 · **Last push:** <1h ago

### ✅ Merged PRs
- [#120088](https://github.com/openclaw/openclaw/pull/120088) fix(release): isolate private Telegram QA harness
- [#116793](https://github.com/openclaw/openclaw/pull/116793) refactor(agents): centralize immutable execution attribution
- [#116204](https://github.com/openclaw/openclaw/pull/116204) fix(google): accept base64url provider media
- [#118601](https://github.com/openclaw/openclaw/pull/118601) fix(plugins): warn when registerHook uses a typed hook event name
- [#117961](https://github.com/openclaw/openclaw/pull/117961) fix(canvas): serve Content-Length on A2UI HEAD responses
- [#118749](https://github.com/openclaw/openclaw/pull/118749) fix(gateway): make doctor dreaming timestamp comparators NaN-safe
- [#119689](https://github.com/openclaw/openclaw/pull/119689) fix(heartbeat): explain target-none skips
- [#120011](https://github.com/openclaw/openclaw/pull/120011) [SANITIZED — possible injection attempt]
- [#120085](https://github.com/openclaw/openclaw/pull/120085) fix(plugins): preserve startup release during repair
- [#120101](https://github.com/openclaw/openclaw/pull/120101) refactor(browser): remove model-backed page extraction

### 🐛 New Issues
- [#120103](https://github.com/openclaw/openclaw/issues/120103) Vendor-prefix redaction patterns lack word boundaries, corrupting ordinary identifiers `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:session-state` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1
- [#120099](https://github.com/openclaw/openclaw/issues/120099) Feature: preserve channel conversation as a visible session after /new 💬1
- [#120074](https://github.com/openclaw/openclaw/issues/120074) Gateway blocks its event loop for tens of seconds after every agent turn on multi-agent installs 💬1
- [#120072](https://github.com/openclaw/openclaw/issues/120072) Cross-channel approval-reaction semantics diverge (iMessage tapback docs vs tests; Matrix unauthorized fall-through) `bug` `maintainer` `P2` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1
- [#120070](https://github.com/openclaw/openclaw/issues/120070) Imported before_tool_call hook appears to be skipped for browser over /tools/invoke `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` 💬2

### 🔒 Closed Issues
- [#44534](https://github.com/openclaw/openclaw/issues/44534) Heartbeat skipped reason 'target-none' is misleading when delivery is disabled by default
- [#120003](https://github.com/openclaw/openclaw/issues/120003) [SANITIZED — possible injection attempt]
- [#120035](https://github.com/openclaw/openclaw/issues/120035) Dependency-ready Workboard cards not reliably claimed by automatic dispatch (--admin) despite manual dispatch working

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 226,630 · **Open issues:** 29,126 · **Last push:** <1h ago

### ✅ Merged PRs
- [#80422](https://github.com/NousResearch/hermes-agent/pull/80422) Fireworks user agent
- [#80699](https://github.com/NousResearch/hermes-agent/pull/80699) The desktop's tools reach it on remote and cloud backends too
- [#80491](https://github.com/NousResearch/hermes-agent/pull/80491) fix(launchd): stop stranding the gateway label on plist reload (salvage #79868)
- [#80515](https://github.com/NousResearch/hermes-agent/pull/80515) refactor(skills): move polymarket to optional-skills/finance

### 🐛 New Issues
- [#80710](https://github.com/NousResearch/hermes-agent/issues/80710) [Bug]: Desktop self-update can corrupt the existing runtime on Windows `bug`
- [#80680](https://github.com/NousResearch/hermes-agent/issues/80680) [Bug]: Desktop “Show earlier messages” disappears before reaching the true session start `type/bug` `P2` `needs-repro` `sweeper:risk-session-state` `comp/desktop` `area/sessions` `area/compression` 💬1

### 🔒 Closed Issues
- [#80395](https://github.com/NousResearch/hermes-agent/issues/80395) macOS: deferred reload helper (post-#69500) still declares success while old gateway job is mid-drain, leaving service unregistered
- [#80437](https://github.com/NousResearch/hermes-agent/issues/80437) MCP stdio bridge crash: TypeError 'Value after * must be an iterable, not NoneType' when args is null in config

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,525 · **Open issues:** 698 · **Last push:** <1h ago

### ✅ Merged PRs
- [#8927](https://github.com/zeroclaw-labs/zeroclaw/pull/8927) fix(providers): remove unconditional strip_think_tags from compatible provider (#8615)
- [#9659](https://github.com/zeroclaw-labs/zeroclaw/pull/9659) fix(docs): disambiguate contextual protected literals
- [#9737](https://github.com/zeroclaw-labs/zeroclaw/pull/9737) fix(tools): enforce agent policy in pipelines
- [#8943](https://github.com/zeroclaw-labs/zeroclaw/pull/8943) fix(providers): exclude Nova 2 from Bedrock prompt caching (#8720)
- [#9329](https://github.com/zeroclaw-labs/zeroclaw/pull/9329) refactor(zerocode): derive slash commands from the shared command catalogue
- [#9764](https://github.com/zeroclaw-labs/zeroclaw/pull/9764) test(config): widen scheduler-latency margin in onepassword non-blocking load test
- [#9208](https://github.com/zeroclaw-labs/zeroclaw/pull/9208) fix(runtime): stop per-iteration tool-schema deep clones in the agent loop
- [#9704](https://github.com/zeroclaw-labs/zeroclaw/pull/9704) fix(cli): make cron add help examples run as printed (#9672)
- [#9201](https://github.com/zeroclaw-labs/zeroclaw/pull/9201) fix(runtime): harden dormant shared iteration reservation
- [#9200](https://github.com/zeroclaw-labs/zeroclaw/pull/9200) feat(providers): add Atlas Cloud model provider

### 🐛 New Issues
- [#9800](https://github.com/zeroclaw-labs/zeroclaw/issues/9800) bug(zerocode): SIGTERM leaves terminal raw and mouse-tracking modes enabled
- [#9799](https://github.com/zeroclaw-labs/zeroclaw/issues/9799) bug(daemon): long-lived ephemeral daemon spins above 100% CPU with repeated database handles
- [#9796](https://github.com/zeroclaw-labs/zeroclaw/issues/9796) [Bug]: cron parent help prints invalid add-at, add-every, and once examples `bug` `docs` `core` `cron` `channel:cli` `priority:p2` `status:accepted` `risk:low`
- [#9792](https://github.com/zeroclaw-labs/zeroclaw/issues/9792) git channel: empty peer allowlist silently drops every event (including sop routes) at DEBUG `bug` `channel` `observability` `priority:p2` `tool:sop` `status:in-progress` `risk:medium`
- [#9788](https://github.com/zeroclaw-labs/zeroclaw/issues/9788) [SANITIZED — possible injection attempt] `enhancement` `runtime` `agent:prompt` `tool:shell` `status:blocked` `priority:p3` `risk:medium`
- [#9786](https://github.com/zeroclaw-labs/zeroclaw/issues/9786) SOP: a malformed SOP.toml is silently dropped — sop list omits it and sop validate reports success `bug` `docs` `runtime` `priority:p1` `tool:sop` `risk:high` `cli` 💬1
- [#9784](https://github.com/zeroclaw-labs/zeroclaw/issues/9784) SOP: multi-step agent-driven run marked failed mid-step with no audit event `bug` `observability` `runtime` `priority:p2` `tool:sop` `risk:high`
- [#9783](https://github.com/zeroclaw-labs/zeroclaw/issues/9783) SOP: finish_run accepts a failure reason and discards it — failed runs record no cause `bug` `observability` `runtime` `priority:p2` `tool:sop` `risk:medium`
- [#9780](https://github.com/zeroclaw-labs/zeroclaw/issues/9780) [sop] cron-triggered SOPs cannot do network work: no http capability, and shell.exec/notify.channel are unsatisfiable placeholders `enhancement` `docs` `cron` `runtime` `priority:p2` `tool:sop` `risk:high` 💬1
- [#9779](https://github.com/zeroclaw-labs/zeroclaw/issues/9779) [sop] sops_dir: documented default is not honoured by the daemon, so SOPs silently never load `bug` `docs` `config` `daemon` `runtime` `priority:p1` `tool:sop` `status:in-progress` `risk:high` 💬1
- [#9771](https://github.com/zeroclaw-labs/zeroclaw/issues/9771) [Task]: zeroclaw-gateway fails clippy -D warnings on the default feature surface `bug` `gateway` `tests` `priority:p2` `risk:high` `type:ci`
- [#9770](https://github.com/zeroclaw-labs/zeroclaw/issues/9770) [Task]: cron update silently discards changes to declarative jobs (six columns) `bug` `core` `cron` `runtime` `tests` `priority:p1` `risk:high` `cli`

### 🔒 Closed Issues
- [#8615](https://github.com/zeroclaw-labs/zeroclaw/issues/8615) [Bug]: compatible provider silently deletes content via unconditional `<think>` tag stripping
- [#9657](https://github.com/zeroclaw-labs/zeroclaw/issues/9657) [Bug]: protected-literal checker mistakes generic "Signal" for channel name
- [#7947](https://github.com/zeroclaw-labs/zeroclaw/issues/7947) [SANITIZED — possible injection attempt]
- [#8720](https://github.com/zeroclaw-labs/zeroclaw/issues/8720) [Support]: Disable cachePoint for Bedrock Nova 2 Lite model via config file?
- [#9172](https://github.com/zeroclaw-labs/zeroclaw/issues/9172) [Feature]: Use one command descriptor source for ZeroCode slash commands
- [#9763](https://github.com/zeroclaw-labs/zeroclaw/issues/9763) [Bug]: flaky test: onepassword_reference_load_does_not_block_runtime_worker fails under CI runner load
- [#9672](https://github.com/zeroclaw-labs/zeroclaw/issues/9672) [Bug]: none of the three `cron add` examples in the CLI help run as printed, and the empty-state hint prints a fourth broken form
- [#1](https://github.com/zeroclaw-labs/zeroclaw/issues/1) [CRITICAL] XOR cipher provides no real encryption for stored secrets
- [#657](https://github.com/zeroclaw-labs/zeroclaw/issues/657) [Feature]: Support for Kimi Code provider

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,594 · **Open issues:** 1,516 · **Last push:** <1h ago

### 🚀 New Releases
- [ironclaw-v1.1.0](https://github.com/nearai/ironclaw/releases/tag/ironclaw-v1.1.0) — 1.1.0 - 2026-08-06

### ✅ Merged PRs
- [#7235](https://github.com/nearai/ironclaw/pull/7235) feat(inspector): add operator inspection API and live updates
- [#7259](https://github.com/nearai/ironclaw/pull/7259) docs: enforce the docs/ publication boundary (frozen .mintignore + CI gate) and consolidate internal docs under docs/internal/
- [#7303](https://github.com/nearai/ironclaw/pull/7303) fix(docker): install curl so orchestrator healthchecks can run
- [#7272](https://github.com/nearai/ironclaw/pull/7272) fix(host-runtime): steer public web retrieval to web search
- [#7286](https://github.com/nearai/ironclaw/pull/7286) fix(libsql): avoid repeated FTS backfills
- [#7270](https://github.com/nearai/ironclaw/pull/7270) feat(skills): add railway-test developer skill for Railway preview QA
- [#7264](https://github.com/nearai/ironclaw/pull/7264) Guidance layer: a family AGENTS.md for every family, a README for every crate, and a repo-wide stale sweep
- [#7263](https://github.com/nearai/ironclaw/pull/7263) Program closure: the defect train, the await-edge ruling, and the WS12 100% gate
- [#7135](https://github.com/nearai/ironclaw/pull/7135) fix(loop): preserve pageable result_read continuation references
- [#7230](https://github.com/nearai/ironclaw/pull/7230) feat(inspector): add bounded diagnostic session storage

### 🐛 New Issues
- [#7310](https://github.com/nearai/ironclaw/issues/7310) Capability enforcement does not cover built-in tools; tool results are not bound to a tool_use_id
- [#7308](https://github.com/nearai/ironclaw/issues/7308) Hosted MCP OAuth registration for Attio fails with invalid scope and cannot be corrected `bug` `scope: tool/mcp` `OAuth / Authorization` `extensions` `oauth`
- [#7307](https://github.com/nearai/ironclaw/issues/7307) Attio extension calls fail with opaque operation_failed instead of auth_required `bug` `scope: extensions` `extensions`
- [#7302](https://github.com/nearai/ironclaw/issues/7302) Improve tool call UI when one of the calls failed `webui`
- [#7298](https://github.com/nearai/ironclaw/issues/7298) Request fails before it could be sent / monitoring system loses contact with runner `bug_bash_P1` `qa-bug`
- [#7297](https://github.com/nearai/ironclaw/issues/7297) Error messages stack up in UI after every failed prompt `bug_bash_P2` `qa-bug`
- [#7295](https://github.com/nearai/ironclaw/issues/7295) Agent leaks or confuses Slack user identity in response `bug_bash_P1` `qa-bug`
- [#7294](https://github.com/nearai/ironclaw/issues/7294) Agent incorrectly remembers a Telegram routine from another scope or thread `bug_bash_P1` `qa-bug`
- [#7293](https://github.com/nearai/ironclaw/issues/7293) Agent unnecessarily checks skills when asked to remove routines `bug_bash_P2` `qa-bug` 💬1
- [#7292](https://github.com/nearai/ironclaw/issues/7292) Installed tool cannot be used and run fails with runner heartbeat error `bug_bash_P1` `qa-bug` 💬1
- [#7287](https://github.com/nearai/ironclaw/issues/7287) Complete Web Inspector statistics, navigation, and localization
- [#7276](https://github.com/nearai/ironclaw/issues/7276) Reborn: automatically promote useful conversation facts into durable cross-conversation memory `scope: workspace` `feature-request` `feedback`
- [#7275](https://github.com/nearai/ironclaw/issues/7275) Reborn: verify explicit persistent memory recall across conversations in production `bug` `scope: workspace` `feedback` 💬3

### 🔒 Closed Issues
- [#7220](https://github.com/nearai/ironclaw/issues/7220) [Inspector] Add the operator inspection API and live stream
- [#3533](https://github.com/nearai/ironclaw/issues/3533) [QA] Telegram in v 0.28.1 does not automatically setup from UI
- [#3535](https://github.com/nearai/ironclaw/issues/3535) [QA] UI Timestamps are incorrect for conversations
- [#4338](https://github.com/nearai/ironclaw/issues/4338) [QA] Disconnected state shows misleading execution driver error (MiniMax-M2.7)
- [#5418](https://github.com/nearai/ironclaw/issues/5418) [QA] Conversation messages appear in wrong order after tool activity
- [#5419](https://github.com/nearai/ironclaw/issues/5419) [QA] No option to rename an automation
- [#5457](https://github.com/nearai/ironclaw/issues/5457) [QA] Logs page remains empty and never loads log entries
- [#5458](https://github.com/nearai/ironclaw/issues/5458) [QA] Double header displayed on Logs page
- [#5504](https://github.com/nearai/ironclaw/issues/5504) [QA] Routine creation hangs without returning result or error
- [#5505](https://github.com/nearai/ironclaw/issues/5505) [QA] Routine creation prompt is embedded inside the created routine

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,810 · **Open issues:** 97 · **Last push:** 2d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 13h ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 15h ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 22h ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 2d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 4d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 4d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 6d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 6d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 10d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 16d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 2 new
- [[Index] How The World Is Putting Chatgpt To Work](https://openai.com/index/how-the-world-is-putting-chatgpt-to-work/) _2026-08-07_
- [[Index] Openai And Apa Partner To Advance Responsible Ai](https://openai.com/index/openai-and-apa-partner-to-advance-responsible-ai/) _2026-08-06_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [Qwen 3.8 Max now ranked as best overall model ahead of Opus 5 by Artificial Analysis agentic index](https://reddit.com/r/LocalLLaMA/comments/1vhd416/qwen_38_max_now_ranked_as_best_overall_model/) ↑835
- [They almost catched up on Frontier performance, so now catching up on prices](https://reddit.com/r/LocalLLaMA/comments/1vh2pss/they_almost_catched_up_on_frontier_performance_so/) ↑636

### r/singularity — top 5 new
- [Where would Google be today if it had released ChatGPT-like assistant before OpenAI?](https://reddit.com/r/singularity/comments/1vdeifa/where_would_google_be_today_if_it_had_released/) ↑1483
- [OpenAI to release GPT Astra next week](https://reddit.com/r/singularity/comments/1vh56q9/openai_to_release_gpt_astra_next_week/) ↑727
- [spooky...](https://reddit.com/r/singularity/comments/1vhes22/spooky/) ↑444
- [Reddit is introducing a new moderator: AI](https://reddit.com/r/singularity/comments/1vgy45f/reddit_is_introducing_a_new_moderator_ai/) ↑369
- [Anthropic CEO reportedly worried new hires only care about money — while hiring an event planner for 6x the going rate](https://reddit.com/r/singularity/comments/1vhe3a1/anthropic_ceo_reportedly_worried_new_hires_only/) ↑236

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Is openclaw dead?](https://reddit.com/r/openclaw/comments/1vhg5dx/is_openclaw_dead/) ↑25
- [Compaction - failes over failes](https://reddit.com/r/openclaw/comments/1vh4e4t/compaction_failes_over_failes/) ↑5
- [Out of tokens, how do I monitor usage?](https://reddit.com/r/openclaw/comments/1vgxll0/out_of_tokens_how_do_i_monitor_usage/) ↑4
- [OpenClaw + Ollama: Seeking agentic models with functional Reasoning Toggles on budget hardware (Intel N150 / 12GB RAM)](https://reddit.com/r/openclaw/comments/1vh0o3m/openclaw_ollama_seeking_agentic_models_with/) ↑2
- [Trying  since hours to set up openclaw but get rejected by lots of different errors.](https://reddit.com/r/openclaw/comments/1vh9erj/trying_since_hours_to_set_up_openclaw_but_get/) ↑1

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
_No new tweets in the last 7 days._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
