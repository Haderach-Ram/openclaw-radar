---
layout: post
title: "Ecosystem Digest — 2026-11-14"
date: 2026-11-14 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-14
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 394,400 | 10 | 3 | 10 | 0 |
| **hermesagent** | 263,232 | 4 | 9 | 10 | 1 |
| **ZeroClaw** | 33,356 | 7 | 0 | 1 | 0 |
| **IronClaw** | 12,715 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,959 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 394,400 · **Open issues:** 8,164 · **Last push:** <1h ago

### ✅ Merged PRs
- [#198566](https://github.com/openclaw/openclaw/pull/198566) improve(sessions): reuse list selections after usage updates
- [#197922](https://github.com/openclaw/openclaw/pull/197922) feat(update): new releases run their own pre-update rehearsal
- [#198564](https://github.com/openclaw/openclaw/pull/198564) perf(sessions): skip unused cached child clock views
- [#198481](https://github.com/openclaw/openclaw/pull/198481) fix: show plugin-delivered images in Control UI
- [#196951](https://github.com/openclaw/openclaw/pull/196951) feat(agents): support required manual-step handoffs in chat
- [#197633](https://github.com/openclaw/openclaw/pull/197633) fix(sessions): avoid transcript overreads when recovering nested tool activity
- [#198510](https://github.com/openclaw/openclaw/pull/198510) fix(ci): unused exports fail the dependency check
- [#198372](https://github.com/openclaw/openclaw/pull/198372) fix(google-meet): cancel interrupted status, transcript and doctor reads
- [#198544](https://github.com/openclaw/openclaw/pull/198544) fix(ci): keep the model picker target helper private
- [#198511](https://github.com/openclaw/openclaw/pull/198511) chore(postgres): qualify notice transcript crash recovery

### 🐛 New Issues
- [#198573](https://github.com/openclaw/openclaw/issues/198573) [Docs Bug]: claude-cli docs say skills load via a --plugin-dir plugin, but managed turns load no Claude skills `no-stale` `P3` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#198569](https://github.com/openclaw/openclaw/issues/198569) Desktop companions: open identity-only ClawHub catalog review links `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:linked-pr-open` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1
- [#198559](https://github.com/openclaw/openclaw/issues/198559) [Bug]: `templates validate` accepts a `BOOTSTRAP.md` that `templates build` rejects `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#198558](https://github.com/openclaw/openclaw/issues/198558) [Bug]: No CLI way to continue a Template agent kept after a failed Gateway Add `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#198556](https://github.com/openclaw/openclaw/issues/198556) [Bug]: `templates add @publisher/slug` hides why a downloaded Template manifest is invalid `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#198554](https://github.com/openclaw/openclaw/issues/198554) [Bug]: Invalid Template MCP declarations report only "Invalid input" `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#198551](https://github.com/openclaw/openclaw/issues/198551) [Bug]: `templates add` prints "Added agent" when the Add failed and was rolled back `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#198549](https://github.com/openclaw/openclaw/issues/198549) [Feature]: Make Usage JSON exports self-describing with report context `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#198548](https://github.com/openclaw/openclaw/issues/198548) [Bug]: Template publish that fails before upload locks the review card as "Submission unconfirmed" `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#198543](https://github.com/openclaw/openclaw/issues/198543) agents.delete waits for unrelated model-catalog work in every worker; hourly CI times out on it `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1

### 🔒 Closed Issues
- [#156548](https://github.com/openclaw/openclaw/issues/156548) [Bug]: Plugin toolContext.delivery.send media does not appear in Control UI
- [#196643](https://github.com/openclaw/openclaw/issues/196643) [Bug]: Template review drops the CLAW.md description and rewrites the agent name when publishing from chat
- [#198363](https://github.com/openclaw/openclaw/issues/198363) CI: reduce repeated traversal in the database-worker ratchet

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬81 · 2d ago
- [#116201](https://github.com/openclaw/openclaw/issues/116201) Realtime voice work can retain unbounded provider and consult state — 💬59 · 42d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 263,232 · **Open issues:** 53,232 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.23.1+canary.20261113T064447Z](https://github.com/NousResearch/hermes-agent/releases/tag/v0.23.1%2Bcanary.20261113T064447Z) — Hermes Agent canary v0.23.1+canary.20261113T064447Z

### ✅ Merged PRs
- [#155289](https://github.com/NousResearch/hermes-agent/pull/155289) fix(redact): mask ANSI-wrapped and Unicode-glued tokens in prefix and Bearer sweeps
- [#155288](https://github.com/NousResearch/hermes-agent/pull/155288) [SANITIZED — possible injection attempt]
- [#155284](https://github.com/NousResearch/hermes-agent/pull/155284) fix(skills): always scan background-review skill writes
- [#155279](https://github.com/NousResearch/hermes-agent/pull/155279) fix(terminal): keep a delegated child's shell exports out of its parent
- [#155272](https://github.com/NousResearch/hermes-agent/pull/155272) fix(cli): drop raw interrupt_debug.log writes that persisted typed input unredacted
- [#155271](https://github.com/NousResearch/hermes-agent/pull/155271) fix(kanban): keep worker logs out of world read; redact the booked reply
- [#155270](https://github.com/NousResearch/hermes-agent/pull/155270) fix(config): drop world access on every config.yaml write
- [#155251](https://github.com/NousResearch/hermes-agent/pull/155251) fix(approval): cover profile homes in the Hermes config/env write rules
- [#155241](https://github.com/NousResearch/hermes-agent/pull/155241) fix(file-safety): casefold credential deny checks on macOS and Windows
- [#155221](https://github.com/NousResearch/hermes-agent/pull/155221) fix(webhook): mask the HMAC secret in `hermes webhook subscribe` output

### 🐛 New Issues
- [#155416](https://github.com/NousResearch/hermes-agent/issues/155416) [Bug] disk-cleanup plugin: concurrent post_tool_call hooks race on shared `.tmp` / `.bak` (no lock) `type/bug` `comp/plugins` `P2`
- [#155410](https://github.com/NousResearch/hermes-agent/issues/155410) [Bug]: Webapp read-aloud speaks operational interruption notices as assistant replies `type/bug` `comp/agent` `tool/tts` `P2`
- [#155409](https://github.com/NousResearch/hermes-agent/issues/155409) [Bug]: Android Webapp/PWA clipboard image paste does not attach an image `type/bug` `P2` `comp/desktop`
- [#155393](https://github.com/NousResearch/hermes-agent/issues/155393) [Bug]: scratch prune kills live read-only processes (e.g. 1Password op daemon): idleness is mtime-only and reap_processes_rooted_in ignores open files `type/bug` `P2`

### 🔒 Closed Issues
- [#81073](https://github.com/NousResearch/hermes-agent/issues/81073) [Bug]: gateway: _GATEWAY_SECRET_PATTERNS \b anchors miss CJK/Unicode-glued tokens on fallback path
- [#81012](https://github.com/NousResearch/hermes-agent/issues/81012) redact: complete CSI/SGR sequences defeat prefix masking (ESC-byte-only stripping leaves 'm'-glue)
- [#43666](https://github.com/NousResearch/hermes-agent/issues/43666) Redaction gaps at the persistence boundary: tool output file dumps, compaction blocks, DB URIs (split from #43083)
- [#78515](https://github.com/NousResearch/hermes-agent/issues/78515) [SANITIZED — possible injection attempt]
- [#84536](https://github.com/NousResearch/hermes-agent/issues/84536) [SANITIZED — possible injection attempt]
- [#75461](https://github.com/NousResearch/hermes-agent/issues/75461) [SANITIZED — possible injection attempt]
- [#63594](https://github.com/NousResearch/hermes-agent/issues/63594) [SANITIZED — possible injection attempt]
- [#59726](https://github.com/NousResearch/hermes-agent/issues/59726) [SANITIZED — possible injection attempt]
- [#79030](https://github.com/NousResearch/hermes-agent/issues/79030) [SANITIZED — possible injection attempt]

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,356 · **Open issues:** 1,213 · **Last push:** 4h ago

### ✅ Merged PRs
- [#12419](https://github.com/zeroclaw-labs/zeroclaw/pull/12419) chore(deps): bump quinn-udp to 0.5.16 for RUSTSEC-2026-0538

### 🐛 New Issues
- [#12422](https://github.com/zeroclaw-labs/zeroclaw/issues/12422) RFC: Scoped use of operator-managed service credentials
- [#12421](https://github.com/zeroclaw-labs/zeroclaw/issues/12421) perf(cron): agent cron jobs run outside any session-key scope, so they get no provider prompt-cache affinity
- [#12416](https://github.com/zeroclaw-labs/zeroclaw/issues/12416) [Feature]: ADR-016 holding-crate exception for host-mediated WASM plugin wake dispatch (zeroclaw-runtime) `enhancement`
- [#12415](https://github.com/zeroclaw-labs/zeroclaw/issues/12415) Dashboard sign-out should support OIDC RP-initiated logout (end_session_endpoint)
- [#12413](https://github.com/zeroclaw-labs/zeroclaw/issues/12413) [Bug]: OpenCode Go context-window discovery returns no capacity `bug`
- [#12412](https://github.com/zeroclaw-labs/zeroclaw/issues/12412) [Bug]: OpenCode Go uses Zen's model catalogue `bug`
- [#12373](https://github.com/zeroclaw-labs/zeroclaw/issues/12373) [Feature]: Write-only WebUI credential management and scoped secret references 💬1

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,715 · **Open issues:** 1,571 · **Last push:** 4d ago

### 🐛 New Issues
- [#8170](https://github.com/nearai/ironclaw/issues/8170) ci: add GitHub's workflow lockfile (actions.lock), two pins to refresh first

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,959 · **Open issues:** 121 · **Last push:** 21d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬4 · 1d ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 11d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 20d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 39d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 47d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 49d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 59d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 67d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 69d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 77d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Research] Building Strong Safety Evaluations](https://www.anthropic.com/research/building-strong-safety-evaluations) _2026-11-13_

### OpenAI — 3 new
- [[Policies] Chatgpt Wallet Privacy Notice](https://openai.com/policies/chatgpt-wallet-privacy-notice/) _2026-11-14_
- [[Customer-Stories] Shield](https://openai.com/business/customer-stories/shield/) _2026-11-14_
- [[Policies] Chatgpt Wallet Terms](https://openai.com/policies/chatgpt-wallet-terms/) _2026-11-13_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Jensen Huang's mistake was being too pro LocalAI, which was a threat to companies like ClosedAI and Anthropic which are about to go IPO](https://reddit.com/r/LocalLLaMA/comments/1xujb7c/jensen_huangs_mistake_was_being_too_pro_localai/) ↑2871
- [Stories coming out about Jensen](https://reddit.com/r/LocalLLaMA/comments/1xuvexw/stories_coming_out_about_jensen/) ↑2854
- [‘Bring Back THE Boss’: Nvidia Employees Petition for Jensen Huang’s Return](https://reddit.com/r/LocalLLaMA/comments/1xuxxmb/bring_back_the_boss_nvidia_employees_petition_for/) ↑1886
- [So this will be true in couple of years?](https://reddit.com/r/LocalLLaMA/comments/1xukt9t/so_this_will_be_true_in_couple_of_years/) ↑1737
- [llama.cpp v1.0 is here 🦙](https://reddit.com/r/LocalLLaMA/comments/1xv8t2e/llamacpp_v10_is_here/) ↑1421

### r/singularity — top 2 new
- [Huang: The Game](https://reddit.com/r/singularity/comments/1xva8yj/huang_the_game/) ↑2532
- [The FAA rolled out its $875 million AI Air Traffic tool today with reassurances it would not affect safety](https://reddit.com/r/singularity/comments/1xvl00y/the_faa_rolled_out_its_875_million_ai_air_traffic/) ↑1009

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [2026.11.x has been fantastic](https://reddit.com/r/openclaw/comments/1xuxhkz/202611x_has_been_fantastic/) ↑54
- [Free golf tee time finder app](https://reddit.com/r/openclaw/comments/1xvlfu3/free_golf_tee_time_finder_app/) ↑3

### X — @openclaw
- [Gemini 4 Hydrogen is out and you can already use it in OpenClaw! 🦞


https://
x.com/OfficialLoganK
/status/2120940951292](https://x.com/openclaw/status/2121098531205501401) ↑0 🔁0 · recent


### X — @steipete
_No new tweets since the last digest. Most recent:_
- [My team wrote about how we run persistent agents inside OpenAI.](https://x.com/steipete/status/2121058770767982997)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
