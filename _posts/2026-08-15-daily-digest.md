---
layout: post
title: "Ecosystem Digest — 2026-08-15"
date: 2026-08-15 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-08-15
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 386,315 | 7 | 5 | 10 | 0 |
| **hermesagent** | 230,674 | 7 | 5 | 5 | 0 |
| **ZeroClaw** | 32,581 | 7 | 3 | 5 | 0 |
| **IronClaw** | 12,601 | 15 | 3 | 10 | 0 |
| **Moltis** | 2,818 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 386,315 · **Open issues:** 5,547 · **Last push:** <1h ago

### ✅ Merged PRs
- [#123919](https://github.com/openclaw/openclaw/pull/123919) fix(gateway): allow worker bootstrap on slow uplinks
- [#123829](https://github.com/openclaw/openclaw/pull/123829) fix: visible sessions explain working-directory denials
- [#116489](https://github.com/openclaw/openclaw/pull/116489) feat(security): require acknowledgement for install policy warnings
- [#123923](https://github.com/openclaw/openclaw/pull/123923) perf(test): move direct import smoke to test fixtures
- [#123917](https://github.com/openclaw/openclaw/pull/123917) fix(gateway): include build identity in status JSON
- [#123916](https://github.com/openclaw/openclaw/pull/123916) refactor(ui): remove disconnected build mismatch projection
- [#121081](https://github.com/openclaw/openclaw/pull/121081) fix(gateway): reject stale worker bundles before tunnel start
- [#123914](https://github.com/openclaw/openclaw/pull/123914) fix(cron): keep agent-less schedules running after adding an agent
- [#123901](https://github.com/openclaw/openclaw/pull/123901) fix(workers): bound Gateway bundle cache growth
- [#123913](https://github.com/openclaw/openclaw/pull/123913) refactor(sessions): avoid duplicate SQLite conformance runs

### 🐛 New Issues
- [#123926](https://github.com/openclaw/openclaw/issues/123926) [Bug]: CoreDNS zone updates can publish partial files `bug` `maintainer` 💬1
- [#123918](https://github.com/openclaw/openclaw/issues/123918) [Bug]: inline-button prompt guidance ignores chat type, so scoped Telegram configs advertise sends the runtime rejects `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬2
- [#123915](https://github.com/openclaw/openclaw/issues/123915) [Bug]: ask_user in a Telegram group deletes its preview and delivers nothing to the chat `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬2
- [#123900](https://github.com/openclaw/openclaw/issues/123900) Codex app-server: apply_patch/exec fail with bwrap ENOENT (guardian path resolution + network_proxy re-exec) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🦪 silver shellfish` `impact:other` 💬3
- [#123886](https://github.com/openclaw/openclaw/issues/123886) [Bug]: Telegram model picker overlaps stale rich text after legacy edit `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬3
- [#123881](https://github.com/openclaw/openclaw/issues/123881) [Feature]: Always open links in Control UI browser `enhancement` `maintainer` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬2
- [#123872](https://github.com/openclaw/openclaw/issues/123872) Restart drain waits 300s by default while the packaged systemd unit stops at 30s — every stall ends in SIGKILL instead of a bounded abort `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` `maturity:stable` 💬1

### 🔒 Closed Issues
- [#74743](https://github.com/openclaw/openclaw/issues/74743) [Bug]: Custom session cron jobs do not persist in destination session.
- [#121831](https://github.com/openclaw/openclaw/issues/121831) Any user message arriving mid-run kills the active run and silently drops the message
- [#123304](https://github.com/openclaw/openclaw/issues/123304) [Bug]: stale-foreground suppression overwrites the assistant's own reply text in the transcript, erasing it from the model's context (agent disowns a message the user can see)
- [#123427](https://github.com/openclaw/openclaw/issues/123427) [Bug]: openclaw agent returns before its gateway lane finishes, so a second invocation on the same session key hits EmbeddedAttemptSessionTakeoverError
- [#121036](https://github.com/openclaw/openclaw/issues/121036) [Bug]: Cloud Worker recovery can open tunnels to stale worker bundles after Gateway upgrade

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 230,674 · **Open issues:** 32,281 · **Last push:** <1h ago

### ✅ Merged PRs
- [#86399](https://github.com/NousResearch/hermes-agent/pull/86399) fix(telegram): hold inbound messages across disconnect instead of destroying them
- [#86378](https://github.com/NousResearch/hermes-agent/pull/86378) fix(send_message): hand unresolved cron and react targets to the adapter again
- [#86374](https://github.com/NousResearch/hermes-agent/pull/86374) fix(tui): prepend Hermes tool dirs to slash_worker PATH (salvage #83854)
- [#86313](https://github.com/NousResearch/hermes-agent/pull/86313) fix(agent): bot prompt leaks default profile's skills index + identity
- [#86559](https://github.com/NousResearch/hermes-agent/pull/86559) fmt(js): `npm run fix` auto-fix

### 🐛 New Issues
- [#86602](https://github.com/NousResearch/hermes-agent/issues/86602) [Bug]: Desktop read-aloud speaks hardcoded English placeholders ("code block omitted", "link") and silently drops tables `type/bug` `tool/tts` `P3` `comp/desktop` `area/i18n`
- [#86601](https://github.com/NousResearch/hermes-agent/issues/86601) [Bug]: Desktop auto-TTS reads the same reply again right after playback finishes `type/bug` `tool/tts` `P3` `sweeper:risk-session-state` `comp/desktop`
- [#86581](https://github.com/NousResearch/hermes-agent/issues/86581) [Bug]: Truncated-response continuation (finish_reason=length) never checks for repetition before retrying, and Discord delivery has no split-count cap — one degenerate turn floods a channel with 30+ m `type/bug` `comp/agent` `comp/gateway` `platform/discord` `P2` `sweeper:risk-message-delivery`
- [#86580](https://github.com/NousResearch/hermes-agent/issues/86580) Gateway auto-resume persists an empty user message that triggers Pre-call sanitizer on every subsequent turn `type/bug` `comp/gateway` `P3` `sweeper:risk-session-state` `area/sessions`
- [#86579](https://github.com/NousResearch/hermes-agent/issues/86579) Windows: kanban dispatcher-spawned worker crashes ~60s after spawn (pid not alive) even for trivial tasks; same profile works when launched manually `type/bug` `comp/cron` `P3` `sweeper:risk-platform-windows` `platform/windows`
- [#86577](https://github.com/NousResearch/hermes-agent/issues/86577) [Bug]: Desktop — "↓ needs approval" floating bar reappears after the turn finished (stale per-session approval entry) `type/bug` `area/auth` `P3` `sweeper:risk-session-state` `comp/desktop`
- [#86574](https://github.com/NousResearch/hermes-agent/issues/86574) Kanban project worktrees start from stale local HEAD instead of fetched origin/main `type/bug` `comp/cron` `P3` `needs-decision` `sweeper:risk-compatibility`

### 🔒 Closed Issues
- [#84507](https://github.com/NousResearch/hermes-agent/issues/84507) [Bug]: Hermes opening chrome link for local browser searching
- [#86576](https://github.com/NousResearch/hermes-agent/issues/86576) Strip encrypted reasoning tokens from conversation context on cross-provider delegation and model switch
- [#85128](https://github.com/NousResearch/hermes-agent/issues/85128) [Bug]: Cron delivery silently dropped and react opaque-id passthrough gone for targets resolve_send_target can't resolve
- [#78647](https://github.com/NousResearch/hermes-agent/issues/78647) [EPIC — COMPLETE] All Gods Must Die: 20/20 killed
- [#83845](https://github.com/NousResearch/hermes-agent/issues/83845) [Bug]: Dashboard slash_worker PATH omits Hermes venv/user bin, causing browser_exec CLI discovery to fail

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,581 · **Open issues:** 706 · **Last push:** 7h ago

### ✅ Merged PRs
- [#9974](https://github.com/zeroclaw-labs/zeroclaw/pull/9974) feat(providers): send OpenRouter app-attribution categories header
- [#9992](https://github.com/zeroclaw-labs/zeroclaw/pull/9992) chore(deps): bump nanoid to 3.3.18
- [#9968](https://github.com/zeroclaw-labs/zeroclaw/pull/9968) fix(providers): preserve compatible-provider integrity
- [#9424](https://github.com/zeroclaw-labs/zeroclaw/pull/9424) fix(runtime): reject semantic-empty terminal completions
- [#9822](https://github.com/zeroclaw-labs/zeroclaw/pull/9822) feat(channels): show Telegram tool progress in partial drafts

### 🐛 New Issues
- [#9998](https://github.com/zeroclaw-labs/zeroclaw/issues/9998) RFC: Session-scoped persistent prompt attachments
- [#9990](https://github.com/zeroclaw-labs/zeroclaw/issues/9990) RFC: Calibrate PR risk and security approval requirements `docs` `priority:p2` `needs-maintainer-review` `type:rfc` `status:no-stale` `risk:high`
- [#9983](https://github.com/zeroclaw-labs/zeroclaw/issues/9983) [Bug]: Fallback model without vision incorrectly reports cause of error `bug` 💬1
- [#9972](https://github.com/zeroclaw-labs/zeroclaw/issues/9972) [Tracker]: Eliminate user-facing literal output outside localization boundaries `enhancement` `core` `runtime` `tests` `priority:p2` `status:no-stale` `type:tracker` 💬1
- [#9970](https://github.com/zeroclaw-labs/zeroclaw/issues/9970) [Feature]: Authorize Discord members by role, not just user ID `enhancement` `channel` `config` `daemon` `runtime` `channel:discord` `domain:security` `priority:p2` `status:in-progress` `risk:high` 💬1
- [#9967](https://github.com/zeroclaw-labs/zeroclaw/issues/9967) [Tracker]: Establish a harness evaluation framework to guide development direction `enhancement` `tests` `priority:p2` `status:no-stale` `risk:medium` `type:tracker` 💬1
- [#9965](https://github.com/zeroclaw-labs/zeroclaw/issues/9965) [Task]: cron custom-shell test hits ETXTBSY under the parallel runtime gate and fails unrelated PRs `bug` `cron` `runtime` `tests` `priority:p1` `status:accepted` `risk:medium` `type:test` 💬1

### 🔒 Closed Issues
- [#9982](https://github.com/zeroclaw-labs/zeroclaw/issues/9982) [Proposal] Hosted memory for ZeroClaw users — 97.5% fewer tokens (ViBo Cloud API)
- [#9991](https://github.com/zeroclaw-labs/zeroclaw/issues/9991) ci: npm audit failed — 2026-08-14
- [#6663](https://github.com/zeroclaw-labs/zeroclaw/issues/6663) feat(telegram): show tool-call progress during partial streaming

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,601 · **Open issues:** 1,512 · **Last push:** <1h ago

### ✅ Merged PRs
- [#7562](https://github.com/nearai/ironclaw/pull/7562) feat(unbound-turns): design + phase 1 — prepared-context accept door, unbound run lane, kernel binding-ref deletion
- [#7665](https://github.com/nearai/ironclaw/pull/7665) fix(auth): support origin-scoped hosted MCP OAuth
- [#7652](https://github.com/nearai/ironclaw/pull/7652) perf(stress): measure production DB write workloads
- [#7666](https://github.com/nearai/ironclaw/pull/7666) fix(extensions): tell the truth on cards and install results (QA #7660 + install guidance)
- [#7658](https://github.com/nearai/ironclaw/pull/7658) fix(telegram): recognize the 2FA gate on migrated DCs and say where login codes arrive
- [#7533](https://github.com/nearai/ironclaw/pull/7533) refactor(agent-loop): trust model-emitted parallel batches
- [#7464](https://github.com/nearai/ironclaw/pull/7464) feat(telegram): pair linked devices with the bot channel
- [#7571](https://github.com/nearai/ironclaw/pull/7571) feat(webui): introduce shared search field - #7569
- [#7549](https://github.com/nearai/ironclaw/pull/7549) feat(canary): report model-emitted tool batches
- [#7630](https://github.com/nearai/ironclaw/pull/7630) perf(stress): measure per-turn LibSQL/Postgres writes

### 🐛 New Issues
- [#7669](https://github.com/nearai/ironclaw/issues/7669) Prepared-marker backfill: move the per-scope sweep off the listing path
- [#7667](https://github.com/nearai/ironclaw/issues/7667) telegram: phone-mode login code hint should reflect sentCode.type_ (raw-TL send path)
- [#7664](https://github.com/nearai/ironclaw/issues/7664) Pluggable memory over MCP: wire the provider, land Mnesis as first consumer, publish the contract `enhancement`
- [#7662](https://github.com/nearai/ironclaw/issues/7662) MP4 attachment fails with invalid_value (attachments.mime_type) error in Telegram `bug_bash_P2` `qa-bug`
- [#7660](https://github.com/nearai/ironclaw/issues/7660) Slack shows "Reconnect" and "Finish Setup" despite active working connection `bug_bash_P2` `qa-bug`
- [#7659](https://github.com/nearai/ironclaw/issues/7659) Extensions installed by other users are visible on Extensions/Registry page `bug_bash_P2` `qa-bug`
- [#7653](https://github.com/nearai/ironclaw/issues/7653) Implement structured Ask User cards in WebUI
- [#7647](https://github.com/nearai/ironclaw/issues/7647) feat(automations): add a deterministic no-delivery outcome for scheduled runs `enhancement` `v1.3.0`
- [#7646](https://github.com/nearai/ironclaw/issues/7646) feat(automations): preflight grants and acquire scoped standing approval leases `enhancement` `v1.3.0`
- [#7645](https://github.com/nearai/ironclaw/issues/7645) feat(automations): pin an LLM model profile per structured execution contract `enhancement` `v1.3.0`
- [#7644](https://github.com/nearai/ironclaw/issues/7644) feat(automations): verify a structured automation once before arming its schedule `enhancement` `v1.3.0`
- [#7639](https://github.com/nearai/ironclaw/issues/7639) Introduce a shared InlineNotice for page feedback
- [#7638](https://github.com/nearai/ironclaw/issues/7638) Replace thread deletion alerts with global toast feedback
- [#7637](https://github.com/nearai/ironclaw/issues/7637) Type the design-system component boundary
- [#7624](https://github.com/nearai/ironclaw/issues/7624) v0: ACP harness executor — claude-code as the loop, dev-only yolo (#7482) `enhancement` `reborn`

### 🔒 Closed Issues
- [#7656](https://github.com/nearai/ironclaw/issues/7656) Add Slack-to-Console bridge with interactive Slack response metadata
- [#7569](https://github.com/nearai/ironclaw/issues/7569) Introduce a shared SearchField for common list filtering
- [#7592](https://github.com/nearai/ironclaw/issues/7592) [Tier 0] Per-turn DB write measurement harness (pg_stat_statements baseline)

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,818 · **Open issues:** 106 · **Last push:** <1h ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 3h ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 2d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 5d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 8d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 8d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 10d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 12d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 12d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 14d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 14d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Claude Text Watermark](https://www.anthropic.com/news/claude-text-watermark) _2026-08-14_

### OpenAI — 4 new
- [[Learn] How Our Sales Team Uses Chatgpt Work](https://openai.com/business/learn/how-our-sales-team-uses-chatgpt-work/) _2026-08-15_
- [[Learn] Download The Chatgpt Work Guide For Sales Teams](https://openai.com/business/learn/download-the-chatgpt-work-guide-for-sales-teams/) _2026-08-14_
- [[Plugins] Data](https://openai.com/business/plugins/data/) _2026-08-14_
- [[Plugins] Azure Devops](https://openai.com/business/plugins/azure-devops/) _2026-08-14_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [IT'S OUT](https://reddit.com/r/LocalLLaMA/comments/1vo9mj4/its_out/) ↑1823
- [Qwen/Qwen3.8-27B · released](https://reddit.com/r/LocalLLaMA/comments/1vo9nn7/qwenqwen3827b_released/) ↑906

### r/singularity — top 5 new
- [Neurosurgery resident at a Peking College Hospital uses GPT 5.6 Sol to prove a 2 decades old mathematical conjecture underlying a major problem in numerical linear algebra — All for the purposes of hi](https://reddit.com/r/singularity/comments/1vnz6og/neurosurgery_resident_at_a_peking_college/) ↑899
- [No way 💀 what an AI week](https://reddit.com/r/singularity/comments/1vnypqt/no_way_what_an_ai_week/) ↑850
- [GLM 5.3 finds 2436 unpatched open source vulnerabilities likely missed by Mythos (Project Glasswing)](https://reddit.com/r/singularity/comments/1vo56qy/glm_53_finds_2436_unpatched_open_source/) ↑539
- [Qwen 3.8 27b is here](https://reddit.com/r/singularity/comments/1voa4mo/qwen_38_27b_is_here/) ↑429
- [GLM 5.3 released: Frontier Coding with Emergent Cyber Capabilities](https://reddit.com/r/singularity/comments/1vnz30c/glm_53_released_frontier_coding_with_emergent/) ↑425

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Update on the upcoming release](https://reddit.com/r/openclaw/comments/1vok1ae/update_on_the_upcoming_release/) ↑43
- [Did you use Deepseek? What now?](https://reddit.com/r/openclaw/comments/1voaqo5/did_you_use_deepseek_what_now/) ↑9

### X — @openclaw
- [The future is here.](https://x.com/openclaw/status/2087978729754825193) ↑0 🔁0 · recent
- [Unfiltered Q&A with OpenClaw Founder 
@steipete



@hrudolph
 and 
@Pat_Erichsen
 put community questions to Peter about](https://x.com/openclaw/status/2087689758759899173) ↑0 🔁0 · recent
- [Grok 4.6 from 
@SpaceXAI

is LIVE on OpenClaw.](https://x.com/openclaw/status/2087563414210302084) ↑0 🔁0 · recent


### X — @steipete
_No new tweets in the last 7 days._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
