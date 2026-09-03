---
layout: post
title: "Ecosystem Digest — 2026-09-03"
date: 2026-09-03 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-03
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 388,668 | 6 | 5 | 10 | 0 |
| **hermesagent** | 240,158 | 7 | 2 | 8 | 0 |
| **ZeroClaw** | 32,714 | 11 | 7 | 10 | 0 |
| **IronClaw** | 12,604 | 7 | 4 | 9 | 0 |
| **Moltis** | 2,843 | 2 | 0 | 0 | 3 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 388,668 · **Open issues:** 6,102 · **Last push:** <1h ago

### ✅ Merged PRs
- [#135707](https://github.com/openclaw/openclaw/pull/135707) refactor(anthropic): share model ref parsing
- [#135177](https://github.com/openclaw/openclaw/pull/135177) chore(deps): refresh seven-day eligible packages
- [#136809](https://github.com/openclaw/openclaw/pull/136809) refactor(cron): settle fixture cores before teardown
- [#135886](https://github.com/openclaw/openclaw/pull/135886) refactor(release): share ASCII comparator
- [#136796](https://github.com/openclaw/openclaw/pull/136796) fix(e2e): unblock stable Docker upgrade survivor validation
- [#136799](https://github.com/openclaw/openclaw/pull/136799) chore(cron): require the previous daily occurrence in tests
- [#135732](https://github.com/openclaw/openclaw/pull/135732) refactor(imessage): share GUID normalization
- [#136718](https://github.com/openclaw/openclaw/pull/136718) chore(macos): adopt Peekaboo 4.3.0
- [#128482](https://github.com/openclaw/openclaw/pull/128482) fix(ui): stop media prompts after leaving Appearance
- [#136793](https://github.com/openclaw/openclaw/pull/136793) fix(bench): keep synthetic Gateways off LAN discovery

### 🐛 New Issues
- [#136842](https://github.com/openclaw/openclaw/issues/136842) [Bug]: build-artifacts red on every PR since 2026-09-03 01:40Z — Control UI startup JS gzip 125 B over the enforcement limit 💬1
- [#136841](https://github.com/openclaw/openclaw/issues/136841) [Bug]: GitHub hovercards hide rate-limit and credential recovery guidance `bug` `maintainer` 💬1
- [#136834](https://github.com/openclaw/openclaw/issues/136834) [Bug]: Swarm fan-out fails at the Code Mode bridge limit `bug` `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` 💬1
- [#136831](https://github.com/openclaw/openclaw/issues/136831) [Bug]: Native prompt annotation slows down with unrelated transcript history `bug` `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#136821](https://github.com/openclaw/openclaw/issues/136821) Session assignment omits teammates for archived conversations `bug` `maintainer` `P1` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#136818](https://github.com/openclaw/openclaw/issues/136818) Session tools lose role-aware visibility and need generalized bulk patch targets `maintainer` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#136837](https://github.com/openclaw/openclaw/issues/136837) [Bug]: WhatsApp channel: outbound "sent message" log falsely confirms delivery when a concurrent send to a different target overlaps
- [#136824](https://github.com/openclaw/openclaw/issues/136824) [Bug]:  飞书所有账号消息无响应 - 2026.8.2 回归 Bug
- [#136815](https://github.com/openclaw/openclaw/issues/136815) 8.2: assistant commentary text rendered 3x in Control UI during tool runs (streaming dedupe regression)
- [#136791](https://github.com/openclaw/openclaw/issues/136791) [Bug]: Gateway benchmarks leave LAN discovery enabled on macOS
- [#136804](https://github.com/openclaw/openclaw/issues/136804) [Bug]: Control UI renders assistant process text 3x when a reply contains tool calls

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 240,158 · **Open issues:** 38,620 · **Last push:** <1h ago

### ✅ Merged PRs
- [#92164](https://github.com/NousResearch/hermes-agent/pull/92164) perf(process): poll sandbox job logs for new bytes only
- [#96633](https://github.com/NousResearch/hermes-agent/pull/96633) fix(relay): upgrade to 0.8.3
- [#101725](https://github.com/NousResearch/hermes-agent/pull/101725) perf(state): exclude cron sessions from the trigram FTS index (salvage #101266)
- [#101720](https://github.com/NousResearch/hermes-agent/pull/101720) fix(state): bound FTS indexing for large tool results (salvage #93834)
- [#101709](https://github.com/NousResearch/hermes-agent/pull/101709) fix(agent): evict stale screenshot payloads from the outbound copy before send (salvage #97889)
- [#101714](https://github.com/NousResearch/hermes-agent/pull/101714) fix(search): bounded, fail-closed search_files fallbacks with shared engine/ordering policy (salvage #97770)
- [#101707](https://github.com/NousResearch/hermes-agent/pull/101707) perf(agent): accumulate streamed reply text as parts instead of rebuilding per delta (salvage #92166)
- [#101703](https://github.com/NousResearch/hermes-agent/pull/101703) perf(mcp): skip npx's resident parent when the package is already cached (salvage #93083)

### 🐛 New Issues
- [#101803](https://github.com/NousResearch/hermes-agent/issues/101803) Custom/local Ollama provider: instant [Errno 65] No route to host on every chat completion, while curl to the same endpoint always succeeds `type/bug` `comp/agent` `comp/gateway` `provider/ollama` `area/config` `P2` `needs-repro` `sweeper:risk-compatibility`
- [#101800](https://github.com/NousResearch/hermes-agent/issues/101800) Rate-limit exit sentinel is unreachable: quota exhaustion is misclassified as a clean-exit protocol violation and crashloops the board `type/bug` `comp/cli` `comp/cron` `P3` `area/usage-cost`
- [#101789](https://github.com/NousResearch/hermes-agent/issues/101789) Windows desktop update fails at final swap: rename of release\win-unpacked blocked by third-party process whose CWD is inside it (e.g. SogouCloud.exe) `type/bug` `P2` `sweeper:risk-compatibility` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows` `area/install-update`
- [#101788](https://github.com/NousResearch/hermes-agent/issues/101788) kanban reclaim releases a claim without noticing the worktree has uncommitted work `type/bug` `comp/cron` `P3` `sweeper:risk-session-state`
- [#101786](https://github.com/NousResearch/hermes-agent/issues/101786) [Bug]: 项目级技能无法在项目的会话中通过/唤醒和调用 `type/bug` `duplicate` `tool/skills` `area/config` `P2` `sweeper:risk-session-state` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows` `bug` `area/sessions` 💬1
- [#101785](https://github.com/NousResearch/hermes-agent/issues/101785) kanban complete succeeds on a blocked task, silently erasing a needs_input gate (and the dispatcher's own auto-block) `type/bug` `comp/cron` `P3` `sweeper:risk-session-state`
- [#101783](https://github.com/NousResearch/hermes-agent/issues/101783) Discord typing indicator persists after idle (leaked _keep_typing task) `type/bug` `comp/gateway` `platform/discord` `P2` `sweeper:risk-message-delivery` 💬1

### 🔒 Closed Issues
- [#98077](https://github.com/NousResearch/hermes-agent/issues/98077) [Field report]: state.db physical cross-B-tree corruption under SQLite 3.50.4 WAL; canonical writes continued after malformed detection
- [#52945](https://github.com/NousResearch/hermes-agent/issues/52945) Dashboard inherits HERMES_WEB_DIST from Desktop, loading wrong frontend / Dashboard 继承 Desktop 的 HERMES_WEB_DIST，加载错误前端

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,714 · **Open issues:** 803 · **Last push:** 8h ago

### ✅ Merged PRs
- [#10441](https://github.com/zeroclaw-labs/zeroclaw/pull/10441) ci(codeql): route Rust analysis to Blacksmith
- [#10477](https://github.com/zeroclaw-labs/zeroclaw/pull/10477) fix(zerocode): satisfy Rust 1.98 drain lint
- [#10517](https://github.com/zeroclaw-labs/zeroclaw/pull/10517) docs(mdbook): pin mdBook 0.5.4
- [#10481](https://github.com/zeroclaw-labs/zeroclaw/pull/10481) fix(channels/matrix): preserve reasoning source identity
- [#10476](https://github.com/zeroclaw-labs/zeroclaw/pull/10476) fix(config): complete required sections across CLI processes
- [#10081](https://github.com/zeroclaw-labs/zeroclaw/pull/10081) fix(web): show channel descriptor defaults in Quickstart
- [#10478](https://github.com/zeroclaw-labs/zeroclaw/pull/10478) fix(tests): gate POSIX device assertion to Unix
- [#10459](https://github.com/zeroclaw-labs/zeroclaw/pull/10459) fix(mcp): preserve persistent SSE event boundaries
- [#10516](https://github.com/zeroclaw-labs/zeroclaw/pull/10516) fix(ci): align CLI and hardware labels
- [#10380](https://github.com/zeroclaw-labs/zeroclaw/pull/10380) fix(zerocode): restore persisted ACP transcripts

### 🐛 New Issues
- [#10558](https://github.com/zeroclaw-labs/zeroclaw/issues/10558) [Bug]: Cranelift CI hits 20-minute job timeout despite passing final tests `bug`
- [#10550](https://github.com/zeroclaw-labs/zeroclaw/issues/10550) [Feature]: bound skill HTTP DNS resolution and test the full dispatch seam `enhancement`
- [#10549](https://github.com/zeroclaw-labs/zeroclaw/issues/10549) RFC: Simplify RFC voting by removing mandatory discussion windows and making REVISE stop the current snapshot `enhancement` `docs` `core` `needs-maintainer-review` `type:rfc` `status:no-stale` 💬1
- [#10548](https://github.com/zeroclaw-labs/zeroclaw/issues/10548) [Bug]: Preserve Mermaid diagram accessibility inside the zoom dialog `bug`
- [#10547](https://github.com/zeroclaw-labs/zeroclaw/issues/10547) [Bug]: Preserve 85% docs reader scale after reload `bug`
- [#10546](https://github.com/zeroclaw-labs/zeroclaw/issues/10546) Extract cron into a dedicated zeroclaw-cron crate
- [#10540](https://github.com/zeroclaw-labs/zeroclaw/issues/10540) [Feature]: Report Web dashboard availability in zeroclaw status `enhancement` `gateway` `runtime` `status:in-progress` `priority:p3` `risk:medium` `web` `cli` 💬1
- [#10536](https://github.com/zeroclaw-labs/zeroclaw/issues/10536) [Bug]: macOS Seatbelt ignores configured allowed_roots for shell commands `bug` `config` `runtime` `security` `tool` `domain:security` `priority:p1` `tool:shell` `status:in-progress` `risk:high` 💬1
- [#10535](https://github.com/zeroclaw-labs/zeroclaw/issues/10535) [Task]: resolve the zerocode SOP pane's read-only gate `enhancement` `docs` `domain:security` `priority:p2` `tool:sop` `zerocode` `risk:high` `cli` 💬1
- [#10534](https://github.com/zeroclaw-labs/zeroclaw/issues/10534) [Bug]: bounded delegates silently strip the delegate tool, contradicting delegation_policy/max_delegation_depth config `bug` `docs` `agent` `config` `runtime` `security` `tool` `tool:delegate` `security:policy` `domain:security` `priority:p2` `risk:high` 💬1
- [#10533](https://github.com/zeroclaw-labs/zeroclaw/issues/10533) [Bug]: model_routing_config rejects custom.* (and other valid) provider slots — tool validation diverges from config schema `bug` `config` `provider` `tool` `provider:router` `domain:architecture` `priority:p1` `status:in-progress` `risk:high` 💬1

### 🔒 Closed Issues
- [#10510](https://github.com/zeroclaw-labs/zeroclaw/issues/10510) [Docs]: Upgrade mdBook to 0.5.4 and adopt built-in image zoom
- [#10561](https://github.com/zeroclaw-labs/zeroclaw/issues/10561) [Bug]: Windows cron workspace assertion rejects POSIX path representation
- [#10193](https://github.com/zeroclaw-labs/zeroclaw/issues/10193) [Bug]: Matrix full reasoning can collide with generated thinking status
- [#10147](https://github.com/zeroclaw-labs/zeroclaw/issues/10147) [Bug]: Explicit config init sections cannot be completed across CLI processes
- [#9760](https://github.com/zeroclaw-labs/zeroclaw/issues/9760) bug(web): display channel descriptor defaults in Quickstart
- [#10456](https://github.com/zeroclaw-labs/zeroclaw/issues/10456) [Bug]: Persistent MCP SSE reader accepts a suffix after an oversized event
- [#9680](https://github.com/zeroclaw-labs/zeroclaw/issues/9680) [Feature]: ci: audit remaining CLI and hardware path-label ownership

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,604 · **Open issues:** 1,505 · **Last push:** 1h ago

### ✅ Merged PRs
- [#8051](https://github.com/nearai/ironclaw/pull/8051) fix(reply): the answer is the current model call's text; earlier calls are narration
- [#8050](https://github.com/nearai/ironclaw/pull/8050) ci: stop cold-compiling every Reborn lane (stable hermetic Cargo home, push-only shared caches, stable toolchain, warm in-place mutation gate)
- [#8006](https://github.com/nearai/ironclaw/pull/8006) feat(channels): add durable progressive replies and native Slack Agent UI
- [#8042](https://github.com/nearai/ironclaw/pull/8042) fix(cli,ci): keep serve alive when stderr closes, bind before the banner, and judge only named mutants in the critical gate
- [#8021](https://github.com/nearai/ironclaw/pull/8021) fix(webui): replace native SettingsField controls with shared components
- [#8024](https://github.com/nearai/ironclaw/pull/8024) feat(webui): use shared SearchField for Workspace and Logs
- [#8023](https://github.com/nearai/ironclaw/pull/8023) refactor(webui): adopt shared components in Extension Configure
- [#8022](https://github.com/nearai/ironclaw/pull/8022) refactor(webui): migrate Automations notices to InlineNotice
- [#8031](https://github.com/nearai/ironclaw/pull/8031) refactor(agent-loop): decompose capability stage mechanics

### 🐛 New Issues
- [#8041](https://github.com/nearai/ironclaw/issues/8041) A tool failure whose kind is wrong sends the model somewhere it cannot recover
- [#8036](https://github.com/nearai/ironclaw/issues/8036) Type WebUI Test Infrastructure and Remove Remaining Test Suppressions
- [#8035](https://github.com/nearai/ironclaw/issues/8035) Remove `@ts-nocheck` from WebUI Production Components and Hooks
- [#8034](https://github.com/nearai/ironclaw/issues/8034) Add Shared API Types and Remove `@ts-nocheck` from Frontend Boundary Modules
- [#8033](https://github.com/nearai/ironclaw/issues/8033) Remove Redundant `@ts-nocheck` Directives and Prevent New Suppressions
- [#8032](https://github.com/nearai/ironclaw/issues/8032) Eliminate `@ts-nocheck` Debt from the WebUI v2 Frontend
- [#7921](https://github.com/nearai/ironclaw/issues/7921) perf(llm): OpenAI-family backends send no prompt_cache_key — measured ~82%→29% cache-hit collapse past ~200 calls `p2`

### 🔒 Closed Issues
- [#8018](https://github.com/nearai/ironclaw/issues/8018) Replace native SettingsField controls with shared Input and SelectMenu
- [#8020](https://github.com/nearai/ironclaw/issues/8020) Use the shared SearchField for Workspace and Logs filters
- [#8019](https://github.com/nearai/ironclaw/issues/8019) Migrate Automations status banners to InlineNotice
- [#8017](https://github.com/nearai/ironclaw/issues/8017) Adopt shared form and feedback components in Extension Configure

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,843 · **Open issues:** 84 · **Last push:** 5h ago

### 🚀 New Releases
- [20260902.03](https://github.com/moltis-org/moltis/releases/tag/20260902.03) — 20260902.03
- [20260902.02](https://github.com/moltis-org/moltis/releases/tag/20260902.02) — 20260902.02
- [20260902.01](https://github.com/moltis-org/moltis/releases/tag/20260902.01) — 20260902.01

### 🐛 New Issues
- [#1255](https://github.com/moltis-org/moltis/issues/1255) [Bug]: AgentEnd, MessageSending, and MessageSent hooks are declared but never dispatched
- [#1254](https://github.com/moltis-org/moltis/issues/1254) [Feature]: Include a stable tool call ID in hook payloads

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬2 · 1d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 3d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 5d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 9d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 21d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 24d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 27d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 29d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 31d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 33d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 2 new
- [[Learn] Agent Security Enterprise](https://openai.com/business/learn/agent-security-enterprise/) _2026-09-02_
- [[Index] Atv Big Air Tour](https://openai.com/index/atv-big-air-tour/) _2026-09-02_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [Muse Spark open weights coming soon](https://reddit.com/r/LocalLLaMA/comments/1w5l8bw/muse_spark_open_weights_coming_soon/) ↑531
- [GLM 5.3 Flash makes a black hole Minecraft mod running locally on 4x RTX PRO 6000 WS](https://reddit.com/r/LocalLLaMA/comments/1w5gk2b/glm_53_flash_makes_a_black_hole_minecraft_mod/) ↑160

### r/singularity — top 5 new
- [Gemini 3.8 Flash Benchmarks](https://reddit.com/r/singularity/comments/1w5d1pz/gemini_38_flash_benchmarks/) ↑732
- ["GPT-6-ASTRA" has been staged on the OpenAI API](https://reddit.com/r/singularity/comments/1w5f55h/gpt6astra_has_been_staged_on_the_openai_api/) ↑580
- [Sam Altman on X: "We are going to be launching our next model soon. There is an obvious tension… Astra is very good. We are proud of our work."](https://reddit.com/r/singularity/comments/1w52kvr/sam_altman_on_x_we_are_going_to_be_launching_our/) ↑550
- [Muse Spark 1.3 Released](https://reddit.com/r/singularity/comments/1w5knze/muse_spark_13_released/) ↑478
- [Who does a better job of explaining the future of generative AI: Ben Affleck or AI CEOs?](https://reddit.com/r/singularity/comments/1w5q76e/who_does_a_better_job_of_explaining_the_future_of/) ↑229

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw 2.0 (v2026.8.2) Open your main agent in a side panel, Update break fixes, and use the new Linux app](https://reddit.com/r/openclaw/comments/1w50zlr/openclaw_20_v202682_open_your_main_agent_in_a/) ↑50
- [found out what my coworker report actually says bc his agent repeated it to me](https://reddit.com/r/openclaw/comments/1w5euhm/found_out_what_my_coworker_report_actually_says/) ↑23
- [I am enjoying this update](https://reddit.com/r/openclaw/comments/1w5cor2/i_am_enjoying_this_update/) ↑11
- [New Memory System](https://reddit.com/r/openclaw/comments/1w50fmg/new_memory_system/) ↑9
- [Thread per project, file for the long stuff: how I organize my OpenClaw agent home](https://reddit.com/r/openclaw/comments/1w4d41p/thread_per_project_file_for_the_long_stuff_how_i/) ↑7

### X — @openclaw
- [What is it like to maintain OpenClaw? 
@github
 asked the people building it.](https://x.com/openclaw/status/2095323424143159411) ↑0 🔁0 · recent
- [A look behind OpenClaw with the people building and securing it. Thanks 
@github
 for having us.](https://x.com/openclaw/status/2095134656404308306) ↑0 🔁0 · recent
- [OpenClaw v2026.8.2 is out 🦞

🏠 Home rides shotgun
🐧 Linux joins the party
⚙️ Tasks work backstage
🎨 Fresh skins
🔧 Fewer ](https://x.com/openclaw/status/2095005122409742535) ↑0 🔁0 · recent
- [Tomorrow on The ClawCast: OpenClaw 2.0.

OpenClaw founder Peter Steinberger (
@steipete
) joins 
@hrudolph
 and 
@Pat_Er](https://x.com/openclaw/status/2094959144335974637) ↑0 🔁0 · recent
- [OpenClaw Nodes let your agent reach devices anywhere.](https://x.com/openclaw/status/2094911616441876729) ↑0 🔁0 · recent


### X — @steipete
- [Two months ago, we started the mission to “build OpenClaw with OpenClaw,” and bit by bit, we moved everyone from using t](https://x.com/steipete/status/2094290652649636173) ↑0 🔁0 · recent
- [This turned out so good! Thank you GitHub folks for making this happen! 🙏](https://x.com/steipete/status/2093013213038469205) ↑0 🔁0 · recent
- [codex' visualization feature got really good.](https://x.com/steipete/status/2092822007843061823) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
