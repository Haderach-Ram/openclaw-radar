---
layout: post
title: "Ecosystem Digest — 2026-08-18"
date: 2026-08-18 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-08-18
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 386,568 | 7 | 2 | 10 | 0 |
| **hermesagent** | 232,064 | 11 | 3 | 10 | 1 |
| **ZeroClaw** | 32,609 | 13 | 6 | 10 | 0 |
| **IronClaw** | 12,607 | 15 | 6 | 10 | 1 |
| **Moltis** | 2,823 | 1 | 2 | 6 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 386,568 · **Open issues:** 5,683 · **Last push:** <1h ago

### ✅ Merged PRs
- [#125007](https://github.com/openclaw/openclaw/pull/125007) fix(cli): render missing gateway credentials consistently
- [#125491](https://github.com/openclaw/openclaw/pull/125491) refactor(tooling): unify benchmark and process helpers
- [#125503](https://github.com/openclaw/openclaw/pull/125503) refactor(agents): unify exec approval decisions
- [#125455](https://github.com/openclaw/openclaw/pull/125455) fix(config): keep missing env references unavailable without rejecting literals
- [#125505](https://github.com/openclaw/openclaw/pull/125505) fix(ui): prevent side panel tab labels from clipping
- [#124995](https://github.com/openclaw/openclaw/pull/124995) fix(doctor): report unusable cloud worker profiles
- [#125458](https://github.com/openclaw/openclaw/pull/125458) fix(voice-call): survive gateway in-process restart and stop CLI dead-ends
- [#125500](https://github.com/openclaw/openclaw/pull/125500) fix(memory): record the omitted memory corpus in corpus=all searches
- [#125473](https://github.com/openclaw/openclaw/pull/125473) fix: keep Workboard visible in the sidebar
- [#125444](https://github.com/openclaw/openclaw/pull/125444) feat(android): render durable progress card in chat

### 🐛 New Issues
- [#125509](https://github.com/openclaw/openclaw/issues/125509) [Bug]: Model picker reports authentication failure during Gateway restart `bug` `maintainer` 💬1
- [#125506](https://github.com/openclaw/openclaw/issues/125506) [Bug]: Setup registry reports false missing-runtime warnings for metadata-only provider descriptors `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#125496](https://github.com/openclaw/openclaw/issues/125496) [Bug][Windows/WSL] Native dev update leaves Companion CLI wrapper pointing at previous local-prefix install `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬3
- [#125482](https://github.com/openclaw/openclaw/issues/125482) Release validation: v2026.8.1-beta.2 `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🌊 off-meta tidepool` `impact:other` 💬1
- [#125477](https://github.com/openclaw/openclaw/issues/125477) [Bug]: ChatGPT Responses WebSocket 1006 after initial event loses transport diagnostics `bug` `bug:behavior` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:message-loss` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#125475](https://github.com/openclaw/openclaw/issues/125475) Release validation: v2026.8.1-beta.3 `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🌊 off-meta tidepool` `impact:other` 💬1
- [#125461](https://github.com/openclaw/openclaw/issues/125461) iMessage CLI treats bare numeric chat row IDs as phone handles despite `handle/chat_id` help `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬2

### 🔒 Closed Issues
- [#125504](https://github.com/openclaw/openclaw/issues/125504) [Bug]: Side panel tab labels are vertically clipped
- [#125501](https://github.com/openclaw/openclaw/issues/125501) diagnostics: memory-pressure rss_threshold (1.5 GiB) is not configurable; permanent warnings on large-memory hosts

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 232,064 · **Open issues:** 32,784 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.8.16.2](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.8.16.2) — Hermes Agent v0.20.3 (2026.8.16.2)

### ✅ Merged PRs
- [#85582](https://github.com/NousResearch/hermes-agent/pull/85582) fix(relay): unwrap lazy completed streams
- [#85579](https://github.com/NousResearch/hermes-agent/pull/85579) fix(relay): use canonical managed operation names
- [#88818](https://github.com/NousResearch/hermes-agent/pull/88818) fmt(js): `npm run fix` auto-fix
- [#88813](https://github.com/NousResearch/hermes-agent/pull/88813) fmt(js): `npm run fix` auto-fix
- [#88800](https://github.com/NousResearch/hermes-agent/pull/88800) feat(bot-mode): hide bots from the roster via right-click — header eye toggle reveals and unhides them
- [#88787](https://github.com/NousResearch/hermes-agent/pull/88787) fix(cron): configurable media-send timeout + non-empty failure reasons (salvages #87965, #87967)
- [#88788](https://github.com/NousResearch/hermes-agent/pull/88788) fix(desktop): Bots pane is a Sessions-zone tab again (not stacked below) and the Cronjobs pane only appears in Bots mode
- [#88785](https://github.com/NousResearch/hermes-agent/pull/88785) fix(bot-mode): ownership-based sweep hides CLI-born Bot Mode sessions from the global sidebar
- [#88776](https://github.com/NousResearch/hermes-agent/pull/88776) fix(plugins): hide bundled model providers from plugin list (salvage #27268)
- [#88773](https://github.com/NousResearch/hermes-agent/pull/88773) docs: unified Gateways page, settings profile scope, plugins cleanup, Bot Mode group rows, host.openWorkspace

### 🐛 New Issues
- [#88852](https://github.com/NousResearch/hermes-agent/issues/88852) [Bug]: TUI session switch leaks queued /q message to the newly-active session
- [#88848](https://github.com/NousResearch/hermes-agent/issues/88848) [Bug]: macOS: hermes update reports success while the launchd reload helper dies before bootstrapping — gateway left unregistered for 36 min (post-#80491) `type/bug` `comp/cli` `comp/gateway` `P1` `sweeper:risk-message-delivery` `sweeper:risk-compatibility` `area/install-update`
- [#88844](https://github.com/NousResearch/hermes-agent/issues/88844) feat(desktop): system-wide selection assistant — floating AI panel appears when selecting text in any app `type/feature` `P3` `comp/desktop`
- [#88842](https://github.com/NousResearch/hermes-agent/issues/88842) [Bug] Profile directory '~/.hermes/profiles/0' is created without a config.yaml on v0.20.3 first launch `type/bug` `P2` `sweeper:risk-compatibility` `comp/desktop` `area/profiles` 💬3
- [#88841](https://github.com/NousResearch/hermes-agent/issues/88841) [Bug] Desktop profile rail shows every profile twice with a 'macmini' host chip after v0.20.3 upgrade `type/bug` `P2` `comp/desktop` `area/profiles`
- [#88839](https://github.com/NousResearch/hermes-agent/issues/88839) operational surfaces have no structured output — gateway status, cron list, dispatch-status are human-text only, and the only alternative source (gateway.log) contains message content `type/feature` `comp/cli` `comp/gateway` `comp/cron` `P3`
- [#88838](https://github.com/NousResearch/hermes-agent/issues/88838) Windows: `hermes update` self-locks its own console-script launcher; ZIP fallback masks it and leaves the venv editable install stale `type/bug` `comp/cli` `P2` `sweeper:risk-compatibility` `sweeper:risk-platform-windows` `platform/windows` `area/install-update`
- [#88830](https://github.com/NousResearch/hermes-agent/issues/88830) Auxiliary title generation fails with HTTP 400 on DeepSeek: response_format json_schema unsupported `type/bug` `duplicate` `comp/agent` `provider/deepseek` `P3` 💬1
- [#88829](https://github.com/NousResearch/hermes-agent/issues/88829) [Bug]: False-positive "Deprecated .env settings" TERMINAL_CWD warning on every startup (self-reported by config bridge) `type/bug` `duplicate` `comp/cli` `area/config` `P2` `sweeper:risk-compatibility` `bug` 💬1
- [#88827](https://github.com/NousResearch/hermes-agent/issues/88827) Desktop "update available" notification only triggers WSL backend update, never rebuilds the desktop client — creates an infinite update loop on Windows+WSL `type/bug` `P3` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows`
- [#88824](https://github.com/NousResearch/hermes-agent/issues/88824) Desktop Bot Mode misclassifies active remote profiles as local and duplicates rows `type/bug` `P2` `comp/desktop` `area/profiles`

### 🔒 Closed Issues
- [#88840](https://github.com/NousResearch/hermes-agent/issues/88840) test
- [#87663](https://github.com/NousResearch/hermes-agent/issues/87663) [Setup]: Termux install fails / hangs building cryptography==50.0.0 from source (no Android wheel available yet)
- [#57921](https://github.com/NousResearch/hermes-agent/issues/57921) hermes_state.py: timeout=1.0 causes "database is locked" when dashboard event loop stalls under GIL pressure

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,609 · **Open issues:** 725 · **Last push:** 3h ago

### ✅ Merged PRs
- [#9973](https://github.com/zeroclaw-labs/zeroclaw/pull/9973) fix(providers): keep Gemini API keys out of URLs
- [#10043](https://github.com/zeroclaw-labs/zeroclaw/pull/10043) ci(lint): remove duplicate architecture test guards
- [#9547](https://github.com/zeroclaw-labs/zeroclaw/pull/9547) chore(channels): upgrade CPAL to 0.18
- [#10000](https://github.com/zeroclaw-labs/zeroclaw/pull/10000) fix(channels): bound QQ and Mattermost downloads
- [#10010](https://github.com/zeroclaw-labs/zeroclaw/pull/10010) test(cron): avoid ETXTBSY race in custom shell test
- [#10039](https://github.com/zeroclaw-labs/zeroclaw/pull/10039) ci(clippy): share Clippy command runner across workflows
- [#9996](https://github.com/zeroclaw-labs/zeroclaw/pull/9996) fix(security): make action budget accounting atomic
- [#9993](https://github.com/zeroclaw-labs/zeroclaw/pull/9993) fix(email): stop implicit attachment file reads
- [#9612](https://github.com/zeroclaw-labs/zeroclaw/pull/9612) fix(channels): tie the WhatsApp Cloud approval token to a guard so no exit orphans it
- [#9765](https://github.com/zeroclaw-labs/zeroclaw/pull/9765) fix(sop): load SOP definitions from the shared workspace, not data_dir

### 🐛 New Issues
- [#10069](https://github.com/zeroclaw-labs/zeroclaw/issues/10069) RFC: Agent Portability `type:rfc`
- [#10068](https://github.com/zeroclaw-labs/zeroclaw/issues/10068) [Bug]: Interactive agent session caps context at 32,000 tokens, ignoring max_context_tokens = 131072 `bug` 💬1
- [#10067](https://github.com/zeroclaw-labs/zeroclaw/issues/10067) [Bug]: One oversized tool result is unrecoverable — the shell output cap is a 1 MB memory bound, not a context bound `bug`
- [#10066](https://github.com/zeroclaw-labs/zeroclaw/issues/10066) [Bug]: SOP engine promotes and runs later steps before recording a step's output-schema rejection `bug`
- [#10063](https://github.com/zeroclaw-labs/zeroclaw/issues/10063) [Bug]: Anthropic-backed compatible gateways reject image_url blocks inside tool results `bug` `provider` `provider:compatible` `priority:p1` `follow-up` `risk:medium`
- [#10062](https://github.com/zeroclaw-labs/zeroclaw/issues/10062) [Bug]: TodoWrite plan leaks across ZeroCode session switches `bug` `priority:p2` `risk:medium` `zerocode`
- [#10061](https://github.com/zeroclaw-labs/zeroclaw/issues/10061) [Bug]: Provider-rejected image poisons later turns in a vision-capable session `bug` `provider` `runtime` `priority:p1` `follow-up` `zerocode` `risk:high`
- [#10059](https://github.com/zeroclaw-labs/zeroclaw/issues/10059) [Feature]: Support Option-Backspace word deletion in ZeroCode text inputs `enhancement` `good first issue` `priority:p3` `zerocode` `risk:low` 💬2
- [#10058](https://github.com/zeroclaw-labs/zeroclaw/issues/10058) [Bug]: ZeroCode file explorer search mode ignores row and page navigation `bug` `good first issue` `priority:p2` `zerocode` `risk:low` 💬1
- [#10051](https://github.com/zeroclaw-labs/zeroclaw/issues/10051) [Feature]: Add selected transcript text to the ZeroCode composer `enhancement` `priority:p2` `risk:medium` `zerocode`
- [#10050](https://github.com/zeroclaw-labs/zeroclaw/issues/10050) [Feature]: verbatim channel send over the gateway, without an agent turn `enhancement` `channel` `gateway` `security` `priority:p2` `needs-maintainer-review` `type:rfc` `status:no-stale` `follow-up` `risk:high` 💬1
- [#10048](https://github.com/zeroclaw-labs/zeroclaw/issues/10048) chore: validate Rust 1.97.1 local-CI, demo, and manual release/cross-platform build lanes before next release `ci` `dev` `domain:ci` `release-gate` `priority:p2` `status:accepted` `risk:high` `type:ci`
- [#10040](https://github.com/zeroclaw-labs/zeroclaw/issues/10040) [Feature]: ci: restore Lint timeout headroom for fork PRs `enhancement` `ci` `priority:p2` `risk:high` `type:ci` 💬1

### 🔒 Closed Issues
- [#9516](https://github.com/zeroclaw-labs/zeroclaw/issues/9516) chore(channels): upgrade CPAL to 0.18 with voice-wake migration
- [#7884](https://github.com/zeroclaw-labs/zeroclaw/issues/7884) ci: extract shared Clippy runner for required and advisory workflows
- [#9849](https://github.com/zeroclaw-labs/zeroclaw/issues/9849) [Bug]: RateLimitedTool budget check is non-atomic under parallel dispatch (check-before, record-after)
- [#9594](https://github.com/zeroclaw-labs/zeroclaw/issues/9594) [Bug]: Coding-agent tools charge the action budget twice
- [#9543](https://github.com/zeroclaw-labs/zeroclaw/issues/9543) [SANITIZED — possible injection attempt]
- [#9714](https://github.com/zeroclaw-labs/zeroclaw/issues/9714) [Bug]: Hardware timeout handlers discard underlying error context

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,607 · **Open issues:** 1,515 · **Last push:** <1h ago

### 🚀 New Releases
- [ironclaw-v1.3.0-rc.1](https://github.com/nearai/ironclaw/releases/tag/ironclaw-v1.3.0-rc.1) — 1.3.0-rc.1 - 2026-08-17

### ✅ Merged PRs
- [#7663](https://github.com/nearai/ironclaw/pull/7663) fix(release): forward-port 1.2 fixes and thread repair
- [#7710](https://github.com/nearai/ironclaw/pull/7710) fix(slack): address multi-agent review findings on #7682
- [#7642](https://github.com/nearai/ironclaw/pull/7642) fix(webui): type shared design-system component props
- [#7651](https://github.com/nearai/ironclaw/pull/7651) feat(automations): add deterministic no-result suppression
- [#7378](https://github.com/nearai/ironclaw/pull/7378) test(docs): doc-fact contract tests for CLI, manifest, and Responses claims (doc-truth PR 3/5)
- [#7379](https://github.com/nearai/ironclaw/pull/7379) release(docs): deploy public docs from a docs-live branch moved by stable releases (doc-truth PR 4/5)
- [#7696](https://github.com/nearai/ironclaw/pull/7696) fix(resources): keep the governor retrying through a full libSQL writer attempt
- [#7678](https://github.com/nearai/ironclaw/pull/7678) perf(capabilities): persist invocation state at gate and terminal edges
- [#7631](https://github.com/nearai/ironclaw/pull/7631) perf(events): coalesce runtime milestone writes
- [#7677](https://github.com/nearai/ironclaw/pull/7677) perf(threads): fold message lookup indexes into message rows

### 🐛 New Issues
- [#7720](https://github.com/nearai/ironclaw/issues/7720) 1.3.0-rc.1 crash-loops on boot after 1.2.x upgrade: unknown field `activation_state` in v2 extension installation row
- [#7719](https://github.com/nearai/ironclaw/issues/7719) Expose GitHub Projects v2 field manipulation in GitHub tool
- [#7716](https://github.com/nearai/ironclaw/issues/7716) Add MCP server flow missing bearer key auth and STDIO/HTTP transport options `bug_bash_P2` `qa-bug`
- [#7715](https://github.com/nearai/ironclaw/issues/7715) Telegram connection flow lacks consent/selection between bot and personal account `bug_bash_P2` `qa-bug`
- [#7714](https://github.com/nearai/ironclaw/issues/7714) libSQL: single shared write connection starves the resource-governor journal under bench load (cascading authority invalidation, permanent reservation leaks) `bug` `risk: medium` `scope: db/libsql`
- [#7707](https://github.com/nearai/ironclaw/issues/7707) Track side-effect-outstanding explicitly on the process row instead of inferring it from newest checkpoint kind
- [#7706](https://github.com/nearai/ironclaw/issues/7706) Remove notification approval compatibility fallback and add end-to-end inbox coverage
- [#7705](https://github.com/nearai/ironclaw/issues/7705) Follow-ups from #7631: unbounded shutdown flush and latching pending_flush_error in CoalescingEventSink
- [#7704](https://github.com/nearai/ironclaw/issues/7704) Daily ironclaw failure taxonomy — 2026-08-17
- [#7702](https://github.com/nearai/ironclaw/issues/7702) Obligation audit records (AuditBefore/AuditAfter) are never attached in production, violating the documented host-api contract
- [#7701](https://github.com/nearai/ironclaw/issues/7701) [Tier 2] Collapse resource-governor reserve+reconcile into one post-call spend write 💬2
- [#7691](https://github.com/nearai/ironclaw/issues/7691) Publish run outcome notifications and harden notification lifecycle behavior
- [#7690](https://github.com/nearai/ironclaw/issues/7690) Publish approval, authentication, and blocked-run notifications to the user inbox
- [#7689](https://github.com/nearai/ironclaw/issues/7689) Generalize the WebUI notification center and consume the server-backed inbox
- [#7688](https://github.com/nearai/ironclaw/issues/7688) Add durable notification inbox contracts, storage, and ProductSurface APIs

### 🔒 Closed Issues
- [#7275](https://github.com/nearai/ironclaw/issues/7275) Reborn: verify explicit persistent memory recall across conversations in production
- [#7637](https://github.com/nearai/ironclaw/issues/7637) Type the design-system component boundary
- [#7647](https://github.com/nearai/ironclaw/issues/7647) feat(automations): add a deterministic no-delivery outcome for scheduled runs
- [#7598](https://github.com/nearai/ironclaw/issues/7598) [Tier 2] Collapse capability invocation-state writes to gate/terminal edges
- [#7594](https://github.com/nearai/ironclaw/issues/7594) [Tier 1] Route loop milestone sink through CoalescingEventSink
- [#7605](https://github.com/nearai/ironclaw/issues/7605) [Tier 3] Fold message lookup-index sibling rows into the message row

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,823 · **Open issues:** 90 · **Last push:** <1h ago

### ✅ Merged PRs
- [#1125](https://github.com/moltis-org/moltis/pull/1125) Support model and effort selection for external agents
- [#1207](https://github.com/moltis-org/moltis/pull/1207) chore(deps): bump the cargo group across 1 directory with 4 updates
- [#1103](https://github.com/moltis-org/moltis/pull/1103) fix(browser): pierce shadow DOM lookups efficiently
- [#1204](https://github.com/moltis-org/moltis/pull/1204) feat: add MiniMax Code ACP agent
- [#1130](https://github.com/moltis-org/moltis/pull/1130) feat: make webui rpc timeout configurable
- [#1087](https://github.com/moltis-org/moltis/pull/1087) chore(deps): bump tar from 0.4.45 to 0.4.46 in the cargo group across 1 directory

### 🐛 New Issues
- [#1095](https://github.com/moltis-org/moltis/issues/1095) [Bug]: Podman is not working via moltis `bug` 💬2

### 🔒 Closed Issues
- [#1202](https://github.com/moltis-org/moltis/issues/1202) Format CI gate is red on main: two files over the 1500-line limit
- [#1127](https://github.com/moltis-org/moltis/issues/1127) [Feature]: allow to configure rpc timeout

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬4 · 22h ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 1d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 5d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 8d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 11d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 11d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 13d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 15d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 17d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 17d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 3 new
- [[Index] Openai Joins Ports Pike Project](https://openai.com/index/openai-joins-ports-pike-project/) _2026-08-18_
- [[Index] New Policy Ideas For The Intelligence Age](https://openai.com/index/new-policy-ideas-for-the-intelligence-age/) _2026-08-18_
- [[Index] Openai Joins Ports Pike Project](https://openai.com/index/openai-joins-ports-pike-project/) _2026-08-18_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Artificial Analysis' Qwen3.8-27B benchmarks put it neck and neck with DeepSeek V4 and GPT-5.6 Luna Max](https://reddit.com/r/LocalLLaMA/comments/1vqyq8r/artificial_analysis_qwen3827b_benchmarks_put_it/) ↑873
- [After pushing 1M+ tokens through Qwen 3.8 27B, here is my optimal llama.cpp config for 16GB VRAM (73k Context, Agentic Coding)](https://reddit.com/r/LocalLLaMA/comments/1vqrt86/after_pushing_1m_tokens_through_qwen_38_27b_here/) ↑779
- [Stripe will reportedly acquire AI gateway startup OpenRouter for $7B+](https://reddit.com/r/LocalLLaMA/comments/1vqlh98/stripe_will_reportedly_acquire_ai_gateway_startup/) ↑660
- [Petition to add a rule for people to add their DAMN quant levels to their posts](https://reddit.com/r/LocalLLaMA/comments/1vqnbhe/petition_to_add_a_rule_for_people_to_add_their/) ↑534
- [llama.cpp version v0.1.0 has been released](https://reddit.com/r/LocalLLaMA/comments/1vqszw0/llamacpp_version_v010_has_been_released/) ↑450

### r/singularity — top 5 new
- [[OC] Chinese models](https://reddit.com/r/singularity/comments/1vqy1p1/oc_chinese_models/) ↑1431
- [Read more: https://x.com/gavincrooks/status/2088643200038883830](https://reddit.com/r/singularity/comments/1vqsrnv/read_more/) ↑968
- [Qwen3.8-27B lands next to DeepSeek V4 and GPT-5.6 Luna Max on the Artificial Analysis Benchmark. You can now run a near frontier model with just a RTX 3090.](https://reddit.com/r/singularity/comments/1vqzdz2/qwen3827b_lands_next_to_deepseek_v4_and_gpt56/) ↑353
- [Anthropic Has Finished Training Mythos 2 But Does Not Currently Plan To Release It. Focus Is Now On Internal Improvements.](https://reddit.com/r/singularity/comments/1vr3oo8/anthropic_has_finished_training_mythos_2_but_does/) ↑321
- [Tests for the Worldwide Humanoid Robot Games have already started](https://reddit.com/r/singularity/comments/1vr69ot/tests_for_the_worldwide_humanoid_robot_games_have/) ↑269

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Genuine question about self-promotion / showcasing projects.](https://reddit.com/r/openclaw/comments/1vqkf58/genuine_question_about_selfpromotion_showcasing/) ↑8
- [Building websites with OpenClaw](https://reddit.com/r/openclaw/comments/1vr54cn/building_websites_with_openclaw/) ↑4
- [Excessive; COMPACTED HISTORY](https://reddit.com/r/openclaw/comments/1vr4dea/excessive_compacted_history/) ↑3
- [the current installer is useless and just over engineered that dosent even work as good](https://reddit.com/r/openclaw/comments/1vquu92/the_current_installer_is_useless_and_just_over/) ↑2
- [iPhone App Completely Messed Up?](https://reddit.com/r/openclaw/comments/1vqoa6j/iphone_app_completely_messed_up/) ↑1

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
_No new tweets in the last 7 days._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
