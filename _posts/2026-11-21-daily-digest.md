---
layout: post
title: "Ecosystem Digest — 2026-11-21"
date: 2026-11-21 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-21
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 394,929 | 11 | 5 | 10 | 0 |
| **hermesagent** | 265,004 | 6 | 6 | 10 | 1 |
| **ZeroClaw** | 33,539 | 9 | 0 | 0 | 0 |
| **IronClaw** | 12,717 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,978 | 1 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 394,929 · **Open issues:** 8,690 · **Last push:** <1h ago

### ✅ Merged PRs
- [#202839](https://github.com/openclaw/openclaw/pull/202839) fix: let subagents inherit registered project folders
- [#202762](https://github.com/openclaw/openclaw/pull/202762) fix: report invalid PostgreSQL vector dimensions in Doctor
- [#202837](https://github.com/openclaw/openclaw/pull/202837) fix: release completed lease callers and keep input tests portable
- [#202838](https://github.com/openclaw/openclaw/pull/202838) feat(plugins): legacy memory runtimes as backends and optional provider store
- [#201519](https://github.com/openclaw/openclaw/pull/201519) fix: keep unused Code Mode lookups from tainting memory
- [#201488](https://github.com/openclaw/openclaw/pull/201488) fix: explain how to call deferred tools after a direct call
- [#201615](https://github.com/openclaw/openclaw/pull/201615) fix: keep invited collaborators from loosening your session's guardrails or approving your commands
- [#202812](https://github.com/openclaw/openclaw/pull/202812) chore(test): remove duplicate chat mention coverage
- [#202654](https://github.com/openclaw/openclaw/pull/202654) feat: prepare restricted connections for Session Share steering
- [#202478](https://github.com/openclaw/openclaw/pull/202478) feat: keep unused Knowledge workers asleep in lean mode

### 🐛 New Issues
- [#202859](https://github.com/openclaw/openclaw/issues/202859) Consolidate iOS speech-language selection ownership
- [#202857](https://github.com/openclaw/openclaw/issues/202857) Use one connection-state input for iOS chat status
- [#202854](https://github.com/openclaw/openclaw/issues/202854) Remove duplicate iOS wake-word matching ownership `clawsweeper:intake:bug` `clawsweeper:intake:needs-repro` 💬1
- [#202853](https://github.com/openclaw/openclaw/issues/202853) [Feature]: Keep a condition script's console output when its evaluation fails `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#202851](https://github.com/openclaw/openclaw/issues/202851) refactor: keep attachment header inspection independent of image encoding `P3` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#202849](https://github.com/openclaw/openclaw/issues/202849) refactor(memory): isolate vector checks from cache persistence `P3` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#202847](https://github.com/openclaw/openclaw/issues/202847) Reuse shared Decision provider integration fixtures `P3` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#202844](https://github.com/openclaw/openclaw/issues/202844) [Feature]: Use one Google music output-format policy for metadata and execution `enhancement` `P3` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#202842](https://github.com/openclaw/openclaw/issues/202842) refactor(tts): isolate automatic-mode schema from core config `P3` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#202830](https://github.com/openclaw/openclaw/issues/202830) Adding a manifest without activation.onStartup silently stops an enabled standalone plugin file from starting with the Gateway `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:security` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#202827](https://github.com/openclaw/openclaw/issues/202827) Test iOS speech segmentation without constructing the Talk manager `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:linked-pr-open` `issue-rating: 🌊 off-meta tidepool` 💬1

### 🔒 Closed Issues
- [#202761](https://github.com/openclaw/openclaw/issues/202761) [Bug]: PostgreSQL vector search DDL renders index dimensions without checking them
- [#196857](https://github.com/openclaw/openclaw/issues/196857) Code Mode catalog search taints the turn with no network call, so memory writes become permanently untrusted
- [#186716](https://github.com/openclaw/openclaw/issues/186716) [Bug]: Tool Search `tools` mode answers a direct call to a deferred tool with a bare "Tool <name> not found"
- [#202378](https://github.com/openclaw/openclaw/issues/202378) Expose the resource profile to plugins; Knowledge lazy start for lean
- [#202366](https://github.com/openclaw/openclaw/issues/202366) Session rejects chat.send with SessionMutationFactsUnavailableError after its SQLite store worker dies mid-write

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬84 · <1h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 265,004 · **Open issues:** 54,168 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.23.3+canary.20261120T064609Z](https://github.com/NousResearch/hermes-agent/releases/tag/v0.23.3%2Bcanary.20261120T064609Z) — Hermes Agent canary v0.23.3+canary.20261120T064609Z

### ✅ Merged PRs
- [#151194](https://github.com/NousResearch/hermes-agent/pull/151194) fix(skills): release a skill_view dedup entry the model only saw as a preview
- [#158350](https://github.com/NousResearch/hermes-agent/pull/158350) fix(release): probe Windows MSIX executableVersion and track canary reds in-run
- [#158056](https://github.com/NousResearch/hermes-agent/pull/158056) fix(mcp): allow opted-in Streamable HTTP tool calls to overlap
- [#158326](https://github.com/NousResearch/hermes-agent/pull/158326) Desktop: new hermes://launch link opens the app and does nothing else
- [#158377](https://github.com/NousResearch/hermes-agent/pull/158377) fix(gateway): a Kanban wake shows in an idle classic CLI chat (salvage #158169)
- [#155300](https://github.com/NousResearch/hermes-agent/pull/155300) fix(cron): end the gateway-admitted session row when a gate suppresses or refuses a fire
- [#155346](https://github.com/NousResearch/hermes-agent/pull/155346) fix(gateway): read startup session-recovery backlogs off the event loop (native + local)
- [#155299](https://github.com/NousResearch/hermes-agent/pull/155299) fix(agent): drop guardrail-removed calls from native replay sidecars
- [#158291](https://github.com/NousResearch/hermes-agent/pull/158291) feat(skills): make the skill-index description width configurable (skills.index_desc_limit)
- [#158184](https://github.com/NousResearch/hermes-agent/pull/158184) fix(desktop): stop the "install WSL" console on Windows without WSL

### 🐛 New Issues
- [#158441](https://github.com/NousResearch/hermes-agent/issues/158441) control socket: 2s hard timeout turns "receipt not yet terminal" into a crashed kanban worker under concurrent load `type/bug` `comp/gateway` `area/config` `P2`
- [#158439](https://github.com/NousResearch/hermes-agent/issues/158439) [Bug]: Ctrl+C landing during the TUI exit summary prints a raw KeyboardInterrupt traceback instead of the resume hint `type/bug` `comp/cli` `P2`
- [#158434](https://github.com/NousResearch/hermes-agent/issues/158434) [Vision] Preserve fine UI/rendering defects: opt-in high-fidelity screenshot mode (2K → 720p, lossy JPEG) `type/feature` `comp/tools` `tool/browser` `tool/vision` `area/config` `P3`
- [#158430](https://github.com/NousResearch/hermes-agent/issues/158430) Support question: completed-delegation linkage lookup and normal approval workflow `comp/tools` `tool/delegate` `P3` `area/sessions`
- [#158426](https://github.com/NousResearch/hermes-agent/issues/158426) [Feature]: Public API for the write-approval queue (Desktop review plugin) `type/feature` `comp/tools` `tool/memory` `P3`
- [#158416](https://github.com/NousResearch/hermes-agent/issues/158416) [Feature]: Spoiler images in gateway replies via ||![alt](url)|| (Discord and Telegram) `type/feature` `comp/gateway` `platform/telegram` `platform/discord` `P3` `area/streaming` 💬1

### 🔒 Closed Issues
- [#158435](https://github.com/NousResearch/hermes-agent/issues/158435) diagnostic - deleting
- [#158431](https://github.com/NousResearch/hermes-agent/issues/158431) probe
- [#151192](https://github.com/NousResearch/hermes-agent/issues/151192) [Bug]: skill_view returns the "unchanged" stub after its first result was spilled to a preview
- [#158266](https://github.com/NousResearch/hermes-agent/issues/158266) [Bug]: ModuleNotFoundError: No module named 'hermes_state_runtime' on every chat request (image digest sha256:3e9fe4c6ef36...)
- [#66081](https://github.com/NousResearch/hermes-agent/issues/66081) Bug: Model selector dropdown loads but selection doesn't apply
- [#158142](https://github.com/NousResearch/hermes-agent/issues/158142) Canary E2E on 32dbc1dcda2255fd35969ec99cfc0170988c3eca is red (4 jobs)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,539 · **Open issues:** 1,351 · **Last push:** <1h ago

### 🐛 New Issues
- [#12614](https://github.com/zeroclaw-labs/zeroclaw/issues/12614) [Feature]: browser tool has no file-upload action, blocking every form that requires attaching a file
- [#12613](https://github.com/zeroclaw-labs/zeroclaw/issues/12613) [Tracker]: Deslop pass: dead code, inert features, comment slop and extra docs `dev` `priority:p2` `type:tracker`
- [#12611](https://github.com/zeroclaw-labs/zeroclaw/issues/12611) [Feature]: Retire the local LLM response cache `enhancement`
- [#12607](https://github.com/zeroclaw-labs/zeroclaw/issues/12607) Memory recall misses a saved fact, saves the wrong answer, and keeps both versions after correction
- [#12606](https://github.com/zeroclaw-labs/zeroclaw/issues/12606) [Bug]: a2a.client.peers cannot be set via config set/patch — A2aClientConfig uses prefix "a2a_client"
- [#12604](https://github.com/zeroclaw-labs/zeroclaw/issues/12604) [Bug]: MCP results from FastMCP tools that return a string still reach the model twice
- [#12601](https://github.com/zeroclaw-labs/zeroclaw/issues/12601) [Bug]: PR risk 9530 test-only proof reads base-side source at base.sha instead of the merge-base `bug`
- [#12598](https://github.com/zeroclaw-labs/zeroclaw/issues/12598) [Feature]: WhatsApp Web: send agent replies as quoted replies so group members know they were answered
- [#12597](https://github.com/zeroclaw-labs/zeroclaw/issues/12597) [Bug]: Telegram channel stops receiving messages when a voice message fails transcription (offset never advances) `bug` 💬1

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,717 · **Open issues:** 1,574 · **Last push:** 11d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,978 · **Open issues:** 121 · **Last push:** 28d ago

### 🐛 New Issues
- [#1324](https://github.com/moltis-org/moltis/issues/1324) [Bug]: exec tool `command` parameter says "shell command" but paired-node exec doesn't use a shell

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬5 · 10h ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 18d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 27d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 46d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 54d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 56d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 66d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 74d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 76d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 84d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Ipo Close](https://www.anthropic.com/news/ipo-close) _2026-11-20_

### OpenAI — 5 new
- [[Index] Combatting Adversarial Distillation](https://openai.com/index/combatting-adversarial-distillation/) _2026-11-21_
- [[Customer-Stories] Hebbia](https://openai.com/business/customer-stories/hebbia/) _2026-11-20_
- [[Safety-Alignment] Beyond Gmean Squared](https://openai.com/safety-alignment/beyond-gmean-squared/)
- [Safety Alignment](https://openai.com/safety-alignment/)
- [[Safety-Alignment] Misalignment Reports](https://openai.com/safety-alignment/misalignment-reports/)

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [xi called to support open source](https://reddit.com/r/LocalLLaMA/comments/1y065go/xi_called_to_support_open_source/) ↑2291
- [thinkingmachines/Inkling-2-Mini (MoE: 26b, a3B)](https://reddit.com/r/LocalLLaMA/comments/1y1diuk/thinkingmachinesinkling2mini_moe_26b_a3b/) ↑987
- [Today marks the two week anniversary of the becoming begins](https://reddit.com/r/LocalLLaMA/comments/1y135y5/today_marks_the_two_week_anniversary_of_the/) ↑781
- [Inkling 2 mini uncensored](https://reddit.com/r/LocalLLaMA/comments/1y1ig9e/inkling_2_mini_uncensored/) ↑199
- [unsloth/Inkling-2-Mini-GGUF · Hugging Face](https://reddit.com/r/LocalLLaMA/comments/1y1drpd/unslothinkling2minigguf_hugging_face/) ↑198

### r/singularity — top 2 new
- [The parrot strikes back](https://reddit.com/r/singularity/comments/1y1dns9/the_parrot_strikes_back/) ↑1119
- [Anthropic’s Claude solves the Riemann Hypothesis (the Holy Grail of maths) with a massive 250,000-page formal proof🚨](https://reddit.com/r/singularity/comments/1y1ibpk/anthropics_claude_solves_the_riemann_hypothesis/) ↑742

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw 2026.11.5 and 2026.11.6 bring fixes and stability improvements across chat, messaging, updates, plugins, and the native apps.](https://reddit.com/r/openclaw/comments/1y0w66x/openclaw_2026115_and_2026116_bring_fixes_and/) ↑16
- [Gemini 4 Neon is now in OpenClaw! 🦞](https://reddit.com/r/openclaw/comments/1y0ux6e/gemini_4_neon_is_now_in_openclaw/) ↑14
- [OpenClaw isn't free](https://reddit.com/r/openclaw/comments/1y1ewcq/openclaw_isnt_free/) ↑12
- [Using Openclaw with standard LLM for image generation](https://reddit.com/r/openclaw/comments/1y0rvat/using_openclaw_with_standard_llm_for_image/) ↑8
- [Banter: an OSS voice chat repo for OpenClaw](https://reddit.com/r/openclaw/comments/1y0rz4t/banter_an_oss_voice_chat_repo_for_openclaw/) ↑7

### X — @openclaw
- [Lobsters in the enterprise 🦞

Love seeing Microsoft build on OpenClaw, and even more seeing your team give back as maint](https://x.com/openclaw/status/2123934646195073378) ↑0 🔁0 · recent
- [At a recent conference someone asked 
@Pishgar
 "If OpenClaw is so powerful, why is it free?" 

Well it's not

As we get](https://x.com/openclaw/status/2123884900487237873) ↑0 🔁0 · recent
- [OpenClaw 2026.11.5 and 2026.11.6 bring fixes and stability improvements across chat, messaging, updates, plugins, and th](https://x.com/openclaw/status/2123660366140014721) ↑0 🔁0 · recent
- [Gemini 4 Neon is now in OpenClaw! 🦞

Google built Neon to get hard coding jobs done faster and for less than Carbon. At ](https://x.com/openclaw/status/2123640619931484511) ↑0 🔁0 · recent


### X — @steipete
_No new tweets since the last digest. Most recent:_
- [Landed a fix for that in OpenClaw yesterday (for the few folks using the embedded harness instead of codex, since it’s a](https://x.com/steipete/status/2123487048250327497)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
