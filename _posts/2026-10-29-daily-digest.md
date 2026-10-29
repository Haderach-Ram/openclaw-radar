---
layout: post
title: "Ecosystem Digest — 2026-10-29"
date: 2026-10-29 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-29
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 393,297 | 9 | 6 | 10 | 0 |
| **hermesagent** | 258,092 | 11 | 5 | 10 | 0 |
| **ZeroClaw** | 33,061 | 15 | 1 | 0 | 0 |
| **IronClaw** | 12,688 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,927 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 393,297 · **Open issues:** 7,760 · **Last push:** <1h ago

### ✅ Merged PRs
- [#187158](https://github.com/openclaw/openclaw/pull/187158) fix(test): make broker lifecycle ordering checks deterministic
- [#187121](https://github.com/openclaw/openclaw/pull/187121) fix: restore Files catalog after preview retirement
- [#187096](https://github.com/openclaw/openclaw/pull/187096) fix: keep New Session tooltip from blocking sidebar controls
- [#187138](https://github.com/openclaw/openclaw/pull/187138) improve(ios): narrow release source checkout
- [#187144](https://github.com/openclaw/openclaw/pull/187144) fix: restore lint compliance in sessions-send admission tests
- [#187162](https://github.com/openclaw/openclaw/pull/187162) chore: restore measured test-code headroom
- [#187147](https://github.com/openclaw/openclaw/pull/187147) fix(ios): qualify keyboard layout with completed tool work
- [#184660](https://github.com/openclaw/openclaw/pull/184660) chore(deps): remove expired tsrs release-age exceptions
- [#186446](https://github.com/openclaw/openclaw/pull/186446) fix(agents): don't stop CLI-backed replies as stalled while the model is still thinking
- [#186485](https://github.com/openclaw/openclaw/pull/186485) fix(pr): unblock attributed artifact-build failures after primary CI passes

### 🐛 New Issues
- [#187171](https://github.com/openclaw/openclaw/issues/187171) Gateway: reserved readiness endpoints (/ready /readyz /startup) are unqueryable during the entire boot window — external watchers cannot distinguish starting from dead `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#187163](https://github.com/openclaw/openclaw/issues/187163) [Feature]: independent reviewed test-line allocations `enhancement` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#187155](https://github.com/openclaw/openclaw/issues/187155) [Bug]: update on PostgreSQL families reports original-state capture unavailable, "writer is unknown" and an unsealed capture after a successful update; SQLite on the same build seals it `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `maturity:stable` `impact:ux-friction` `clawsweeper:bulk-filed` 💬1
- [#187154](https://github.com/openclaw/openclaw/issues/187154) [Bug]: Resume keeps its pre-TUI Gateway connection alive after interruption `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:crash-loop` `issue-rating: 🦞 diamond lobster` 💬1
- [#187153](https://github.com/openclaw/openclaw/issues/187153) [Bug]: Interrupting dashboard leaves Control UI document readiness running `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬1
- [#187151](https://github.com/openclaw/openclaw/issues/187151) [Bug]: update refuses PostgreSQL families with "cannot be captured by this updater" when the real cause is a failed family lookup (e.g. missing unaccent) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` `clawsweeper:bulk-filed` 💬1
- [#187150](https://github.com/openclaw/openclaw/issues/187150) [Bug]: backup create: SQLite header probe uses one 10 s budget for the whole state dir, so backups fail once it holds a few hundred thousand files `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `clawsweeper:bulk-filed` 💬1
- [#187149](https://github.com/openclaw/openclaw/issues/187149) [Feature]: PlanetScale Neki native agent storage via a pre-boot PostgreSQL lifecycle extension `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🦪 silver shellfish` `impact:other` 💬2
- [#187143](https://github.com/openclaw/openclaw/issues/187143) Gateway restart removes an unanswered prompt from active chat history `P2` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#187172](https://github.com/openclaw/openclaw/issues/187172) [Bug]: Control UI memory search uses legacy RPC for provider-runtime engines
- [#187107](https://github.com/openclaw/openclaw/issues/187107) [Bug]: Files stays blank after preview retirement during task navigation
- [#187088](https://github.com/openclaw/openclaw/issues/187088) [Bug]: New Session shortcut tooltip blocks adjacent sidebar header controls
- [#187166](https://github.com/openclaw/openclaw/issues/187166) Update failure: package-install-omit-optional (2026.10.5)
- [#187119](https://github.com/openclaw/openclaw/issues/187119) CI mock-export ratchet rejects Gateway lifecycle fixtures
- [#186898](https://github.com/openclaw/openclaw/issues/186898) Version skew: `npm install -g` can target a different Node prefix than the running gateway, then migrate agent DBs past the running build

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 258,092 · **Open issues:** 51,757 · **Last push:** <1h ago

### ✅ Merged PRs
- [#146117](https://github.com/NousResearch/hermes-agent/pull/146117) fix(webapp): refuse unbound profile tickets and bind explicit profiles on launch sockets (stacked on #146097)
- [#146100](https://github.com/NousResearch/hermes-agent/pull/146100) docs(security): allow_private_urls guards cloud browsers and web tools, not the local sidecar (salvage #126299)
- [#146126](https://github.com/NousResearch/hermes-agent/pull/146126) fix(cli,tui): text + Enter in one write submits (tmux send-keys, process_manage submit), salvage #70099
- [#146240](https://github.com/NousResearch/hermes-agent/pull/146240) Saved passwords fill on Camofox pages (browser page backend seam for browser_vault)
- [#146097](https://github.com/NousResearch/hermes-agent/pull/146097) fix(webapp): Webapp socket and billing reads keep their profile's secret scope on a multiplexed gateway (salvage #137897)
- [#146110](https://github.com/NousResearch/hermes-agent/pull/146110) fix(desktop): a reply that finishes during a reconnect no longer stays stuck on its first words
- [#146195](https://github.com/NousResearch/hermes-agent/pull/146195) Docker tests: a stalled docker exec no longer fails the whole poll (arm64 dashboard flake)
- [#146079](https://github.com/NousResearch/hermes-agent/pull/146079) fix(search): search_files keeps results when a directory under the root is unreadable (salvage #114655)
- [#146214](https://github.com/NousResearch/hermes-agent/pull/146214) fix(update): a checkout-lock probe never reads another probe as a running update
- [#146290](https://github.com/NousResearch/hermes-agent/pull/146290) Camofox catalog pin: browser_vault fills saved passwords on the Camofox tab

### 🐛 New Issues
- [#146297](https://github.com/NousResearch/hermes-agent/issues/146297) fix(state): quarantined handle still runs SQLite's close-time checkpoint on Python <3.12 — recurrence of the #101093 shutdown half
- [#146293](https://github.com/NousResearch/hermes-agent/issues/146293) Memory: claim_instance lets one provider instance be re-initialized for another profile when multiplexing is off (cross-profile memory reads/writes in multi-profile hosts) `type/security` `comp/agent` `tool/memory` `P3` `area/profiles`
- [#146291](https://github.com/NousResearch/hermes-agent/issues/146291) [desktop] Mic start freezes the window for 1-7 s on Windows: recorder builds a new AudioContext on every take `type/perf` `P2` `comp/desktop` `desktop/chat` `os/windows` 💬1
- [#146288](https://github.com/NousResearch/hermes-agent/issues/146288) [Bug]: claude-subscription-directsdk: PermissionError [WinError 32] on exit when cleaning up claude-directsdk-picker temp dir (Windows) `type/bug` `comp/plugins` `P3` `os/windows`
- [#146281](https://github.com/NousResearch/hermes-agent/issues/146281) [Bug]: matrix/python-olm build fails on gcc-only hosts — managed PBS sysconfig wants missing clang++/clang and a dead /tools/llvm/bin/llvm-ar; update still reports success and pm doctor passes `type/bug` `comp/cli` `platform/matrix` `P3` `area/install-update`
- [#146280](https://github.com/NousResearch/hermes-agent/issues/146280) Anthropic usage: utilization <= 1% reported as 100% (fraction scaling on a percent field) `type/bug` `comp/agent` `provider/anthropic` `P2` `area/billing` 💬1
- [#146278](https://github.com/NousResearch/hermes-agent/issues/146278) cron: agent jobs refused with 'Gateway draining: update_paused' while a PM sync (or a running cron worker) holds the update fence `type/bug` `comp/cli` `P2` 💬1
- [#146275](https://github.com/NousResearch/hermes-agent/issues/146275) [Bug]: [TUI] the model list is huge to select `type/bug` `comp/tui` `area/config` `P2` 💬1
- [#146272](https://github.com/NousResearch/hermes-agent/issues/146272) user plugin's transform_tool_result hook registers but never dispatches in CLI/chat (v0.22.5) `type/bug` `comp/cli` `comp/plugins` `P2` 💬1
- [#146266](https://github.com/NousResearch/hermes-agent/issues/146266) Feature request: let Hermes Desktop set (and reset) the backend dashboard username/password, instead of only signing in to an existing one `type/feature` `area/auth` `area/config` `P3` `comp/desktop` `desktop/settings`
- [#146265](https://github.com/NousResearch/hermes-agent/issues/146265) Surface routed + backend model in runtime footer and CLI status bar (combines #106973 + #49026) `type/feature` `comp/cli` `comp/gateway` `P3`

### 🔒 Closed Issues
- [#139611](https://github.com/NousResearch/hermes-agent/issues/139611) [Bug]: Telegram reply anchors crash on non-numeric ids since v0.22.1 — raw int() on wake-identity JSON kills every reply into affected sessions
- [#126247](https://github.com/NousResearch/hermes-agent/issues/126247) [Feature]: Support password-blind Hermes Vault credential injection with CamoFox
- [#132686](https://github.com/NousResearch/hermes-agent/issues/132686) browser_vault_fill cannot see login fields inside open shadow roots ("No login form fields were found")
- [#122561](https://github.com/NousResearch/hermes-agent/issues/122561) [Bug]: browser_vault_fill cannot discover login fields inside open Shadow DOM
- [#144750](https://github.com/NousResearch/hermes-agent/issues/144750) checkout_lock_held() probe is observable: parallel readers turn each other's probe into 'Gateway draining: update_paused'

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,061 · **Open issues:** 1,094 · **Last push:** 15h ago

### 🐛 New Issues
- [#12086](https://github.com/zeroclaw-labs/zeroclaw/issues/12086) [Feature]: Protect WhatsApp phone number `enhancement`
- [#12081](https://github.com/zeroclaw-labs/zeroclaw/issues/12081) [Bug]: Memory_store tool call failure `bug`
- [#12076](https://github.com/zeroclaw-labs/zeroclaw/issues/12076) [Docs]: Ship the v0.8.7 translation fixes found by a full read of the catalogues `docs` `type:docs` 💬1
- [#12075](https://github.com/zeroclaw-labs/zeroclaw/issues/12075) [Bug]: Android: shell tool always fails — `/system/bin/sh` cannot be canonicalized (EPERM) since #10381 💬1
- [#12072](https://github.com/zeroclaw-labs/zeroclaw/issues/12072) [Bug]: OpenAI Codex stream-decode fallback retries without streaming, which the default ChatGPT endpoint always rejects 💬2
- [#12069](https://github.com/zeroclaw-labs/zeroclaw/issues/12069) [Feature]: Add /load-session to resume a Code session by name or UUID `enhancement` 💬2
- [#12067](https://github.com/zeroclaw-labs/zeroclaw/issues/12067) [Bug]: untrusted_guard_sensitivity moves the prompt guard and the leak detector in opposite directions 💬1
- [#12066](https://github.com/zeroclaw-labs/zeroclaw/issues/12066) [Bug]: Prompt guard flags any semicolon or pipe as command injection, so most clean SOP payloads come back Suspicious 💬1
- [#12064](https://github.com/zeroclaw-labs/zeroclaw/issues/12064) [Bug]: Discord plaintext approvals can be answered by an allowlisted peer bot 💬1
- [#12055](https://github.com/zeroclaw-labs/zeroclaw/issues/12055) [Bug]: MCP HTTP client has no pool/keep-alive control, so a stale pooled socket loses the tool call as outcome-unknown 💬2
- [#12054](https://github.com/zeroclaw-labs/zeroclaw/issues/12054) [Feature]: Honor runtime-profile thinking levels for OpenAI 💬1
- [#12014](https://github.com/zeroclaw-labs/zeroclaw/issues/12014) [Bug]: Custom OpenAI-compatible provider with no context_window silently assumes 32,000, then rejects valid turns locally 💬4
- [#11972](https://github.com/zeroclaw-labs/zeroclaw/issues/11972) [Bug]: zeroclaw gateway get-paircode exits 0 when it cannot fetch a code `bug` `gateway` 💬2
- [#11917](https://github.com/zeroclaw-labs/zeroclaw/issues/11917) [Bug]: A web chat receives no cron results or pushed session messages until its first reply 💬2
- [#11908](https://github.com/zeroclaw-labs/zeroclaw/issues/11908) [SANITIZED — possible injection attempt] 💬2

### 🔒 Closed Issues
- [#11612](https://github.com/zeroclaw-labs/zeroclaw/issues/11612) [Bug]: Re-running an already-approved shell command in the same turn aborts the agent loop ("repeated prompt-required tool call 'shell' with identical arguments before approval") and ends the ACP sess

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,688 · **Open issues:** 1,566 · **Last push:** 3d ago

### 🐛 New Issues
- [#8161](https://github.com/nearai/ironclaw/issues/8161) Would you accept Obscurify.ai as a named provider?

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,927 · **Open issues:** 121 · **Last push:** 5d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬2 · 4d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 4d ago
- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 14d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 23d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 31d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 33d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 43d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 51d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 53d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 61d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Ai For Science Expands Foundations Research Institutions](https://www.anthropic.com/news/ai-for-science-expands-foundations-research-institutions) _2026-10-28_

### OpenAI — 2 new
- [[Index] Legora](https://openai.com/index/legora/) _2026-10-29_
- [[Index] Openai Servicenow Partnership Expansion](https://openai.com/index/openai-servicenow-partnership-expansion/) _2026-10-29_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

_No new posts in the last 24h._

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw
_No new posts in the last 24h._

### X — @openclaw
- [One Agent, Many Sessions


@hrudolph
 is joined by 
@jjjhenriksen
 and 
@TheAngryPit
 to discuss sharing an OpenClaw age](https://x.com/openclaw/status/2115606508587360269) ↑0 🔁0 · recent
- [Building Together with AI Agents | ClawCast Community Roundtable](https://x.com/openclaw/status/2115511317520122085) ↑0 🔁0 · recent


### X — @steipete
- [OpenClaw’s web UI now works offline and uses a smart websocket compression/reconnect logic.

Been flying to Vienna today](https://x.com/steipete/status/2115397368229060636) ↑0 🔁0 · recent
- [Meanwhile people still work local and in the cli? 👴](https://x.com/steipete/status/2115398725212238088) ↑0 🔁0 · recent
- [Kinda funny how easy it is to spot bugs by agents vs humans. Someone at Disney still writes code by HAND?](https://x.com/steipete/status/2115380217938158049) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
