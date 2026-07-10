---
layout: post
title: "Ecosystem Digest — 2026-07-10"
date: 2026-07-10 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-07-10
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 382,364 | 10 | 5 | 10 | 0 |
| **hermesagent** | 212,246 | 6 | 7 | 10 | 0 |
| **ZeroClaw** | 32,214 | 5 | 5 | 10 | 0 |
| **IronClaw** | 12,515 | 15 | 0 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 382,364 · **Open issues:** 6,283 · **Last push:** <1h ago

### ✅ Merged PRs
- [#103253](https://github.com/openclaw/openclaw/pull/103253) fix(ui): apply selected reasoning and speed before sending
- [#101023](https://github.com/openclaw/openclaw/pull/101023) fix(outbound): publish conversation bindings after SQLite commit
- [#102445](https://github.com/openclaw/openclaw/pull/102445) fix(cron): channel failure alerts drop when global webhook failure destination is set
- [#102202](https://github.com/openclaw/openclaw/pull/102202) fix: tasks.list re-sorts the whole registry on every Control UI poll
- [#101078](https://github.com/openclaw/openclaw/pull/101078) fix(cron): preserve cron context in session entry for async completion wakes
- [#103244](https://github.com/openclaw/openclaw/pull/103244) ci: pin docs i18n Go toolchain
- [#103237](https://github.com/openclaw/openclaw/pull/103237) fix(ci): verify performance report after push timeout
- [#103175](https://github.com/openclaw/openclaw/pull/103175) docs(web): the Lobster gets its own page
- [#103197](https://github.com/openclaw/openclaw/pull/103197) fix(opencode): list current Zen models in offline discovery
- [#103172](https://github.com/openclaw/openclaw/pull/103172) feat(webchat): the Lobsterdex — collect every lobster that ever visits

### 🐛 New Issues
- [#103262](https://github.com/openclaw/openclaw/issues/103262) Onboarding migration import commits config before applying the migration plan, then locks retry behind fresh-setup gate
- [#103257](https://github.com/openclaw/openclaw/issues/103257) CI iOS build fails without a named simulator device `bug` `maintainer`
- [#103250](https://github.com/openclaw/openclaw/issues/103250) Codex Computer Use setup kills all agent turns on macOS after Codex.app was merged into ChatGPT.app
- [#103246](https://github.com/openclaw/openclaw/issues/103246) queue-helpers: applyQueueDropPolicy can drop the item currently mid-delivery, producing a duplicate/contradictory overflow record
- [#103245](https://github.com/openclaw/openclaw/issues/103245) `claude-cli` backend: `thinkingDefault: "adaptive"` is silently pinned to `--effort medium` — validation accepts adaptive, the spawn path flattens it
- [#103242](https://github.com/openclaw/openclaw/issues/103242) xAI catalog and server-tool defaults lag current models `bug` `maintainer`
- [#103239](https://github.com/openclaw/openclaw/issues/103239) Crash between git worktree add and the registry insert during create() leaves a permanent, unreconcilable orphan that also blocks recreation under the same name
- [#103235](https://github.com/openclaw/openclaw/issues/103235) Make Codex supervision interactive and owned by the Codex plugin `maintainer`
- [#103234](https://github.com/openclaw/openclaw/issues/103234) [Feature]: Default new OpenAI selections to GPT-5.6 `maintainer`
- [#103231](https://github.com/openclaw/openclaw/issues/103231) `claude-cli` backend: `ownsNativeCompaction` assumption is false for `claude -p` sessions — nobody compacts, sessions grow past 200% context, and every recovery path (stuck-session abort, safeguard co

### 🔒 Closed Issues
- [#101716](https://github.com/openclaw/openclaw/issues/101716) tasks.list full in-memory sort on every RPC call causes O(n log n) event-loop stalls
- [#102235](https://github.com/openclaw/openclaw/issues/102235) cron: global webhook failureDestination default swallows a job's channel-shaped failure route
- [#99919](https://github.com/openclaw/openclaw/issues/99919) [SANITIZED — possible injection attempt]
- [#103240](https://github.com/openclaw/openclaw/issues/103240) ci: pin docs-i18n to a patched Go 1.25 toolchain
- [#103184](https://github.com/openclaw/openclaw/issues/103184) Beta blocker: opencode - refresh Zen static catalog

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 212,246 · **Open issues:** 27,316 · **Last push:** <1h ago

### ✅ Merged PRs
- [#61767](https://github.com/NousResearch/hermes-agent/pull/61767) fix(gateway): enforce reconnect contract across adapters
- [#61740](https://github.com/NousResearch/hermes-agent/pull/61740) fix(gateway): malformed scalar config sections no longer crash gateway startup (#40834)
- [#61733](https://github.com/NousResearch/hermes-agent/pull/61733) fix(config): empty YAML section keys no longer replace default dicts (#58277)
- [#61732](https://github.com/NousResearch/hermes-agent/pull/61732) fix(agent): reapply provider headers after model switch (#61099)
- [#61726](https://github.com/NousResearch/hermes-agent/pull/61726) fix(memory): share one SQLite connection per holographic store database
- [#61716](https://github.com/NousResearch/hermes-agent/pull/61716) fix(gateway): in-place compaction no longer wipes the archived transcript
- [#61734](https://github.com/NousResearch/hermes-agent/pull/61734) test(cli): deflake --accept-hooks position test (one driver, one import)
- [#61723](https://github.com/NousResearch/hermes-agent/pull/61723) fix(cron): malformed job records no longer freeze the scheduler (class fix)
- [#61345](https://github.com/NousResearch/hermes-agent/pull/61345) fix(export): escape tool-call name in HTML session export
- [#61715](https://github.com/NousResearch/hermes-agent/pull/61715) [SANITIZED — possible injection attempt]

### 🐛 New Issues
- [#61778](https://github.com/NousResearch/hermes-agent/issues/61778) [Bug]: Codex 0-event hang is undetectable for >10k-token requests — TTFB exemption + event-idle precondition leave only the wall-clock stale timeout, which loses the race to delegation child_timeout
- [#61768](https://github.com/NousResearch/hermes-agent/issues/61768) Desktop serve backend: cron ticker thread races _call_cron_for_profile global retarget → destructive cross-profile jobs.json overwrite (full-store clone) `type/bug` `comp/cron` `P1` `sweeper:risk-session-state` `sweeper:risk-message-delivery` `comp/dashboard` 💬1
- [#61765](https://github.com/NousResearch/hermes-agent/issues/61765) Feature: per-profile MCP scoping (--profile on hermes mcp add/remove/configure/list/test) `type/feature` `comp/cli` `tool/mcp` `area/config` `P3`
- [#61764](https://github.com/NousResearch/hermes-agent/issues/61764) [Bug]: Desktop launcher death-loop: backend probe timeout (PROBE_TIMEOUT_MS=5000) too short on slow Windows boots `type/bug` `P2` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows` `bug`
- [#61762](https://github.com/NousResearch/hermes-agent/issues/61762) [Bug]: Unable to perceive when uploading pictures on Wecom `type/bug` `duplicate` `comp/gateway` `platform/wecom` `P2` `sweeper:risk-message-delivery` `bug` 💬1
- [#61761](https://github.com/NousResearch/hermes-agent/issues/61761) Output-cap retry loop never converges when margin is erased by per-retry input-token drift `type/bug` `comp/agent` `provider/openai` `P2`

### 🔒 Closed Issues
- [#52914](https://github.com/NousResearch/hermes-agent/issues/52914) [Bug]: fix(qqbot): QQBot adapter.connect() missing is_reconnect parameter causes infinite retry loop
- [#60794](https://github.com/NousResearch/hermes-agent/issues/60794) build_channel_directory blocks the event loop with synchronous SQLite queries (Discord heartbeat stalls)
- [#40834](https://github.com/NousResearch/hermes-agent/issues/40834) Gateway config deserializers crash on malformed scalar sections
- [#58277](https://github.com/NousResearch/hermes-agent/issues/58277) [Bug]: Empty YAML key (terminal:) in profile config.yaml crashes load_cli_config with TypeError
- [#61243](https://github.com/NousResearch/hermes-agent/issues/61243) [Feature]: self-hosted OIDC provider should support RP-Initiated Logout (end_session_endpoint)
- [#61099](https://github.com/NousResearch/hermes-agent/issues/61099) [Bug]: OpenRouter logs show 'Unknown' App for Hermes Agent requests intermittently
- [#55503](https://github.com/NousResearch/hermes-agent/issues/55503) [BUG] Holographic memory provider permanent write lock on memory_store.db

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,214 · **Open issues:** 487 · **Last push:** <1h ago

### ✅ Merged PRs
- [#8833](https://github.com/zeroclaw-labs/zeroclaw/pull/8833) fix(config): widen config-set alias auto-materialization past providers.*
- [#7836](https://github.com/zeroclaw-labs/zeroclaw/pull/7836) fix(channels/orchestrator): use resolved agent config for strict_tool_parsing and parallel_tools
- [#8881](https://github.com/zeroclaw-labs/zeroclaw/pull/8881) fix(cron): expose wechat, signal, email in cron delivery schema
- [#8872](https://github.com/zeroclaw-labs/zeroclaw/pull/8872) fix(zerocode): use runtime profile max_context_tokens for context meter
- [#8873](https://github.com/zeroclaw-labs/zeroclaw/pull/8873) fix(cli): UTF-8-safe stdin cap in exit prompt + audit trail (#7828)
- [#8884](https://github.com/zeroclaw-labs/zeroclaw/pull/8884) test(log): cover llm request UTF-8 truncation
- [#8912](https://github.com/zeroclaw-labs/zeroclaw/pull/8912) fix(runtime): gate agent stdout output on interactive flag (#8760)
- [#8824](https://github.com/zeroclaw-labs/zeroclaw/pull/8824) fix(gateway): use constant_time_eq for nodes.auth_token comparison
- [#8917](https://github.com/zeroclaw-labs/zeroclaw/pull/8917) docs(architecture): add tool execution lifecycle guide
- [#8690](https://github.com/zeroclaw-labs/zeroclaw/pull/8690) fix(channels): gate /model --agent behind per-sender authorization (#8044)

### 🐛 New Issues
- [#8925](https://github.com/zeroclaw-labs/zeroclaw/issues/8925) [Support]: Proper Way to Configure Amazon Bedrock Connection `r:support`
- [#8919](https://github.com/zeroclaw-labs/zeroclaw/issues/8919) [Feature]: Add a right-click context menu to ZeroCode chat `enhancement` `priority:p2` `zerocode` `risk:low`
- [#8915](https://github.com/zeroclaw-labs/zeroclaw/issues/8915) [Bug]: agent_start/agent_end never emitted for channel and process_message turns — /api/events and /history carry only llm_request `bug` `agent` `channel` `gateway` `observability` `runtime` `priority:p2` `status:in-progress` `risk:high`
- [#8907](https://github.com/zeroclaw-labs/zeroclaw/issues/8907) zerocode TUI: unified plugin/capability catalog pane (Track A surface 4/4) `enhancement` `channel` `config` `runtime` `runtime:wasm` `domain:architecture` `priority:p2` `status:blocked` `status:accepted` `zerocode` `risk:high` 💬1
- [#8894](https://github.com/zeroclaw-labs/zeroclaw/issues/8894) [Feature]: Add discoverable ZeroCode session archiving and cleanup controls `enhancement` `runtime` `priority:p3` `follow-up` `risk:medium` `zerocode`

### 🔒 Closed Issues
- [#7809](https://github.com/zeroclaw-labs/zeroclaw/issues/7809) [Bug]: Channel turns ignore runtime-profile strict/parallel tool flags
- [#8760](https://github.com/zeroclaw-labs/zeroclaw/issues/8760) bug(runtime): keep daemon-owned agent output out of daemon stdout
- [#8044](https://github.com/zeroclaw-labs/zeroclaw/issues/8044) Harden /model --agent scope with per-sender authorization
- [#5262](https://github.com/zeroclaw-labs/zeroclaw/issues/5262) [Feature]: Add ZeroClaw logo to official Agent Skills client list
- [#5903](https://github.com/zeroclaw-labs/zeroclaw/issues/5903) [Bug]: MCP stdio child processes accumulate on daemon with heartbeat.enabled=true (one orphan per tick)

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,515 · **Open issues:** 1,347 · **Last push:** <1h ago

### ✅ Merged PRs
- [#5652](https://github.com/nearai/ironclaw/pull/5652) build(lints): deny unused_must_use (dropped Result must not compile)
- [#5791](https://github.com/nearai/ironclaw/pull/5791) Prefer default-backed builder setters across Reborn crates
- [#5799](https://github.com/nearai/ironclaw/pull/5799) Add default setters for reborn config sections
- [#5812](https://github.com/nearai/ironclaw/pull/5812) Use default setters in event projection fixtures
- [#5811](https://github.com/nearai/ironclaw/pull/5811) Use default setters in memory native fixtures
- [#5800](https://github.com/nearai/ironclaw/pull/5800) Use default setters in reborn CLI config fixtures
- [#5798](https://github.com/nearai/ironclaw/pull/5798) Use default setters in reborn composition fixtures
- [#5794](https://github.com/nearai/ironclaw/pull/5794) Use read scope setters in reborn event store tests
- [#5793](https://github.com/nearai/ironclaw/pull/5793) Use default setters for event read scopes
- [#5792](https://github.com/nearai/ironclaw/pull/5792) Use default setters for trigger poller config

### 🐛 New Issues
- [#5897](https://github.com/nearai/ironclaw/issues/5897) [TECH DEBT] Decompose first-party skill activation module
- [#5891](https://github.com/nearai/ironclaw/issues/5891) "Last completed" displays active run timestamp instead of last finished execution `bug_bash_P3`
- [#5890](https://github.com/nearai/ironclaw/issues/5890) Slack notifications use inconsistent sender identity `bug_bash_P3`
- [#5889](https://github.com/nearai/ironclaw/issues/5889) "Load older messages" button does not load additional activity messages `bug_bash_P3`
- [#5888](https://github.com/nearai/ironclaw/issues/5888) Cannot delete old threads from the thread list `bug_bash_P3`
- [#5887](https://github.com/nearai/ironclaw/issues/5887) Run hits maximum action limit and discards accumulated progress `bug_bash_P2`
- [#5886](https://github.com/nearai/ironclaw/issues/5886) Pending approval blocks subsequent automation runs `bug_bash_P2`
- [#5885](https://github.com/nearai/ironclaw/issues/5885) Approval notification opens action without showing the approval message `bug_bash_P2`
- [#5884](https://github.com/nearai/ironclaw/issues/5884) Routine loses credentials after external token revocation `bug_bash_P2`
- [#5883](https://github.com/nearai/ironclaw/issues/5883) Generic "model output could not be used" error after successful tool execution `bug_bash_P2`
- [#5882](https://github.com/nearai/ironclaw/issues/5882) Repeated Slack reconnect attempts leave authentication flow in broken state `bug_bash_P2`
- [#5881](https://github.com/nearai/ironclaw/issues/5881) Authentication notification sent to wrong Slack app/channel `bug_bash_P2`
- [#5880](https://github.com/nearai/ironclaw/issues/5880) Slack auth completed externally is not reflected in Web UI approval flow `bug_bash_P2`
- [#5879](https://github.com/nearai/ironclaw/issues/5879) Stale error banner remains visible after successful follow-up response `bug_bash_P2`
- [#5878](https://github.com/nearai/ironclaw/issues/5878) Revoked GitHub token produces misleading errors instead of re-authentication flow `bug_bash_P2`

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬3 · 1h ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 15h ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬6 · 2d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬9 · 2d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 3d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 3d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 3d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 10d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 10d ago
- ⚫ [#94780](https://github.com/openclaw/openclaw/issues/94780) [Feature]: Per-cron model selection independent of agent default — run cheap/free models on automation jobs while keeping main agent on premium LLM — 💬1 · 14d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 4 new
- [[News] Ben Bernanke](https://www.anthropic.com/news/ben-bernanke) _2026-07-09_
- [[News] Hard Questions](https://www.anthropic.com/news/hard-questions) _2026-07-09_
- [[News] Reflect With Claude](https://www.anthropic.com/news/reflect-with-claude) _2026-07-09_
- [[News] Ust Claude](https://www.anthropic.com/news/ust-claude) _2026-07-10_

### OpenAI — 25 new
- [[Business] Plugins](https://openai.com/business/plugins/) _2026-07-10_
- [[Solutions] Operations](https://openai.com/business/solutions/operations/) _2026-07-10_
- [Chatgpt Work](https://openai.com/chatgpt-work/) _2026-07-10_
- [[Policies] Chatgpt Sites Data Processing Addendum](https://openai.com/policies/chatgpt-sites-data-processing-addendum/) _2026-07-10_
- [[Partners] Dropbox](https://openai.com/business/partners/dropbox/) _2026-07-09_
- [Build Week](https://openai.com/build-week/) _2026-07-09_
- [[Plugins] Gmail](https://openai.com/business/plugins/gmail/) _2026-07-09_
- [[Plugins] Microsoft Outlook Calendar](https://openai.com/business/plugins/microsoft-outlook-calendar/) _2026-07-09_
- [[Plugins] Slack](https://openai.com/business/plugins/slack/) _2026-07-09_
- [[Plugins] Microsoft Teams](https://openai.com/business/plugins/microsoft-teams/) _2026-07-09_
- [[Plugins] Google Calendar](https://openai.com/business/plugins/google-calendar/) _2026-07-09_
- [[Plugins] Atlassian Rovo](https://openai.com/business/plugins/atlassian-rovo/) _2026-07-09_
- [[Plugins] Zoom](https://openai.com/business/plugins/zoom/) _2026-07-09_
- [[Plugins] Fireflies](https://openai.com/business/plugins/fireflies/) _2026-07-09_
- [[Plugins] Microsoft Outlook Email](https://openai.com/business/plugins/microsoft-outlook-email/) _2026-07-09_
- [[Plugins] Conductor](https://openai.com/business/plugins/conductor/) _2026-07-10_
- [[Plugins] Lseg](https://openai.com/business/plugins/lseg/) _2026-07-09_
- [[Plugins] Daloopa](https://openai.com/business/plugins/daloopa/) _2026-07-09_
- [[Plugins] Morningstar](https://openai.com/business/plugins/morningstar/) _2026-07-09_
- [[Plugins] Databricks](https://openai.com/business/plugins/databricks/) _2026-07-09_
- [[Plugins] Hex](https://openai.com/business/plugins/hex/) _2026-07-09_
- [[Plugins] Bigquery](https://openai.com/business/plugins/bigquery/) _2026-07-09_
- [[Plugins] Airtable](https://openai.com/business/plugins/airtable/) _2026-07-09_
- [[Plugins] Atlassian Rovo](https://openai.com/business/plugins/atlassian-rovo/) _2026-07-09_
- [[Plugins] Data Analytics](https://openai.com/business/plugins/data-analytics/) _2026-07-09_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Now brothers we know why we are so fucked up](https://reddit.com/r/LocalLLaMA/comments/1urh2mg/now_brothers_we_know_why_we_are_so_fucked_up/) ↑711
- [GLM-5.2 fearmongering in the press](https://reddit.com/r/LocalLLaMA/comments/1urhzox/glm52_fearmongering_in_the_press/) ↑415
- [GLM-5.2 (744B MoE) on a 25GB-RAM consumer machine](https://reddit.com/r/LocalLLaMA/comments/1us5m0g/glm52_744b_moe_on_a_25gbram_consumer_machine/) ↑214
- [NVIDIA Puzzle-75B-A9B NVFP4 at 132 t/s on 3×3090 — Why is this size category a desert otherwise?](https://reddit.com/r/LocalLLaMA/comments/1uru9ja/nvidia_puzzle75ba9b_nvfp4_at_132_ts_on_33090_why/) ↑102
- [Reasoning-Medical0.1-27B (Qwen3.5-27B medical finetune, claims to surpass MedGemma)](https://reddit.com/r/LocalLLaMA/comments/1urni78/reasoningmedical0127b_qwen3527b_medical_finetune/) ↑90

### r/singularity — top 5 new
- [1X unveils NEO's new robotics hands](https://reddit.com/r/singularity/comments/1us0av5/1x_unveils_neos_new_robotics_hands/) ↑836
- [Superhuman competitive programming AI is here](https://reddit.com/r/singularity/comments/1urlaam/superhuman_competitive_programming_ai_is_here/) ↑635
- [GPT-5.6](https://reddit.com/r/singularity/comments/1urwctc/gpt56/) ↑513
- [ChatGPT 5.6 - ARC-AGI 3 score](https://reddit.com/r/singularity/comments/1urx8hy/chatgpt_56_arcagi_3_score/) ↑458
- [Muse spark 1.1 has been released with the lowest cost.](https://reddit.com/r/singularity/comments/1urrd6o/muse_spark_11_has_been_released_with_the_lowest/) ↑389

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw + Google Workspace (Gmail) Trigger](https://reddit.com/r/openclaw/comments/1urokbg/openclaw_google_workspace_gmail_trigger/) ↑9
- [I updated and it worked!](https://reddit.com/r/openclaw/comments/1uruju0/i_updated_and_it_worked/) ↑6
- [Coding plan selection help](https://reddit.com/r/openclaw/comments/1urfoc5/coding_plan_selection_help/) ↑6
- ["The Switzerland of AI": OpenClaw becomes a non-profit foundation](https://reddit.com/r/openclaw/comments/1us7a3f/the_switzerland_of_ai_openclaw_becomes_a/) ↑4
- [Looking for something like monitor function in claude code in openclaw](https://reddit.com/r/openclaw/comments/1urwi1t/looking_for_something_like_monitor_function_in/) ↑3

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
- [Godspeed, Fidji! I hope we succeed in building intelligence that will help with this](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
