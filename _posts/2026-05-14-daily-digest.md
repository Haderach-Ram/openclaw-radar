---
layout: post
title: "Ecosystem Digest — 2026-05-14"
date: 2026-05-14 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-14
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 371,626 | 9 | 8 | 5 | 3 |
| **hermesagent** | 148,792 | 10 | 0 | 6 | 0 |
| **ZeroClaw** | 31,320 | 12 | 8 | 10 | 0 |
| **IronClaw** | 12,235 | 10 | 2 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 371,626 · **Open issues:** 7,298 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.12-beta.6](https://github.com/openclaw/openclaw/releases/tag/v2026.5.12-beta.6) — openclaw 2026.5.12-beta.6
- [v2026.5.12-beta.5](https://github.com/openclaw/openclaw/releases/tag/v2026.5.12-beta.5) — openclaw 2026.5.12-beta.5
- [v2026.5.12-beta.4](https://github.com/openclaw/openclaw/releases/tag/v2026.5.12-beta.4) — openclaw 2026.5.12-beta.4

### ✅ Merged PRs
- [#79550](https://github.com/openclaw/openclaw/pull/79550) fix(sessions): report ACP-runtime metadata for ACP-keyed sessions
- [#81597](https://github.com/openclaw/openclaw/pull/81597) fix(migrate): swap glyphs on manual-review and archive item rows
- [#81591](https://github.com/openclaw/openclaw/pull/81591) Load Codex for selectable OpenAI agent models
- [#81487](https://github.com/openclaw/openclaw/pull/81487) feat(ui): add browser-local Control UI text size setting
- [#81562](https://github.com/openclaw/openclaw/pull/81562) Preserve user HOME for Codex app-server launches

### 🐛 New Issues
- [#81606](https://github.com/openclaw/openclaw/issues/81606) [Bug]: Web version WebChat shows "Maximum call stack size exceeded" when uploading attachments larger than ~4MB `bug` `bug:behavior` 💬2
- [#81598](https://github.com/openclaw/openclaw/issues/81598) [Bug]: TTS engagement is skipped on all message-tool sendMessage* paths (cross-provider; structurally unmet in group channels with visibleReplies="message_tool"; regardless of tts.auto mode) 💬1
- [#81595](https://github.com/openclaw/openclaw/issues/81595) observability: emit per-MCP-server sub-spans inside bundle-tools so cold-start cost is attributable 💬1
- [#81594](https://github.com/openclaw/openclaw/issues/81594) [Bug]: Text /steer can target slash lane instead of active direct lane 💬1
- [#81583](https://github.com/openclaw/openclaw/issues/81583) [Feature]: Full-text search across session history in Control UI 💬1
- [#81581](https://github.com/openclaw/openclaw/issues/81581) openclaw message thread create for Telegram: thread-create → topic-create remap not happening; gateway rejects with Unsupported Telegram action 💬1
- [#81575](https://github.com/openclaw/openclaw/issues/81575) Gateway path returns "incomplete terminal response" for all anthropic models — affects all gateway-routed channels (Telegram, TUI, terminal) `bug` `regression` 💬1
- [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop 💬1
- [#81566](https://github.com/openclaw/openclaw/issues/81566) nextcloud-talk channel returns 400 "Invalid payload format" on non-message Talk events (file shares) 💬1

### 🔒 Closed Issues
- [#79850](https://github.com/openclaw/openclaw/issues/79850) SSRF guard blocks hostnames ending in .internal (e.g. host.docker.internal) even with allowPrivateNetwork config
- [#81194](https://github.com/openclaw/openclaw/issues/81194) Beta audit: 2026.5.10-beta.1 -> 2026.5.12-beta.2 update findings
- [#75699](https://github.com/openclaw/openclaw/issues/75699) Feature request: native config-backed automatic context rollover with durable handoff for Telegram/direct sessions
- [#75607](https://github.com/openclaw/openclaw/issues/75607) feat(active-memory): make recall budget split configurable (maxMemoryResults, snippet length, wiki max chars)
- [#75416](https://github.com/openclaw/openclaw/issues/75416) Bug: QQBot streaming + stuck session recovery deadlock causes permanent session freeze
- [#81602](https://github.com/openclaw/openclaw/issues/81602) [Bug]: 2026.5.12-beta.6 isolated agent cron jobs failing at attempt-dispatch
- [#75239](https://github.com/openclaw/openclaw/issues/75239) WebChat assistant replies still duplicate after #66875 fix (2026.4.27)
- [#75192](https://github.com/openclaw/openclaw/issues/75192) Feature Request: Agent Selector in WebChat UI

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 148,792 · **Open issues:** 10,982 · **Last push:** <1h ago

### ✅ Merged PRs
- [#25341](https://github.com/NousResearch/hermes-agent/pull/25341) perf(tools): cache Nous auth + .env loads, drop `hermes tools` All Platforms from 14s to <1.5s
- [#25355](https://github.com/NousResearch/hermes-agent/pull/25355) feat(slack): support !cmd as alternate prefix for slash commands in threads
- [#25302](https://github.com/NousResearch/hermes-agent/pull/25302) docs: close in-tree memory plugins to new PRs and codify skill standards
- [#25307](https://github.com/NousResearch/hermes-agent/pull/25307) fix(tools-config): write video_gen.provider on Reconfigure tool path
- [#25299](https://github.com/NousResearch/hermes-agent/pull/25299) feat(skills): unified EVM multi-chain skill (salvages #25291 + #2010 + folds in base/)
- [#24182](https://github.com/NousResearch/hermes-agent/pull/24182) feat(codex-runtime): optional codex app-server runtime for OpenAI/Codex models

### 🐛 New Issues
- [#25364](https://github.com/NousResearch/hermes-agent/issues/25364) C:/Program Files/Git/model 选择器中增加思考模式（reasoning）的可视化配置
- [#25363](https://github.com/NousResearch/hermes-agent/issues/25363) 模型选择器 /model 支持置顶常用模型（favorites / LRU）
- [#25362](https://github.com/NousResearch/hermes-agent/issues/25362) [Feature]: Question：如何在对话框同时打开Hermes的两个gateway的agent
- [#25354](https://github.com/NousResearch/hermes-agent/issues/25354) [Bug] Volcengine Ark API fails with HTTP 400 due to User-Agent fingerprinting - need custom headers support for providers
- [#25352](https://github.com/NousResearch/hermes-agent/issues/25352) Settings UI: fallback_providers renders as "[object Object], [object Object]" in General settings
- [#25351](https://github.com/NousResearch/hermes-agent/issues/25351) Dashboard chat silently breaks behind reverse proxies: _hermes_ink_bundle_stale() always returns True, triggering 15s blocking npm run build on every PTY spawn 💬1
- [#25349](https://github.com/NousResearch/hermes-agent/issues/25349) Discord streaming can duplicate final responses across chunked delivery `type/bug` `comp/gateway` `platform/discord` `P2`
- [#25339](https://github.com/NousResearch/hermes-agent/issues/25339) Hermes CLI v0.13.0 shows wrong model name in banner — displays 'kimicode' instead of actual model `type/bug` `comp/cli` `P3` 💬1
- [#25335](https://github.com/NousResearch/hermes-agent/issues/25335) Feature Request: Custom Slash Commands / Shortcuts for Messaging Platforms `type/feature` `comp/cli` `comp/gateway` `P3`
- [#25333](https://github.com/NousResearch/hermes-agent/issues/25333) run_agent: 'Unrepairable tool_call arguments' when Gemini-3-Flash-Preview emits parallel tool calls as }{ — JSON parser drops them `type/bug` `comp/agent` `provider/gemini` `P1` 💬1

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,320 · **Open issues:** 472 · **Last push:** 1h ago

### ✅ Merged PRs
- [#6597](https://github.com/zeroclaw-labs/zeroclaw/pull/6597) fix(providers): supports_vision() must reflect default/primary, not .any() (#6589)
- [#6600](https://github.com/zeroclaw-labs/zeroclaw/pull/6600) fix(providers): trust system CA roots for provider HTTPS requests
- [#6599](https://github.com/zeroclaw-labs/zeroclaw/pull/6599) fix(runtime): load workspace profiles at startup
- [#6601](https://github.com/zeroclaw-labs/zeroclaw/pull/6601) fix(tools): resolve gws via PATH so Windows .cmd shims work
- [#6633](https://github.com/zeroclaw-labs/zeroclaw/pull/6633) fix(gateway/nextcloud-talk): process webhook async to avoid 5s cancel (#6156)
- [#6610](https://github.com/zeroclaw-labs/zeroclaw/pull/6610) fix(matrix): include attachment media metadata
- [#6612](https://github.com/zeroclaw-labs/zeroclaw/pull/6612) fix(gateway): cancel turn on WS disconnect to stop forward_fut spin (#6514)
- [#6614](https://github.com/zeroclaw-labs/zeroclaw/pull/6614) fix(providers): use --prompt for gemini-cli (replaces removed --print) (#6520)
- [#6615](https://github.com/zeroclaw-labs/zeroclaw/pull/6615) fix(providers): accept `reasoning` alias on OpenAI-compatible responses (#6584)
- [#6527](https://github.com/zeroclaw-labs/zeroclaw/pull/6527) fix(gateway,runtime): broadcast agent observer events to /api/events SSE

### 🐛 New Issues
- [#6648](https://github.com/zeroclaw-labs/zeroclaw/issues/6648) [Bug]: cron session_target=main still runs in an isolated cron session `bug` `risk: high` `cron` `runtime` `priority:p2`
- [#6647](https://github.com/zeroclaw-labs/zeroclaw/issues/6647) [Bug]: Title: Cron job output not routed to configured channels `bug`
- [#6646](https://github.com/zeroclaw-labs/zeroclaw/issues/6646) [Bug]: Title: web_search_tool and web_fetch not firing via Telegram channel in v0.7.5 `bug`
- [#6645](https://github.com/zeroclaw-labs/zeroclaw/issues/6645) SkillImprover + skill_manage only handle `SKILL.toml`, not `manifest.toml`
- [#6644](https://github.com/zeroclaw-labs/zeroclaw/issues/6644) Skill review fork: `💾` summary parser misses tool receipts
- [#6643](https://github.com/zeroclaw-labs/zeroclaw/issues/6643) [Bug]: Thoughts merge into final message using GLM-5.1 `bug`
- [#6642](https://github.com/zeroclaw-labs/zeroclaw/issues/6642) [Feature]: Capture full prompt/completion on llm.call spans via gen_ai.input.messages / gen_ai.output.messages `enhancement` `observability`
- [#6641](https://github.com/zeroclaw-labs/zeroclaw/issues/6641) [Feature]: Turn-level OTel trace correlation — nest llm.call / tool.call / memory.* spans under a single turn trace `enhancement` `observability`
- [#6637](https://github.com/zeroclaw-labs/zeroclaw/issues/6637) feat(gateway): clarify /api/events lifecycle event semantics `enhancement` `gateway` `observability` `gateway: sse` `priority:p3`
- [#6634](https://github.com/zeroclaw-labs/zeroclaw/issues/6634) [Bug]: cron-scheduled webhook callbacks drop thread_id `bug` `risk: high` `channel` `config` `cron` `gateway` `runtime` `priority:p2` `channel:webhook` `status:in-progress` `status:no-stale`
- [#6632](https://github.com/zeroclaw-labs/zeroclaw/issues/6632) bug(cron): manual cron_run still persists best-effort delivery failures as ok `bug` `risk: high` `cron` `runtime` `tool`
- [#6627](https://github.com/zeroclaw-labs/zeroclaw/issues/6627) [Bug]: Stale tool-result images replay across later provider turns `bug` `risk: medium` `provider` `priority:p1` `status:in-progress`

### 🔒 Closed Issues
- [#6589](https://github.com/zeroclaw-labs/zeroclaw/issues/6589) [SANITIZED — possible injection attempt]
- [#6528](https://github.com/zeroclaw-labs/zeroclaw/issues/6528) [Bug]: Trust system CA for provider requests
- [#6419](https://github.com/zeroclaw-labs/zeroclaw/issues/6419) [Bug]: WorkspaceManager fails to load profiles at Runtime startup
- [#6410](https://github.com/zeroclaw-labs/zeroclaw/issues/6410) [Bug]: google_workspace tool fails to find gws on Windows and mangles --params JSON via shell fallback
- [#6156](https://github.com/zeroclaw-labs/zeroclaw/issues/6156) [Bug]: Nextcloud Talk model request is canceled after ~5sec
- [#6609](https://github.com/zeroclaw-labs/zeroclaw/issues/6609) [Bug]: Matrix outbound attachments omit size metadata
- [#6514](https://github.com/zeroclaw-labs/zeroclaw/issues/6514) [Bug]: gateway WebSocket turn may spin after client disconnect and make abort/health unresponsive
- [#6520](https://github.com/zeroclaw-labs/zeroclaw/issues/6520) [Bug]:Gemini CLI provider crashes due to outdated argument syntax (--print vs --prompt)

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,235 · **Open issues:** 888 · **Last push:** <1h ago

### ✅ Merged PRs
- [#3559](https://github.com/nearai/ironclaw/pull/3559) fix(extensions): restore chat-driven tool_install + fix double-invoke + auto-approve footgun (#3533)
- [#3589](https://github.com/nearai/ironclaw/pull/3589) test(e2e): unxfail two auth-matrix tests now that contracts match
- [#3469](https://github.com/nearai/ironclaw/pull/3469) GitHub issue #3433: [Reborn] Complete HostManagedModelGateway budget, credential, and redaction tests
- [#3561](https://github.com/nearai/ironclaw/pull/3561) Architectural improvements: isolate product inbound turn handoff
- [#3536](https://github.com/nearai/ironclaw/pull/3536) [Reborn] Add deterministic instruction bundle builder
- [#3574](https://github.com/nearai/ironclaw/pull/3574) docs(reborn): add channel porting guide
- [#3541](https://github.com/nearai/ironclaw/pull/3541) Architectural improvements: preserve typed dispatch failure kinds
- [#3521](https://github.com/nearai/ironclaw/pull/3521) feat(reborn): add substrate composition root
- [#3545](https://github.com/nearai/ironclaw/pull/3545) Architectural improvements: reuse host-managed prompt bundle port
- [#3528](https://github.com/nearai/ironclaw/pull/3528) feat(reborn-cli): add inspection command surfaces

### 🐛 New Issues
- [#3582](https://github.com/nearai/ironclaw/issues/3582) Port WeChat channel to Reborn ProductAdapter `scope: channel` `scope: channel/wasm` `suggested_P0` `reborn`
- [#3581](https://github.com/nearai/ironclaw/issues/3581) Port Telegram channel to Reborn ProductAdapter `scope: channel` `scope: channel/wasm` `suggested_P0` `reborn`
- [#3580](https://github.com/nearai/ironclaw/issues/3580) Port WebUI / Web Gateway to native Reborn surface `scope: channel` `scope: channel/web` `suggested_P0` `reborn`
- [#3579](https://github.com/nearai/ironclaw/issues/3579) Port Slack channel to Reborn ProductAdapter `scope: channel` `scope: channel/wasm` `suggested_P0` `reborn`
- [#3578](https://github.com/nearai/ironclaw/issues/3578) Define host-owned ingress boundary for Reborn HTTP surfaces `reborn`
- [#3577](https://github.com/nearai/ironclaw/issues/3577) Track Reborn ports for v1 channels `scope: channel` `scope: channel/web` `scope: channel/wasm` `suggested_P0` `reborn`
- [#3576](https://github.com/nearai/ironclaw/issues/3576) Reborn: harvest pi_agent_rust runtime, extension, and security patterns `enhancement` `risk: high` `scope: agent` `scope: safety` `scope: extensions` `reborn` 💬1
- [#3572](https://github.com/nearai/ironclaw/issues/3572) Structure Reborn ProductAdapters as WASM components in separate runtime `reborn`
- [#3571](https://github.com/nearai/ironclaw/issues/3571) Refactor HostHttpEgressService to accept Arc<dyn SecretStore>
- [#3567](https://github.com/nearai/ironclaw/issues/3567) [Reborn] Self-authored hooks: agent-created restrictions with monotonic-restriction + unforgeable-channel ratification

### 🔒 Closed Issues
- [#3459](https://github.com/nearai/ironclaw/issues/3459) [Reborn] Add user-selectable model routes and provider pool
- [#2905](https://github.com/nearai/ironclaw/issues/2905) [QA] the agent is saving files /home/agent which is not accessible in the hosted setup

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬1 · 2h ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 1d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 4d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Claude For Small Business](https://www.anthropic.com/news/claude-for-small-business) _2026-05-13_

### OpenAI — 2 new
- [[Business] Amex Chatgpt Business Credit](https://openai.com/business/amex-chatgpt-business-credit/) _2026-05-13_
- [[Index] Building Codex Windows Sandbox](https://openai.com/index/building-codex-windows-sandbox/) _2026-05-13_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
