---
layout: post
title: "Ecosystem Digest — 2026-06-27"
date: 2026-06-27 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-27
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 380,619 | 1 | 3 | 10 | 0 |
| **hermesagent** | 203,805 | 13 | 6 | 8 | 0 |
| **ZeroClaw** | 32,051 | 15 | 7 | 10 | 1 |
| **IronClaw** | 12,482 | 6 | 2 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 380,619 · **Open issues:** 6,685 · **Last push:** <1h ago

### ✅ Merged PRs
- [#97128](https://github.com/openclaw/openclaw/pull/97128) fix(opencode-go): re-arm idle timer on block-boundary events to prevent false stalled-stream abort
- [#87081](https://github.com/openclaw/openclaw/pull/87081) test(policy): add config coverage report
- [#97130](https://github.com/openclaw/openclaw/pull/97130) fix(telegram): retain socket failure context
- [#96989](https://github.com/openclaw/openclaw/pull/96989) fix(provider-transport-fetch): bound SSE buffer to prevent OOM
- [#97041](https://github.com/openclaw/openclaw/pull/97041) fix(agents): guard delivery-evidence attachment recursion against cycles
- [#96772](https://github.com/openclaw/openclaw/pull/96772) fix(googlechat): replace unbounded response.json() with readProviderJsonResponse
- [#96762](https://github.com/openclaw/openclaw/pull/96762) fix(openai-chatgpt-responses): bound streaming success-body SSE reads at 16 MiB
- [#89884](https://github.com/openclaw/openclaw/pull/89884) fix(voice-call): emit canonical session keys
- [#96963](https://github.com/openclaw/openclaw/pull/96963) fix(agents): truncate exec command detail on code-point boundaries
- [#96801](https://github.com/openclaw/openclaw/pull/96801) chore(catalog): bump Weixin plugin to 2.4.6

### 🐛 New Issues
- [#97115](https://github.com/openclaw/openclaw/issues/97115) Bug: Cron fallback chain broken — models return zero-token success or killed by shared AbortController `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#97142](https://github.com/openclaw/openclaw/issues/97142) [Feature]: make the gateway support android
- [#96518](https://github.com/openclaw/openclaw/issues/96518) [Bug]: opencode-go stalled-stream watchdog aborts a live stream and drops the completed answer (idle timer re-arms only on token deltas, not block-boundary events)
- [#94620](https://github.com/openclaw/openclaw/issues/94620) Misleading Telegram fallback log + dead-code remote-IP retry on EADDRNOTAVAIL

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 203,805 · **Open issues:** 23,998 · **Last push:** <1h ago

### ✅ Merged PRs
- [#53357](https://github.com/NousResearch/hermes-agent/pull/53357) fix(desktop): keep titlebar overlay off session title
- [#53335](https://github.com/NousResearch/hermes-agent/pull/53335) fix(desktop): show custom (non-curated) model in Settings model pickers
- [#53239](https://github.com/NousResearch/hermes-agent/pull/53239) fix(dashboard-auth): exclude non-interactive providers from interactive login surfaces
- [#53294](https://github.com/NousResearch/hermes-agent/pull/53294) fix(mcp): suppress interactive OAuth stdin prompts during background discovery (#35927)
- [#53319](https://github.com/NousResearch/hermes-agent/pull/53319) fix(hermes-home): only honour legacy dir layout when it has content
- [#53316](https://github.com/NousResearch/hermes-agent/pull/53316) fix(gateway): suppress operational status/error noise on all chat gateways (#39293)
- [#53312](https://github.com/NousResearch/hermes-agent/pull/53312) fix(desktop): broken "Open setup guide" button for plugin platforms (Teams, Google Chat)
- [#53304](https://github.com/NousResearch/hermes-agent/pull/53304) fix(tui): preserve filtered model provider selection

### 🐛 New Issues
- [#53370](https://github.com/NousResearch/hermes-agent/issues/53370) fix(windows): suppress console window flash when spawning gh auth token
- [#53368](https://github.com/NousResearch/hermes-agent/issues/53368) fix(desktop): sidebar silently drops sessions after rebuild — empty drafts, compression intermediates, and delegate children hidden with no toggle `type/bug` `P3` `sweeper:risk-session-state` `comp/desktop` `comp/dashboard`
- [#53367](https://github.com/NousResearch/hermes-agent/issues/53367) fix: garbled Chinese text in Desktop projects list `type/bug` `P3` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows`
- [#53362](https://github.com/NousResearch/hermes-agent/issues/53362) TUI Python process pegs CPU at 99% and becomes unresponsive — /stop, Ctrl+C, and keyboard input all ignored `type/bug` `comp/tui` `P2` `needs-repro`
- [#53361](https://github.com/NousResearch/hermes-agent/issues/53361) [BUG] Agent enters infinite reasoning loop when instruction contradicts current environment state (Instruction-Reality Mismatch) `type/bug` `comp/agent` `provider/ollama` `P3` `needs-repro`
- [#53360](https://github.com/NousResearch/hermes-agent/issues/53360) [Feature]: Add google_chat config section to config.yaml `type/feature` `comp/gateway` `P3`
- [#53359](https://github.com/NousResearch/hermes-agent/issues/53359) [Setup]: how to tailor context for a model? `type/docs` `question` `comp/agent` `provider/ollama` `P3`
- [#53352](https://github.com/NousResearch/hermes-agent/issues/53352) Desktop: renderer crash  boot loop on Windows + build overwrites source `type/bug` `P3` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows`
- [#53349](https://github.com/NousResearch/hermes-agent/issues/53349) [Feature]: support cwd-local soul.md for per-directory agent identity `type/feature` `comp/agent` `P3` 💬2
- [#53347](https://github.com/NousResearch/hermes-agent/issues/53347) [Feature]: Allow context_length below 64K — warn instead of hard failure `type/feature` `comp/agent` `P3`
- [#53342](https://github.com/NousResearch/hermes-agent/issues/53342) [Bug]: The Hermes desktop client on Windows keeps flickering black command prompt windows nonstop, making the program completely inoperable. This is a critical blocking bug! `type/bug` `duplicate` `tool/terminal` `P2` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows` `bug` 💬1
- [#53341](https://github.com/NousResearch/hermes-agent/issues/53341) feat(cli): add `!` prefix for direct shell command passthrough `duplicate` `type/feature` `comp/cli` `P3` 💬1
- [#53338](https://github.com/NousResearch/hermes-agent/issues/53338) Windows prebuilt installer (Hermes-Setup.exe) aborts at the `python` stage:  install.ps1 pins Python 3.11 (fallbacks ≤3.13) `type/bug` `comp/cli` `area/config` `P2` `sweeper:risk-platform-windows` `platform/windows`

### 🔒 Closed Issues
- [#20250](https://github.com/NousResearch/hermes-agent/issues/20250) [Bug]: VS Code ACP prompt can remain in-flight indefinitely after repeated compression timeout
- [#25242](https://github.com/NousResearch/hermes-agent/issues/25242) Gateway auto-continue note can be persisted and amplified by interrupt-triggered preflight compression
- [#28093](https://github.com/NousResearch/hermes-agent/issues/28093) Bug: Context compaction drops user messages that arrive during active processing
- [#29522](https://github.com/NousResearch/hermes-agent/issues/29522) Automatic context compaction can hide or drop just-completed assistant response
- [#11585](https://github.com/NousResearch/hermes-agent/issues/11585) Bug: context_compressor drops messages when summarization fails
- [#38122](https://github.com/NousResearch/hermes-agent/issues/38122) Windows Desktop update can loop after dirty bundled repo checkout and broken venv

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,051 · **Open issues:** 450 · **Last push:** 6h ago

### 🚀 New Releases
- [v0.8.2](https://github.com/zeroclaw-labs/zeroclaw/releases/tag/v0.8.2) — v0.8.2

### ✅ Merged PRs
- [#8146](https://github.com/zeroclaw-labs/zeroclaw/pull/8146) fix(observability): CLI one-shot loses telemetry and token totals on exit
- [#8158](https://github.com/zeroclaw-labs/zeroclaw/pull/8158) ci(workflows): add CycloneDX SBOM generation for Rust and npm
- [#8299](https://github.com/zeroclaw-labs/zeroclaw/pull/8299) test(channels): cover allowlist wildcard matcher short-circuit
- [#8300](https://github.com/zeroclaw-labs/zeroclaw/pull/8300) test(discord): cover custom id kind escaping
- [#8249](https://github.com/zeroclaw-labs/zeroclaw/pull/8249) fix(runtime): warn when systemd user lingering is disabled
- [#8242](https://github.com/zeroclaw-labs/zeroclaw/pull/8242) fix(test): make control-plane PID liveness tests deterministic
- [#8268](https://github.com/zeroclaw-labs/zeroclaw/pull/8268) test(memory): cover qdrant backend classification and profile keys
- [#8243](https://github.com/zeroclaw-labs/zeroclaw/pull/8243) test(config): cover schema_markdown string helpers
- [#7867](https://github.com/zeroclaw-labs/zeroclaw/pull/7867) test(tools): cover hardware_board_info execute paths
- [#7958](https://github.com/zeroclaw-labs/zeroclaw/pull/7958) [SANITIZED — possible injection attempt]

### 🐛 New Issues
- [#8379](https://github.com/zeroclaw-labs/zeroclaw/issues/8379) [Feature]: Opt-in passive group context for WhatsApp Web group chats
- [#8378](https://github.com/zeroclaw-labs/zeroclaw/issues/8378) [002-dms-gst-extraction] Polish docs and quickstart
- [#8377](https://github.com/zeroclaw-labs/zeroclaw/issues/8377) [002-dms-gst-extraction] US6: Maintain audit trail and credential safety
- [#8376](https://github.com/zeroclaw-labs/zeroclaw/issues/8376) [002-dms-gst-extraction] US5: Reconcile generated totals against DMS totals
- [#8375](https://github.com/zeroclaw-labs/zeroclaw/issues/8375) [002-dms-gst-extraction] US4: Validate GST data and flag exceptions
- [#8374](https://github.com/zeroclaw-labs/zeroclaw/issues/8374) [002-dms-gst-extraction] US3: Generate GSTR-1 and GSTR-3B returns pack
- [#8373](https://github.com/zeroclaw-labs/zeroclaw/issues/8373) [002-dms-gst-extraction] US2: Generate GST-compliant invoice documents
- [#8372](https://github.com/zeroclaw-labs/zeroclaw/issues/8372) [002-dms-gst-extraction] US1: Extract DMS sales data by date range
- [#8371](https://github.com/zeroclaw-labs/zeroclaw/issues/8371) [002-dms-gst-extraction] Bootstrap dms-gst-agent foundation
- [#8369](https://github.com/zeroclaw-labs/zeroclaw/issues/8369) [Bug]: max_history_messages hard cap still uses legacy message-count trimming after whole-turn trim rewrite `bug` `docs` `agent` `runtime` `priority:p2` `risk:high`
- [#8367](https://github.com/zeroclaw-labs/zeroclaw/issues/8367) RFC: capability-aware documentation for agent-visible features `docs` `config` `provider` `skills` `tool` `domain:architecture` `type:rfc` `priority:p3`
- [#8366](https://github.com/zeroclaw-labs/zeroclaw/issues/8366) [Bug]: Heartbeat engine reads HEARTBEAT.md from data_dir instead of agent workspace `bug` `heartbeat` `runtime` `heartbeat:engine` `priority:p2` `status:accepted` `risk:medium` 💬1
- [#8363](https://github.com/zeroclaw-labs/zeroclaw/issues/8363) [Tracker]: v0.8.3 config, runtime routing, and tool policy `enhancement` `config` `runtime` `tool` `priority:p2` `status:accepted` `risk:high`
- [#8362](https://github.com/zeroclaw-labs/zeroclaw/issues/8362) [Tracker]: v0.8.3 channel adapter behavior and interaction parity `enhancement` `channel` `runtime` `priority:p2` `status:accepted` `risk:high`
- [#8360](https://github.com/zeroclaw-labs/zeroclaw/issues/8360) [Tracker]: v0.8.3 provider and native-tool message serialization `enhancement` `provider` `runtime` `tool` `priority:p2` `status:accepted` `risk:high`

### 🔒 Closed Issues
- [#5844](https://github.com/zeroclaw-labs/zeroclaw/issues/5844) [Bug]: Too much emphasis on memory
- [#4879](https://github.com/zeroclaw-labs/zeroclaw/issues/4879) [Bug]: Gemini CLI OAuth is simply not working
- [#6434](https://github.com/zeroclaw-labs/zeroclaw/issues/6434) [Bug]: Shell tool calls are refused at `[autonomy] level = "full"` — no `tool_dispatch` ever reaches the runtime
- [#8047](https://github.com/zeroclaw-labs/zeroclaw/issues/8047) [Bug]: ReadSkillTool looks in `data_dir` but skills live in agent workspace
- [#7689](https://github.com/zeroclaw-labs/zeroclaw/issues/7689) feat(tools): cover hardware board tool execute paths
- [#5866](https://github.com/zeroclaw-labs/zeroclaw/issues/5866) [Bug]: in the Telegram group bot ignores replies on its messages when mention_only=true
- [#7746](https://github.com/zeroclaw-labs/zeroclaw/issues/7746) [Docs]: Document how to load and switch existing zerocode sessions

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,482 · **Open issues:** 1,275 · **Last push:** <1h ago

### ✅ Merged PRs
- [#5367](https://github.com/nearai/ironclaw/pull/5367) [codex] test llm loop failures
- [#5265](https://github.com/nearai/ironclaw/pull/5265) feat(reborn): env-configurable turn-runner concurrency (0 = unlimited)
- [#4934](https://github.com/nearai/ironclaw/pull/4934) build(deps-dev): bump js-yaml from 4.1.1 to 4.2.0 in /docs/architecture-video
- [#5352](https://github.com/nearai/ironclaw/pull/5352) fix(reborn): unblock parallel-thread sends and new chats during active runs
- [#5345](https://github.com/nearai/ironclaw/pull/5345) [codex] Add Reborn WebUI legacy E2E harness
- [#5351](https://github.com/nearai/ironclaw/pull/5351) fix(ci): gate skills io/Read import to unix (Clippy Windows follow-up to #5325)
- [#5307](https://github.com/nearai/ironclaw/pull/5307) fix(reborn): discourage disabled tool workarounds
- [#5299](https://github.com/nearai/ironclaw/pull/5299) fix(webui-v2): anchor run failure messages
- [#5309](https://github.com/nearai/ironclaw/pull/5309) fix(reborn): persist always-allow for shared registry tools
- [#5325](https://github.com/nearai/ironclaw/pull/5325) fix(ci): green up main + cargo/non-cargo network resilience

### 🐛 New Issues
- [#5368](https://github.com/nearai/ironclaw/issues/5368) [reborn-webui] Wire non-Slack channel personal pairing end-to-end
- [#5364](https://github.com/nearai/ironclaw/issues/5364) Make "Always allow eligible tools" the default
- [#5350](https://github.com/nearai/ironclaw/issues/5350) reborn harness fixes from benchmark hill-climbing (PinchBench/ClawBench) — see nearai/benchmarks#190 for scores
- [#5337](https://github.com/nearai/ironclaw/issues/5337) Wasm-channel OAuth setup can't reach auth_url on first-time configure (channel auth descriptor never seeded)
- [#5333](https://github.com/nearai/ironclaw/issues/5333) [Reborn] Composer keeps the submitted message visible briefly after sending
- [#5332](https://github.com/nearai/ironclaw/issues/5332) Coverage --all-features auto-enables forward-feature gates (pr7-ready/pr3180-ready), running deferred-work tests

### 🔒 Closed Issues
- [#5009](https://github.com/nearai/ironclaw/issues/5009) Bring live (non-triggered) Slack OAuth path to structural DM-parity
- [#5197](https://github.com/nearai/ironclaw/issues/5197) [Reborn] Disabled tool may cause the assistant to invoke unrelated tools instead of reporting the tool is unavailable

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#94780](https://github.com/openclaw/openclaw/issues/94780) [Feature]: Per-cron model selection independent of agent default — run cheap/free models on automation jobs while keeping main agent on premium LLM — 💬1 · 1d ago
- ⚫ [#93032](https://github.com/openclaw/openclaw/issues/93032) [Bug] v2026.6.6: Cron scheduler loads 0 jobs after upgrade — SQLite WAL not committed at first startup — 💬2 · 1d ago
- ⚫ [#92974](https://github.com/openclaw/openclaw/issues/92974) Bug: v2026.6.6 getAttributionHeaders() crashes on Bedrock models — baseUrl undefined (null-guard missing) — 💬1 · 1d ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬4 · 3d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬7 · 4d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 5d ago
- 🟢 [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬1 · 5d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬2 · 5d ago
- 🟢 [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 5d ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 5d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Research] Economic Index June 2026 Report](https://www.anthropic.com/research/economic-index-june-2026-report) _2026-06-26_

### OpenAI — 4 new
- [[Policies] Professional Services Security Measures](https://openai.com/policies/professional-services-security-measures/) _2026-06-26_
- [[Solutions] Education](https://openai.com/business/solutions/education/) _2026-06-26_
- [[Form] Openai Campus Leaders Interest Form](https://openai.com/form/openai-campus-leaders-interest-form/) _2026-06-26_
- [[Form] Trusted Access For Biology Research](https://openai.com/form/trusted-access-for-biology-research/) _2026-06-26_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [US Govt to individually approve who gets GPT 5.6.](https://reddit.com/r/LocalLLaMA/comments/1ufo0un/us_govt_to_individually_approve_who_gets_gpt_56/) ↑1101
- [Why do people keep investing in Intel for AI?](https://reddit.com/r/LocalLLaMA/comments/1ugcbqx/why_do_people_keep_investing_in_intel_for_ai/) ↑342
- [audio.cpp: 12 audio models (Qwen3-TTS, PocketTTS, VeVo2 etc) in 1 C++/ggml runtime — TTS up to 5x faster than Python on CUDA](https://reddit.com/r/LocalLLaMA/comments/1ufpnm6/audiocpp_12_audio_models_qwen3tts_pockettts_vevo2/) ↑339
- ["What should I do?" - consider post-training](https://reddit.com/r/LocalLLaMA/comments/1ugg1dm/what_should_i_do_consider_posttraining/) ↑325
- [When you don't have a data center GPU](https://reddit.com/r/LocalLLaMA/comments/1uft2sv/when_you_dont_have_a_data_center_gpu/) ↑141

### r/singularity — top 3 new
- [Yann LeCun says xAI is a failure](https://reddit.com/r/singularity/comments/1ugfgzu/yann_lecun_says_xai_is_a_failure/) ↑748
- [The US lifts its block on Mythos 5](https://reddit.com/r/singularity/comments/1ugme72/the_us_lifts_its_block_on_mythos_5/) ↑231
- [Worst Degrees To Choose In The AI Era](https://reddit.com/r/singularity/comments/1ugp3wa/worst_degrees_to_choose_in_the_ai_era/) ↑0

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Hot take: if you have to come to this sub and ask how to get started, openclaw probably isnt for you.](https://reddit.com/r/openclaw/comments/1ugcsb1/hot_take_if_you_have_to_come_to_this_sub_and_ask/) ↑24
- [SOUL Atlas > a map of how the world thinks](https://reddit.com/r/openclaw/comments/1ugoo6q/soul_atlas_a_map_of_how_the_world_thinks/) ↑2

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
- [I love how Apple notarization breaks multiple times a year until I manually log in and accept some new legal agreements.](https://x.com/steipete) ↑0 🔁0 · recent
- [I’ll wait for the public release to comment.](https://x.com/steipete) ↑0 🔁0 · recent
- [You can highlight that this is useful for debugging, but it’s dangerous to suggest this could help on crash reporting.](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
