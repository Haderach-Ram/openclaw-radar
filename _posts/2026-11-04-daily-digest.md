---
layout: post
title: "Ecosystem Digest — 2026-11-04"
date: 2026-11-04 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-04
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 393,870 | 5 | 2 | 10 | 1 |
| **hermesagent** | 260,263 | 10 | 4 | 5 | 1 |
| **ZeroClaw** | 33,119 | 10 | 3 | 9 | 0 |
| **IronClaw** | 12,712 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,939 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 393,870 · **Open issues:** 7,775 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.10.10](https://github.com/openclaw/openclaw/releases/tag/v2026.10.10) — openclaw 2026.10.10

### ✅ Merged PRs
- [#192407](https://github.com/openclaw/openclaw/pull/192407) fix(doctor): skip unrelated recovery captures before hashing
- [#184507](https://github.com/openclaw/openclaw/pull/184507) fix(sessions): avoid extra maintenance scans for embedded archives
- [#192030](https://github.com/openclaw/openclaw/pull/192030) test(team-reports): cover public PostgreSQL store transport
- [#192020](https://github.com/openclaw/openclaw/pull/192020) fix(team-reports): recover after database connection loss
- [#192017](https://github.com/openclaw/openclaw/pull/192017) fix(workboard): recover after database connection loss
- [#192011](https://github.com/openclaw/openclaw/pull/192011) fix(logbook): recover after database connection loss
- [#192406](https://github.com/openclaw/openclaw/pull/192406) fix(doctor): allow slow original-state backups to finish
- [#192449](https://github.com/openclaw/openclaw/pull/192449) test(ui): align remaining rebuilt toast expectations
- [#191977](https://github.com/openclaw/openclaw/pull/191977) fix(logbook): prune files outside PostgreSQL transactions
- [#192391](https://github.com/openclaw/openclaw/pull/192391) fix: clarify PR recovery and delayed completion guidance

### 🐛 New Issues
- [#192472](https://github.com/openclaw/openclaw/issues/192472) [Feature]: Google Chat: opt-in per-thread sessions for threaded replies `clawsweeper:intake:feature` 💬1
- [#192465](https://github.com/openclaw/openclaw/issues/192465) [Bug]: /v1/responses returns 500 "internal error" for the retryable "changed while starting work" rejection `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬1
- [#192460](https://github.com/openclaw/openclaw/issues/192460) [Bug]: WebChat keeps message(final=false) progress visible with Keep commentary off `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#192446](https://github.com/openclaw/openclaw/issues/192446) [Bug]: Feishu streaming card shows the last block twice when preview and block streaming are both on `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#192442](https://github.com/openclaw/openclaw/issues/192442) [Bug]: 2026.10.10 cloud worker turns fail: "Runtime config is not prepared. Await captureRuntimeConfigAsyncReader()() first" `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `issue-rating: 🦐 gold shrimp` `impact:other` 💬2

### 🔒 Closed Issues
- [#192470](https://github.com/openclaw/openclaw/issues/192470) state.admission.fast-path spends 1-2.7s in SQL per admission (schema/integrity re-check inside a write transaction)
- [#192463](https://github.com/openclaw/openclaw/issues/192463) [Bug]: Regression in 2026.10.10 — upgrading removes cross-provider fallback from existing cron jobs

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬69 · 2d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 260,263 · **Open issues:** 52,621 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.22.7](https://github.com/NousResearch/hermes-agent/releases/tag/v0.22.7) — Hermes Agent v0.22.7

### ✅ Merged PRs
- [#148639](https://github.com/NousResearch/hermes-agent/pull/148639) Optional skills that the MCP catalog, catalog plugins, built-in web search or vendor skill repos cover are removed
- [#148648](https://github.com/NousResearch/hermes-agent/pull/148648) Skill installs apply the current trust level after a repo's trust changes, not a cached one
- [#148570](https://github.com/NousResearch/hermes-agent/pull/148570) fix(desktop): keep one tool row per call when events repeat or ids are reused
- [#148655](https://github.com/NousResearch/hermes-agent/pull/148655) test(install-e2e): journeys turn STT off so an old release's boot probe cannot stall the send
- [#148658](https://github.com/NousResearch/hermes-agent/pull/148658) ci(js): drop vitest's run history from the cached node_modules

### 🐛 New Issues
- [#148710](https://github.com/NousResearch/hermes-agent/issues/148710) [Bug]: a conflicted autostash restore discards every file that already merged
- [#148704](https://github.com/NousResearch/hermes-agent/issues/148704) [Bug]: Desktop applies wrong-installation roster metadata after MISROUTED (follow-up to #131853)
- [#148703](https://github.com/NousResearch/hermes-agent/issues/148703) [SANITIZED — possible injection attempt]
- [#148702](https://github.com/NousResearch/hermes-agent/issues/148702) API server: per-request opt-out for title generation and background review
- [#148701](https://github.com/NousResearch/hermes-agent/issues/148701) [Feature]: Operator-initiated pause of a RUNNING kanban worker with session-preserving resume (suspend mid-run without losing the run)
- [#148698](https://github.com/NousResearch/hermes-agent/issues/148698) [Bug]: Feishu redelivery of same message_id beyond 5-min dedup TTL hard-interrupts in-flight turn
- [#148697](https://github.com/NousResearch/hermes-agent/issues/148697) [Feature]: Per-task / per-subtree kanban pause with correct semantics across statuses (block can't touch gated todo; review lane ignores it)
- [#148691](https://github.com/NousResearch/hermes-agent/issues/148691) [Bug]: Nix install: `hermes desktop` dead-ends with "Desktop GUI source not found" while `hermes-desktop` is installed
- [#148689](https://github.com/NousResearch/hermes-agent/issues/148689) Windows: `hermes acp` under a host whose job object forbids breakaway can't start a session (`windows_breakaway_unavailable`) 💬1
- [#148686](https://github.com/NousResearch/hermes-agent/issues/148686) [Bug]: Webapp foreground transcript misses persisted user and assistant messages after disconnect

### 🔒 Closed Issues
- [#140667](https://github.com/NousResearch/hermes-agent/issues/140667) [Bug]: Desktop: session.control.read times out at 30s - one slow read-only handler (session.context_breakdown) starves every queued RPC on the same WS
- [#143414](https://github.com/NousResearch/hermes-agent/issues/143414) [Bug]: /new session rotation drops live reasoning in classic CLI — show_reasoning flag not re-synced to the fresh session
- [#140397](https://github.com/NousResearch/hermes-agent/issues/140397) [Bug]: Desktop repeats a tool row when a sealed call's completion arrives under a newer sequence
- [#148663](https://github.com/NousResearch/hermes-agent/issues/148663) [Bug]: Docker backend — persisted MCP results announced with the host path when no sandbox exists yet, and the miss is reported as "expired"

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,119 · **Open issues:** 1,155 · **Last push:** 1h ago

### ✅ Merged PRs
- [#10873](https://github.com/zeroclaw-labs/zeroclaw/pull/10873) chore(deps): bump similar from 2.7.0 to 3.2.1
- [#11624](https://github.com/zeroclaw-labs/zeroclaw/pull/11624) fix(zerocode): answer dropped elicitations and record them in the transcript
- [#11234](https://github.com/zeroclaw-labs/zeroclaw/pull/11234) fix(rpc): judge queued session ownership by current authority
- [#12084](https://github.com/zeroclaw-labs/zeroclaw/pull/12084) chore(docs): import AGENTS.md in CLAUDE.md for Claude Code
- [#11318](https://github.com/zeroclaw-labs/zeroclaw/pull/11318) test(gateway): cover plugin webhook ingress in required CI
- [#11739](https://github.com/zeroclaw-labs/zeroclaw/pull/11739) fix(channels/telegram): withdraw the ack reaction when a reply finishes
- [#11054](https://github.com/zeroclaw-labs/zeroclaw/pull/11054) feat(channels/whatsapp-web): render thematic breaks and setext headings
- [#11270](https://github.com/zeroclaw-labs/zeroclaw/pull/11270) ci(desktop): run zeroclaw-desktop tests on 3 OS
- [#12003](https://github.com/zeroclaw-labs/zeroclaw/pull/12003) feat(channels): allow inbound-only email channels without SMTP

### 🐛 New Issues
- [#12218](https://github.com/zeroclaw-labs/zeroclaw/issues/12218) [Bug]: The Windows Clippy change detector times out on its full-history fetch `bug`
- [#12217](https://github.com/zeroclaw-labs/zeroclaw/issues/12217) [Docs]: Email tools-only setup should say approval routes also start the IMAP listener `docs` `type:docs`
- [#12214](https://github.com/zeroclaw-labs/zeroclaw/issues/12214) [Feature]: Outbound media markers cannot carry a caption — text + image is always delivered as two separate messages
- [#12211](https://github.com/zeroclaw-labs/zeroclaw/issues/12211) [Bug]: delegated agents don't load TOOLS.md (delegate prompt uses its own file list, not PERSONALITY_FILES)
- [#12210](https://github.com/zeroclaw-labs/zeroclaw/issues/12210) [Bug]: Source Docker image builds fail to load the workspace: tests/fixtures/runtime-composition-consumer is not copied before the pre-fetch `bug` `priority:p1` `release:v0.9.0` 💬1
- [#12203](https://github.com/zeroclaw-labs/zeroclaw/issues/12203) web_search_tool silently compiled out without tools-external — no TOOL_COMPILED_OUT warning 💬1
- [#12194](https://github.com/zeroclaw-labs/zeroclaw/issues/12194) runtime: unknown model silently falls back to a 32k context budget (UNCONFIGURED_CONTEXT_WINDOW_FALLBACK) and fails turns that would fit the real window 💬1
- [#12191](https://github.com/zeroclaw-labs/zeroclaw/issues/12191) [Feature]: hybrid (dense + BM25) recall for the Qdrant memory backend 💬1
- [#12186](https://github.com/zeroclaw-labs/zeroclaw/issues/12186) [Bug]: zerocode --agent / -a is parsed but never used; TUI always opens on the Dashboard 💬1
- [#12107](https://github.com/zeroclaw-labs/zeroclaw/issues/12107) [Task]: show a detached chat turn's answer when the socket reopens before the turn ends `web` 💬1

### 🔒 Closed Issues
- [#11623](https://github.com/zeroclaw-labs/zeroclaw/issues/11623) [Bug]: ZeroCode drops a pending ask_user prompt without replying, so the tool times out after 600 s and the question leaves no record
- [#11126](https://github.com/zeroclaw-labs/zeroclaw/issues/11126) [SANITIZED — possible injection attempt]
- [#11052](https://github.com/zeroclaw-labs/zeroclaw/issues/11052) [Feature]: Render thematic breaks and setext headings for WhatsApp

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,712 · **Open issues:** 1,570 · **Last push:** 8h ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,939 · **Open issues:** 121 · **Last push:** 11d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 1d ago
- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬2 · 10d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 10d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 29d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 37d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 39d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 49d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 57d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 59d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 67d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Research] Provable Inference](https://www.anthropic.com/research/provable-inference) _2026-11-03_

### OpenAI — 3 new
- [[Index] Cisco Cyber](https://openai.com/index/cisco-cyber/) _2026-11-04_
- [[Index] Heimstaden](https://openai.com/index/heimstaden/) _2026-11-04_
- [[Index] Jill Hazelbaker Chief Corporate Affairs Officer](https://openai.com/index/jill-hazelbaker-chief-corporate-affairs-officer/) _2026-11-04_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [British fintech Revolut slashes AI coding costs 10x by cutting out Claude and going self-hosted](https://reddit.com/r/LocalLLaMA/comments/1xn568h/british_fintech_revolut_slashes_ai_coding_costs/) ↑1018
- [Alibaba's Qwen Code repo just leaked qwen4-max, qwen4-coder-plus, and qwen4-omni-120b](https://reddit.com/r/LocalLLaMA/comments/1xmitzx/alibabas_qwen_code_repo_just_leaked_qwen4max/) ↑853
- [RTX 5090 with 64GB and 96GB VRAM 'confirmed' by US GPU repair tech](https://reddit.com/r/LocalLLaMA/comments/1xmqq2a/rtx_5090_with_64gb_and_96gb_vram_confirmed_by_us/) ↑637
- [Like GPT-6 Astra, Qwen 3.8 27B can interpret model weights](https://reddit.com/r/LocalLLaMA/comments/1xmz9ca/like_gpt6_astra_qwen_38_27b_can_interpret_model/) ↑435
- [What do people with normal hardware : 32GB ram 16GB VRAM run?](https://reddit.com/r/LocalLLaMA/comments/1xn2jyz/what_do_people_with_normal_hardware_32gb_ram_16gb/) ↑201

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw
_No new posts in the last 24h._

### X — @openclaw
- [Particle-1 is available in OpenClaw.


@particle_api
 reports ~45% fewer output tokens than DeepSeek V4.1 Flash with com](https://x.com/openclaw/status/2117637498902077498) ↑0 🔁0 · recent
- [OpenClaw v2026.10.10 🦞

🗂️ Chat Details pulls up beside wide chats
🧭 Advisor suggests course corrections
🎙️ Browser Talk](https://x.com/openclaw/status/2117605921102995968) ↑0 🔁0 · recent


### X — @steipete
- [very neat!](https://x.com/steipete/status/2117755295552221683) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
