---
layout: post
title: "Ecosystem Digest — 2026-07-04"
date: 2026-07-04 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-07-04
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 381,608 | 6 | 4 | 10 | 0 |
| **hermesagent** | 208,739 | 10 | 2 | 6 | 0 |
| **ZeroClaw** | 32,138 | 8 | 2 | 10 | 0 |
| **IronClaw** | 12,498 | 13 | 3 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 381,608 · **Open issues:** 7,031 · **Last push:** <1h ago

### ✅ Merged PRs
- [#99238](https://github.com/openclaw/openclaw/pull/99238) Expose channel preview warning doctor findings
- [#99370](https://github.com/openclaw/openclaw/pull/99370) fix(file-transfer): don't inline zero-byte files as image content blocks
- [#99658](https://github.com/openclaw/openclaw/pull/99658) feat(providers): add ClawRouter routing and quotas
- [#99736](https://github.com/openclaw/openclaw/pull/99736) fix(qa): prevent smoke gateways from losing built files
- [#99549](https://github.com/openclaw/openclaw/pull/99549) fix(auto-reply): don't block reply completion on transcript mirror
- [#99231](https://github.com/openclaw/openclaw/pull/99231) improve: native iOS look with stock SwiftUI navigation, forms, chat, and talk visualizer
- [#99705](https://github.com/openclaw/openclaw/pull/99705) improve(qa): execute runtime scenarios through Docker
- [#99676](https://github.com/openclaw/openclaw/pull/99676) refactor: consolidate string reader mechanics
- [#99722](https://github.com/openclaw/openclaw/pull/99722) fix: group agent session resume churns when messages toggle between @-mention and plain
- [#99721](https://github.com/openclaw/openclaw/pull/99721) refactor: consolidate async timing helpers

### 🐛 New Issues
- [#99762](https://github.com/openclaw/openclaw/issues/99762) MCP: render large JSON tool outputs as structured artifacts/previews
- [#99761](https://github.com/openclaw/openclaw/issues/99761) MCP: first-class pattern for read-only query registries
- [#99760](https://github.com/openclaw/openclaw/issues/99760) Control UI: tool-call rendering is visually heavy (triple-nested boxes, gradients, drop shadows) `enhancement` `maintainer` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` `maturity:stable` 💬1
- [#99732](https://github.com/openclaw/openclaw/issues/99732) Gateway crash: ERR_INVALID_STATE — FileHandle closed during GC (active-memory plugin session.jsonl.lock) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `impact:crash-loop` `issue-rating: 🐚 platinum hermit` `maturity:stable` 💬1
- [#99730](https://github.com/openclaw/openclaw/issues/99730) [Bug]: 2026.6.11 npm publish is broken — installs 2026.6.10 content `bug` `regression` `P2` `impact:other` `maturity:stable` 💬1
- [#99729](https://github.com/openclaw/openclaw/issues/99729) Structural: two-class CLI session reuse (soft resume on prompt drift, hard invalidate only on mechanical change) `enhancement` `agents` `maintainer` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#99758](https://github.com/openclaw/openclaw/issues/99758) [Feature]: feat: Add option to delete unnecessary chat sessions from sidebar
- [#99657](https://github.com/openclaw/openclaw/issues/99657) Add bundled ClawRouter models and quota integration
- [#99734](https://github.com/openclaw/openclaw/issues/99734) [Bug]: QA Smoke scripts can invalidate dist used by flow Gateways
- [#99195](https://github.com/openclaw/openclaw/issues/99195) [Feature]: native iOS reskin — replace custom "Pro" chrome with stock SwiftUI (HIG)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 208,739 · **Open issues:** 25,461 · **Last push:** 1h ago

### ✅ Merged PRs
- [#57969](https://github.com/NousResearch/hermes-agent/pull/57969) fix(desktop): fix scrollbar overlap and add tooltip on tool output copy button
- [#57924](https://github.com/NousResearch/hermes-agent/pull/57924) refactor(desktop): localize settled TODO(i18n) literals
- [#57685](https://github.com/NousResearch/hermes-agent/pull/57685) feat(gateway): add /sessions search <query>
- [#57590](https://github.com/NousResearch/hermes-agent/pull/57590) Capabilities page (Skills/Tools/MCP + Hub) + responsive overlay nav & mobile polish (desktop)
- [#57913](https://github.com/NousResearch/hermes-agent/pull/57913) feat(desktop): auto-scrolling window for long tool-call runs
- [#57902](https://github.com/NousResearch/hermes-agent/pull/57902) skills(unbroker): blind opt-out default, email fallback, PeopleConnect delete-wipes-suppression

### 🐛 New Issues
- [#58017](https://github.com/NousResearch/hermes-agent/issues/58017) [Bug]: Hermes treats SSE-encoded provider errors in HTTP 200 streams as assistant text `type/bug` `comp/agent` `provider/openai` `provider/qwen` `P2`
- [#58013](https://github.com/NousResearch/hermes-agent/issues/58013) [Bug]: Anthropic OAuth login: transient HTTP 429 on token exchange burns the single-use authorization code (no retry) `type/bug` `comp/agent` `provider/anthropic` `area/auth` `P2`
- [#58010](https://github.com/NousResearch/hermes-agent/issues/58010) AsyncSessionDB breaks /resume — missing await in slash_commands.py `type/bug` `duplicate` `comp/gateway` `P1` `sweeper:risk-session-state` 💬1
- [#58009](https://github.com/NousResearch/hermes-agent/issues/58009) Bug: Tool output replaced with <<ccr:...>> content reference tags when exceeding ~1KB threshold `type/bug` `comp/agent` `P2` `needs-repro` 💬1
- [#58005](https://github.com/NousResearch/hermes-agent/issues/58005) dashboard: SIGTERM ignored - systemctl stop always escalates to SIGKILL (no uvicorn timeout_graceful_shutdown, no force-exit on repeated SIGTERM) `type/bug` `P2` `comp/dashboard`
- [#57997](https://github.com/NousResearch/hermes-agent/issues/57997) [Bug]: Installing Hermes Desktop broke iTerm disk access and nvm usage `type/bug` `comp/cli` `P2` `needs-repro` `comp/desktop` `bug`
- [#57994](https://github.com/NousResearch/hermes-agent/issues/57994) terminal.container_disk cap is silently unenforced on common storage backends — config accepts a quota Docker never applies `type/bug` `backend/docker` `P2`
- [#57993](https://github.com/NousResearch/hermes-agent/issues/57993) Kanban auto-subscribe can leak notifications across profiles `type/bug` `comp/cron` `P3` `sweeper:risk-session-state`
- [#57988](https://github.com/NousResearch/hermes-agent/issues/57988) feat(desktop): Steer messages should appear at their chronological position, not at the end of the turn `type/feature` `P3` `comp/desktop`
- [#57986](https://github.com/NousResearch/hermes-agent/issues/57986) [Bug]: /journey crashes when a skill’s frontmatter metadata is not a dict `type/bug` `duplicate` `comp/agent` `tool/memory` `tool/skills` `P3` `bug` 💬1

### 🔒 Closed Issues
- [#48441](https://github.com/NousResearch/hermes-agent/issues/48441) [Security] Terminal session snapshots leak .env secrets to disk in plaintext (cache/terminal/hermes-snap-*.sh)
- [#51922](https://github.com/NousResearch/hermes-agent/issues/51922) Desktop shows bogus client update count in dirty shallow checkout

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,138 · **Open issues:** 455 · **Last push:** <1h ago

### ✅ Merged PRs
- [#8524](https://github.com/zeroclaw-labs/zeroclaw/pull/8524) fix(providers): omit empty assistant tool-call content in OpenAI-compatible requests
- [#8542](https://github.com/zeroclaw-labs/zeroclaw/pull/8542) chore(deps): bump wasmtime 43 -> 45.0.3 to clear three wasmtime-wasi CVEs (#8519)
- [#8658](https://github.com/zeroclaw-labs/zeroclaw/pull/8658) fix(skill_http): reject URL userinfo to close parser-level SSRF gap (rebased)
- [#8566](https://github.com/zeroclaw-labs/zeroclaw/pull/8566) feat(install): add --full flag to install everything
- [#8570](https://github.com/zeroclaw-labs/zeroclaw/pull/8570) feat(memory): epic A durable store seam (supersede/dedup/budget/policy-gate)
- [#8613](https://github.com/zeroclaw-labs/zeroclaw/pull/8613) docs(skills): add squash-merge freshness basis
- [#8604](https://github.com/zeroclaw-labs/zeroclaw/pull/8604) build(windows): statically link MSVC CRT for windows-msvc targets
- [#8507](https://github.com/zeroclaw-labs/zeroclaw/pull/8507) fix(runtime): seed full personality preset on agent creation
- [#8463](https://github.com/zeroclaw-labs/zeroclaw/pull/8463) fix(agent): cap interactive CLI stdin lines to 1 MiB
- [#8574](https://github.com/zeroclaw-labs/zeroclaw/pull/8574) test(skills): add regression tests for zip entries with lying declared sizes

### 🐛 New Issues
- [#8678](https://github.com/zeroclaw-labs/zeroclaw/issues/8678) [SANITIZED — possible injection attempt] `bug`
- [#8677](https://github.com/zeroclaw-labs/zeroclaw/issues/8677) [Feature]: Add uses_memory check box to web gateway `enhancement`
- [#8675](https://github.com/zeroclaw-labs/zeroclaw/issues/8675) [Bug]: Malformed native tool-call arguments sent unvalidated to OpenRouter/OpenAI-format providers → provider 400 → empty reply
- [#8664](https://github.com/zeroclaw-labs/zeroclaw/issues/8664) [Bug]: ZeroCode code-block Copy includes Markdown fences and highlights the message `bug` `priority:p2` `risk:medium` `zerocode`
- [#8654](https://github.com/zeroclaw-labs/zeroclaw/issues/8654) [Bug]: skill-review fork panics (out-of-range slice at skills/review.rs:159) → daemon SIGSEGV after tool-heavy turn `bug` `agent` `runtime` `skills` `priority:p1` `status:accepted` `risk:high` 💬1
- [#8653](https://github.com/zeroclaw-labs/zeroclaw/issues/8653) [Feature]: Auto-resume the most recent Code session on pane entry `enhancement` `priority:p3` `risk:medium` `zerocode`
- [#8652](https://github.com/zeroclaw-labs/zeroclaw/issues/8652) [Bug]: ZeroCode transcript highlight does not dismiss on blank side clicks `bug` `priority:p3` `zerocode` `risk:low`
- [#8650](https://github.com/zeroclaw-labs/zeroclaw/issues/8650) [Feature]: Show active resolved log path in ZeroCode diagnostics `enhancement` `config` `observability` `observability:log` `priority:p3` `zerocode` `risk:low`

### 🔒 Closed Issues
- [#7756](https://github.com/zeroclaw-labs/zeroclaw/issues/7756) [Bug]: native/MCP tools unavailable on OpenAI Responses/reasoning and Anthropic turns
- [#5542](https://github.com/zeroclaw-labs/zeroclaw/issues/5542) [Bug]: consecutive OOM in wsl2

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,498 · **Open issues:** 1,289 · **Last push:** <1h ago

### ✅ Merged PRs
- [#5567](https://github.com/nearai/ironclaw/pull/5567) refactor(types,traits): execute judged dedup backlog — 6 traits removed, 6 DTO clusters unified
- [#5625](https://github.com/nearai/ironclaw/pull/5625) feat(reborn): manifest-projected host-ingress route + fail-closed credential coherence
- [#5585](https://github.com/nearai/ironclaw/pull/5585) [codex] Refactor Reborn composition internals
- [#5624](https://github.com/nearai/ironclaw/pull/5624) Reborn #3231 follow-ups: extract host-runtime test harness + landing-policy doc
- [#5619](https://github.com/nearai/ironclaw/pull/5619) refactor(reborn_identity): de-slop — dead types, boundary rule, CONTRACT, error-path tests
- [#5622](https://github.com/nearai/ironclaw/pull/5622) feat(skills): add parallel-pr-review skill
- [#5620](https://github.com/nearai/ironclaw/pull/5620) docs: reference main, not staging, as the PR/integration branch
- [#5612](https://github.com/nearai/ironclaw/pull/5612) docs(commands): add /deslop-reborn de-slop loop command
- [#5607](https://github.com/nearai/ironclaw/pull/5607) Stabilize QA6 and QA8 live canary assertions
- [#5362](https://github.com/nearai/ironclaw/pull/5362) [codex] Harden Slack pairing activation flows

### 🐛 New Issues
- [#5618](https://github.com/nearai/ironclaw/issues/5618) ironclaw_reborn_identity: decide the ExternalIdentityKey + lookup/bind public surface (wire to Slack or drop) `question` `risk: low`
- [#5617](https://github.com/nearai/ironclaw/issues/5617) ironclaw_reborn_identity: login seam (OAuth route → WebuiUserDirectory → resolver) is tested only with fakes on both sides `bug` `risk: medium`
- [#5616](https://github.com/nearai/ironclaw/issues/5616) ironclaw_reborn_identity: adopt_migrated_identity never writes StoredUser and reverses the index/identity write order `bug` `risk: medium`
- [#5615](https://github.com/nearai/ironclaw/issues/5615) ironclaw_reborn_identity: bind() has no OAuth-surface guard (defense-in-depth) `bug` `risk: high`
- [#5614](https://github.com/nearai/ironclaw/issues/5614) ironclaw_reborn_identity: cross-process divergent-email logins can split a principal `bug` `risk: high`
- [#5608](https://github.com/nearai/ironclaw/issues/5608) reborn: retry path is unreachable for local-dev synthetic capabilities — reused input_ref fails staging check, collapsing retry contract into terminal driver_unavailable
- [#5605](https://github.com/nearai/ironclaw/issues/5605) reborn: memory prompt-context injection is unwired — ProductionMemoryPromptContextService never composed, memory_snippets always empty
- [#5603](https://github.com/nearai/ironclaw/issues/5603) CI red on main after engine-v2 removal: Docker Build missing prompts COPY + Clippy Windows unused import
- [#5602](https://github.com/nearai/ironclaw/issues/5602) Can't connect Slack from chat
- [#5595](https://github.com/nearai/ironclaw/issues/5595) Daily ironclaw failure taxonomy — 2026-07-03
- [#5590](https://github.com/nearai/ironclaw/issues/5590) Make main branch CI checks green again `bug` `scope: ci` `reborn`
- [#5588](https://github.com/nearai/ironclaw/issues/5588) reborn: track QA-discovered production follow-ups removed from PR #5380 `reborn`
- [#5583](https://github.com/nearai/ironclaw/issues/5583) reborn: hallucinated call to a disabled capability fails the run as model_error instead of a model-visible denial 💬1

### 🔒 Closed Issues
- [#3231](https://github.com/nearai/ironclaw/issues/3231) [Reborn] Follow-up architecture deepening after main substrate landing
- [#3087](https://github.com/nearai/ironclaw/issues/3087) [Reborn] Compose ironclaw_host_runtime services
- [#3068](https://github.com/nearai/ironclaw/issues/3068) [Reborn Cutover Blocker] Preserve brokered HTTP credential injection

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 8h ago
- 🟢 [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬2 · 1d ago
- 🟢 [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬2 · 3d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 4d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 4d ago
- ⚫ [#94780](https://github.com/openclaw/openclaw/issues/94780) [Feature]: Per-cron model selection independent of agent default — run cheap/free models on automation jobs while keeping main agent on premium LLM — 💬1 · 8d ago
- ⚫ [#93032](https://github.com/openclaw/openclaw/issues/93032) [Bug] v2026.6.6: Cron scheduler loads 0 jobs after upgrade — SQLite WAL not committed at first startup — 💬2 · 8d ago
- ⚫ [#92974](https://github.com/openclaw/openclaw/issues/92974) Bug: v2026.6.6 getAttributionHeaders() crashes on Bedrock models — baseUrl undefined (null-guard missing) — 💬1 · 8d ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬4 · 10d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬7 · 11d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Visible Extended Thinking](https://www.anthropic.com/news/visible-extended-thinking) _2026-07-03_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [GLM5.2 on 5x Pro 6000s and a 5090, an expensive journey](https://reddit.com/r/LocalLLaMA/comments/1umcr5m/glm52_on_5x_pro_6000s_and_a_5090_an_expensive/) ↑967
- [Deepseek drops another HUGE breakthrough - DSpark. Waaay faster than MTP [Video explaining it]](https://reddit.com/r/LocalLLaMA/comments/1um9j5q/deepseek_drops_another_huge_breakthrough_dspark/) ↑589
- [Mistral released Leanstral-1.5-119B-A6B](https://reddit.com/r/LocalLLaMA/comments/1umgdhx/mistral_released_leanstral15119ba6b/) ↑487
- [Palantir is a free org on HF with 0 open-source models and 0 public datasets shared](https://reddit.com/r/LocalLLaMA/comments/1umbw0v/palantir_is_a_free_org_on_hf_with_0_opensource/) ↑474
- [Follow-up: DeepSeek V4 Flash on 2x RTX PRO 6000 finishes real coding tasks faster than Sonnet and Opus, at about Sonnet quality](https://reddit.com/r/LocalLLaMA/comments/1um84bd/followup_deepseek_v4_flash_on_2x_rtx_pro_6000/) ↑248

### r/singularity — top 2 new
- [Came across this on X. Thought it was pretty accurate.](https://reddit.com/r/singularity/comments/1umg3u3/came_across_this_on_x_thought_it_was_pretty/) ↑2976
- [Noetix is another player in the robotic faces space](https://reddit.com/r/singularity/comments/1umm06c/noetix_is_another_player_in_the_robotic_faces/) ↑158

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [AgentTransfer: OpenSource DropBox for Agents - get agents to share files and talk / work together on projects](https://reddit.com/r/openclaw/comments/1umo47i/agenttransfer_opensource_dropbox_for_agents_get/) ↑109
- [Deepseek price hike - Flash was the one genuinely cheap model that didn't suck. That's the part that worries me about V4.](https://reddit.com/r/openclaw/comments/1uiq29y/deepseek_price_hike_flash_was_the_one_genuinely/) ↑38
- [Claw Voice makes OpenClaw personal](https://reddit.com/r/openclaw/comments/1um9k26/claw_voice_makes_openclaw_personal/) ↑29
- [🦞 Peter Just Torched the “OpenAI Owns OpenClaw” Conspiracy on Clawcast… Can We Finally Cut the BS](https://reddit.com/r/openclaw/comments/1umr8mc/peter_just_torched_the_openai_owns_openclaw/) ↑9
- [Improve UI/UX quality](https://reddit.com/r/openclaw/comments/1umh9kr/improve_uiux_quality/) ↑7

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
- [This argument is getting old. computer automation needs surprisingly little token. try it.](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
