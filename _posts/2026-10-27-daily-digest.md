---
layout: post
title: "Ecosystem Digest — 2026-10-27"
date: 2026-10-27 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-27
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 393,159 | 8 | 0 | 10 | 0 |
| **hermesagent** | 257,431 | 10 | 5 | 10 | 0 |
| **ZeroClaw** | 33,050 | 15 | 0 | 0 | 0 |
| **IronClaw** | 12,677 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,917 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 393,159 · **Open issues:** 7,944 · **Last push:** <1h ago

### ✅ Merged PRs
- [#185291](https://github.com/openclaw/openclaw/pull/185291) test(codex,gateway): remove low-value tests (batch d647)
- [#184743](https://github.com/openclaw/openclaw/pull/184743) fix(ui): keep unsaved Talk captions where they were spoken, not below later typed messages
- [#185250](https://github.com/openclaw/openclaw/pull/185250) fix(agents): stop runtime rebuild storms during auth cooldowns
- [#185299](https://github.com/openclaw/openclaw/pull/185299) fix: let Gateway clients identify read-only config writes
- [#184847](https://github.com/openclaw/openclaw/pull/184847) fix(beam): match canonically equivalent session titles
- [#185256](https://github.com/openclaw/openclaw/pull/185256) perf(workspace): avoid copying owned projection mutations
- [#184110](https://github.com/openclaw/openclaw/pull/184110) fix: keep plugin utilities available in registered callbacks
- [#184166](https://github.com/openclaw/openclaw/pull/184166) fix(update): use canonical JSON for cleanup exceptions
- [#185301](https://github.com/openclaw/openclaw/pull/185301) perf(agents): reuse unchanged Code Mode store replay
- [#185312](https://github.com/openclaw/openclaw/pull/185312) refactor(test): remove stale terminal fixture setup

### 🐛 New Issues
- [#185317](https://github.com/openclaw/openclaw/issues/185317) [Bug]: sessions_spawn "model not allowed" error omits the modelPolicy.allow fix guidance that the /model path already provides `bug` `no-stale` `bug:behavior` `P3` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#185305](https://github.com/openclaw/openclaw/issues/185305) LINE shows the loading animation in a one-to-one chat even when session send policy denies replies `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#185303](https://github.com/openclaw/openclaw/issues/185303) [Bug]: sessions_send from a claude-cli turn leaks its tool-call authority into the target run; configured MCP calls fail "Tool call authorization expired" `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1
- [#185298](https://github.com/openclaw/openclaw/issues/185298) [Bug]: media-bearing Control UI live replies re-parse the whole reply per delta (12.4 s at 128 KB) `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#185297](https://github.com/openclaw/openclaw/issues/185297) [Bug]: Reading client credentials on a freshly bootstrapped database now throws instead of returning no identity `bug` `bug:behavior` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` `clawsweeper:bulk-filed` 💬1
- [#185289](https://github.com/openclaw/openclaw/issues/185289) [Bug]: a partial HTML/JSX tag at a streamed delta boundary re-projects the whole reply (1.0 s at 64 KB, 15.1 s at 256 KB) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#185286](https://github.com/openclaw/openclaw/issues/185286) [Bug]: Codex terminal reasoning reorders checkpointed work and blocks final-answer recovery `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#185280](https://github.com/openclaw/openclaw/issues/185280) [Bug]: message read --channel discord still loads all plugins when Discord is an external plugin (Gateway-owned skip never applies) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬2

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 257,431 · **Open issues:** 51,301 · **Last push:** <1h ago

### ✅ Merged PRs
- [#145204](https://github.com/NousResearch/hermes-agent/pull/145204) GPT-6.1 Terra is selectable on OpenRouter and Nous Portal
- [#145107](https://github.com/NousResearch/hermes-agent/pull/145107) fix(webapp): report a browser-blocked pop-out within seconds
- [#145106](https://github.com/NousResearch/hermes-agent/pull/145106) fix(webapp): plain-HTTP sends and copies, browser edit menus, rebuild-safe chunks, image links and restart-wait prompts
- [#145114](https://github.com/NousResearch/hermes-agent/pull/145114) fix(webapp): do not route or mark reachable a profile the gateway does not serve
- [#145113](https://github.com/NousResearch/hermes-agent/pull/145113) fix(webapp): keep folder prefs with the profile that owns them
- [#145112](https://github.com/NousResearch/hermes-agent/pull/145112) fix(webapp): each prepared-submission journal entry lives under its own storage key
- [#145111](https://github.com/NousResearch/hermes-agent/pull/145111) fix(webapp): give each send its own retry record when Web Locks are missing
- [#145108](https://github.com/NousResearch/hermes-agent/pull/145108) fix(dashboard-auth): give every password-provider session its own tokens
- [#145116](https://github.com/NousResearch/hermes-agent/pull/145116) fix(webapp): keep reading a host terminal socket behind a waiting write, so keepalive pongs are seen
- [#145115](https://github.com/NousResearch/hermes-agent/pull/145115) fix(webapp): a down SSH host no longer stalls file requests on other SSH profiles

### 🐛 New Issues
- [#145333](https://github.com/NousResearch/hermes-agent/issues/145333) Desktop: one user message rendered as two bubbles in the same turn (delivered once, executed once) `type/bug` `P3` `comp/desktop` `desktop/chat`
- [#145332](https://github.com/NousResearch/hermes-agent/issues/145332) [Bug]: Windows Desktop cannot open a bot's legacy Bot Chat: adoption re-feeds saved cwd '/' into build_policy (invalid_params cwd) `type/bug` `comp/gateway` `backend/local` `P2` `area/sessions` `os/windows` 💬1
- [#145329](https://github.com/NousResearch/hermes-agent/issues/145329) [Bug]: node-inspect-debugger selects an arbitrary existing TUI process instead of debugging its own launch `type/bug` `comp/cli` `tool/skills` `P2`
- [#145327](https://github.com/NousResearch/hermes-agent/issues/145327) [Bug]: Codex auxiliary adapter silently drops response_format (strict json_schema never sent as text.format) `type/bug` `comp/agent` `provider/openai` `P2`
- [#145318](https://github.com/NousResearch/hermes-agent/issues/145318) WhatsApp adapter 缺 `CREATE_BREAKAWAY_FROM_JOB` retry fallback，致 gateway（Windows Task Scheduler 啟動）WhatsApp channel 永久 down `type/bug` `comp/plugins` `tool/file` `platform/whatsapp` `P3` `os/windows` 💬1
- [#145315](https://github.com/NousResearch/hermes-agent/issues/145315) [Bug]: Webhook `cron_job` fires deadlock the gateway once as many run at once as the default thread pool has threads `type/bug` `comp/gateway` `comp/cron` `platform/webhook` `P2` 💬1
- [#145314](https://github.com/NousResearch/hermes-agent/issues/145314) [Bug]: quiet cron script leaves a permanent empty session every firing (non-no_agent path) `type/bug` `comp/cron` `P2` `area/sessions` 💬1
- [#145313](https://github.com/NousResearch/hermes-agent/issues/145313) Plugin catalog: supported way to reuse an existing Composio user credential `type/feature` `comp/plugins` `area/auth` `P3` `comp/portal` `area/profiles` 💬3
- [#145308](https://github.com/NousResearch/hermes-agent/issues/145308) clarify in a message_agent-started turn never renders but holds the session lease; restart --yes waits on it `type/bug` `comp/gateway` `P2` `area/sessions` 💬2
- [#145306](https://github.com/NousResearch/hermes-agent/issues/145306) [Bug]: Bundled skill-authoring guidance targets installed copies and discards existing work `type/docs` `tool/file` `tool/skills` `P3` `area/i18n` 💬1

### 🔒 Closed Issues
- [#145126](https://github.com/NousResearch/hermes-agent/issues/145126) [Webapp] Chat send, new session and copy buttons are dead on plain-HTTP origins — unguarded crypto.randomUUID / navigator.clipboard in apps/desktop (extends #138913)
- [#144673](https://github.com/NousResearch/hermes-agent/issues/144673) [Bug]: A browser-blocked Webapp pop-out shows no error behind the sign-in gate and a late one on a launch-link tab
- [#109423](https://github.com/NousResearch/hermes-agent/issues/109423) [Bug]: Telegram allowed_chats stored as JSON string is mis-parsed → group messages silently dropped
- [#144681](https://github.com/NousResearch/hermes-agent/issues/144681) [Bug]: The Webapp treats every installed profile as served by its gateway
- [#144679](https://github.com/NousResearch/hermes-agent/issues/144679) [Bug]: A Webapp new chat or tab can start in another profile's default folder

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,050 · **Open issues:** 1,074 · **Last push:** 3h ago

### 🐛 New Issues
- [#12054](https://github.com/zeroclaw-labs/zeroclaw/issues/12054) [Feature]: Honor runtime-profile thinking levels for OpenAI
- [#12053](https://github.com/zeroclaw-labs/zeroclaw/issues/12053) [Bug]: /api/docs loads an unpinned third-party script without integrity checks on the dashboard origin `bug` `gateway` `security` `topic:identity-access`
- [#12052](https://github.com/zeroclaw-labs/zeroclaw/issues/12052) [Bug]: Gateway limiters key on the first X-Forwarded-For entry, so a client behind an appending proxy can claim the loopback exemption `bug` `gateway` `security` `topic:identity-access`
- [#12051](https://github.com/zeroclaw-labs/zeroclaw/issues/12051) [Bug]: sop_workshop apply lets a scoped principal author shared SOPs that later run with operator authority `bug` `runtime` `security` `topic:identity-access`
- [#12050](https://github.com/zeroclaw-labs/zeroclaw/issues/12050) [Bug]: The OIDC callback token page has no browser binding, allowing login CSRF `bug` `gateway` `security` `topic:identity-access`
- [#12049](https://github.com/zeroclaw-labs/zeroclaw/issues/12049) [Bug]: Four remote addresses can fill the browser sign-in flow store and block sign-in for everyone, loopback included `bug` `gateway` `security` `topic:identity-access`
- [#12048](https://github.com/zeroclaw-labs/zeroclaw/issues/12048) [Feature]: Validate the OIDC browser-flow redirect_uri against a configured dashboard origin instead of trusting the Host header `enhancement` `gateway` `security` `topic:identity-access`
- [#12047](https://github.com/zeroclaw-labs/zeroclaw/issues/12047) [Bug]: OIDC bearer verification on gateway routes has no attempt limiter or outbound cap `bug` `gateway` `security` `topic:identity-access`
- [#12046](https://github.com/zeroclaw-labs/zeroclaw/issues/12046) [Bug]: Non-admin principals with a wildcard tool selector keep principal-unaware tools (cron, schedule, peer messaging, SOP execution) `bug` `runtime` `security` `topic:identity-access`
- [#12045](https://github.com/zeroclaw-labs/zeroclaw/issues/12045) [Bug]: Response bodies from user/LLM-controlled URLs are buffered whole before the size cap is applied (link_enricher, WeChat, multimodal remote images)
- [#12043](https://github.com/zeroclaw-labs/zeroclaw/issues/12043) [Bug]: glob_search silently drops authorized matches outside the workspace, and rejects absolute patterns under read-only allowed roots
- [#12042](https://github.com/zeroclaw-labs/zeroclaw/issues/12042) ZeroClaw was independently reviewed on Hlido — scored 79/100, right of reply open
- [#12041](https://github.com/zeroclaw-labs/zeroclaw/issues/12041) [Feature]: Bring gitea/forgejo feature set on-parity with the github one `enhancement`
- [#12022](https://github.com/zeroclaw-labs/zeroclaw/issues/12022) [Feature]: memory recall: an opt-in external rerank stage over the eligible candidate pool 💬1
- [#12021](https://github.com/zeroclaw-labs/zeroclaw/issues/12021) [Bug]: When saving configuration settings via the banner in the web ui, the config group save button is still highlighted afterwards `bug` 💬2

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,677 · **Open issues:** 1,565 · **Last push:** 1d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,917 · **Open issues:** 120 · **Last push:** 3d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬2 · 2d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 2d ago
- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 12d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 21d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 29d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 31d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 41d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 49d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 51d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 59d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] S1 Sec](https://www.anthropic.com/news/s1-sec) _2026-10-26_

### OpenAI — 1 new
- [[Index] Fanatics Streamline Fan Experience](https://openai.com/index/fanatics-streamline-fan-experience/) _2026-10-27_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

_No new posts in the last 24h._

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw
_No new posts in the last 24h._

### X — @openclaw
- [GPT-6.1 Terra from 
@OpenAI
 is already available in OpenClaw.

Use ChatGPT sign-in or your OpenAI API key, then select ](https://x.com/openclaw/status/2114850737645879629) ↑0 🔁0 · recent
- [OpenClaw Hero 
@ArkStabler
  was doing pest control in Ocala, Florida nine months ago.

Now he sets up OpenClaw agents f](https://x.com/openclaw/status/2114846187312521528) ↑0 🔁0 · recent
- [OpenClaw v2026.10.7 🦞

🔧 Earlier update checks
🧠 Claude CLI context fixes
🎙️ macOS Talk reply fixes
🐰 Bun startup fixes
](https://x.com/openclaw/status/2114590330276442521) ↑0 🔁0 · recent


### X — @steipete
- [I spent some time on the weekend to test bun's AOT compiler and results are nothing short of amazing. Performance up 2-3](https://x.com/steipete/status/2114879798434758905) ↑0 🔁0 · recent
- [Banger.](https://x.com/steipete/status/2114879359857422729) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
