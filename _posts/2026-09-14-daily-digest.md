---
layout: post
title: "Ecosystem Digest — 2026-09-14"
date: 2026-09-14 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-14
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 389,623 | 8 | 3 | 10 | 0 |
| **hermesagent** | 245,184 | 6 | 4 | 3 | 0 |
| **ZeroClaw** | 32,795 | 7 | 5 | 10 | 0 |
| **IronClaw** | 12,619 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,859 | 1 | 2 | 4 | 1 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 389,623 · **Open issues:** 7,150 · **Last push:** <1h ago

### ✅ Merged PRs
- [#147593](https://github.com/openclaw/openclaw/pull/147593) perf: avoid redundant byte copies in Workshop text validation
- [#147672](https://github.com/openclaw/openclaw/pull/147672) perf(logging): avoid empty redaction edit sets
- [#147585](https://github.com/openclaw/openclaw/pull/147585) fix(tasks): record execution ownership and settle orphaned records at restore
- [#147671](https://github.com/openclaw/openclaw/pull/147671) refactor(gateway): reuse cron validation response helpers
- [#147670](https://github.com/openclaw/openclaw/pull/147670) fix(ui): keep consumed prompts from reappearing
- [#147663](https://github.com/openclaw/openclaw/pull/147663) perf(sqlite): reuse prepared table existence probes
- [#147574](https://github.com/openclaw/openclaw/pull/147574) fix(ui): load Home and System busyness inside their panels
- [#147500](https://github.com/openclaw/openclaw/pull/147500) refactor(android): simplify recap test fixtures
- [#147617](https://github.com/openclaw/openclaw/pull/147617) refactor(matrix): own room history tracker factory
- [#145869](https://github.com/openclaw/openclaw/pull/145869) refactor(setup): share inference option projection

### 🐛 New Issues
- [#147728](https://github.com/openclaw/openclaw/issues/147728) [Bug]: xAI OAuth inference 426s: x-grok-client-version carries OpenClaw's version, and isolated/utility completions omit the Grok headers entirely
- [#147722](https://github.com/openclaw/openclaw/issues/147722) Control UI: cannot turn off Labs "Gateway Host Desktop" — desktop.host.enabled is a required boolean so the Labs reset patch is rejected
- [#147719](https://github.com/openclaw/openclaw/issues/147719) [Bug]: /btw does not open the side chat or focus its composer `maintainer` 💬1
- [#147717](https://github.com/openclaw/openclaw/issues/147717) [Bug]: doctor --fix cannot complete legacy state migration until invalid config is manually repaired (2026.9.4 upgrade) `clawsweeper:needs-info` `impact:session-state` `P0` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-release-blocker` 💬1
- [#147715](https://github.com/openclaw/openclaw/issues/147715) Code Mode result fitting repeats captured byte counts `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` 💬1
- [#147710](https://github.com/openclaw/openclaw/issues/147710) Avoid repeated install-choice catalog work in non-interactive provider setup `maintainer` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` 💬1
- [#147704](https://github.com/openclaw/openclaw/issues/147704) Real-world autonomous business deployment: 105 operational challenges and improvement opportunities `enhancement` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:needs-info` `impact:security` `P0` `issue-rating: 🦪 silver shellfish` `impact:ux-release-blocker` 💬2
- [#147701](https://github.com/openclaw/openclaw/issues/147701) [Bug]: Robinhood MCP session DELETE returns 400 after successful catalog discovery `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1

### 🔒 Closed Issues
- [#143420](https://github.com/openclaw/openclaw/issues/143420) Forced drain timeout leaves background task records running; successor restart drains on them again
- [#147690](https://github.com/openclaw/openclaw/issues/147690) Sub-agent completion announces direct-deliver to the owner's personal chat when the requester is an agent (AI orchestrator)
- [#135658](https://github.com/openclaw/openclaw/issues/135658) [Bug]: 2026.8.2 delivers the synthesized "no final summary was produced" fallback for cron jobs that deliberately end with NO_REPLY after tool calls (2026.8.1 stayed silent)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 245,184 · **Open issues:** 42,801 · **Last push:** <1h ago

### ✅ Merged PRs
- [#109532](https://github.com/NousResearch/hermes-agent/pull/109532) fix(cron): hold wall-clock cron hours and real elapsed intervals across DST (salvage #98553, #109414 + qwen-code#11723 guard)
- [#110346](https://github.com/NousResearch/hermes-agent/pull/110346) Reasoning effort selectable on every model picker (hermes model, aux models, /model CLI + TUI)
- [#109502](https://github.com/NousResearch/hermes-agent/pull/109502) Profile clones no longer carry messaging bot credentials (--clone-channels opts in); gateway.multiplex_profiles registered; explicit migrate --multiplex flips the flag

### 🐛 New Issues
- [#110472](https://github.com/NousResearch/hermes-agent/issues/110472) apps/desktop: electron 40.x carries an open HIGH advisory that npm audit misreports as fixed at 40.10.6 (real fix is 41.10.3, never backported) `type/security` `P3` `dependencies` `comp/desktop`
- [#110469](https://github.com/NousResearch/hermes-agent/issues/110469) [Bug]: Windows start attestation is PID-only — a stale marker can authorize a cold start, and PID reuse can suppress a real recovery `type/bug` `comp/cli` `comp/gateway` `P2` `sweeper:risk-platform-windows` `platform/windows` `area/install-update`
- [#110467](https://github.com/NousResearch/hermes-agent/issues/110467) Работа `invalid` `P3` 💬1
- [#110464](https://github.com/NousResearch/hermes-agent/issues/110464) write denylist drifted from the read credential denylist `type/security` `comp/agent` `tool/file` `area/auth` `P3`
- [#110456](https://github.com/NousResearch/hermes-agent/issues/110456) [Bug]: skill_view treats Markdown under prompts/ as a legacy flat skill `type/bug` `comp/agent` `tool/skills` `P2` 💬2
- [#110448](https://github.com/NousResearch/hermes-agent/issues/110448) Aux recovery ladder: a failed auth-refresh retry escapes instead of falling through to the configured fallback_chain `type/bug` `comp/agent` `provider/nous` `area/auth` `P2`

### 🔒 Closed Issues
- [#110424](https://github.com/NousResearch/hermes-agent/issues/110424) 1Password vault backend binds a Login item to only its first URL, so multi-website items can't fill on their other origins
- [#85209](https://github.com/NousResearch/hermes-agent/issues/85209) Model picker should show only the reasoning-effort levels a model actually supports
- [#108383](https://github.com/NousResearch/hermes-agent/issues/108383) Dashboard chat (/chat) sessions never go live: stuck "Setup Required"/queued forever, while CLI (hermes chat) works fine on same gateway
- [#62333](https://github.com/NousResearch/hermes-agent/issues/62333) [Bug]: OAuth refresh_token erased on every token refresh - MCP servers die ~1h after login

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,795 · **Open issues:** 832 · **Last push:** 7h ago

### ✅ Merged PRs
- [#10819](https://github.com/zeroclaw-labs/zeroclaw/pull/10819) fix(tools): expand only a leading tilde in knowledge.db_path
- [#10248](https://github.com/zeroclaw-labs/zeroclaw/pull/10248) feat(security): canonical principals and shared grant resolution (#8289 stage 2, supersedes #8672 in part)
- [#10414](https://github.com/zeroclaw-labs/zeroclaw/pull/10414) fix(cron): guard agent manual trigger and history
- [#10646](https://github.com/zeroclaw-labs/zeroclaw/pull/10646) ci(docs): check all authored internal links
- [#10686](https://github.com/zeroclaw-labs/zeroclaw/pull/10686) fix(config): map openai-chat/openai_chat V2 kind to canonical openai family
- [#10016](https://github.com/zeroclaw-labs/zeroclaw/pull/10016) fix(hooks): correlate webhook audit calls by identity
- [#10554](https://github.com/zeroclaw-labs/zeroclaw/pull/10554) fix(tools): reuse configured provider refs for agents
- [#10240](https://github.com/zeroclaw-labs/zeroclaw/pull/10240) docs(contributing): narrow screenshot evidence rule
- [#9927](https://github.com/zeroclaw-labs/zeroclaw/pull/9927) feat(intake): narrow RFC routing across intake surfaces
- [#10598](https://github.com/zeroclaw-labs/zeroclaw/pull/10598) chore(deps): bump docker/setup-buildx-action from 3.11.1 to 4.3.0

### 🐛 New Issues
- [#10842](https://github.com/zeroclaw-labs/zeroclaw/issues/10842) [Bug]: Telegram reaction tool silently no-ops, inherited Channel trait default returns Ok(()) without calling the Telegram API
- [#10828](https://github.com/zeroclaw-labs/zeroclaw/issues/10828) [Bug]: openai-codex --device-code uses obsolete/incorrect OpenAI device auth endpoint and returns 404 `bug` `docs` `provider` `provider:openai` `domain:security` `priority:p1` `status:accepted` `risk:high` `cli` 💬1
- [#10826](https://github.com/zeroclaw-labs/zeroclaw/issues/10826) [Feature]: Make ZeroCode session root selection explicit and preserve resumed roots `enhancement` `docs` `runtime` `priority:p2` `status:accepted` `follow-up` `risk:medium` `zerocode` `channel:acp` `cli` 💬1
- [#10822](https://github.com/zeroclaw-labs/zeroclaw/issues/10822) [Feature]: `config/set-many` — atomic batch config mutation over RPC `enhancement` `config` `runtime` `security` `domain:security` `priority:p2` `status:in-progress` `status:accepted` `follow-up` `risk:high` 💬1
- [#10821](https://github.com/zeroclaw-labs/zeroclaw/issues/10821) [Bug]: `zeroclaw service logs` shows stale stderr as current — service-installed daemon emits no tracing to stderr without `--verbose` `bug` `daemon` `observability` `runtime` `service` `observability:log` `priority:p2` `status:accepted` `follow-up` `risk:medium` `cli` 💬1
- [#10814](https://github.com/zeroclaw-labs/zeroclaw/issues/10814) [Tracker]: Release efficiency and repeatable publication `priority:p1` `risk:high` `type:ci` `type:tracker`
- [#10812](https://github.com/zeroclaw-labs/zeroclaw/issues/10812) [Feature]: Populate DocumentMessage.jpegThumbnail so PDFs sent over WhatsApp preview on phones `enhancement` `channel` `channel:whatsapp` `priority:p3` `risk:medium` 💬1

### 🔒 Closed Issues
- [#10837](https://github.com/zeroclaw-labs/zeroclaw/issues/10837) [Bug]: RPC config/set persists values that Config::validate() rejects; gateway PATCH and CLI do not
- [#10721](https://github.com/zeroclaw-labs/zeroclaw/issues/10721) [Bug]: knowledge.db_path tilde expansion is a global replace, not a home prefix - knowledge tool silently dropped
- [#10324](https://github.com/zeroclaw-labs/zeroclaw/issues/10324) [Bug]: cron manual trigger and run-history reads remain check-then-act across an agent rename
- [#10580](https://github.com/zeroclaw-labs/zeroclaw/issues/10580) [Feature]: Docs links gate should catch dangling internal links repo-wide, not only added links
- [#10533](https://github.com/zeroclaw-labs/zeroclaw/issues/10533) [Bug]: model_routing_config rejects custom.* (and other valid) provider slots — tool validation diverges from config schema

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,619 · **Open issues:** 1,523 · **Last push:** 5h ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,859 · **Open issues:** 83 · **Last push:** 1h ago

### 🚀 New Releases
- [20260913.02](https://github.com/moltis-org/moltis/releases/tag/20260913.02) — 20260913.02

### ✅ Merged PRs
- [#1266](https://github.com/moltis-org/moltis/pull/1266) feat(chat): persist configurable default reasoning effort
- [#1263](https://github.com/moltis-org/moltis/pull/1263) chore(deps): bump the npm_and_yarn group across 2 directories with 4 updates
- [#1253](https://github.com/moltis-org/moltis/pull/1253) feat(reasoning): add max effort level
- [#1265](https://github.com/moltis-org/moltis/pull/1265) fix(telegram): expose shared-chat tool policy controls

### 🐛 New Issues
- [#1268](https://github.com/moltis-org/moltis/issues/1268) Could Moltis expose an optional advanced memory provider?

### 🔒 Closed Issues
- [#1259](https://github.com/moltis-org/moltis/issues/1259) [Feature]: Configurable default reasoning/thinking level (persist across sessions)
- [#1264](https://github.com/moltis-org/moltis/issues/1264) [Bug]: Tools stop working in shared Telegram channels

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 6d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 8d ago
- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬2 · 12d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 14d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 16d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 20d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 32d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 35d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 38d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 40d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [This seems more probable than it was before.](https://reddit.com/r/LocalLLaMA/comments/1wepx7w/this_seems_more_probable_than_it_was_before/) ↑1720
- [The Hugging Bay](https://reddit.com/r/LocalLLaMA/comments/1weujw6/the_hugging_bay/) ↑1037
- [The Local LLM community feels like the golden era of the internet all over again](https://reddit.com/r/LocalLLaMA/comments/1wf3i1m/the_local_llm_community_feels_like_the_golden_era/) ↑871
- [3k$ 128GB VRAM + 256GB RAM DDR4 Server](https://reddit.com/r/LocalLLaMA/comments/1wfe9zt/3k_128gb_vram_256gb_ram_ddr4_server/) ↑567
- [The rhetoric is really heating up!](https://reddit.com/r/LocalLLaMA/comments/1wf6nbi/the_rhetoric_is_really_heating_up/) ↑127

### r/singularity — top 2 new
- [Trump is refusing a slowdown](https://reddit.com/r/singularity/comments/1wfduzz/trump_is_refusing_a_slowdown/) ↑1774
- [Astra notices user isn't paying attention, makes the Mac beep](https://reddit.com/r/singularity/comments/1wfnrqj/astra_notices_user_isnt_paying_attention_makes/) ↑637

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw Dashboards DEMO!](https://reddit.com/r/openclaw/comments/1wc2tzc/openclaw_dashboards_demo/) ↑14
- [OpenClaw to the Rescue!](https://reddit.com/r/openclaw/comments/1wfl8os/openclaw_to_the_rescue/) ↑9
- [Local Hosting? Disable Session Observer.](https://reddit.com/r/openclaw/comments/1wfebmu/local_hosting_disable_session_observer/) ↑7
- [Does anyone have their agent generate a visual daily brief?](https://reddit.com/r/openclaw/comments/1we3ran/does_anyone_have_their_agent_generate_a_visual/) ↑5
- [Opinions about your AI memory](https://reddit.com/r/openclaw/comments/1wfcrh6/opinions_about_your_ai_memory/) ↑1

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [🦞 OpenClaw v2026.9.4 is out, thank you to all 293 contributors!

🧩 Find your next plugin or skill
🧠 Turn old chats into ](https://x.com/openclaw/status/2098449762119020926)

### X — @steipete
- [Next release (or dev channel) does worktrees ~80% faster via apfs/brtfs/xfs/ReFS folder clones.

Also saves lots of disk](https://x.com/steipete/status/2099197266636783989) ↑0 🔁0 · recent
- [This is all written in Rust.
Because you can't escape Rust.](https://x.com/steipete/status/2099201162922938418) ↑0 🔁0 · recent
- [Fixed so many little perf issues that didn't matter much for single users... before we made it good for teams. 

OC stem](https://x.com/steipete/status/2099195896508617141) ↑0 🔁0 · recent
- [If you haven't given Linux a go lately, try with agents.
You can fix anything with a prompt now.

Got a Dell XPS. Webcam](https://x.com/steipete/status/2099172248213225791) ↑0 🔁0 · recent
- [Yeah, was just about to say the same.](https://x.com/steipete/status/2099171190925640188) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
