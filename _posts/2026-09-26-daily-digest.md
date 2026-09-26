---
layout: post
title: "Ecosystem Digest — 2026-09-26"
date: 2026-09-26 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-26
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 390,523 | 4 | 6 | 10 | 0 |
| **hermesagent** | 248,991 | 15 | 4 | 10 | 0 |
| **ZeroClaw** | 32,884 | 15 | 10 | 10 | 0 |
| **IronClaw** | 12,633 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,873 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 390,523 · **Open issues:** 8,671 · **Last push:** <1h ago

### ✅ Merged PRs
- [#158472](https://github.com/openclaw/openclaw/pull/158472) fix(codex): preserve memory instructions with Desktop Computer Use
- [#158313](https://github.com/openclaw/openclaw/pull/158313) refactor: share filesystem admission and cleanup with fs-safe
- [#158504](https://github.com/openclaw/openclaw/pull/158504) fix(gateway): close failed connects after client registration
- [#148154](https://github.com/openclaw/openclaw/pull/148154) chore(channels): cover thread binding duration text boundaries
- [#158549](https://github.com/openclaw/openclaw/pull/158549) fix(diagnostics): identify waiting and failed lane tasks
- [#158538](https://github.com/openclaw/openclaw/pull/158538) refactor(test): separate interrupted replay fixtures
- [#158503](https://github.com/openclaw/openclaw/pull/158503) perf(streaming): scan SSE frames incrementally and accept CR framing
- [#158508](https://github.com/openclaw/openclaw/pull/158508) fix(e2e): skip redaction startup for empty logs
- [#158401](https://github.com/openclaw/openclaw/pull/158401) fix: session creation fails through directory aliases
- [#154868](https://github.com/openclaw/openclaw/pull/154868) fix: faulty compaction probe wedges run steering and restart aborts

### 🐛 New Issues
- [#158556](https://github.com/openclaw/openclaw/issues/158556) [Feature]: Let operators disable client file and image uploads `enhancement` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:linked-pr-open` `impact:security` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#158550](https://github.com/openclaw/openclaw/issues/158550) Plugin approval requests fail permanently after the first CLI-turn client disconnects (claude-cli backend, MCP loopback) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-security-review` `clawsweeper:needs-info` `impact:security` `issue-rating: 🦐 gold shrimp` `impact:ux-friction` 💬1
- [#158541](https://github.com/openclaw/openclaw/issues/158541) [Feature]: Android Settings — compact Providers and models with per-provider sign-in `enhancement` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1
- [#158540](https://github.com/openclaw/openclaw/issues/158540) [Feature]: Native Wayland Quick Chat shortcuts `enhancement` `P2` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#156841](https://github.com/openclaw/openclaw/issues/156841) [Bug]: Android effort gauge stops reflecting Effort when Fast mode is on
- [#158566](https://github.com/openclaw/openclaw/issues/158566) Native CLI tool approvals fail with '/description: must not have more than 512 characters' for long Bash commands and Write/Edit
- [#154700](https://github.com/openclaw/openclaw/issues/154700) [Bug]: Run steering crashes when isCompacting() throws instead of failing closed
- [#158557](https://github.com/openclaw/openclaw/issues/158557) Legacy subagent registry rows with a failed delivery keep replaying and cannot be dismissed
- [#158351](https://github.com/openclaw/openclaw/issues/158351) Session SQLite migration recovery report (session-sqlite-1790369664564-117e401f)
- [#144392](https://github.com/openclaw/openclaw/issues/144392) cli-backend silently drops session history when resume aborts (falls back to useResume=false with no warning)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 248,991 · **Open issues:** 43,395 · **Last push:** <1h ago

### ✅ Merged PRs
- [#123271](https://github.com/NousResearch/hermes-agent/pull/123271) fix(gateway): a silence marker on a Slack message not addressed to the bot stays silent; addressed ones still get the notice (salvage #122752)
- [#122633](https://github.com/NousResearch/hermes-agent/pull/122633) Claude Opus 5.5 shows in the Anthropic and Bedrock pickers; Bedrock Opus 5/5.5 get 1M context (salvage #119444, #75824)
- [#122550](https://github.com/NousResearch/hermes-agent/pull/122550) fix(gateway): secondary-profile bots authorize button taps against their own allowlist (#120639, salvage #120642)
- [#121635](https://github.com/NousResearch/hermes-agent/pull/121635) fix(update): stop reading gateway identity off the Windows restart watcher's argv (#107002)
- [#123020](https://github.com/NousResearch/hermes-agent/pull/123020) fix(skins): carry customCSS end-to-end so user CSS survives desktop updates
- [#122899](https://github.com/NousResearch/hermes-agent/pull/122899) fix(desktop): stop approval.respond timing out behind stalled WS writes
- [#122912](https://github.com/NousResearch/hermes-agent/pull/122912) fix(desktop): trust macOS keychain CAs for remote gateways like Windows
- [#122859](https://github.com/NousResearch/hermes-agent/pull/122859) fix(desktop): deliver /background results to the originating conversation
- [#121453](https://github.com/NousResearch/hermes-agent/pull/121453) A hung-provider turn no longer trips the stale breaker for the next turn on a busy host (fixes provider_hang liveness flake)
- [#122483](https://github.com/NousResearch/hermes-agent/pull/122483) fix(update): stop showing 'managed outside dashboard' as a copyable shell command

### 🐛 New Issues
- [#123347](https://github.com/NousResearch/hermes-agent/issues/123347) Group Chat hosted-room worker startup: _frozen_importlib._DeadlockError via run_startup → tui_gateway.server import chain
- [#123346](https://github.com/NousResearch/hermes-agent/issues/123346) hermes update mis-detects orphan divergence after a --depth pre-fetch and force-resets the branch
- [#123345](https://github.com/NousResearch/hermes-agent/issues/123345) terminal tool: notify=true (boolean) rejected by validator — 'notify must be true/false'
- [#123344](https://github.com/NousResearch/hermes-agent/issues/123344) Secondary managed environment staged without install-stamp.json → persistent version 'vunknown' (pm repair/install don't heal)
- [#123343](https://github.com/NousResearch/hermes-agent/issues/123343) Dependency pin httpx2==2.7.0 / httpcore2 2.7.0 hits six published CVEs (PYSEC-2026-3844..3849)
- [#123341](https://github.com/NousResearch/hermes-agent/issues/123341) To Hermes keychoice
- [#123340](https://github.com/NousResearch/hermes-agent/issues/123340) systemd gateway re-runs source-completion tail on every start; installs/<hash>/environments grows to tens of GB / ENOSPC
- [#123339](https://github.com/NousResearch/hermes-agent/issues/123339) [Bug]: Desktop Force Reload shows the provider picker on a configured remote backend and drops the open session
- [#123338](https://github.com/NousResearch/hermes-agent/issues/123338) [Feature]: Desktop: edit a project's description (and icon/color) after creation
- [#123337](https://github.com/NousResearch/hermes-agent/issues/123337) [Bug]: Desktop rename succeeds but project-scoped and forked session rows stay stale until profile switch `type/bug` `P3` `sweeper:risk-session-state` `comp/desktop` `area/sessions`
- [#123333](https://github.com/NousResearch/hermes-agent/issues/123333) Windows terminal PATH: node's bundled npm shadows the pm store npm (EBADENGINE with engine-strict) `type/bug` `comp/cli` `tool/terminal` `backend/local` `P2` `sweeper:risk-compatibility` `sweeper:risk-platform-windows` `platform/windows` `area/install-update`
- [#123327](https://github.com/NousResearch/hermes-agent/issues/123327) Webhook server rejects every connection: setsockopt SO_KEEPALIVE invalid argument (errno 22) on macOS `type/bug` `comp/gateway` `platform/webhook` `P2` `sweeper:risk-message-delivery`
- [#123325](https://github.com/NousResearch/hermes-agent/issues/123325) Hub skill replacement deletes the installed version before transfer and hashing succeed `type/bug` `comp/cli` `tool/skills` `P2`
- [#123324](https://github.com/NousResearch/hermes-agent/issues/123324) fix(update): macOS source update aborts on Git partial-clone assertion `type/bug` `comp/cli` `P2` `sweeper:risk-compatibility` `area/install-update` 💬1
- [#123322](https://github.com/NousResearch/hermes-agent/issues/123322) [Bug]: hermes sessions repair / optimize / optimize-storage / archive exit 0 when they fail `type/bug` `comp/cli` `P2` `sweeper:risk-session-state` `area/sessions`

### 🔒 Closed Issues
- [#122424](https://github.com/NousResearch/hermes-agent/issues/122424) package.json pins js-yaml@4.3.1 / yaml<2.9 to known CVE ranges (GHSA-2883-xcg3-v3hh, GHSA-48c2-rrv3-qjmp)
- [#122736](https://github.com/NousResearch/hermes-agent/issues/122736) [Windows] Gateway on the managed store Python (3.14) overlays the in-tree 3.11 venv site-packages → hosted_room_worker dies on pydantic_core ABI mismatch
- [#74263](https://github.com/NousResearch/hermes-agent/issues/74263) [Bug] BEDROCK_CONTEXT_LENGTHS has no Claude 5 entries — sonnet-5/opus-5 resolve to the 128K catch-all, compressor compacts 8x too early
- [#120639](https://github.com/NousResearch/hermes-agent/issues/120639) [Bug]: Telegram inline callbacks refuse allowlisted user when a secondary profile owns its own bot under multiplex (callback auth runs outside profile secret scope)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,884 · **Open issues:** 749 · **Last push:** 1h ago

### ✅ Merged PRs
- [#9986](https://github.com/zeroclaw-labs/zeroclaw/pull/9986) feat(agents): export an agent to a portable bundle
- [#10259](https://github.com/zeroclaw-labs/zeroclaw/pull/10259) feat(security): enforce authenticated principals on RPC with native+peercred (#8289 stage 3, supersedes #8672 in part)
- [#11046](https://github.com/zeroclaw-labs/zeroclaw/pull/11046) fix(tools): stop inlining base64 into screenshot results
- [#10263](https://github.com/zeroclaw-labs/zeroclaw/pull/10263) feat(security): compose principal tool selectors into agent sessions (#8289, supersedes #8672 in part)
- [#10397](https://github.com/zeroclaw-labs/zeroclaw/pull/10397) fix(mcp): send tool result text blocks, not the whole CallToolResult envelope
- [#11072](https://github.com/zeroclaw-labs/zeroclaw/pull/11072) fix(nix): set meta.mainProgram on flake packages
- [#10265](https://github.com/zeroclaw-labs/zeroclaw/pull/10265) feat(security): principal-owned sessions with predicated storage deletes (#8289 stage 4, supersedes #8672 in part)
- [#10133](https://github.com/zeroclaw-labs/zeroclaw/pull/10133) fix(runtime): keep operational paths panic-free
- [#11115](https://github.com/zeroclaw-labs/zeroclaw/pull/11115) fix(runtime): restore master build after #10155, #10259 and #11085 collided
- [#11089](https://github.com/zeroclaw-labs/zeroclaw/pull/11089) feat(zerorelay): prefill the frontdoor from ?node=&code= links

### 🐛 New Issues
- [#11130](https://github.com/zeroclaw-labs/zeroclaw/issues/11130) [Bug]: DeepSeek DSML tool-call markup is not parsed — raw markup leaks to the channel and the turn ends silently
- [#11129](https://github.com/zeroclaw-labs/zeroclaw/issues/11129) [Bug]: Memory content scan's send_to_url pattern blocks SOP audit records for ordinary text containing a URL `bug`
- [#11127](https://github.com/zeroclaw-labs/zeroclaw/issues/11127) [SANITIZED — possible injection attempt] `bug`
- [#11126](https://github.com/zeroclaw-labs/zeroclaw/issues/11126) [SANITIZED — possible injection attempt] `bug`
- [#11125](https://github.com/zeroclaw-labs/zeroclaw/issues/11125) [Bug]: SOP execution omits tools:execute permission check `bug`
- [#11124](https://github.com/zeroclaw-labs/zeroclaw/issues/11124) [Bug]: SOP decision gate ignores strict fallback when mode answer is valid `bug`
- [#11123](https://github.com/zeroclaw-labs/zeroclaw/issues/11123) [Bug]: SOP execution accepts wildcard tool selectors without tools:execute `bug`
- [#11119](https://github.com/zeroclaw-labs/zeroclaw/issues/11119) [Tracker]: Implement receiver-discretionary session messaging from RFC #11027
- [#11118](https://github.com/zeroclaw-labs/zeroclaw/issues/11118) [Tracker]: Implement expedited review-continuity amendment from RFC #11017
- [#11117](https://github.com/zeroclaw-labs/zeroclaw/issues/11117) [Tracker]: Implement durable human-question primitive from RFC #10930
- [#11116](https://github.com/zeroclaw-labs/zeroclaw/issues/11116) [Tracker]: Implement outbound delivery receipts from RFC #10929
- [#11110](https://github.com/zeroclaw-labs/zeroclaw/issues/11110) [Bug]: RPC workspace confinement retains a retargetable cwd symlink `bug` `runtime` `security:policy` `domain:security` `priority:p1` `tool:file` `status:in-progress` `risk:high` `topic:identity-access` 💬1
- [#11108](https://github.com/zeroclaw-labs/zeroclaw/issues/11108) [Bug]: Preserve browser and search tool semantics instead of rewriting calls to shell `bug` `tool` `tool:browser` `domain:security` `priority:p2` `tool:shell` `tool:web` `needs-maintainer-review` `risk:high` 💬1
- [#11103](https://github.com/zeroclaw-labs/zeroclaw/issues/11103) feat(providers): add Cheaper Inference as a typed OpenAI-compatible provider `enhancement` `docs` `config` `provider` `provider:compatible` `priority:p2` `status:in-progress` `needs-maintainer-review` `risk:medium` 💬2
- [#11100](https://github.com/zeroclaw-labs/zeroclaw/issues/11100) [Feature]: Preserve configured provider aliases in cost-rate catalog prefill `enhancement` `config` `gateway` `provider` `runtime` `provider:openai` `provider:compatible` `priority:p2` `follow-up` `web` `zerocode` `risk:high` 💬1

### 🔒 Closed Issues
- [#10394](https://github.com/zeroclaw-labs/zeroclaw/issues/10394) MCP tool results are stored as the whole CallToolResult envelope, duplicating every payload
- [#11096](https://github.com/zeroclaw-labs/zeroclaw/issues/11096) RFC: Risk-based merge-result freshness
- [#11027](https://github.com/zeroclaw-labs/zeroclaw/issues/11027) RFC: Agent-to-agent session messaging with receiver discretion
- [#11017](https://github.com/zeroclaw-labs/zeroclaw/issues/11017) RFC: Preserve applicable reviews and simplify expedited merge decisions
- [#10930](https://github.com/zeroclaw-labs/zeroclaw/issues/10930) RFC: One durable primitive for questions an agent asks a human
- [#10929](https://github.com/zeroclaw-labs/zeroclaw/issues/10929) RFC: Delivery receipts for outbound messages
- [#8431](https://github.com/zeroclaw-labs/zeroclaw/issues/8431) [Tracker]: audit temporary artifact lifecycle and owner-side cleanup
- [#8586](https://github.com/zeroclaw-labs/zeroclaw/issues/8586) refactor(gateway): centralize webhook channel message dispatch
- [#6864](https://github.com/zeroclaw-labs/zeroclaw/issues/6864) [Feature]: Invert zeroclaw-channels → zeroclaw-runtime layer dependency and move orchestrator into runtime
- [#10805](https://github.com/zeroclaw-labs/zeroclaw/issues/10805) [Bug]: control_plane liveness tests race process teardown on Windows (Advisory Windows nextest)

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,633 · **Open issues:** 1,531 · **Last push:** 23h ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,873 · **Open issues:** 95 · **Last push:** 3d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 22h ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 3d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 10d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 18d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 20d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 28d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 32d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 44d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 47d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 50d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Research] Yes Claude Can Do Nine Loops](https://www.anthropic.com/research/yes-claude-can-do-nine-loops) _2026-09-25_

### OpenAI — 1 new
- [[Index] Proaction](https://openai.com/index/proaction/) _2026-09-25_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Qwengram-0.8B: I transferred Qwen3.8 Flash-Next’s n-gram memory into Qwen3.5-0.8B — 5.05% lower validation perplexity](https://reddit.com/r/LocalLLaMA/comments/1wpvep4/qwengram08b_i_transferred_qwen38_flashnexts_ngram/) ↑315
- [Swift1.5-Qwen3.8-Flash-Next is phenomenal vs. base 3.8-Flash!](https://reddit.com/r/LocalLLaMA/comments/1wq56pf/swift15qwen38flashnext_is_phenomenal_vs_base/) ↑168
- [I ran the actual break-even math on buying vs renting an H200 box, and it is not where I expected](https://reddit.com/r/LocalLLaMA/comments/1wq672b/i_ran_the_actual_breakeven_math_on_buying_vs/) ↑134
- [Jev vs. Kev: open-source Jev alternative tested side by side](https://reddit.com/r/LocalLLaMA/comments/1wq2hfc/jev_vs_kev_opensource_jev_alternative_tested_side/) ↑80
- [Mica v0.1 4B got an iron pickaxe in real Minecraft without generating a single token](https://reddit.com/r/LocalLLaMA/comments/1wqahbz/mica_v01_4b_got_an_iron_pickaxe_in_real_minecraft/) ↑64

### r/singularity — top 2 new
- [In just 100 days, AI crossed into real medical work. 37,000 agents searched 55,000 trials for new treatments, an AI-designed pulmonary fibrosis drug entered Phase III, and an autonomous medical agent ](https://reddit.com/r/singularity/comments/1wq52am/in_just_100_days_ai_crossed_into_real_medical/) ↑861
- [Opus 5.5 cut out em dashes almost entirely](https://reddit.com/r/singularity/comments/1wq9wtj/opus_55_cut_out_em_dashes_almost_entirely/) ↑575

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [QWEN3.6-27B-MLX-8bit (29.5GIG) Is Excellent](https://reddit.com/r/openclaw/comments/1wpnva4/qwen3627bmlx8bit_295gig_is_excellent/) ↑20
- [OpenClaw 2026.9.6 broke all my cron jobs](https://reddit.com/r/openclaw/comments/1wpw4x1/openclaw_202696_broke_all_my_cron_jobs/) ↑18
- [Meta admits its new Muse AI was heavily inspired by OpenClaw 👀](https://reddit.com/r/openclaw/comments/1wq2smx/meta_admits_its_new_muse_ai_was_heavily_inspired/) ↑12
- [The worst model I've seen in a while.](https://reddit.com/r/openclaw/comments/1wplg9n/the_worst_model_ive_seen_in_a_while/) ↑8
- [Model/agent hierarchy](https://reddit.com/r/openclaw/comments/1wptcr0/modelagent_hierarchy/) ↑7

### X — @openclaw
- [Two Mac minis up for grabs!!!

Sign up now and submit your entry by Sept 28:

https://
luma.com/zhkhsnpa](https://x.com/openclaw/status/2103651326752371010) ↑0 🔁0 · recent
- [Also checkout the 
@aiworthusing
 podcast episode with 
@steipete](https://x.com/openclaw/status/2103651559645364505) ↑0 🔁0 · recent
- [Sometimes you need to let your session cook

That's why 
@Pat_Erichsen
 recently updated how plugins load in OpenClaw al](https://x.com/openclaw/status/2103619712945123383) ↑0 🔁0 · recent


### X — @steipete
- [keep thinking](https://x.com/steipete/status/2103654562523705675) ↑0 🔁0 · recent
- [The biggest design mistake I made when we moved OC to sqlite: using sync db access. When it was just an agent that repor](https://x.com/steipete/status/2103648679169257737) ↑0 🔁0 · recent
- [day of the dead](https://x.com/steipete/status/2103615459426001163) ↑0 🔁0 · recent
- [That sounds 100% like the OC hype cycle we had 8 months ago.

Biggest limitation isn’t the tech, it’s imagination and cr](https://x.com/steipete/status/2103580623239827941) ↑0 🔁0 · recent
- [Microsoft shipped a really compelling product on top of 
@OpenClaw
 today. We worked with them since March to make the c](https://x.com/steipete/status/2103491173927272531) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
