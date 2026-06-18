---
layout: post
title: "Ecosystem Digest — 2026-06-18"
date: 2026-06-18 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-18
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 379,236 | 1 | 8 | 7 | 0 |
| **hermesagent** | 196,254 | 13 | 3 | 10 | 0 |
| **ZeroClaw** | 31,938 | 15 | 2 | 10 | 0 |
| **IronClaw** | 12,456 | 7 | 5 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 379,236 · **Open issues:** 6,493 · **Last push:** <1h ago

### ✅ Merged PRs
- [#93713](https://github.com/openclaw/openclaw/pull/93713) fix: route deleted-agent session purge through lifecycle seam
- [#84172](https://github.com/openclaw/openclaw/pull/84172) fix(exec): rebuild command authorization on the Tree-sitter command planner
- [#89596](https://github.com/openclaw/openclaw/pull/89596) fix(policy): recognize declared tool allowlists
- [#92016](https://github.com/openclaw/openclaw/pull/92016) fix(plugins): compose live hook registry view for tool-call hooks
- [#94296](https://github.com/openclaw/openclaw/pull/94296) fix: require all taxonomy coverage ids for a feature - AND not OR
- [#93704](https://github.com/openclaw/openclaw/pull/93704) refactor: add session cleanup lifecycle seam
- [#94282](https://github.com/openclaw/openclaw/pull/94282) Support owner-qualified ClawHub skill installs

### 🐛 New Issues
- [#94360](https://github.com/openclaw/openclaw/issues/94360) [Bug]: Feishu - exec stderr output sent as user-visible reply, covers actual agent response 💬1

### 🔒 Closed Issues
- [#94330](https://github.com/openclaw/openclaw/issues/94330) replay_invalid (stale thinking-block signature) surfaces a hard error + drops the user message instead of self-recovering
- [#94258](https://github.com/openclaw/openclaw/issues/94258) Bug: Tier routing not resolving tier-* aliases to actual models in v2026.6.8
- [#94336](https://github.com/openclaw/openclaw/issues/94336) msteams plugin: proactive sends fail with "UND_ERR_INVALID_ARG" after 2026.6.8 upgrade
- [#94313](https://github.com/openclaw/openclaw/issues/94313) [Bug] QQBot token refresh 503 storm poisons shared undici global dispatcher, causing cross-plugin network failures
- [#94302](https://github.com/openclaw/openclaw/issues/94302) Vega Habits v2 follow-up
- [#94293](https://github.com/openclaw/openclaw/issues/94293) Channel health-monitor restart never recovers a wedged account (stale task guard skipped)
- [#94278](https://github.com/openclaw/openclaw/issues/94278) Regression: aborted-before-content turns persist empty content:[], poisoning session (death spiral) on native Anthropic (v2026.6.6)
- [#94318](https://github.com/openclaw/openclaw/issues/94318) [Feature]: Prefix bootstrap files with openclaw_ to prevent project file collisions

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 5h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 196,254 · **Open issues:** 21,675 · **Last push:** <1h ago

### ✅ Merged PRs
- [#48147](https://github.com/NousResearch/hermes-agent/pull/48147) feat(relay): connector⇄gateway channel auth + signed-HTTP inbound receiver + enroll CLI
- [#47555](https://github.com/NousResearch/hermes-agent/pull/47555) fix(docker): supervised gateway uses --replace to take over stale holder (NS-505)
- [#48108](https://github.com/NousResearch/hermes-agent/pull/48108) fix(xai): native web_search swap + incomplete guard for OAuth Responses (salvage #44341)
- [#48122](https://github.com/NousResearch/hermes-agent/pull/48122) fix(desktop): retry the self-update rebuild once so the app relaunches
- [#48109](https://github.com/NousResearch/hermes-agent/pull/48109) fix(agent): dampen empty-name phantom tool-call loop (#47967)
- [#47674](https://github.com/NousResearch/hermes-agent/pull/47674) fix(dashboard): recover the Chat tab when the agent session ends (NS-504)
- [#48104](https://github.com/NousResearch/hermes-agent/pull/48104) fix(dump): show commit date instead of release date in hermes debug
- [#48091](https://github.com/NousResearch/hermes-agent/pull/48091) fix(desktop): resolve electronDist dynamically + self-heal blocked installs (supersedes #48081/#48082)
- [#48078](https://github.com/NousResearch/hermes-agent/pull/48078) feat(gateway): relay adapter + capability descriptor (Gateway Gateway phases 0-1)
- [#47490](https://github.com/NousResearch/hermes-agent/pull/47490) Harden hosted Docker install tree against self-modification

### 🐛 New Issues
- [#48173](https://github.com/NousResearch/hermes-agent/issues/48173) [SANITIZED — possible injection attempt] `type/bug` `comp/agent` `P2`
- [#48172](https://github.com/NousResearch/hermes-agent/issues/48172) browser: macOS app-bundle Chrome is ignored by local tool availability check `type/bug` `tool/browser` `P2`
- [#48171](https://github.com/NousResearch/hermes-agent/issues/48171) browser: macOS /browser connect ignores per-user Applications installs `type/bug` `tool/browser` `P3`
- [#48169](https://github.com/NousResearch/hermes-agent/issues/48169) dashboard: profile setup command assumes optional wrapper alias exists `type/bug` `comp/cli` `P3`
- [#48167](https://github.com/NousResearch/hermes-agent/issues/48167) [Bug] Gateway GUI start button doesn't work, but 'hermes gateway run' CLI works fine `type/bug` `comp/gateway` `comp/tui` `P2` 💬1
- [#48164](https://github.com/NousResearch/hermes-agent/issues/48164) gateway: launchd plist generator does not XML-escape dynamic strings `type/bug` `comp/gateway` `P3`
- [#48161](https://github.com/NousResearch/hermes-agent/issues/48161) Chinese IME input not displayed until next keypress on Windows (patch_stdout interferes with IME composition) `type/bug` `comp/cli` `P2` 💬1
- [#48160](https://github.com/NousResearch/hermes-agent/issues/48160) desktop: macOS in-app updater misses mac-x64 rebuilt app bundle `type/bug` `comp/tui` `P3`
- [#48159](https://github.com/NousResearch/hermes-agent/issues/48159) Feature Request: Add Kanban board view to Hermes Desktop `duplicate` `type/feature` `comp/tui` `P3` 💬1
- [#48158](https://github.com/NousResearch/hermes-agent/issues/48158) desktop: macOS resolvers ignore Homebrew PATH before backend spawn `type/bug` `comp/cli` `comp/tui` `P3`
- [#48156](https://github.com/NousResearch/hermes-agent/issues/48156) [Feature Request/Bug] Prevent plaintext API key storage in auth.json and fix Credential Pool merging for .env and manual keys `type/feature` `comp/cli` `area/auth` `area/config` `P3`
- [#48152](https://github.com/NousResearch/hermes-agent/issues/48152) test-issue-ignore `invalid`
- [#48150](https://github.com/NousResearch/hermes-agent/issues/48150) Plain text gateway adapters swallow Markdown bullet lists and literal asterisks (strip_markdown eats `*`) `type/bug` `comp/gateway` `P2` 💬1

### 🔒 Closed Issues
- [#48149](https://github.com/NousResearch/hermes-agent/issues/48149) [Bug] gh CLI authentication fails with 401/Blocked when using environment variables in certain Hermes session contexts
- [#47967](https://github.com/NousResearch/hermes-agent/issues/47967) [Bug]: XML tool call syntax in external file content generates phantom tool calls and corrupts conversation context
- [#47477](https://github.com/NousResearch/hermes-agent/issues/47477) [Feature]: # WhatsApp Group Sending with Hermes Skill (Termux) ג€” One-File Guide

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,938 · **Open issues:** 378 · **Last push:** <1h ago

### ✅ Merged PRs
- [#7842](https://github.com/zeroclaw-labs/zeroclaw/pull/7842) feat(cli): agents/providers/channels CRUD + skill-bundle cascade (#7468/#7175)
- [#7841](https://github.com/zeroclaw-labs/zeroclaw/pull/7841) feat(gateway): agent owned-state rename cascade + rename wiring (#7468)
- [#7840](https://github.com/zeroclaw-labs/zeroclaw/pull/7840) feat(config): rename_with_cascade for aliased entries (#7468)
- [#7684](https://github.com/zeroclaw-labs/zeroclaw/pull/7684) fix(acp): surface history-pruner and turn-cancel as visible events
- [#7678](https://github.com/zeroclaw-labs/zeroclaw/pull/7678) fix(runtime): thread shared CanvasStore into WS chat and ACP agent sessions
- [#7754](https://github.com/zeroclaw-labs/zeroclaw/pull/7754) perf(docs): publish rustdoc once, dedupe per-locale assets, drop print pages
- [#7839](https://github.com/zeroclaw-labs/zeroclaw/pull/7839) feat(config): delete_with_cascade for channels (#7175)
- [#7838](https://github.com/zeroclaw-labs/zeroclaw/pull/7838) feat(gateway): agent owned-state cascade on delete (#7175)
- [#7802](https://github.com/zeroclaw-labs/zeroclaw/pull/7802) feat(zerocode): add doctor pane
- [#7780](https://github.com/zeroclaw-labs/zeroclaw/pull/7780) fix(runtime): forward trimming budgets through agent_turn wrapper

### 🐛 New Issues
- [#7910](https://github.com/zeroclaw-labs/zeroclaw/issues/7910) Add Windows runtime test coverage for the self-update swap/rollback/sidecar paths
- [#7907](https://github.com/zeroclaw-labs/zeroclaw/issues/7907) [Bug]: agent rename can move owned state before config persistence `bug` `risk: high` `agent` `config` `cron` `gateway` `memory` `runtime` `gateway: api` `priority:p1`
- [#7904](https://github.com/zeroclaw-labs/zeroclaw/issues/7904) [Bug]: always-inject SKILL.md frontmatter no longer works in compact prompt mode `bug` `risk: medium` `agent` `runtime` `skills` `priority:p2` `status:accepted`
- [#7900](https://github.com/zeroclaw-labs/zeroclaw/issues/7900) [SANITIZED — possible injection attempt] `bug` `risk: medium` `provider` `provider:anthropic` `tool:schema` `priority:p2` `status:accepted`
- [#7899](https://github.com/zeroclaw-labs/zeroclaw/issues/7899) [Bug]: OpenAI STT provider ignores env-based credentials `bug` `risk: medium` `channel` `config` `provider` `status:accepted` `priority:p3`
- [#7898](https://github.com/zeroclaw-labs/zeroclaw/issues/7898) [Bug]: rust_native browser snapshots and @ref selectors fail under WebDriver `bug` `risk: medium` `tool` `tool: browser` `priority:p2` `status:accepted`
- [#7897](https://github.com/zeroclaw-labs/zeroclaw/issues/7897) [Feature]: Apply security policy and channel config updates without full daemon reload `enhancement` `risk: high` `channel` `config` `daemon` `gateway` `security` `type:rfc` `status:accepted` `priority:p3`
- [#7896](https://github.com/zeroclaw-labs/zeroclaw/issues/7896) [Bug]: Groq native tool messages should include the tool name `bug` `risk: medium` `provider` `provider: compatible` `provider: groq` `priority:p2` `status:accepted`
- [#7895](https://github.com/zeroclaw-labs/zeroclaw/issues/7895) [Bug]: daemon gateway supervisor should reuse an existing healthy gateway `bug` `risk: high` `daemon` `gateway` `runtime` `priority:p2` `status:accepted`
- [#7894](https://github.com/zeroclaw-labs/zeroclaw/issues/7894) [Bug]: OpenAI Codex account id extraction should prefer chatgpt_account_id claims `bug` `risk: high` `provider` `provider: openai_codex` `priority:p2` `status:accepted`
- [#7892](https://github.com/zeroclaw-labs/zeroclaw/issues/7892) [Bug]: CLI approval prompt should read controlling terminal when stdin is detached `bug` `risk: high` `runtime` `security` `priority:p2` `status:accepted`
- [#7891](https://github.com/zeroclaw-labs/zeroclaw/issues/7891) [Feature]: Add Signal media attachment support `enhancement` `risk: high` `channel` `priority:p2` `channel:signal` `status:accepted`
- [#7890](https://github.com/zeroclaw-labs/zeroclaw/issues/7890) [Feature]: Render Signal outbound Markdown as native text styles `enhancement` `risk: medium` `channel` `channel:signal` `status:accepted` `priority:p3`
- [#7889](https://github.com/zeroclaw-labs/zeroclaw/issues/7889) [Bug]: session_end hook is defined but never fired `bug` `risk: high` `channel` `gateway` `runtime` `priority:p2` `status:accepted`
- [#7888](https://github.com/zeroclaw-labs/zeroclaw/issues/7888) [Bug]: zeroclaw-runtime still depends on rumqttc without channel-mqtt `bug` `risk: medium` `dependencies` `channel` `runtime` `priority:p2` `channel:mqtt` `status:accepted`

### 🔒 Closed Issues
- [#7563](https://github.com/zeroclaw-labs/zeroclaw/issues/7563) [Bug]: canvas-store regression in WS chat/ACP sessions breaks /canvas after #6986
- [#7736](https://github.com/zeroclaw-labs/zeroclaw/issues/7736) bug(runtime): forward trimming budgets through agent turn wrapper

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,456 · **Open issues:** 1,191 · **Last push:** <1h ago

### ✅ Merged PRs
- [#5022](https://github.com/nearai/ironclaw/pull/5022) feat(agent-loop): output-aware no-progress detection (PR3)
- [#5000](https://github.com/nearai/ironclaw/pull/5000) feat(agent-loop): content-digest plumbing for output-aware progress (PR2)
- [#5035](https://github.com/nearai/ironclaw/pull/5035) feat(reborn): show tool arguments live while the tool is running
- [#5051](https://github.com/nearai/ironclaw/pull/5051) fix: Gmail auth-resume failure — stop run-borking + restore persistent-approval grant
- [#5029](https://github.com/nearai/ironclaw/pull/5029) feat(coding): byte budget for read_file to bound context growth
- [#5024](https://github.com/nearai/ironclaw/pull/5024) perf(webui-v2): self-host all frontend assets, drop CDN round-trips
- [#4993](https://github.com/nearai/ironclaw/pull/4993) fix(agent-loop): no-progress stop fails honestly instead of faking completion
- [#4955](https://github.com/nearai/ironclaw/pull/4955) fix(reborn): correlate run logs with thread_id/run_id for operator Logs panel
- [#5014](https://github.com/nearai/ironclaw/pull/5014) fix(reborn): cancel stale AuthFlow on Slack auth auto-deny (#4952)
- [#5010](https://github.com/nearai/ironclaw/pull/5010) Surface tool calls and outputs in OpenAI Responses API

### 🐛 New Issues
- [#5058](https://github.com/nearai/ironclaw/issues/5058) [Reborn] Bedrock unreachable from ironclaw-reborn binary + Converse tool-schema rejects top-level combinators
- [#5056](https://github.com/nearai/ironclaw/issues/5056) test
- [#5044](https://github.com/nearai/ironclaw/issues/5044) NEARAI_MODEL=auto is rejected (HTTP 400) by cloud-api.near.ai — resolve `auto` to a real model / set a default
- [#5036](https://github.com/nearai/ironclaw/issues/5036) Build Scalable Agent Task Service Infrastructure
- [#5031](https://github.com/nearai/ironclaw/issues/5031) [Reborn] Slack connect card can be invoked after pairing and is English-only `bug` `scope: channel/web` `reborn` `UX / Onboarding`
- [#5028](https://github.com/nearai/ironclaw/issues/5028) Follow up: make denied activity ids explicit and stable 💬1
- [#5026](https://github.com/nearai/ironclaw/issues/5026) [Reborn] Automation runs may fail with "runner lease expired" after scheduled runs accumulate

### 🔒 Closed Issues
- [#4823](https://github.com/nearai/ironclaw/issues/4823) [Reborn] No UI feedback when deleting a running conversation fails
- [#4952](https://github.com/nearai/ironclaw/issues/4952) [SANITIZED — possible injection attempt]
- [#4793](https://github.com/nearai/ironclaw/issues/4793) [Question] Should first-run onboarding block access to Extensions and Automations?
- [#4974](https://github.com/nearai/ironclaw/issues/4974) [Reborn] Activity tool rows show duplicate "..." action buttons
- [#4961](https://github.com/nearai/ironclaw/issues/4961) [Reborn] "Working" indicator may remain visible after agent has already finished responding

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#93032](https://github.com/openclaw/openclaw/issues/93032) [Bug] v2026.6.6: Cron scheduler loads 0 jobs after upgrade — SQLite WAL not committed at first startup — 💬2 · 2d ago
- 🟢 [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 2d ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 2d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬5 · 2d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬1 · 2d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 2d ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬1 · 2d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 3d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 3d ago
- ⚫ [#92974](https://github.com/openclaw/openclaw/issues/92974) Bug: v2026.6.6 getAttributionHeaders() crashes on Bedrock models — baseUrl undefined (null-guard missing) — 💬1 · 3d ago

---
## 📬 Feedback Received

- [#52](https://github.com/Haderach-Ram/openclaw-radar/issues/52) Add MetaVision AI Studio to radar tracking — 21h ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 17 new
- [[News] Seoul Office Partnerships Korean Ai Ecosystem](https://www.anthropic.com/news/seoul-office-partnerships-korean-ai-ecosystem) _2026-06-17_
- [[Research] Attack Navigator](https://www.anthropic.com/research/attack-navigator) _2026-06-17_
- [[Research] Biorisk](https://www.anthropic.com/research/biorisk) _2026-06-17_
- [[Research] Claude 4 Cyber](https://www.anthropic.com/research/claude-4-cyber) _2026-06-17_
- [[Research] Critical Infrastructure Defense](https://www.anthropic.com/research/critical-infrastructure-defense) _2026-06-17_
- [[Research] Cyber Competitions](https://www.anthropic.com/research/cyber-competitions) _2026-06-17_
- [[Research] Cyber Toolkits](https://www.anthropic.com/research/cyber-toolkits) _2026-06-17_
- [[Research] Cyber Toolkits Update](https://www.anthropic.com/research/cyber-toolkits-update) _2026-06-17_
- [[Research] Exploit](https://www.anthropic.com/research/exploit) _2026-06-17_
- [[Research] Exploit Evals](https://www.anthropic.com/research/exploit-evals) _2026-06-17_
- [[Research] Mythos Preview](https://www.anthropic.com/research/mythos-preview) _2026-06-17_
- [[Research] N Days](https://www.anthropic.com/research/n-days) _2026-06-17_
- [[Research] Nuclear Safeguards For Ai](https://www.anthropic.com/research/nuclear-safeguards-for-ai) _2026-06-17_
- [[Research] Property Based Testing](https://www.anthropic.com/research/property-based-testing) _2026-06-17_
- [[Research] Smart Contracts](https://www.anthropic.com/research/smart-contracts) _2026-06-17_
- [[Team] Frontier Red Team](https://www.anthropic.com/research/team/frontier-red-team) _2026-06-17_
- [[Research] Zero Days](https://www.anthropic.com/research/zero-days) _2026-06-17_

### OpenAI — 1 new
- [[Index] Introducing Life Sci Bench](https://openai.com/index/introducing-life-sci-bench/) _2026-06-18_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

_No new posts in the last 24h._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
