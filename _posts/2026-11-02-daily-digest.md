---
layout: post
title: "Ecosystem Digest — 2026-11-02"
date: 2026-11-02 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-02
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 393,645 | 5 | 4 | 10 | 0 |
| **hermesagent** | 259,529 | 8 | 6 | 4 | 0 |
| **ZeroClaw** | 33,094 | 7 | 1 | 3 | 0 |
| **IronClaw** | 12,702 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,940 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 393,645 · **Open issues:** 7,732 · **Last push:** <1h ago

### ✅ Merged PRs
- [#190004](https://github.com/openclaw/openclaw/pull/190004) chore(tokenjuice): update runtime to 0.10.0
- [#190777](https://github.com/openclaw/openclaw/pull/190777) fix: align clean-install agent exec live expectations
- [#120232](https://github.com/openclaw/openclaw/pull/120232) fix(ci): route Knip cleanup owners to Windows
- [#190781](https://github.com/openclaw/openclaw/pull/190781) fix: restore prepared registry reuse for plugin subagent completions
- [#190775](https://github.com/openclaw/openclaw/pull/190775) fix(ui): distinguish hydrated composer readiness in warm probe
- [#190760](https://github.com/openclaw/openclaw/pull/190760) test(matrix): exercise the canonical approval error classifier
- [#187771](https://github.com/openclaw/openclaw/pull/187771) refactor: consolidate Codex fixture text-turn completion
- [#167259](https://github.com/openclaw/openclaw/pull/167259) fix(gateway): standing-grant cards can split emoji at display caps
- [#190762](https://github.com/openclaw/openclaw/pull/190762) fix(ci): terminate Android cleanup when emulator is unavailable
- [#190707](https://github.com/openclaw/openclaw/pull/190707) refactor(models): define compatibility at the schema owner

### 🐛 New Issues
- [#190797](https://github.com/openclaw/openclaw/issues/190797) Web-search Docker regression crashes after the mock completes a response `P2` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#190784](https://github.com/openclaw/openclaw/issues/190784) Shutdown lifecycle test freezes the wrong grace-budget clock `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#190779](https://github.com/openclaw/openclaw/issues/190779) Docs: broken relative links found (fix available) `P3` 💬1
- [#190773](https://github.com/openclaw/openclaw/issues/190773) [Bug]: Native iOS recurrent AUTH_RATE_LIMITED lockouts; separate captured missed-tick reconnect cancellation `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `impact:auth-provider` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#190772](https://github.com/openclaw/openclaw/issues/190772) [Bug]: Managed Tailscale Serve recovery misses "must be root" denial and skips sudo fallback `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `maturity:stable` 💬1

### 🔒 Closed Issues
- [#190748](https://github.com/openclaw/openclaw/issues/190748) Discord: delete/edit cannot target the current DM when tools.message.crossContext is locked
- [#189997](https://github.com/openclaw/openclaw/issues/189997) Update tokenjuice plugin runtime to 0.10.0
- [#190776](https://github.com/openclaw/openclaw/issues/190776) Clean-install agent exec live test rejects automatic Code Mode
- [#190759](https://github.com/openclaw/openclaw/issues/190759) Android native qualification hangs in cleanup when the emulator never connects

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬69 · 6h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 259,529 · **Open issues:** 52,255 · **Last push:** <1h ago

### ✅ Merged PRs
- [#147678](https://github.com/NousResearch/hermes-agent/pull/147678) fix(gateway): background jobs that finish during a busy turn come back as one turn, not one each
- [#147681](https://github.com/NousResearch/hermes-agent/pull/147681) fix(desktop): every gateway stays connected, and picking one no longer asks to switch or blanks the session list
- [#147664](https://github.com/NousResearch/hermes-agent/pull/147664) feat(telemetry): see when people wait on a busy agent (busy arrivals + daily peak of busy chats)
- [#147672](https://github.com/NousResearch/hermes-agent/pull/147672) fix(telemetry): Spotify and old browser_vault tool names from older releases export as recorded again

### 🐛 New Issues
- [#147771](https://github.com/NousResearch/hermes-agent/issues/147771) [SANITIZED — possible injection attempt]
- [#147766](https://github.com/NousResearch/hermes-agent/issues/147766) [Bug]: checkpoints stop for good when a nested repo's .git breaks after it was recorded as a gitlink
- [#147765](https://github.com/NousResearch/hermes-agent/issues/147765) [Feature]: Windows install should offer (never auto-apply) a Defender exclusion for the Hermes folder
- [#147759](https://github.com/NousResearch/hermes-agent/issues/147759) kanban: add a claim-time veto for per-model concurrency (every lifecycle hook is post-hoc, so plugins cannot refuse a claim)
- [#147758](https://github.com/NousResearch/hermes-agent/issues/147758) doctor: "Stale channel record" is a false positive — staleness check requires install.json, which only a desktop e2e fixture writes 💬1
- [#147756](https://github.com/NousResearch/hermes-agent/issues/147756) [Bug]: Desktop Bot relay strands settled replies without a new outbox push; restart does not recover claims
- [#147747](https://github.com/NousResearch/hermes-agent/issues/147747) [Bug]: Cron agent sessions never receive the firing profile's .env — mnemosyne_* tools silently operate on the default profile's memory bank
- [#147744](https://github.com/NousResearch/hermes-agent/issues/147744) [Setup]: python error

### 🔒 Closed Issues
- [#139135](https://github.com/NousResearch/hermes-agent/issues/139135) [Bug]: Discord async child completes but durable result stays pending and parent does not resume
- [#143447](https://github.com/NousResearch/hermes-agent/issues/143447) [Bug]: Automation wakes refused admission_conflict forever when the lane's profile route postdates the session origin
- [#141893](https://github.com/NousResearch/hermes-agent/issues/141893) Async delegation watcher retries stranded pending deliveries every 2s forever (no backoff, no attempt accounting)
- [#144006](https://github.com/NousResearch/hermes-agent/issues/144006) [Bug]: Discord thread delegate_task completions refused admission_conflict forever: the session-key fallback source never carries parent_chat_id
- [#146136](https://github.com/NousResearch/hermes-agent/issues/146136) [Bug]: Plain Telegram group (no topics, group_sessions_per_user: false): delegate_task completions refused admission_conflict, delivered only on the next inbound turn
- [#145611](https://github.com/NousResearch/hermes-agent/issues/145611) [Bug]: Telegram forum-topic delegate_task completions refused admission_conflict forever; parent never notified

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,094 · **Open issues:** 1,137 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11686](https://github.com/zeroclaw-labs/zeroclaw/pull/11686) docs(plugins): correct the call_channel! note on results that fail to lift
- [#12159](https://github.com/zeroclaw-labs/zeroclaw/pull/12159) fix(install): show package version from zeroclaw --version field 2
- [#11940](https://github.com/zeroclaw-labs/zeroclaw/pull/11940) fix(enroll): redeem enrollment codes on the daemon's canonical pairing guard

### 🐛 New Issues
- [#12181](https://github.com/zeroclaw-labs/zeroclaw/issues/12181) [Feature]: Web managed document upload (first #9488 Phase 2 Web slice)
- [#12178](https://github.com/zeroclaw-labs/zeroclaw/issues/12178) [Bug]: deliver_file description tells the model to write the attachment uri into the reply text
- [#12176](https://github.com/zeroclaw-labs/zeroclaw/issues/12176) [SANITIZED — possible injection attempt]
- [#12175](https://github.com/zeroclaw-labs/zeroclaw/issues/12175) [Bug]: The personality editor's "changes take effect on the next message — no daemon reload needed" copy is wrong for channels
- [#12173](https://github.com/zeroclaw-labs/zeroclaw/issues/12173) [Bug]: Lark card chunking panics when a byte budget lands inside a multi-byte character
- [#12131](https://github.com/zeroclaw-labs/zeroclaw/issues/12131) RFC: Shared execution permissions and same-identity credential renewal `type:rfc` 💬1
- [#12130](https://github.com/zeroclaw-labs/zeroclaw/issues/12130) [Feature]: Configurable daemon session quotas with local operator reserve `enhancement` 💬1

### 🔒 Closed Issues
- [#12154](https://github.com/zeroclaw-labs/zeroclaw/issues/12154) [Bug]: install.sh shows the build commit instead of the version: "Installed: … (v(99bd353), 74M)"

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,702 · **Open issues:** 1,569 · **Last push:** 2d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,940 · **Open issues:** 121 · **Last push:** 9d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬2 · 8d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 8d ago
- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 18d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 27d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 35d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 37d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 47d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 55d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 57d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 65d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [Heretic 2.0 released: Model modification for everyone](https://reddit.com/r/LocalLLaMA/comments/1xl2tcm/heretic_20_released_model_modification_for/) ↑1159
- [[GLB-3D-Coder] A tiny 4B coding model that creates 3D assets for Godot and other game engines](https://reddit.com/r/LocalLLaMA/comments/1xlh0zw/glb3dcoder_a_tiny_4b_coding_model_that_creates_3d/) ↑167

### r/singularity — top 2 new
- [Anthropic's growing restrictions are creating a new divide in the AI capabilities race: Gemini 4 Argon recreates Pixar's iconic intro, while Claude Opus 5.5 refuses over copyright and builds a toaster](https://reddit.com/r/singularity/comments/1xl6vk8/anthropics_growing_restrictions_are_creating_a/) ↑1213
- [OpenAI is testing GPT-6.2 Astra](https://reddit.com/r/singularity/comments/1xl0rs3/openai_is_testing_gpt62_astra/) ↑431

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [migrating to hermes here is what i found so far](https://reddit.com/r/openclaw/comments/1xlbi42/migrating_to_hermes_here_is_what_i_found_so_far/) ↑18
- [What the hell? Why?](https://reddit.com/r/openclaw/comments/1xkzv2a/what_the_hell_why/) ↑5
- [Open source proactive to-do assistant & CRM for OpenClaw](https://reddit.com/r/openclaw/comments/1xl134v/open_source_proactive_todo_assistant_crm_for/) ↑3
- [I am absolutely slaying it with incorporating OpenClaw into my HVAC, and I don’t even like talking about lol.](https://reddit.com/r/openclaw/comments/1xlkz1p/i_am_absolutely_slaying_it_with_incorporating/) ↑2

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [OpenClaw v2026.10.9 is out 🦞

🔧 Update rollback fixes
💾 Agent data and chat archive repairs
📁 New editor sessions run in](https://x.com/openclaw/status/2115913639236665715)

### X — @steipete
_No new tweets since the last digest. Most recent:_
- [This is smart. Wild that this wasn’t the default. Unpredictable inference quality was usually why I recommended skipping](https://x.com/steipete/status/2116183103530217488)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
