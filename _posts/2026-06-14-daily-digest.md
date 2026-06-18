---
title: "Ecosystem Digest — 2026-06-14"
date: 2026-06-14 07:46:00 +0530
categories: [digest]
tags: [digest, daily]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-14
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 378,585 | 6 | 7 | 10 | 2 |
| **hermesagent** | 192,804 | 7 | 4 | 10 | 0 |
| **ZeroClaw** | 31,901 | 2 | 6 | 10 | 0 |
| **IronClaw** | 12,447 | 2 | 0 | 5 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 378,585 · **Open issues:** 7,555 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.8-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.6.8-beta.1) — openclaw 2026.6.8-beta.1
- [v2026.6.7-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.6.7-beta.1) — openclaw 2026.6.7-beta.1

### ✅ Merged PRs
- [#92830](https://github.com/openclaw/openclaw/pull/92830) fix(copilot): strip replayed thinking blocks
- [#90889](https://github.com/openclaw/openclaw/pull/90889) [SANITIZED — possible injection attempt]
- [#92825](https://github.com/openclaw/openclaw/pull/92825) fix(telegram): preserve command callbacks while prefixing generic callback data
- [#92820](https://github.com/openclaw/openclaw/pull/92820) UI: localize Logs tab labels
- [#92746](https://github.com/openclaw/openclaw/pull/92746) fix(gateway): preserve active runs during plugin finalization
- [#92795](https://github.com/openclaw/openclaw/pull/92795) fix(gateway): use resolveNonNegativeNumber for totalTokens to display 0 instead of ? (fixes #43009)
- [#92778](https://github.com/openclaw/openclaw/pull/92778) fix(macos): defer isOverflowing mutation to break SwiftUI render loop (fixes #43480)
- [#92806](https://github.com/openclaw/openclaw/pull/92806) fix(telegram): skip IPv4 fallback when user explicitly configures non-ipv4first dnsResultOrder (fixes #41671)
- [#92690](https://github.com/openclaw/openclaw/pull/92690) fix(doctor): avoid false-positive legacy cron store warning when store was already migrated (fixes #92683)
- [#92745](https://github.com/openclaw/openclaw/pull/92745) fix(memory): explain skipped short-term recall hits

### 🐛 New Issues
- [#92827](https://github.com/openclaw/openclaw/issues/92827) [Bug]: 如果启用沙箱，agent无法将文件发送到webchat和QQBot `bug` `P2` `clawsweeper:needs-live-repro` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬1
- [#92816](https://github.com/openclaw/openclaw/issues/92816) [Bug]: 当tts设置为always时，cron会投递失败，但是结果会显示已投递 `bug` `no-stale` `bug:behavior` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#92808](https://github.com/openclaw/openclaw/issues/92808) [Bug]: Title: Local embedding provider breaks on upgrade (two consecutive releases) — no migration path, misleading error `bug` `regression` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬1
- [#92783](https://github.com/openclaw/openclaw/issues/92783) Scheduled-action force-run / dry-run interface — no way to deterministically exercise a heartbeat/cron job without a live agent turn `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#92777](https://github.com/openclaw/openclaw/issues/92777) [Bug]: TUI: Backspace key stops working after agent response renders (WSL2/Ubuntu) `bug` `bug:behavior` `P1` `clawsweeper:needs-info` `issue-rating: 🦐 gold shrimp` `impact:other` 💬1
- [#92776](https://github.com/openclaw/openclaw/issues/92776) Session model pinning persists indefinitely: snap-back probe (PR #82676) defeated by origin-field pollution upstream — repros on 2026.5.28 through 2026.6.7-beta.1, byte-identical paths `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#81520](https://github.com/openclaw/openclaw/issues/81520) [Bug]: Reasoning model thinking blocks (<thinking> tags) in conversation history cause HTTP 400 on GitHub Copilot provider
- [#39857](https://github.com/openclaw/openclaw/issues/39857) Status/session context window can over-report the selected model's actual window
- [#54909](https://github.com/openclaw/openclaw/issues/54909) [Bug]: Telegram inline button callback_query not routed to agent — hallucination instead of tool call
- [#55044](https://github.com/openclaw/openclaw/issues/55044) [Bug]: ignored an explicit stop/no-action instruction
- [#46938](https://github.com/openclaw/openclaw/issues/46938) 模型超时导致记忆维护失败，建议增加 session 临时存储机制
- [#43009](https://github.com/openclaw/openclaw/issues/43009) TUI displays Context Tokens as ?/200k instead of actual value
- [#43480](https://github.com/openclaw/openclaw/issues/43480) macOS app pinwheels due to SwiftUI infinite render loop in VoiceWakeOverlay

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 2d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 192,804 · **Open issues:** 20,350 · **Last push:** <1h ago

### ✅ Merged PRs
- [#45853](https://github.com/NousResearch/hermes-agent/pull/45853) fix(desktop): surface off-screen approvals via the jump-to-bottom control
- [#45837](https://github.com/NousResearch/hermes-agent/pull/45837) fix(skills): make bundled-update backup handling crash-safe
- [#43852](https://github.com/NousResearch/hermes-agent/pull/43852) fix(utils): EXDEV/EBUSY copy fallback in atomic_replace (port from gemini-cli#21541)
- [#37082](https://github.com/NousResearch/hermes-agent/pull/37082) feat(read): extract .ipynb/.docx/.xlsx to text in read_file
- [#45821](https://github.com/NousResearch/hermes-agent/pull/45821) fix(approval): gate sensitive user-file terminal writes
- [#36142](https://github.com/NousResearch/hermes-agent/pull/36142) Port from nearai/ironclaw#4211: search budget hits become soft truncation
- [#45822](https://github.com/NousResearch/hermes-agent/pull/45822) fix(agent): treat Codex reasoning items as thinking-only
- [#45824](https://github.com/NousResearch/hermes-agent/pull/45824) fix(telegram): harden rich message fallback handling
- [#45812](https://github.com/NousResearch/hermes-agent/pull/45812) [SANITIZED — possible injection attempt]
- [#36141](https://github.com/NousResearch/hermes-agent/pull/36141) fix(gemini): strip self provider prefix before native generateContent

### 🐛 New Issues
- [#45913](https://github.com/NousResearch/hermes-agent/issues/45913) Desktop: 对话框滚动不到底 + 会话大纲点击跳转不准
- [#45912](https://github.com/NousResearch/hermes-agent/issues/45912) [Feature]: Whatsapp/telegram Predefined Keyboard Input
- [#45911](https://github.com/NousResearch/hermes-agent/issues/45911) [Bug]: The rendering of messages in Telegram is off, and not all are consistent.
- [#45908](https://github.com/NousResearch/hermes-agent/issues/45908) anthropic_messages: malformed upstream stream (non-contiguous content_block index) crashes with IndexError and retries 10x
- [#45903](https://github.com/NousResearch/hermes-agent/issues/45903) Discord interactive-view timeout is hardcoded to 300s — make it configurable
- [#45894](https://github.com/NousResearch/hermes-agent/issues/45894) [Bug] Hermes Desktop: right-sidebar file-tree refresh button disappears when cursor moves onto it `type/bug` `comp/tui` `P3`
- [#45893](https://github.com/NousResearch/hermes-agent/issues/45893) Agent misroutes local host paths when Desktop terminal backend is SSH `type/bug` `comp/agent` `comp/tui` `P3`

### 🔒 Closed Issues
- [#501](https://github.com/NousResearch/hermes-agent/issues/501) Feature: Web UI Gateway — Local Browser-Based Interface with Streaming, Artifacts & Rich Rendering
- [#44927](https://github.com/NousResearch/hermes-agent/issues/44927) [Feature]: feat: add back streaming auto-follow as an opt-in setting
- [#44942](https://github.com/NousResearch/hermes-agent/issues/44942) [Bug]: skill-update backup handling can corrupt or silently lose skills (stale/orphaned .bak interactions)
- [#42454](https://github.com/NousResearch/hermes-agent/issues/42454) Photon Issue

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,901 · **Open issues:** 412 · **Last push:** <1h ago

### ✅ Merged PRs
- [#7513](https://github.com/zeroclaw-labs/zeroclaw/pull/7513) fix(quickstart): bail with a clear error on non-TTY stdin
- [#7524](https://github.com/zeroclaw-labs/zeroclaw/pull/7524) feat(channels/discord): derive gateway intents from config instead of hardcoding
- [#7406](https://github.com/zeroclaw-labs/zeroclaw/pull/7406) fix(runtime): suppress skill suggestions for installed tools
- [#6993](https://github.com/zeroclaw-labs/zeroclaw/pull/6993) fix(runtime): clarify peer send targets
- [#7477](https://github.com/zeroclaw-labs/zeroclaw/pull/7477) fix(zerocode): keep Cmd-C separate from quit on macOS
- [#7482](https://github.com/zeroclaw-labs/zeroclaw/pull/7482) fix(zerocode): theme markdown body text
- [#7480](https://github.com/zeroclaw-labs/zeroclaw/pull/7480) fix(tools): localize file download tool strings
- [#7021](https://github.com/zeroclaw-labs/zeroclaw/pull/7021) feat(channels/email): XOAUTH2 auth, observer mode, and read-only IMAP tools
- [#7503](https://github.com/zeroclaw-labs/zeroclaw/pull/7503) fix(docker): add vim-tiny to runtime images for editor support
- [#7448](https://github.com/zeroclaw-labs/zeroclaw/pull/7448) fix(cron): inject Lark and Feishu delivery defaults from chat context (#6880)

### 🐛 New Issues
- [#7577](https://github.com/zeroclaw-labs/zeroclaw/issues/7577) [Bug]: Extra-nested model provider alias tables silently drop fields and pass validation `bug` `risk: medium` `config` `provider` `priority:p2` `status:accepted`
- [#7563](https://github.com/zeroclaw-labs/zeroclaw/issues/7563) [Bug]: canvas-store regression in WS chat/ACP sessions breaks /canvas after #6986 `bug` `risk: high` `agent` `channel` `gateway` `runtime` `gateway: ws` `priority:p1` `status:accepted` `web` 💬1

### 🔒 Closed Issues
- [#7507](https://github.com/zeroclaw-labs/zeroclaw/issues/7507) [Bug]: quickstart infinite redraw loop on non-TTY stdin — flooded 4.3 GB of output instead of erroring
- [#7378](https://github.com/zeroclaw-labs/zeroclaw/issues/7378) [Bug]: zerocode can treat macOS Cmd-C copy as the quit chord
- [#7377](https://github.com/zeroclaw-labs/zeroclaw/issues/7377) [Bug]: zerocode dark themes can inherit unreadable terminal foreground text
- [#6990](https://github.com/zeroclaw-labs/zeroclaw/issues/6990) i18n: bring new file_download tool strings under the fl!() / Fluent contract
- [#7469](https://github.com/zeroclaw-labs/zeroclaw/issues/7469) [Bug]: Default using "vi" but container does not include it
- [#6880](https://github.com/zeroclaw-labs/zeroclaw/issues/6880) fix(cron): inject Lark and Feishu delivery defaults from chat context

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,447 · **Open issues:** 1,159 · **Last push:** <1h ago

### ✅ Merged PRs
- [#4672](https://github.com/nearai/ironclaw/pull/4672) feat(reborn): accept inline attachment uploads on the WebChat v2 send path (#4644)
- [#4670](https://github.com/nearai/ironclaw/pull/4670) feat(attachments): bridge inbound bytes into transcript AttachmentRefs (#4644)
- [#4668](https://github.com/nearai/ironclaw/pull/4668) feat(attachments): MountView-based attachment landing crate (#4644)
- [#4655](https://github.com/nearai/ironclaw/pull/4655) feat(threads): carry attachment refs through the Reborn transcript contract (#4644)
- [#4654](https://github.com/nearai/ironclaw/pull/4654) feat(common): extensible attachment format registry (#4644)

### 🐛 New Issues
- [#4845](https://github.com/nearai/ironclaw/issues/4845) Extract shared resume-authority head across resume_json / auth_resume_json
- [#4108](https://github.com/nearai/ironclaw/issues/4108) Nightly E2E failed

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 8d ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 9d ago
- ⚫ [#88967](https://github.com/openclaw/openclaw/issues/88967) Telegram: allowBots support for group chats (bot-authored messages not ingested into session) — 💬1 · 9d ago
- ⚫ [#88517](https://github.com/openclaw/openclaw/issues/88517) [SANITIZED — possible injection attempt] — 💬3 · 10d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 11d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 11d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬5 · 13d ago
- ⚫ [#86371](https://github.com/openclaw/openclaw/issues/86371) Bug: message tool filePath fails with LocalMediaAccessError in retry flows when agentId is not propagated — 💬1 · 16d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 19d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 32d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

_No new posts in the last 24h._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*