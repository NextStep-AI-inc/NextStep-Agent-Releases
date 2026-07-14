# NextStep Agent — Downloads

Public installers and auto-update feeds for **NextStep Agent**, the desktop app for
Canvas teachers. Source code is private; this repo only hosts release artifacts.

## Get the app

| | |
|---|---|
| **Latest** | [0.2.93](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/latest) |
| **All releases** | [https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases) |

**Platforms:** macOS (Apple Silicon + Intel), Windows (x64), Linux (x64 + arm64 AppImage).

Installed copies update automatically once a release is published here.

---

## Release history

### 0.2.93 **(latest)** — 7/14/2026

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

[Download 0.2.84](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.84)

### 0.2.83 — 7/10/2026

  - Pin sync collection scope to the desktop build.

[Download 0.2.83](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.83)

### 0.2.82 — 7/10/2026

  - Release desktop 0.2.82 concurrent chats
  - close concurrent-session review blockers
  - ignore spike-out scratch dir
  - docs: redact local username paths and API responseId from spike findings
  - restore xpfx guard-comment reword lost after #137
  - docs: record concurrent-sessions acceptance run

[Download 0.2.82](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.82)

### 0.2.81 — 7/9/2026

  - Bump desktop to 0.2.81 for remote sync interval.
  - Simplify admin All users chrome to match the portal.
  - Revert admin device detail to portal styling.
  - Default folder sync to 30 min and mint interval from Worker.
  - Restyle admin device detail in a Starlink-like dark panel.
  - Spin down zip containers 30s after the last job.

[Download 0.2.81](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.81)

### 0.2.80 — 7/9/2026

  - Support optional Worker-configured diagnostic sync paths.
  - Mint rclone include and exclude filters from the Worker.
  - Include Crashpad and logs in folder rclone sync.
  - Fix Linux rclone zip extract and bump to 0.2.77.
  - Match Windows realpath normalization in Electron config test
  - Preserve desktop workflow newline

[Download 0.2.80](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.80)

---

*This page is generated from tagged releases in the private `NextStep-Agent` repo.
Last updated for `v0.2.93`.*
