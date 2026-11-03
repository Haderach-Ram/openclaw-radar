---
layout: post
title: "Ecosystem Digest — 2026-11-03"
date: 2026-11-03 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-03
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 393,759 | 7 | 3 | 10 | 0 |
| **hermesagent** | 259,894 | 14 | 5 | 5 | 1 |
| **ZeroClaw** | 33,107 | 15 | 1 | 4 | 0 |
| **IronClaw** | 12,708 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,939 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 393,759 · **Open issues:** 7,747 · **Last push:** <1h ago

### ✅ Merged PRs
- [#191587](https://github.com/openclaw/openclaw/pull/191587) fix(auth): cron fallback fails with another provider’s session pin
- [#191602](https://github.com/openclaw/openclaw/pull/191602) fix(voice-call): keep late caller transcripts ahead of replies
- [#191585](https://github.com/openclaw/openclaw/pull/191585) fix(feishu): deliver captioned media with block streaming disabled
- [#191595](https://github.com/openclaw/openclaw/pull/191595) test(discord): assert exact approval truncation boundary
- [#191599](https://github.com/openclaw/openclaw/pull/191599) feat(plugins): agent_end hooks receive the completed turn to fork
- [#191586](https://github.com/openclaw/openclaw/pull/191586) perf(memory): attribute project recall preparation stages
- [#191574](https://github.com/openclaw/openclaw/pull/191574) fix(sandbox): avoid Podman discovery before every command
- [#191583](https://github.com/openclaw/openclaw/pull/191583) chore(worktrees): attribute ignored-file provisioning time
- [#191582](https://github.com/openclaw/openclaw/pull/191582) fix: reduce memory pressure during GitHub publication
- [#191547](https://github.com/openclaw/openclaw/pull/191547) fix(update): select PostgreSQL in migrated finalizer

### 🐛 New Issues
- [#191605](https://github.com/openclaw/openclaw/issues/191605) [Feature]: Android Gateway-owned pending inputs and receipt-aware send recovery 💬1
- [#191601](https://github.com/openclaw/openclaw/issues/191601) [Bug]: Linux 2026.10.9 standalone doctor --fix silent for ~79 min (0% CPU) after "Stopped the managed Gateway", then completes; Gateway down the whole time `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `impact:crash-loop` `issue-rating: 🦪 silver shellfish` `maturity:stable` 💬1
- [#191600](https://github.com/openclaw/openclaw/issues/191600) [Bug]: Session observer's 30 s deadline covers the utility fallback chain, so configured fallbacks get no time `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#191596](https://github.com/openclaw/openclaw/issues/191596) [Feature]: Android cursor-aware history and stable reading position `P2` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#191593](https://github.com/openclaw/openclaw/issues/191593) New-session view gets stuck on "Restoring your last session setup…" after archiving the active conversation `bug` `bug:behavior` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `P0` `issue-rating: 🦪 silver shellfish` `impact:ux-release-blocker` 💬1
- [#191590](https://github.com/openclaw/openclaw/issues/191590) [Bug]: Overflow recovery compaction hides the degraded-summary warning `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#191566](https://github.com/openclaw/openclaw/issues/191566) [Bug]: inbound turns to plugin-bound conversations refused by SessionCanonicalKeyMigrationRequiredError; doctor --fix does not repair plugin-binding:* keys `P2` `impact:session-state` `impact:message-loss` `issue-rating: 🦪 silver shellfish` 💬2

### 🔒 Closed Issues
- [#161810](https://github.com/openclaw/openclaw/issues/161810) [Bug]: Cron fallback candidate receives the primary provider's auth pin ("is not configured for openai")
- [#191542](https://github.com/openclaw/openclaw/issues/191542) [Bug]: On PostgreSQL families, a Git update that migrates state exits with update-recovery-pending because the migrated finalize worker reads the SQLite state anchor ("schema role missing")
- [#191412](https://github.com/openclaw/openclaw/issues/191412) [Bug]: install.sh gives PATH advice when Homebrew's Node is too old

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬69 · 1d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 259,894 · **Open issues:** 52,368 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.22.6](https://github.com/NousResearch/hermes-agent/releases/tag/v0.22.6) — Hermes Agent v0.22.6

### ✅ Merged PRs
- [#141376](https://github.com/NousResearch/hermes-agent/pull/141376) fix(approval): flag variation selectors that do not follow an emoji
- [#148216](https://github.com/NousResearch/hermes-agent/pull/148216) fix(web): run config schema build and egress status read off the event loop
- [#141377](https://github.com/NousResearch/hermes-agent/pull/141377) fix(approval): an approved rule no longer hides a credential upload
- [#148127](https://github.com/NousResearch/hermes-agent/pull/148127) fix(anthropic): treat Claude Mythos as mandatory-thinking
- [#148187](https://github.com/NousResearch/hermes-agent/pull/148187) fix(profiles): keep existing profile dirs when a force install fails

### 🐛 New Issues
- [#148262](https://github.com/NousResearch/hermes-agent/issues/148262) pm strips UV_CONCURRENT_DOWNLOADS, so a slow link cannot lower download concurrency — parallel large wheels all hit the HTTP timeout
- [#148261](https://github.com/NousResearch/hermes-agent/issues/148261) local_runtime: hardcoded `--load-mode dio` materializes spilled MoE experts as a 19 GB Vulkan host buffer → KV cache allocation fails with 1.9/8 GB VRAM in use (mmap loads fine)
- [#148258](https://github.com/NousResearch/hermes-agent/issues/148258) [Bug]: Matrix message "read only = no" renders as "read" `type/bug` `comp/plugins` `platform/matrix` `P2`
- [#148257](https://github.com/NousResearch/hermes-agent/issues/148257) [Bug]: Group Chat members can't be woken after a standalone→gateway handoff — "message.member authority epoch does not match the room" `type/bug` `comp/gateway` `P2` 💬1
- [#148255](https://github.com/NousResearch/hermes-agent/issues/148255) [Bug]: /model <alias> with key_env bills the default Anthropic key — per-request refresh and gateway restart drop the alias credential `type/security` `comp/agent` `comp/gateway` `tool/delegate` `provider/anthropic` `area/auth` `area/config` `P3` `area/sessions` 💬1
- [#148249](https://github.com/NousResearch/hermes-agent/issues/148249) local_runtime: GPU device probe silently fails when MSVCP140.dll is missing → budget falls back to system RAM → `spilled: false` on a model 3× larger than VRAM → ErrorOutOfDeviceMemory at load `type/bug` `comp/cli` `P2` `area/local-models` `os/windows`
- [#148248](https://github.com/NousResearch/hermes-agent/issues/148248) Multiplexed gateway: /new and /undo confirm reads the launch profile's approvals.destructive_slash_confirm, not the chat's profile `type/bug` `comp/gateway` `P2` `area/profiles`
- [#148246](https://github.com/NousResearch/hermes-agent/issues/148246) [Bug]: [Mobile app - Android beta] Direct connection option when adding an instance discovers that dashboards has Nous auth, but fails with "Unable to resolve host: [hostname]. No address associated w `type/bug` `area/auth` `P3`
- [#148245](https://github.com/NousResearch/hermes-agent/issues/148245) [Bug]: Desktop in remote-gateway mode ignores "Default project directory" for the first chat after launch (stale per-connection workspace wins) `type/bug` `area/config` `P2` `comp/desktop` `area/sessions` `desktop/chat` `desktop/sessions` 💬1
- [#148241](https://github.com/NousResearch/hermes-agent/issues/148241) [Bug]: 0.22.6 provider clients ignore SSL_CERT_FILE (resolve_httpx_verify drops the bundle), TLS fails behind intercepting proxies `type/bug` `comp/agent` `P2`
- [#148238](https://github.com/NousResearch/hermes-agent/issues/148238) [Bug]: session.resume refuses a chat whose stored cwd no longer exists, with a bare invalid_params `type/bug` `comp/gateway` `P2` `area/sessions` 💬1
- [#148237](https://github.com/NousResearch/hermes-agent/issues/148237) [Bug]: live-system test guard blocks its own subtree's teardown signal when psutil is absent, wedging pytest in Popen.__exit__'s unbounded wait `type/bug` `P2`
- [#148236](https://github.com/NousResearch/hermes-agent/issues/148236) Telegram: agent-facing labeled inline buttons (callback) for section navigation `type/feature` `comp/gateway` `comp/plugins` `platform/telegram` `P3`
- [#148235](https://github.com/NousResearch/hermes-agent/issues/148235) Buzz: native (imeta) attachment download is unauthenticated, always gets HTTP 401, and tells the agent the attachment failed even when the media localizer fetched it `type/bug` `comp/plugins` `area/auth` `P2`

### 🔒 Closed Issues
- [#143268](https://github.com/NousResearch/hermes-agent/issues/143268) [Bug] LOCAL Kanban notify+wake never reaches the session FIFO: LocalSessionAdapter has no gateway_runner
- [#147036](https://github.com/NousResearch/hermes-agent/issues/147036) [Bug]: /api/config/schema builds the config schema on the event loop, freezing every other request (and /api/ws chat) for ~3 s
- [#148197](https://github.com/NousResearch/hermes-agent/issues/148197) Feature: restore model_picker.models / provider_priority readers, or add a transform_models_payload plugin hook
- [#148198](https://github.com/NousResearch/hermes-agent/issues/148198) Feature: add correlation_id to tool-hook payloads
- [#88918](https://github.com/NousResearch/hermes-agent/issues/88918) [Bug]: Canonical Bot Chat stays on 429 after Codex account switch and cannot be reset or reassigned

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,107 · **Open issues:** 1,159 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11297](https://github.com/zeroclaw-labs/zeroclaw/pull/11297) fix(runtime): honour keep_tool_context_turns when building provider requests
- [#11174](https://github.com/zeroclaw-labs/zeroclaw/pull/11174) feat(runtime): add capability-taking constructors for turn entry points
- [#12200](https://github.com/zeroclaw-labs/zeroclaw/pull/12200) fix(deps): bump pulldown-cmark to 0.13.6 for RUSTSEC-2026-0433
- [#11686](https://github.com/zeroclaw-labs/zeroclaw/pull/11686) docs(plugins): correct the call_channel! note on results that fail to lift

### 🐛 New Issues
- [#12205](https://github.com/zeroclaw-labs/zeroclaw/issues/12205) [Bug]: Empty canvases are never removed, stay in the viewer list and count toward the 100-canvas limit
- [#12203](https://github.com/zeroclaw-labs/zeroclaw/issues/12203) web_search_tool silently compiled out without tools-external — no TOOL_COMPILED_OUT warning
- [#12199](https://github.com/zeroclaw-labs/zeroclaw/issues/12199) config validate: warn on dead delegate grants (delegates roster unreachable under delegation_policy.mode = forbidden)
- [#12194](https://github.com/zeroclaw-labs/zeroclaw/issues/12194) runtime: unknown model silently falls back to a 32k context budget (UNCONFIGURED_CONTEXT_WINDOW_FALLBACK) and fails turns that would fit the real window
- [#12193](https://github.com/zeroclaw-labs/zeroclaw/issues/12193) gateway: single-command bearer token rotation (paired_tokens hash drift breaks WS with no rollback path)
- [#12191](https://github.com/zeroclaw-labs/zeroclaw/issues/12191) [Feature]: hybrid (dense + BM25) recall for the Qdrant memory backend
- [#12190](https://github.com/zeroclaw-labs/zeroclaw/issues/12190) [Feature]:  Let a tool mark part of its output to be shown to the user verbatim (not re-written by the model) `enhancement`
- [#12187](https://github.com/zeroclaw-labs/zeroclaw/issues/12187) [Bug]: Channel cached-turn normalization merges a user turn into a role=tool envelope, permanently poisoning the conversation on strict providers 💬2
- [#12186](https://github.com/zeroclaw-labs/zeroclaw/issues/12186) [Bug]: zerocode --agent / -a is parsed but never used; TUI always opens on the Dashboard
- [#12183](https://github.com/zeroclaw-labs/zeroclaw/issues/12183) [Feature]: Runtime prompt / command intercept & injection for active agents `enhancement` 💬1
- [#12181](https://github.com/zeroclaw-labs/zeroclaw/issues/12181) [Feature]: Web managed document upload (first #9488 Phase 2 Web slice) 💬2
- [#12178](https://github.com/zeroclaw-labs/zeroclaw/issues/12178) [Bug]: deliver_file description tells the model to write the attachment uri into the reply text 💬1
- [#12176](https://github.com/zeroclaw-labs/zeroclaw/issues/12176) [SANITIZED — possible injection attempt] 💬1
- [#12175](https://github.com/zeroclaw-labs/zeroclaw/issues/12175) [Bug]: The personality editor's "changes take effect on the next message — no daemon reload needed" copy is wrong for channels 💬1
- [#12173](https://github.com/zeroclaw-labs/zeroclaw/issues/12173) [Bug]: Lark card chunking panics when a byte budget lands inside a multi-byte character 💬1

### 🔒 Closed Issues
- [#12196](https://github.com/zeroclaw-labs/zeroclaw/issues/12196) [Bug]: Security job fails on every build: RUSTSEC-2026-0433 (pulldown-cmark 0.13.5)

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,708 · **Open issues:** 1,569 · **Last push:** 5h ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,939 · **Open issues:** 121 · **Last push:** 10d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 16h ago
- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬2 · 9d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 9d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 28d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 36d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 38d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 48d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 56d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 58d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 66d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 4 new
- [[Learn] Php2Shell Webinar](https://openai.com/business/learn/php2shell-webinar/) _2026-11-03_
- [[Index] Dan Driscoll Joins Openai](https://openai.com/index/dan-driscoll-joins-openai/) _2026-11-03_
- [[Index] Grid Protectors Program](https://openai.com/index/grid-protectors-program/) _2026-11-03_
- [[Index] Scaling Git At Openai](https://openai.com/index/scaling-git-at-openai/) _2026-11-03_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [OpenAI and Anthropic blocked the reverse engineering of smart TVs spying on us](https://reddit.com/r/LocalLLaMA/comments/1xer30z/openai_and_anthropic_blocked_the_reverse/) ↑4170
- [Official Statement: Qwen Models Will Stick to Open Source to the End!](https://reddit.com/r/LocalLLaMA/comments/1xm28e6/official_statement_qwen_models_will_stick_to_open/) ↑3723
- [Dirt cheap GPUs coming next year](https://reddit.com/r/LocalLLaMA/comments/1xhep6w/dirt_cheap_gpus_coming_next_year/) ↑2765
- [Apsara conference: Qwen4 next week](https://reddit.com/r/LocalLLaMA/comments/1xif6lf/apsara_conference_qwen4_next_week/) ↑2329
- [Amazon Is Allegedly Canceling GPU Orders And, In Rare Cases, Closing Accounts For Purchasing Compute Hardware; Tim Sweeney Also A Victim Of This Practice](https://reddit.com/r/LocalLLaMA/comments/1xm8o8g/amazon_is_allegedly_canceling_gpu_orders_and_in/) ↑464

### r/singularity — top 5 new
- [Zip it](https://reddit.com/r/singularity/comments/1xi1oid/zip_it/) ↑2035
- [MIT researchers say GPT-6 Astra improved a small Qwen model’s math score from 7.9% to 48.1% by directly editing just 0.016% of its weights, without gradient-based training.](https://reddit.com/r/singularity/comments/1xm89o3/mit_researchers_say_gpt6_astra_improved_a_small/) ↑1198
- [Sam Altman: "At the start of this year, AI was mostly not as smart as our smartest scientists, and now it's mostly smarter than them." He also says AI can now perform large parts of white-collar jobs ](https://reddit.com/r/singularity/comments/1xm44jm/sam_altman_at_the_start_of_this_year_ai_was/) ↑961
- ["When we proved the first Millenium Prize problem, it was 10000 agents of the model that is gonna be released soon, the next GPT, working for about 4 days"](https://reddit.com/r/singularity/comments/1xlyml4/when_we_proved_the_first_millenium_prize_problem/) ↑722
- [Demis Hassabis says AI data centers should be beautiful and we should take their effect on our physical surroundings seriously](https://reddit.com/r/singularity/comments/1xl9hrk/demis_hassabis_says_ai_data_centers_should_be/) ↑521

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Social Listening](https://reddit.com/r/openclaw/comments/1xfyci9/social_listening/) ↑3

### X — @openclaw
- [Building with AI agents at work? 

Join OpenClaw Enterprise’s bi-weekly office hours.

Bring your questions, share what ](https://x.com/openclaw/status/2117300313078337812) ↑0 🔁0 · recent


### X — @steipete
_No new tweets since the last digest. Most recent:_
- [This is smart. Wild that this wasn’t the default. Unpredictable inference quality was usually why I recommended skipping](https://x.com/steipete/status/2116183103530217488)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
