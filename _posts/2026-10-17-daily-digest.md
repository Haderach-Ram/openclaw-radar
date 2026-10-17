---
layout: post
title: "Ecosystem Digest — 2026-10-17"
date: 2026-10-17 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-17
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 392,204 | 4 | 1 | 10 | 0 |
| **hermesagent** | 254,447 | 10 | 7 | 8 | 0 |
| **ZeroClaw** | 32,982 | 14 | 5 | 10 | 0 |
| **IronClaw** | 12,659 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,892 | 1 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 392,204 · **Open issues:** 9,457 · **Last push:** <1h ago

### ✅ Merged PRs
- [#174964](https://github.com/openclaw/openclaw/pull/174964) fix(agents): balance forced open-fence chunks
- [#174935](https://github.com/openclaw/openclaw/pull/174935) fix(crabbox): report executable and lease inspection failures
- [#174941](https://github.com/openclaw/openclaw/pull/174941) refactor(ui): read page snapshots through owner projections
- [#174939](https://github.com/openclaw/openclaw/pull/174939) perf(ui): defer plugin-management copy from chat boot
- [#174915](https://github.com/openclaw/openclaw/pull/174915) fix: reuse retained source objects for guest base refresh
- [#174389](https://github.com/openclaw/openclaw/pull/174389) fix(gateway): deleting an agent breaks other agents' live updates, health, and usage
- [#174616](https://github.com/openclaw/openclaw/pull/174616) fix(memory): avoid rescanning unchanged shared watcher roots
- [#174604](https://github.com/openclaw/openclaw/pull/174604) perf(runtime): remove redundant cron and resource checks
- [#174603](https://github.com/openclaw/openclaw/pull/174603) perf(skills): return mutation receipts from applied changes
- [#174602](https://github.com/openclaw/openclaw/pull/174602) perf(audit): reuse admitted and inserted audit facts

### 🐛 New Issues
- [#174975](https://github.com/openclaw/openclaw/issues/174975) [Bug]: Conversation readers cannot open saved inline widgets `bug` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#174968](https://github.com/openclaw/openclaw/issues/174968) [Feature]: WhatsApp: name approvers separately from allowFrom (execApprovals.approvers) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1
- [#174956](https://github.com/openclaw/openclaw/issues/174956) gateway-cron-placement live test deadlocks after session-bound cron writer waits (#165310) `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#174955](https://github.com/openclaw/openclaw/issues/174955) [Bug]: iOS Settings Dashboard shows the Gateway's raw error text and a false "update the Gateway" banner, with no Reload `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `P0` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-release-blocker` 💬1

### 🔒 Closed Issues
- [#1754](https://github.com/openclaw/openclaw/issues/1754) Proposal: Add `computer` Tool for Agentic UI Automation

### 🔥 Hot Issues (most commented)
- [#143524](https://github.com/openclaw/openclaw/issues/143524) [Bug]: Agent SQLite WAL grows to 1.4–2.8 GB in days despite wal_autocheckpoint=1000; blocks gateway startup (Windows, 2026.9.2/9.3) — 💬131 · 11h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 254,447 · **Open issues:** 49,663 · **Last push:** 1h ago

### ✅ Merged PRs
- [#140203](https://github.com/NousResearch/hermes-agent/pull/140203) v0.22.2 installs fast-forward to main (record v0.22.2 as an ancestor, #139099)
- [#139674](https://github.com/NousResearch/hermes-agent/pull/139674) fix(approval): no whole-script execute_code prompt in a local session's own turns
- [#139691](https://github.com/NousResearch/hermes-agent/pull/139691) fix(plugins): fire pre_command in the gateway for every local command
- [#139577](https://github.com/NousResearch/hermes-agent/pull/139577) fix(gateway): config and new MCP servers reach resumed sessions as committed policy generations
- [#139689](https://github.com/NousResearch/hermes-agent/pull/139689) fix(plugins): run a served profile's dashboard plugins in its own plugin host
- [#139569](https://github.com/NousResearch/hermes-agent/pull/139569) fix(plugins): one consent gate for plugin websockets, and Desktop plugin sockets on a local gateway
- [#139575](https://github.com/NousResearch/hermes-agent/pull/139575) fix(plugins): classic CLI plugin commands run in the gateway, and disable reaches the running gateway
- [#140176](https://github.com/NousResearch/hermes-agent/pull/140176) Low-disk auto-prune prompt never makes startup wait on the session database

### 🐛 New Issues
- [#140239](https://github.com/NousResearch/hermes-agent/issues/140239) [bug] GLM-5.3 rejects reasoning_effort=medium with 400/1210; GLM53_EFFORTS still lists medium and the main path falls back instead of clamping
- [#140238](https://github.com/NousResearch/hermes-agent/issues/140238) [Bug]: Multiplexed gateway: non-default profiles get zero tools — built-in platform toolset list degrades to zero because catalog plugins are discovered only in the launch home `type/bug` `comp/gateway` `tool/code-exec` `P1` `area/profiles`
- [#140231](https://github.com/NousResearch/hermes-agent/issues/140231) [Bug][Desktop]: When a subagent loads a skill, the parent agent gets a turn, breaking it's wait for the subagent to complete. `type/perf` `comp/agent` `tool/delegate` `tool/skills` `P2`
- [#140229](https://github.com/NousResearch/hermes-agent/issues/140229) Muse Spark 1.3 supports max, Hermes clamps it to xhigh `type/bug` `comp/agent` `P3`
- [#140226](https://github.com/NousResearch/hermes-agent/issues/140226) [Bug]: Compaction that lands just under the trigger counts as recovery, so near-zero-yield passes loop every 1-4 minutes `type/perf` `comp/agent` `P2` `area/compression`
- [#140224](https://github.com/NousResearch/hermes-agent/issues/140224) Desktop voice conversation stalls on Preparing audio: local native speak-stream connection rejected with HTTP 403 `type/bug` `comp/cli` `comp/gateway` `tool/tts` `area/auth` `P2` `comp/desktop`
- [#140222](https://github.com/NousResearch/hermes-agent/issues/140222) cron: agent jobs with a monitor create an empty session on every unchanged tick (gate runs after canonical admission) `type/bug` `comp/cron` `P2` `area/sessions` 💬1
- [#140221](https://github.com/NousResearch/hermes-agent/issues/140221) [Bug]: hermes config set agent.reasoning_effort warns 'not a recognized config key' and refuses without --force `type/bug` `comp/cli` `area/config` `P2`
- [#140217](https://github.com/NousResearch/hermes-agent/issues/140217) Desktop SSH (Windows): cold-opening a Bot takes ~25-30 s because each step is a fresh SSH connection; reuse the connection, batch the probes, cache platform/version `type/perf` `backend/ssh` `P2` `comp/desktop` `area/profiles` `os/windows` `desktop/connection`
- [#140216](https://github.com/NousResearch/hermes-agent/issues/140216) Desktop Bot Mode: support Ctrl/Cmd+click, middle-click and "Open in new tab" on Bot roster rows `type/feature` `comp/plugins` `P3` `comp/desktop`

### 🔒 Closed Issues
- [#123343](https://github.com/NousResearch/hermes-agent/issues/123343) Dependency pin httpx2==2.7.0 / httpcore2 2.7.0 hits six published CVEs (PYSEC-2026-3844..3849)
- [#134333](https://github.com/NousResearch/hermes-agent/issues/134333) chore(deps): workspace lockfile bump requested — build-tooling advisory chain (source-map-js/undici/brace-expansion/yaml/vitest)
- [#127791](https://github.com/NousResearch/hermes-agent/issues/127791) package.json pins ip-address 10.3.1 (2 SSRF CVEs, GHSA-rpw4-54j3-4h4q / GHSA-2vr4-cq9g-pvrc) and undici@^6 6.28.0 (WebSocket DoS, GHSA-3wwx-pv8p-q78v)
- [#140041](https://github.com/NousResearch/hermes-agent/issues/140041) [Bug]: Gateway crash-loops after reboot when a stale host-ownership record's PID is reused (incarnation start-time match too permissive)
- [#139523](https://github.com/NousResearch/hermes-agent/issues/139523) Gateway fixes (#134889), package 5: plugins, and config the gateway reads once
- [#59560](https://github.com/NousResearch/hermes-agent/issues/59560) [Bug]: custom_providers.models list is ignored — combo/9router models are not detected/selectable in Hermes Desktop
- [#139099](https://github.com/NousResearch/hermes-agent/issues/139099) Desktop updater: stable channel always offers v0.22.2 to git installs on main, then fails with exit 1 (refusal surfaced as 'Failed to update')

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,982 · **Open issues:** 978 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11791](https://github.com/zeroclaw-labs/zeroclaw/pull/11791) docs(runtime): record file_read pattern allowlist exception
- [#11725](https://github.com/zeroclaw-labs/zeroclaw/pull/11725) fix(runtime): deliver mid-turn steering at the next step, not after the final answer
- [#11506](https://github.com/zeroclaw-labs/zeroclaw/pull/11506) feat(zerocode): show saved and applied config status
- [#11460](https://github.com/zeroclaw-labs/zeroclaw/pull/11460) feat(zerocode): rename provider aliases in Config
- [#10567](https://github.com/zeroclaw-labs/zeroclaw/pull/10567) feat(memory): stamp recalled entries with their storage date
- [#11466](https://github.com/zeroclaw-labs/zeroclaw/pull/11466) feat(config): report per-target application results
- [#11732](https://github.com/zeroclaw-labs/zeroclaw/pull/11732) docs(runtime): propose recall, docs and status placement exceptions
- [#11465](https://github.com/zeroclaw-labs/zeroclaw/pull/11465) feat(tools): expose cooperative cancellation context
- [#11700](https://github.com/zeroclaw-labs/zeroclaw/pull/11700) fix(zerocode): keep composer and completion keys and clicks out of the transcript
- [#11288](https://github.com/zeroclaw-labs/zeroclaw/pull/11288) fix(zerocode): make scrollbar seeking continuous across loaded history

### 🐛 New Issues
- [#11799](https://github.com/zeroclaw-labs/zeroclaw/issues/11799) [Feature]: Shell policy refusals should say why, and accept an operator hint
- [#11796](https://github.com/zeroclaw-labs/zeroclaw/issues/11796) [Bug]: ZeroClaw daemon suddenly prompts for GitHub credentials on startup and blocks `bug` 💬1
- [#11794](https://github.com/zeroclaw-labs/zeroclaw/issues/11794) [Feature]: per-user runtime-directory fallback for the config lifecycle lock on filesystems without Unix permissions (WSL `/mnt/c`, CIFS, FAT)
- [#11793](https://github.com/zeroclaw-labs/zeroclaw/issues/11793) [Feature]: create the data directory owner-only and check group- or world-writable data roots
- [#11792](https://github.com/zeroclaw-labs/zeroclaw/issues/11792) [Bug]: an interrupted `plugin install` can leave an abandoned `.<name>.installing-v1-<id>` stage that no command ever removes
- [#11788](https://github.com/zeroclaw-labs/zeroclaw/issues/11788) [Task]: Distinguish configured-but-unselected tools from unavailable tools
- [#11787](https://github.com/zeroclaw-labs/zeroclaw/issues/11787) [Task]: Warn about unknown tools.optional entries without changing selection
- [#11786](https://github.com/zeroclaw-labs/zeroclaw/issues/11786) [Task]: Tie the built-in Core inventory to CORE_TOOL_NAMES
- [#11783](https://github.com/zeroclaw-labs/zeroclaw/issues/11783) [Bug]: Can't create Alpine container image `bug` 💬1
- [#11777](https://github.com/zeroclaw-labs/zeroclaw/issues/11777) [Bug]: Loop detector default threshould is too low `bug` 💬1
- [#11773](https://github.com/zeroclaw-labs/zeroclaw/issues/11773) [Bug]: Regional OS locales (fr_FR, es_ES, ja_JP) fall back to English 💬1
- [#11771](https://github.com/zeroclaw-labs/zeroclaw/issues/11771) Bootstrap file cap differs between gateway turns (20,000) and channel/agent-loop turns (6,000 with compact_context); doctor reports one 💬1
- [#11769](https://github.com/zeroclaw-labs/zeroclaw/issues/11769) [Bug]: Voice-drop and model-fallback channel tests depend on the operator locale 💬1
- [#11764](https://github.com/zeroclaw-labs/zeroclaw/issues/11764) [Bug]: WhatsApp Web drops an untranscribed voice note without telling the sender 💬1

### 🔒 Closed Issues
- [#11491](https://github.com/zeroclaw-labs/zeroclaw/issues/11491) [Feature]: Show saved versus applied config status in ZeroCode Config
- [#5836](https://github.com/zeroclaw-labs/zeroclaw/issues/5836) [Feature]: add cooperative cancellation to the Tool execution contract
- [#11488](https://github.com/zeroclaw-labs/zeroclaw/issues/11488) [Bug]: ZeroCode Config filtering affects both panes and loses the section on cancel
- [#10577](https://github.com/zeroclaw-labs/zeroclaw/issues/10577) [Feature]: Implement opt-in single-tool provider rounds
- [#11606](https://github.com/zeroclaw-labs/zeroclaw/issues/11606) model_routing_config upsert_agent rewrites entire config: fabricates risk/runtime profiles, drops fields, resets agent limits

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,659 · **Open issues:** 1,551 · **Last push:** 3d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,892 · **Open issues:** 114 · **Last push:** 24d ago

### 🐛 New Issues
- [#1305](https://github.com/moltis-org/moltis/issues/1305) [Bug]: web_fetch omits User-Agent, causing HTTP 403 from GitHub REST API

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 2d ago
- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬1 · 8d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 11d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 19d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 21d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 31d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 39d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 41d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 49d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 53d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 5 new
- [[Research] Ai Expectations Gap](https://www.anthropic.com/research/ai-expectations-gap) _2026-10-16_
- [[Research] Designing Efficient Quantum Circuits](https://www.anthropic.com/research/designing-efficient-quantum-circuits) _2026-10-16_
- [[Research] Ecdsa Curve Origins](https://www.anthropic.com/research/ecdsa-curve-origins) _2026-10-16_
- [[Research] Employment At Anthropic](https://www.anthropic.com/research/employment-at-anthropic) _2026-10-16_
- [[Research] Expectations For The Future](https://www.anthropic.com/research/expectations-for-the-future) _2026-10-16_

### OpenAI — 3 new
- [[Index] Localiza Generative Ai](https://openai.com/index/localiza-generative-ai/) _2026-10-17_
- [[Index] Grupo Boticario](https://openai.com/index/grupo-boticario/) _2026-10-17_
- [[Index] Itau Generative Ai](https://openai.com/index/itau-generative-ai/) _2026-10-16_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/singularity — top 5 new
- [An internal Anthropic research model's chain of thought after cracking the 26-year-old NSA elliptic curve seed mystery in under 30 minutes](https://reddit.com/r/singularity/comments/1x7vivf/an_internal_anthropic_research_models_chain_of/) ↑388
- [Agentic workflows coming for Minecraft building?](https://reddit.com/r/singularity/comments/1x76yfu/agentic_workflows_coming_for_minecraft_building/) ↑346
- [The last line of the Navier-Stokes chain of thought](https://reddit.com/r/singularity/comments/1x7nv4y/the_last_line_of_the_navierstokes_chain_of_thought/) ↑313
- [Claude Mythos 5 designed quantum circuits that improve on the best published ones, sometimes by an order of magnitude or more](https://reddit.com/r/singularity/comments/1x7s98a/claude_mythos_5_designed_quantum_circuits_that/) ↑221
- [Researchers Stranded an AI Agent on a Virtual Island. Things Got Very Weird.](https://reddit.com/r/singularity/comments/1x7polo/researchers_stranded_an_ai_agent_on_a_virtual/) ↑164

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Set up OpenClaw out of the box on the new NVIDIA RTX Spark laptops](https://reddit.com/r/openclaw/comments/1x7r4qg/set_up_openclaw_out_of_the_box_on_the_new_nvidia/) ↑15
- [OpenClaw v2026.10.4 patch release is out with update recovery, chat refresh, messaging and sign-in fixes](https://reddit.com/r/openclaw/comments/1x75nn8/openclaw_v2026104_patch_release_is_out_with/) ↑13
- [Excessive token usage inside OpenClaw with Codex](https://reddit.com/r/openclaw/comments/1x7ddgn/excessive_token_usage_inside_openclaw_with_codex/) ↑2
- [Update models from providers](https://reddit.com/r/openclaw/comments/1x77mce/update_models_from_providers/) ↑2

### X — @openclaw
- [Set up OpenClaw out of the box on the new 
@nvidia
 RTX Spark laptops.

Choose a local model or connect a cloud provider](https://x.com/openclaw/status/2111190844225306694) ↑0 🔁0 · recent
- [Donna burns a trillion tokens a month

She runs loops you haven't even conceived of](https://x.com/openclaw/status/2111137678406381614) ↑0 🔁0 · recent
- [OpenClaw v2026.10.4 patch release is out 🦞

🔄 Update + recovery fixes
💬 Chats unstuck after updates
📨 Messaging + sign-i](https://x.com/openclaw/status/2110934479569379617) ↑0 🔁0 · recent


### X — @steipete
_No new tweets since the last digest. Most recent:_
- [crabbox is underrated](https://x.com/steipete/status/2110795475075084471)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
