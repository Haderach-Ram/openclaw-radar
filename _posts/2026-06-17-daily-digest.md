---
layout: post
title: "Ecosystem Digest — 2026-06-17"
date: 2026-06-17 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-17
*Generated 07:49 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 379,061 | 4 | 4 | 10 | 2 |
| **hermesagent** | 195,418 | 7 | 4 | 6 | 0 |
| **ZeroClaw** | 31,927 | 15 | 5 | 10 | 0 |
| **IronClaw** | 12,456 | 15 | 9 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 379,061 · **Open issues:** 6,218 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.8](https://github.com/openclaw/openclaw/releases/tag/v2026.6.8) — openclaw 2026.6.8
- [v2026.6.8-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.6.8-beta.2) — openclaw 2026.6.8-beta.2

### ✅ Merged PRs
- [#93806](https://github.com/openclaw/openclaw/pull/93806) fix(reasoning-tags): strip MiniMax mm: tags on silent-reply and streaming paths missed by #93767
- [#93691](https://github.com/openclaw/openclaw/pull/93691) refactor: add gateway sessions.create lifecycle seam
- [#93797](https://github.com/openclaw/openclaw/pull/93797) fix(browser): use openTab return value to prevent wsUrl race in ensureTabAvailable (fixes #63343)
- [#93796](https://github.com/openclaw/openclaw/pull/93796) fix(feishu): paginate wiki node and space listing (#37626)
- [#93792](https://github.com/openclaw/openclaw/pull/93792) fix(android): wait for node capability approval before onboarding
- [#93803](https://github.com/openclaw/openclaw/pull/93803) fix(ui): preserve WebChat visible messages across session switches
- [#93810](https://github.com/openclaw/openclaw/pull/93810) fix(cron): preserve startup overflow catch-up deferrals in start() maintenance pass
- [#93811](https://github.com/openclaw/openclaw/pull/93811) Strip UTF-8 BOM when reading SKILL.md in quick_validate
- [#93716](https://github.com/openclaw/openclaw/pull/93716) fix(discord): propagate timeout through channel capabilities diagnostics
- [#93726](https://github.com/openclaw/openclaw/pull/93726) fix(typing): start typing on reasoning deltas in thinking mode before visible text

### 🐛 New Issues
- [#93858](https://github.com/openclaw/openclaw/issues/93858) fix(auto-reply): defer foreground fence to delivery to prevent interleaving (lazy fence) 💬3
- [#93854](https://github.com/openclaw/openclaw/issues/93854) [Bug] Docker sandbox fails to start with 'Duplicate mount point' when custom binds target reserved paths 💬1
- [#93851](https://github.com/openclaw/openclaw/issues/93851) exec secrets provider: resolver script does not pass BWS_SERVER_URL to child process
- [#93835](https://github.com/openclaw/openclaw/issues/93835) [Bug]: Telegram /think menu shows only off for live-discovered Ollama thinking models, but /think <level> accepts them `bug`

### 🔒 Closed Issues
- [#91016](https://github.com/openclaw/openclaw/issues/91016) ⚠️ 升级 2026.6.1 后 DeepSeek Prompt Cache 完全失效，一小时烧掉约 $6
- [#63343](https://github.com/openclaw/openclaw/issues/63343) Browser bridge: "tab not found" race in ensureTabAvailable when wsUrl lags CDP discovery
- [#37626](https://github.com/openclaw/openclaw/issues/37626) [feishu plugin] wiki spaceNode.list 分页不生效，只返回前20条记录
- [#80855](https://github.com/openclaw/openclaw/issues/80855) [Bug]: # WebChat 会话在切换对话框时被清空

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · <1h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 195,418 · **Open issues:** 21,239 · **Last push:** <1h ago

### ✅ Merged PRs
- [#47131](https://github.com/NousResearch/hermes-agent/pull/47131) fix(cli): detect containerd/CRI cgroup-v2 containers in is_container()
- [#47253](https://github.com/NousResearch/hermes-agent/pull/47253) feat(gateway): optional message timestamps for LLM context
- [#46895](https://github.com/NousResearch/hermes-agent/pull/46895) fix(desktop): open remote-gateway artifacts via authenticated download
- [#47251](https://github.com/NousResearch/hermes-agent/pull/47251) feat(prompt): configurable context-file truncation limit + warnings
- [#47447](https://github.com/NousResearch/hermes-agent/pull/47447) fix(desktop): honor pre-session model pick + restore global reasoning/speed defaults
- [#47276](https://github.com/NousResearch/hermes-agent/pull/47276) fix(desktop): re-download Electron binary via mirror when pack fails (#47266)

### 🐛 New Issues
- [#47557](https://github.com/NousResearch/hermes-agent/issues/47557) [Bug] Windows: scripts/install.ps1 venv recreation fails when pythonw.exe holds .pyd locks — only kills hermes.exe
- [#47549](https://github.com/NousResearch/hermes-agent/issues/47549) [Bug]: Desktop "New profile" dialog shows raw IPC error for reserved names (e.g. 'test', 'sudo') `type/bug` `comp/tui` `P3`
- [#47548](https://github.com/NousResearch/hermes-agent/issues/47548) [Feature Request] Hermes Studio Desktop: 为 provider 设置添加多 API Key / 凭证池管理界面 `type/feature` `comp/tui` `P3`
- [#47541](https://github.com/NousResearch/hermes-agent/issues/47541) Would you accept empty-by-default observer seams for an out-of-tree multi-client plugin? `type/feature` `comp/gateway` `P3`
- [#47539](https://github.com/NousResearch/hermes-agent/issues/47539) Telegram typing indicator stuck infinitely (orphaned _keep_typing task) `type/bug` `duplicate` `comp/gateway` `platform/telegram` `P2` 💬1
- [#47534](https://github.com/NousResearch/hermes-agent/issues/47534) [Feature]: Cost & usage visibility / provider/routing UX `type/feature` `comp/agent` `P3`
- [#47527](https://github.com/NousResearch/hermes-agent/issues/47527) fix(openviking): v0.4.1 compatibility - auth headers and search limit `type/bug` `comp/plugins` `tool/memory` `P3`

### 🔒 Closed Issues
- [#47111](https://github.com/NousResearch/hermes-agent/issues/47111) is_container() misses containerd + cgroup v2 (k8s/k3s) → s6 gateway supervision silently disabled → gateway double-start crash loop
- [#47529](https://github.com/NousResearch/hermes-agent/issues/47529) [Feature]: Slack: render clarify choices as Block Kit buttons (counterpart to Discord #19111)
- [#47513](https://github.com/NousResearch/hermes-agent/issues/47513) [Feature]: Slack: render clarify choices as Block Kit buttons (counterpart to Discord #19111)
- [#47360](https://github.com/NousResearch/hermes-agent/issues/47360) [Bug]: Discord gateway connects successfully but never receives MESSAGE_CREATE events (on_message never fires)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,927 · **Open issues:** 400 · **Last push:** <1h ago

### ✅ Merged PRs
- [#7717](https://github.com/zeroclaw-labs/zeroclaw/pull/7717) fix(tools): encode weather location path input
- [#7719](https://github.com/zeroclaw-labs/zeroclaw/pull/7719) test(gateway): cover public event history filtering
- [#7704](https://github.com/zeroclaw-labs/zeroclaw/pull/7704) fix(memory): disable hot response cache at zero capacity
- [#7788](https://github.com/zeroclaw-labs/zeroclaw/pull/7788) docs(contributing): add first-party extension architecture guide
- [#7677](https://github.com/zeroclaw-labs/zeroclaw/pull/7677) test(runtime): cover RPC approval lifecycle cleanup
- [#7656](https://github.com/zeroclaw-labs/zeroclaw/pull/7656) fix(memory): include recall windows in retrieval cache key
- [#7767](https://github.com/zeroclaw-labs/zeroclaw/pull/7767) fix(channels/email): stabilize missing message ids
- [#7773](https://github.com/zeroclaw-labs/zeroclaw/pull/7773) fix(runtime): route native tool narration to stderr
- [#7792](https://github.com/zeroclaw-labs/zeroclaw/pull/7792) fix(runtime): resolve runtime profiles for direct turns
- [#7812](https://github.com/zeroclaw-labs/zeroclaw/pull/7812) fix(ci): narrow Kilo provider path label

### 🐛 New Issues
- [#7820](https://github.com/zeroclaw-labs/zeroclaw/issues/7820) Zeroclaw repeats identical shell approval loops before bounding
- [#7816](https://github.com/zeroclaw-labs/zeroclaw/issues/7816) [Feature]: Pluggable skill registries — keep GitHub repo as default tier, add flagged external + user-configured registries `enhancement` `risk: high` `config` `runtime` `security` `skillforge` `skills` `priority:p2`
- [#7815](https://github.com/zeroclaw-labs/zeroclaw/issues/7815) [Bug]: ZeroCode Config does not show which config source/state it is editing `bug` `risk: medium` `config` `priority:p2` `zerocode`
- [#7814](https://github.com/zeroclaw-labs/zeroclaw/issues/7814) [Bug]: ZeroCode config fields look editable before Enter activates editing `bug` `risk: medium` `config` `priority:p2` `zerocode`
- [#7810](https://github.com/zeroclaw-labs/zeroclaw/issues/7810) [Bug]: git_operations gives no recovery hint outside a repository `bug` `risk: high` `tool` `tool: git_operations` `priority:p2`
- [#7809](https://github.com/zeroclaw-labs/zeroclaw/issues/7809) [Bug]: Channel turns ignore runtime-profile strict/parallel tool flags `bug` `risk: high` `channel` `config` `runtime` `priority:p1`
- [#7808](https://github.com/zeroclaw-labs/zeroclaw/issues/7808) [Bug]: CLI secret prompts give no feedback after paste `bug` `risk: medium` `core` `config` `priority:p2`
- [#7807](https://github.com/zeroclaw-labs/zeroclaw/issues/7807) [Bug]: Approval overlay can inherit terminal background instead of ZeroCode theme `bug` `risk: medium` `priority:p2` `zerocode`
- [#7805](https://github.com/zeroclaw-labs/zeroclaw/issues/7805) [Bug]: Cancelled Code turns can show queue-paused hint with an empty queue `bug` `risk: medium` `priority:p3` `zerocode`
- [#7804](https://github.com/zeroclaw-labs/zeroclaw/issues/7804) [Bug]: Code history can send non-alternating Anthropic messages `bug` `risk: high` `provider` `runtime` `provider:anthropic` `priority:p1`
- [#7803](https://github.com/zeroclaw-labs/zeroclaw/issues/7803) [Bug]: Active Code sessions cannot switch agents directly `bug` `risk: medium` `agent` `priority:p2` `zerocode`
- [#7800](https://github.com/zeroclaw-labs/zeroclaw/issues/7800) [Bug]: Code help/keybindings are misleading or unreachable, especially on macOS `bug` `risk: medium` `priority:p2` `zerocode`
- [#7799](https://github.com/zeroclaw-labs/zeroclaw/issues/7799) [Bug]: Resumed Code sessions reopen with a blank transcript `bug` `risk: high` `runtime` `priority:p1` `zerocode`
- [#7795](https://github.com/zeroclaw-labs/zeroclaw/issues/7795) static_voice_peers caches config-derived voice peers on the channel handle (latent SSOT violation) `bug` `risk: high` `channel` `config` `channel:telegram` `priority:p2`
- [#7794](https://github.com/zeroclaw-labs/zeroclaw/issues/7794) [Feature]: Per-agent opt-in Dream Mode + action-surface parity (chat command, gateway Dreams view) `enhancement` `risk: high` `agent` `config` `daemon` `memory` `runtime` `priority:p2` `status:in-progress`

### 🔒 Closed Issues
- [#7729](https://github.com/zeroclaw-labs/zeroclaw/issues/7729) test(runtime): cover RPC approval lifecycle cleanup
- [#7728](https://github.com/zeroclaw-labs/zeroclaw/issues/7728) bug(memory): prevent retrieval cache reuse across recall windows
- [#7796](https://github.com/zeroclaw-labs/zeroclaw/issues/7796) [Bug]: Direct agent turns ignore runtime-profile max_tool_iterations
- [#7738](https://github.com/zeroclaw-labs/zeroclaw/issues/7738) bug(channels/email): use stable UID fallback when Message-ID is missing
- [#6856](https://github.com/zeroclaw-labs/zeroclaw/issues/6856) [Bug]: show_tool_calls is missing from [channel]

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,456 · **Open issues:** 1,193 · **Last push:** <1h ago

### ✅ Merged PRs
- [#4902](https://github.com/nearai/ironclaw/pull/4902) feat(openai-compat): vision support for inline images (#4644)
- [#4858](https://github.com/nearai/ironclaw/pull/4858) fix(reborn): show sanitized command details
- [#4995](https://github.com/nearai/ironclaw/pull/4995) feat(bench): forward NEARAI_API_KEY so /benchmark reborn runs use NEAR cloud
- [#4954](https://github.com/nearai/ironclaw/pull/4954) fix(reborn): surface approval-gate denial to model instead of cancelling the run
- [#4933](https://github.com/nearai/ironclaw/pull/4933) feat(reborn): downloadable project files in WebChat v2
- [#4957](https://github.com/nearai/ironclaw/pull/4957) fix(webui): avoid token prompt for OAuth auth gates
- [#4962](https://github.com/nearai/ironclaw/pull/4962) fix(reborn): show friendly Google OAuth scope failure
- [#4964](https://github.com/nearai/ironclaw/pull/4964) fix(webui): keep extension cards natural height
- [#4956](https://github.com/nearai/ironclaw/pull/4956) fix(reborn): Automations/Inference/chat UI bug fixes + Automations i18n completion
- [#4973](https://github.com/nearai/ironclaw/pull/4973) fix(reborn): recover tool input/output on every terminal run

### 🐛 New Issues
- [#5007](https://github.com/nearai/ironclaw/issues/5007) [Reborn] Skills validation error does not clear after required fields are filled
- [#5006](https://github.com/nearai/ironclaw/issues/5006) [Reborn] Skills Findings 06/15/2026 - 06/21/2026
- [#5005](https://github.com/nearai/ironclaw/issues/5005)  [Reborn] Automations page provides status views but no management actions
- [#5004](https://github.com/nearai/ironclaw/issues/5004) [Reborn] Automations Failure summary card is not actionable
- [#4999](https://github.com/nearai/ironclaw/issues/4999) Scale google-drive download_file extraction beyond the 1 MB WASM round-trip cap
- [#4992](https://github.com/nearai/ironclaw/issues/4992) [Reborn] Local-dev SSO access mismatch can make Railway automations fail before run/thread creation `bug` `risk: medium` `scope: channel/web` `scope: db/libsql` `scope: worker` `reborn` `OAuth / Authorization`
- [#4991](https://github.com/nearai/ironclaw/issues/4991) WASM google-drive auth failures dead-end as operation_failed without refresh-retry or AuthRequired gate
- [#4988](https://github.com/nearai/ironclaw/issues/4988) [Reborn] Recent runs visualization is difficult to understand `UX / Onboarding`
- [#4987](https://github.com/nearai/ironclaw/issues/4987) [Reborn] Automation run threads are difficult to discover when user approval is required
- [#4986](https://github.com/nearai/ironclaw/issues/4986) [Reborn] Recurring automation can become permanently blocked waiting for tool approval `bug` 💬1
- [#4985](https://github.com/nearai/ironclaw/issues/4985) Engine V2: persist LLM usage so /api/admin/usage returns data
- [#4983](https://github.com/nearai/ironclaw/issues/4983) Remove NEAR AI tool-message flattening compatibility path
- [#4982](https://github.com/nearai/ironclaw/issues/4982) [Reborn] Automation row selection area is unexpectedly limited `UX / Onboarding`
- [#4981](https://github.com/nearai/ironclaw/issues/4981) [Reborn] Dashboard status badges are confusing and appear unrelated to automation state `UX / Onboarding`
- [#4980](https://github.com/nearai/ironclaw/issues/4980) [Reborn] Automations empty state does not explain how to create automations `UX / Onboarding`

### 🔒 Closed Issues
- [#2721](https://github.com/nearai/ironclaw/issues/2721) Engine V2 quality: Milestone 0 + multi-route execution
- [#2725](https://github.com/nearai/ironclaw/issues/2725) Milestone 0: evaluate orchestrator-first sprint and decide next step
- [#2724](https://github.com/nearai/ironclaw/issues/2724) Milestone 0: tighten CodeAct prompt for simple-task behavior and finalization
- [#2723](https://github.com/nearai/ironclaw/issues/2723) Milestone 0: tighten orchestrator loop behavior in default.py
- [#4852](https://github.com/nearai/ironclaw/issues/4852) [Reborn] Shell command is not visible in approval dialog or Activity history
- [#4884](https://github.com/nearai/ironclaw/issues/4884) [Reborn] Google Calendar auth prompt requests access token instead of guiding users through OAuth flow
- [#4914](https://github.com/nearai/ironclaw/issues/4914) [Reborn] Gmail OAuth with no selected scopes returns raw malformed_callback error
- [#4926](https://github.com/nearai/ironclaw/issues/4926) [Reborn] Expanding capabilities stretches all cards in the same row
- [#4823](https://github.com/nearai/ironclaw/issues/4823) [Reborn] No UI feedback when deleting a running conversation fails

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#93032](https://github.com/openclaw/openclaw/issues/93032) [Bug] v2026.6.6: Cron scheduler loads 0 jobs after upgrade — SQLite WAL not committed at first startup — 💬2 · 1d ago
- 🟢 [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 1d ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 1d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬5 · 1d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬1 · 1d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 1d ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬1 · 1d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 2d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 2d ago
- ⚫ [#92974](https://github.com/openclaw/openclaw/issues/92974) Bug: v2026.6.6 getAttributionHeaders() crashes on Bedrock models — baseUrl undefined (null-guard missing) — 💬1 · 2d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Donate your coding sessions to an open CC-BY-4.0 dataset to help train open-weight and open source models](https://reddit.com/r/LocalLLaMA/comments/1u795pb/donate_your_coding_sessions_to_an_open_ccby40/) ↑1132
- [We should set up a torrent network for open source models.](https://reddit.com/r/LocalLLaMA/comments/1u4gto1/we_should_set_up_a_torrent_network_for_open/) ↑975
- [zai-org/GLM-5.2 is here!](https://reddit.com/r/LocalLLaMA/comments/1u7kcwf/zaiorgglm52_is_here/) ↑682
- [Hashicorp founder thinks local models "aren't good ENOUGH yet"](https://reddit.com/r/LocalLLaMA/comments/1u7nph8/hashicorp_founder_thinks_local_models_arent_good/) ↑385
- [Be wary of Qwen/Claude distillations - they're often worse than the base model](https://reddit.com/r/LocalLLaMA/comments/1u7a2hn/be_wary_of_qwenclaude_distillations_theyre_often/) ↑325

### r/singularity — top 1 new
- ["Anthropic Amendments" Proposed Regarding Export Control Directives](https://reddit.com/r/singularity/comments/1u7s7xu/anthropic_amendments_proposed_regarding_export/) ↑70

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
