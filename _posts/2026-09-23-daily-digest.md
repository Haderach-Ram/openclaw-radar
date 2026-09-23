---
layout: post
title: "Ecosystem Digest — 2026-09-23"
date: 2026-09-23 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-23
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 390,266 | 11 | 1 | 10 | 0 |
| **hermesagent** | 248,125 | 4 | 0 | 5 | 0 |
| **ZeroClaw** | 32,862 | 9 | 6 | 10 | 0 |
| **IronClaw** | 12,629 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,870 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 390,266 · **Open issues:** 8,298 · **Last push:** <1h ago

### ✅ Merged PRs
- [#156050](https://github.com/openclaw/openclaw/pull/156050) fix(ui): repair keyboard access, screen reader semantics, and contrast
- [#156059](https://github.com/openclaw/openclaw/pull/156059) ci: shorten lint and test-type queues
- [#156082](https://github.com/openclaw/openclaw/pull/156082) fix: restore release validation routing
- [#154946](https://github.com/openclaw/openclaw/pull/154946) perf(sqlite): reuse prepared schema-version statements
- [#155890](https://github.com/openclaw/openclaw/pull/155890) chore(qa): add Crabline Slack callback candidate tests
- [#156058](https://github.com/openclaw/openclaw/pull/156058) fix(tests): prevent shared filesystem mode from breaking archive tests
- [#155505](https://github.com/openclaw/openclaw/pull/155505) perf: avoid plugin metadata load for local hints
- [#155504](https://github.com/openclaw/openclaw/pull/155504) test: reduce ACP in-memory poll latency
- [#155199](https://github.com/openclaw/openclaw/pull/155199) fix(ui): preserve message footer focus outlines
- [#151176](https://github.com/openclaw/openclaw/pull/151176) feat(openai): add explicit Agents API MVP harness

### 🐛 New Issues
- [#156099](https://github.com/openclaw/openclaw/issues/156099) [regression] Replies stop dispatching - 'prepared reply dispatch runtime owner was not published for main' under heavy host load (2026.9.5, Windows scheduled task)
- [#156098](https://github.com/openclaw/openclaw/issues/156098) Background exec continues after its original operator access is revoked `maintainer`
- [#156094](https://github.com/openclaw/openclaw/issues/156094) [Bug]: Discord Activity titles with emoji are rejected as over 80 characters when they are not 💬1
- [#156091](https://github.com/openclaw/openclaw/issues/156091) Update failure: doctor-failed (2026.9.4) 💬1
- [#156090](https://github.com/openclaw/openclaw/issues/156090) [Bug]: Stop can restart a completed helper continuation 💬1
- [#156089](https://github.com/openclaw/openclaw/issues/156089) sessions_spawn with worktree:true + projectGitUrl to a different agent fails with "git checkout has no commits" against the target agent's own workspace, not the requested repo `P2` `impact:session-state` 💬1
- [#156088](https://github.com/openclaw/openclaw/issues/156088) Update failure: finalize:plugins (2026.9.5) 💬1
- [#156086](https://github.com/openclaw/openclaw/issues/156086) [Feature]: tools.exec.mode "auto" does not auto-review claude-cli native Bash, so it behaves like "ask" 💬1
- [#156075](https://github.com/openclaw/openclaw/issues/156075) Repeated configured-model fallbacks rebuild prefix and provider lookup work `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#156070](https://github.com/openclaw/openclaw/issues/156070) [Bug]: Codex-native completion can create a duplicate final reply after the parent already consumed the child result via wait_agent `bug` `bug:behavior` `P2` `impact:message-loss` `issue-rating: 🦪 silver shellfish` 💬1
- [#156069](https://github.com/openclaw/openclaw/issues/156069) Update failure: runtime-verification-failed (2026.9.4) `clawsweeper:needs-info` `P0` `issue-rating: 🦪 silver shellfish` `impact:ux-release-blocker` 💬2

### 🔒 Closed Issues
- [#111990](https://github.com/openclaw/openclaw/issues/111990) [Bug]: memory_search can use a stale cached memory manager and time out or return false zero-hit results

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 248,125 · **Open issues:** 44,077 · **Last push:** <1h ago

### ✅ Merged PRs
- [#119649](https://github.com/NousResearch/hermes-agent/pull/119649) fmt(js): `npm run fix` auto-fix
- [#119644](https://github.com/NousResearch/hermes-agent/pull/119644) Installed plugins' MCP tools and skills are live in every open chat, no Connect-now
- [#119633](https://github.com/NousResearch/hermes-agent/pull/119633) Catalog install card: plugin and skill rows with an Advanced install modal
- [#119605](https://github.com/NousResearch/hermes-agent/pull/119605) fix(desktop): keep typing and refreshed transcripts stable
- [#119601](https://github.com/NousResearch/hermes-agent/pull/119601) The last four MCP enabled-flag readers use the shared reader (ACP, hermes tools picker, desktop connector card, health sweep)

### 🐛 New Issues
- [#119733](https://github.com/NousResearch/hermes-agent/issues/119733) [Bug]: ${VAR} env var substitution in config.yaml is not expanded for gateway platform config (platforms.*.extra — webhook secret, api_server key, teams credentials) 💬1
- [#119730](https://github.com/NousResearch/hermes-agent/issues/119730) [Bug] Canonical Bot Chat archived while visible (archived=1, hidden=0, end_reason=NULL) deadlocks the title — falls through both retire and resurrection paths
- [#119716](https://github.com/NousResearch/hermes-agent/issues/119716) Desktop: Codex interim commentary reappears inside Thinking after tool-call hydration
- [#119707](https://github.com/NousResearch/hermes-agent/issues/119707) zsh completion does nothing on the first Tab when autoloaded from fpath

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,862 · **Open issues:** 740 · **Last push:** 13h ago

### ✅ Merged PRs
- [#11038](https://github.com/zeroclaw-labs/zeroclaw/pull/11038) chore(security): ignore RUSTSEC-2026-0292 (imbl-sized-chunks double free)
- [#11042](https://github.com/zeroclaw-labs/zeroclaw/pull/11042) docs(developing): record the replacement-first integration policy
- [#10958](https://github.com/zeroclaw-labs/zeroclaw/pull/10958) fix(channels): use length-prefixed interruption scope keys to prevent boundary collisions (#10948)
- [#10953](https://github.com/zeroclaw-labs/zeroclaw/pull/10953) fix(providers): keep signed reasoning intact on the seam sanitizers
- [#10982](https://github.com/zeroclaw-labs/zeroclaw/pull/10982) fix(channels/whatsapp-web): attach inline previews to outgoing images
- [#10895](https://github.com/zeroclaw-labs/zeroclaw/pull/10895) fix(anthropic): keep the rolling cache breakpoint when the last message ends with an image
- [#10916](https://github.com/zeroclaw-labs/zeroclaw/pull/10916) fix(providers): forward reasoning_effort through compatible providers via opt-in passthrough flag
- [#11040](https://github.com/zeroclaw-labs/zeroclaw/pull/11040) fix(nix): build zerocode with its own feature set
- [#10956](https://github.com/zeroclaw-labs/zeroclaw/pull/10956) feat(runtime): detect platform default shell
- [#10475](https://github.com/zeroclaw-labs/zeroclaw/pull/10475) feat(whatsapp): render outbound Markdown in WhatsApp's dialect

### 🐛 New Issues
- [#11059](https://github.com/zeroclaw-labs/zeroclaw/issues/11059) [Bug]: WhatsApp Web ignores force_voice, so send_via cannot route a turn to voice
- [#11058](https://github.com/zeroclaw-labs/zeroclaw/issues/11058) [Bug]: an explicit `allowed_commands` entry exempts a high-risk command from `block_high_risk_commands` — it then runs unprompted, with no approval and no log
- [#11055](https://github.com/zeroclaw-labs/zeroclaw/issues/11055) [Bug]: The daemon never registers the channel-map factory, so webhook, cron and SOP turns have no channels 💬1
- [#11053](https://github.com/zeroclaw-labs/zeroclaw/issues/11053) RFC: Knowledge graph as a first-class agent memory layer
- [#11052](https://github.com/zeroclaw-labs/zeroclaw/issues/11052) [Feature]: Render thematic breaks and setext headings for WhatsApp `enhancement` 💬3
- [#11050](https://github.com/zeroclaw-labs/zeroclaw/issues/11050) [Feature]: Pace native polls with other outbound channel messages `enhancement`
- [#11036](https://github.com/zeroclaw-labs/zeroclaw/issues/11036) OpenCode big-pickle returns 403 FreeTierError on v0.8.4 `bug` `provider` `provider:openai` `provider:compatible` `priority:p2` `r:needs-repro` `needs-author-action` `risk:medium` `topic:provider-transport` 💬2
- [#11027](https://github.com/zeroclaw-labs/zeroclaw/issues/11027) RFC: Agent-to-agent session messaging with receiver discretion `agent` `channel` `runtime` `security` `tool` `domain:security` `domain:architecture` `priority:p2` `needs-maintainer-review` `type:rfc` `zerocode` `risk:high` `topic:identity-access` `topic:agent-loop` `topic:zerocode` 💬3
- [#11017](https://github.com/zeroclaw-labs/zeroclaw/issues/11017) RFC: Preserve applicable reviews and simplify expedited merge decisions `docs` `priority:p2` `needs-maintainer-review` `type:rfc` `risk:high` 💬3

### 🔒 Closed Issues
- [#11016](https://github.com/zeroclaw-labs/zeroclaw/issues/11016) [Docs]: Document the lighter-core replacement-first integration policy
- [#10948](https://github.com/zeroclaw-labs/zeroclaw/issues/10948) [Bug]: interruption-scope keys collide across component boundaries
- [#10952](https://github.com/zeroclaw-labs/zeroclaw/issues/10952) Seam sanitizers rewrite signed reasoning inside the assistant tool-call envelope; Anthropic rejects the replayed thinking
- [#10981](https://github.com/zeroclaw-labs/zeroclaw/issues/10981) [Bug]: Outgoing WhatsApp images carry no jpegThumbnail or dimensions, so phones show an empty card
- [#10889](https://github.com/zeroclaw-labs/zeroclaw/issues/10889) [Bug]: native Anthropic provider drops the rolling cache breakpoint when the last message ends with an image block
- [#9392](https://github.com/zeroclaw-labs/zeroclaw/issues/9392) [Bug]: LINE group messages skip the allowlist and the pairing handshake

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,629 · **Open issues:** 1,528 · **Last push:** 1d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,870 · **Open issues:** 96 · **Last push:** 10h ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 11h ago
- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬3 · 4d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 7d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 15d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 17d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 25d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 29d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 41d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 44d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 47d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [Claude Opus 5 5](https://www.anthropic.com/claude-opus-5-5)

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [New 6B image model coming, AntLing just open sourced the Ming-Image-0.1-Design family](https://reddit.com/r/LocalLLaMA/comments/1wnipcz/new_6b_image_model_coming_antling_just_open/) ↑236
- [Qwen image 2.1 (Fast FP8) generates premium quality images](https://reddit.com/r/LocalLLaMA/comments/1wnhq8d/qwen_image_21_fast_fp8_generates_premium_quality/) ↑105

### r/singularity — top 5 new
- [Introducing GPT-6 Sol and Luna](https://reddit.com/r/singularity/comments/1wngzou/introducing_gpt6_sol_and_luna/) ↑1031
- [Claude Opus 5.5 Benchmarks](https://reddit.com/r/singularity/comments/1wneb1u/claude_opus_55_benchmarks/) ↑974
- [Introducing Claude Opus 5.5, 40% Cheaper and Smarter Than Ever Before](https://reddit.com/r/singularity/comments/1wne89f/introducing_claude_opus_55_40_cheaper_and_smarter/) ↑741
- [Opus 5.5 built this](https://reddit.com/r/singularity/comments/1wngd2w/opus_55_built_this/) ↑575
- [The race for AGI](https://reddit.com/r/singularity/comments/1wnn1p8/the_race_for_agi/) ↑563

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [The more I use OpenClaw; The less I understand](https://reddit.com/r/openclaw/comments/1wna116/the_more_i_use_openclaw_the_less_i_understand/) ↑21
- [OpenClaw Completes Security Audit Through OpenAI’s Patch the Planet Initiative](https://reddit.com/r/openclaw/comments/1wnmusy/openclaw_completes_security_audit_through_openais/) ↑4
- [Openclaw Vs Claude Code](https://reddit.com/r/openclaw/comments/1wno25i/openclaw_vs_claude_code/) ↑1
- [Build Your Startup’s First Hire | OpenClaw 2.0 Hackathon Kickoff](https://reddit.com/r/openclaw/comments/1wno0gj/build_your_startups_first_hire_openclaw_20/) ↑1

### X — @openclaw
- [Everything's coming up Jev!

Last week 
@jlehman_
 pushed support for decision models in OpenClaw core and for plugins

](https://x.com/openclaw/status/2102488199486656862) ↑0 🔁0 · recent


### X — @steipete
- [Had ChatGPT sometimes crashing on me after updating to macOS 27 and... Astra found a ~14 year old bug in libuv.](https://x.com/steipete/status/2102501642176528743) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
