---
layout: post
title: "Ecosystem Digest — 2026-10-23"
date: 2026-10-23 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-23
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 392,794 | 3 | 4 | 10 | 1 |
| **hermesagent** | 256,266 | 13 | 1 | 10 | 0 |
| **ZeroClaw** | 33,028 | 14 | 9 | 10 | 0 |
| **IronClaw** | 12,669 | 1 | 1 | 0 | 0 |
| **Moltis** | 2,906 | 0 | 0 | 2 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 392,794 · **Open issues:** 8,974 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.10.6](https://github.com/openclaw/openclaw/releases/tag/v2026.10.6) — openclaw 2026.10.6

### ✅ Merged PRs
- [#181151](https://github.com/openclaw/openclaw/pull/181151) perf(agents): reuse prompt size records and fork options
- [#181180](https://github.com/openclaw/openclaw/pull/181180) fix(gateway): show interruptions for unrecoverable requesters
- [#181188](https://github.com/openclaw/openclaw/pull/181188) refactor: keep private presentation and profile APIs at their owners
- [#177836](https://github.com/openclaw/openclaw/pull/177836) fix(config): accept web search provider ids that differ only in case
- [#181167](https://github.com/openclaw/openclaw/pull/181167) fix(ui): stabilize the cold multi-select selection test
- [#181183](https://github.com/openclaw/openclaw/pull/181183) fix(ui): center microphone-picker keyboard focus
- [#181130](https://github.com/openclaw/openclaw/pull/181130) fix(doctor): complete legacy heartbeat migration without blocking startup
- [#181122](https://github.com/openclaw/openclaw/pull/181122) refactor: remove unused private runtime inputs
- [#181168](https://github.com/openclaw/openclaw/pull/181168) fix: correct macOS thread and gateway window shortcuts
- [#181003](https://github.com/openclaw/openclaw/pull/181003) refactor(ui): remove unused provider read receipts

### 🐛 New Issues
- [#181197](https://github.com/openclaw/openclaw/issues/181197) [SANITIZED — possible injection attempt] `clawsweeper:intake:bug` 💬1
- [#181175](https://github.com/openclaw/openclaw/issues/181175) [Bug]: A2A outbound "peer has no url" failure is thrown as an untyped Error, so it is never classified as permanent (2026.10.6: 4 agent turns for one completion, then dead-letter) `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#181165](https://github.com/openclaw/openclaw/issues/181165) [Bug]: tools.github.configure swallows the real failure cause and always reports "GitHub identity setup failed" `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#176994](https://github.com/openclaw/openclaw/issues/176994) QA: subagent handoff times out without identifying which transition was missing
- [#181013](https://github.com/openclaw/openclaw/issues/181013) [Bug]: doctor heartbeat→Automations migration blocks on legacy heartbeat-main cron scratch; config stays invalid, gateway exits 78/CONFIG
- [#181110](https://github.com/openclaw/openclaw/issues/181110) [Bug]: doctor --fix deadlocks on legacy agents.defaults.heartbeat: plugin-migration settle rejects the invalid config before heartbeat retirement runs
- [#144223](https://github.com/openclaw/openclaw/issues/144223) 2026.9.3 cloud workers: every turn on a freshly attached worker rejected with embedded-tool-authority mismatch; remote workspace never materializes

### 🔥 Hot Issues (most commented)
- [#143524](https://github.com/openclaw/openclaw/issues/143524) [Bug]: Agent SQLite WAL grows to 1.4–2.8 GB in days despite wal_autocheckpoint=1000; blocks gateway startup (Windows, 2026.9.2/9.3) — 💬134 · 19h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 256,266 · **Open issues:** 50,575 · **Last push:** <1h ago

### ✅ Merged PRs
- [#143318](https://github.com/NousResearch/hermes-agent/pull/143318) Windows x64 MSIX smoke launches the app again, and says why when a launch dies
- [#143329](https://github.com/NousResearch/hermes-agent/pull/143329) PM survival test stops failing on a rebuilt fixture wheel's hash
- [#143325](https://github.com/NousResearch/hermes-agent/pull/143325) nix flake check evaluates again after the uv revision-5 relock
- [#143292](https://github.com/NousResearch/hermes-agent/pull/143292) Windows desktop builds compile cold-cache sdists again (short uv path, no MAX_PATH LNK1104)
- [#143248](https://github.com/NousResearch/hermes-agent/pull/143248) feat(connectors): no guest on page open, connector sign-in offer
- [#143236](https://github.com/NousResearch/hermes-agent/pull/143236) feat(desktop): sign-in result shows who signed in and what moved
- [#143235](https://github.com/NousResearch/hermes-agent/pull/143235) feat(auth): every Nous sign-in is the plain device login
- [#143234](https://github.com/NousResearch/hermes-agent/pull/143234) feat(auth): hand the free-tier guest to the account after sign-in
- [#143281](https://github.com/NousResearch/hermes-agent/pull/143281) fix: uv resolution works again on newest uv
- [#143291](https://github.com/NousResearch/hermes-agent/pull/143291) Windows update from v0.22.4 publishes the new launcher and stamp across the Python repin

### 🐛 New Issues
- [#143347](https://github.com/NousResearch/hermes-agent/issues/143347) Vision probes can't resolve `catalog_provider` for named custom providers (routed as `custom`)
- [#143346](https://github.com/NousResearch/hermes-agent/issues/143346) kanban dispatcher: report cap-hold reason in the stuck warning `type/feature` `comp/cron` `comp/plugins` `P3`
- [#143338](https://github.com/NousResearch/hermes-agent/issues/143338) clarify: add an optional per-choice preview (and description) field `type/feature` `comp/tools` `platform/discord` `P3`
- [#143335](https://github.com/NousResearch/hermes-agent/issues/143335) [Setup]: `type/bug` `comp/cli` `P2` `area/install-update` `os/windows` 💬1
- [#143333](https://github.com/NousResearch/hermes-agent/issues/143333) [Bug]: `hermes profile rename` strands every local (Desktop/Webapp/CLI) chat of the profile: `profile_mismatch` on resume, and `migrate-identity` does not repair it `type/bug` `comp/gateway` `P2` `area/sessions` `area/profiles` 💬1
- [#143331](https://github.com/NousResearch/hermes-agent/issues/143331) hermes update fails every run on Windows: stale gateway.pid beside a held lock aborts gateway pause (plus stable-channel downgrade refusal exits 1) `type/bug` `comp/gateway` `P2` `area/install-update` `area/profiles` `os/windows` 💬2
- [#143330](https://github.com/NousResearch/hermes-agent/issues/143330) [Feature]: Resolve provider API keys from the user login shell environment (Desktop and WSL backends miss .bashrc keys) `type/feature` `comp/agent` `comp/cli` `provider/xai` `area/auth` `area/config` `P2` `area/profiles` `os/windows` 💬1
- [#143326](https://github.com/NousResearch/hermes-agent/issues/143326) [Bug]: issues following recent update / Model selection delay `type/bug` `comp/gateway` `area/config` `P2` `comp/desktop` `desktop/chat` `os/windows` `comp/tui-gateway` `desktop/connection` 💬4
- [#143324](https://github.com/NousResearch/hermes-agent/issues/143324) [Bug]: Canonical group chats lost avatars and thinking indicators `type/bug` `P2` `comp/desktop` `desktop/chat`
- [#143323](https://github.com/NousResearch/hermes-agent/issues/143323) [Bug]: Desktop model picker commits the picked model with the session's current provider — cross-provider route mismatch (variant of #79536) `type/bug` `area/config` `P2` `comp/desktop` `area/sessions` `desktop/settings` `desktop/chat` 💬1
- [#143320](https://github.com/NousResearch/hermes-agent/issues/143320) [Bug]: Desktop turn-end chime fires for another session while the chat on screen is still working `type/bug` `P2` `comp/desktop` `area/streaming` 💬2
- [#143316](https://github.com/NousResearch/hermes-agent/issues/143316) [Bug]: Compression threshold assumes a 524,288-token window and only reports the mismatch after silently auto-lowering `type/bug` `comp/agent` `area/config` `P2` `area/compression` 💬2
- [#143315](https://github.com/NousResearch/hermes-agent/issues/143315) [Bug]: auxiliary.compression.provider "auto" inherits the chat model's provider and 404s on models it cannot serve `type/bug` `comp/agent` `area/config` `P2` `area/compression` `provider/other` 💬2

### 🔒 Closed Issues
- [#143327](https://github.com/NousResearch/hermes-agent/issues/143327) preflight_db_writability reports "read-only" for a -wal/-shm sidecar that SQLite deleted mid-check (TOCTOU race)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,028 · **Open issues:** 1,035 · **Last push:** 2h ago

### ✅ Merged PRs
- [#11863](https://github.com/zeroclaw-labs/zeroclaw/pull/11863) test(runtime): make the receipt-bound late_tool_search tests opt-in
- [#11848](https://github.com/zeroclaw-labs/zeroclaw/pull/11848) fix(plugins): name the sender in plugin_channel_sender_denied records
- [#11841](https://github.com/zeroclaw-labs/zeroclaw/pull/11841) docs(changelog): match the v0.8.6 In brief wording on OIDC
- [#11941](https://github.com/zeroclaw-labs/zeroclaw/pull/11941) ci(plugins): raise the cranelift runtime leg timeout to 30 minutes
- [#11833](https://github.com/zeroclaw-labs/zeroclaw/pull/11833) ci(docker): bound arm64 build memory and add a dry-run dispatch to docker-publish
- [#11967](https://github.com/zeroclaw-labs/zeroclaw/pull/11967) fix(ci): run the crates.io preflight only for a pull request's own version bump
- [#11854](https://github.com/zeroclaw-labs/zeroclaw/pull/11854) ci(release): raise the macOS universal desktop job timeout to 240 minutes
- [#11903](https://github.com/zeroclaw-labs/zeroclaw/pull/11903) fix(security): share one JWKS fetch among concurrent token checks
- [#11809](https://github.com/zeroclaw-labs/zeroclaw/pull/11809) fix(plugins): remove a loaded plugin from the directory it was loaded from
- [#11927](https://github.com/zeroclaw-labs/zeroclaw/pull/11927) ci(security): audit the full lockfile in the daily scan

### 🐛 New Issues
- [#11995](https://github.com/zeroclaw-labs/zeroclaw/issues/11995) [Feature]: Restore owned background delegation with principal-scoped results `enhancement` `follow-up`
- [#11992](https://github.com/zeroclaw-labs/zeroclaw/issues/11992) [Feature]: Email channel: operator templates and a sanitised HTML body for send_via
- [#11991](https://github.com/zeroclaw-labs/zeroclaw/issues/11991) [Bug]: outbound email HTML carries raw markup and arbitrary image URLs from the agent's text
- [#11989](https://github.com/zeroclaw-labs/zeroclaw/issues/11989) [Bug]: per-channel excluded_tools is never applied
- [#11987](https://github.com/zeroclaw-labs/zeroclaw/issues/11987) [Bug]: Inline nosemgrep comments don't stop Semgrep code scanning alerts `bug`
- [#11985](https://github.com/zeroclaw-labs/zeroclaw/issues/11985) [Task]: Gateway tests for scoped dashboard chat under JWKS validation, a failed write and a retirement race `gateway` `tests` `follow-up` `type:test`
- [#11984](https://github.com/zeroclaw-labs/zeroclaw/issues/11984) [Feature]: Dashboard chat for signed-in accounts without administrator rights `enhancement` `gateway` `web` `release:v0.9.0`
- [#11982](https://github.com/zeroclaw-labs/zeroclaw/issues/11982) [Task]: build the runtime-composition consumer fixture on its own in CI
- [#11981](https://github.com/zeroclaw-labs/zeroclaw/issues/11981) [Task]: key the non-interactive shell approval exemption on the native shell tool
- [#11978](https://github.com/zeroclaw-labs/zeroclaw/issues/11978) [Bug]: enrollment loopback listener tests time out intermittently under load (paused clock over real sockets) `bug`
- [#11972](https://github.com/zeroclaw-labs/zeroclaw/issues/11972) [Bug]: zeroclaw gateway get-paircode exits 0 when it cannot fetch a code `bug` `gateway`
- [#11971](https://github.com/zeroclaw-labs/zeroclaw/issues/11971) [Feature]: Build ZeroClaw without the gateway or dashboard (CLI-only source build) `enhancement` `cli` `release:v0.9.0`
- [#11970](https://github.com/zeroclaw-labs/zeroclaw/issues/11970) [Bug]: agents delete/rename skip the owned-state cascade and the live-ACP check in builds without the gateway `bug` `cli` `release:v0.9.0`
- [#11969](https://github.com/zeroclaw-labs/zeroclaw/issues/11969) [Bug]: the metrics and embedded-web features compile the whole gateway into headless builds `bug` `gateway` `release:v0.9.0`

### 🔒 Closed Issues
- [#11806](https://github.com/zeroclaw-labs/zeroclaw/issues/11806) [Task]: make the receipt-bound late_tool_search tests opt-in outside the runtime plugin job
- [#11821](https://github.com/zeroclaw-labs/zeroclaw/issues/11821) [Bug]: plugin_channel_sender_denied records do not name the sender, so the operator cannot tell whom to admit
- [#11828](https://github.com/zeroclaw-labs/zeroclaw/issues/11828) [Task]: the arm64 `dist` image runs out of memory in docker-publish.yml, so v0.8.6 can ship without its `dist` image
- [#10558](https://github.com/zeroclaw-labs/zeroclaw/issues/10558) [Bug]: Cranelift CI hits 20-minute job timeout despite passing final tests
- [#11966](https://github.com/zeroclaw-labs/zeroclaw/issues/11966) [Bug]: crates.io Package Preflight runs on pull requests that only inherit master's version bump, and fails once the tag exists
- [#10526](https://github.com/zeroclaw-labs/zeroclaw/issues/10526) RFC: Append-only session event history, deterministic state replay, and derived agent streams
- [#11902](https://github.com/zeroclaw-labs/zeroclaw/issues/11902) [Bug]: a valid OIDC token is refused as misconfigured when it is checked during another check's JWKS fetch
- [#11357](https://github.com/zeroclaw-labs/zeroclaw/issues/11357) [Bug]: `plugin remove` of a loaded plugin deletes `plugins_dir/<name>`, not the directory it was loaded from
- [#11926](https://github.com/zeroclaw-labs/zeroclaw/issues/11926) [Feature]: audit the full lockfile in the daily advisory scan

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,669 · **Open issues:** 1,562 · **Last push:** 13h ago

### 🐛 New Issues
- [#8153](https://github.com/nearai/ironclaw/issues/8153) Daily ironclaw failure taxonomy — 2026-10-22

### 🔒 Closed Issues
- [#3168](https://github.com/nearai/ironclaw/issues/3168) Add arm64/aarch64 platform support for Docker builds

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,906 · **Open issues:** 121 · **Last push:** <1h ago

### ✅ Merged PRs
- [#1314](https://github.com/moltis-org/moltis/pull/1314) fix(providers): refresh retired MiniMax models and verify live tool use
- [#1313](https://github.com/moltis-org/moltis/pull/1313) fix(tls): update certificate verifier and roots for CA distrust

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬1 · 18h ago
- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 8d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 17d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 25d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 27d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 37d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 45d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 47d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 55d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 59d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 5 new
- [Guest Investigator Program](https://www.anthropic.com/guest-investigator-program) _2026-10-22_
- [[Legal] Guest Investigator Program Terms](https://www.anthropic.com/legal/guest-investigator-program-terms) _2026-10-22_
- [[News] Donating Agent Skills To The Agentic Ai Foundation](https://www.anthropic.com/news/donating-agent-skills-to-the-agentic-ai-foundation) _2026-10-22_
- [[News] Open Call Guest Investigators Life Sciences](https://www.anthropic.com/news/open-call-guest-investigators-life-sciences) _2026-10-22_
- [[Research] Formal Verification](https://www.anthropic.com/research/formal-verification) _2026-10-22_

### OpenAI — 3 new
- [[Business] Forward Deployed Engineering](https://openai.com/business/forward-deployed-engineering/) _2026-10-23_
- [[Index] Forward Deployed Engineering Means](https://openai.com/index/forward-deployed-engineering-means/) _2026-10-23_
- [[Index] Uber Chatgpt Work Rollout](https://openai.com/index/uber-chatgpt-work-rollout/) _2026-10-23_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Qwen4 and Kimi3.1 on Arena apperantly](https://reddit.com/r/LocalLLaMA/comments/1xcj1wm/qwen4_and_kimi31_on_arena_apperantly/) ↑643
- [Repair shop receives eight GeForce RTX 5090 and RTX 4090 cards with melted 16-pin connectors in two days](https://reddit.com/r/LocalLLaMA/comments/1xckdep/repair_shop_receives_eight_geforce_rtx_5090_and/) ↑202
- [DeepSeek and MiniMax Clear China’s AI Export Rules for Overseas Open-Source Releases](https://reddit.com/r/LocalLLaMA/comments/1xcoelw/deepseek_and_minimax_clear_chinas_ai_export_rules/) ↑180
- [Ant Ling just announced a second model today: Ling-3.0-flash-Sante (124B, 5.1B active)](https://reddit.com/r/LocalLLaMA/comments/1xcljvi/ant_ling_just_announced_a_second_model_today/) ↑140
- [Meta's 816B Muse Spark Open scores 39 on Artificial Analysis, the 180B Qwen3.8-Flash-Next scores 40. Score vs size for 11 open-weight models](https://reddit.com/r/LocalLLaMA/comments/1xcthj8/metas_816b_muse_spark_open_scores_39_on/) ↑120

### r/singularity — top 5 new
- [Every AI model has the same “controversial” take on humans](https://reddit.com/r/singularity/comments/1xckfuy/every_ai_model_has_the_same_controversial_take_on/) ↑414
- [Tesla Optimus production starts, targets 20,000 robots weekly](https://reddit.com/r/singularity/comments/1xcjgeh/tesla_optimus_production_starts_targets_20000/) ↑390
- [The AI cyber arms race is escalating fast. PHP2Shell triggers millions of exploit attempts. China-linked hackers use AI agents to target 2,250+ cloud tenants, gaining privileged access in under 3 hour](https://reddit.com/r/singularity/comments/1xcc2cx/the_ai_cyber_arms_race_is_escalating_fast/) ↑362
- [Safety Research = Capabilities Research](https://reddit.com/r/singularity/comments/1xcv9zi/safety_research_capabilities_research/) ↑306
- [Introducing NPCTalk: Make the NPCs of any game talk in realtime, in character, in their own cloned voice, in under 1s, and they act on what you say.](https://reddit.com/r/singularity/comments/1xczh14/introducing_npctalk_make_the_npcs_of_any_game/) ↑236

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [DeepSeek V4.1 Flash is now available in OpenClaw](https://reddit.com/r/openclaw/comments/1xd024j/deepseek_v41_flash_is_now_available_in_openclaw/) ↑10
- [OpenClaw v2026.10.6 patch release is out with urgent install, update, and startup fixes](https://reddit.com/r/openclaw/comments/1xcunwz/openclaw_v2026106_patch_release_is_out_with/) ↑9

### X — @openclaw
- [Tomorrow, 
@hrudolph
 joins 
@crazy4pi314
 for 
@github
's Open Source Friday, with a live OpenClaw demo and community Q](https://x.com/openclaw/status/2113416584907948506) ↑0 🔁0 · recent
- [DeepSeek V4.1 Flash from 
@deepseek_ai
 is now available in OpenClaw.

Already using it with your agents? Let us know ho](https://x.com/openclaw/status/2113414141327380480) ↑0 🔁0 · recent
- [OpenClaw v2026.10.6 patch release is out 🦞

🔧 Install, update + startup fixes
🪟 Windows setup fixes
💬 Discord command re](https://x.com/openclaw/status/2113385659918639399) ↑0 🔁0 · recent
- [The only industry that moved faster than AI this week was cyber security](https://x.com/openclaw/status/2113330445714878939) ↑0 🔁0 · recent
- [COME SPEND OUR TOKENS

OpenClaw focus weeks are an invitation to join our team server and build along side us

You're us](https://x.com/openclaw/status/2113322783551959406) ↑0 🔁0 · recent


### X — @steipete
_No new tweets since the last digest. Most recent:_
- [That PHP vulnerability that’s gonna cause havoc this week was found with… GPT‑5.6 Sol.](https://x.com/steipete/status/2112913060709228764)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
