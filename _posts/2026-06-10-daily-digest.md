---
layout: post
title: "Ecosystem Digest — 2026-06-10"
date: 2026-06-10 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-10
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 377,834 | 13 | 6 | 10 | 2 |
| **hermesagent** | 188,905 | 8 | 1 | 10 | 0 |
| **ZeroClaw** | 31,847 | 8 | 2 | 10 | 0 |
| **IronClaw** | 12,437 | 9 | 3 | 9 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 377,834 · **Open issues:** 7,989 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.5](https://github.com/openclaw/openclaw/releases/tag/v2026.6.5) — openclaw 2026.6.5
- [v2026.6.5-beta.6](https://github.com/openclaw/openclaw/releases/tag/v2026.6.5-beta.6) — openclaw 2026.6.5-beta.6

### ✅ Merged PRs
- [#91785](https://github.com/openclaw/openclaw/pull/91785) fix(imessage): surface inbound startup diagnostics
- [#91783](https://github.com/openclaw/openclaw/pull/91783) fix(imessage): harden outbound send transport
- [#91787](https://github.com/openclaw/openclaw/pull/91787) fix(doctor): keep TTS legacy migration on supported paths
- [#91757](https://github.com/openclaw/openclaw/pull/91757) fix(config): clarify retired skill workshop plugin warning
- [#91750](https://github.com/openclaw/openclaw/pull/91750) fix(search): enforce native web search tool policy
- [#91780](https://github.com/openclaw/openclaw/pull/91780) fix(ui): drain restored chat queue after session switch
- [#88530](https://github.com/openclaw/openclaw/pull/88530) fix(imessage): skip idle approval discovery scans
- [#91741](https://github.com/openclaw/openclaw/pull/91741) Validate sandbox bind parent paths [AI]
- [#91773](https://github.com/openclaw/openclaw/pull/91773) fix(mcp): lowercase SSE event-source header keys to prevent duplicate Authorization (401)
- [#91777](https://github.com/openclaw/openclaw/pull/91777) docs: remove superpowers spec draft

### 🐛 New Issues
- [#91809](https://github.com/openclaw/openclaw/issues/91809) [Performance] /models command slow in v2026.6.1 — catalog loading regression `bug` 💬1
- [#91808](https://github.com/openclaw/openclaw/issues/91808) [Feature]: Update CODEOWNERS to reflect documented maintainer area ownership `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:other` 💬2
- [#91806](https://github.com/openclaw/openclaw/issues/91806) [Bug]: Session shows openai/gpt-5.5 in UI, but new turns execute via DeepSeek and chat history collapses into new leaf sessions `bug` `regression` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬1
- [#91805](https://github.com/openclaw/openclaw/issues/91805) Support Anthropic adaptive thinking API for Claude Fable 5 💬1
- [#91804](https://github.com/openclaw/openclaw/issues/91804) [Bug]: Internal Reasoning Leakage in 2026.6.5 `bug` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#91799](https://github.com/openclaw/openclaw/issues/91799) [Bug]: Discord Agents cannot access MCP tools (works via CLI) `bug` `bug:behavior` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#91795](https://github.com/openclaw/openclaw/issues/91795) Expose running version on /healthz (or /version) for multi-tenant operators `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#91788](https://github.com/openclaw/openclaw/issues/91788) feat(agents): opt-in config to re-enable the message tool for spawned subagent sessions `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#91781](https://github.com/openclaw/openclaw/issues/91781) [Bug]: Android node advertises SMS permission but sms.search remains disallowed `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1
- [#91778](https://github.com/openclaw/openclaw/issues/91778) [P0] memory_search cassé — index metadata is missing depuis v2026.6.1, reproduit sur v2026.6.5 `P1` `clawsweeper:needs-live-repro` `impact:session-state` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬1
- [#91775](https://github.com/openclaw/openclaw/issues/91775) One-shot `at` cron jobs are disabled before execution, always skipped as "disabled" `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#91774](https://github.com/openclaw/openclaw/issues/91774) [Bug]: Codex native exec does not honor OpenClaw notifyOnExit/notifyOnExitEmptySuccess completion wake semantics 💬1
- [#91772](https://github.com/openclaw/openclaw/issues/91772) [SANITIZED — possible injection attempt] `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1

### 🔒 Closed Issues
- [#84329](https://github.com/openclaw/openclaw/issues/84329) iMessage outbound sends should prefer configurable IMCore transport when available
- [#91793](https://github.com/openclaw/openclaw/issues/91793) CLI native harness compaction misclassifies benign Codex automatic-compaction skip as fatal
- [#91792](https://github.com/openclaw/openclaw/issues/91792) `configure --section channels` fails for Telegram with stale `requireMention` validation error in 2026.6.5-beta.7
- [#91789](https://github.com/openclaw/openclaw/issues/91789) (withdrawn)
- [#91779](https://github.com/openclaw/openclaw/issues/91779) [Bug]: cron list omits enabled jobs — list count < status count
- [#90092](https://github.com/openclaw/openclaw/issues/90092) Thank you: v2026.6.1 dashboard chat controls are much more accessible with VoiceOver

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 14d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 188,905 · **Open issues:** 20,062 · **Last push:** <1h ago

### ✅ Merged PRs
- [#43214](https://github.com/NousResearch/hermes-agent/pull/43214) [SANITIZED — possible injection attempt]
- [#43219](https://github.com/NousResearch/hermes-agent/pull/43219) feat(desktop): open any chat in its own window
- [#42856](https://github.com/NousResearch/hermes-agent/pull/42856) docs(windows): correct native data dir to %LOCALAPPDATA%\hermes
- [#43188](https://github.com/NousResearch/hermes-agent/pull/43188) feat(tui): include session name in the terminal titlebar
- [#43197](https://github.com/NousResearch/hermes-agent/pull/43197) fix(desktop): scope thinking disclosure pending state
- [#43111](https://github.com/NousResearch/hermes-agent/pull/43111) feat(desktop): Mac-style session switcher (^Tab / ^⇧Tab / ^1-9)
- [#43147](https://github.com/NousResearch/hermes-agent/pull/43147) fix(desktop): sidebar sections never overlap — two-mode CSS scroll + collapse/cap groups
- [#42733](https://github.com/NousResearch/hermes-agent/pull/42733) fix(terminal): lazy-parse Docker env config
- [#39639](https://github.com/NousResearch/hermes-agent/pull/39639) fix(desktop): send on Enter from live editor text, not stale composer state
- [#40892](https://github.com/NousResearch/hermes-agent/pull/40892) fix(tui_gateway): honor target profile's terminal.cwd on desktop profile switch

### 🐛 New Issues
- [#43228](https://github.com/NousResearch/hermes-agent/issues/43228) Footer model name polluted by auxiliary channel calls (vision/compression/title-gen etc.)
- [#43225](https://github.com/NousResearch/hermes-agent/issues/43225) Feature Request: System notification (toast) when agent response is ready
- [#43224](https://github.com/NousResearch/hermes-agent/issues/43224) Feature Request: Minimize-to-tray compact chat popup (like Codex)
- [#43220](https://github.com/NousResearch/hermes-agent/issues/43220) [Feature]: make every python work with hermes agent
- [#43216](https://github.com/NousResearch/hermes-agent/issues/43216) Kanban dashboard: inline 'Reply & unblock' for blocked tasks `type/feature` `comp/plugins` `P3`
- [#43211](https://github.com/NousResearch/hermes-agent/issues/43211) Stale stream errors silently retry on same provider instead of triggering runtime fallback `type/bug` `comp/agent` `P2`
- [#43201](https://github.com/NousResearch/hermes-agent/issues/43201) [Feature]: Suggestion: When the pre_tool_call hook returns a block result, support terminating the current agent loop to prevent the LLM from attempting other tools continuously. `type/feature` `comp/plugins` `P3`
- [#43196](https://github.com/NousResearch/hermes-agent/issues/43196) Dashboard wedges (SIGKILL required) when hosted as a persistent service: two bugs in the PTY/Chat tab path `type/bug` `comp/cli` `P3`

### 🔒 Closed Issues
- [#42725](https://github.com/NousResearch/hermes-agent/issues/42725) [Bug]: TERMINAL_DOCKER_VOLUMES parsed eagerly with json.loads regardless of terminal.backend, crashes all subprocess tools

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,847 · **Open issues:** 502 · **Last push:** 11h ago

### ✅ Merged PRs
- [#7425](https://github.com/zeroclaw-labs/zeroclaw/pull/7425) fix(runtime): resolve channel pricing via bare-type fallback in cost lookup
- [#7383](https://github.com/zeroclaw-labs/zeroclaw/pull/7383) fix(ci): add missing file and shell tool labeler paths
- [#7407](https://github.com/zeroclaw-labs/zeroclaw/pull/7407) fix(runtime): require configured model switch profiles
- [#6905](https://github.com/zeroclaw-labs/zeroclaw/pull/6905) fix(channels): keep runtime reload defaults context-scoped
- [#7405](https://github.com/zeroclaw-labs/zeroclaw/pull/7405) docs(maintainers): define tracker stale exemptions
- [#7060](https://github.com/zeroclaw-labs/zeroclaw/pull/7060) feat(wasi): define WIT interface files for Tool, Channel, and Memory plugins (FND-001 §5.2)
- [#7235](https://github.com/zeroclaw-labs/zeroclaw/pull/7235) feat(web): plugin lifecycle endpoints + management UI (stubs)
- [#7411](https://github.com/zeroclaw-labs/zeroclaw/pull/7411) refactor(api): move HookHandler trait and HookResult to zeroclaw-api
- [#7404](https://github.com/zeroclaw-labs/zeroclaw/pull/7404) fix(channels): prevent Matrix /sync from timing out at exactly 30 seconds
- [#7396](https://github.com/zeroclaw-labs/zeroclaw/pull/7396) docs(readme): update project banner

### 🐛 New Issues
- [#7439](https://github.com/zeroclaw-labs/zeroclaw/issues/7439) [Bug]: Custom provider results in Doctor error model_provider "custom.<alias>" is invalid `bug`
- [#7436](https://github.com/zeroclaw-labs/zeroclaw/issues/7436) [Bug]: image_info tool output does not reach multimodal/vision models in common cases
- [#7432](https://github.com/zeroclaw-labs/zeroclaw/issues/7432) [Tracker]: v0.9.0 auth, security, gateway, and breaking-change queue `enhancement` `risk: high` `config` `gateway` `runtime` `security` `domain:security` `domain:architecture` `priority:p2` `status:accepted`
- [#7431](https://github.com/zeroclaw-labs/zeroclaw/issues/7431) [Feature]: Pre-turn routing intent extraction
- [#7421](https://github.com/zeroclaw-labs/zeroclaw/issues/7421) [Bug]: Postgres memory backend fails to initiailize `bug` `risk: high` `memory` `runtime` `priority:p1` `status:accepted` `memory:postgres`
- [#7420](https://github.com/zeroclaw-labs/zeroclaw/issues/7420) RFC: Native Dynamic-Library Plugin System `enhancement` `risk: high` `core` `runtime` `security` `tool` `domain:architecture` `priority:p2` `needs-maintainer-review` `type:rfc`
- [#7415](https://github.com/zeroclaw-labs/zeroclaw/issues/7415) RFC: Unify the three agent turn engines (run_tool_call_loop + turn_streamed + Agent::turn) `enhancement` `risk: high` `agent` `channel` `gateway` `runtime` `tool` `domain:architecture` `priority:p2` `needs-maintainer-review` `type:rfc` 💬1
- [#7412](https://github.com/zeroclaw-labs/zeroclaw/issues/7412) [Bug]: web_fetch/http_request `allowed_private_hosts = ["*"]` does not cover domain names that resolve to private IPs `bug` `risk: high` `config` `security` `tool` `priority:p2` `tool:web` `status:in-progress` `status:accepted`

### 🔒 Closed Issues
- [#4710](https://github.com/zeroclaw-labs/zeroclaw/issues/4710) [Feature]: A better LOGO of Zeroclaw
- [#7117](https://github.com/zeroclaw-labs/zeroclaw/issues/7117) [Feature]: Config UX parity across CLI, Quickstart, zerocode (incl. navigation), and web surfaces

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,437 · **Open issues:** 1,117 · **Last push:** <1h ago

### ✅ Merged PRs
- [#4669](https://github.com/nearai/ironclaw/pull/4669) Add thermo-nuclear code quality review skill
- [#4645](https://github.com/nearai/ironclaw/pull/4645) Make Reborn production runtime launchable
- [#4582](https://github.com/nearai/ironclaw/pull/4582) docs(reborn): WU-B subagent durability sub-spec
- [#4651](https://github.com/nearai/ironclaw/pull/4651) [codex] Handle Reborn Railway start command placeholders
- [#4631](https://github.com/nearai/ironclaw/pull/4631) Reborn: wire production Postgres storage config
- [#4605](https://github.com/nearai/ironclaw/pull/4605) Setup reborn webui v2 playwright E2E smoke test
- [#4614](https://github.com/nearai/ironclaw/pull/4614) Add webchat v2 authentication parity audit and route tests
- [#4599](https://github.com/nearai/ironclaw/pull/4599) [codex] Add Reborn operator command-plane route shells
- [#4637](https://github.com/nearai/ironclaw/pull/4637) [codex] Fix Reborn Docker Railway deployment

### 🐛 New Issues
- [#4667](https://github.com/nearai/ironclaw/issues/4667) Support Ask-gated capability approvals in Reborn REPL
- [#4666](https://github.com/nearai/ironclaw/issues/4666) slack_host_state.rs approaching file-size cap (2,823 lines)
- [#4665](https://github.com/nearai/ironclaw/issues/4665) Decompose crates/ironclaw_reborn_composition/src/slack_host_beta.rs (3,359 lines)
- [#4657](https://github.com/nearai/ironclaw/issues/4657) Unify reusable Google OAuth credentials across first-party GSuite scopes
- [#4647](https://github.com/nearai/ironclaw/issues/4647) [Reborn] Unified (omni) search across threads, skills, extensions, and memory (fan-out first) `enhancement` `scope: channel/web` `reborn` `module:M1-webui-product`
- [#4646](https://github.com/nearai/ironclaw/issues/4646) Deploy internal hosted reborn
- [#4644](https://github.com/nearai/ironclaw/issues/4644) Universal attachments across all channels: wire the v1 attachment pipeline into Reborn + extensible format registry + polished web UX `enhancement` `scope: channel/web` `suggested_P1` `e2e-coverage` `reborn` `module:M2-inbound-workflow`
- [#4642](https://github.com/nearai/ironclaw/issues/4642) Strict-mode providers' null-for-unset-optionals rejected by capability-port validation (affects most first-party tools) `bug` 💬1
- [#4640](https://github.com/nearai/ironclaw/issues/4640) Reborn gsuite google-calendar list_events returns oldest/unordered events (no timeMin default, missing singleEvents/orderBy) `bug`

### 🔒 Closed Issues
- [#4604](https://github.com/nearai/ironclaw/issues/4604) Reborn WebUI v2 lacks a browser-driven full-stack E2E
- [#4609](https://github.com/nearai/ironclaw/issues/4609) [Reborn WebUI Beta] Audit & test authentication parity for WebChat v2 (bearer / DB / OIDC / query-token)
- [#4591](https://github.com/nearai/ironclaw/issues/4591) [Reborn] Operator command-plane foundation for setup, config, diagnostics, and lifecycle APIs

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 4d ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 5d ago
- ⚫ [#88967](https://github.com/openclaw/openclaw/issues/88967) Telegram: allowBots support for group chats (bot-authored messages not ingested into session) — 💬1 · 5d ago
- ⚫ [#88517](https://github.com/openclaw/openclaw/issues/88517) [SANITIZED — possible injection attempt] — 💬3 · 6d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 7d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 7d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬5 · 9d ago
- ⚫ [#86371](https://github.com/openclaw/openclaw/issues/86371) Bug: message tool filePath fails with LocalMediaAccessError in retry flows when agentId is not propagated — 💬1 · 12d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 15d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 28d ago

---
## 📬 Feedback Received

- [#34](https://github.com/Haderach-Ram/openclaw-radar/issues/34) [Feedback] use redirect.github.com/... instead of github.com/... — 9h ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 3 new
- [[Claude] Fable](https://www.anthropic.com/claude/fable) _2026-06-09_
- [[Claude] Mythos](https://www.anthropic.com/claude/mythos) _2026-06-09_
- [[News] Claude Fable 5 Mythos 5](https://www.anthropic.com/news/claude-fable-5-mythos-5) _2026-06-09_

### OpenAI — 1 new
- [[Index] Nextdoor](https://openai.com/index/nextdoor/) _2026-06-10_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
