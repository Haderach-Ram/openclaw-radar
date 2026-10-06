---
layout: post
title: "Ecosystem Digest — 2026-10-06"
date: 2026-10-06 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-06
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 391,450 | 10 | 6 | 10 | 1 |
| **hermesagent** | 251,463 | 11 | 4 | 10 | 0 |
| **ZeroClaw** | 32,936 | 14 | 2 | 9 | 0 |
| **IronClaw** | 12,638 | 2 | 0 | 0 | 0 |
| **Moltis** | 2,884 | 2 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 391,450 · **Open issues:** 9,424 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.10.1-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.10.1-beta.1) — openclaw 2026.10.1-beta.1

### ✅ Merged PRs
- [#165870](https://github.com/openclaw/openclaw/pull/165870) fix: Gemini turn fails instead of retrying when the stream is cut mid-frame
- [#165854](https://github.com/openclaw/openclaw/pull/165854) fix: doctor updates recover archives without leaving gateways stopped
- [#165773](https://github.com/openclaw/openclaw/pull/165773) refactor(routing): remove redundant route-target guards
- [#165608](https://github.com/openclaw/openclaw/pull/165608) perf(gateway): acknowledge chat sends before skill preparation
- [#165896](https://github.com/openclaw/openclaw/pull/165896) perf(workboard): speed up sessions board revision reads
- [#165897](https://github.com/openclaw/openclaw/pull/165897) perf(chat): bound history pages and reuse recovery cursors
- [#165644](https://github.com/openclaw/openclaw/pull/165644) perf(auth): move auth saves to workers and publish incrementally
- [#165803](https://github.com/openclaw/openclaw/pull/165803) perf(gateway): keep deferred database opens off readiness
- [#165891](https://github.com/openclaw/openclaw/pull/165891) test(state): deduplicate admission test routing
- [#165833](https://github.com/openclaw/openclaw/pull/165833) refactor(runtime): deslop runtime

### 🐛 New Issues
- [#165903](https://github.com/openclaw/openclaw/issues/165903) [Bug]: Manual heartbeat run transcript is unavailable in Automations viewer `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬3
- [#165899](https://github.com/openclaw/openclaw/issues/165899) Feature: select an exact package release through update.run `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:other` 💬1
- [#165892](https://github.com/openclaw/openclaw/issues/165892) [Bug]: WebChat collapses \n\n in long assistant replies (non-directive boundary) — revival of #20410, follow-up to #146330 `P2` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#165888](https://github.com/openclaw/openclaw/issues/165888) Live provider catalog failures lose safe diagnostic causes `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#165884](https://github.com/openclaw/openclaw/issues/165884) [Bug]: 2026.9.8 gateway fails startup in sessions.projection with shared-state reader error `bug` `regression` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:crash-loop` `P0` `issue-rating: 🦐 gold shrimp` `maturity:stable` 💬1
- [#165875](https://github.com/openclaw/openclaw/issues/165875) Update failure: verifying (2026.9.7) `clawsweeper:needs-info` `P0` `issue-rating: 🦪 silver shellfish` `impact:ux-release-blocker` 💬1
- [#165874](https://github.com/openclaw/openclaw/issues/165874) [Bug]: Browser plugin's Playwright connection never releases tabs closed in Chrome (iframe-heavy pages stay "open"), leaking ~2.3 MB of Gateway heap per tab `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#165869](https://github.com/openclaw/openclaw/issues/165869) Updater retention temporarily invalidates checkout plugin skills `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `maturity:stable` 💬2
- [#165868](https://github.com/openclaw/openclaw/issues/165868) Update failure: global-install-failed (2026.9.4) `clawsweeper:needs-info` `P0` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-release-blocker` 💬1
- [#165865](https://github.com/openclaw/openclaw/issues/165865) Systems: reduce finished-worker clutter and identify runs by task/start time `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#145079](https://github.com/openclaw/openclaw/issues/145079) [Bug]: Gemini and Vertex AI turns fail with "Google SSE stream ended with an incomplete frame" instead of retrying when the stream is cut mid-event
- [#161734](https://github.com/openclaw/openclaw/issues/161734) [Bug]: Doctor archive migration repeats expensive admission checks in two transactions per unchanged archive
- [#165893](https://github.com/openclaw/openclaw/issues/165893) [Bug]: Codex model requests fall back to Ollama when global Codex plugin is untrusted
- [#158095](https://github.com/openclaw/openclaw/issues/158095) [Bug]: A gateway worker keeps state-lifecycle after acquireSqliteWorkerLifecycle; every later acquire fails until restart
- [#161953](https://github.com/openclaw/openclaw/issues/161953) [Bug]: Windows: sessions.create always fails with "Session creation publication owner is no longer current" on 2026.9.7 (win32 \\?\ SQLite path leaks into the creation-publication guard)
- [#132888](https://github.com/openclaw/openclaw/issues/132888) Exec approval from a non-native approval channel is auto-cancelled (run-aborted) when the turn ends, so `/approve` can never succeed

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 251,463 · **Open issues:** 48,061 · **Last push:** <1h ago

### ✅ Merged PRs
- [#133598](https://github.com/NousResearch/hermes-agent/pull/133598) fix(gateway): voice turns drop the /voice join message id and name uncached speakers
- [#133469](https://github.com/NousResearch/hermes-agent/pull/133469) fix(gateway): a thread's own channel skill binding wins over its parent's in any config order
- [#133478](https://github.com/NousResearch/hermes-agent/pull/133478) fix(discord): a role-authorized member's speech, native slash commands and /thread starters reach the agent
- [#133562](https://github.com/NousResearch/hermes-agent/pull/133562) feat(plugins): let plugins register Automation Blueprints via ctx
- [#133567](https://github.com/NousResearch/hermes-agent/pull/133567) Treeless installs convert before the update's dependency steps and on installer re-runs (#129514, salvage #132428)
- [#133566](https://github.com/NousResearch/hermes-agent/pull/133566) feat(plugins): plugin aux slots inherit a built-in slot and show up in Dashboard/Desktop aux settings
- [#133556](https://github.com/NousResearch/hermes-agent/pull/133556) Computer use: plugins can ship the one active driver (computer_use.backend)
- [#133563](https://github.com/NousResearch/hermes-agent/pull/133563) feat(plugins): inject_message(origin=...) starts a gateway session in the plugin's own profile
- [#133552](https://github.com/NousResearch/hermes-agent/pull/133552) feat(browser): public CDP call seam for trusted plugins (salvage #132752)
- [#133471](https://github.com/NousResearch/hermes-agent/pull/133471) fix(discord): an utterance transcribed across a /voice join rebind is not posted to the new channel

### 🐛 New Issues
- [#133620](https://github.com/NousResearch/hermes-agent/issues/133620) [Bug] [Human-Written]: When switching profiles, sidebar state gets wonky `bug`
- [#133616](https://github.com/NousResearch/hermes-agent/issues/133616) [Bug]: standalone MCP probes do not load enabled plugin secret sources `type/bug` `comp/cli` `comp/plugins` `tool/mcp` `area/auth` `P3` `sweeper:risk-security-boundary`
- [#133612](https://github.com/NousResearch/hermes-agent/issues/133612) [Feature]: show model price and sale discount in the model submenu instead of on every row `type/feature` `P3` `comp/desktop` `area/usage-cost`
- [#133608](https://github.com/NousResearch/hermes-agent/issues/133608) [Bug]: Desktop composer-images is never cleaned up — survives session delete, all sweeps, and most uninstalls `type/bug` `tool/vision` `P2` `sweeper:risk-session-state` `comp/desktop` `area/sessions` 💬1
- [#133606](https://github.com/NousResearch/hermes-agent/issues/133606) [SANITIZED — possible injection attempt] `type/bug` `comp/agent` `provider/openai` `area/config` `P2` `sweeper:risk-compatibility`
- [#133603](https://github.com/NousResearch/hermes-agent/issues/133603) background_review fork still fires pre_tool_call/post_tool_call under the parent session_id (follow-up to #107062) `type/bug` `comp/agent` `comp/plugins` `P3`
- [#133602](https://github.com/NousResearch/hermes-agent/issues/133602) [Bug]: LSP typescript diagnostics always time out: first publishDiagnostics after didOpen is discarded as seed `type/bug` `comp/agent` `P2` `comp/lsp`
- [#133601](https://github.com/NousResearch/hermes-agent/issues/133601) [Feature]: expose local Desktop/CLI sessions through `hermes mcp serve` for read-only supervision `type/feature` `comp/cli` `tool/mcp` `P3` `comp/desktop` `area/sessions`
- [#133596](https://github.com/NousResearch/hermes-agent/issues/133596) [Bug]: computer_use screenshots embedded with no size cap; Claude DirectSDK 'Image base64 size exceeds API limit' evades image-shrink recovery `type/bug` `comp/tools` `tool/vision` `provider/anthropic` `P2` `area/sessions`
- [#133595](https://github.com/NousResearch/hermes-agent/issues/133595) zai provider: glm-5.3-flash rejects reasoning_effort=medium on the standard endpoint (HTTP 400 / code 1210) `type/bug` `comp/agent` `comp/plugins` `provider/zai` `P3`
- [#133587](https://github.com/NousResearch/hermes-agent/issues/133587) [Bug]: Built-in adapter construction failure prevents healthy gateway platforms from starting `type/bug` `comp/gateway` `platform/webhook` `P2` `sweeper:risk-message-delivery`

### 🔒 Closed Issues
- [#133554](https://github.com/NousResearch/hermes-agent/issues/133554) [Bug]: Cannot select an OpenAI model after Copilot fallback has been used
- [#130302](https://github.com/NousResearch/hermes-agent/issues/130302) [Bug]: Discord voice-channel speech from a role-authorized member never reaches the agent (voice source drops role_authorized)
- [#118958](https://github.com/NousResearch/hermes-agent/issues/118958) [Bug]: Discord slash commands from role-authorized users are rejected by the gateway (slash event never carries role_authorized)
- [#132373](https://github.com/NousResearch/hermes-agent/issues/132373) Let profiles (and plugins) register their own Automation Blueprints

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,936 · **Open issues:** 932 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11533](https://github.com/zeroclaw-labs/zeroclaw/pull/11533) test(runtime): isolate bootstrap WARN capture in parallel tests
- [#11493](https://github.com/zeroclaw-labs/zeroclaw/pull/11493) fix(zerocode): drain past unrelated notifications
- [#11437](https://github.com/zeroclaw-labs/zeroclaw/pull/11437) fix(ci): give Alpine ARM64 Docker builds more memory
- [#11444](https://github.com/zeroclaw-labs/zeroclaw/pull/11444) ci(windows): avoid optimizing the service smoke fixture
- [#10522](https://github.com/zeroclaw-labs/zeroclaw/pull/10522) test(rpc): enforce SOP manual-run step scope
- [#10967](https://github.com/zeroclaw-labs/zeroclaw/pull/10967) test(runtime): make the trim log capture failure self-diagnosing
- [#11330](https://github.com/zeroclaw-labs/zeroclaw/pull/11330) fix(rpc): fence session/configure on the authorized incarnation
- [#11111](https://github.com/zeroclaw-labs/zeroclaw/pull/11111) docs(runtime): propose bounded SOP RPC placement exception
- [#10504](https://github.com/zeroclaw-labs/zeroclaw/pull/10504) refactor(turn): typed stop taxonomy for turn-path aborts

### 🐛 New Issues
- [#11554](https://github.com/zeroclaw-labs/zeroclaw/issues/11554) [Bug]: Earlier path-marker images are re-sent on every later turn, so the model describes phantom "new" images
- [#11553](https://github.com/zeroclaw-labs/zeroclaw/issues/11553) [Feature]: Merge split inbound messages reliably (per-channel debounce and attachment-preserving batches)
- [#11552](https://github.com/zeroclaw-labs/zeroclaw/issues/11552) [Bug]: the tool egress ceremony ignores websocket_client and socket_client declarations `bug` `cli` `topic:plugins`
- [#11551](https://github.com/zeroclaw-labs/zeroclaw/issues/11551) [Feature]: Define composable child-SOP nodes for visual authoring `enhancement` `gateway` `runtime` `web` `topic:sop` `status:icebox` `topic:operator-ux`
- [#11550](https://github.com/zeroclaw-labs/zeroclaw/issues/11550) [Feature]: Persist named SOP library groups across clients `enhancement` `gateway` `runtime` `web` `topic:sop` `status:icebox` `topic:operator-ux`
- [#11549](https://github.com/zeroclaw-labs/zeroclaw/issues/11549) [Feature]: Expose reviewable SOP gate payloads and supported decision actions `enhancement` `gateway` `runtime` `web` `topic:sop` `status:icebox` `topic:operator-ux`
- [#11548](https://github.com/zeroclaw-labs/zeroclaw/issues/11548) [Feature]: Add explicit SOP helper authority and opt-in live adaptation `enhancement` `gateway` `runtime` `web` `topic:sop` `status:icebox` `topic:operator-ux`
- [#11547](https://github.com/zeroclaw-labs/zeroclaw/issues/11547) [Feature]: Bind SOP runs to immutable workflow-definition revisions `enhancement` `gateway` `runtime` `topic:sop` `status:icebox` `topic:operator-ux`
- [#11546](https://github.com/zeroclaw-labs/zeroclaw/issues/11546) [Feature]: Bind each SOP to a persistent managing-agent conversation `enhancement` `gateway` `runtime` `web` `topic:sop` `status:icebox` `topic:operator-ux`
- [#11545](https://github.com/zeroclaw-labs/zeroclaw/issues/11545) [Task]: remove obsolete StreamErrorWithUsage after image recovery lands
- [#11540](https://github.com/zeroclaw-labs/zeroclaw/issues/11540) [Bug]: bubblewrap sandbox isn't detected on linux falling back to application-layer `bug`
- [#11539](https://github.com/zeroclaw-labs/zeroclaw/issues/11539) [Bug]: Firejail sandbox fails with Error: Error: invalid --nowheel command line option `bug`
- [#11538](https://github.com/zeroclaw-labs/zeroclaw/issues/11538) [Bug]: Firejail sandbox fails with Error: Error: invalid private directory `bug`
- [#11519](https://github.com/zeroclaw-labs/zeroclaw/issues/11519) [Bug]: resumed workspace split hides installed plugins from recovery `bug` `config` `priority:p1` `status:in-progress` `risk:medium` `release:v0.8.6` `plugins` 💬1

### 🔒 Closed Issues
- [#11482](https://github.com/zeroclaw-labs/zeroclaw/issues/11482) [Bug]: Chat updates wait behind unrelated log notifications
- [#11294](https://github.com/zeroclaw-labs/zeroclaw/issues/11294) [Bug]: Flaky: configure_refuses_an_incarnation_replaced_under_the_lock races its 150 ms sleep under the parallel runtime gate

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,638 · **Open issues:** 1,544 · **Last push:** 1d ago

### 🐛 New Issues
- [#8126](https://github.com/nearai/ironclaw/issues/8126) Daily ironclaw failure taxonomy — 2026-10-05
- [#8124](https://github.com/nearai/ironclaw/issues/8124) WebChat: stale action status and no completion notification in background tabs (silent Web Push gap on non-HTTPS deployments)

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,884 · **Open issues:** 106 · **Last push:** 13d ago

### 🐛 New Issues
- [#1294](https://github.com/moltis-org/moltis/issues/1294) [Feature]: per-sender MCP credentials in shared chats, so group messages are attributed to whoever sent them
- [#1292](https://github.com/moltis-org/moltis/issues/1292) [Bug]: create_skill writes unquoted YAML frontmatter and reports success for a skill discovery can't parse

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 16h ago
- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 2d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 8d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 10d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 20d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 28d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 30d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 38d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 42d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 54d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 1 new
- [[Index] New Chatgpt Ads Format And Measurement](https://openai.com/index/new-chatgpt-ads-format-and-measurement/) _2026-10-05_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [How is it possible that qwen 27b is so good? When GPT 4o had a trillion parameters and was worse?](https://reddit.com/r/LocalLLaMA/comments/1wyefkt/how_is_it_possible_that_qwen_27b_is_so_good_when/) ↑998
- [PewDiePie getting banned twice by OpenAI while making a local model is top-tier comedy 💀](https://reddit.com/r/LocalLLaMA/comments/1wymgu6/pewdiepie_getting_banned_twice_by_openai_while/) ↑852
- [Reflection AI Is About to Release a US Open-Weight Model to Take On DeepSeek and Qwen](https://reddit.com/r/LocalLLaMA/comments/1wy0jrc/reflection_ai_is_about_to_release_a_us_openweight/) ↑333
- [Make no mistake, selling 64 GB DGX Spark variants at the same cost as the original 128 GB is straight drug dealer behavior.](https://reddit.com/r/LocalLLaMA/comments/1wyea30/make_no_mistake_selling_64_gb_dgx_spark_variants/) ↑300
- [When Redditors come in here and ask why we run LLMs, this is why: Big AI is watching.](https://reddit.com/r/LocalLLaMA/comments/1wyjuh0/when_redditors_come_in_here_and_ask_why_we_run/) ↑269

### r/singularity — top 5 new
- [AI Is About to Transform Materials Science](https://reddit.com/r/singularity/comments/1wykgbk/ai_is_about_to_transform_materials_science/) ↑1153
- [A researcher spent 3 months making software for designing quantum circuits ~10,000× faster. GPT-6 Astra took the already-optimized code and made it another ~10× faster overnight](https://reddit.com/r/singularity/comments/1wxxz1n/a_researcher_spent_3_months_making_software_for/) ↑619
- [DeepMind’s new AI designed enzymes from scratch, one made a chemical building block found in many medicines 99× more often than the competing product, while another broke down a plastic pollutant at 9](https://reddit.com/r/singularity/comments/1wyft2i/deepminds_new_ai_designed_enzymes_from_scratch/) ↑492
- [Chat GPT fixed my PC after different technicians over the years couldn't or wouldn't](https://reddit.com/r/singularity/comments/1wy8c0l/chat_gpt_fixed_my_pc_after_different_technicians/) ↑351
- [German lab Aleph Alpha releases Kolibri: a sovereign open-weight model,78B parameters, 3.46B active. Up to 1M tokens of context.](https://reddit.com/r/singularity/comments/1wy5b5g/german_lab_aleph_alpha_releases_kolibri_a/) ↑248

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw voice assistant without losing "Hey Google"?](https://reddit.com/r/openclaw/comments/1wyoayp/openclaw_voice_assistant_without_losing_hey_google/) ↑3
- [On-device language model unavailable](https://reddit.com/r/openclaw/comments/1wyoygd/ondevice_language_model_unavailable/) ↑1

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [OpenClaw v2026.9.8 is out, and this one's a fun-sized lobster 🦞

🧠 GPT-6.1 Sol support
💬 Agent replies find their way ba](https://x.com/openclaw/status/2106247624634531889)

### X — @steipete
_No new tweets since the last digest. Most recent:_
- [bug fixes & performance improvements](https://x.com/steipete/status/2106796559400882209)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
