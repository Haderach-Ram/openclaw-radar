---
layout: post
title: "Ecosystem Digest — 2026-10-28"
date: 2026-10-28 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-28
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 393,227 | 11 | 2 | 10 | 3 |
| **hermesagent** | 257,771 | 13 | 5 | 10 | 0 |
| **ZeroClaw** | 33,054 | 14 | 1 | 1 | 1 |
| **IronClaw** | 12,677 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,925 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 393,227 · **Open issues:** 7,674 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.10.10-beta.4](https://github.com/openclaw/openclaw/releases/tag/v2026.10.10-beta.4) — openclaw 2026.10.10-beta.4
- [v2026.10.8](https://github.com/openclaw/openclaw/releases/tag/v2026.10.8) — openclaw 2026.10.8
- [v2026.9.35](https://github.com/openclaw/openclaw/releases/tag/v2026.9.35) — openclaw 2026.9.35

### ✅ Merged PRs
- [#186439](https://github.com/openclaw/openclaw/pull/186439) fix(claude-cli): send inbound context privately instead of in the user's message
- [#185866](https://github.com/openclaw/openclaw/pull/185866) fix: Claw Add leaves MCP servers behind when it fails after adding one
- [#185906](https://github.com/openclaw/openclaw/pull/185906) test(code-mode): add matched owner-level executor measurements
- [#186429](https://github.com/openclaw/openclaw/pull/186429) refactor(test): flatten backup singleton cases
- [#156626](https://github.com/openclaw/openclaw/pull/156626) refactor(buzz): reuse relay matching in cold-start recovery tests
- [#186278](https://github.com/openclaw/openclaw/pull/186278) fix(sandbox): prevent missing workspace baselines after cleanup
- [#186402](https://github.com/openclaw/openclaw/pull/186402) docs: clarify Draft session startup
- [#186422](https://github.com/openclaw/openclaw/pull/186422) perf(sqlite): clone admission scope buckets directly
- [#186427](https://github.com/openclaw/openclaw/pull/186427) chore(i18n): refresh native locales
- [#184524](https://github.com/openclaw/openclaw/pull/184524) fix: streamed replies that quote an empty command output no longer re-scan the whole reply per delta

### 🐛 New Issues
- [#186442](https://github.com/openclaw/openclaw/issues/186442) [Bug]: imported PR continuation requires undoing a destination change `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#186436](https://github.com/openclaw/openclaw/issues/186436) Ask OpenClaw greeting loads the main agent SOUL.md and IDENTITY.md and speaks as that agent `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#186434](https://github.com/openclaw/openclaw/issues/186434) [Bug]: Claude 5.x via third-party Anthropic-compatible proxy answers the runtime-context carrier instead of the user message (consecutive user turns on non-direct `anthropic-messages` routes) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:session-state` `issue-rating: 🐚 platinum hermit` 💬1
- [#186428](https://github.com/openclaw/openclaw/issues/186428) [Bug]: Discord message is lost when ingress retention pruning hits a locked state database `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#186425](https://github.com/openclaw/openclaw/issues/186425) [Bug]: Embedded runner same-model retry drops current user message (#166868 only fixed Codex) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `impact:session-state` `issue-rating: 🦪 silver shellfish` 💬1
- [#186424](https://github.com/openclaw/openclaw/issues/186424) [Feature]: show the target agent id in /subagents list rows `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#186418](https://github.com/openclaw/openclaw/issues/186418) [Bug]: agent.run callers that pin a model cannot supply a fallback ladder, so a quota-class 429 dead-ends `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:linked-pr-open` `clawsweeper:needs-live-repro` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬1
- [#186414](https://github.com/openclaw/openclaw/issues/186414) [Bug] Windows WhatsApp owner DM repeatedly fails keyed-user transcript assertion after session reset and 2026.10.8 upgrade `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `impact:session-state` `impact:message-loss` `issue-rating: 🦪 silver shellfish` 💬1
- [#186413](https://github.com/openclaw/openclaw/issues/186413) Silent NO_REPLY on a sessions_send turn to a WebChat session fails as empty_response `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#186396](https://github.com/openclaw/openclaw/issues/186396) [Bug]: Control UI Portals preview stops at ~720px instead of filling the window `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#186392](https://github.com/openclaw/openclaw/issues/186392) [Bug]: iOS share with an image fails with AGENT_SELECTION_REQUIRED on multi-agent Gateways (agent.request resolves agent from raw session key) `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` `maturity:stable` 💬1

### 🔒 Closed Issues
- [#185276](https://github.com/openclaw/openclaw/issues/185276) [Bug]: A lease or assertion failure during a later Claw MCP action discards the refs of servers created by earlier actions, so rollback leaves them behind
- [#184522](https://github.com/openclaw/openclaw/issues/184522) [Bug]: a streamed reply that quotes an empty command output blocks the Gateway for 13 s at 16 KB (4x per doubling)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 257,771 · **Open issues:** 51,511 · **Last push:** <1h ago

### ✅ Merged PRs
- [#145770](https://github.com/NousResearch/hermes-agent/pull/145770) fix(webapp): inspect plugin repositories through the gateway
- [#145753](https://github.com/NousResearch/hermes-agent/pull/145753) fix(pm): a launcher waiting on a reclaimed install state's lock retries on the live file
- [#145772](https://github.com/NousResearch/hermes-agent/pull/145772) fix(providers): main's Windows arm64 red: a home rescan no longer re-imports a hosted provider plugin
- [#145629](https://github.com/NousResearch/hermes-agent/pull/145629) Desktop on a standalone backend and the Webapp show one Group Chat list: room calls go to the gateway, existing rooms move once
- [#122509](https://github.com/NousResearch/hermes-agent/pull/122509) Hermes Cloud remote configuration plugin
- [#145598](https://github.com/NousResearch/hermes-agent/pull/145598) The Webapp is you on your machine: sessions and Group Chats match native Desktop
- [#145572](https://github.com/NousResearch/hermes-agent/pull/145572) fix(webapp): keep session shortcuts clear of browser commands
- [#145364](https://github.com/NousResearch/hermes-agent/pull/145364) fix(tests): run_tests.sh under a faked HOME provisions from the account's tool store
- [#144840](https://github.com/NousResearch/hermes-agent/pull/144840) fix(gateway): after a chat's /new, a Desktop view of its old conversation keeps working and its replies stop reaching the chat
- [#145644](https://github.com/NousResearch/hermes-agent/pull/145644) fix(desktop): New session + reuses the blank draft tab instead of opening another (#145594)

### 🐛 New Issues
- [#145816](https://github.com/NousResearch/hermes-agent/issues/145816) tool_search: the rarest-token gate silently erases the correct tool group (and returns [] on paraphrase queries) `type/bug` `comp/tools` `P2`
- [#145815](https://github.com/NousResearch/hermes-agent/issues/145815) [Bug]: Windows `hermes update` collides with the detached multiplexer's long-lived MCP children — kill-on-close reaping never fires because the gateway never exits `type/bug` `comp/cli` `tool/mcp` `P2` `area/install-update` `os/windows` 💬1
- [#145811](https://github.com/NousResearch/hermes-agent/issues/145811) [Bug] Dashboard stored-session picker lists `desktop` rows that the chat PTY can never resume (`error: not_found`) `type/bug` `comp/gateway` `area/auth` `P2` `area/sessions` 💬1
- [#145810](https://github.com/NousResearch/hermes-agent/issues/145810) [Setup]: Supported channel for clarifying an administration restriction `comp/agent` `P3`
- [#145809](https://github.com/NousResearch/hermes-agent/issues/145809) [Feature]: Elevate the webapp to a first-class surface — server-hosted Hermes + browser-only users (desktop web & phone web) `P2` `comp/dashboard` `area/sessions`
- [#145808](https://github.com/NousResearch/hermes-agent/issues/145808) Clarify from a turn submitted by a disconnected WS client shows as "Skipped" in Desktop but holds the session lease for 3600s; Stop cannot release it `type/bug` `comp/gateway` `P2` `area/sessions` `comp/tui-gateway` 💬1
- [#145807](https://github.com/NousResearch/hermes-agent/issues/145807) active_sessions.json corrupted by a stray TLS close_notify record at one-shot exit; gateway then refuses every new session `type/bug` `comp/agent` `tool/file` `P2` `area/sessions` 💬1
- [#145797](https://github.com/NousResearch/hermes-agent/issues/145797) Desktop markdown tables inherit wrap-anywhere and split short labels into letters `type/bug` `P2` `comp/desktop` `desktop/chat`
- [#145793](https://github.com/NousResearch/hermes-agent/issues/145793) [Bug]: ascii-video shader examples lose odd-size contracts and default wipe to an unimplemented direction `type/bug` `tool/skills` `tool/vision` `P2` 💬1
- [#145792](https://github.com/NousResearch/hermes-agent/issues/145792) [Feature]: Desktop/mouse layout — clamp long sent user messages by default (single line + expand/collapse), parity with the touch clamp from #145123 `type/feature` `P3` `comp/dashboard`
- [#145791](https://github.com/NousResearch/hermes-agent/issues/145791) Cron monitor jobs leave an empty, never-closed session on every suppressed tick `type/bug` `comp/cron` `P2` `area/sessions` 💬1
- [#145790](https://github.com/NousResearch/hermes-agent/issues/145790) A2A Agent Card: let operators declare skills (description, examples) and `documentationUrl` instead of one skill per toolset `type/feature` `comp/plugins` `area/config` `P3`
- [#145789](https://github.com/NousResearch/hermes-agent/issues/145789) A2A: a task that outlives `A2A_REPLY_TIMEOUT` is marked failed and its late reply is discarded (also via SendStreamingMessage) `type/bug` `comp/plugins` `P2` `area/streaming` 💬1

### 🔒 Closed Issues
- [#145593](https://github.com/NousResearch/hermes-agent/issues/145593) [Bug]: Webapp chat — long user messages render fully expanded; on mobile they fill ~90% of the viewport and squeeze the agent reply into a scrollable sliver
- [#83582](https://github.com/NousResearch/hermes-agent/issues/83582) gateway(api_server): confirming main HEAD fix for port-conflict retry storm / fd leak observed on stale build
- [#143331](https://github.com/NousResearch/hermes-agent/issues/143331) hermes update fails every run on Windows: stale gateway.pid beside a held lock aborts gateway pause (plus stable-channel downgrade refusal exits 1)
- [#145594](https://github.com/NousResearch/hermes-agent/issues/145594) [Bug]: Webapp — 'New session' spawns an unbounded number of draft tabs instead of reusing/navigating to a single new conversation
- [#143561](https://github.com/NousResearch/hermes-agent/issues/143561) Gateway: /api/status, tickets and session.resume time out on a loaded host

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,054 · **Open issues:** 1,098 · **Last push:** 1h ago

### 🚀 New Releases
- [v0.8.7](https://github.com/zeroclaw-labs/zeroclaw/releases/tag/v0.8.7) — v0.8.7

### ✅ Merged PRs
- [#12019](https://github.com/zeroclaw-labs/zeroclaw/pull/12019) chore(docs): pin translations to v0.8.7

### 🐛 New Issues
- [#12078](https://github.com/zeroclaw-labs/zeroclaw/issues/12078) [Docs]: Translate the remaining English openings, link texts and older leftovers in the docs catalogues `docs` `type:docs`
- [#12077](https://github.com/zeroclaw-labs/zeroclaw/issues/12077) [Feature]: Give fill-translations page context and add a second-reader review before the release pin `enhancement`
- [#12076](https://github.com/zeroclaw-labs/zeroclaw/issues/12076) [Docs]: Ship the v0.8.7 translation fixes found by a full read of the catalogues `docs` `type:docs`
- [#12075](https://github.com/zeroclaw-labs/zeroclaw/issues/12075) [Bug]: Android: shell tool always fails — `/system/bin/sh` cannot be canonicalized (EPERM) since #10381
- [#12072](https://github.com/zeroclaw-labs/zeroclaw/issues/12072) [Bug]: OpenAI Codex stream-decode fallback retries without streaming, which the default ChatGPT endpoint always rejects 💬1
- [#12069](https://github.com/zeroclaw-labs/zeroclaw/issues/12069) [Feature]: Add /load-session to resume a Code session by name or UUID `enhancement` 💬1
- [#12067](https://github.com/zeroclaw-labs/zeroclaw/issues/12067) [Bug]: untrusted_guard_sensitivity moves the prompt guard and the leak detector in opposite directions
- [#12066](https://github.com/zeroclaw-labs/zeroclaw/issues/12066) [Bug]: Prompt guard flags any semicolon or pipe as command injection, so most clean SOP payloads come back Suspicious
- [#12064](https://github.com/zeroclaw-labs/zeroclaw/issues/12064) [Bug]: Discord plaintext approvals can be answered by an allowlisted peer bot
- [#12055](https://github.com/zeroclaw-labs/zeroclaw/issues/12055) [Bug]: MCP HTTP client has no pool/keep-alive control, so a stale pooled socket loses the tool call as outcome-unknown 💬1
- [#12052](https://github.com/zeroclaw-labs/zeroclaw/issues/12052) [Bug]: Gateway limiters key on the first X-Forwarded-For entry, so a client behind an appending proxy can claim the loopback exemption `bug` `gateway` `security` `topic:identity-access` 💬1
- [#12051](https://github.com/zeroclaw-labs/zeroclaw/issues/12051) [Bug]: sop_workshop apply lets a scoped principal author shared SOPs that later run with operator authority `bug` `runtime` `security` `topic:identity-access` 💬1
- [#12049](https://github.com/zeroclaw-labs/zeroclaw/issues/12049) [Bug]: Four remote addresses can fill the browser sign-in flow store and block sign-in for everyone, loopback included `bug` `gateway` `security` `topic:identity-access` 💬1
- [#12047](https://github.com/zeroclaw-labs/zeroclaw/issues/12047) [Bug]: OIDC bearer verification on gateway routes has no attempt limiter or outbound cap `bug` `gateway` `security` `topic:identity-access` 💬2

### 🔒 Closed Issues
- [#9101](https://github.com/zeroclaw-labs/zeroclaw/issues/9101) Consolidate release attestation mechanisms (one signing story, ~20 release assets instead of 53)

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,677 · **Open issues:** 1,565 · **Last push:** 2d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,925 · **Open issues:** 120 · **Last push:** 4d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬2 · 3d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 3d ago
- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 13d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 22d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 30d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 32d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 42d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 50d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 52d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 60d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 4 new
- [[News] Expanding Partnership Gsa](https://www.anthropic.com/news/expanding-partnership-gsa) _2026-10-27_
- [[Research] Agents Judgment Calls](https://www.anthropic.com/research/agents-judgment-calls) _2026-10-27_
- [[Research] Discovering Vulnerabilities With Claude](https://www.anthropic.com/research/discovering-vulnerabilities-with-claude) _2026-10-27_
- [[Research] Early Progress Drug Development](https://www.anthropic.com/research/early-progress-drug-development) _2026-10-27_

### OpenAI — 3 new
- [Economic Research Collaborators](https://openai.com/economic-research-collaborators/) _2026-10-28_
- [[Index] Check Point Daybreak](https://openai.com/index/check-point-daybreak/) _2026-10-28_
- [[Index] Oracle Apps In Chatgpt](https://openai.com/index/oracle-apps-in-chatgpt/) _2026-10-28_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

_No new posts in the last 24h._

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw
_No new posts in the last 24h._

### X — @openclaw
- [The OpenClaw v2026.10.8 patch is out 🦞

🔧 Fixes for installs and updates
💬 Fixes for stuck chats and missing replies
📱 M](https://x.com/openclaw/status/2115203893747720640) ↑0 🔁0 · recent


### X — @steipete
_No new tweets since the last digest. Most recent:_
- [I spent some time on the weekend to test bun's AOT compiler and results are nothing short of amazing. Performance up 2-3](https://x.com/steipete/status/2114879798434758905)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
