---
layout: post
title: "Ecosystem Digest — 2026-11-20"
date: 2026-11-20 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-20
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 394,838 | 15 | 1 | 10 | 2 |
| **hermesagent** | 264,770 | 14 | 1 | 10 | 2 |
| **ZeroClaw** | 33,516 | 3 | 2 | 4 | 0 |
| **IronClaw** | 12,716 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,976 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 394,838 · **Open issues:** 8,505 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.11.10-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.11.10-beta.1) — openclaw 2026.11.10-beta.1
- [v2026.11.6](https://github.com/openclaw/openclaw/releases/tag/v2026.11.6) — openclaw 2026.11.6

### ✅ Merged PRs
- [#202168](https://github.com/openclaw/openclaw/pull/202168) fix: let Crabbox wrapper tests load native renderer assets
- [#202060](https://github.com/openclaw/openclaw/pull/202060) improve: preview a Template without expanding its files in chat
- [#202115](https://github.com/openclaw/openclaw/pull/202115) fix: show the right agent and live activity when adding a template
- [#202126](https://github.com/openclaw/openclaw/pull/202126) feat: show planned automations and their controls in chat
- [#200592](https://github.com/openclaw/openclaw/pull/200592) improve(ios): rebuild the chat transcript around the web reading model
- [#202018](https://github.com/openclaw/openclaw/pull/202018) fix: keep proxy-signed-in automations running after proxy settings change
- [#201913](https://github.com/openclaw/openclaw/pull/201913) docs: restore the OpenClaw 2026.11.5 release notes
- [#202106](https://github.com/openclaw/openclaw/pull/202106) fix(ci): match updater group build expectations
- [#202077](https://github.com/openclaw/openclaw/pull/202077) improve: show progress when creating a Template and keep the agent’s portrait
- [#202149](https://github.com/openclaw/openclaw/pull/202149) chore(ui): refresh control ui locales

### 🐛 New Issues
- [#202176](https://github.com/openclaw/openclaw/issues/202176) [Bug]: macOS process census fails the whole Codex start when any transient process has incomplete topology ("Process identity is unavailable") `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:other` 💬2
- [#202173](https://github.com/openclaw/openclaw/issues/202173) [Bug]: Foreground exec trims structured output `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#202172](https://github.com/openclaw/openclaw/issues/202172) [SANITIZED — possible injection attempt] `bug` `no-stale` `bug:behavior` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#202169](https://github.com/openclaw/openclaw/issues/202169) [Bug]: macOS Gateway aborts with Alloc(AllocError) in bundled Bun module resolver `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:crash-loop` `issue-rating: 🦪 silver shellfish` 💬1
- [#202167](https://github.com/openclaw/openclaw/issues/202167) [Bug]: 2026.11.5 macOS BA-EA case collision persists — recovery identity failure and pending Codex migration `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` `maturity:stable` 💬1
- [#202165](https://github.com/openclaw/openclaw/issues/202165) Realtime voice token usage is never recorded in session usage or cost reports `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#202163](https://github.com/openclaw/openclaw/issues/202163) [Feature]: Install guide for Control Plane `P3` 💬1
- [#202161](https://github.com/openclaw/openclaw/issues/202161) CLI-provider candidate in a cron agentTurn falls through to the OpenAI-completions stub (TypeError), masking the first-hop error `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `impact:auth-provider` `issue-rating: 🦪 silver shellfish` 💬1
- [#202159](https://github.com/openclaw/openclaw/issues/202159) [Bug]: backup create --verify detects case-only filename collision only after writing a 32.8 GB archive `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#202158](https://github.com/openclaw/openclaw/issues/202158) [Bug]: [Bug]: OpenClaw AI 응답 오류 반복 및 서비스 중단 `bug` `regression` `P2` `impact:ux-friction` 💬1
- [#202152](https://github.com/openclaw/openclaw/issues/202152) [Bug]: Turn aborted right after auto-compaction succeeded shows "The operation was aborted. | 20" with no cause and no account of the work already done `bug` `bug:behavior` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#202151](https://github.com/openclaw/openclaw/issues/202151) [Feature]: Pick a new progress label each time a status starts (random from the pool, or a hook) `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` 💬1
- [#202150](https://github.com/openclaw/openclaw/issues/202150) [SANITIZED — possible injection attempt] `P2` `clawsweeper:needs-info` `impact:session-state` `issue-rating: 🦐 gold shrimp` 💬1
- [#202146](https://github.com/openclaw/openclaw/issues/202146) [Bug]: Default Proactive check runs a full main-session model turn every 30 minutes when no owner route exists `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#202140](https://github.com/openclaw/openclaw/issues/202140) Automation runs post a bare "⚠️ Tool Call failed" when record_result is repeated through Tool Search `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#174089](https://github.com/openclaw/openclaw/issues/174089) [Bug]: OpenClaw 2026.10.4 blocks Telegram offset migration: BA-EA/ba-ea SQLite case collision

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬83 · 3d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 264,770 · **Open issues:** 53,917 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.23.3](https://github.com/NousResearch/hermes-agent/releases/tag/v0.23.3) — Hermes Agent v0.23.3
- [v0.23.2+canary.20261119T064637Z](https://github.com/NousResearch/hermes-agent/releases/tag/v0.23.2%2Bcanary.20261119T064637Z) — Hermes Agent canary v0.23.2+canary.20261119T064637Z

### ✅ Merged PRs
- [#156734](https://github.com/NousResearch/hermes-agent/pull/156734) fix(desktop): a turn's end-of-turn report does not settle the next turn
- [#156733](https://github.com/NousResearch/hermes-agent/pull/156733) fix(dashboard): late-bound helpers wait for a module another thread is importing
- [#156731](https://github.com/NousResearch/hermes-agent/pull/156731) fix(desktop): a reply the gateway reports complete is not shown as a failure
- [#157983](https://github.com/NousResearch/hermes-agent/pull/157983) fix(ssl): SSL_CERT_FILE stays trusted on Windows and macOS for provider clients (salvage #148253)
- [#157036](https://github.com/NousResearch/hermes-agent/pull/157036) fix(env): load an unreadable profile .op.env as absent, like .env
- [#158005](https://github.com/NousResearch/hermes-agent/pull/158005) plugin-catalog: 17 official and labs plugins get today's reviewed fixes
- [#158002](https://github.com/NousResearch/hermes-agent/pull/158002) fix(vault): follow-up nits from the #157803 review
- [#157803](https://github.com/NousResearch/hermes-agent/pull/157803) fix(vault): type login secrets as trusted input and verify they stuck
- [#157985](https://github.com/NousResearch/hermes-agent/pull/157985) chore(ci): run Linux install/update E2E jobs on Blacksmith
- [#157991](https://github.com/NousResearch/hermes-agent/pull/157991) fix(modal): routed preflight reads only the serving profile's tokens

### 🐛 New Issues
- [#158066](https://github.com/NousResearch/hermes-agent/issues/158066) [Bug] Interactive CLI on WSL2: bottom input box visibly flickers whenever content above it re-renders (streaming / tool-result repaints)
- [#158065](https://github.com/NousResearch/hermes-agent/issues/158065) Desktop chats lose all MCP tools when dashboard.turn_isolation is enabled
- [#158064](https://github.com/NousResearch/hermes-agent/issues/158064) [Setup]: Cannot setup with python 3.15 `type/bug` `comp/cli` `P2` `area/install-update`
- [#158063](https://github.com/NousResearch/hermes-agent/issues/158063) [Feature][Desktop]: Next/previous session in sidebar order (simple ⌥↑/⌥↓, no switcher semantics) `type/feature` `P3` `comp/desktop` `area/sessions` `desktop/sessions` `desktop/shell`
- [#158059](https://github.com/NousResearch/hermes-agent/issues/158059) Desktop app: Files/Folder sidebar panel shows UNREADABLE (ENOENT) when switching from a remote gateway bot to a Local bot `type/bug` `P3` `comp/desktop` `desktop/sessions` `desktop/files`
- [#158054](https://github.com/NousResearch/hermes-agent/issues/158054) [Bug]: Desktop new chat from Home pane sends the sidebar section token as cwd ('/resume') with cwd_explicit:false — session.create refuses with invalid_params `type/bug` `comp/gateway` `P2` `area/sessions`
- [#158051](https://github.com/NousResearch/hermes-agent/issues/158051) Small-window local models: tool schemas are ~77% of a fresh prompt; make the default tool_search defer list window-aware `type/feature` `comp/agent` `comp/tools` `tool/code-exec` `area/config` `P3` `area/compression` `area/local-models`
- [#158050](https://github.com/NousResearch/hermes-agent/issues/158050) write_file: local models re-send files they just wrote (38–48% of writes); the rewrite hint only covers ≥20k-char files `type/perf` `comp/tools` `tool/file` `P2`
- [#158047](https://github.com/NousResearch/hermes-agent/issues/158047) CLI startup takes 6 to 10 s before any command runs `type/perf` `comp/cli` `P2`
- [#158046](https://github.com/NousResearch/hermes-agent/issues/158046) Skip secret-source loading for read-only CLI commands (kanban list/show, --version) `type/feature` `comp/cli` `area/auth` `P3`
- [#158043](https://github.com/NousResearch/hermes-agent/issues/158043) gateway: bg-process completion notification truncates to 0 chars when the line-boundary snap eats the whole tail (sys-wv4zo0) `type/bug` `comp/gateway` `tool/file` `P2` 💬1
- [#158042](https://github.com/NousResearch/hermes-agent/issues/158042) [Feature]: Show the quoted message on replies in gateway-owned Group Chats (and give it to members) `type/feature` `comp/gateway` `P3`
- [#158041](https://github.com/NousResearch/hermes-agent/issues/158041) Community plugin: LearnHermes — evidence-based journey companion (beta testers wanted) `comp/plugins` `P3`
- [#158040](https://github.com/NousResearch/hermes-agent/issues/158040) docs: hooks.md contradicts itself on pre_llm_call injection placement (append vs prepend) and firing order vs compression `type/docs` `P3` `area/compression` 💬1

### 🔒 Closed Issues
- [#145743](https://github.com/NousResearch/hermes-agent/issues/145743) [Feature]: Recover tool_call arguments with unescaped inner quotes (heredoc payloads) instead of replacing them with {}

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,516 · **Open issues:** 1,335 · **Last push:** <1h ago

### ✅ Merged PRs
- [#12571](https://github.com/zeroclaw-labs/zeroclaw/pull/12571) fix(xtask): read the Windows prebuilt installer when the guide is rendered
- [#12577](https://github.com/zeroclaw-labs/zeroclaw/pull/12577) fix(deps): patch heapless and Wasmtime RustSec advisories
- [#12499](https://github.com/zeroclaw-labs/zeroclaw/pull/12499) fix(gateway): keep per-connection task records out of the INFO trace
- [#11994](https://github.com/zeroclaw-labs/zeroclaw/pull/11994) feat(security): read POSIX commands in bash's grammar when bash runs them

### 🐛 New Issues
- [#12570](https://github.com/zeroclaw-labs/zeroclaw/issues/12570) [Bug]: Daemon hangs at startup when the log directory holds millions of leaked `runtime-trace.tmp.*` files from failed rolling trims `bug`
- [#12569](https://github.com/zeroclaw-labs/zeroclaw/issues/12569) [Bug]: `plugin install` and `plugin list --verify` report a tool plugin as loading when a built-in tool name reserves it `bug`
- [#12568](https://github.com/zeroclaw-labs/zeroclaw/issues/12568) [Bug]: Dashboard Cost Overview bars are scaled to the largest figure, so the Monthly bar is always full 💬1

### 🔒 Closed Issues
- [#12476](https://github.com/zeroclaw-labs/zeroclaw/issues/12476) [Bug]: gateway logs every connection at INFO through spawn!, flooding the runtime trace
- [#12217](https://github.com/zeroclaw-labs/zeroclaw/issues/12217) [Docs]: Email tools-only setup should say approval routes also start the IMAP listener

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,716 · **Open issues:** 1,574 · **Last push:** 10d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,976 · **Open issues:** 120 · **Last push:** 27d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬4 · 7d ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 17d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 26d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 45d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 53d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 55d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 65d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 73d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 75d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 83d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 2 new
- [[Customers] Portland Leather](https://openai.com/ads/customers/portland-leather/)
- [[Customers] Weightwatchers](https://openai.com/ads/customers/weightwatchers/)

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/singularity — top 2 new
- [Anyone else confused? Made with Hydrogen](https://reddit.com/r/singularity/comments/1y0fu5q/anyone_else_confused_made_with_hydrogen/) ↑399
- [Google models in a year be like](https://reddit.com/r/singularity/comments/1y0hxjq/google_models_in_a_year_be_like/) ↑359

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Chasing "AGI-like" persistent memory in OpenClaw: an agent that actually learns and stays the same entity over months. Where we're stuck.](https://reddit.com/r/openclaw/comments/1y077pk/chasing_agilike_persistent_memory_in_openclaw_an/) ↑22
- [My Agent Team Org Chart](https://reddit.com/r/openclaw/comments/1y0m6t5/my_agent_team_org_chart/) ↑15
- [Bulk / iterative tasks with LLM classification - how to optimise?](https://reddit.com/r/openclaw/comments/1y04mna/bulk_iterative_tasks_with_llm_classification_how/) ↑4
- [Context Compression takes really long](https://reddit.com/r/openclaw/comments/1y03jy5/context_compression_takes_really_long/) ↑3
- [Should an agent's persistent memory ever forget on purpose?](https://reddit.com/r/openclaw/comments/1xzzmi5/should_an_agents_persistent_memory_ever_forget_on/) ↑2

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [The ClawCast — Episode 17](https://x.com/openclaw/status/2123136511910576608)

### X — @steipete
- [Landed a fix for that in OpenClaw yesterday (for the few folks using the embedded harness instead of codex, since it’s a](https://x.com/steipete/status/2123487048250327497) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
