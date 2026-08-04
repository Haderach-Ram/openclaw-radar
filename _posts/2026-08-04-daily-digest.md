---
layout: post
title: "Ecosystem Digest — 2026-08-04"
date: 2026-08-04 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-08-04
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 385,049 | 9 | 3 | 10 | 2 |
| **hermesagent** | 224,935 | 11 | 7 | 1 | 1 |
| **ZeroClaw** | 32,490 | 12 | 4 | 6 | 0 |
| **IronClaw** | 12,586 | 15 | 4 | 10 | 0 |
| **Moltis** | 2,805 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 385,049 · **Open issues:** 5,465 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.7.1-2](https://github.com/openclaw/openclaw/releases/tag/v2026.7.1-2) — openclaw 2026.7.1-2
- [v2026.7.1-1](https://github.com/openclaw/openclaw/releases/tag/v2026.7.1-1) — openclaw 2026.7.1-1

### ✅ Merged PRs
- [#119012](https://github.com/openclaw/openclaw/pull/119012) test(qa): prove container health endpoints
- [#119032](https://github.com/openclaw/openclaw/pull/119032) test(qa): prove agent session scope continuity
- [#119021](https://github.com/openclaw/openclaw/pull/119021) chore(qa): prove workspace mutation tools
- [#118854](https://github.com/openclaw/openclaw/pull/118854) fix(gateway): keep plugin model allowlists static
- [#119046](https://github.com/openclaw/openclaw/pull/119046) fix(cli): gateway call honors local --port
- [#119045](https://github.com/openclaw/openclaw/pull/119045) fix(xai): stop realtime sessions when playback acknowledgements stall
- [#119015](https://github.com/openclaw/openclaw/pull/119015) fix(gateway): honor external status target context
- [#119038](https://github.com/openclaw/openclaw/pull/119038) chore(qa): cover sandbox workspace isolation
- [#119028](https://github.com/openclaw/openclaw/pull/119028) test(qa): cover agent session streaming
- [#119039](https://github.com/openclaw/openclaw/pull/119039) test(qa): cover progress followthrough evidence

### 🐛 New Issues
- [#119060](https://github.com/openclaw/openclaw/issues/119060) [Bug]: memory_search mislabels canonical session migration as an embedding/provider failure
- [#119058](https://github.com/openclaw/openclaw/issues/119058) QA Playwright scenarios skip required ffmpeg on clean runners `maintainer`
- [#119054](https://github.com/openclaw/openclaw/issues/119054) Workboard: child card can never reach done when its parent is an intentionally long-lived multi-phase umbrella
- [#119049](https://github.com/openclaw/openclaw/issues/119049) [Bug]: Local model setup loses the exact prepared model before activation `maintainer`
- [#119048](https://github.com/openclaw/openclaw/issues/119048) Channel delivery lacks turn-level idempotency — duplicate Telegram replies after model fallback and send-retry
- [#119044](https://github.com/openclaw/openclaw/issues/119044) [Feature]: Map compatible bundle agents to native templates 💬1
- [#119041](https://github.com/openclaw/openclaw/issues/119041) [Bug]: Slack partial preview rotates into new messages on MiniMax reasoning boundaries 💬1
- [#119035](https://github.com/openclaw/openclaw/issues/119035) [Feature]: Add a wake-only cron payload kind `enhancement` `maintainer` 💬2
- [#119026](https://github.com/openclaw/openclaw/issues/119026) flaky(macos-swift): wall-clock deadline assertions fail nondeterministically on hosted runners

### 🔒 Closed Issues
- [#106504](https://github.com/openclaw/openclaw/issues/106504) [SANITIZED — possible injection attempt]
- [#119036](https://github.com/openclaw/openclaw/issues/119036) [SANITIZED — possible injection attempt]
- [#105435](https://github.com/openclaw/openclaw/issues/105435) [Bug] Out-of-order message processing in parseWebSocket due to raced async message decoding

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬116 · 2d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 224,935 · **Open issues:** 27,263 · **Last push:** 1h ago

### 🚀 New Releases
- [v2026.8.3](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.8.3) — Hermes Agent v0.20.0 (2026.8.3)

### ✅ Merged PRs
- [#78024](https://github.com/NousResearch/hermes-agent/pull/78024) feat(models): add qwen3.8-max to Nous portal + OpenRouter, replacing qwen3.7-max

### 🐛 New Issues
- [#78115](https://github.com/NousResearch/hermes-agent/issues/78115) [Bug]: slack multiple choice questions are unreadable when truncated `bug`
- [#78109](https://github.com/NousResearch/hermes-agent/issues/78109) [Bug]: Desktop GUI: @file: reference stuck in input box after session — X button does not remove it
- [#78106](https://github.com/NousResearch/hermes-agent/issues/78106) [Bug]: Slack mention triggers a run but mention context is stripped before the agent response decision `type/bug` `comp/gateway` `platform/slack` `P2` `sweeper:risk-message-delivery`
- [#78105](https://github.com/NousResearch/hermes-agent/issues/78105) [Bug]: Desktop — draft text from one chat session carries over into another chat session `type/bug` `duplicate` `P2` `sweeper:risk-session-state` `comp/desktop` 💬1
- [#78103](https://github.com/NousResearch/hermes-agent/issues/78103) [Bug]: `hermes config set platform_toolsets.cli '["hermes-cli"]'` writes a literal string, silently discarding the explicit toolset selection `type/bug` `duplicate` `comp/cli` `area/config` `P2` `sweeper:risk-compatibility` 💬1
- [#78102](https://github.com/NousResearch/hermes-agent/issues/78102) [Bug]: Startup warns "Unknown toolsets: mcp-<server>" for valid MCP toolset names `type/bug` `comp/cli` `tool/mcp` `area/config` `P3`
- [#78101](https://github.com/NousResearch/hermes-agent/issues/78101) [Bug]: Desktop app silently exits when SingletonLock held by zombie/defunct Electron process (Linux/X11) `type/bug` `P2` `comp/desktop`
- [#78098](https://github.com/NousResearch/hermes-agent/issues/78098) [Bug]: Desktop conversation mode drops successful transcription and sends Transcription(...) error repr as the message `type/bug` `tool/tts` `P2` `comp/desktop` `bug`
- [#78097](https://github.com/NousResearch/hermes-agent/issues/78097) Feature: Support per-provider fast-tier (service_tier) routing, incl. gateway-backed providers `type/feature` `comp/agent` `comp/gateway` `provider/openai` `area/config` `P3`
- [#78089](https://github.com/NousResearch/hermes-agent/issues/78089) Windows: venv-blocker preflight still aborts desktop Update for .hermes-runtime gateways — cmdline truncated at 120 chars defeats the pausable-gateway exemption added by #75881 `type/bug` `comp/cli` `P2` `sweeper:risk-compatibility` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows` `area/install-update` 💬1
- [#78085](https://github.com/NousResearch/hermes-agent/issues/78085) [Setup]: when installing, it hangs on installing ripgrep `type/bug` `comp/cli` `P2` `needs-repro` `sweeper:risk-platform-windows` `platform/windows` `area/install-update`

### 🔒 Closed Issues
- [#71319](https://github.com/NousResearch/hermes-agent/issues/71319) [Bug][Windows] cua-driver installer stale-lock recovery from #58762 is POSIX-only — install.ps1's file lock can still wedge permanently
- [#77320](https://github.com/NousResearch/hermes-agent/issues/77320) [Bug]: WebUI user messages lose workspace prefix on replay, nuking prompt cache every turn
- [#78099](https://github.com/NousResearch/hermes-agent/issues/78099) Desktop app silently exits when SingletonLock held by zombie/defunct Electron process (Linux/X11)
- [#78072](https://github.com/NousResearch/hermes-agent/issues/78072) [Bug] Custom provider: model.provider gets set to display name (e.g. "custom:9router") instead of runtime name ("custom:Custom"), causing "Unknown provider" error
- [#78057](https://github.com/NousResearch/hermes-agent/issues/78057) [Bug]: Gateway startup status notice can complete an A2A task with unrelated text
- [#78071](https://github.com/NousResearch/hermes-agent/issues/78071) sanitize_api_messages does not catch tool messages with missing/empty tool_call_id
- [#78052](https://github.com/NousResearch/hermes-agent/issues/78052) Telegram gateway connect hangs forever in v0.20.0 inside gateway process only; standalone adapter connects fine

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,490 · **Open issues:** 698 · **Last push:** 2h ago

### ✅ Merged PRs
- [#9423](https://github.com/zeroclaw-labs/zeroclaw/pull/9423) fix(runtime): stop reporting an unanswerable approval as a user denial
- [#8969](https://github.com/zeroclaw-labs/zeroclaw/pull/8969) feat(channels/slack): hydrate thread context on first bot interaction
- [#8985](https://github.com/zeroclaw-labs/zeroclaw/pull/8985) feat(slack): show visible lifecycle progress while agent is working
- [#9691](https://github.com/zeroclaw-labs/zeroclaw/pull/9691) fix(container): align StageX pins and MSRV so all-features builds
- [#9589](https://github.com/zeroclaw-labs/zeroclaw/pull/9589) fix(deps): bump wasmtime stack to 47.0.3 for RUSTSEC-2026-0222
- [#9616](https://github.com/zeroclaw-labs/zeroclaw/pull/9616) fix(config): expose workspace paths to config set

### 🐛 New Issues
- [#9719](https://github.com/zeroclaw-labs/zeroclaw/issues/9719) bug(runtime): prevent stale provider refreshes from mutating replacement sessions `bug` `runtime` `priority:p2` `status:accepted` `risk:high`
- [#9718](https://github.com/zeroclaw-labs/zeroclaw/issues/9718) [Bug]: Telegram channel delivers duplicate messages when model emits both tool_call and content `bug` 💬1
- [#9716](https://github.com/zeroclaw-labs/zeroclaw/issues/9716) [Feature]: Add a structured localization boundary for provider errors `enhancement` `provider` `runtime` `priority:p3` `risk:high`
- [#9714](https://github.com/zeroclaw-labs/zeroclaw/issues/9714) [Bug]: Hardware timeout handlers discard underlying error context `bug` `priority:p3` `risk:medium` `hardware`
- [#9712](https://github.com/zeroclaw-labs/zeroclaw/issues/9712) [Feature]: Support weekly lettered cuts within a numbered release line `enhancement` `ci` `docs` `release-gate` `priority:p1` `risk:high` `type:ci` `cli`
- [#9711](https://github.com/zeroclaw-labs/zeroclaw/issues/9711) bug(hardware): clean up Arduino flash temporary directories on every exit `bug` `priority:p3` `follow-up` `hardware` `risk:low`
- [#9710](https://github.com/zeroclaw-labs/zeroclaw/issues/9710) bug(desktop): clean up temporary screenshot files on every exit `bug` `desktop` `priority:p3` `follow-up` `risk:low`
- [#9708](https://github.com/zeroclaw-labs/zeroclaw/issues/9708) bug(daemon): bound service launcher stdout and stderr logs `bug` `daemon` `observability` `priority:p2` `follow-up` `risk:medium`
- [#9706](https://github.com/zeroclaw-labs/zeroclaw/issues/9706) bug(provider): clean up Edge TTS temporary output on every error path `bug` `provider` `priority:p3` `follow-up` `risk:low`
- [#9703](https://github.com/zeroclaw-labs/zeroclaw/issues/9703) RFC: Goal mode v3 — asynchronous child supervision `enhancement` `agent` `runtime` `tool` `tool:delegate` `domain:architecture` `priority:p2` `needs-maintainer-review` `type:rfc` `status:no-stale` `risk:high` 💬1
- [#9702](https://github.com/zeroclaw-labs/zeroclaw/issues/9702) RFC: Goal mode v2 — durable continuation and paired Web controls `enhancement` `agent` `gateway` `runtime` `security` `domain:security` `domain:architecture` `priority:p2` `needs-maintainer-review` `type:rfc` `status:no-stale` `web` `risk:high` 💬1
- [#9697](https://github.com/zeroclaw-labs/zeroclaw/issues/9697) [Bug]: ZeroCode cannot connect to daemon launched by Windows Task Scheduler `bug` `daemon` `runtime` `priority:p1` `needs-author-action` `risk:medium` `zerocode` 💬1

### 🔒 Closed Issues
- [#9642](https://github.com/zeroclaw-labs/zeroclaw/issues/9642) [Bug]: an approval that times out is recorded as an explicit operator denial
- [#9162](https://github.com/zeroclaw-labs/zeroclaw/issues/9162) refactor(providers): extract duplicated OAuth-refresh retry loop into oauth_common
- [#6641](https://github.com/zeroclaw-labs/zeroclaw/issues/6641) [Feature]: Turn-level OTel trace correlation — nest llm.call / tool.call / memory.* spans under a single turn trace
- [#7082](https://github.com/zeroclaw-labs/zeroclaw/issues/7082) feat(channel/mattermost): add optional WebSocket listener mode

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,586 · **Open issues:** 1,476 · **Last push:** <1h ago

### ✅ Merged PRs
- [#7064](https://github.com/nearai/ironclaw/pull/7064) refactor(loop): shed the model gateway and tool disclosure into loop_host (WS3/WS4)
- [#7024](https://github.com/nearai/ironclaw/pull/7024) fix(extensions): resolve custom MCP auth during registration
- [#7049](https://github.com/nearai/ironclaw/pull/7049) docs: add weekly Wednesday release strategy
- [#7040](https://github.com/nearai/ironclaw/pull/7040) refactor(contracts): close the WS2 strays and WS2.1 follow-ups
- [#7070](https://github.com/nearai/ironclaw/pull/7070) fix(webui): unblock main E2E coverage — SSE keep_alive cursor, admin retry, stale selectors
- [#6968](https://github.com/nearai/ironclaw/pull/6968) Instrument progressive-disclosure canary metrics
- [#5981](https://github.com/nearai/ironclaw/pull/5981) Reborn queued-message steering (ported to current main, turn-boundary races fixed)
- [#6991](https://github.com/nearai/ironclaw/pull/6991) docs(research): pi agent harness deep dive and IronClaw adoption plan
- [#6780](https://github.com/nearai/ironclaw/pull/6780) feat(reborn-ironhub): deep-link register/install gateway + private manifest source
- [#7050](https://github.com/nearai/ironclaw/pull/7050) perf: recover hosted Postgres API capacity regressed by the row-native process journal (#6696)

### 🐛 New Issues
- [#7098](https://github.com/nearai/ironclaw/issues/7098) WS6: retire the surviving `local_runtime` misnomer (191 occurrences, 6 public API symbols — not the 1-line residue the docs claim)
- [#7097](https://github.com/nearai/ironclaw/issues/7097) Add billing support escalation pathways to billing page `p2` `feedback` `feature`
- [#7095](https://github.com/nearai/ironclaw/issues/7095) products-tier: ironclaw_extension_manager still holds a direct ironclaw_secrets edge (§8.2)
- [#7093](https://github.com/nearai/ironclaw/issues/7093) §11.2.7: seventeen cross-crate include_str! sites remain, owned by three lanes that are not the WS2 row
- [#7092](https://github.com/nearai/ironclaw/issues/7092) WS2: re-layer ironclaw_extension_host to loops — twelve product files and a second blocking edge
- [#7091](https://github.com/nearai/ironclaw/issues/7091) WS8: three callerless public builder methods on HostRuntimeServices
- [#7087](https://github.com/nearai/ironclaw/issues/7087) Reborn PR test planner hard-fails on Dockerfile, .githooks/, .claude/, crates/AGENTS.md, test-tools/ and two scripts/ gates 💬3
- [#7086](https://github.com/nearai/ironclaw/issues/7086) Stale guidance: .claude/commands/add-tool.md targets the deleted tools-src/ tree
- [#7085](https://github.com/nearai/ironclaw/issues/7085) check-version-bumps.sh silently skips the WIT_TOOL_VERSION cross-check on macOS (BSD sed has no \+) 💬2
- [#7083](https://github.com/nearai/ironclaw/issues/7083) Coverage is dark for the entire crates/extensions/ family — CRATE_RE still requires a crate directly under crates/ `bug` 💬1
- [#7082](https://github.com/nearai/ironclaw/issues/7082) builtin.skill_install: inline multi-file installs are unreachable, and url installs silently drop files/source/source_url `bug`
- [#7081](https://github.com/nearai/ironclaw/issues/7081) Docker fail-closed test gate is wired to nothing (IRONCLAW_REQUIRE_DOCKER_TESTS never set) 💬1
- [#7078](https://github.com/nearai/ironclaw/issues/7078) Shared-vendor OAuth scope ceiling is store-wide, not caller-scoped 💬1
- [#7075](https://github.com/nearai/ironclaw/issues/7075) Agent ignores follow-up question after failed run `bug_bash_P2`
- [#7074](https://github.com/nearai/ironclaw/issues/7074) Multi-tool meeting research fails after retrieving calendar data `bug_bash_P1`

### 🔒 Closed Issues
- [#6481](https://github.com/nearai/ironclaw/issues/6481) Epic: Manifest-Driven Extension Lifecycle
- [#6482](https://github.com/nearai/ironclaw/issues/6482) Epic: Pluggable Memory Providers
- [#6999](https://github.com/nearai/ironclaw/issues/6999) reborn_dependency_boundaries' server-lifecycle rule never covered the WebChat v2 route surface it documents
- [#6734](https://github.com/nearai/ironclaw/issues/6734) Give IronClaw agent access to its own documentation to guide tool/channel configuration

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,805 · **Open issues:** 96 · **Last push:** 19h ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 1d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 1d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 2d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 3d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 3d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 3d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬10 · 3d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 7d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 13d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 24d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 3 new
- [[Partners] Sk Inc Ax](https://openai.com/business/partners/sk-inc-ax/) _2026-08-04_
- [[Index] Circles](https://openai.com/index/circles/) _2026-08-04_
- [[Index] Continuous Voice Interaction With Gpt Live](https://openai.com/index/continuous-voice-interaction-with-gpt-live/) _2026-08-03_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Qwen3.8-27B announced alongside Qwen3.8-Max](https://reddit.com/r/LocalLLaMA/comments/1ve0psn/qwen3827b_announced_alongside_qwen38max/) ↑2614
- [Daniel Han of Unsloth validates Qwen3.8-27B will run only 17GB VRAM](https://reddit.com/r/LocalLLaMA/comments/1ve4uoe/daniel_han_of_unsloth_validates_qwen3827b_will/) ↑1574
- [I CANNOT believe I've got DeepSeek-V4-Flash-0731, a frontier model, running on my home PC. Insane!](https://reddit.com/r/LocalLLaMA/comments/1vehn87/i_cannot_believe_ive_got_deepseekv4flash0731_a/) ↑582
- [The Chinese labs everyone lumps together are making four pretty different bets. I work at one of them.](https://reddit.com/r/LocalLLaMA/comments/1veipya/the_chinese_labs_everyone_lumps_together_are/) ↑563
- [MiniMax-H3 now on huggingface](https://reddit.com/r/LocalLLaMA/comments/1ve1mvh/minimaxh3_now_on_huggingface/) ↑538

### r/singularity — top 5 new
- [Qwen 3.8 morning to you too Dario, 2$ input/ 6$ output per 1M.](https://reddit.com/r/singularity/comments/1ve6k6v/qwen_38_morning_to_you_too_dario_2_input_6_output/) ↑1224
- [The U.S. lead over China in AI is all but gone.](https://reddit.com/r/singularity/comments/1veoeho/the_us_lead_over_china_in_ai_is_all_but_gone/) ↑391
- [Elon Musk: "The next step is getting rid of “source code” entirely and just making an efficient binary directly with AI."](https://reddit.com/r/singularity/comments/1veslal/elon_musk_the_next_step_is_getting_rid_of_source/) ↑296
- [Is anyone else surprised Google DeepMind isn't leading these mathematical benchmarks?](https://reddit.com/r/singularity/comments/1ven8ow/is_anyone_else_surprised_google_deepmind_isnt/) ↑127
- [Models are now training models.](https://reddit.com/r/singularity/comments/1veje3t/models_are_now_training_models/) ↑108

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Oh well telegram has been removed on Apple Store](https://reddit.com/r/openclaw/comments/1vewjuk/oh_well_telegram_has_been_removed_on_apple_store/) ↑24
- [Z.AI - will they steal my data?](https://reddit.com/r/openclaw/comments/1vevpq8/zai_will_they_steal_my_data/) ↑5
- [New lower Codex limited just nuked my amazing Openclaw setup](https://reddit.com/r/openclaw/comments/1vei1h2/new_lower_codex_limited_just_nuked_my_amazing/) ↑4
- [How to utilize the long-running tasks on Qwen 3.8 MAX](https://reddit.com/r/openclaw/comments/1veiaqu/how_to_utilize_the_longrunning_tasks_on_qwen_38/) ↑2
- [Openclaw with Claude or Chatgpt?](https://reddit.com/r/openclaw/comments/1veun2a/openclaw_with_claude_or_chatgpt/) ↑2

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
_No new tweets in the last 7 days._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
