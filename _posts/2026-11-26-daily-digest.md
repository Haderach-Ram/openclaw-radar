---
layout: post
title: "Ecosystem Digest — 2026-11-26"
date: 2026-11-26 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-26
*Generated 07:47 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 395,233 | 7 | 6 | 10 | 2 |
| **hermesagent** | 266,135 | 10 | 2 | 5 | 1 |
| **ZeroClaw** | 33,624 | 6 | 3 | 9 | 0 |
| **IronClaw** | 12,722 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,989 | 1 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 395,233 · **Open issues:** 9,207 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.11.10](https://github.com/openclaw/openclaw/releases/tag/v2026.11.10) — openclaw 2026.11.10
- [v2026.10.34](https://github.com/openclaw/openclaw/releases/tag/v2026.10.34) — openclaw 2026.10.34

### ✅ Merged PRs
- [#205679](https://github.com/openclaw/openclaw/pull/205679) fix(test): unblock restart-auth plugin and worker publication qualification
- [#205691](https://github.com/openclaw/openclaw/pull/205691) chore(ui): refresh control ui locales
- [#201064](https://github.com/openclaw/openclaw/pull/201064) fix: reduce memory during SQLite usage refresh
- [#205266](https://github.com/openclaw/openclaw/pull/205266) fix(plugins): readmit native captures with a dangling host link
- [#205680](https://github.com/openclaw/openclaw/pull/205680) chore(i18n): refresh native locales
- [#204881](https://github.com/openclaw/openclaw/pull/204881) fix: keep daily skill maintenance running when a learned skill has Markdown files outside its support folders
- [#205668](https://github.com/openclaw/openclaw/pull/205668) fix(update): hash SQLite lock bytes as zeros so Windows exclusion cannot fail verification
- [#205655](https://github.com/openclaw/openclaw/pull/205655) fix: keep the resident launcher when reinstalling Gateway
- [#200932](https://github.com/openclaw/openclaw/pull/200932) fix(plugins): clarify dated SDK migration notices
- [#200455](https://github.com/openclaw/openclaw/pull/200455) fix: show the whole reply when you reopen a TUI session

### 🐛 New Issues
- [#205695](https://github.com/openclaw/openclaw/issues/205695) [Bug]: Manual upgrade 2026.10.8 → 2026.11.10 cannot finish on an explicit multi-agent config: Doctor falls back to a default config without the systemAgent owner, so the legacy/heartbeat config write  `clawsweeper:intake:bug` 💬1
- [#205694](https://github.com/openclaw/openclaw/issues/205694) [Bug]: 2026.11.10 cannot start: state upgrade stops at agent-schema with "no such module: vec0" (schema 23, expected 42) `bug` `regression` `clawsweeper:intake:bug` 💬1
- [#205684](https://github.com/openclaw/openclaw/issues/205684) [Bug]: Git upgrade reports unprepared cursor-cli Doctor source during automation account migration `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:auth-provider` `issue-rating: 🦪 silver shellfish` 💬1
- [#205683](https://github.com/openclaw/openclaw/issues/205683) Knowledge plugin: Control UI panel not registered (2026.11.10); tools need allow-list + restart `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬2
- [#205672](https://github.com/openclaw/openclaw/issues/205672) [Bug]: plugin policy is read by hand in three places, so the doctor scan and /tools notice disagree with what actually loads `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:security` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#205667](https://github.com/openclaw/openclaw/issues/205667) [Bug]: knowledge_grep never matches CJK words inside a sentence (FTS5 unicode61 has no CJK segmentation) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#205660](https://github.com/openclaw/openclaw/issues/205660) [Bug]: Cron jobs that target a conversation (session:<key>) end their turn on the first message-tool send; isolated jobs to the same target do not `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#204737](https://github.com/openclaw/openclaw/issues/204737) [Bug]: Skill Workshop daily maintenance aborts before its skip handler on learned skills with root-level support files (diet, undo and restore all fail)
- [#190536](https://github.com/openclaw/openclaw/issues/190536) Plugin compatibility notices cite retirement dates that have already passed, and still say "keeps working until then"
- [#205617](https://github.com/openclaw/openclaw/issues/205617) Bug: gateway install replaces the resident launcher with a release-slot entry after conversion
- [#200408](https://github.com/openclaw/openclaw/issues/200408) [Bug]: TUI shows replies over 8,000 characters cut with "...(truncated)..." after reopening a session
- [#205642](https://github.com/openclaw/openclaw/issues/205642) Provider prompt-image handoff drops the image size limits, so `imageMaxDimensionPx: 2400` still resized at 1200 and two JPEGs came back larger than their source
- [#205678](https://github.com/openclaw/openclaw/issues/205678) Update 2026.11.6 → 2026.11.10 fails at candidate-doctor: Agent database resources are closing

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬87 · 1d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 266,135 · **Open issues:** 54,586 · **Last push:** <1h ago

### 🚀 New Releases
- [canary.20261125T064800Z-v0.23.4](https://github.com/NousResearch/hermes-agent/releases/tag/canary.20261125T064800Z-v0.23.4) — Hermes Agent canary canary.20261125T064800Z-v0.23.4

### ✅ Merged PRs
- [#160195](https://github.com/NousResearch/hermes-agent/pull/160195) docs(delegation): describe delegate_task as the code runs it
- [#159126](https://github.com/NousResearch/hermes-agent/pull/159126) ci(install-e2e): gate bundle-inputs on manifests or bundled routes
- [#160201](https://github.com/NousResearch/hermes-agent/pull/160201) refactor(providers): decouple Gemini core seams and consolidate bundled provider plugin
- [#158696](https://github.com/NousResearch/hermes-agent/pull/158696) fix(plugin-catalog): re-pin severian to ac020bc (v0.6.4)
- [#159941](https://github.com/NousResearch/hermes-agent/pull/159941) test(desktop): fire the retry test's second move when the first lookup fails

### 🐛 New Issues
- [#160264](https://github.com/NousResearch/hermes-agent/issues/160264) Gateway boot: failed launch-authority build calls registry.remove() on the launch slot, masking the real error `type/bug` `comp/gateway` `P2` `area/sessions`
- [#160261](https://github.com/NousResearch/hermes-agent/issues/160261) [Bug]: macOS setup app (Hermes-Setup) still ships hardcoded 0.0.1 in Info.plist — regression of #107177 (v0.21.2) `type/bug` `P2` `area/install-update` `os/macos`
- [#160255](https://github.com/NousResearch/hermes-agent/issues/160255) pm.activate() computes the venv verdict under the bare tools interpreter and reports 'install out of sync' on a healthy install (ModuleNotFoundError: ruamel) `type/bug` `comp/cli` `P2`
- [#160254](https://github.com/NousResearch/hermes-agent/issues/160254) Telegram approval cards skip RetryAfter; a failed text fallback looks like user silence `type/bug` `comp/gateway` `comp/plugins` `platform/telegram` `P2`
- [#160249](https://github.com/NousResearch/hermes-agent/issues/160249) [Bug]: Nix install warns "install out of sync (ffmpeg, node, npm, ripgrep)" on every dispatch though the pinned builds are on PATH `type/bug` `comp/cli` `P3` `area/install-update`
- [#160244](https://github.com/NousResearch/hermes-agent/issues/160244) Pages deploy wait step: a duplicate artifact listing counts as ready, and the last sleep overruns the 120 s budget `type/bug` `P2`
- [#160241](https://github.com/NousResearch/hermes-agent/issues/160241) [Bug]: Plugin injection and startup auto-resume refuse every Telegram DM thread a cron delivery opened: its stored origin keeps user_id system:cron
- [#160239](https://github.com/NousResearch/hermes-agent/issues/160239) [Bug]: cron deliver='bot-chat' shows the agent-facing framing line ("scheduled job, not the user…") verbatim to the human in the shared Bot Chat
- [#160238](https://github.com/NousResearch/hermes-agent/issues/160238) Background-process notifications don't tell the agent it may reply [SILENT], so every completion produces a visible status message `type/bug` `comp/gateway` `tool/terminal` `P2`
- [#160237](https://github.com/NousResearch/hermes-agent/issues/160237) [Feature]: Name the Messaging Clear control for screen readers in Hermes Desktop `type/feature` `area/auth` `P3` `comp/desktop` `desktop/settings`

### 🔒 Closed Issues
- [#159964](https://github.com/NousResearch/hermes-agent/issues/159964) WebApp in iOS home-screen standalone mode: tapping the top-left/top-right panel toggle icons reloads the whole page
- [#152181](https://github.com/NousResearch/hermes-agent/issues/152181) [Bug]:

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,624 · **Open issues:** 1,247 · **Last push:** <1h ago

### ✅ Merged PRs
- [#12345](https://github.com/zeroclaw-labs/zeroclaw/pull/12345) fix(rpc): rehydrate reaped ACP sessions on provider switch
- [#12643](https://github.com/zeroclaw-labs/zeroclaw/pull/12643) fix(log): remove the rolling trim's temp file on failure and skip the startup directory scan
- [#12168](https://github.com/zeroclaw-labs/zeroclaw/pull/12168) fix(tools): enforce Act policy on send_message_to_peer
- [#12479](https://github.com/zeroclaw-labs/zeroclaw/pull/12479) fix(providers): send drop_block so edited history no longer fails Anthropic thinking requests
- [#12706](https://github.com/zeroclaw-labs/zeroclaw/pull/12706) ci(platform-tests): fix the macOS install and timeout and the Windows test fixtures
- [#11862](https://github.com/zeroclaw-labs/zeroclaw/pull/11862) feat(channels): add optional Telegram rich messages
- [#11717](https://github.com/zeroclaw-labs/zeroclaw/pull/11717) feat(config): add optional model to local Whisper transcription
- [#12708](https://github.com/zeroclaw-labs/zeroclaw/pull/12708) docs(runtime): record the approval of the #12609 refresh-grant row
- [#12376](https://github.com/zeroclaw-labs/zeroclaw/pull/12376) fix(web): show a detached chat turn and load its answer when it ends

### 🐛 New Issues
- [#12712](https://github.com/zeroclaw-labs/zeroclaw/issues/12712) [Tracker]: Roadmap to v1.0.0 `status:no-stale` `type:tracker` 💬1
- [#12710](https://github.com/zeroclaw-labs/zeroclaw/issues/12710) [Bug]: Containerfile `check` stage: the test step fails in the StageX image, and no workflow builds the stage `bug`
- [#12709](https://github.com/zeroclaw-labs/zeroclaw/issues/12709) [Feature]: Add native local Turso as an opt-in memory backend
- [#12707](https://github.com/zeroclaw-labs/zeroclaw/issues/12707) [Tracker]: Daemon-held OIDC refresh grants for device sessions (ADR-017) `enhancement` `domain:security` `risk:high` `type:tracker` `topic:identity-access`
- [#12703](https://github.com/zeroclaw-labs/zeroclaw/issues/12703) Email channel: live-processed messages stay UNSEEN, so every restart re-answers the backlog 💬1
- [#12697](https://github.com/zeroclaw-labs/zeroclaw/issues/12697) [Tracker]: Split zeroclaw-runtime into smaller crates `runtime` `domain:architecture` `status:no-stale` `type:tracker` 💬3

### 🔒 Closed Issues
- [#12167](https://github.com/zeroclaw-labs/zeroclaw/issues/12167) [Bug]: send_message_to_peer ignores the sender's autonomy level and action budget
- [#8415](https://github.com/zeroclaw-labs/zeroclaw/issues/8415) [Feature]: Implement Telegram Bot API 10.1 Rich Messages
- [#12107](https://github.com/zeroclaw-labs/zeroclaw/issues/12107) [Task]: show a detached chat turn's answer when the socket reopens before the turn ends

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,722 · **Open issues:** 1,575 · **Last push:** 16d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,989 · **Open issues:** 125 · **Last push:** 33d ago

### 🐛 New Issues
- [#1328](https://github.com/moltis-org/moltis/issues/1328) Agent cannot read PDF text in a sandboxed session

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬5 · 5d ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 23d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 32d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 51d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 59d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 61d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 71d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 79d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 81d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 89d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Research] Migrating Api To Rust](https://www.anthropic.com/research/migrating-api-to-rust) _2026-11-25_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [another cut of nvidia gpu](https://reddit.com/r/LocalLLaMA/comments/1y5blyd/another_cut_of_nvidia_gpu/) ↑704
- [Latency doesn't lie: Jev is (probably) Qwen3.5-35B-A3B!](https://reddit.com/r/LocalLLaMA/comments/1y5nllv/latency_doesnt_lie_jev_is_probably_qwen3535ba3b/) ↑104

### r/singularity — top 5 new
- [Singularity for me not for thee](https://reddit.com/r/singularity/comments/1y5bv5v/singularity_for_me_not_for_thee/) ↑2496
- [OpenAI claims to have solved one of the biggest open problems in computer science: the exact speed limit of matrix multiplication is 9/4 (2.25), shattering the decades-old ω = 2 conjecture.](https://reddit.com/r/singularity/comments/1y517t1/openai_claims_to_have_solved_one_of_the_biggest/) ↑2433
- [Anthropic has achieved a remarkable 99.56% reduction in the formalization of the Riemann Hypothesis in Lean](https://reddit.com/r/singularity/comments/1y5k855/anthropic_has_achieved_a_remarkable_9956/) ↑1020
- [Rumor that OpenAI or Anthropic found a way to break RSA encryption reaches ACM Prize–winning UT Austin professor Scott Aaronson, AI tipster Andrew Curran (who flagged the Navier–Stokes rumors early), ](https://reddit.com/r/singularity/comments/1y59ef1/rumor_that_openai_or_anthropic_found_a_way_to/) ↑607
- [One prompt, no human help: Google's AI took on math problems open since 1964 and 1988 and says it has lean proofs for all six](https://reddit.com/r/singularity/comments/1y5635t/one_prompt_no_human_help_googles_ai_took_on_math/) ↑482

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw 2026.11.10 brings built-in Deep Research, the new Knowledge memory system, and Browser handoff](https://reddit.com/r/openclaw/comments/1y587gq/openclaw_20261110_brings_builtin_deep_research/) ↑47
- [My Openclaw now calls my phone when it needs me. No Twilio, no phone number, free](https://reddit.com/r/openclaw/comments/1y53mcs/my_openclaw_now_calls_my_phone_when_it_needs_me/) ↑34
- [We're heading to Shenzhen for ClawCon on Sunday, Dec 6](https://reddit.com/r/openclaw/comments/1y4vybe/were_heading_to_shenzhen_for_clawcon_on_sunday/) ↑12
- [Smallest local llm for general openclaw use](https://reddit.com/r/openclaw/comments/1y5md97/smallest_local_llm_for_general_openclaw_use/) ↑4
- [Job Hunting and Using Voice in OpenClaw](https://reddit.com/r/openclaw/comments/1y5pa92/job_hunting_and_using_voice_in_openclaw/) ↑1

### X — @openclaw
_No tweets found on profile (fetch may have failed)._

### X — @steipete
_No tweets found on profile (fetch may have failed)._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
