---
layout: post
title: "Ecosystem Digest — 2026-05-27"
date: 2026-05-27 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-27
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 374,898 | 8 | 7 | 10 | 2 |
| **hermesagent** | 168,813 | 3 | 3 | 2 | 0 |
| **ZeroClaw** | 31,601 | 6 | 0 | 1 | 0 |
| **IronClaw** | 12,352 | 9 | 0 | 10 | 1 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 374,898 · **Open issues:** 6,905 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.26-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.5.26-beta.1) — openclaw 2026.5.26-beta.1
- [v2026.5.25-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.5.25-beta.1) — openclaw 2026.5.25-beta.1

### ✅ Merged PRs
- [#78526](https://github.com/openclaw/openclaw/pull/78526) fix(browser): validate current tab before snapshots
- [#87000](https://github.com/openclaw/openclaw/pull/87000) fix(onboard): preserve configured default model
- [#81225](https://github.com/openclaw/openclaw/pull/81225) fix(telegram): route plugin-bound topic messages
- [#87028](https://github.com/openclaw/openclaw/pull/87028) fix(diagnostics): recover orphaned session activity and yield event loop during lock contention
- [#87101](https://github.com/openclaw/openclaw/pull/87101) fix(media): resolve inbound media refs consistently
- [#87049](https://github.com/openclaw/openclaw/pull/87049) fix(ollama): normalize greedy top_p
- [#83741](https://github.com/openclaw/openclaw/pull/83741) clickclack: enforce inbound sender allowlist [AI]
- [#86956](https://github.com/openclaw/openclaw/pull/86956) refactor: centralize user turn transcript persistence
- [#86455](https://github.com/openclaw/openclaw/pull/86455) fix(agents): release yield abort session lock
- [#87062](https://github.com/openclaw/openclaw/pull/87062) fix(filefetch): wrap fetched text as external content

### 🐛 New Issues
- [#87117](https://github.com/openclaw/openclaw/issues/87117) Abort settle timeout causes zombie session write lock cascade 💬1
- [#87110](https://github.com/openclaw/openclaw/issues/87110) When calling a VLLM model, the usage page statistics show no data. How can I calculate usage and cost when using VLLM? `bug` `regression` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-info` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#87109](https://github.com/openclaw/openclaw/issues/87109) [Bug]: Gateway heap grows to 1073MB+ at idle on macOS, cron jobs fail silently under memory pressure (ref #86613, #86509) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `impact:crash-loop` `issue-rating: 🐚 platinum hermit` 💬1
- [#87107](https://github.com/openclaw/openclaw/issues/87107) /compact command reply silently dropped after upgrade to 2026.5.22 (delivered=true but no actual delivery) `P1` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬1
- [#87099](https://github.com/openclaw/openclaw/issues/87099) [Bug]:  Pi + Codex OAuth route mismatch and encrypted-reasoning retries on GPT-5.5 `bug` `bug:behavior` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#87095](https://github.com/openclaw/openclaw/issues/87095) Dreaming short-term-recall.json grows unbounded — overflows context at /new 💬1
- [#87089](https://github.com/openclaw/openclaw/issues/87089) [Bug]: iMessage remote attachment staged after media understanding — image tool sees raw Mac path before SCP fetch `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#87082](https://github.com/openclaw/openclaw/issues/87082) bug(plugin-sdk): normalizeDiagnosticEventsModule hardcodes stale minified export alias `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:linked-pr-open` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` 💬1

### 🔒 Closed Issues
- [#87116](https://github.com/openclaw/openclaw/issues/87116) [Bug]: Google Generative AI API 404 - gemini-3.1-flash-lite-preview model is no longer available
- [#87024](https://github.com/openclaw/openclaw/issues/87024) Telegram inbound images downloaded to ~/.openclaw/media/inbound/, but media://inbound refs were not resolved consistently across image-loading paths
- [#87114](https://github.com/openclaw/openclaw/issues/87114) [SANITIZED — possible injection attempt]
- [#81249](https://github.com/openclaw/openclaw/issues/81249) [Feature/Bug]: Local Ollama embeddings fail when proxy is enabled (SSRF defenses ignore NO_PROXY)
- [#75720](https://github.com/openclaw/openclaw/issues/75720) [Bug]: Auto-onboard / plugin presets unconditionally overwrite user-set agents.defaults.model.primary
- [#87106](https://github.com/openclaw/openclaw/issues/87106) [feishu] bitable extension: missing dashboard, workflow, table management and embedded docx (ldx) support
- [#85953](https://github.com/openclaw/openclaw/issues/85953) Bug: sessions_yield can leave parent session transcript lock held, causing subagent completion callback timeout

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 22h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 168,813 · **Open issues:** 14,200 · **Last push:** 3h ago

### ✅ Merged PRs
- [#32859](https://github.com/NousResearch/hermes-agent/pull/32859) docs(auth): replace stale 'hermes login' references with 'hermes auth add'
- [#32815](https://github.com/NousResearch/hermes-agent/pull/32815) fix(gateway): refresh cached agent tools on /reload-mcp

### 🐛 New Issues
- [#32943](https://github.com/NousResearch/hermes-agent/issues/32943) [Feature]: Multi-profile Telegram group communication — bots don't see each other's messages `type/feature` `comp/gateway` `platform/telegram` `P3`
- [#32932](https://github.com/NousResearch/hermes-agent/issues/32932) [Bug] Gateway systemd service fails on Fedora with SELinux enforcing (status 203/EXEC) `type/bug` `comp/gateway` `area/config` `P2`
- [#32925](https://github.com/NousResearch/hermes-agent/issues/32925) Feature Request: Integrate Microsoft SkillOpt for Self-Evolving Agent Skills `type/feature` `innovation` `tool/skills` `P3`

### 🔒 Closed Issues
- [#5678](https://github.com/NousResearch/hermes-agent/issues/5678) [Bug]: openai-codex provider fails with 'Responses API returned no output items' when output[] is empty but streaming delivered text (gpt-5.4)
- [#29125](https://github.com/NousResearch/hermes-agent/issues/29125) [Bug]: Hermes does not work through Claude CLI
- [#13891](https://github.com/NousResearch/hermes-agent/issues/13891) [Bug]: Matrix gateway unable to decrypt message

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,601 · **Open issues:** 528 · **Last push:** 2h ago

### ✅ Merged PRs
- [#6942](https://github.com/zeroclaw-labs/zeroclaw/pull/6942) fix(web): tighten Canvas iframe sandbox to prevent token theft via XSS (GHSA-f385-f6h2-3gqj)

### 🐛 New Issues
- [#6954](https://github.com/zeroclaw-labs/zeroclaw/issues/6954) RFC: Route scheduled tasks through the orchestrator message pipeline
- [#6950](https://github.com/zeroclaw-labs/zeroclaw/issues/6950) fix(tui): add Alt+1–5 keybindings for compact keyboards without F-keys `bug` `core`
- [#6944](https://github.com/zeroclaw-labs/zeroclaw/issues/6944) [SANITIZED — possible injection attempt]
- [#6943](https://github.com/zeroclaw-labs/zeroclaw/issues/6943) [RFC]: Deconflict Plugin System Goals in FND-001 `enhancement`
- [#6937](https://github.com/zeroclaw-labs/zeroclaw/issues/6937) docs(api): document attachment path validation boundary `enhancement` `risk: medium` `channel` `channel:email`
- [#6909](https://github.com/zeroclaw-labs/zeroclaw/issues/6909) [Feature]: computer-use support (screen interaction like Codex / Peekaboo) `enhancement` `risk: high` `runtime` `security` `tool` `tool:browser` `priority:p2` `type:rfc` `status:accepted` 💬3

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,352 · **Open issues:** 1,021 · **Last push:** <1h ago

### 🚀 New Releases
- [ironclaw-v0.29.0](https://github.com/nearai/ironclaw/releases/tag/ironclaw-v0.29.0) — 0.29.0 - 2026-05-26

### ✅ Merged PRs
- [#4103](https://github.com/nearai/ironclaw/pull/4103) Enable save_to for Reborn builtin HTTP
- [#4099](https://github.com/nearai/ironclaw/pull/4099) [codex] Add Reborn extension lifecycle CLI
- [#4095](https://github.com/nearai/ironclaw/pull/4095) Wire Reborn CLI skills list
- [#4071](https://github.com/nearai/ironclaw/pull/4071) [codex] Add Reborn HTTP response body saving
- [#4079](https://github.com/nearai/ironclaw/pull/4079) [codex] Use shared LLM config resolution for Reborn
- [#4061](https://github.com/nearai/ironclaw/pull/4061) feat: webui v2 static port
- [#4098](https://github.com/nearai/ironclaw/pull/4098) [codex] Unify Reborn skill install URL path
- [#4096](https://github.com/nearai/ironclaw/pull/4096) docs(reborn): add context compaction design spec
- [#4073](https://github.com/nearai/ironclaw/pull/4073) [codex] Persist durable tool previews
- [#4064](https://github.com/nearai/ironclaw/pull/4064) Install GitHub WASM extension through Reborn lifecycle

### 🐛 New Issues
- [#4102](https://github.com/nearai/ironclaw/issues/4102) feat: trait-level grant expiry enforcement + binding-store tenant-scoping (attested-signing durable-store follow-ups) `reborn` 💬1
- [#4092](https://github.com/nearai/ironclaw/issues/4092) feat: non-consuming background-subagent result poll + durable parent/child index (follow-up to #4084 Gap 2) `reborn`
- [#4091](https://github.com/nearai/ironclaw/issues/4091) Track production and multi-tenant extension lifecycle wiring
- [#4088](https://github.com/nearai/ironclaw/issues/4088) Track decomposition of oversized Reborn integration files
- [#4086](https://github.com/nearai/ironclaw/issues/4086) feat: add coder/explorer/planner subagent flavors + fix flavor_id schema surface
- [#4085](https://github.com/nearai/ironclaw/issues/4085) [Reborn] Production host-runtime builders don't wire TenantSandboxProcessPort — perma-failing composition tests mask CI signal `reborn` 💬1
- [#4084](https://github.com/nearai/ironclaw/issues/4084) fix: background subagent results never delivered to parent `bug`
- [#4082](https://github.com/nearai/ironclaw/issues/4082) [Security] Stop unwrapping SecretString into String on the credential path
- [#4081](https://github.com/nearai/ironclaw/issues/4081) [Security] Signer approval gate should not be Optional

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 1d ago
- ⚫ [#86371](https://github.com/openclaw/openclaw/issues/86371) Bug: message tool filePath fails with LocalMediaAccessError in retry flows when agentId is not propagated — 💬1 · 1d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 10d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬2 · 11d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 14d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 2 new
- [[Engineering] How We Contain Claude](https://www.anthropic.com/engineering/how-we-contain-claude) _2026-05-26_
- [[News] Kiyoung Choi Representative Director Anthropic Korea](https://www.anthropic.com/news/kiyoung-choi-representative-director-anthropic-korea) _2026-05-26_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
