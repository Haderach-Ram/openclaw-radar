---
layout: post
title: "Ecosystem Digest — 2026-10-04"
date: 2026-10-04 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-04
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 391,246 | 6 | 4 | 10 | 1 |
| **hermesagent** | 250,994 | 12 | 6 | 10 | 0 |
| **ZeroClaw** | 32,925 | 7 | 7 | 9 | 0 |
| **IronClaw** | 12,636 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,884 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 391,246 · **Open issues:** 9,275 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.9.8](https://github.com/openclaw/openclaw/releases/tag/v2026.9.8) — openclaw 2026.9.8

### ✅ Merged PRs
- [#164588](https://github.com/openclaw/openclaw/pull/164588) refactor(auth-profiles): record shared auth-profile usage through workers
- [#164686](https://github.com/openclaw/openclaw/pull/164686) test(memory): speed up session-file tests
- [#162275](https://github.com/openclaw/openclaw/pull/162275) fix: finish Doctor upgrades for public plugin setup entries
- [#164677](https://github.com/openclaw/openclaw/pull/164677) fix(update): hand the private Node runtime to npm lifecycle children
- [#164520](https://github.com/openclaw/openclaw/pull/164520) refactor(runtime): deslop runtime caches
- [#164637](https://github.com/openclaw/openclaw/pull/164637) refactor(native): deslop macOS and Android shells
- [#164679](https://github.com/openclaw/openclaw/pull/164679) refactor(media): deslop media
- [#164649](https://github.com/openclaw/openclaw/pull/164649) fix(telegram): streamed reply vanishes when its replacement message never lands
- [#164676](https://github.com/openclaw/openclaw/pull/164676) fix: restore Codex registration tests on Linux
- [#164680](https://github.com/openclaw/openclaw/pull/164680) fix: reduce Windows startup delays with installed plugins

### 🐛 New Issues
- [#164699](https://github.com/openclaw/openclaw/issues/164699) [Bug]: openclaw update rolls back with EXDEV at package-swap when the npm package was installed in a Docker image layer (overlayfs) `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `P0` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-release-blocker` 💬1
- [#164696](https://github.com/openclaw/openclaw/issues/164696) [Bug]: claude-cli live session holds WhatsApp reply until the next inbound message (turn completion not observed) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `impact:message-loss` `issue-rating: 🦪 silver shellfish` 💬1
- [#164695](https://github.com/openclaw/openclaw/issues/164695) [Bug]: macOS Desktop update hangs after package publication during post-core settlement `bug` `regression` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `P0` `issue-rating: 🦪 silver shellfish` `impact:ux-release-blocker` 💬1
- [#164693](https://github.com/openclaw/openclaw/issues/164693) fix(update): managed handoff hides early refusal reason and details `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬1
- [#164690](https://github.com/openclaw/openclaw/issues/164690) [Bug] claude-cli runs spawn every stdio MCP server twice (Gateway policy runtime + CLI mcp.json); relay+anchor wrapper costs ~144 MB per stdio child, not configurable `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` 💬1
- [#164672](https://github.com/openclaw/openclaw/issues/164672) [Bug]: npm update aborts at package-swap with "Package publication object has an unsafe identity" when the Node prefix bin/ and lib/node_modules are owned by another uid (nvm installed as root) `no-stale` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `P0` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-release-blocker` 💬1

### 🔒 Closed Issues
- [#164525](https://github.com/openclaw/openclaw/issues/164525) [Bug]: Private Node runtime is not propagated to npm lifecycle child processes
- [#164611](https://github.com/openclaw/openclaw/issues/164611) Gate superseded-preview delete on confirmed replacement delivery (draft-stream.ts)
- [#164610](https://github.com/openclaw/openclaw/issues/164610) Streaming preview deleted without persistent replacement on harness turns
- [#164646](https://github.com/openclaw/openclaw/issues/164646) [Bug]: Activity E2E waits for a redundant session refresh

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 250,994 · **Open issues:** 47,863 · **Last push:** <1h ago

### ✅ Merged PRs
- [#132457](https://github.com/NousResearch/hermes-agent/pull/132457) hermes -z now closes its Relay session (fixes #79471)
- [#132518](https://github.com/NousResearch/hermes-agent/pull/132518) fix(whatsapp): serve a paired WhatsApp session on every profile under the host multiplexer
- [#132512](https://github.com/NousResearch/hermes-agent/pull/132512) fix(launchers): bind published launchers to the install's own store, not an inherited runtime dir
- [#131127](https://github.com/NousResearch/hermes-agent/pull/131127) fix(plugins): a forced reinstall of the same source keeps the user's files
- [#132409](https://github.com/NousResearch/hermes-agent/pull/132409) fix(desktop): list the active gateway's default in the condensed fleet menu
- [#128144](https://github.com/NousResearch/hermes-agent/pull/128144) fix(nix): pick up wayland in the desktop app
- [#132464](https://github.com/NousResearch/hermes-agent/pull/132464) Duplicate skill names resolve the same way on every surface (salvage #64462, #55634)
- [#132462](https://github.com/NousResearch/hermes-agent/pull/132462) fix(agent): stamp the activity clock at turn end and dump stacks on watchdog fire [risk 0.80]
- [#132377](https://github.com/NousResearch/hermes-agent/pull/132377) fix(process_registry): PTY kill no longer hangs on a setsid() escapee
- [#132458](https://github.com/NousResearch/hermes-agent/pull/132458) fmt(js): `npm run fix` auto-fix

### 🐛 New Issues
- [#132532](https://github.com/NousResearch/hermes-agent/issues/132532) [Feature]: Installer resilience improvements for GitHub-restricted networks (mainland China) - stale script cache, no mirror fallback, misleading recovery hints
- [#132531](https://github.com/NousResearch/hermes-agent/issues/132531) [Bug]: bootstrap-installer.log garbles all non-ASCII output (UTF-8/GBK mixing) on Chinese-locale Windows
- [#132526](https://github.com/NousResearch/hermes-agent/issues/132526) Web toolset picker: "Ready" badge does not reflect actual backend availability
- [#132522](https://github.com/NousResearch/hermes-agent/issues/132522) [Bug]: Telegram DM topics are recreated as duplicates when the adapter is rebuilt after a network incident `type/bug` `comp/gateway` `platform/telegram` `P2` `sweeper:risk-message-delivery`
- [#132517](https://github.com/NousResearch/hermes-agent/issues/132517) [Bug]: multiplexed gateway: a served profile's own quick_commands are never consulted (Unknown command) `type/bug` `comp/gateway` `P2` `area/profiles`
- [#132516](https://github.com/NousResearch/hermes-agent/issues/132516) [Bug]: exec-approval prompts are sent with disable_notification in Telegram "important" mode, so a degraded prompt times out unseen `type/bug` `comp/gateway` `platform/telegram` `P2` `sweeper:risk-message-delivery`
- [#132515](https://github.com/NousResearch/hermes-agent/issues/132515) skills.external_dirs set via managed scope is recognized/enforced by config resolution but ignored by skill discovery `type/bug` `duplicate` `tool/skills` `area/config` `P2` `sweeper:risk-compatibility`
- [#132511](https://github.com/NousResearch/hermes-agent/issues/132511) Web toolset picker: "Active backend" ignores web.search_backend / web.extract_backend `type/bug` `tool/web` `area/config` `P3` `comp/desktop` 💬2
- [#132508](https://github.com/NousResearch/hermes-agent/issues/132508) [SANITIZED — possible injection attempt] `type/bug` `backend/ssh` `P2` `comp/desktop` 💬3
- [#132507](https://github.com/NousResearch/hermes-agent/issues/132507) approval: a plugin-escalated approval with no user present tells the agent to find another route and how to switch approvals to approve `type/bug` `comp/tools` `comp/plugins` `area/auth` `P3` `sweeper:risk-security-boundary`
- [#132504](https://github.com/NousResearch/hermes-agent/issues/132504) OpenRouter 403 "prompt injection patterns detected" from bundled skills containing <tool> — mislabelled as a firewall block, and it poisons the whole session `type/bug` `comp/agent` `tool/skills` `provider/openrouter` `P1` `sweeper:risk-session-state` `area/sessions` 💬1
- [#132502](https://github.com/NousResearch/hermes-agent/issues/132502) [SANITIZED — possible injection attempt] `type/docs` `question` `comp/cron` `tool/terminal` `area/auth` `P3` 💬1

### 🔒 Closed Issues
- [#79471](https://github.com/NousResearch/hermes-agent/issues/79471) [Bug]: One-shot execution exits without closing the Relay session lifecycle
- [#131745](https://github.com/NousResearch/hermes-agent/issues/131745) [Bug] Launcher published against e2e scratch Python — gateway exit-127 crash loop after reboot
- [#131126](https://github.com/NousResearch/hermes-agent/issues/131126) [Bug]: hermes plugins install --force deletes the plugin's user files, and it is the only documented way to move a pinned plugin
- [#132505](https://github.com/NousResearch/hermes-agent/issues/132505) [SANITIZED — possible injection attempt]
- [#126063](https://github.com/NousResearch/hermes-agent/issues/126063) [Feature]: Ship a pre-installed "Hermes Ops" expert profile the main agent can consult + a proactive update reporter
- [#131632](https://github.com/NousResearch/hermes-agent/issues/131632) Desktop: fleet mode leaves the local default profile with no entry point in the profile picker

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,925 · **Open issues:** 926 · **Last push:** 5h ago

### ✅ Merged PRs
- [#11439](https://github.com/zeroclaw-labs/zeroclaw/pull/11439) docs(runtime): propose bounded session-prompt exception
- [#11430](https://github.com/zeroclaw-labs/zeroclaw/pull/11430) chore(deps): bump distroless/cc-debian13 from `54df941` to `e792ab3`
- [#11219](https://github.com/zeroclaw-labs/zeroclaw/pull/11219) fix(zerocode): start fresh local sessions in the launch directory
- [#11461](https://github.com/zeroclaw-labs/zeroclaw/pull/11461) fix(tools): clarify sessions_send append semantics
- [#11447](https://github.com/zeroclaw-labs/zeroclaw/pull/11447) test(runtime): avoid fresh executables in process fixtures
- [#11459](https://github.com/zeroclaw-labs/zeroclaw/pull/11459) refactor(zerocode): centralize transcript layout cache
- [#11445](https://github.com/zeroclaw-labs/zeroclaw/pull/11445) fix(zerocode): retain recovery notices in ACP history
- [#11424](https://github.com/zeroclaw-labs/zeroclaw/pull/11424) fix(daemon): fail fast on macOS SIGBUS after executable loss
- [#11475](https://github.com/zeroclaw-labs/zeroclaw/pull/11475) fix(deps): upgrade Wasmtime to clear eight RustSec advisories

### 🐛 New Issues
- [#11517](https://github.com/zeroclaw-labs/zeroclaw/issues/11517) [Bug]: Web chat: reloading mid-turn drops the user's prompt (screen and localStorage) because hydration replaces local state with a snapshot that predates the running turn
- [#11515](https://github.com/zeroclaw-labs/zeroclaw/issues/11515) [Bug]: cost ledger drops torn-write records from all rollups (WARN only, no quarantine, totals look complete) `bug`
- [#11492](https://github.com/zeroclaw-labs/zeroclaw/issues/11492) [Feature]: Improve action discovery in ZeroCode client settings `enhancement` `priority:p2` `status:in-progress` `risk:medium` `zerocode`
- [#11491](https://github.com/zeroclaw-labs/zeroclaw/issues/11491) [Feature]: Show saved versus applied config status in ZeroCode Config `enhancement` `config` `priority:p2` `status:in-progress` `risk:medium` `zerocode`
- [#11490](https://github.com/zeroclaw-labs/zeroclaw/issues/11490) [Feature]: Explain empty Config sections and alias setup in ZeroCode `enhancement` `config` `priority:p2` `status:in-progress` `risk:medium` `zerocode`
- [#11489](https://github.com/zeroclaw-labs/zeroclaw/issues/11489) [Feature]: Improve Config field labels and access to full descriptions in ZeroCode `enhancement` `config` `priority:p2` `status:in-progress` `zerocode` `risk:low`
- [#11488](https://github.com/zeroclaw-labs/zeroclaw/issues/11488) [Bug]: ZeroCode Config filtering affects both panes and loses the section on cancel `bug` `config` `priority:p2` `status:in-progress` `risk:medium` `zerocode`

### 🔒 Closed Issues
- [#7108](https://github.com/zeroclaw-labs/zeroclaw/issues/7108) feat(ci): improve cached Rust builds and CI critical path
- [#10662](https://github.com/zeroclaw-labs/zeroclaw/issues/10662) [Bug]: OAuth system-prefix cache marker is below Anthropic's cache minimum and consumes one of the four breakpoint slots
- [#10734](https://github.com/zeroclaw-labs/zeroclaw/issues/10734) [Bug]: RpcDispatcher::process_line runs within 2% of its 2 MB stack guard (surfaced by Advisory Windows nextest)
- [#10701](https://github.com/zeroclaw-labs/zeroclaw/issues/10701) [Bug]: a user message with an image attachment invalidates the whole history cache prefix, not just the new message
- [#11387](https://github.com/zeroclaw-labs/zeroclaw/issues/11387) [Bug]: zerocode ignores its launch directory again and forces the agent workspace as cwd (regression of #10609)
- [#10293](https://github.com/zeroclaw-labs/zeroclaw/issues/10293) [Feature]: Define explicit lifecycle semantics for sessions_send
- [#10739](https://github.com/zeroclaw-labs/zeroclaw/issues/10739) [Feature]: Extract ZeroCode transcript layout cache ownership

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,636 · **Open issues:** 1,539 · **Last push:** 2d ago

### 🐛 New Issues
- [#8122](https://github.com/nearai/ironclaw/issues/8122) ironclaw serve fails with credential read failed: BackendUnavailable for extension web-app on macOS (local-dev profile)

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,884 · **Open issues:** 102 · **Last push:** 11d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 7h ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 6d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 7d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 8d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 18d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 26d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 28d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 36d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 40d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 52d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [I made my iPhone a second GPU for my 24 GB MacBook: Qwen 3.8 27B prefills 29–44% faster & my holds part of the CTX window.](https://reddit.com/r/LocalLLaMA/comments/1wvz1ex/i_made_my_iphone_a_second_gpu_for_my_24_gb/) ↑1687
- [Qwen3.8-27B-Humanlike-Chat 2.0: texts like a human, now with tool calls and better instruction following](https://reddit.com/r/LocalLLaMA/comments/1wvxl4n/qwen3827bhumanlikechat_20_texts_like_a_human_now/) ↑804
- [I'm pretty close to the middle thanks to you all](https://reddit.com/r/LocalLLaMA/comments/1wwbcdt/im_pretty_close_to_the_middle_thanks_to_you_all/) ↑479
- [Yes bots we get it, Strata is good now please stop](https://reddit.com/r/LocalLLaMA/comments/1wwobfg/yes_bots_we_get_it_strata_is_good_now_please_stop/) ↑471
- [Aleph-Alpha/Kolibri-1 · Hugging Face - 78B parameters. 3.46B active. Up to 1M tokens of context - Apache 2.0](https://reddit.com/r/LocalLLaMA/comments/1wwl7y6/alephalphakolibri1_hugging_face_78b_parameters/) ↑466

### r/singularity — top 5 new
- [Gemini 4 Argon solved hallucinations.](https://reddit.com/r/singularity/comments/1wuj72j/gemini_4_argon_solved_hallucinations/) ↑1560
- [Intelligence Explosion](https://reddit.com/r/singularity/comments/1wwjonr/intelligence_explosion/) ↑406
- [Could the simulated fruit-fly brain be considered the first “immortal” living being?](https://reddit.com/r/singularity/comments/1wwr56b/could_the_simulated_fruitfly_brain_be_considered/) ↑341
- [I Quit OpenAI Because Its Culture Is Broken](https://reddit.com/r/singularity/comments/1wwlywn/i_quit_openai_because_its_culture_is_broken/) ↑205
- [Google is changing Gemini model access starting Oct 9](https://reddit.com/r/singularity/comments/1wwwe6m/google_is_changing_gemini_model_access_starting/) ↑86

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Updating OpenClaw is harder than moving to a new house IRL](https://reddit.com/r/openclaw/comments/1wwi635/updating_openclaw_is_harder_than_moving_to_a_new/) ↑75
- [OpenClaw v2026.9.8 | GPT-6.1 Sol, bug fixes, and a suspiciously small lobster](https://reddit.com/r/openclaw/comments/1wwepgl/openclaw_v202698_gpt61_sol_bug_fixes_and_a/) ↑14
- [I don't read Hebrew, so I built a plugin that translates the WhatsApp groups my family depends on](https://reddit.com/r/openclaw/comments/1wwtudl/i_dont_read_hebrew_so_i_built_a_plugin_that/) ↑8
- [Happy to Report version 9.8 is Good](https://reddit.com/r/openclaw/comments/1wx3htb/happy_to_report_version_98_is_good/) ↑6
- [New Sessions are broken in 2006.9.7, 8!](https://reddit.com/r/openclaw/comments/1wx3jb8/new_sessions_are_broken_in_200697_8/) ↑1

### X — @openclaw
- [OpenClaw v2026.9.8 is out, and this one's a fun-sized lobster 🦞

🧠 GPT-6.1 Sol support
💬 Agent replies find their way ba](https://x.com/openclaw/status/2106247624634531889) ↑0 🔁0 · recent


### X — @steipete
- [laughing about how we all are building the same thing.](https://x.com/steipete/status/2106489264443981978) ↑0 🔁0 · recent
- [Do I know anyone at Google who could help? We're now over a week in review limbo for OpenClaw's Android app.](https://x.com/steipete/status/2106446147791597774) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
