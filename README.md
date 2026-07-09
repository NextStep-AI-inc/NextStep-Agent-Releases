# NextStep Agent — Downloads

Public installers and auto-update feeds for **NextStep Agent**, the desktop app for
Canvas teachers. Source code is private; this repo only hosts release artifacts.

## Get the app

| | |
|---|---|
| **Latest** | [0.2.75](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/latest) |
| **All releases** | [https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases) |

**Platforms:** macOS (Apple Silicon + Intel), Windows (x64), Linux (x64 + arm64 AppImage).

Installed copies update automatically once a release is published here.

---

## Release history

### 0.2.75 **(latest)** — 7/9/2026

  - Fix Windows onboarding-persist smoke race on slow school DNS.
  - Add direct R2 multipart uploads for large artifacts.
  - Document R2 Local Uploads on the support-bundles bucket.
  - Clarify gateway sync comments and rename path-guard test.
  - Support multi-GB tree sync via chunked finalize and higher walk caps.
  - Exclude appVersion unit test from Workers SPA typecheck.

[Download 0.2.75](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.75)

### 0.2.72 — 7/9/2026

  - Make admin autosync fail-soft so one bad file cannot stall.

[Download 0.2.72](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.72)

### 0.2.71 — 7/9/2026

  - Fix force-update test types for desktop typecheck.
  - Add admin force-update for desktops that fall behind.
  - Show all known devices with app version in Admin fleet list.
  - Tag admin bundle downloads with who requested and who downloaded.
  - Isolate desktop dev instances per worktree (#122)

[Download 0.2.71](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.71)

### 0.2.70 — 7/9/2026

  - Replace auto-snapshot ZIPs with resumable rsync-like tree sync.
  - Fix autoSnapshots test fetch typing for desktop typecheck.
  - Upload workspace and app-data snapshots on start and every 6h.

[Download 0.2.70](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.70)

### 0.2.69 — 7/9/2026

  - bump version to 0.2.69
  - Preserve pending tabs on quit freeze (#119)
  - Refactor admin live telemetry composition out of god files.
  - Add admin live presence, brain/OMP inspect, and remote support bundles.
  - Fix approval editor platform shortcut

[Download 0.2.69](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.69)

### 0.2.68 — 7/9/2026

  - bump version to 0.2.68
  - toolbar squeeze - side clusters floor at content, field shrinks

[Download 0.2.68](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.68)

### 0.2.67 — 7/9/2026

  - bump version to 0.2.67
  - group creation moves you in (tab at birth); center address field
  - freeze-frame canvas under overlays + inline group creation
  - toolbar GroupSwitcher replaces tab-bar group chips
  - Safari 1:1 tab segments - stadium shape, full-area click, unfilled inactive
  - real liquid glass - macOS window vibrancy under translucent chrome

[Download 0.2.67](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.67)

### 0.2.66 — 7/9/2026

  - bump version to 0.2.66
  - restore the tab strip across restarts + Clear Browsing Data menu
  - Fix NavRail stale source assertions

[Download 0.2.66](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.66)

### 0.2.65 — 7/8/2026

  - import JSX and RefObject types in NavRail
  - repair main regressions blocking the v0.2.65 build
  - bump version to 0.2.65
  - persist session cookies so the Canvas login survives restarts
  - Validate desktop billing external URLs
  - align email template styling

[Download 0.2.65](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.65)

### 0.2.64 — 7/8/2026

  - tolerate missing tag ref when deleting stale draft releases
  - retry hindsight contract fetch and use the workflow token
  - style(invites): match the account-confirmation email template
  - restore worker observability config
  - invite a friend with referral auto-apply, resend email, and house dialog
  - use Sentry cron monitor wrapper

[Download 0.2.64](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.64)

### 0.2.63 — 7/8/2026

  - Polish Canvas theme settings and bump release to v0.2.63.
  - Fix dark Canvas theming on CDN-hosted stylesheets via a CORS-free preload fetch bridge.
  - Revert "chore: temporarily roll back codebase to v0.2.59."
  - temporarily roll back codebase to v0.2.59.

[Download 0.2.63](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.63)

### 0.2.62 — 7/8/2026

  - sync package-lock.json for darkreader dependency.

[Download 0.2.62](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.62)

### 0.2.61 *(building)* — —

  - bump version to 0.2.61
  - auto-refetch school primaryColor when missing from saved settings.
  - Update profile-skills test for the bundled canvas-theme skill.
  - Add Canvas theme row (Default/Dark/Custom) with assistant-designed custom themes.
  - Expose canvasTheme over IPC: set-mode handler, prepareCustom, AppState field, boot init.
  - add school and custom accent color pickers in Settings.

[Download 0.2.61](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.61)

### 0.2.60 *(building)* — —

  - bump version to 0.2.60
  - Fix sidebar chat list scroll getting stuck mid-list.
  - Add canvasTheme setting (default/dark/custom), drop dead reskinEnabled.
  - Bundle canvas-theme skill for assistant-designed custom Canvas themes.
  - Add Canvas themes implementation plan.
  - Add Canvas themes design spec (Default / Dark / Custom + canvas-theme skill).

[Download 0.2.60](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.60)

---

*This page is generated from tagged releases in the private `NextStep-Agent` repo.
Last updated for `v0.2.75`.*
