---
layout: post
title: "Ecosystem Digest — 2026-10-07"
date: 2026-10-07 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-07
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 391,522 | 7 | 4 | 10 | 0 |
| **hermesagent** | 251,718 | 11 | 2 | 6 | 0 |
| **ZeroClaw** | 32,937 | 12 | 5 | 10 | 0 |
| **IronClaw** | 12,639 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,883 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 391,522 · **Open issues:** 9,445 · **Last push:** <1h ago

### ✅ Merged PRs
- [#166390](https://github.com/openclaw/openclaw/pull/166390) chore(ui): refresh control ui locales
- [#166361](https://github.com/openclaw/openclaw/pull/166361) fix(models): list standalone models with the catalog owner's plugin registry
- [#161907](https://github.com/openclaw/openclaw/pull/161907) docs: repair section links whose fragments no longer resolve
- [#162110](https://github.com/openclaw/openclaw/pull/162110) fix(browser): ignore extension pages during target enumeration
- [#150593](https://github.com/openclaw/openclaw/pull/150593) docs(google-vertex): document the ADC sentinel credential and required project/location env vars
- [#166338](https://github.com/openclaw/openclaw/pull/166338) fix(models): keep logged-out Claude CLI models listed with a login reason
- [#165432](https://github.com/openclaw/openclaw/pull/165432) fix(gateway): claude-cli session tools fail after the turn that started the MCP loopback ends
- [#166381](https://github.com/openclaw/openclaw/pull/166381) fix(git): expose slow content-read attribution in journal logs
- [#165993](https://github.com/openclaw/openclaw/pull/165993) perf(state): switching between agents reopens agent database executors on every request
- [#166104](https://github.com/openclaw/openclaw/pull/166104) fix: avoid heap-check stalls in busy Bun Gateways

### 🐛 New Issues
- [#166382](https://github.com/openclaw/openclaw/issues/166382) [Bug]: plugin source capture fails with EBADF on Linux reflink filesystems (fs-safe clone:auto returns write-only fd) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#166377](https://github.com/openclaw/openclaw/issues/166377) [Bug]: Package recovery record stuck in `prepared` — `repair` refuses (publication object changed) and `retire` refuses (cannot retire `prepared`) `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `P0` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-release-blocker` 💬1
- [#166369](https://github.com/openclaw/openclaw/issues/166369) [Bug]: sessions.patch lifecycle mutation holders stay in phase run for hours; later patches time out until gateway restart `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `impact:session-state` `impact:crash-loop` `issue-rating: 🦪 silver shellfish` `clawsweeper:bulk-filed` 💬1
- [#166351](https://github.com/openclaw/openclaw/issues/166351) [Bug]: sessions.send runs an undispatched session on the Gateway after sessions.dispatch to an isolation=container node was refused `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1
- [#166350](https://github.com/openclaw/openclaw/issues/166350) Codex native children: define persistent activity in chat history `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1
- [#166349](https://github.com/openclaw/openclaw/issues/166349) Codex native children: define parent wake and restart recovery semantics `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-info` `impact:session-state` `impact:message-loss` `issue-rating: 🦪 silver shellfish` 💬1
- [#166336](https://github.com/openclaw/openclaw/issues/166336) Agent `automations` tool silently vanishes org-wide mid-session — run-level cron creator authority resolves falsy for every session (worker_turn_tool_authorities empty), persists across cold restarts, `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1

### 🔒 Closed Issues
- [#143764](https://github.com/openclaw/openclaw/issues/143764) [Docs Bug]: Vertex ADC path requires the literal credential value "gcp-vertex-credentials", undocumented
- [#164672](https://github.com/openclaw/openclaw/issues/164672) [Bug]: npm update aborts at package-swap with "Package publication object has an unsafe identity" when the Node prefix bin/ and lib/node_modules are owned by another uid (nvm installed as root)
- [#157126](https://github.com/openclaw/openclaw/issues/157126) [Bug]: claude-cli MCP bridge inherits the request scope that first started it; after a restart-recovery run, owner turns lose operator.admin
- [#154630](https://github.com/openclaw/openclaw/issues/154630) Bug: Gateway restart fails with version mismatch error after upgrade

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 251,718 · **Open issues:** 47,734 · **Last push:** <1h ago

### ✅ Merged PRs
- [#128515](https://github.com/NousResearch/hermes-agent/pull/128515) test(desktop): pin one backend per host across reconnect storms and the orphan reap (#81275)
- [#134157](https://github.com/NousResearch/hermes-agent/pull/134157) fix(agent): a credit-limited 402 retries once with the affordable output cap instead of failing as billing
- [#130430](https://github.com/NousResearch/hermes-agent/pull/130430) Windows: PM no longer fails on store paths over 260 characters (#130232, #130242)
- [#134248](https://github.com/NousResearch/hermes-agent/pull/134248) CI runs the update E2Es when a package __init__ on the update path changes
- [#134242](https://github.com/NousResearch/hermes-agent/pull/134242) hermes update from v2026.9.24 no longer crashes on local_runtime's gpu_class import
- [#134165](https://github.com/NousResearch/hermes-agent/pull/134165) test(update): a failed pause-record test no longer orphans its draining gateway

### 🐛 New Issues
- [#134275](https://github.com/NousResearch/hermes-agent/issues/134275) feat(cli): doctor/sessions health check for state.db: snapshot-based probe, FTS integrity-check, scheduled last-good snapshots `type/feature` `comp/cli` `P3` `needs-decision` `sweeper:risk-session-state` `area/sessions` 💬1
- [#134268](https://github.com/NousResearch/hermes-agent/issues/134268) [Bug]: Desktop hand-off exports the wrong pid as HERMES_UPDATE_HANDOFF_PID — every desktop-initiated update self-blocks with exit 2 `type/bug` `comp/cli` `P2` `sweeper:risk-compatibility` `comp/desktop` `area/install-update`
- [#134265](https://github.com/NousResearch/hermes-agent/issues/134265) bug(pm/matrix): Matrix extra gated to sys_platform == 'linux' breaks unencrypted Matrix on macOS on every hermes update `type/bug` `duplicate` `comp/cli` `comp/plugins` `platform/matrix` `area/config` `P2` `sweeper:risk-compatibility` `area/install-update` 💬1
- [#134264](https://github.com/NousResearch/hermes-agent/issues/134264) [Bug]: Docker backend on a Windows host: sandbox paths (/workspace/...) never map to host files, so files made in the sandbox cannot be delivered `type/bug` `comp/gateway` `backend/docker` `P2` `sweeper:risk-message-delivery` `sweeper:risk-platform-windows` `platform/windows` `bug`
- [#134261](https://github.com/NousResearch/hermes-agent/issues/134261) [Bug]: DeepSeek content-moderation 400 ("Content Exists Risk") on a >50-message gateway session is misclassified as context overflow — turn not persisted, session wedges until /reset `type/bug` `comp/gateway` `provider/deepseek` `P1` `sweeper:risk-session-state` `sweeper:risk-message-delivery` `area/sessions`
- [#134258](https://github.com/NousResearch/hermes-agent/issues/134258) [Bug]: Discord /model provider selection times out due to duplicate select option value `type/bug` `comp/plugins` `platform/discord` `P3`
- [#134257](https://github.com/NousResearch/hermes-agent/issues/134257) [Bug]: /reasoning --global with no level errors instead of opening the picker (unlike /model --global) `type/bug` `comp/gateway` `platform/telegram` `area/config` `P2` `sweeper:risk-compatibility` 💬2
- [#134253](https://github.com/NousResearch/hermes-agent/issues/134253) Upstream lockfile bump request: npm vulnerabilities in agent-browser, web, and ui-tui workspaces `duplicate` `type/security` `comp/tui` `tool/browser` `P3` `needs-repro` `comp/dashboard`
- [#134252](https://github.com/NousResearch/hermes-agent/issues/134252) Run LLM middleware for auxiliary client calls `type/feature` `comp/agent` `comp/plugins` `P3`
- [#134251](https://github.com/NousResearch/hermes-agent/issues/134251) Allow execution middleware to deny a call (fail-open prevents spend guards) `duplicate` `type/feature` `comp/agent` `comp/cli` `comp/plugins` `P3` 💬1
- [#134250](https://github.com/NousResearch/hermes-agent/issues/134250) Let transform_llm_output hooks chain instead of first-wins `type/feature` `comp/agent` `comp/plugins` `P3`

### 🔒 Closed Issues
- [#49769](https://github.com/NousResearch/hermes-agent/issues/49769) Recoverable 402 ("can only afford N tokens") is treated as terminal billing and drops the request
- [#130232](https://github.com/NousResearch/hermes-agent/issues/130232) Windows: plugin enable fails when PM copies the bundled Python tree past MAX_PATH (WinError 3)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,937 · **Open issues:** 944 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11509](https://github.com/zeroclaw-labs/zeroclaw/pull/11509) feat(channels): prefer attachments for large generated artifacts
- [#11451](https://github.com/zeroclaw-labs/zeroclaw/pull/11451) fix(secrets): protect Windows key files at creation
- [#11132](https://github.com/zeroclaw-labs/zeroclaw/pull/11132) feat(runtime): turn parity over RPC for steering, totals, and session ops
- [#11574](https://github.com/zeroclaw-labs/zeroclaw/pull/11574) docs(pr-template): keep labels in GitHub metadata
- [#11499](https://github.com/zeroclaw-labs/zeroclaw/pull/11499) fix(security): report Seatbelt initialization during registry construction
- [#10911](https://github.com/zeroclaw-labs/zeroclaw/pull/10911) feat(config): publish atomic live revisions
- [#11503](https://github.com/zeroclaw-labs/zeroclaw/pull/11503) refactor(zerocode): isolate context menu logic
- [#10938](https://github.com/zeroclaw-labs/zeroclaw/pull/10938) fix(tools): declare tool attachments explicitly instead of scanning tool text for image markers
- [#11292](https://github.com/zeroclaw-labs/zeroclaw/pull/11292) feat(runtime): report live progress for running background delegates
- [#11458](https://github.com/zeroclaw-labs/zeroclaw/pull/11458) fix(memory): harden audit hygiene SQLite admission

### 🐛 New Issues
- [#11586](https://github.com/zeroclaw-labs/zeroclaw/issues/11586) [Bug]: ZeroCode sidebar turns failed sessions green after the daemon restarts `bug`
- [#11585](https://github.com/zeroclaw-labs/zeroclaw/issues/11585) [SANITIZED — possible injection attempt] `bug`
- [#11583](https://github.com/zeroclaw-labs/zeroclaw/issues/11583) feat(providers): add Opper as a typed OpenAI-compatible provider `enhancement`
- [#11580](https://github.com/zeroclaw-labs/zeroclaw/issues/11580) [Task]: x86_64 Linux release binary is about 0.7 MB under the 64 MiB size cap
- [#11579](https://github.com/zeroclaw-labs/zeroclaw/issues/11579) [Bug]: save_dirty stamps schema_version = 3 on an unmigrated V1/V2 config, so the next load skips migration and the agent disappears
- [#11570](https://github.com/zeroclaw-labs/zeroclaw/issues/11570) [Feature]: Translate the shared authorization validators' refusals for CLI output `enhancement`
- [#11569](https://github.com/zeroclaw-labs/zeroclaw/issues/11569) [Feature]: Scoped service identity for the standalone gateway's daemon connection `enhancement`
- [#11568](https://github.com/zeroclaw-labs/zeroclaw/issues/11568) [Feature]: Leave one standalone gateway path for /plugin/{path} `enhancement`
- [#11567](https://github.com/zeroclaw-labs/zeroclaw/issues/11567) [Feature]: State plugin-webhook/dispatch wire bounds in the OpenRPC schema `enhancement`
- [#11566](https://github.com/zeroclaw-labs/zeroclaw/issues/11566) [Feature]: One local-only gate for RPC methods, published in the OpenRPC document `enhancement`
- [#11565](https://github.com/zeroclaw-labs/zeroclaw/issues/11565) [Feature]: Give each plugin channel instance its own share of the webhook dedup budget `enhancement`
- [#11562](https://github.com/zeroclaw-labs/zeroclaw/issues/11562) [Bug]: discovery can pair one generation's manifest with another's component during plugin update

### 🔒 Closed Issues
- [#9460](https://github.com/zeroclaw-labs/zeroclaw/issues/9460) feat(secrets): harden Windows key-file ACLs at creation
- [#8527](https://github.com/zeroclaw-labs/zeroclaw/issues/8527) [Feature]: Route large generated files through channel attachments
- [#10536](https://github.com/zeroclaw-labs/zeroclaw/issues/10536) [Bug]: macOS Seatbelt ignores configured allowed_roots for shell commands
- [#10908](https://github.com/zeroclaw-labs/zeroclaw/issues/10908) [Bug]: Image markers in tool-result text are promoted to attachments without provenance; literal source and log text is stripped or attached
- [#10912](https://github.com/zeroclaw-labs/zeroclaw/issues/10912) [Bug]: Streaming text guard suppresses whole replies when prose quotes a tool-result-shaped object; three retries then a generic format error

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,639 · **Open issues:** 1,544 · **Last push:** 2d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,883 · **Open issues:** 106 · **Last push:** 14d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 1d ago
- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 3d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 9d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 11d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 21d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 29d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 31d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 39d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 43d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 55d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 2 new
- [[Legal] Startup Program Addendum](https://www.anthropic.com/legal/startup-program-addendum) _2026-10-06_
- [[News] Cyber Verification Program](https://www.anthropic.com/news/cyber-verification-program) _2026-10-06_

### OpenAI — 4 new
- [[Form] Computer Use Research Collaboration](https://openai.com/form/computer-use-research-collaboration/) _2026-10-07_
- [[Index] Jump Trading](https://openai.com/index/jump-trading/) _2026-10-07_
- [[Learn] Board Guide Cybersecurity Ai](https://openai.com/business/learn/board-guide-cybersecurity-ai/) _2026-10-06_
- [[Index] Atlassian Partnership](https://openai.com/index/atlassian-partnership/) _2026-10-06_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [54gb vram for 35$](https://reddit.com/r/LocalLLaMA/comments/1wz6ist/54gb_vram_for_35/) ↑943
- [Microsoft confirms OpenAI has been using Looped Transformers in the GPT-6 series](https://reddit.com/r/LocalLLaMA/comments/1wz00vv/microsoft_confirms_openai_has_been_using_looped/) ↑875
- [Woman used claude as her diary - and got reported to the police for contents of her diary](https://reddit.com/r/LocalLLaMA/comments/1wz5b30/woman_used_claude_as_her_diary_and_got_reported/) ↑539
- [Qwen 4 apparently coming out at the end of October](https://reddit.com/r/LocalLLaMA/comments/1wz1pqn/qwen_4_apparently_coming_out_at_the_end_of_october/) ↑488
- [google/embeddinggemma-2 · Hugging Face](https://reddit.com/r/LocalLLaMA/comments/1wz5va3/googleembeddinggemma2_hugging_face/) ↑364

### r/singularity — top 5 new
- [Microsoft has accidentally revealed GPT-6.1 Sol uses the same base weights as GPT-6 Sol, but with only 2 inference passes instead of 3.](https://reddit.com/r/singularity/comments/1wyu0ss/microsoft_has_accidentally_revealed_gpt61_sol/) ↑673
- [LE CHATON FAT IS REAL](https://reddit.com/r/singularity/comments/1wz2r59/le_chaton_fat_is_real/) ↑635
- [Sharing AI progress in mathematics](https://reddit.com/r/singularity/comments/1wzg6bt/sharing_ai_progress_in_mathematics/) ↑577
- [Europe finally takes the lead](https://reddit.com/r/singularity/comments/1wze844/europe_finally_takes_the_lead/) ↑484
- [Le chonk official launch video](https://reddit.com/r/singularity/comments/1wz9xy6/le_chonk_official_launch_video/) ↑363

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Best free web search provider?](https://reddit.com/r/openclaw/comments/1wyxgkq/best_free_web_search_provider/) ↑17
- [Still Running v2026.3.1](https://reddit.com/r/openclaw/comments/1wzdr50/still_running_v202631/) ↑5
- [Convince me to update - or not](https://reddit.com/r/openclaw/comments/1wxo84y/convince_me_to_update_or_not/) ↑5
- [Show off your Openclaw agent](https://reddit.com/r/openclaw/comments/1wyvva5/show_off_your_openclaw_agent/) ↑4
- [WhatsApp replies replaced by "I couldn't confirm whether my previous reply reached this chat" since 2026.9.7 (still on 9.8) - anyone found a fix?](https://reddit.com/r/openclaw/comments/1wy9uvn/whatsapp_replies_replaced_by_i_couldnt_confirm/) ↑4

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [OpenClaw v2026.9.8 is out, and this one's a fun-sized lobster 🦞

🧠 GPT-6.1 Sol support
💬 Agent replies find their way ba](https://x.com/openclaw/status/2106247624634531889)

### X — @steipete
_No new tweets since the last digest. Most recent:_
- [bug fixes & performance improvements](https://x.com/steipete/status/2106796559400882209)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
