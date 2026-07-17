# NextStep Agent — Downloads

Public installers and auto-update feeds for **NextStep Agent**, the desktop app for
Canvas teachers. Source code is private; this repo only hosts release artifacts.

## Get the app

| | |
|---|---|
| **Latest** | [0.2.97](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/latest) |
| **All releases** | [https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases) |

**Platforms:** macOS (Apple Silicon + Intel), Windows (x64), Linux (x64 + arm64 AppImage).

Installed copies update automatically once a release is published here.

---

## Release history

### 0.2.97 **(latest)** — 7/17/2026

  - keep browser lock acquire timer ref'd and clear on abandon
  - do not force sync on every auth token refresh
  - bound worktree subagent fan-out in skill
  - time out browser_tabs lock acquire
  - abort chat turns on wall-clock and tool-step caps
  - rotate OMP session on halt, steady entry, and max turns

[Download 0.2.97](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.97)

### 0.2.96 — 7/14/2026

  - stop steady-state sync kicks on Canvas tab chrome
  - bump version to 0.2.96 after v0.2.95 stable release

[Download 0.2.96](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.96)

### 0.2.95 — 7/14/2026

  - auto-reset the Canvas mirror on a sync-logic schema bump
  - a 403 is never 'expected' — overreport via sync_feedback
  - backfill completes once reachable courses are done — restricted courses no longer block it
  - role-aware canvas_sync — student roles skip staff-only sections
  - stop perpetual 'syncing' loop — steady cadence keys off backfill completion, not the always-active mirror goal
  - sync_feedback auto-attaches the chat transcript + folds sync-log/status/coverage into every report

[Download 0.2.95](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.95)

### 0.2.94 — 7/14/2026

  - Fix nightly source tag: set git identity for annotated tags
  - Fix nightly updater feed: set GitHub publish channel to nightly
  - Polish beta program copy and force stable install on opt-out
  - Add nightly channel, stable-branch releases, and beta program setting

[Download 0.2.94](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.94)

### 0.2.93 — 7/14/2026

  - bump version to 0.2.93
  - restore device-id fallback for bug report submit
  - ci: remove redundant Actions Worker deploy (Cloudflare Workers Builds owns deploys)
  - welcome From is 'Jason Hedrick' (comma broke name parsing)
  - ci: build web assets before wrangler deploy
  - ci: deploy apps/web Worker via GitHub Actions

[Download 0.2.93](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.93)

### 0.2.92 — 7/13/2026

  - client-checked force-update gate (min-version)

[Download 0.2.92](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.92)

### 0.2.91 — 7/13/2026

  - bump version to 0.2.91
  - Use Google instead of DuckDuckGo for address-bar search
  - docs: force-update kill-switch design spec
  - docs: drop em-dashes from welcome email copy
  - docs: welcome-email-on-signup design spec

[Download 0.2.91](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.91)

### 0.2.90 — 7/13/2026

  - run Canvas sync on lightspeed instead of tiny

[Download 0.2.90](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.90)

### 0.2.89 — 7/13/2026

  - Revert "Merge pull request #147 from NextStep-AI-inc/worktree-canvas-get-pipeline"
  - enable AGENT_SESSION_RUNTIME binding after worker ship
  - repair omp-container wrangler.jsonc after bad edit
  - keep v1 DO migration for new session-runtime worker
  - migrate omp-container DO classes for session runtime
  - defer AGENT_SESSION_RUNTIME binding until Phase 3

[Download 0.2.89](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.89)

### 0.2.88 — 7/11/2026

  - bump version to 0.2.88
  - Layer Canvas sync reset confirm like Bug reports.
  - Replace native reset confirm with an in-app dialog.
  - Tuck Reset mirror into the Canvas sync info popover.
  - Add Reset mirror to wipe the local Canvas sync and restart backfill.
  - Tune Canvas sync info tip: flat multiline copy with a light outline.

[Download 0.2.88](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.88)

### 0.2.87 — 7/10/2026

  - harden Canvas gather pipeline for release
  - test(desktop): unbreak gatewayPathGuard on a current-prefix comment
  - reject prefix-lookalike origins in canvas pagination guard
  - docs(brain): add live real-call A/B token measurement (81 nextstep-tiny completions)
  - docs(brain): add canvas gather pipeline implementation plan
  - docs(brain): add canvas token-burn report measured on live bench

[Download 0.2.87](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.87)

### 0.2.86 — 7/10/2026

  - bump version to 0.2.86
  - Send legacy screenshot so prod Linear still gets bug-report images.
  - Cover multi-image bug-report submit and the four-item media cap.
  - Fix blank desktop UI from case-colliding editor module names.
  - Include Canvas browser content in bug-report screenshots.
  - Fix markup editor wiring test after toolbar split.

[Download 0.2.86](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.86)

### 0.2.85 — 7/10/2026

  - bump version to 0.2.85
  - open reports from account menu and harden Linear filing
  - classify gateway route failures
  - simplify bug report dialog header
  - close reports when auth degrades
  - contain untrusted crash data

[Download 0.2.85](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.85)

### 0.2.84 — 7/10/2026

  - Remove remote force-update from admin and desktop.
  - Pin sync collection scope to the desktop build.
  - Release desktop 0.2.82 concurrent chats
  - close concurrent-session review blockers
  - ignore spike-out scratch dir
  - docs: redact local username paths and API responseId from spike findings

[Download 0.2.84](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.84)

---

*This page is generated from tagged releases in the private `NextStep-Agent` repo.
Last updated for `v0.2.97`.*
