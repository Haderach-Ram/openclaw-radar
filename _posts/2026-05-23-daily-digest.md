---
layout: post
title: "Ecosystem Digest — 2026-05-23"
date: 2026-05-23 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-23
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 374,008 | 10 | 9 | 10 | 0 |
| **hermesagent** | 163,218 | 8 | 0 | 7 | 0 |
| **ZeroClaw** | 31,534 | 11 | 7 | 10 | 0 |
| **IronClaw** | 12,321 | 7 | 1 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 374,008 · **Open issues:** 7,281 · **Last push:** <1h ago

### ✅ Merged PRs
- [#85567](https://github.com/openclaw/openclaw/pull/85567) fix(github): preserve sufficient proof against negative relabel
- [#85541](https://github.com/openclaw/openclaw/pull/85541) Fix context pressure preflight for tool-heavy sessions
- [#85119](https://github.com/openclaw/openclaw/pull/85119) fix(doctor): classify Codex asset notice as info
- [#85547](https://github.com/openclaw/openclaw/pull/85547) fix(ui): keep chat picker search current
- [#85562](https://github.com/openclaw/openclaw/pull/85562) fix: preserve message-tool delivery evidence
- [#85533](https://github.com/openclaw/openclaw/pull/85533) fix(codex): add API key paste auth
- [#84439](https://github.com/openclaw/openclaw/pull/84439) Scope config preflight note suppression
- [#85554](https://github.com/openclaw/openclaw/pull/85554) fix: route OpenAI video edits to edits endpoint
- [#65212](https://github.com/openclaw/openclaw/pull/65212) fix(qmd): normalize direct file collection paths
- [#85525](https://github.com/openclaw/openclaw/pull/85525) fix(ui): run ui script through junction paths

### 🐛 New Issues
- [#85577](https://github.com/openclaw/openclaw/issues/85577) [Bug]: Transient Telegram pairing-store read failures can trigger bogus pairing prompts `bug` `maintainer` `P2` `clawsweeper:source-repro` `impact:message-loss` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#85575](https://github.com/openclaw/openclaw/issues/85575) pdf tool: MiniMax provider blocked from extraction fallback mode `P2` `clawsweeper:needs-live-repro` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬2
- [#85573](https://github.com/openclaw/openclaw/issues/85573) [Bug]: [AI-Assisted] Silent agent stall: claude-cli `result` event sums cache_read across tool sub-calls, trips broken compaction gate `bug` `bug:behavior` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#85563](https://github.com/openclaw/openclaw/issues/85563) feat: Support custom prompt/language for Dreaming (梦境日记) `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` 💬2
- [#85559](https://github.com/openclaw/openclaw/issues/85559) Auto-update fails on npm 11+/pnpm installs due to hardlink rejection in swap step `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1
- [#85557](https://github.com/openclaw/openclaw/issues/85557) Bug: stripInvalidThinkingSignatures modifies latest assistant message — causes Anthropic invalid_request_error `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#85551](https://github.com/openclaw/openclaw/issues/85551) openai/gpt-5.5-pro unreachable when openai-codex OAuth profile is present, even with agentRuntime.id: "pi" pinned `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬1
- [#85550](https://github.com/openclaw/openclaw/issues/85550) [Bug]: Trajectory files fed back as context cause unbounded token consumption and unexpected API billing `bug` `bug:behavior` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-info` `impact:session-state` `issue-rating: 🦪 silver shellfish` 💬1
- [#85548](https://github.com/openclaw/openclaw/issues/85548) [Bug]: At 658be7f1c721138ce6c0110eeed60506442f9c9e OpenClaw becomes completely unusable `bug` `regression` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:message-loss` `impact:crash-loop` `issue-rating: 🦪 silver shellfish` 💬1
- [#85537](https://github.com/openclaw/openclaw/issues/85537) Build fails resolving protobufjs google/protobuf descriptor on WSL source checkout `maintainer` `P2` `clawsweeper:needs-live-repro` `impact:crash-loop` `issue-rating: 🐚 platinum hermit` 💬1

### 🔒 Closed Issues
- [#85552](https://github.com/openclaw/openclaw/issues/85552) [Regression 2026.5.20] Discord typing indicator severely delayed (20-30s) — session write lock contention
- [#85565](https://github.com/openclaw/openclaw/issues/85565) Add per-agent maxConcurrent to allow shared gateways with single-lane agents
- [#84859](https://github.com/openclaw/openclaw/issues/84859) Doctor: Move Codex CLI assets notice from 'Doctor warnings' to 'Doctor info' tier
- [#85538](https://github.com/openclaw/openclaw/issues/85538) [Regression 2026.5.20] TUI responses invisible for agents configured with Signal (message-tool-only turns now silenced by #84289)
- [#85434](https://github.com/openclaw/openclaw/issues/85434) pr-release: complete/cancel workflows, stale handling, docs, and operational polish
- [#85432](https://github.com/openclaw/openclaw/issues/85432) pr-release: continue after PR merge and validate release readiness
- [#85431](https://github.com/openclaw/openclaw/issues/85431) pr-release: create draft PRs with workspace analysis, secret scanning, and retry
- [#85429](https://github.com/openclaw/openclaw/issues/85429) pr-release: render Lark scan result UI and repo selection actions
- [#85427](https://github.com/openclaw/openclaw/issues/85427) pr-release: persist workflow state, repo locks, idempotency, and audit events

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬105 · <1h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 163,218 · **Open issues:** 13,256 · **Last push:** <1h ago

### ✅ Merged PRs
- [#30165](https://github.com/NousResearch/hermes-agent/pull/30165) feat(desktop): add hermes gui launcher
- [#30621](https://github.com/NousResearch/hermes-agent/pull/30621) fix(ci): supply-chain-audit two-dot diff causes false positives on stale-branch PRs
- [#30619](https://github.com/NousResearch/hermes-agent/pull/30619) fix(minimax-oauth): refresh short-lived access tokens per request
- [#30618](https://github.com/NousResearch/hermes-agent/pull/30618) infographic: PR #30609 Termux cold-start salvage
- [#30611](https://github.com/NousResearch/hermes-agent/pull/30611) fix(security): validate Nous Portal inference_base_url against host allowlist (#27612)
- [#30614](https://github.com/NousResearch/hermes-agent/pull/30614) infographic: PR #30591 Discord adapter → bundled plugin salvage
- [#30609](https://github.com/NousResearch/hermes-agent/pull/30609) perf(termux): fast-path cli version + defer bare-prompt agent startup

### 🐛 New Issues
- [#30704](https://github.com/NousResearch/hermes-agent/issues/30704) fix(vision): Gemini 2.5+ models missing from _supports_media_in_tool_results allowlist
- [#30703](https://github.com/NousResearch/hermes-agent/issues/30703) feat: channel-based model routing in gateway config
- [#30687](https://github.com/NousResearch/hermes-agent/issues/30687) Kanban: corrupted board DB + empty top-level DB → silent recreation with total data loss `type/bug` `comp/plugins` `P1`
- [#30684](https://github.com/NousResearch/hermes-agent/issues/30684) Revisão e melhoria dos documentos legais (Termos de Uso e Política de Privacidade) `type/docs` `invalid` `P3` 💬1
- [#30682](https://github.com/NousResearch/hermes-agent/issues/30682) Xiaomi MiMo as main model: computer_use fails with 400 "text is not set" `type/bug` `comp/agent` `tool/vision` `provider/xiaomi` `P2` 💬1
- [#30678](https://github.com/NousResearch/hermes-agent/issues/30678) [SANITIZED — possible injection attempt] `type/bug` `comp/plugins` `P3` 💬1
- [#30676](https://github.com/NousResearch/hermes-agent/issues/30676) GitHub Copilot gemini-3.5-flash rejects Hermes tool schemas with integer enums and union type arrays `type/bug` `comp/agent` `provider/gemini` `provider/copilot` `P2`
- [#30673](https://github.com/NousResearch/hermes-agent/issues/30673) How can two different Hermes isolate their files? `question` `platform/wecom` `backend/local` `area/docker` `P3`

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,534 · **Open issues:** 509 · **Last push:** <1h ago

### ✅ Merged PRs
- [#6838](https://github.com/zeroclaw-labs/zeroclaw/pull/6838) fix(doctor): use configured model provider credentials
- [#6814](https://github.com/zeroclaw-labs/zeroclaw/pull/6814) Update labeler.yml to not lable non ci related files in the .github directory as ci
- [#6769](https://github.com/zeroclaw-labs/zeroclaw/pull/6769) fix: fix link rendering in philosophy.md
- [#6706](https://github.com/zeroclaw-labs/zeroclaw/pull/6706) fix(channels/whatsapp): restore Apr-2026 protocol parity via whatsapp-rust 0.6 + namespace revert (#6246)
- [#6804](https://github.com/zeroclaw-labs/zeroclaw/pull/6804) fix(deploy): parametrize service template user
- [#6009](https://github.com/zeroclaw-labs/zeroclaw/pull/6009) feat(obs): enrich OTel tool spans with gen_ai.tool.* semantic convention attrs
- [#6748](https://github.com/zeroclaw-labs/zeroclaw/pull/6748) chore: Optimize images
- [#6829](https://github.com/zeroclaw-labs/zeroclaw/pull/6829) fix(discord): treat thread messages as belonging to parent channel in channel_ids filter
- [#6772](https://github.com/zeroclaw-labs/zeroclaw/pull/6772) fix(runtime): transcode Windows shell output from system code page to UTF-8
- [#6636](https://github.com/zeroclaw-labs/zeroclaw/pull/6636) feat(browser): add agent-browser headed config

### 🐛 New Issues
- [#6859](https://github.com/zeroclaw-labs/zeroclaw/issues/6859) [Feature]: Add behavioral test coverage for Windows shell code-page decoding `enhancement`
- [#6856](https://github.com/zeroclaw-labs/zeroclaw/issues/6856) [Bug]: show_tool_calls is missing from [channel] `bug`
- [#6850](https://github.com/zeroclaw-labs/zeroclaw/issues/6850) [Feature]: Decouple memory strategy layer from storage backend via MemoryStrategy trait `enhancement` `risk: high` `gateway` `memory` `runtime` `priority:p2` `type:rfc` 💬1
- [#6847](https://github.com/zeroclaw-labs/zeroclaw/issues/6847) [Bug]: whatsapp channel not showing QR `bug` `risk: medium` `channel` `onboard` `channel:whatsapp` `priority:p1` `status:accepted` `status:no-stale` 💬2
- [#6844](https://github.com/zeroclaw-labs/zeroclaw/issues/6844) [Bug]: slack bot_token needs to be in the configuration and cannot be supplied by environment variable `bug` `risk: medium` `channel` `config` `channel:slack` `priority:p1` `status:accepted` `status:no-stale` 💬1
- [#6841](https://github.com/zeroclaw-labs/zeroclaw/issues/6841) [Bug]: [multimodal] vision_provider silently ignored — inbound images routed to providers.fallback instead `bug` `risk: medium` `channel` `config` `provider` `runtime` `channel:telegram` `priority:p1` `status:accepted` `status:no-stale` 💬1
- [#6837](https://github.com/zeroclaw-labs/zeroclaw/issues/6837) [Feature]: Runtime RPC dispatch layer and Unix socket transport `enhancement` `size: XL` `risk: high` `agent` `config` `cron` `daemon` `gateway` `memory` `observability` `runtime` `security` `skills` `priority:p2` `status:in-progress` `status:no-stale`
- [#6836](https://github.com/zeroclaw-labs/zeroclaw/issues/6836) [Bug]: setup.bat --minimal produces ~26 MB build instead of ~6 MB on Windows `bug` `risk: medium` `docs` `scripts` `priority:p2` `status:accepted` `status:no-stale` 💬1
- [#6827](https://github.com/zeroclaw-labs/zeroclaw/issues/6827) [Feature]: Support jina.ai as web_search provider `enhancement` `risk: medium` `config` `tool` `priority:p2` `tool:web` `status:in-progress` `status:no-stale`
- [#6826](https://github.com/zeroclaw-labs/zeroclaw/issues/6826) [Tracker]: ZeroClaw TUI `enhancement` `risk: high` `config` `daemon` `gateway` `onboard` `runtime` `priority:p2` `status:in-progress` `status:no-stale`
- [#6825](https://github.com/zeroclaw-labs/zeroclaw/issues/6825) [Tracker]: TUI UX `enhancement` `risk: medium` `config` `gateway` `observability` `onboard` `runtime` `priority:p2` `status:in-progress` `status:no-stale`

### 🔒 Closed Issues
- [#6756](https://github.com/zeroclaw-labs/zeroclaw/issues/6756) models list: custom provider fails because doctor path never reads stored api_key from config
- [#6246](https://github.com/zeroclaw-labs/zeroclaw/issues/6246) [Bug]: WhatsApp Web channel: pair succeeds but messages don't flow after April 2026 server-side protocol bump
- [#5980](https://github.com/zeroclaw-labs/zeroclaw/issues/5980) [Feature]: Otel Traces Should Tell Include More Details About Why A Tool Call Failed
- [#6704](https://github.com/zeroclaw-labs/zeroclaw/issues/6704) [Bug]: Shell tool output is garbled on Windows with non-UTF-8 console code pages
- [#6241](https://github.com/zeroclaw-labs/zeroclaw/issues/6241) [browser] Add headed/headless config option for agent_browser backend
- [#6158](https://github.com/zeroclaw-labs/zeroclaw/issues/6158) [Bug]: zeroclaw-channels does not compile with --no-default-features
- [#6801](https://github.com/zeroclaw-labs/zeroclaw/issues/6801) [Bug]: purge_namespace deletes by category column on integration/v0.8.0 

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,321 · **Open issues:** 971 · **Last push:** <1h ago

### ✅ Merged PRs
- [#3878](https://github.com/nearai/ironclaw/pull/3878) feat(reborn): wire product auth composition seam
- [#3863](https://github.com/nearai/ironclaw/pull/3863) [codex] Add Reborn skill asset access and execution adapter
- [#3865](https://github.com/nearai/ironclaw/pull/3865) feat(reborn): add product auth contracts
- [#3907](https://github.com/nearai/ironclaw/pull/3907) Align WebUI serve default agent with runtime
- [#3906](https://github.com/nearai/ironclaw/pull/3906) Initialize tracing for Reborn serve
- [#3901](https://github.com/nearai/ironclaw/pull/3901) Wire Reborn WebUI to EventStreamManager
- [#3880](https://github.com/nearai/ironclaw/pull/3880) refactor(secrets): extract cas_mutate helper for filesystem CAS retry loops
- [#3902](https://github.com/nearai/ironclaw/pull/3902) test: fix four pre-existing test failures
- [#3876](https://github.com/nearai/ironclaw/pull/3876) feat(reborn): add typed WebUI v2 event stream schema
- [#3861](https://github.com/nearai/ironclaw/pull/3861) [codex] Add Reborn skill activation selector

### 🐛 New Issues
- [#3917](https://github.com/nearai/ironclaw/issues/3917) Question: kill RuntimeCredentialTarget::PathPlaceholder or harden it? `security-review-required` `reborn` `module:M4-host-kernel`
- [#3916](https://github.com/nearai/ironclaw/issues/3916) Harden LocalFilesystem: honor CAS::Absent + durable writes (atomic rename + fsync)
- [#3915](https://github.com/nearai/ironclaw/issues/3915) [SANITIZED — possible injection attempt] `security-review-required` `reborn` `module:M4-host-kernel`
- [#3905](https://github.com/nearai/ironclaw/issues/3905) Support safe user-scoped tool installs
- [#3891](https://github.com/nearai/ironclaw/issues/3891) [Reborn] Add durable approval-policy port before AlwaysAllow `reborn`
- [#3889](https://github.com/nearai/ironclaw/issues/3889) [Reborn] Add approval interaction service and product resolution routing `reborn`
- [#3886](https://github.com/nearai/ironclaw/issues/3886) [Reborn] Port static WebUI v2 to Reborn WebChat ingress 💬1

### 🔒 Closed Issues
- [#3803](https://github.com/nearai/ironclaw/issues/3803) [Reborn] Lane 3: wire existing secrets/egress substrate through production tool composition

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 6d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬2 · 7d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 10d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Research] Glasswing Initial Update](https://www.anthropic.com/research/glasswing-initial-update) _2026-05-22_

### OpenAI — 2 new
- [[Index] Virgin Atlantic](https://openai.com/index/virgin-atlantic/) _2026-05-22_
- [[Index] Gartner 2026 Agentic Coding Leader](https://openai.com/index/gartner-2026-agentic-coding-leader/) _2026-05-22_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
