---
layout: post
title: "Ecosystem Digest — 2026-11-01"
date: 2026-11-01 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-01
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 393,565 | 4 | 2 | 10 | 0 |
| **hermesagent** | 259,200 | 15 | 1 | 3 | 0 |
| **ZeroClaw** | 33,080 | 13 | 4 | 5 | 0 |
| **IronClaw** | 12,701 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,936 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 393,565 · **Open issues:** 7,891 · **Last push:** <1h ago

### ✅ Merged PRs
- [#189512](https://github.com/openclaw/openclaw/pull/189512) fix: session assessments stop after five-second Codex discovery
- [#189952](https://github.com/openclaw/openclaw/pull/189952) fix(state): admit native agent lease release during close
- [#189836](https://github.com/openclaw/openclaw/pull/189836) perf(test): reuse private changed-lane repository seeds
- [#189959](https://github.com/openclaw/openclaw/pull/189959) fix(tests): reach release policy checks from temporary repositories
- [#189821](https://github.com/openclaw/openclaw/pull/189821) perf(control-ui): mount only visible sidebar rows and prepare advertised methods once
- [#189893](https://github.com/openclaw/openclaw/pull/189893) refactor(runtime): defer unused model pricing lookup
- [#189917](https://github.com/openclaw/openclaw/pull/189917) fix(ui): saving a provider key says when the model policy hides its models
- [#189954](https://github.com/openclaw/openclaw/pull/189954) fix(browser): recover after the Chrome relay owner disconnects
- [#189833](https://github.com/openclaw/openclaw/pull/189833) perf(test): reuse private unborn SDK fixture seeds
- [#189945](https://github.com/openclaw/openclaw/pull/189945) fix(test): scope reaper assertions to owned listeners

### 🐛 New Issues
- [#189962](https://github.com/openclaw/openclaw/issues/189962) [Bug]: invalid --limit/--max-bytes/--interval/--timeout/--probe-timeout values print only a generic 'The CLI command failed.' with no reason `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬1
- [#189957](https://github.com/openclaw/openclaw/issues/189957) [Bug]: `openclaw path find 'oc://x.jsonl/**/key'` returns no matches for keys nested inside JSONL line values `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#189955](https://github.com/openclaw/openclaw/issues/189955) [SANITIZED — possible injection attempt] `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#189947](https://github.com/openclaw/openclaw/issues/189947) [Bug]: Failure alerts for delivery.target "owner" automations resolve the session's last route instead of the owner DM `bug` `bug:behavior` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:security` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#189508](https://github.com/openclaw/openclaw/issues/189508) Session observer assessments stop when Codex model discovery takes five seconds
- [#137247](https://github.com/openclaw/openclaw/issues/137247) # ACP bridge: fallback session key has no agent owner in multi-agent mode

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬67 · <1h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 259,200 · **Open issues:** 52,223 · **Last push:** <1h ago

### ✅ Merged PRs
- [#147172](https://github.com/NousResearch/hermes-agent/pull/147172) fix(desktop-plugins): host reconcile treats Windows junctions as links; Desktop/ tested on a real case-insensitive volume
- [#147164](https://github.com/NousResearch/hermes-agent/pull/147164) fix(update): update-lock tidy-ups from the #146396 reviews
- [#146417](https://github.com/NousResearch/hermes-agent/pull/146417) fix(desktop): a native plugin install never replaces a folder outside desktop-plugins

### 🐛 New Issues
- [#147393](https://github.com/NousResearch/hermes-agent/issues/147393) [Feature]: Desktop approval-timeout recovery with stale-command guard
- [#147387](https://github.com/NousResearch/hermes-agent/issues/147387) Gated dashboard middleware rejects Desktop token-mode credentials (X-Hermes-Session-Token header / ?token=) — Remote gateway connections fail on any auth-gated dashboard
- [#147386](https://github.com/NousResearch/hermes-agent/issues/147386) [Bug]: Desktop: the divider line between a bot's processing and its response doesn't render (it shows on iOS) `bug`
- [#147385](https://github.com/NousResearch/hermes-agent/issues/147385) [Feature]: Desktop sidebar: make bot status clear at a glance
- [#147384](https://github.com/NousResearch/hermes-agent/issues/147384) Memory plugin config_schema.py loaded standalone breaks relative imports (ModuleNotFoundError: _hermes_memory_config_schema)
- [#147383](https://github.com/NousResearch/hermes-agent/issues/147383) Memory provider stays 'activated' after initialize() fails — half-built provider crashes every hook for the process lifetime
- [#147379](https://github.com/NousResearch/hermes-agent/issues/147379) [Bug] Gateway delivery ledger: a failed mark_attempting leaves a delivered reply 'pending', so the next restart resends it with no duplicate marker
- [#147377](https://github.com/NousResearch/hermes-agent/issues/147377) [Bug]: Login-stamped legacy Bot Chat row (source 'tui') can't be adopted by any actor or displaced; message_agent gets not_found permanently `bug`
- [#147374](https://github.com/NousResearch/hermes-agent/issues/147374) ctx.register_skill() accepts a directory and only fails later, at skill_view() read time
- [#147373](https://github.com/NousResearch/hermes-agent/issues/147373) Masked Destruction: Hermes Agent’s Smart Approval Auto-Approved a PowerShell Command That Removed 188,303 Files and Freed 21.4 GiB of User Data `bug` 💬1
- [#147371](https://github.com/NousResearch/hermes-agent/issues/147371) [Bug][Mobile iOS beta] Filter options intermittently missing on startup (Webhook runs, Project) 💬1
- [#147368](https://github.com/NousResearch/hermes-agent/issues/147368) Desktop queued-busy-input admissions re-deliver after later turns; delivered messages sometimes never render
- [#147366](https://github.com/NousResearch/hermes-agent/issues/147366) Kanban gateway shutdown consumes a task's failure budget 💬1
- [#147364](https://github.com/NousResearch/hermes-agent/issues/147364) Subdirectory AGENTS.md hint is re-sent on every turn after the agent is rebuilt
- [#147361](https://github.com/NousResearch/hermes-agent/issues/147361) [Bug]: Mobile app chat WebSocket always 403 on a remote gateway Webapp (Origin-less subprotocol ticket rejected in run_api.py before the ticket gate) 💬1

### 🔒 Closed Issues
- [#147345](https://github.com/NousResearch/hermes-agent/issues/147345) [Bug]: Android beta shows thinking notification but no notification when final reply completes

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,080 · **Open issues:** 1,132 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11940](https://github.com/zeroclaw-labs/zeroclaw/pull/11940) fix(enroll): redeem enrollment codes on the daemon's canonical pairing guard
- [#11822](https://github.com/zeroclaw-labs/zeroclaw/pull/11822) fix(security): split POSIX commands at substitution and subshell boundaries
- [#12071](https://github.com/zeroclaw-labs/zeroclaw/pull/12071) feat(zerocode): add /load-session to resume a saved session by name or id
- [#12111](https://github.com/zeroclaw-labs/zeroclaw/pull/12111) feat(install): install the CLI-only build and switch it to the standard build only on request
- [#12129](https://github.com/zeroclaw-labs/zeroclaw/pull/12129) fix(deps): bump Wasmtime to 48.0.8 for RUSTSEC-2026-0420 to 0424

### 🐛 New Issues
- [#12169](https://github.com/zeroclaw-labs/zeroclaw/issues/12169) [Bug]: send_message_to_peer starts the recipient's turn outside the tool scope of the headless SOP step that called it
- [#12167](https://github.com/zeroclaw-labs/zeroclaw/issues/12167) [Bug]: send_message_to_peer ignores the sender's autonomy level and action budget
- [#12158](https://github.com/zeroclaw-labs/zeroclaw/issues/12158) Security review findings: 10 unpatched vulnerabilities (reference implementations available)
- [#12156](https://github.com/zeroclaw-labs/zeroclaw/issues/12156) [Bug]: zeroclaw update always downloads the glibc build, so it can't update a musl install `bug`
- [#12155](https://github.com/zeroclaw-labs/zeroclaw/issues/12155) [Bug]: Cancelled quickstart says "No config written" but ~/.zeroclaw/config.toml exists afterwards `bug`
- [#12154](https://github.com/zeroclaw-labs/zeroclaw/issues/12154) [Bug]: install.sh shows the build commit instead of the version: "Installed: … (v(99bd353), 74M)" `bug`
- [#12153](https://github.com/zeroclaw-labs/zeroclaw/issues/12153) [Bug]: install.sh picks the musl build on glibc hosts that have the musl package installed `bug`
- [#12152](https://github.com/zeroclaw-labs/zeroclaw/issues/12152) [Task]: give the PowerShell tests in `platform/native.rs` their own PowerShell cache
- [#12147](https://github.com/zeroclaw-labs/zeroclaw/issues/12147) [Bug]: the audit log is created with default permissions inside a 0755 config directory and `agent_alias` sits outside the hash chain, so other local users can read the tool-call history and a same-us `bug` `observability` `security` `domain:security`
- [#12146](https://github.com/zeroclaw-labs/zeroclaw/issues/12146) [Bug]: the MCP SSE client accepts an absolute URL from the server's `endpoint` event and posts there with the configured secret headers, so a server can redirect the daemon's requests and bearer token `bug` `security` `security:secrets` `domain:security` `tool:mcp`
- [#12145](https://github.com/zeroclaw-labs/zeroclaw/issues/12145) [Bug]: the plugin store limiter caps each linear memory at `max_memory_mb` and instances at 64 but keeps wasmtime's defaults of 10,000 memories and 10,000 tables per store, so a plugin can commit thou `bug` `security` `runtime:wasm` `domain:security` `topic:plugins`
- [#12144](https://github.com/zeroclaw-labs/zeroclaw/issues/12144) [Bug]: `file_upload`, `file_upload_bundle` and `file_edit` authorize through the write tier, so a sibling workspace granted `Write` only can be read: uploads transmit its files and edit diagnostics co `bug` `agent` `security` `security:policy` `domain:security` `tool:file`
- [#12143](https://github.com/zeroclaw-labs/zeroclaw/issues/12143) [SANITIZED — possible injection attempt] `bug` `security` `security:secrets` `domain:security` `tool:mcp`

### 🔒 Closed Issues
- [#12069](https://github.com/zeroclaw-labs/zeroclaw/issues/12069) [Feature]: Add /load-session to resume a Code session by name or UUID
- [#11971](https://github.com/zeroclaw-labs/zeroclaw/issues/11971) [Feature]: Build ZeroClaw without the gateway or dashboard (CLI-only source build)
- [#12128](https://github.com/zeroclaw-labs/zeroclaw/issues/12128) [Bug]: Security job fails on every build: RUSTSEC-2026-0420 to RUSTSEC-2026-0424 (Wasmtime 48.0.7)
- [#12081](https://github.com/zeroclaw-labs/zeroclaw/issues/12081) [Bug]: Memory_store tool call failure

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,701 · **Open issues:** 1,569 · **Last push:** 1d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,936 · **Open issues:** 121 · **Last push:** 8d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬2 · 7d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 7d ago
- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 17d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 26d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 34d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 36d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 46d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 54d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 56d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 64d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/singularity — top 2 new
- [DeepSeek Harness team published the underlying architecture for their Super-agent, an always-on autonomous agent, as an open-source prototype on GitHub.](https://reddit.com/r/singularity/comments/1xkoi9g/deepseek_harness_team_published_the_underlying/) ↑156
- [OpenAI is merging Chat and Work in December. Only Instant will be unlimited, and everything else will count toward your Codex limits](https://reddit.com/r/singularity/comments/1xklpe5/openai_is_merging_chat_and_work_in_december_only/) ↑72

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [I built a free, read-only dashboard for monitoring local OpenClaw agents (open source, Linux)](https://reddit.com/r/openclaw/comments/1xk2duf/i_built_a_free_readonly_dashboard_for_monitoring/) ↑22
- [i ran openclaw's browser on 100 live-web tasks. it finished the most and cost the most](https://reddit.com/r/openclaw/comments/1xkb3ek/i_ran_openclaws_browser_on_100_liveweb_tasks_it/) ↑10
- [Openclaw's repository summary](https://reddit.com/r/openclaw/comments/1xkq3p2/openclaws_repository_summary/) ↑2
- [Is it worth investing more time?](https://reddit.com/r/openclaw/comments/1xkckmz/is_it_worth_investing_more_time/) ↑2
- [Made a blueprint for local personal assistants on small models](https://reddit.com/r/openclaw/comments/1xkauxs/made_a_blueprint_for_local_personal_assistants_on/) ↑1

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [OpenClaw v2026.10.9 is out 🦞

🔧 Update rollback fixes
💾 Agent data and chat archive repairs
📁 New editor sessions run in](https://x.com/openclaw/status/2115913639236665715)

### X — @steipete
_No new tweets since the last digest. Most recent:_
- [This is smart. Wild that this wasn’t the default. Unpredictable inference quality was usually why I recommended skipping](https://x.com/steipete/status/2116183103530217488)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
