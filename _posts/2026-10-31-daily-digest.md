---
layout: post
title: "Ecosystem Digest — 2026-10-31"
date: 2026-10-31 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-31
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 393,486 | 8 | 3 | 10 | 1 |
| **hermesagent** | 258,896 | 11 | 5 | 3 | 0 |
| **ZeroClaw** | 33,073 | 15 | 0 | 5 | 0 |
| **IronClaw** | 12,700 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,931 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 393,486 · **Open issues:** 7,926 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.10.10-beta.5](https://github.com/openclaw/openclaw/releases/tag/v2026.10.10-beta.5) — openclaw 2026.10.10-beta.5

### ✅ Merged PRs
- [#188816](https://github.com/openclaw/openclaw/pull/188816) fix: preserve Git failure reasons during PR preparation
- [#188968](https://github.com/openclaw/openclaw/pull/188968) test(release): retain final live fixture owners
- [#188959](https://github.com/openclaw/openclaw/pull/188959) fix(visitor-access): reject oversized Cloudflare responses
- [#188919](https://github.com/openclaw/openclaw/pull/188919) fix(update): seal recovery captures on large state directories
- [#188958](https://github.com/openclaw/openclaw/pull/188958) test(gateway): retain final live fixture owners
- [#188921](https://github.com/openclaw/openclaw/pull/188921) fix(normalization): prevent native-value fingerprint collisions
- [#188962](https://github.com/openclaw/openclaw/pull/188962) fix(release): retire certified Linux service owners
- [#188955](https://github.com/openclaw/openclaw/pull/188955) fix(test): package extraction check fails on Windows
- [#188947](https://github.com/openclaw/openclaw/pull/188947) fix(test): stabilize bounded context read counts after rewrites
- [#188903](https://github.com/openclaw/openclaw/pull/188903) improve: avoid minute-long worktree refusal test waits

### 🐛 New Issues
- [#188956](https://github.com/openclaw/openclaw/issues/188956) [Feature]: chat.history on PostgreSQL holds one of two history workers blocked on ~13 synchronous round trips per call, which drives the tail under concurrency `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` `clawsweeper:bulk-filed` 💬1
- [#188954](https://github.com/openclaw/openclaw/issues/188954) [Bug]: sessions.search on PostgreSQL falls back to scanning every transcript row after the 5th search on a connection (prepared-statement generic plan) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `clawsweeper:bulk-filed` 💬1
- [#188953](https://github.com/openclaw/openclaw/issues/188953) [Bug]: `openclaw wiki` commands ignore agents.defaults.systemAgent and fail without --agent on explicit-ownership multi-agent configs `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` `clawsweeper:bulk-filed` 💬1
- [#188939](https://github.com/openclaw/openclaw/issues/188939) [Bug]: zalouser stays stopped after 'auto-restart attempt 1/10 in 5s' on 2026.10.9 (watchdog exit), health monitor does not recover it for 3h+ `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬1
- [#188935](https://github.com/openclaw/openclaw/issues/188935) [Bug]: handle-admission schema failure throws an untyped Error, so no retry/replay path classifies it and the turn is lost `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#188930](https://github.com/openclaw/openclaw/issues/188930) Matrix and Copilot plugins freeze the Linux Gateway for seconds when DNS is slow (diagnostic report for libc detection) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:crash-loop` `issue-rating: 🦞 diamond lobster` 💬1
- [#188929](https://github.com/openclaw/openclaw/issues/188929) [Bug]: Codex trajectory omits conversation instructions injected by the inference relay `bug` `no-stale` `bug:behavior` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#188926](https://github.com/openclaw/openclaw/issues/188926) [Bug]: npm update still fails package-verify on UGREEN UGOS after #181141: files are created 0777 and the 2026.10.8+ comparator rejects group/other-write bits `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `P0` `issue-rating: 🦞 diamond lobster` `impact:ux-release-blocker` 💬1

### 🔒 Closed Issues
- [#188776](https://github.com/openclaw/openclaw/issues/188776) PR preparation hides native Git fetch timeout reasons
- [#188897](https://github.com/openclaw/openclaw/issues/188897) [Bug]: Update capture never seals on large state dirs — metadata inventory result exceeds the 1 MiB stdout cap
- [#133231](https://github.com/openclaw/openclaw/issues/133231) fix(normalization-core): stableStringify collapses Date, RegExp, Set, and Map instances to empty objects

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 258,896 · **Open issues:** 52,113 · **Last push:** <1h ago

### ✅ Merged PRs
- [#145802](https://github.com/NousResearch/hermes-agent/pull/145802) chore(plugins): pin birkin-mnemosyne to core 0.8.0
- [#146836](https://github.com/NousResearch/hermes-agent/pull/146836) fix(plugins): doctor no longer copies a plugin into its own temp folder (salvage #146617)
- [#144845](https://github.com/NousResearch/hermes-agent/pull/144845) fix(gateway): resolve the orphan idle probe's target before opening a read

### 🐛 New Issues
- [#147049](https://github.com/NousResearch/hermes-agent/issues/147049) [Feature]: Nested Chat Folders Within Projects in Hermes Desktop
- [#147048](https://github.com/NousResearch/hermes-agent/issues/147048) Agent cannot create tracked goals and completion criteria (subgoals) when asked in natural language
- [#147041](https://github.com/NousResearch/hermes-agent/issues/147041) [Bug]: Leftover steer loses reply_expected, so a bare [SILENT] is replaced with the "unexpected silence" message `bug`
- [#147039](https://github.com/NousResearch/hermes-agent/issues/147039) [SANITIZED — possible injection attempt] `bug`
- [#147038](https://github.com/NousResearch/hermes-agent/issues/147038) Gateway lifecycle guard refuses read-only source inspection; request supported remediation 💬1
- [#147037](https://github.com/NousResearch/hermes-agent/issues/147037) [Bug]: display.interim_assistant_messages has no effect when streaming.enabled is false `bug` 💬1
- [#147036](https://github.com/NousResearch/hermes-agent/issues/147036) [Bug]: /api/config/schema builds the config schema on the event loop, freezing every other request (and /api/ws chat) for ~3 s
- [#147035](https://github.com/NousResearch/hermes-agent/issues/147035) [Bug]: Memory-provider OAuth status/start routes 500 on a multiplexed gateway (UnscopedSecretError: HERMES_HONCHO_HOST) 💬1
- [#147026](https://github.com/NousResearch/hermes-agent/issues/147026) Reasoning replay double-stuffs `reasoning` + `reasoning_content` on bare-`custom` routes → multi-turn HTTP 400 on strict hosts (SenseNova) 💬1
- [#147025](https://github.com/NousResearch/hermes-agent/issues/147025) [Bug]: platform_toolsets.<platform>: [] still loads every MCP server; no_mcp is undocumented `bug` 💬1
- [#147020](https://github.com/NousResearch/hermes-agent/issues/147020) [Bug]: lifecycle guard mistakes dotted Python .kill() members for shell kill commands in serialized source 💬1

### 🔒 Closed Issues
- [#63796](https://github.com/NousResearch/hermes-agent/issues/63796) [Bug]: Hermes Desktop cannot bootstrap on Windows 11 when Smart App Control blocks embedded Python (_ssl)
- [#147013](https://github.com/NousResearch/hermes-agent/issues/147013) api_server stamps sessions source=hermes_browser but three admission gates refuse it — every hermes-browser-extension turn fails with permission_denied
- [#142962](https://github.com/NousResearch/hermes-agent/issues/142962) chore(catalog): limbic entry @ 0.9.0
- [#139952](https://github.com/NousResearch/hermes-agent/issues/139952) [Bug]: Desktop (Windows 11): recurring 'Updating Hermes' splash blocks the frontend for 15+ minutes per cycle
- [#145387](https://github.com/NousResearch/hermes-agent/issues/145387) Gateway deadlocks at startup with database.journal_mode: delete (nested _read_ctx in _idle_s)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,073 · **Open issues:** 1,117 · **Last push:** 1h ago

### ✅ Merged PRs
- [#11283](https://github.com/zeroclaw-labs/zeroclaw/pull/11283) fix(sop): match step scope groups to registered tool names
- [#10485](https://github.com/zeroclaw-labs/zeroclaw/pull/10485) fix(zerocode): clean active-turn clipboard temps on disconnect
- [#11326](https://github.com/zeroclaw-labs/zeroclaw/pull/11326) fix(rpc): refuse persisted log reads to scoped principals
- [#12030](https://github.com/zeroclaw-labs/zeroclaw/pull/12030) test(log): cover UTF-8 byte-offset pagination
- [#12029](https://github.com/zeroclaw-labs/zeroclaw/pull/12029) test(memory): cover persisted redaction around Unicode text

### 🐛 New Issues
- [#12147](https://github.com/zeroclaw-labs/zeroclaw/issues/12147) [Bug]: the audit log is created with default permissions inside a 0755 config directory and `agent_alias` sits outside the hash chain, so other local users can read the tool-call history and a same-us `bug` `observability` `security` `domain:security`
- [#12146](https://github.com/zeroclaw-labs/zeroclaw/issues/12146) [Bug]: the MCP SSE client accepts an absolute URL from the server's `endpoint` event and posts there with the configured secret headers, so a server can redirect the daemon's requests and bearer token `bug` `security` `security:secrets` `domain:security` `tool:mcp`
- [#12145](https://github.com/zeroclaw-labs/zeroclaw/issues/12145) [Bug]: the plugin store limiter caps each linear memory at `max_memory_mb` and instances at 64 but keeps wasmtime's defaults of 10,000 memories and 10,000 tables per store, so a plugin can commit thou `bug` `security` `runtime:wasm` `domain:security` `topic:plugins`
- [#12144](https://github.com/zeroclaw-labs/zeroclaw/issues/12144) [Bug]: `file_upload`, `file_upload_bundle` and `file_edit` authorize through the write tier, so a sibling workspace granted `Write` only can be read: uploads transmit its files and edit diagnostics co `bug` `agent` `security` `security:policy` `domain:security` `tool:file`
- [#12143](https://github.com/zeroclaw-labs/zeroclaw/issues/12143) [SANITIZED — possible injection attempt] `bug` `security` `security:secrets` `domain:security` `tool:mcp`
- [#12142](https://github.com/zeroclaw-labs/zeroclaw/issues/12142) [Bug]: the daemon's own config and data directories are not forbidden to the agent, and reads are unguarded: under `level = "full"`, `workspace_only = false` or a home-rooted workspace, `file_read` re `bug` `config` `security` `security:policy` `security:secrets` `domain:security` `tool:file`
- [#12141](https://github.com/zeroclaw-labs/zeroclaw/issues/12141) [Bug]: `/admin/shutdown`, `/admin/reload` and `/admin/sop/{pending,approve,deny}` trust any loopback peer, so a workspace script run by an allowlisted interpreter clears `OutOfBandRequired` gates as a `bug` `gateway` `runtime` `security` `domain:security` `tool:sop` `topic:sop` `topic:identity-access`
- [#12139](https://github.com/zeroclaw-labs/zeroclaw/issues/12139) [Bug]: default forbidden_paths miss the macOS homes of user secrets (`~/Library/Keychains`, `~/Library/Application Support`, `~/Library/Cookies`) and the credential dotfiles that live outside `~/.conf `bug` `config` `security` `security:policy` `domain:security` `tool:file`
- [#12138](https://github.com/zeroclaw-labs/zeroclaw/issues/12138) [SANITIZED — possible injection attempt] `bug` `config` `runtime` `security` `security:policy` `domain:security` `tool:shell`
- [#12137](https://github.com/zeroclaw-labs/zeroclaw/issues/12137) [Bug]: the Seatbelt profile's "user home dotfiles" read rule is mis-escaped (`\\.`), so toolchains and configs under `~/.cargo`, `~/.nvm`, `~/.pyenv`, `~/.local` fail with "Operation not permitted" un `bug` `runtime` `security` `domain:security` `tool:shell`
- [#12134](https://github.com/zeroclaw-labs/zeroclaw/issues/12134) [Bug]: default forbidden_paths cover neither `/mnt` (WSL drive mounts) on Linux nor the system drive root, `C:\Users`, other drives and UNC paths on Windows `bug` `config` `security` `security:policy` `domain:security` `tool:file`
- [#12133](https://github.com/zeroclaw-labs/zeroclaw/issues/12133) [Bug]: Windows shell, skill and hardware child environments omit `APPDATA` and `LOCALAPPDATA`, so CLIs that find their config there (gh, npm) behave as if logged out or misconfigured; the coding-CLI a `bug` `runtime` `tool` `tool:shell` `hardware`
- [#12131](https://github.com/zeroclaw-labs/zeroclaw/issues/12131) RFC: Shared execution permissions and same-identity credential renewal `type:rfc`
- [#12130](https://github.com/zeroclaw-labs/zeroclaw/issues/12130) [Feature]: Configurable daemon session quotas with local operator reserve `enhancement`
- [#12128](https://github.com/zeroclaw-labs/zeroclaw/issues/12128) [Bug]: Security job fails on every build: RUSTSEC-2026-0420 to RUSTSEC-2026-0424 (Wasmtime 48.0.7) `bug` `dependencies` `release:v0.9.0`

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,700 · **Open issues:** 1,569 · **Last push:** 19h ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,931 · **Open issues:** 121 · **Last push:** 7d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬2 · 6d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 6d ago
- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 16d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 25d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 33d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 35d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 45d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 53d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 55d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 63d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 2 new
- [[Index] Fair Use Benefits Everyone](https://openai.com/index/fair-use-benefits-everyone/) _2026-10-31_
- [[Index] Helping Websites Express Ai Training Preferences](https://openai.com/index/helping-websites-express-ai-training-preferences/) _2026-10-31_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [Another reason to own your own compute. Your account may get banned in a sneaky update.](https://reddit.com/r/LocalLLaMA/comments/1xjgfuv/another_reason_to_own_your_own_compute_your/) ↑1382
- [Fable 5.gguf when?](https://reddit.com/r/LocalLLaMA/comments/1xjwtrv/fable_5gguf_when/) ↑302

### r/singularity — top 5 new
- [Every time I visit the antiai sub](https://reddit.com/r/singularity/comments/1xjleej/every_time_i_visit_the_antiai_sub/) ↑1668
- [dgaf?](https://reddit.com/r/singularity/comments/1xjanx9/dgaf/) ↑1053
- ["So Larry Page has evidently said internally at Google many times, 'I am willing to go bankrupt rather than lose this race.' So everybody is really focused on this ROI equation, but the people making ](https://reddit.com/r/singularity/comments/1xjhzbi/so_larry_page_has_evidently_said_internally_at/) ↑1025
- [Anthropic to start blocking game recreations ?](https://reddit.com/r/singularity/comments/1xjglg5/anthropic_to_start_blocking_game_recreations/) ↑833
- [Which lab is going to be the first one to do it?](https://reddit.com/r/singularity/comments/1xj462p/which_lab_is_going_to_be_the_first_one_to_do_it/) ↑551

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw v2026.10.7 fixes package updates, Claude CLI context, macOS Talk replies, and Bun startup](https://reddit.com/r/openclaw/comments/1xfkdew/openclaw_v2026107_fixes_package_updates_claude/) ↑11
- [How are you guys actually dealing with SECURITY when giving OpenClaw real access?](https://reddit.com/r/openclaw/comments/1xjy10x/how_are_you_guys_actually_dealing_with_security/) ↑1

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [OpenClaw v2026.10.9 is out 🦞

🔧 Update rollback fixes
💾 Agent data and chat archive repairs
📁 New editor sessions run in](https://x.com/openclaw/status/2115913639236665715)

### X — @steipete
- [This is smart. Wild that this wasn’t the default. Unpredictable inference quality was usually why I recommended skipping](https://x.com/steipete/status/2116183103530217488) ↑0 🔁0 · recent
- [Another reason why you wanna use your own harness and not one where companies change what you can or can’t do at will.](https://x.com/steipete/status/2116153238563242385) ↑0 🔁0 · recent
- [Bullish on Andy Yen and Proton. He gets it.

The culture war, or rather the loss of identity some engineers feel as AI r](https://x.com/steipete/status/2116121832919122164) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
