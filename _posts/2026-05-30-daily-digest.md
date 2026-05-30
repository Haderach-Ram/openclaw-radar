---
layout: post
title: "Ecosystem Digest — 2026-05-30"
date: 2026-05-30 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-30
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 375,524 | 10 | 5 | 10 | 4 |
| **hermesagent** | 172,894 | 11 | 4 | 8 | 1 |
| **ZeroClaw** | 31,636 | 12 | 1 | 5 | 0 |
| **IronClaw** | 12,373 | 8 | 1 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 375,524 · **Open issues:** 7,082 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.28-beta.4](https://github.com/openclaw/openclaw/releases/tag/v2026.5.28-beta.4) — openclaw 2026.5.28-beta.4
- [v2026.5.28-beta.3](https://github.com/openclaw/openclaw/releases/tag/v2026.5.28-beta.3) — openclaw 2026.5.28-beta.3
- [v2026.5.28-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.5.28-beta.2) — openclaw 2026.5.28-beta.2
- [v2026.5.28-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.5.28-beta.1) — openclaw 2026.5.28-beta.1

### ✅ Merged PRs
- [#88161](https://github.com/openclaw/openclaw/pull/88161) Fix restart sentinel internal continuations
- [#88134](https://github.com/openclaw/openclaw/pull/88134) fix(imessage): preserve SMS approval reply routes
- [#88191](https://github.com/openclaw/openclaw/pull/88191) Fix Codex raw image generation media projection
- [#88182](https://github.com/openclaw/openclaw/pull/88182) Fix subagent DM completion delivery after yield
- [#88162](https://github.com/openclaw/openclaw/pull/88162) fix(agents): extend terminal outcome projections
- [#88178](https://github.com/openclaw/openclaw/pull/88178) feat(workboard): add orchestration primitives
- [#84814](https://github.com/openclaw/openclaw/pull/84814) fix(agents): classify embedded provider business denials for fallback
- [#88107](https://github.com/openclaw/openclaw/pull/88107) feat: only include the current changelog section in tarball
- [#88130](https://github.com/openclaw/openclaw/pull/88130) fix(agents): preserve Codex auth for compaction fallback
- [#84535](https://github.com/openclaw/openclaw/pull/84535) fix(gateway): resolve message actions against runtime config

### 🐛 New Issues
- [#88201](https://github.com/openclaw/openclaw/issues/88201) [Bug]: OpenClaw 5.22: ~10 sec per-call inference overhead in infer model run (both --gateway and --local) vs ~1.3 sec direct provider call `bug` `regression`
- [#88198](https://github.com/openclaw/openclaw/issues/88198) Bug: independent scripts in ~/.openclaw/extensions/ crash Gateway (missing openclaw.plugin.json) `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:crash-loop` `issue-rating: 🦞 diamond lobster` 💬1
- [#88197](https://github.com/openclaw/openclaw/issues/88197) cron: deleteAfterRun 失败 run 不触发删除导致孤儿堆积 `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#88196](https://github.com/openclaw/openclaw/issues/88196) Codex cron agentTurn regression: app-server attempt/turn idle timeout after 2026.5.27 `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬1
- [#88195](https://github.com/openclaw/openclaw/issues/88195) ${ENV_VAR} refs in plugins.entries.*.config not resolved before passing to plugin (regression in 2026.5.28-beta.4) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:needs-info` `impact:auth-provider` `issue-rating: 🦐 gold shrimp` 💬1
- [#88188](https://github.com/openclaw/openclaw/issues/88188) Auto-compaction not triggering despite config (midTurnPrecheck + maxActiveTranscriptBytes) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `issue-rating: 🐚 platinum hermit` 💬2
- [#88176](https://github.com/openclaw/openclaw/issues/88176) [Bug]: Control UI Chat Talk shows stale 'gpt-realtime' error even when gateway-relay talk.session.create succeeds 💬1
- [#88173](https://github.com/openclaw/openclaw/issues/88173) RFC: Skills Dependency Visualizer — understand skill interdependencies visually `P3` 💬3
- [#88168](https://github.com/openclaw/openclaw/issues/88168) Synthetic 'missing tool result' entries injected for parallel tool calls on Anthropic Claude, despite real results being produced `P1` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬2
- [#88167](https://github.com/openclaw/openclaw/issues/88167) Approval-gate denials routed via followup-channel produce phantom 'missing tool result' synthetic placeholders `P2` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬1

### 🔒 Closed Issues
- [#87792](https://github.com/openclaw/openclaw/issues/87792) Restart-sentinel turn on channel-bound session emits outbound reply to source chat
- [#87948](https://github.com/openclaw/openclaw/issues/87948) Codex app-server idle watchdog fires after image_generation_call raw completed item
- [#88042](https://github.com/openclaw/openclaw/issues/88042) Subagent announce fails after sessions_yield: adapter unavailable during yield suspension
- [#88187](https://github.com/openclaw/openclaw/issues/88187) [Bug] Feishu dispatch fails after upgrade to v2026.5.27 on Windows - TypeError Cannot read properties of undefined reading run
- [#88179](https://github.com/openclaw/openclaw/issues/88179) ERR_INVALID_STATE crash: FileHandle closed during GC in session-write-lock (Node.js v25)

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 3d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 172,894 · **Open issues:** 15,002 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.29.2](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.5.29.2) — Hermes Agent v0.15.2 (2026.5.29.2)

### ✅ Merged PRs
- [#35081](https://github.com/NousResearch/hermes-agent/pull/35081) fix(gateway): name what the /status token number actually is
- [#34853](https://github.com/NousResearch/hermes-agent/pull/34853) fix(gateway): drop outbound silence-narration messages pre-send
- [#35054](https://github.com/NousResearch/hermes-agent/pull/35054) fix(compression): avoid repeat preflight compaction from rough estimates
- [#34839](https://github.com/NousResearch/hermes-agent/pull/34839) fix(cli): repaint input area after inline /steer and /model submit
- [#35048](https://github.com/NousResearch/hermes-agent/pull/35048) Inspired by Claude Code: /compress here [N] — boundary-aware 'summarize up to here'
- [#34835](https://github.com/NousResearch/hermes-agent/pull/34835) fix(cli): remove Hermes-managed node/npm/npx symlinks on uninstall
- [#34845](https://github.com/NousResearch/hermes-agent/pull/34845) fix(auxiliary): stop capping output with max_tokens by default (#34530)
- [#34851](https://github.com/NousResearch/hermes-agent/pull/34851) fix(deps): declare setuptools in dev extra for packaging tests

### 🐛 New Issues
- [#35084](https://github.com/NousResearch/hermes-agent/issues/35084) [Setup]: Docker build fails on QNAP NAS: s6-overlay "Cannot change mode" Bad address
- [#35080](https://github.com/NousResearch/hermes-agent/issues/35080) kanban create --priority should accept human-readable strings (high/medium/low) in addition to integers
- [#35075](https://github.com/NousResearch/hermes-agent/issues/35075) [Bug]: cron injection scanner misses invisible-unicode classes the install-time scanner catches `type/security` `comp/agent` `comp/tools` `comp/cron` `P1` 💬1
- [#35072](https://github.com/NousResearch/hermes-agent/issues/35072) Kanban worker iteration-budget exhaustion creates permanent sticky block (no auto-recovery) `type/bug` `comp/agent` `comp/cli` `P3`
- [#35070](https://github.com/NousResearch/hermes-agent/issues/35070) Version mismatch: hermes_cli/__init__.py gets reverted during upgrade conflict resolution `type/bug` `comp/cli` `P3`
- [#35067](https://github.com/NousResearch/hermes-agent/issues/35067) security: pin patched Starlette for CVE-2026-48710 BadHost `type/security` `comp/gateway` `area/config` `P1`
- [#35063](https://github.com/NousResearch/hermes-agent/issues/35063) Proposal: native ACP client transport alongside copilot_acp_client.py shim `type/feature` `comp/agent` `comp/acp` `P3` 💬1
- [#35062](https://github.com/NousResearch/hermes-agent/issues/35062) [Weixin] ret=-3 cron push silently fails after tokenless retry (regression from v0.14) `type/bug` `comp/gateway` `comp/cron` `P2` 💬1
- [#35060](https://github.com/NousResearch/hermes-agent/issues/35060) Feature Request: Configurable `deliver` target for `watch_entities`/`watch_domains` in Home Assistant integration `type/feature` `comp/gateway` `P3`
- [#35059](https://github.com/NousResearch/hermes-agent/issues/35059) non-default profile gateway fails: /root/.ssh/config not found `type/bug` `backend/ssh` `comp/cli` `comp/gateway` `area/docker` `P2` 💬1
- [#35057](https://github.com/NousResearch/hermes-agent/issues/35057) macOS iTerm2: Shift+Enter should insert newline in prompt_toolkit CLI `type/feature` `comp/cli` `P3` 💬1

### 🔒 Closed Issues
- [#34616](https://github.com/NousResearch/hermes-agent/issues/34616) gateway: drop outbound 'silence narration' messages pre-send (anti-loop control)
- [#34569](https://github.com/NousResearch/hermes-agent/issues/34569) /steer leaves submitted prompt in TUI input buffer, allows accidental re-submit
- [#34071](https://github.com/NousResearch/hermes-agent/issues/34071) [Bug] v0.15.0 Docker image: stage2-hook.sh, main-wrapper.sh missing; container_boot module removed
- [#30931](https://github.com/NousResearch/hermes-agent/issues/30931) [Bug]: Image generation (and perhaps other Python-dependent tools) broken when Hermes Agent installed via Nix

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,636 · **Open issues:** 543 · **Last push:** <1h ago

### ✅ Merged PRs
- [#6607](https://github.com/zeroclaw-labs/zeroclaw/pull/6607) fix(providers): respect explicit provider kind
- [#5450](https://github.com/zeroclaw-labs/zeroclaw/pull/5450) fix(tools): add ipv6 support and use reqwest.url
- [#6945](https://github.com/zeroclaw-labs/zeroclaw/pull/6945) feat(agents): add per-agent `classifier_provider` to route reply-intent precheck to a cheaper model
- [#6907](https://github.com/zeroclaw-labs/zeroclaw/pull/6907) feat(memory): introduce MemoryStrategy trait and DefaultMemoryStrategy
- [#6884](https://github.com/zeroclaw-labs/zeroclaw/pull/6884) fix(web_fetch): treat max_response_size=0 as unlimited

### 🐛 New Issues
- [#7005](https://github.com/zeroclaw-labs/zeroclaw/issues/7005) [Bug]: Onboarding wizard still has pre-existing bare user-facing strings `bug` `risk: medium` `onboard` `runtime` `priority:p2`
- [#7001](https://github.com/zeroclaw-labs/zeroclaw/issues/7001) [Bug]: TTS voice replies resolve the wrong agent's tts_provider in multi-agent configs `bug` `risk: medium` `channel` `config` `provider` `channel:telegram` `priority:p2`
- [#6999](https://github.com/zeroclaw-labs/zeroclaw/issues/6999) [Bug]: Telegram voice transcription always fails — channel never wires transcription_provider alias `bug` `risk: high` `channel` `provider` `channel:telegram` `priority:p1` `channel:transcription`
- [#6998](https://github.com/zeroclaw-labs/zeroclaw/issues/6998) RFC: Schema-Guided Reasoning (SGR) — cross-provider structured output `enhancement` `risk: high` `memory` `provider` `runtime` `tool` `priority:p2` `needs-maintainer-review` `type:rfc`
- [#6997](https://github.com/zeroclaw-labs/zeroclaw/issues/6997) [Bug]: Documentation version does not match latest release `bug` `type: docs` `risk: medium` `docs` `priority:p2` `web`
- [#6996](https://github.com/zeroclaw-labs/zeroclaw/issues/6996) RFC: Granular sandbox policy — filesystem and network restrictions `enhancement` `risk: high` `config` `runtime` `security` `priority:p2` `needs-maintainer-review` `type:rfc`
- [#6995](https://github.com/zeroclaw-labs/zeroclaw/issues/6995) [Bug]: Backspace in `zeroclaw agent` CLI deletes byte-by-byte instead of character-by-character (UTF-8 CJK chars need 3 backspaces) `bug` `risk: low` `agent` `channel` `runtime` `channel:cli` `priority:p3`
- [#6992](https://github.com/zeroclaw-labs/zeroclaw/issues/6992) [Bug]: Slack Socket Mode rejects all messages as "unauthorized user" `bug` `risk: high` `channel` `channel:slack` `priority:p1`
- [#6991](https://github.com/zeroclaw-labs/zeroclaw/issues/6991) bug(runtime): Native tool serialization (tools_to_openai_format) ignores Risk Profile and Tool Filter restrictions in v0.8.0-beta-1 `bug` `risk: high` `agent` `provider` `runtime` `security` `tool` `priority:p1`
- [#6990](https://github.com/zeroclaw-labs/zeroclaw/issues/6990) i18n: bring new file_download tool strings under the fl!() / Fluent contract `enhancement` `risk: low` `tool` `priority:p3` `follow-up`
- [#6989](https://github.com/zeroclaw-labs/zeroclaw/issues/6989) config: extend #[secret] (or add a header-token field) so headers maps redact bearer tokens `bug` `risk: high` `config` `security` `tool` `priority:p1` `status:accepted` `status:no-stale` `follow-up` 💬1
- [#6970](https://github.com/zeroclaw-labs/zeroclaw/issues/6970) [Tracker]: v0.8.1 integration/channel/provider/tool PR queue `enhancement` `risk: high` `channel` `integration` `provider` `tool` `priority:p2` `status:in-progress` `status:no-stale`

### 🔒 Closed Issues
- [#3090](https://github.com/zeroclaw-labs/zeroclaw/issues/3090) [Feature]: Wecom(WxWork) channel support

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,373 · **Open issues:** 1,052 · **Last push:** <1h ago

### ✅ Merged PRs
- [#4228](https://github.com/nearai/ironclaw/pull/4228) [codex] Port Notion MCP extension to Reborn
- [#4233](https://github.com/nearai/ironclaw/pull/4233) Migrate GitHub WASM credentials to product auth
- [#4244](https://github.com/nearai/ironclaw/pull/4244) Refine trigger loop and delivery resolution specs
- [#4231](https://github.com/nearai/ironclaw/pull/4231) Wire Reborn auth consumers through staged credentials
- [#4232](https://github.com/nearai/ironclaw/pull/4232) [codex] Verify auth gate blocked exits
- [#4234](https://github.com/nearai/ironclaw/pull/4234) feat (reborn) durable product auth 
- [#4223](https://github.com/nearai/ironclaw/pull/4223) [codex] Port NEAR AI MCP to Reborn extensions
- [#4243](https://github.com/nearai/ironclaw/pull/4243) fix(product-workflow): update RecordingFlowManager for mark_continuation_dispatched trait method
- [#4240](https://github.com/nearai/ironclaw/pull/4240) docs: add communication delivery resolution design
- [#3874](https://github.com/nearai/ironclaw/pull/3874) docs: add trigger loop design spec

### 🐛 New Issues
- [#4241](https://github.com/nearai/ironclaw/issues/4241) Live Workspace Prompt Inputs Invalidate KV Cache Reuse Across Conversation Turns
- [#4238](https://github.com/nearai/ironclaw/issues/4238) Project product-auth accounts into ironclaw_secrets::CredentialAccountStore (broker projection) 💬1
- [#4237](https://github.com/nearai/ironclaw/issues/4237) PR #4234: cargo test -p ironclaw_product_workflow fails to compile (durable product-auth trait/field additions)
- [#4226](https://github.com/nearai/ironclaw/issues/4226) Bound cleaned process handoff dedupe state
- [#4222](https://github.com/nearai/ironclaw/issues/4222) Zeroize injected HTTP credential material across network request carriers
- [#4204](https://github.com/nearai/ironclaw/issues/4204) WebChat v2 SSO: GitHub + NEAR providers + CLI OAuthRouterConfig wire-up (#4116 follow-up) `reborn` 💬1
- [#4112](https://github.com/nearai/ironclaw/issues/4112) Reborn GSuite: wire WebUI OAuth prompt and browser approval E2E `reborn`
- [#4108](https://github.com/nearai/ironclaw/issues/4108) Nightly E2E failed

### 🔒 Closed Issues
- [#4179](https://github.com/nearai/ironclaw/issues/4179) Carry v1 Google SSO into WebChat v2

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬4 · 12h ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬1 · 22h ago
- ⚫ [#86371](https://github.com/openclaw/openclaw/issues/86371) Bug: message tool filePath fails with LocalMediaAccessError in retry flows when agentId is not propagated — 💬1 · 1d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 4d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 13d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬2 · 14d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 17d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 4 new
- [[Form] Rosalind Biodefense Program](https://openai.com/form/rosalind-biodefense-program/) _2026-05-29_
- [[Index] Braintrust](https://openai.com/index/braintrust/) _2026-05-29_
- [[Index] Boston Childrens Hospital](https://openai.com/index/boston-childrens-hospital/) _2026-05-29_
- [[Index] Mufg](https://openai.com/index/mufg/) _2026-05-29_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
