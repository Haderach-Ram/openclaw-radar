---
layout: post
title: "Ecosystem Digest — 2026-11-25"
date: 2026-11-25 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-25
*Generated 07:47 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 395,167 | 12 | 5 | 10 | 3 |
| **hermesagent** | 265,907 | 14 | 3 | 3 | 2 |
| **ZeroClaw** | 33,609 | 6 | 0 | 10 | 0 |
| **IronClaw** | 12,720 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,987 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 395,167 · **Open issues:** 9,144 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.11.10-beta.3](https://github.com/openclaw/openclaw/releases/tag/v2026.11.10-beta.3) — openclaw 2026.11.10-beta.3
- [v2026.11.9](https://github.com/openclaw/openclaw/releases/tag/v2026.11.9) — openclaw 2026.11.9
- [v2026.11.8](https://github.com/openclaw/openclaw/releases/tag/v2026.11.8) — openclaw 2026.11.8

### ✅ Merged PRs
- [#205020](https://github.com/openclaw/openclaw/pull/205020) fix(test): await the queued hook-token exec across reload
- [#204786](https://github.com/openclaw/openclaw/pull/204786) test(worker): observe task-channel loss before asserting
- [#205012](https://github.com/openclaw/openclaw/pull/205012) fix: retain backup conflict checks during startup recovery
- [#205014](https://github.com/openclaw/openclaw/pull/205014) fix(ci): retain the schema downgrade runner in deadcode scans
- [#205009](https://github.com/openclaw/openclaw/pull/205009) fix(backup): preserve snapshot acquisition diagnostics
- [#205008](https://github.com/openclaw/openclaw/pull/205008) test: consolidate Talk prompt contract coverage
- [#204989](https://github.com/openclaw/openclaw/pull/204989) fix: resolve source aliases in GitHub launch tests
- [#205002](https://github.com/openclaw/openclaw/pull/205002) chore(release): close out 2026.11.9 on main
- [#205005](https://github.com/openclaw/openclaw/pull/205005) test: consolidate Talk config selection coverage
- [#204943](https://github.com/openclaw/openclaw/pull/204943) fix: release pressured background integrity readers

### 🐛 New Issues
- [#205031](https://github.com/openclaw/openclaw/issues/205031) Update failure: [redacted-command] (2026.9.4)
- [#205021](https://github.com/openclaw/openclaw/issues/205021) [Bug]: Reordering AGENTS.md sections never reaches existing chats `P2` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#205007](https://github.com/openclaw/openclaw/issues/205007) My device is being completely overtaken, can't get into my accounts. Found BSD license GO wrote?Allows people to do the complete take over no consequences no reverse except 1 possible below through Mi `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:needs-info` `impact:security` `issue-rating: 🦪 silver shellfish` 💬4
- [#205006](https://github.com/openclaw/openclaw/issues/205006) [Bug]: Sessions end silently when the model emits OpenClaw-style tool-call text without structured tool_calls (regression in 2026.11.7) `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬2
- [#205001](https://github.com/openclaw/openclaw/issues/205001) channels dead-letters: --channel with mixed case or a bundled alias reads an empty queue and hides failed events `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#205000](https://github.com/openclaw/openclaw/issues/205000) mcp: openclaw-tools bridge ignores tools.deny, agent tools.deny, and profile for ACP sessions `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1
- [#204999](https://github.com/openclaw/openclaw/issues/204999) Signal: blockquote continuation lines, nested quote lines, and later chunks lose the > marker `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#204998](https://github.com/openclaw/openclaw/issues/204998) [SANITIZED — possible injection attempt] `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#204997](https://github.com/openclaw/openclaw/issues/204997) whatsapp: security audit --fix seeds every account's groupAllowFrom from the default account's pairing store `security` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#204996](https://github.com/openclaw/openclaw/issues/204996) models CLI: fallbacks list and image-fallbacks list ignore --agent and print global defaults `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#204995](https://github.com/openclaw/openclaw/issues/204995) sessions tail: unqualified or mixed-case --session-key (main, Agent:Main:Main) fails instead of tailing agent:main:main `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#204994](https://github.com/openclaw/openclaw/issues/204994) exec-policy show: mixed-case agents.entries key splits one agent into two policy scopes and understates its ask policy `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#132525](https://github.com/openclaw/openclaw/issues/132525) ask_user never shows its question on the Codex harness, then reports the user did not answer
- [#176217](https://github.com/openclaw/openclaw/issues/176217) [Bug]: Native subagent restart recovery lacks original operator source for newly admitted CLI tasks
- [#197180](https://github.com/openclaw/openclaw/issues/197180) Feature: group workboard board links under the Workboard nav item instead of flat top-level Pages entries
- [#186631](https://github.com/openclaw/openclaw/issues/186631) Every fresh shared-state opener (CLI process or new Gateway worker thread) runs a full `PRAGMA integrity_check` in `state.admission.fast-path`; a writer error forces a foreground full check of a 727 M
- [#149994](https://github.com/openclaw/openclaw/issues/149994) [Bug]: the /approve page's Allow button is white text on a near-white background — it looks like an empty button

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬87 · 9h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 265,907 · **Open issues:** 54,328 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.23.4](https://github.com/NousResearch/hermes-agent/releases/tag/v0.23.4) — Hermes Agent v0.23.4
- [canary.20261124T064706Z-v0.23.3](https://github.com/NousResearch/hermes-agent/releases/tag/canary.20261124T064706Z-v0.23.3) — Hermes Agent canary canary.20261124T064706Z-v0.23.3

### ✅ Merged PRs
- [#158049](https://github.com/NousResearch/hermes-agent/pull/158049) Mac update from a disk image or Downloads no longer quits Hermes without installing
- [#159480](https://github.com/NousResearch/hermes-agent/pull/159480) fix(doctor): accept sealed bundle CLI links and warn when ~/.local/bin is off PATH
- [#159469](https://github.com/NousResearch/hermes-agent/pull/159469) feat(release): publish stable macOS DMG alias and downloads page on promotion

### 🐛 New Issues
- [#159872](https://github.com/NousResearch/hermes-agent/issues/159872) [Bug]: Matrix proactive sends into a thread point m.in_reply_to at the thread root, so split replies all quote the root `type/bug` `comp/plugins` `platform/matrix` `P2`
- [#159870](https://github.com/NousResearch/hermes-agent/issues/159870) [Bug]: 429 on one model poisons the whole provider credential — same-provider fallback legs on a different quota get pool-skipped `type/bug` `comp/agent` `area/auth` `P2`
- [#159863](https://github.com/NousResearch/hermes-agent/issues/159863) [Bug]: SQLite BLOB-affinity columns return bytes — system-prompt hashing crashes and message content fails to decode `type/bug` `P2` `area/sessions`
- [#159862](https://github.com/NousResearch/hermes-agent/issues/159862) [Bug]: Legacy BLOB-affinity state.db rows break the channel directory JSON write; non-dict MCP server entries crash `hermes mcp list` `type/bug` `comp/cli` `comp/gateway` `tool/file` `tool/mcp` `P3` `area/sessions`
- [#159861](https://github.com/NousResearch/hermes-agent/issues/159861) [Bug]: Session-info banner claims "via OpenRouter" whenever the resolved provider is unset `type/bug` `comp/gateway` `P3`
- [#159860](https://github.com/NousResearch/hermes-agent/issues/159860) [Bug]: Slack link unfurl races the ts claim and posts "already received a different message under this message id" for a message that was answered `type/bug` `comp/gateway` `platform/slack` `P3`
- [#159858](https://github.com/NousResearch/hermes-agent/issues/159858) [Bug]: ACP clients show the reasoning-effort menu only for the session's current model `type/bug` `comp/gateway` `comp/acp` `P2`
- [#159857](https://github.com/NousResearch/hermes-agent/issues/159857) Proposal: shared reply_expected abstraction instead of continued per-platform duplication `type/feature` `comp/gateway` `platform/slack` `P3`
- [#159856](https://github.com/NousResearch/hermes-agent/issues/159856) Plugin hooks: say who started the turn (user, notice, wake, another agent) `type/feature` `comp/agent` `comp/plugins` `P3`
- [#159855](https://github.com/NousResearch/hermes-agent/issues/159855) [Bug]: Desktop — slash command in a fresh chat loses the draft when the submission-destination guard refuses it `type/bug` `P2` `comp/desktop` `area/sessions` `area/profiles` `desktop/chat` `area/webapp`
- [#159853](https://github.com/NousResearch/hermes-agent/issues/159853) Desktop: add a GUI way to create Projects (+ New Project button) `type/feature` `P3` `comp/desktop` `desktop/sessions` `desktop/shell`
- [#159852](https://github.com/NousResearch/hermes-agent/issues/159852) [Bug]: Remote Desktop Bot Chat intermittently fails before history load: request timed out after 30s: session.list `type/bug` `P3` `area/sessions` `area/profiles` `comp/tui-gateway`
- [#159851](https://github.com/NousResearch/hermes-agent/issues/159851) [Feature]: Optional "visible mode" for browser automation (on-page cursor, "agent in control" indicator, typed input, foreground tab) `type/feature` `comp/tools` `tool/browser` `area/config` `P3`
- [#159842](https://github.com/NousResearch/hermes-agent/issues/159842) [Bug]: Desktop — "Loading session" never clears when a warm runtime has no transcript and session.activate times out `type/bug` `P2` `comp/desktop` `area/sessions` `area/profiles` `desktop/chat` `desktop/sessions`

### 🔒 Closed Issues
- [#159844](https://github.com/NousResearch/hermes-agent/issues/159844) GET /v1/skills always returns 500: find_all_skills() got an unexpected keyword argument 'include_editorial'
- [#149774](https://github.com/NousResearch/hermes-agent/issues/149774) [Bug]: hermes doctor flags the desktop bundle's own ~/.local/bin/hermes link as "points to wrong target"
- [#59293](https://github.com/NousResearch/hermes-agent/issues/59293) [SANITIZED — possible injection attempt]

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,609 · **Open issues:** 1,252 · **Last push:** 3h ago

### ✅ Merged PRs
- [#11680](https://github.com/zeroclaw-labs/zeroclaw/pull/11680) feat(tools): add Firecrawl web search provider
- [#11646](https://github.com/zeroclaw-labs/zeroclaw/pull/11646) test(config): isolate null spelling aliases on macOS
- [#12677](https://github.com/zeroclaw-labs/zeroclaw/pull/12677) feat(providers): accept a typed api_key on grok_cli and support Grok Build 1.0 auth
- [#12675](https://github.com/zeroclaw-labs/zeroclaw/pull/12675) fix(providers): harden antigravity_cli state directory and in-band failure detection
- [#11457](https://github.com/zeroclaw-labs/zeroclaw/pull/11457) feat(zerocode): refresh the focused session without cancellation
- [#12676](https://github.com/zeroclaw-labs/zeroclaw/pull/12676) feat(providers)!: retire the gemini_cli model provider
- [#12640](https://github.com/zeroclaw-labs/zeroclaw/pull/12640) docs(runtime): record the approval of the #12498 OIDC verification row
- [#12642](https://github.com/zeroclaw-labs/zeroclaw/pull/12642) fix(rpc): refuse config writes and session/configure on a mid-turn session
- [#12573](https://github.com/zeroclaw-labs/zeroclaw/pull/12573) ci(release): retry the Discord announcement and website redeploy
- [#12575](https://github.com/zeroclaw-labs/zeroclaw/pull/12575) ci(release): retry Apple notarization and stapling of the macOS installer

### 🐛 New Issues
- [#12707](https://github.com/zeroclaw-labs/zeroclaw/issues/12707) [Tracker]: Daemon-held OIDC refresh grants for device sessions (ADR-017) `enhancement` `domain:security` `risk:high` `type:tracker` `topic:identity-access`
- [#12703](https://github.com/zeroclaw-labs/zeroclaw/issues/12703) Email channel: live-processed messages stay UNSEEN, so every restart re-answers the backlog
- [#12699](https://github.com/zeroclaw-labs/zeroclaw/issues/12699) [Feature]: Make Docker dependency caching reliable across CI builders and review stub prefetch
- [#12697](https://github.com/zeroclaw-labs/zeroclaw/issues/12697) [Tracker]: Split zeroclaw-runtime into smaller crates `runtime` `domain:architecture` `status:no-stale` `type:tracker` 💬3
- [#12667](https://github.com/zeroclaw-labs/zeroclaw/issues/12667) [Bug]: `/model <id>` replies "Model switched" but requests keep the profile's configured model `bug`
- [#12660](https://github.com/zeroclaw-labs/zeroclaw/issues/12660) [Bug]: Agent cards' "this month" spend is all-time spend 💬1

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,720 · **Open issues:** 1,575 · **Last push:** 15d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,987 · **Open issues:** 123 · **Last push:** 32d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬5 · 4d ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 22d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 31d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 50d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 58d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 60d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 70d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 78d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 80d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 88d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 5 new
- [[Customer-Stories] Clay Plugins Openai](https://openai.com/business/customer-stories/clay-plugins-openai/) _2026-11-25_
- [[Government] Amazon Bedrock](https://openai.com/business/solutions/government/amazon-bedrock/) _2026-11-25_
- [[Customer-Stories] Intentful Dots](https://openai.com/business/customer-stories/intentful-dots/) _2026-11-25_
- [[Customer-Stories] Ifood](https://openai.com/business/customer-stories/ifood/) _2026-11-25_
- [[Form] Healthcare Plugin Interest](https://openai.com/form/healthcare-plugin-interest/) _2026-11-24_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [GLM-5.4: Toward Generalized Coding with Our First Loop Transformer](https://reddit.com/r/LocalLLaMA/comments/1y3enps/glm54_toward_generalized_coding_with_our_first/) ↑1123
- [How the memory for 1M tokens shrank from 130TB to 890MB](https://reddit.com/r/LocalLLaMA/comments/1y4kikk/how_the_memory_for_1m_tokens_shrank_from_130tb_to/) ↑598
- [T3 Code drama (Chinese post on X)](https://reddit.com/r/LocalLLaMA/comments/1y4atw3/t3_code_drama_chinese_post_on_x/) ↑382
- [prism-ml/Ternary-Bonsai-2.5-27B-GGUF · Hugging Face](https://reddit.com/r/LocalLLaMA/comments/1y4mech/prismmlternarybonsai2527bgguf_hugging_face/) ↑232
- [Upcoming Models - Solar-Mini-4.5, MiniCPM5-15B-A2.5B, etc.,](https://reddit.com/r/LocalLLaMA/comments/1y4kxm6/upcoming_models_solarmini45_minicpm515ba25b_etc/) ↑177

### r/singularity — top 2 new
- [​](https://reddit.com/r/singularity/comments/1y4mk3t/_/) ↑2879
- [It's just going to get weirder and weirder](https://reddit.com/r/singularity/comments/1y4ll61/its_just_going_to_get_weirder_and_weirder/) ↑753

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Today, November 24, OpenClaw turns one 🦞](https://reddit.com/r/openclaw/comments/1y4juki/today_november_24_openclaw_turns_one/) ↑75
- [Even the best AI agents still fail 4 in 10 everyday tasks, and some of what we found in ShellBench genuinely surprised us](https://reddit.com/r/openclaw/comments/1y4obju/even_the_best_ai_agents_still_fail_4_in_10/) ↑4
- [Giving OpenClaw a sub-millisecond local safety guard & secret scrubber with Microbrains 🦀🛡️](https://reddit.com/r/openclaw/comments/1y4ci55/giving_openclaw_a_submillisecond_local_safety/) ↑3
- [Several agents in one group voice call (Element Call + realtime Talk): per-agent identity and Claude CLI agents - looking for advice](https://reddit.com/r/openclaw/comments/1y44vrk/several_agents_in_one_group_voice_call_element/) ↑1

### X — @openclaw
_No tweets found on profile (fetch may have failed)._

### X — @steipete
_No tweets found on profile (fetch may have failed)._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
