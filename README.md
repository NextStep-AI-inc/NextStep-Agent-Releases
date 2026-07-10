# NextStep Agent — Downloads

Public installers and auto-update feeds for **NextStep Agent**, the desktop app for
Canvas teachers. Source code is private; this repo only hosts release artifacts.

## Get the app

| | |
|---|---|
| **Latest** | [0.2.83](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/latest) |
| **All releases** | [https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases) |

**Platforms:** macOS (Apple Silicon + Intel), Windows (x64), Linux (x64 + arm64 AppImage).

Installed copies update automatically once a release is published here.

---

## Release history

### 0.2.84 *(building)* — —

  - Remove remote force-update from admin and desktop.

[Download 0.2.84](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.84)

### 0.2.83 **(latest)** — 7/10/2026

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

[Download 0.2.80](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.80)

### 0.2.79 — 7/9/2026

  - Mint rclone include and exclude filters from the Worker.

[Download 0.2.79](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.79)

### 0.2.78 — 7/9/2026

  - Include Crashpad and logs in folder rclone sync.

[Download 0.2.78](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.78)

### 0.2.77 — 7/9/2026

  - Fix Linux rclone zip extract and bump to 0.2.77.

[Download 0.2.77](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.77)

### 0.2.76 *(building)* — —

  - Match Windows realpath normalization in Electron config test
  - Preserve desktop workflow newline
  - Run Electron dev config test on desktop package jobs
  - Sync whole workspace and app-data folders via rclone.
  - Allow symlinked desktop node_modules in Vite
  - Bundle rclone sidecar for reliable large-file tree sync.

[Download 0.2.76](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.76)

### 0.2.75 — 7/9/2026

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
  - bump version to 0.2.68

[Download 0.2.69](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.69)

---

*This page is generated from tagged releases in the private `NextStep-Agent` repo.
Last updated for `v0.2.83`.*
