---
layout: post
title: "Ecosystem Digest — 2026-05-22"
date: 2026-05-22 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-22
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 373,773 | 10 | 6 | 10 | 2 |
| **hermesagent** | 161,614 | 7 | 5 | 7 | 0 |
| **ZeroClaw** | 31,510 | 15 | 2 | 2 | 1 |
| **IronClaw** | 12,309 | 9 | 5 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 373,773 · **Open issues:** 7,413 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.20](https://github.com/openclaw/openclaw/releases/tag/v2026.5.20) — openclaw 2026.5.20
- [v2026.5.20-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.5.20-beta.2) — openclaw 2026.5.20-beta.2

### ✅ Merged PRs
- [#85167](https://github.com/openclaw/openclaw/pull/85167) feat(tui): coalesce repeated idle TUI abort notices
- [#85154](https://github.com/openclaw/openclaw/pull/85154) fix: require configured subagent allowlist targets
- [#84974](https://github.com/openclaw/openclaw/pull/84974) fix(codex): make post-tool raw assistant timeout configurable
- [#85135](https://github.com/openclaw/openclaw/pull/85135) fix(agents): preserve accepted spawn terminal success
- [#85140](https://github.com/openclaw/openclaw/pull/85140) fix: redact denied exec failure params
- [#84423](https://github.com/openclaw/openclaw/pull/84423) fix(cli): keep nodes json stdout clean
- [#85139](https://github.com/openclaw/openclaw/pull/85139) Fix inherited XDG env for exec subprocesses
- [#85142](https://github.com/openclaw/openclaw/pull/85142) perf: skip DTS for local launcher rebuilds
- [#85143](https://github.com/openclaw/openclaw/pull/85143) fix(changelog): record provider setup trust fix
- [#85137](https://github.com/openclaw/openclaw/pull/85137) Fix Matrix configured two-person room routing

### 🐛 New Issues
- [#85177](https://github.com/openclaw/openclaw/issues/85177) [Bug]: claude-cli sessions lose all conversation history after auth-profile / auth-epoch invalidation (reseed fallback silently drops the transcript) `bug` 💬1
- [#85175](https://github.com/openclaw/openclaw/issues/85175) [Feature]: `sendPolicy.peerEquals: "inboundPeer"` — relational predicate to constrain outbound to the current turn's inbound peer 💬1
- [#85174](https://github.com/openclaw/openclaw/issues/85174) [Bug]: user-plugin hook handlers do not dispatch at runtime despite `✓ ready` in `openclaw hooks list` `P2` `issue-rating: 🦞 diamond lobster` 💬1
- [#85165](https://github.com/openclaw/openclaw/issues/85165) [Bug]: token counting broken with local LLM, only user prompts counted `bug` `regression` `P2` `clawsweeper:needs-live-repro` `impact:session-state` `issue-rating: 🐚 platinum hermit` 💬1
- [#85161](https://github.com/openclaw/openclaw/issues/85161) [Bug]: valid tool call XML in LLM reasoning block is sometimes executed by gateway `bug` `bug:behavior` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-security-review` `clawsweeper:needs-info` `impact:session-state` `impact:security` `issue-rating: 🦪 silver shellfish` 💬1
- [#85157](https://github.com/openclaw/openclaw/issues/85157) Plugin-owned conversation bindings intercept native detach/control commands `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#85156](https://github.com/openclaw/openclaw/issues/85156) [Bug]: gemini-3-flash-preview cron sessions still downgrade thinkingDefault "low" to "off" on 2026.5.19 — interactive path fixed but cron path remains broken `bug` `bug:behavior` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#85149](https://github.com/openclaw/openclaw/issues/85149) [Bug]: msteams federated managed identity ignores FIC, leaks MI appid in outbound Bot Framework calls `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#85146](https://github.com/openclaw/openclaw/issues/85146) Bug: `openclaw plugins install` silently upgrades ACP and breaks existing ACP setup `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬1
- [#85145](https://github.com/openclaw/openclaw/issues/85145) openai-codex provider auth: paste-token produces wrong shape; missing API-key mode CLI `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬2

### 🔒 Closed Issues
- [#84811](https://github.com/openclaw/openclaw/issues/84811) agents_list shows orphaned allowlist entries as spawnable agents; sessions_spawn accepts them without validation
- [#85168](https://github.com/openclaw/openclaw/issues/85168) [Bug]: Telegram ingress spool — orphan claim from prior container blocks all inbound (processExists(1) false-positive in PID-namespaced runtimes)
- [#85049](https://github.com/openclaw/openclaw/issues/85049) exec-denied raw_params logged verbatim in gateway.err.log can capture cleartext env-var credentials
- [#85017](https://github.com/openclaw/openclaw/issues/85017) [SANITIZED — possible injection attempt]
- [#72541](https://github.com/openclaw/openclaw/issues/72541) Gateway completeness check false-negative on pure-relay agents
- [#84854](https://github.com/openclaw/openclaw/issues/84854) [Bug]: XDG Base Directory env vars are not inherited by subprocesses, breaking XDG-aware tools (gogcli, mcporter, others)

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬105 · 4h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 161,614 · **Open issues:** 12,917 · **Last push:** <1h ago

### ✅ Merged PRs
- [#30166](https://github.com/NousResearch/hermes-agent/pull/30166) fix(skills,tui): load Linux skills on Termux + salvage adybag14-cyber's Ink TUI termux gates
- [#30145](https://github.com/NousResearch/hermes-agent/pull/30145) fix(computer-use): cap AX elements array to prevent context blowup (#22865)
- [#30162](https://github.com/NousResearch/hermes-agent/pull/30162) fix(tui): preserve scrollback when branching sessions
- [#30084](https://github.com/NousResearch/hermes-agent/pull/30084) feat(tui): mouse_tracking DEC mode presets (salvage of #26681)
- [#30126](https://github.com/NousResearch/hermes-agent/pull/30126) fix(computer_use): route SOM/vision captures via auxiliary.vision (#24015)
- [#29387](https://github.com/NousResearch/hermes-agent/pull/29387) fix(ci): stop pushing per-commit SHA tags to Docker Hub
- [#30121](https://github.com/NousResearch/hermes-agent/pull/30121) perf(termux): speed up non-tui cli startup (salvage #29438)

### 🐛 New Issues
- [#30170](https://github.com/NousResearch/hermes-agent/issues/30170) [Bug]: Sending a message while delegate_task is running kills the subagent — interrupt propagates unconditionally to children `type/bug` `comp/agent` `comp/gateway` `tool/delegate`
- [#30155](https://github.com/NousResearch/hermes-agent/issues/30155) `--replace` cross-kills sibling gateways when multiple HERMES_PROFILE values share one HERMES_HOME `type/bug` `comp/gateway` `area/config` `P2` 💬1
- [#30152](https://github.com/NousResearch/hermes-agent/issues/30152) [bug] api_mode: gemini providers route through OpenAI SDK; URL trailing-slash breaks :generateContent (HTTP 404) `type/bug` `comp/agent` `provider/gemini` `P2`
- [#30151](https://github.com/NousResearch/hermes-agent/issues/30151) Hermes Kanban “Scratch Workspace” Cleanup Silently Deleted My Entire Projects Directory `type/bug` `comp/agent` `P1` 💬1
- [#30150](https://github.com/NousResearch/hermes-agent/issues/30150) hermes-simplex-bugs-report `type/bug` `comp/plugins` `P3` 💬1
- [#30149](https://github.com/NousResearch/hermes-agent/issues/30149) [Bug]: Failed to initialize agent: The 'anthropic' package is required for the Anthropic provider. Install it with: pip install 'anthropic>=0.39.0' `type/bug` `provider/anthropic` `area/config` `P3`
- [#30144](https://github.com/NousResearch/hermes-agent/issues/30144) DingTalk sampleFile returns "robot 不存在" (robot not found) for internal apps `type/bug` `comp/gateway` `platform/dingtalk` `P2` 💬1

### 🔒 Closed Issues
- [#22865](https://github.com/NousResearch/hermes-agent/issues/22865) computer_use capture can blow context on Electron/Obsidian AX trees
- [#30143](https://github.com/NousResearch/hermes-agent/issues/30143) DingTalk sampleFile returns "robot 不存在" (robot not found) for internal apps
- [#30142](https://github.com/NousResearch/hermes-agent/issues/30142) Test issue - please ignore
- [#21844](https://github.com/NousResearch/hermes-agent/issues/21844) Bug: memory tool replace/remove operations fail — old_text parameter not recognized
- [#15843](https://github.com/NousResearch/hermes-agent/issues/15843) [Bug]: Memory Tool Cannot Delete Old Data - memory tool remove/replace operations failing

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,510 · **Open issues:** 519 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.8.0-beta-1](https://github.com/zeroclaw-labs/zeroclaw/releases/tag/v0.8.0-beta-1) — v0.8.0-beta-1

### ✅ Merged PRs
- [#6839](https://github.com/zeroclaw-labs/zeroclaw/pull/6839) feat(runtime): RPC dispatch layer and Unix socket transport
- [#6816](https://github.com/zeroclaw-labs/zeroclaw/pull/6816) fix(policy): allow multiline heredocs in SecurityPolicy command splitting

### 🐛 New Issues
- [#6846](https://github.com/zeroclaw-labs/zeroclaw/issues/6846) NEXUS x402 prediction market data — Kalshi/Polymarket arb API
- [#6844](https://github.com/zeroclaw-labs/zeroclaw/issues/6844) [Bug]: slack bot_token needs to be in the configuration and cannot be supplied by environment variable `bug`
- [#6841](https://github.com/zeroclaw-labs/zeroclaw/issues/6841) [Bug]: [multimodal] vision_provider silently ignored — inbound images routed to providers.fallback instead `bug`
- [#6837](https://github.com/zeroclaw-labs/zeroclaw/issues/6837) [Feature]: Runtime RPC dispatch layer and Unix socket transport `enhancement` `size: XL` `risk: medium` `daemon` `runtime`
- [#6836](https://github.com/zeroclaw-labs/zeroclaw/issues/6836) [Bug]: setup.bat --minimal produces ~26 MB build instead of ~6 MB on Windows `bug`
- [#6827](https://github.com/zeroclaw-labs/zeroclaw/issues/6827) [Feature]: Support jina.ai as web_search provider `enhancement`
- [#6826](https://github.com/zeroclaw-labs/zeroclaw/issues/6826) [Tracker]: ZeroClaw TUI `enhancement`
- [#6825](https://github.com/zeroclaw-labs/zeroclaw/issues/6825) [Tracker]: TUI UX `enhancement`
- [#6824](https://github.com/zeroclaw-labs/zeroclaw/issues/6824) [Tracker]: TUI Agent Chat `enhancement` 💬1
- [#6823](https://github.com/zeroclaw-labs/zeroclaw/issues/6823) [Tracker]: TUI ACP Bridge `enhancement`
- [#6822](https://github.com/zeroclaw-labs/zeroclaw/issues/6822) [Feature]: Add zeroclaw-tui to release build matrix and package managers `enhancement`
- [#6821](https://github.com/zeroclaw-labs/zeroclaw/issues/6821) [Feature]: Move crates/zeroclaw-tui to apps/tui `enhancement` 💬1
- [#6820](https://github.com/zeroclaw-labs/zeroclaw/issues/6820) [Feature]: ACP protocol extensions for diff/file-proposal message types `enhancement` `gateway` 💬2
- [#6819](https://github.com/zeroclaw-labs/zeroclaw/issues/6819) [Feature]: File/attachment upload protocol `enhancement` `gateway`
- [#6818](https://github.com/zeroclaw-labs/zeroclaw/issues/6818) [Feature]: --ephemeral daemon mode `enhancement` `daemon`

### 🔒 Closed Issues
- [#5890](https://github.com/zeroclaw-labs/zeroclaw/issues/5890) RFC: Multi-agent UX flow — design
- [#6771](https://github.com/zeroclaw-labs/zeroclaw/issues/6771) [Bug]: Multiline Heredocs incorrectly blocked by SecurityPolicy

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,309 · **Open issues:** 950 · **Last push:** 1h ago

### ✅ Merged PRs
- [#3831](https://github.com/nearai/ironclaw/pull/3831) [codex] Finish staged secret egress framework
- [#3848](https://github.com/nearai/ironclaw/pull/3848) [codex] Adapt skill bundles into Reborn skill context
- [#3852](https://github.com/nearai/ironclaw/pull/3852) fix(workflow): address before-inbound policy review follow-up
- [#3759](https://github.com/nearai/ironclaw/pull/3759) feat: (product-workflow) Add durable product workflow ledger
- [#3827](https://github.com/nearai/ironclaw/pull/3827) Group first-party host API bindings
- [#3826](https://github.com/nearai/ironclaw/pull/3826) Add Reborn process port seam
- [#3740](https://github.com/nearai/ironclaw/pull/3740) feat(reborn): webui error taxonomy
- [#3849](https://github.com/nearai/ironclaw/pull/3849) test(reborn): cover project and agent isolation
- [#3847](https://github.com/nearai/ironclaw/pull/3847) [codex] Add filesystem-backed Reborn skill bundle source
- [#3819](https://github.com/nearai/ironclaw/pull/3819) test(reborn): cover tenant binding isolation

### 🐛 New Issues
- [#3866](https://github.com/nearai/ironclaw/issues/3866) NEXUS x402 prediction market data — Kalshi/Polymarket arb API
- [#3857](https://github.com/nearai/ironclaw/issues/3857) [Reborn] Lane 10: add Slack ProductAdapter MVP with preconfigured credentials `reborn`
- [#3846](https://github.com/nearai/ironclaw/issues/3846) [Question] Mission notify_channels inherit selected conversation source in Web UI Chat `question`
- [#3840](https://github.com/nearai/ironclaw/issues/3840) Improve channel badges in Web UI conversation list `enhancement`
- [#3839](https://github.com/nearai/ironclaw/issues/3839) Failed Mission “Retry” button calls fire endpoint but returns fired:false
- [#3821](https://github.com/nearai/ironclaw/issues/3821) Thread::restore_from_messages drops orphan assistant rows, preventing out-of-band context injection
- [#3812](https://github.com/nearai/ironclaw/issues/3812) [Reborn] Step 3: Implement Reborn-native OAuth callbacks and setup continuations
- [#3811](https://github.com/nearai/ironclaw/issues/3811) [Reborn] Step 2: Wire Reborn-native product auth and secrets composition 💬1
- [#3810](https://github.com/nearai/ironclaw/issues/3810) [Reborn] Step 1: Auth product contracts, V1 behavior inventory, and fake-service tests

### 🔒 Closed Issues
- [#3623](https://github.com/nearai/ironclaw/issues/3623) [Reborn WebUI Beta] Add BeforeInboundPolicy seam for ProductWorkflow
- [#3610](https://github.com/nearai/ironclaw/issues/3610) [Reborn WebUI Beta] Preserve typed filesystem errors in ProcessError
- [#3013](https://github.com/nearai/ironclaw/issues/3013) Reborn cutover blocker: add kernel TurnCoordinator
- [#3039](https://github.com/nearai/ironclaw/issues/3039) Reborn final integration PR reviewer checklist
- [#3085](https://github.com/nearai/ironclaw/issues/3085) Use shared Reborn runtime HTTP egress for WASM, Script, and MCP

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 5d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬2 · 6d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 9d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Legal] Promotion Credit Terms](https://www.anthropic.com/legal/promotion-credit-terms) _2026-05-21_

### OpenAI — 1 new
- [[Index] Adventhealth](https://openai.com/index/adventhealth/) _2026-05-21_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
