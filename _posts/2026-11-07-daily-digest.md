---
layout: post
title: "Ecosystem Digest — 2026-11-07"
date: 2026-11-07 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-07
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 394,077 | 8 | 0 | 10 | 0 |
| **hermesagent** | 261,224 | 10 | 1 | 10 | 0 |
| **ZeroClaw** | 33,147 | 6 | 5 | 10 | 0 |
| **IronClaw** | 12,713 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,942 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 394,077 · **Open issues:** 7,654 · **Last push:** <1h ago

### ✅ Merged PRs
- [#194407](https://github.com/openclaw/openclaw/pull/194407) fix(ci): preserve worker reuse when test caches grow
- [#194405](https://github.com/openclaw/openclaw/pull/194405) test(ui): wait for configured provider icons before assertions
- [#194152](https://github.com/openclaw/openclaw/pull/194152) ui: move dialog closes and ghost icon actions onto IconButton
- [#194399](https://github.com/openclaw/openclaw/pull/194399) fix(media): cancel interrupted attachment downloads
- [#194401](https://github.com/openclaw/openclaw/pull/194401) improve(ci): reuse native import graph resolutions
- [#194374](https://github.com/openclaw/openclaw/pull/194374) fix(ui): open the mobile Where picker above when space below is short
- [#194382](https://github.com/openclaw/openclaw/pull/194382) improve: reduce Android build GC overhead
- [#194400](https://github.com/openclaw/openclaw/pull/194400) improve(ci): limit update fixture checks to their inputs
- [#194390](https://github.com/openclaw/openclaw/pull/194390) refactor(test): share plugin reload product child fixture
- [#193217](https://github.com/openclaw/openclaw/pull/193217) fix(control-ui): avoid warm chat reload backtracking

### 🐛 New Issues
- [#194408](https://github.com/openclaw/openclaw/issues/194408) [Feature]: Compaction: make MAX_COMPACTION_SUMMARY_CHARS (16,000) configurable; two-thirds of production compactions hit it `enhancement` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#194406](https://github.com/openclaw/openclaw/issues/194406) [Bug]: A local media path whose directory doesn't exist is reported as "not under an allowed directory" `bug` `no-stale` `bug:behavior` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#194404](https://github.com/openclaw/openclaw/issues/194404) [Bug]: Plugin resolveSyntheticAuth skipped when an agent has no saved auth profiles (allowAuthProfileFallback:false also disables plugin synthetic auth) `P2` `clawsweeper:needs-live-repro` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬1
- [#194403](https://github.com/openclaw/openclaw/issues/194403) [Bug]: Helper-completion continuations invalidate their own authority and leave conversations blocked `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `impact:session-state` `issue-rating: 🦪 silver shellfish` 💬1
- [#194402](https://github.com/openclaw/openclaw/issues/194402) Tool-call policy ctx: forward the existing `toolOwnerPluginId` and `workspaceDir` to plugin policies and hooks `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#194394](https://github.com/openclaw/openclaw/issues/194394) [Feature]: Document Wally as a custom OpenAI-compatible provider `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:linked-pr-open` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1
- [#194383](https://github.com/openclaw/openclaw/issues/194383) [Docs Bug]: Plugin reload recovery is described too narrowly `bug` `docs` `no-stale` `P3` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#194366](https://github.com/openclaw/openclaw/issues/194366) MCP relay Control UI stays on connection skeleton in ChatGPT in-app browser; same grant works in Brave `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬2

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬80 · 3h ago
- [#116201](https://github.com/openclaw/openclaw/issues/116201) Realtime voice work can retain unbounded provider and consult state — 💬59 · 35d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 261,224 · **Open issues:** 53,389 · **Last push:** <1h ago

### ✅ Merged PRs
- [#149214](https://github.com/NousResearch/hermes-agent/pull/149214) fix(groups): complete restart stop recovery and keep controls responsive
- [#150286](https://github.com/NousResearch/hermes-agent/pull/150286) feat(gateway): a client can name itself on session.create
- [#150193](https://github.com/NousResearch/hermes-agent/pull/150193) fix(groups): Disband asks a deferred turn's Stop at the home that admitted it
- [#150240](https://github.com/NousResearch/hermes-agent/pull/150240) Group chats no longer drop a message sent while the previous one settles
- [#150152](https://github.com/NousResearch/hermes-agent/pull/150152) llm.oneshot drops schema and redact again; plugins get structured output through their own RPC method
- [#150243](https://github.com/NousResearch/hermes-agent/pull/150243) docs(agents): route core and plugin work to the boundary lint rules, and trim root to make room
- [#150287](https://github.com/NousResearch/hermes-agent/pull/150287) feat(shared): the gateway client takes its session source and client name
- [#150291](https://github.com/NousResearch/hermes-agent/pull/150291) fix(tui): a refused ticket mint shows its repair command again
- [#150288](https://github.com/NousResearch/hermes-agent/pull/150288) feat(gateway): the control socket answers which gateway serves a profile
- [#150285](https://github.com/NousResearch/hermes-agent/pull/150285) feat(cli): add `hermes clipboard image --json` for clients that paste images

### 🐛 New Issues
- [#150431](https://github.com/NousResearch/hermes-agent/issues/150431) [Feature]: managed scope: let an admin lock mcp_servers (no user-layer servers)
- [#150427](https://github.com/NousResearch/hermes-agent/issues/150427) [Bug]: Gateway systemd unit replaces the user manager's PATH, so external-process providers can't find CLIs installed with mise
- [#150426](https://github.com/NousResearch/hermes-agent/issues/150426) [macOS] Missing NSAudioCaptureUsageDescription in setup wrapper causes system sounds (screenshot, Finder) to mute
- [#150424](https://github.com/NousResearch/hermes-agent/issues/150424) Gateway fails to start on macOS when an env var contains control characters (plistlib ValueError reported as "invalid_invocation")
- [#150420](https://github.com/NousResearch/hermes-agent/issues/150420) [Bug]: delegate_task output_schema: a failed first run (failed=True) still triggers the schema retry, which then starts with no history
- [#150414](https://github.com/NousResearch/hermes-agent/issues/150414) Plugin with a pyproject cannot be enabled on two profiles: PM stages every profile's plugin dir into one uv workspace
- [#150410](https://github.com/NousResearch/hermes-agent/issues/150410) Upgrade tests start from an old release and never see a file move
- [#150409](https://github.com/NousResearch/hermes-agent/issues/150409) [Bug]: Gateway: editor MCP validation answers bare -32603 when the optional [acp] extra is not installed
- [#150403](https://github.com/NousResearch/hermes-agent/issues/150403) Updaters from v0.21.6 on import names from the new tree that are not frozen `type/bug` `area/install-update` 💬1
- [#150402](https://github.com/NousResearch/hermes-agent/issues/150402) The e2e-upgrade handoff cell waits the full job timeout on a drain that will not end `type/test` `area/install-update` 💬1

### 🔒 Closed Issues
- [#139818](https://github.com/NousResearch/hermes-agent/issues/139818) [Bug]: Remote-backend desktop sessions are unresumable from a local desktop — session.resume fails with not_found

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,147 · **Open issues:** 1,160 · **Last push:** 2h ago

### ✅ Merged PRs
- [#12233](https://github.com/zeroclaw-labs/zeroclaw/pull/12233) fix(gateway): limit and cap OIDC bearer verification on the config route group
- [#12114](https://github.com/zeroclaw-labs/zeroclaw/pull/12114) fix(gateway): key rate limits on the proxy-appended XFF hop
- [#12273](https://github.com/zeroclaw-labs/zeroclaw/pull/12273) fix(deps): update vodozemac to 0.11.2 for RUSTSEC-2026-0445 and -0451
- [#12254](https://github.com/zeroclaw-labs/zeroclaw/pull/12254) fix(runtime): don't ask for approval of a tool call that can't run
- [#12179](https://github.com/zeroclaw-labs/zeroclaw/pull/12179) fix(tools): deliver_file stops asking the model to write the attachment uri into prose
- [#12177](https://github.com/zeroclaw-labs/zeroclaw/pull/12177) fix(tools): return MCP tool names in sorted order
- [#12162](https://github.com/zeroclaw-labs/zeroclaw/pull/12162) fix(cli): cancel quickstart without claiming no config was written
- [#11240](https://github.com/zeroclaw-labs/zeroclaw/pull/11240) test(gmail): cover nested multipart body extraction
- [#11158](https://github.com/zeroclaw-labs/zeroclaw/pull/11158) test(voice): keep markdown prose eligible
- [#11251](https://github.com/zeroclaw-labs/zeroclaw/pull/11251) test(vi): cover inclusive payment bounds

### 🐛 New Issues
- [#12283](https://github.com/zeroclaw-labs/zeroclaw/issues/12283) resolve_peer_set applies peer-group `ignore` per group, so outbound sends can reach ignored peers
- [#12280](https://github.com/zeroclaw-labs/zeroclaw/issues/12280) [Task]: don't treat a forwarded loopback address as local in SOP cancel authorization
- [#12279](https://github.com/zeroclaw-labs/zeroclaw/issues/12279) [Bug]: channel startup caps a long transcript from an earlier read, overwriting a message appended in between `bug` `channel` `follow-up`
- [#12263](https://github.com/zeroclaw-labs/zeroclaw/issues/12263) [Bug]: Strict provider rejects a long tool-heavy session forever — 422 missing field `tool_call_id` (outbound request larger than stored session)
- [#12261](https://github.com/zeroclaw-labs/zeroclaw/issues/12261) [Task]: session/close: re-check the current TUI before unregistering the channel and removing the session `runtime` `security` `follow-up` `topic:identity-access`
- [#12260](https://github.com/zeroclaw-labs/zeroclaw/issues/12260) [Bug]: RPC cron/add and cron/patch treat the request as an operator approval for the shell command `bug`

### 🔒 Closed Issues
- [#12052](https://github.com/zeroclaw-labs/zeroclaw/issues/12052) [Bug]: Gateway limiters key on the first X-Forwarded-For entry, so a client behind an appending proxy can claim the loopback exemption
- [#12047](https://github.com/zeroclaw-labs/zeroclaw/issues/12047) [Bug]: OIDC bearer verification on gateway routes has no attempt limiter or outbound cap
- [#12272](https://github.com/zeroclaw-labs/zeroclaw/issues/12272) [Bug]: vodozemac 0.11.0 fails Security on RUSTSEC-2026-0445 and RUSTSEC-2026-0451
- [#12248](https://github.com/zeroclaw-labs/zeroclaw/issues/12248) [Task]: Don't ask for approval of a tool call that can't run
- [#12178](https://github.com/zeroclaw-labs/zeroclaw/issues/12178) [Bug]: deliver_file description tells the model to write the attachment uri into the reply text

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,713 · **Open issues:** 1,571 · **Last push:** 2d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,942 · **Open issues:** 122 · **Last push:** 14d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 4d ago
- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬2 · 13d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 13d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 32d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 40d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 42d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 52d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 60d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 62d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 70d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 4 new
- [[Legal] Consumer Credit Terms](https://www.anthropic.com/legal/consumer-credit-terms) _2026-11-06_
- [[Research] Components Of Agent Memory](https://www.anthropic.com/research/components-of-agent-memory) _2026-11-06_
- [[Research] Project Eve Claude Plays Mmorpgs](https://www.anthropic.com/research/project-eve-claude-plays-mmorpgs) _2026-11-06_
- [[Research] Teaching Ai To Build Scientific Models](https://www.anthropic.com/research/teaching-ai-to-build-scientific-models) _2026-11-06_

### OpenAI — 2 new
- [[Policies] Marketplace Customer Program Terms](https://openai.com/policies/marketplace-customer-program-terms/) _2026-11-06_
- [[Customers] Vistaprint](https://openai.com/ads/customers/vistaprint/)

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Asking questions to a 0.5b model is hillarious](https://reddit.com/r/LocalLLaMA/comments/1xp8as6/asking_questions_to_a_05b_model_is_hillarious/) ↑773
- [We are cooked. My QFN 3.8 NVFP4 just drew a dog freehand in MS Paint (using new Open WebUI 0.13.0 and Open Terminal 0.17.2)](https://reddit.com/r/LocalLLaMA/comments/1xpmvf2/we_are_cooked_my_qfn_38_nvfp4_just_drew_a_dog/) ↑468
- [Latest Open-Source Labs are gutting away cybersecurity and reverse-engineering capabilities](https://reddit.com/r/LocalLLaMA/comments/1xp9jt1/latest_opensource_labs_are_gutting_away/) ↑378
- [Oc-e-Non-v1: A language model that gets to the f*cking point](https://reddit.com/r/LocalLLaMA/comments/1xpfhpm/ocenonv1_a_language_model_that_gets_to_the_fcking/) ↑185
- [NousResearch/Arete-27B · Hugging Face (Qwen finetune)](https://reddit.com/r/LocalLLaMA/comments/1xpmj33/nousresearcharete27b_hugging_face_qwen_finetune/) ↑171

### r/singularity — top 5 new
- [Stanford researchers develop a new AI memory system that recalls information from entire conversation histories using just 16 memory tokens. It reduces document-token usage by up to 4,212×, runs 27× f](https://reddit.com/r/singularity/comments/1xpabzx/stanford_researchers_develop_a_new_ai_memory/) ↑1372
- [An unreleased Anthropic AI model reportedly solves an 18-year-old quantum computing conjecture in just 3 days. Researchers at Physical Superintelligence say the proof establishes a fundamental limit o](https://reddit.com/r/singularity/comments/1xpgl2k/an_unreleased_anthropic_ai_model_reportedly/) ↑709
- [No GPT-6.2, no Fable 5.5, no Qwen 4](https://reddit.com/r/singularity/comments/1xpo0j3/no_gpt62_no_fable_55_no_qwen_4/) ↑610
- [Every tech bro rn](https://reddit.com/r/singularity/comments/1xp35e7/every_tech_bro_rn/) ↑436
- [Finally coming. Qwhen4 tease friday is here](https://reddit.com/r/singularity/comments/1xpd4ui/finally_coming_qwhen4_tease_friday_is_here/) ↑250

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [AI agent adoption is way lower than I expected. Are agents still too complicated for most people, or is there something else?](https://reddit.com/r/openclaw/comments/1xp18ng/ai_agent_adoption_is_way_lower_than_i_expected/) ↑11
- [Anyone else’s OpenClaw agents open a ridiculous number of Chrome tabs?](https://reddit.com/r/openclaw/comments/1xp2g3x/anyone_elses_openclaw_agents_open_a_ridiculous/) ↑5
- [Local_AI_selfheal](https://reddit.com/r/openclaw/comments/1xp6tsg/local_ai_selfheal/) ↑2
- [Is OpenClaw actually useless?](https://reddit.com/r/openclaw/comments/1xobtdj/is_openclaw_actually_useless/) ↑0

### X — @openclaw
- [How does one of the largest open source projects in history do releases? 🦞


@dallinfinite
  walks through how OpenClaw ](https://x.com/openclaw/status/2118803977882181986) ↑0 🔁0 · recent
- [A new model shouldn't mean waiting for a new OpenClaw release


@obviyus
  goes inside his work on model catalogs, accou](https://x.com/openclaw/status/2118767484144857342) ↑0 🔁0 · recent


### X — @steipete
_No new tweets since the last digest. Most recent:_
- [Is my perception off or is Apple just lying here? Anytime I build for or use Safari, it’s slower, has fewer features, we](https://x.com/steipete/status/2118492097917628704)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
