---
layout: post
title: "Ecosystem Digest — 2026-11-23"
date: 2026-11-23 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-23
*Generated 07:47 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 395,062 | 10 | 2 | 10 | 1 |
| **hermesagent** | 265,450 | 10 | 2 | 1 | 0 |
| **ZeroClaw** | 33,577 | 10 | 2 | 4 | 0 |
| **IronClaw** | 12,717 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,982 | 1 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 395,062 · **Open issues:** 8,892 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.11.7](https://github.com/openclaw/openclaw/releases/tag/v2026.11.7) — openclaw 2026.11.7

### ✅ Merged PRs
- [#203879](https://github.com/openclaw/openclaw/pull/203879) test(ui): measure the Gateway heading grid track
- [#203878](https://github.com/openclaw/openclaw/pull/203878) test(ui): ignore the clipped phone heading in access layout
- [#203874](https://github.com/openclaw/openclaw/pull/203874) fix(test): restore Slack download revocation checks
- [#198961](https://github.com/openclaw/openclaw/pull/198961) test(plugins): trim redundant metadata test plumbing
- [#203308](https://github.com/openclaw/openclaw/pull/203308) improve(ui): make theme background artwork opt-in
- [#203871](https://github.com/openclaw/openclaw/pull/203871) fix(macos): backport critical 2026.11.6 app repairs
- [#203868](https://github.com/openclaw/openclaw/pull/203868) fix(test): restore cron result copy checks
- [#201865](https://github.com/openclaw/openclaw/pull/201865) fix(memory): keep scope hashes stable across locales
- [#203847](https://github.com/openclaw/openclaw/pull/203847) refactor(gateway): check runtime and HTTP authority once at request start
- [#203862](https://github.com/openclaw/openclaw/pull/203862) test(gateway): exercise pairing and worker Stop commit fences

### 🐛 New Issues
- [#203886](https://github.com/openclaw/openclaw/issues/203886) [Bug]: New-session microphone starts dictation instead of voice conversation 💬1
- [#203884](https://github.com/openclaw/openclaw/issues/203884) Bug: configured Slack owner reply in bot-created thread is rejected as non-owner by privileged delegation `clawsweeper:intake:bug` 💬1
- [#203882](https://github.com/openclaw/openclaw/issues/203882) [Feature] Render approval-card ask text + block approvals without explanation + fix webchat intermediate-message loss `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:needs-info` `impact:security` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#203876](https://github.com/openclaw/openclaw/issues/203876) [Bug]: Browser xAI Talk repeatedly cuts off and does not follow up `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬8
- [#203875](https://github.com/openclaw/openclaw/issues/203875) Support deployment-managed skill mutations and source selection `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:other` 💬1
- [#203870](https://github.com/openclaw/openclaw/issues/203870) [Bug]: Authenticated Slack owner messages lose owner-only tool authority `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:needs-info` `impact:security` `issue-rating: 🦐 gold shrimp` 💬2
- [#203869](https://github.com/openclaw/openclaw/issues/203869) [Bug]:Tool execution fails: gRPC code-mode session closed / BrokenPipe `bug` `regression` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `P0` `issue-rating: 🦐 gold shrimp` `impact:ux-release-blocker` 💬1
- [#203863](https://github.com/openclaw/openclaw/issues/203863) Update failure: reconcile:abandoned (2026.11.6) `P2` `clawsweeper:needs-info` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#203842](https://github.com/openclaw/openclaw/issues/203842) [Bug]: Downloads always cancel when the Gateway runs in WSL2 and attaches to Windows Chrome over CDP (Linux downloadPath) `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬2
- [#203837](https://github.com/openclaw/openclaw/issues/203837) Update failure: package-doctor (2026.10.1) `P2` `clawsweeper:needs-info` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#203637](https://github.com/openclaw/openclaw/issues/203637) Agent DB: retained session actor hits 'execution admission is closed' (UNAVAILABLE) during compaction/turns
- [#201808](https://github.com/openclaw/openclaw/issues/201808) [Bug]: memory index scopeHash uses localeCompare on extraPaths — reindex from a CJK-locale terminal permanently disables memory_search ("index scope changed"), byte-exact repro

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬85 · 1d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 265,450 · **Open issues:** 54,346 · **Last push:** <1h ago

### ✅ Merged PRs
- [#157861](https://github.com/NousResearch/hermes-agent/pull/157861) plugin-catalog: update hermes-kame-api-rotation + hermes-kame-provider to 1.9.0.4

### 🐛 New Issues
- [#159065](https://github.com/NousResearch/hermes-agent/issues/159065) [Bug]: test_kanban_cli_dispatch_passthrough leaks hermes_cli modules into sys.modules, failing ~130 unrelated tests with the real-home guard `type/bug` `comp/cli` `P2`
- [#159061](https://github.com/NousResearch/hermes-agent/issues/159061) [Bug]: lefthook pre-commit template breaks on Windows — every commit needs --no-verify, skipping all lint `type/bug` `P3` `os/windows`
- [#159060](https://github.com/NousResearch/hermes-agent/issues/159060) [Bug]: Desktop — a failed session search renders as "No sessions match" with no re-auth prompt `type/bug` `area/auth` `P2` `comp/desktop` `area/sessions` `desktop/sessions`
- [#159059](https://github.com/NousResearch/hermes-agent/issues/159059) [Bug]: Desktop — Archived view does not cover the messaging sections, so archived threads are unreachable there `type/bug` `P2` `comp/desktop` `area/sessions` `desktop/sessions`
- [#159055](https://github.com/NousResearch/hermes-agent/issues/159055) [Bug][Desktop/SSH]: profile inventory lists marker-less and tombstoned dirs, spawning one isolated backend per leftover `type/perf` `P3` `comp/desktop` `area/profiles` `desktop/settings` `desktop/connection`
- [#159047](https://github.com/NousResearch/hermes-agent/issues/159047) kanban: dir/worktree task with no workspace path is accepted, then spawn_failed twice → gave_up `type/bug` `comp/cli` `comp/cron` `comp/plugins` `P2` 💬1
- [#159046](https://github.com/NousResearch/hermes-agent/issues/159046) Desktop (Windows): add opt-out for Start Menu / Desktop shortcut creation — installer and bootstrap/repair path currently re-create deleted shortcuts `type/feature` `area/config` `P3` `comp/desktop` `area/install-update` `os/windows` `desktop/shell` 💬1
- [#159043](https://github.com/NousResearch/hermes-agent/issues/159043) [Bug]: Removed credentials resurrect — stale processes re-upsert their full in-memory pool on every status transition, and rotation-revert re-selects deleted keys `type/bug` `comp/agent` `comp/cli` `area/auth` `P2` 💬1
- [#159039](https://github.com/NousResearch/hermes-agent/issues/159039) Boot home maintenance: state_db_guard's full integrity_check can block gateway startup for minutes on large state.db (non-deterministic, depends on lock race) `type/perf` `comp/cli` `P2` `area/sessions` `area/install-update`
- [#159038](https://github.com/NousResearch/hermes-agent/issues/159038) A bare 403 defaults to auth advice, so provider policy refusals read as a bad API key `type/bug` `comp/agent` `tool/file` `area/auth` `P2` `area/i18n` `provider/other`

### 🔒 Closed Issues
- [#131216](https://github.com/NousResearch/hermes-agent/issues/131216) [Bug]: A dependency-evicted plugin is left in both plugins.enabled and plugins.disabled, and nothing re-admits it after the dependency problem is fixed
- [#154612](https://github.com/NousResearch/hermes-agent/issues/154612) Bot Mode relay: deliveries into a Hermes Cloud agent are claimed by the Desktop app but never delivered (no error either side)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,577 · **Open issues:** 1,372 · **Last push:** <1h ago

### ✅ Merged PRs
- [#12635](https://github.com/zeroclaw-labs/zeroclaw/pull/12635) fix(gateway/web): keep voice settings changed elsewhere when one is saved
- [#12656](https://github.com/zeroclaw-labs/zeroclaw/pull/12656) fix(deps): update url and ruma for RUSTSEC-2026-0588, -0589 and -0592
- [#11104](https://github.com/zeroclaw-labs/zeroclaw/pull/11104) feat(providers): add Cheaper Inference model provider
- [#12519](https://github.com/zeroclaw-labs/zeroclaw/pull/12519) docs(runtime): record bounded channel progress localization

### 🐛 New Issues
- [#12669](https://github.com/zeroclaw-labs/zeroclaw/issues/12669) [Tracker]: Gemini provider modernization: Antigravity CLI provider, Gemini CLI and Code Assist OAuth retirement
- [#12668](https://github.com/zeroclaw-labs/zeroclaw/issues/12668) [Feature]: let an operator apply a bounded agentic delegate's own thinking level `enhancement`
- [#12667](https://github.com/zeroclaw-labs/zeroclaw/issues/12667) [Bug]: `/model <id>` replies "Model switched" but requests keep the profile's configured model `bug`
- [#12666](https://github.com/zeroclaw-labs/zeroclaw/issues/12666) [Bug]: `delegate` accepts an unknown argument and drops it without an error `bug`
- [#12665](https://github.com/zeroclaw-labs/zeroclaw/issues/12665) [Bug]: recovered tool results from damaged envelopes still omit name, so Groq replay fails
- [#12662](https://github.com/zeroclaw-labs/zeroclaw/issues/12662) [Feature]: Remove the unreachable Raspberry Pi LED tools from zeroclaw-hardware `enhancement`
- [#12661](https://github.com/zeroclaw-labs/zeroclaw/issues/12661) [Bug]: Dashboard sign-in "Generate" pairing-code button always gets 403 `bug`
- [#12660](https://github.com/zeroclaw-labs/zeroclaw/issues/12660) [Bug]: Agent cards' "this month" spend is all-time spend
- [#12655](https://github.com/zeroclaw-labs/zeroclaw/issues/12655) [Bug]: Autonomous skill creation never fires - extractor expects an OpenAI function wrapper, history stores flat tool calls, and output targets data/skills
- [#12649](https://github.com/zeroclaw-labs/zeroclaw/issues/12649) [Bug] Channel-routed tools are registered and approval-gated when their channel does not exist

### 🔒 Closed Issues
- [#11679](https://github.com/zeroclaw-labs/zeroclaw/issues/11679) [Feature]: zerocode obtains and stores its own bearer over the mTLS plane (auth parity with the gateway)
- [#12633](https://github.com/zeroclaw-labs/zeroclaw/issues/12633) [Bug]: A voice settings screen that hasn't refreshed can switch a device back to browser-service recognition

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,717 · **Open issues:** 1,575 · **Last push:** 13d ago

### 🐛 New Issues
- [#8172](https://github.com/nearai/ironclaw/issues/8172) [QA] Make PRIMARY_MODEL_CALL_IDLE_TIMEOUT configurable for slow local LLMs `qa-bug` 💬1

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,982 · **Open issues:** 123 · **Last push:** 30d ago

### 🐛 New Issues
- [#1326](https://github.com/moltis-org/moltis/issues/1326) MCP client only speaks protocol 2024-11-05; servers requiring 2025-06-18+ reject initialize (e.g. Basecamp)

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬5 · 2d ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 20d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 29d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 48d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 56d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 58d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 68d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 76d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 78d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 86d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [Please add a new rule: when you say "I can run X at Y" you also have to say what quant/bpw/size was used.](https://reddit.com/r/LocalLLaMA/comments/1y2oe1x/please_add_a_new_rule_when_you_say_i_can_run_x_at/) ↑593
- [Rumor: dissent in the qwen 4 ranks because not being released](https://reddit.com/r/LocalLLaMA/comments/1y32c42/rumor_dissent_in_the_qwen_4_ranks_because_not/) ↑133

### r/singularity — top 5 new
- [One of my greatest contributions to making Gemini Neon 4 better than Claude fable 5.2](https://reddit.com/r/singularity/comments/1y1zkd4/one_of_my_greatest_contributions_to_making_gemini/) ↑2608
- [The AI Community's Biggest Disagreement Captured In One Exchange](https://reddit.com/r/singularity/comments/1y31pza/the_ai_communitys_biggest_disagreement_captured/) ↑1745
- [GPT 6.2 Astra Confirmed As The Model That Solved Navier-Stokes.](https://reddit.com/r/singularity/comments/1y2xqfz/gpt_62_astra_confirmed_as_the_model_that_solved/) ↑800
- [a coordinated army of agents is trying to solve P = NP (livestreamed)](https://reddit.com/r/singularity/comments/1y30m1o/a_coordinated_army_of_agents_is_trying_to_solve_p/) ↑684
- [2026 in a nutshell](https://reddit.com/r/singularity/comments/1y2rla9/2026_in_a_nutshell/) ↑654

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Current Comparison of OC vs Claude Code with full shell/computer use?](https://reddit.com/r/openclaw/comments/1y2qpmy/current_comparison_of_oc_vs_claude_code_with_full/) ↑1
- [Do you think it is possible to run openclaw with an 8b local model?](https://reddit.com/r/openclaw/comments/1y2kopt/do_you_think_it_is_possible_to_run_openclaw_with/) ↑1

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [What does a lobster do at work? 🦞

While 
@OmarShahine
 was out of the office, his Autopilot, Sebastian, drafted 40 Team](https://x.com/openclaw/status/2124155892543217970)

### X — @steipete
_No new tweets since the last digest. Most recent:_
- [Landed a fix for that in OpenClaw yesterday (for the few folks using the embedded harness instead of codex, since it’s a](https://x.com/steipete/status/2123487048250327497)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
