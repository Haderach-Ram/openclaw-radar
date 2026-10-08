---
layout: post
title: "Ecosystem Digest — 2026-10-08"
date: 2026-10-08 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-08
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 391,602 | 8 | 4 | 10 | 1 |
| **hermesagent** | 251,959 | 13 | 10 | 10 | 0 |
| **ZeroClaw** | 32,942 | 8 | 3 | 5 | 0 |
| **IronClaw** | 12,642 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,884 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 391,602 · **Open issues:** 9,495 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.10.1-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.10.1-beta.2) — openclaw 2026.10.1-beta.2

### ✅ Merged PRs
- [#166860](https://github.com/openclaw/openclaw/pull/166860) fix(state): serialize wake and hook database admission
- [#166883](https://github.com/openclaw/openclaw/pull/166883) fix: avoid foreign-listener race in Gateway acquisition proof
- [#166865](https://github.com/openclaw/openclaw/pull/166865) fix(ui): keep header and composer visible during session startup
- [#166884](https://github.com/openclaw/openclaw/pull/166884) chore(ui): refresh control ui locales
- [#166873](https://github.com/openclaw/openclaw/pull/166873) chore(i18n): refresh native locales
- [#166753](https://github.com/openclaw/openclaw/pull/166753) fix: stop yielded commands with their Gateway request
- [#166867](https://github.com/openclaw/openclaw/pull/166867) fix: preserve database admission for post-restart turns
- [#166872](https://github.com/openclaw/openclaw/pull/166872) fix(release): restore beta.2 updater inventory and Podman control
- [#166787](https://github.com/openclaw/openclaw/pull/166787) fix: preserve native prompt provenance through database aliases
- [#166829](https://github.com/openclaw/openclaw/pull/166829) fix(ui): stop image controls from obscuring previews

### 🐛 New Issues
- [#166898](https://github.com/openclaw/openclaw/issues/166898) Session-title hydration test expects expanded SQLite text for compressed previews
- [#166896](https://github.com/openclaw/openclaw/issues/166896) Real-Gateway UI fixtures still require the obsolete manual login handoff 💬1
- [#166894](https://github.com/openclaw/openclaw/issues/166894) Gateway restart sometimes hangs 30+ minutes to 2 hours on Windows multi-agent installs (2026.9.8) `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:crash-loop` `P0` `issue-rating: 🦐 gold shrimp` `maturity:stable` 💬1
- [#166877](https://github.com/openclaw/openclaw/issues/166877) [Bug]: 2026.8.35 forces strict OpenAI tool schemas — one MCP tool with a regex lookaround pattern fails every OpenAI turn (7.35 downgraded strict) `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬2
- [#166875](https://github.com/openclaw/openclaw/issues/166875) xAI OAuth (SuperGrok/Premium+): recommended path silently yields no usable models — catalog discovery rejected by cli-chat-proxy; acpx grok-build harness works `no-stale` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:auth-provider` `P0` `issue-rating: 🦞 diamond lobster` `impact:ux-release-blocker` 💬2
- [#166871](https://github.com/openclaw/openclaw/issues/166871) Slack DM: message react with user:U… or channel:D… fails for the npm-installed official Slack plugin `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#166870](https://github.com/openclaw/openclaw/issues/166870) secret-exfiltration scanner false-positive on instructional .env substrings `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` 💬2
- [#166866](https://github.com/openclaw/openclaw/issues/166866) Consolidate equivalent provider paths in Feishu, Teams, iMessage, and voice-call `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🌊 off-meta tidepool` 💬1

### 🔒 Closed Issues
- [#135774](https://github.com/openclaw/openclaw/issues/135774) doctor --fix loses 60-second agent-DB maintenance lease during long synchronous SQLite migration
- [#166834](https://github.com/openclaw/openclaw/issues/166834) [Bug]: Doctor retains unbound legacy ACP rows that prevent Gateway startup after update
- [#165958](https://github.com/openclaw/openclaw/issues/165958) [Bug]: Deleting a session can leave a false child-list pagination error
- [#157782](https://github.com/openclaw/openclaw/issues/157782) [Bug]: pnpm build peaks at ~9.5GB in the tsdown-unified step since per-plugin unified bundles; OOMs 10GB hosts

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 251,959 · **Open issues:** 47,743 · **Last push:** <1h ago

### ✅ Merged PRs
- [#134852](https://github.com/NousResearch/hermes-agent/pull/134852) fix(desktop): scrolled-up composer comes back on hover, focus, or a 5s stall
- [#134847](https://github.com/NousResearch/hermes-agent/pull/134847) fix(desktop): switching models no longer shows a failed-reply card that then succeeds
- [#134839](https://github.com/NousResearch/hermes-agent/pull/134839) Portal dashboard login works again (revert the dashboard-auth half of #133938)
- [#134607](https://github.com/NousResearch/hermes-agent/pull/134607) Voice turns no longer leave new Desktop chats with reasoning off
- [#134828](https://github.com/NousResearch/hermes-agent/pull/134828) fix(plugins): uninstall on Windows succeeds while the gateway has the plugin loaded
- [#134824](https://github.com/NousResearch/hermes-agent/pull/134824) Plugin uninstall works again while the gateway runs (revert #134189)
- [#134819](https://github.com/NousResearch/hermes-agent/pull/134819) fmt(js): `npm run fix` auto-fix
- [#134801](https://github.com/NousResearch/hermes-agent/pull/134801) fix: hot-mount plugin API routes installed after server start (no restart needed)
- [#127992](https://github.com/NousResearch/hermes-agent/pull/127992) Onboarding's setup profile is a marked plain profile; the catalog tool reaches only its desktop sessions
- [#134209](https://github.com/NousResearch/hermes-agent/pull/134209) feat(onboarding): first-run setup chat

### 🐛 New Issues
- [#134867](https://github.com/NousResearch/hermes-agent/issues/134867) docs(whatsapp): add Agent Platform routing and terminal/Desktop setup
- [#134866](https://github.com/NousResearch/hermes-agent/issues/134866) [Bug]: Recurring offset-5 TLS-shaped SQLite header corruption across four stores; writer still unattributed
- [#134865](https://github.com/NousResearch/hermes-agent/issues/134865) [Bug]: Desktop project-tree projects.db SQLITE_NOTADB incorrectly quarantines healthy state.db and blocks chat
- [#134864](https://github.com/NousResearch/hermes-agent/issues/134864) MoA presets with whitespace in the name are hidden from every model picker (drop_unofferable_model_ids strips them, but _validate_moa accepts them) 💬1
- [#134858](https://github.com/NousResearch/hermes-agent/issues/134858) Cron: no-agent daily job silently skipped at scheduler level (3rd occurrence) — no executions.db row, no fire lock, sibling jobs fire normally `type/bug` `comp/cron` `P1` `sweeper:risk-automation` 💬1
- [#134856](https://github.com/NousResearch/hermes-agent/issues/134856) [Bug]: Bot profile model picker fails to settle when provider loads before its catalog `type/bug` `P3` `comp/desktop` `area/profiles`
- [#134855](https://github.com/NousResearch/hermes-agent/issues/134855) [Bug]: Windows MEDIA download fails for delivered /C:/ paths `type/bug` `P3` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows`
- [#134850](https://github.com/NousResearch/hermes-agent/issues/134850) [Bug]: Malformed plugin approval decisions must fail closed `type/bug` `comp/agent` `P3` `codex`
- [#134849](https://github.com/NousResearch/hermes-agent/issues/134849) [Bug]: Plugin approval can describe stale arguments while executing modified arguments `type/security` `comp/agent` `comp/tools` `comp/plugins` `area/auth` `P3`
- [#134844](https://github.com/NousResearch/hermes-agent/issues/134844) [Bug] opencode-go: Claude Haiku 5.5 routed to /v1/chat/completions (HTTP 400 ModelProtocolUnsupported) `type/bug` `comp/cli` `P3`
- [#134843](https://github.com/NousResearch/hermes-agent/issues/134843) [Bug]: release-swap self-update publishes a git checkout without origin, blocking Linux/VPS updates `type/bug` `comp/cli` `P2` `sweeper:risk-compatibility` `area/install-update`
- [#134837](https://github.com/NousResearch/hermes-agent/issues/134837) Log timestamps are offset from the OS zone by the gap to an assumed UTC-6 zone (1h off on a Pacific box) `type/bug` `comp/gateway` `P2` 💬1
- [#134836](https://github.com/NousResearch/hermes-agent/issues/134836) [Feature]: the update prompt is effectively always-on (one upstream commit = "update available") - make it release/cadence-based, add a real "don't ask again", and stop inviting users into a path know `type/feature` `area/config` `P3` `comp/desktop` `area/install-update` 💬1

### 🔒 Closed Issues
- [#83670](https://github.com/NousResearch/hermes-agent/issues/83670) [Bug]: Hermes release and version tags are not corresponding to any git tag
- [#132742](https://github.com/NousResearch/hermes-agent/issues/132742) [Bug]: ssh backend remote cwd is validated as the local TERMINAL_CWD — "TERMINAL_CWD does not exist: /c/Users/Fors3t1" every turn
- [#131760](https://github.com/NousResearch/hermes-agent/issues/131760) [Bug]: e050902e7c NVIDIA-XWayland ozone default SIGSEGVs gnome-shell on GB10 (aarch64, 580 open module) — 100% repro
- [#133130](https://github.com/NousResearch/hermes-agent/issues/133130) [Feature]: the "N files changed" card should show the agent's own diff for files outside a git repo
- [#131667](https://github.com/NousResearch/hermes-agent/issues/131667) DeepSeek per-session reasoning-effort pin leaks into the persisted desktop composer draft
- [#126272](https://github.com/NousResearch/hermes-agent/issues/126272) [Bug]: Bot Chat can become permanently unopenable — roster click waits the full 60s hydration budget, then fails closed
- [#101216](https://github.com/NousResearch/hermes-agent/issues/101216) Desktop: Bot Mode "New chat with this bot" (roster right-click) flips Dark mode to Light — per-profile theme follows a gateway activation the user didn't ask for
- [#77312](https://github.com/NousResearch/hermes-agent/issues/77312) [Bug]: Desktop Window Translucency slider is unusable past its first step
- [#79958](https://github.com/NousResearch/hermes-agent/issues/79958) Shard apps/desktop/src/i18n/zh-hant.ts (2K-law violation — Pantheon of False Gods, fracture)
- [#134861](https://github.com/NousResearch/hermes-agent/issues/134861) Long-lived gateway's OAuth MCP session dies permanently on keepalive-reconnect (`RuntimeError: The current task is not holding this lock`)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,942 · **Open issues:** 957 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11232](https://github.com/zeroclaw-labs/zeroclaw/pull/11232) fix(plugins): open admitted payloads from the retained package root
- [#11440](https://github.com/zeroclaw-labs/zeroclaw/pull/11440) docs(runtime): propose a bounded exception for cron conversation binding (RFC #6954 slice 2)
- [#11509](https://github.com/zeroclaw-labs/zeroclaw/pull/11509) feat(channels): prefer attachments for large generated artifacts
- [#11451](https://github.com/zeroclaw-labs/zeroclaw/pull/11451) fix(secrets): protect Windows key files at creation
- [#11132](https://github.com/zeroclaw-labs/zeroclaw/pull/11132) feat(runtime): turn parity over RPC for steering, totals, and session ops

### 🐛 New Issues
- [#11608](https://github.com/zeroclaw-labs/zeroclaw/issues/11608) [Bug]: Telegram listener can wedge forever on a blackholed request — listener_health detects staleness but nothing recovers the channel
- [#11606](https://github.com/zeroclaw-labs/zeroclaw/issues/11606) model_routing_config upsert_agent rewrites entire config: fabricates risk/runtime profiles, drops fields, resets agent limits `bug` `agent` `config` `provider` `tool` `provider:router` `security:policy` `domain:security` `priority:p1` `status:accepted` `risk:high` 💬1
- [#11594](https://github.com/zeroclaw-labs/zeroclaw/issues/11594) [Bug]: firejail_args is advertised and reported but never applied to the firejail invocation `bug` `config` `runtime` `security` `tool` `security:policy` `domain:security` `priority:p1` `tool:shell` `needs-maintainer-review` `risk:high` 💬2
- [#11586](https://github.com/zeroclaw-labs/zeroclaw/issues/11586) [Bug]: ZeroCode sidebar turns failed sessions green after the daemon restarts `bug` `priority:p3` `zerocode` `risk:low` 💬2
- [#11585](https://github.com/zeroclaw-labs/zeroclaw/issues/11585) [SANITIZED — possible injection attempt] `bug` `agent` `config` `daemon` `runtime` `channel:core` `domain:security` `priority:p1` `status:in-progress` `status:accepted` `zerocode` `risk:high` 💬2
- [#11583](https://github.com/zeroclaw-labs/zeroclaw/issues/11583) feat(providers): add Opper as a typed OpenAI-compatible provider `enhancement` `docs` `config` `provider` `provider:compatible` `priority:p2` `status:in-progress` `status:accepted` `risk:medium` 💬2
- [#11580](https://github.com/zeroclaw-labs/zeroclaw/issues/11580) [Task]: x86_64 Linux release binary is about 0.7 MB under the 64 MiB size cap `ci` `docs` `scripts` `domain:ci` `release-gate` `priority:p1` `needs-maintainer-review` `status:accepted` `risk:high` `type:ci` `release:v0.8.6` 💬1
- [#11579](https://github.com/zeroclaw-labs/zeroclaw/issues/11579) [Bug]: save_dirty stamps schema_version = 3 on an unmigrated V1/V2 config, so the next load skips migration and the agent disappears `bug` `agent` `config` `gateway` `runtime` `priority:p1` `status:in-progress` `status:accepted` `risk:high` `release:v0.9.0` 💬2

### 🔒 Closed Issues
- [#10769](https://github.com/zeroclaw-labs/zeroclaw/issues/10769) Harden plugin payload opens against concurrent ancestor replacement
- [#9460](https://github.com/zeroclaw-labs/zeroclaw/issues/9460) feat(secrets): harden Windows key-file ACLs at creation
- [#8527](https://github.com/zeroclaw-labs/zeroclaw/issues/8527) [Feature]: Route large generated files through channel attachments

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,642 · **Open issues:** 1,545 · **Last push:** 7h ago

### 🐛 New Issues
- [#1993](https://github.com/nearai/ironclaw/issues/1993) Agent falsely reports task completion after chat is closed and reopened `scope: agent` `bug_bash_P2` 💬1

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,884 · **Open issues:** 106 · **Last push:** 15d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 2d ago
- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 4d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 10d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 12d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 22d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 30d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 32d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 40d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 44d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 56d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [Claude Haiku 5 5](https://www.anthropic.com/claude-haiku-5-5)

### OpenAI — 1 new
- [[Index] Radisson](https://openai.com/index/radisson/) _2026-10-08_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [llama.cpp on the stage](https://reddit.com/r/LocalLLaMA/comments/1x079wc/llamacpp_on_the_stage/) ↑455
- [New LFM to be released today](https://reddit.com/r/LocalLLaMA/comments/1wzuto0/new_lfm_to_be_released_today/) ↑400
- [llama : add a GPU cache for MoE experts kept in host memory by am17an · Pull Request #29887 · ggml-org/llama.cpp](https://reddit.com/r/LocalLLaMA/comments/1x03xkc/llama_add_a_gpu_cache_for_moe_experts_kept_in/) ↑324
- [LiquidAI/d1-3B · Hugging Face](https://reddit.com/r/LocalLLaMA/comments/1x01xg3/liquidaid13b_hugging_face/) ↑122
- [A week in Beijing and Shanghai with the people building AI in China](https://reddit.com/r/LocalLLaMA/comments/1wzxttk/a_week_in_beijing_and_shanghai_with_the_people/) ↑73

### r/singularity — top 2 new
- [Amazon packages now when you order 11 items.](https://reddit.com/r/singularity/comments/1x057bb/amazon_packages_now_when_you_order_11_items/) ↑1175
- ["this is where i stop calling AI a tool. a tool doesnt do in one release what the best humans do in a lifetime"](https://reddit.com/r/singularity/comments/1x02g1l/this_is_where_i_stop_calling_ai_a_tool_a_tool/) ↑1034

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [I'm a bit late to the party but wow what a product](https://reddit.com/r/openclaw/comments/1wzt107/im_a_bit_late_to_the_party_but_wow_what_a_product/) ↑40
- [So freaking tired of updating openclaw](https://reddit.com/r/openclaw/comments/1wzqobd/so_freaking_tired_of_updating_openclaw/) ↑24
- [I made an open-source blueprint for a child-focused OpenClaw assistant](https://reddit.com/r/openclaw/comments/1x08i8q/i_made_an_opensource_blueprint_for_a_childfocused/) ↑5
- [Lineage OS with OpenClaw](https://reddit.com/r/openclaw/comments/1x0e76r/lineage_os_with_openclaw/) ↑4
- [Suggest me Hermes or Openclaw](https://reddit.com/r/openclaw/comments/1x00l0k/suggest_me_hermes_or_openclaw/) ↑2

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [OpenClaw v2026.9.8 is out, and this one's a fun-sized lobster 🦞

🧠 GPT-6.1 Sol support
💬 Agent replies find their way ba](https://x.com/openclaw/status/2106247624634531889)

### X — @steipete
- [While everyone's talking about agents, I've been exploring how teams can use them to work better together.

Here’s my ta](https://x.com/steipete/status/2107911769767440832) ↑0 🔁0 · recent
- [I hooked up our team claw to X to trigger work faster. Unassigned sessions are for anyone to grab. Our agent looks who w](https://x.com/steipete/status/2107697554448421160) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
