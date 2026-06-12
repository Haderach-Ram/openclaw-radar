---
layout: post
title: "Ecosystem Digest — 2026-06-12"
date: 2026-06-12 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-12
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 378,236 | 6 | 6 | 5 | 0 |
| **hermesagent** | 191,064 | 7 | 2 | 8 | 0 |
| **ZeroClaw** | 31,880 | 9 | 3 | 10 | 1 |
| **IronClaw** | 12,441 | 14 | 4 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 378,236 · **Open issues:** 8,087 · **Last push:** <1h ago

### ✅ Merged PRs
- [#92053](https://github.com/openclaw/openclaw/pull/92053) fix(thinking): apply Claude profile to anthropic-messages catalog rows
- [#91617](https://github.com/openclaw/openclaw/pull/91617) test(sqlite): add state perf query plan harness
- [#92248](https://github.com/openclaw/openclaw/pull/92248) Remove ClawHub owner preflight
- [#92212](https://github.com/openclaw/openclaw/pull/92212) refactor: move workspace skill writes to lifecycle
- [#88245](https://github.com/openclaw/openclaw/pull/88245) refactor(whatsapp): introduce inbound message contexts

### 🐛 New Issues
- [#92306](https://github.com/openclaw/openclaw/issues/92306) [Bug]: cron jobs fails with "LLM request failed" `bug` `regression` `P1` `impact:crash-loop` 💬1
- [#92302](https://github.com/openclaw/openclaw/issues/92302) memory.qmd.command path mangled on Windows — QMD memory backend unusable despite working CLI (CommonJS path concatenation strips separators) `bug` `bug:behavior` 💬1
- [#92296](https://github.com/openclaw/openclaw/issues/92296) before_model_resolve can downgrade a turn but cannot refuse it — no pre-dispatch cost/cancel hook 💬1
- [#92291](https://github.com/openclaw/openclaw/issues/92291) [Bug]: cron edit --cron silently strips schedule.tz and staggerMs (direct path replaces schedule without merging) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:data-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#92289](https://github.com/openclaw/openclaw/issues/92289) CI check-docs failing on all PRs: docs.json references unpublished clawhub/soul-format page 💬3
- [#92285](https://github.com/openclaw/openclaw/issues/92285) [Bug]: Parent subagent task and TaskFlow remain stale_running after child becomes lost `bug` `bug:behavior` 💬1

### 🔒 Closed Issues
- [#91692](https://github.com/openclaw/openclaw/issues/91692) [Feature]: Require device-bound step-up approval for high-risk chat-originated actions
- [#92297](https://github.com/openclaw/openclaw/issues/92297) Concern about the lack of stable immutable releases after v3.13
- [#56263](https://github.com/openclaw/openclaw/issues/56263) Allow configurable file permissions (chmod 0o640/0o750) for multi-user setups
- [#92279](https://github.com/openclaw/openclaw/issues/92279) Model Picker: provider dropdown interaction fails with Discord 3s timeout
- [#91616](https://github.com/openclaw/openclaw/issues/91616) [Bug]: Missing SQLite perf and query-plan harness
- [#92140](https://github.com/openclaw/openclaw/issues/92140) Codex harness message_tool_only turn without the message tool: Telegram DMs answered with "Received the inter-session message. No action needed."

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 2h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 191,064 · **Open issues:** 19,865 · **Last push:** <1h ago

### ✅ Merged PRs
- [#44559](https://github.com/NousResearch/hermes-agent/pull/44559) fix(terminal): advertise persistent env state
- [#44493](https://github.com/NousResearch/hermes-agent/pull/44493) fix(desktop): recover from transient assistant-ui index-lookup crash
- [#44550](https://github.com/NousResearch/hermes-agent/pull/44550) fix(mcp): capability-gate tools/list so prompt-only MCP servers can connect (port opencode#31271)
- [#44545](https://github.com/NousResearch/hermes-agent/pull/44545) fix(coding): don't expose primary worktree path in coding context
- [#44529](https://github.com/NousResearch/hermes-agent/pull/44529) fix(desktop): close out the multi-profile desktop fallout — WS auth + cross-profile session reads
- [#43896](https://github.com/NousResearch/hermes-agent/pull/43896) fix(desktop): collect + persist API key for custom OpenAI-compatible endpoints
- [#44534](https://github.com/NousResearch/hermes-agent/pull/44534) fix(approval): carry allow_permanent to TUI + desktop approval prompts
- [#44528](https://github.com/NousResearch/hermes-agent/pull/44528) fix(ui-tui): stabilize embedded dashboard chat gateway

### 🐛 New Issues
- [#44592](https://github.com/NousResearch/hermes-agent/issues/44592) OAuth token exchange fails when server returns application/x-www-form-urlencoded
- [#44590](https://github.com/NousResearch/hermes-agent/issues/44590) OAuth: ephemeral HTTPServer per flow causes OSError Address already in use
- [#44588](https://github.com/NousResearch/hermes-agent/issues/44588) OAuth redirect_handler/callback_handler use shared globals, causing cross-server state pollution
- [#44585](https://github.com/NousResearch/hermes-agent/issues/44585) [Bug]: Cron can inherit temporary paid provider state and continue billing during pause/stop containment `type/bug` `comp/agent` `comp/cron` `P1` 💬1
- [#44582](https://github.com/NousResearch/hermes-agent/issues/44582) pre_tool_call plugin hook not invoked during agent tool execution `type/bug` `comp/plugins` `tool/terminal` `P3` 💬1
- [#44581](https://github.com/NousResearch/hermes-agent/issues/44581) [Bug]: Desktop folder attach fails — drag-and-drop errors with 'file not found on gateway and no data_url provided', copy-paste silently ignored `type/bug` `comp/gateway` `P3` 💬1
- [#44580](https://github.com/NousResearch/hermes-agent/issues/44580) hermes update reports success when desktop rebuild silently fails `type/bug` `comp/cli` `area/config` `P2` 💬1

### 🔒 Closed Issues
- [#44575](https://github.com/NousResearch/hermes-agent/issues/44575) TEST: should be caught by merged-PR check
- [#14285](https://github.com/NousResearch/hermes-agent/issues/14285) [Feature]: Add possibility to use Xiaomi MiMo token plan

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,880 · **Open issues:** 452 · **Last push:** 2h ago

### 🚀 New Releases
- [v0.8.0](https://github.com/zeroclaw-labs/zeroclaw/releases/tag/v0.8.0) — v0.8.0

### ✅ Merged PRs
- [#7519](https://github.com/zeroclaw-labs/zeroclaw/pull/7519) fix(config): persist [[mcp.servers]] per-field edits via natural-key dirty-path walker
- [#7520](https://github.com/zeroclaw-labs/zeroclaw/pull/7520) fix(ci): install cross g++ for ARM glibc release builds
- [#7364](https://github.com/zeroclaw-labs/zeroclaw/pull/7364) chore(release): release v0.8.0
- [#7454](https://github.com/zeroclaw-labs/zeroclaw/pull/7454) feat(plugins): add office-tools WASM plugin for Office document extraction
- [#7267](https://github.com/zeroclaw-labs/zeroclaw/pull/7267) feat(config): per-field editing for [[mcp.servers]] via #[natural_key]
- [#7463](https://github.com/zeroclaw-labs/zeroclaw/pull/7463) fix(runtime): use agent_workspace_dir for load_skills_for_agent calls
- [#7206](https://github.com/zeroclaw-labs/zeroclaw/pull/7206) fix(tools/calculator): reject factorial inputs above the u128-safe max
- [#7510](https://github.com/zeroclaw-labs/zeroclaw/pull/7510) fix(quickstart): pre-seed --api-key under snake_case api_key
- [#7502](https://github.com/zeroclaw-labs/zeroclaw/pull/7502) fix(docs): polish localized docs chrome
- [#7427](https://github.com/zeroclaw-labs/zeroclaw/pull/7427) fix(agent): remove dead context_aware_tools config field (#6720)

### 🐛 New Issues
- [#7523](https://github.com/zeroclaw-labs/zeroclaw/issues/7523) [Bug]: dashboard not valiable `bug`
- [#7521](https://github.com/zeroclaw-labs/zeroclaw/issues/7521) [Feature]: file_read — decode non-UTF-8 text (cp1251/Latin-1) via charset detection
- [#7518](https://github.com/zeroclaw-labs/zeroclaw/issues/7518) feat(whatsapp-web): support message reactions (ack_reactions parity with Telegram/Discord/Matrix)
- [#7514](https://github.com/zeroclaw-labs/zeroclaw/issues/7514) [Feature]: change `delegate` tool semantics to allow subagents with different risk profiles `enhancement`
- [#7509](https://github.com/zeroclaw-labs/zeroclaw/issues/7509) [Bug]: update self-test find_asset_url_picks_correct_gnu_over_android fails on Windows hosts (zip assets rejected by is_installable_release_asset) `bug`
- [#7507](https://github.com/zeroclaw-labs/zeroclaw/issues/7507) [Bug]: quickstart infinite redraw loop on non-TTY stdin — flooded 4.3 GB of output instead of erroring `bug`
- [#7498](https://github.com/zeroclaw-labs/zeroclaw/issues/7498) [Bug]: config save default-pruning breaks round-trip for fields whose serde default differs from struct Default
- [#7497](https://github.com/zeroclaw-labs/zeroclaw/issues/7497) [RFC]: OCI-Compliant Container Registries as the Plugin Storage and Discovery Mechanism `enhancement` 💬1
- [#7486](https://github.com/zeroclaw-labs/zeroclaw/issues/7486) ci: add non-required cross-platform Clippy coverage `enhancement` `type: ci` `ci` `risk: high` `priority:p2` `status:accepted` 💬2

### 🔒 Closed Issues
- [#7505](https://github.com/zeroclaw-labs/zeroclaw/issues/7505) [Bug]: quickstart --api-key pre-seeds kebab-case 'api-key' — apply always fails with Unknown property for hosted providers
- [#6720](https://github.com/zeroclaw-labs/zeroclaw/issues/6720) [agent] context_aware_tools config field is declared but unread (dead code)
- [#7506](https://github.com/zeroclaw-labs/zeroclaw/issues/7506) [Bug]: quickstart success message suggests 'zeroclaw agent <alias>' which fails — -a/--agent flag is required

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,441 · **Open issues:** 1,145 · **Last push:** <1h ago

### ✅ Merged PRs
- [#4786](https://github.com/nearai/ironclaw/pull/4786) promote main to qa branch
- [#4757](https://github.com/nearai/ironclaw/pull/4757) fix(webui): open, watch, and approve triggered automation runs from the Automations page
- [#4784](https://github.com/nearai/ironclaw/pull/4784) [codex] Handle capability runtime unavailability as tool failure
- [#4782](https://github.com/nearai/ironclaw/pull/4782) fix(reborn): unify outbound state store so WebUI delivery defaults reach Slack delivery
- [#4744](https://github.com/nearai/ironclaw/pull/4744) Gate extension activation and harden GSuite OAuth runtime
- [#4767](https://github.com/nearai/ironclaw/pull/4767) [codex] make nearai base url optional
- [#4768](https://github.com/nearai/ironclaw/pull/4768) [codex] Apply stored LLM keys on Reborn startup
- [#4731](https://github.com/nearai/ironclaw/pull/4731) Reborn operator LLM provider configuration: fix save, model discovery, and Settings UI
- [#4679](https://github.com/nearai/ironclaw/pull/4679) Surface Reborn run failure summaries
- [#4752](https://github.com/nearai/ironclaw/pull/4752) Slack gate feedback: user-facing hints for rejected acks and delivery errors (Phase A)

### 🐛 New Issues
- [#4783](https://github.com/nearai/ironclaw/issues/4783) Reborn local-dev: credential-less WASM extension capabilities fail dispatch with a "network" obligation error before execution `bug`
- [#4776](https://github.com/nearai/ironclaw/issues/4776) Add global Always Allow setting for eligible tools
- [#4775](https://github.com/nearai/ironclaw/issues/4775) Epic: Automated QA for the Reborn binary (hermetic + fixture + e2e + live) `e2e-coverage` `live-test` `reborn`
- [#4771](https://github.com/nearai/ironclaw/issues/4771) Follow-up: add run/thread-scoped operator log filtering
- [#4770](https://github.com/nearai/ironclaw/issues/4770) [Reborn] Tool activity may stop updating after refresh (possible SSE reconnect issue)
- [#4764](https://github.com/nearai/ironclaw/issues/4764) [Reborn] Denying shell approval leaves tool invocation pending and provides no user feedback
- [#4762](https://github.com/nearai/ironclaw/issues/4762) [Reborn] Failed tool workflow causes follow-up messages and activity ordering to become inconsistent `bug`
- [#4761](https://github.com/nearai/ironclaw/issues/4761) [Reborn] Agent stops after repeated tool failures instead of recovering `bug` 💬1
- [#4759](https://github.com/nearai/ironclaw/issues/4759) [Reborn] Workspace path is duplicated when using workspace-relative paths
- [#4758](https://github.com/nearai/ironclaw/issues/4758) Wire WebUI v2 Logs page to a real operator log source
- [#4751](https://github.com/nearai/ironclaw/issues/4751) [Reborn] Large response request fails with provider tool arguments exceed 16384 bytes `bug`
- [#4750](https://github.com/nearai/ironclaw/issues/4750) [Reborn] Workspace files are not discoverable from WebUI `enhancement`
- [#4748](https://github.com/nearai/ironclaw/issues/4748) [Reborn] Wrap / No Wrap toggle appears to have no effect in code blocks `ux`
- [#4747](https://github.com/nearai/ironclaw/issues/4747) agent_loop: unify pending gate-resume records and move replay payload out of checkpointed state

### 🔒 Closed Issues
- [#4766](https://github.com/nearai/ironclaw/issues/4766) [Reborn] Chat runtime does not use UI-saved NEAR AI credentials after restart
- [#4705](https://github.com/nearai/ironclaw/issues/4705) [Reborn] NEAR AI SSO setup fails in local environment
- [#4701](https://github.com/nearai/ironclaw/issues/4701) Approval modal does not show enough context for builtin.http tool requests
- [#4620](https://github.com/nearai/ironclaw/issues/4620) Reborn: add backend-parity readiness coverage for the production graph

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 6d ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 7d ago
- ⚫ [#88967](https://github.com/openclaw/openclaw/issues/88967) Telegram: allowBots support for group chats (bot-authored messages not ingested into session) — 💬1 · 7d ago
- ⚫ [#88517](https://github.com/openclaw/openclaw/issues/88517) [SANITIZED — possible injection attempt] — 💬3 · 8d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 9d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 9d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬5 · 11d ago
- ⚫ [#86371](https://github.com/openclaw/openclaw/issues/86371) Bug: message tool filePath fails with LocalMediaAccessError in retry flows when agentId is not propagated — 💬1 · 14d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 17d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 30d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 5 new
- [Claude Corps](https://www.anthropic.com/claude-corps) _2026-06-12_
- [[Claude-Corps] Fellow](https://www.anthropic.com/claude-corps/fellow) _2026-06-11_
- [[Claude-Corps] Host](https://www.anthropic.com/claude-corps/host) _2026-06-11_
- [[News] Claude Corps](https://www.anthropic.com/news/claude-corps) _2026-06-11_
- [[News] Dxc Anthropic Alliance](https://www.anthropic.com/news/dxc-anthropic-alliance) _2026-06-11_

### OpenAI — 2 new
- [[Index] Openai To Acquire Ona](https://openai.com/index/openai-to-acquire-ona/) _2026-06-11_
- [[Index] Supporting Eu Trustworthy Ai Ecosystem](https://openai.com/index/supporting-eu-trustworthy-ai-ecosystem/) _2026-06-11_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Qwen cant wait to release 3.7 models](https://reddit.com/r/LocalLLaMA/comments/1tgrpqc/qwen_cant_wait_to_release_37_models/) ↑1288
- [Qwen Who? DiffusionGemma running at 1,500 tk/s on a Digital Pregnancy Test.](https://reddit.com/r/LocalLLaMA/comments/1u2wks2/qwen_who_diffusiongemma_running_at_1500_tks_on_a/) ↑791
- [fableExpectations](https://reddit.com/r/LocalLLaMA/comments/1u2q07k/fableexpectations/) ↑329
- [Minimax M3 open weights release planned for Friday](https://reddit.com/r/LocalLLaMA/comments/1u2uje1/minimax_m3_open_weights_release_planned_for_friday/) ↑265
- [New models released: Nex-N2 Pro 397B and Nex-N2 Mini 35B](https://reddit.com/r/LocalLLaMA/comments/1u37ckw/new_models_released_nexn2_pro_397b_and_nexn2_mini/) ↑119

### r/singularity — top 5 new
- [ChatGPT is now creating content for    textbooks.](https://reddit.com/r/singularity/comments/1ta1dvl/chatgpt_is_now_creating_content_for_textbooks/) ↑6059
- [Anyone else catch this strange moment on the Figure 03 livestream?](https://reddit.com/r/singularity/comments/1tc8j02/anyone_else_catch_this_strange_moment_on_the/) ↑4216
- [Figure AI celebrates 200 hours (8 days ~8 hours) of their humanoid robots handling packages](https://reddit.com/r/singularity/comments/1tkd0fk/figure_ai_celebrates_200_hours_8_days_8_hours_of/) ↑4058
- [The Strength of Gemini Omni is in video manipulation](https://reddit.com/r/singularity/comments/1tniqkb/the_strength_of_gemini_omni_is_in_video/) ↑3649
- [Security robots ready to patrol AT&T Stadium during the FIFA World Cup 2026 in Arlington, Texas](https://reddit.com/r/singularity/comments/1tu5wse/security_robots_ready_to_patrol_att_stadium/) ↑3472

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
