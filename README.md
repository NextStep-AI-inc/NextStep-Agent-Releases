# NextStep Agent — Downloads

Public installers and auto-update feeds for **NextStep Agent**, the desktop app for
Canvas teachers. Source code is private; this repo only hosts release artifacts.

## Get the app

| | |
|---|---|
| **Latest** | [0.2.48](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/latest) |
| **All releases** | [https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases) |

**Platforms:** macOS (Apple Silicon + Intel), Windows (x64), Linux (x64 + arm64 AppImage).

Installed copies update automatically once a release is published here.

---

## Release history

### 0.2.49 *(building)* — —

  - mount update banner in the app shell
  - add in-app update ready banner
  - wire update IPC between main and renderer
  - track pending downloads instead of native restart dialog
  - restart intro flow after sign-out from completed app
  - show shell progress as two steps

[Download 0.2.49](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.49)

### 0.2.48 **(latest)** — 7/7/2026

  - Bundle 16 additional shared OMP skills for all agent profiles.
  - Add USAGE_COST_SOURCE toggle to switch metering back to LiteLLM later.
  - Cover dev preview session behavior
  - Meter usage caps from the token rate card instead of LiteLLM cost.
  - Disable implicit update install on quit
  - Fix subscription usage fallback

[Download 0.2.48](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.48)

### 0.2.47 — 7/7/2026

  - Show separate 5-hour and weekly usage bars in Subscription settings.
  - persist Canvas sessions across app restart and update

[Download 0.2.47](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.47)

### 0.2.46 — 7/7/2026

  - Bundle humanizer as a shared OMP skill for all agent profiles.
  - retarget writer to telemetry.ai_calls (nextstep-schema #25)
  - Remove trailing blank line in platform hint test
  - Reject drive-qualified file tool paths
  - Fix renderer platform hints

[Download 0.2.46](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.46)

### 0.2.45 — 7/7/2026

  - Route Canvas brain backfill through lightspeed-slow to cut background sync cost.
  - Raise background anti-hijack cap to $200 per UTC calendar month.
  - Track all-time background and total user spend for internal cost metrics.

[Download 0.2.45](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.45)

### 0.2.44 — 7/7/2026

  - Clarify and test that background lane spend is excluded from usage caps.
  - Switch usage caps to dual window and weekly limits by tier.
  - Move usage display to Subscription settings with percent remaining.

[Download 0.2.44](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.44)

### 0.2.43 — 7/7/2026

  - Fix mac arch-file globs with brace expansion and bump to 0.2.43.

[Download 0.2.43](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.43)

### 0.2.42 *(building)* — —

  - Split trial and paid usage caps and show remaining allowance in the UI.

[Download 0.2.42](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.42)

### 0.2.41 *(building)* — —

  - Fix mac universal git merge rules and bump to 0.2.41.
  - Enforce a $100/month usage cap for trial and paid users.

[Download 0.2.41](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.41)

### 0.2.4 *(building)* — —

  - Replace Canvas exploration sidebar card with a minimal footer progress bar.

[Download 0.2.4](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.4)

### 0.2.3 *(building)* — —

  - Improve Canvas brain auth detection and start exploration immediately on sign-in.

[Download 0.2.3](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.3)

### 0.2.2 *(building)* — —

  - Fix mac universal git bundling and bump to 0.2.2.
  - Fix accidental chromium-pickle-js version in package-lock.

[Download 0.2.2](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.2)

### 0.2.1 *(building)* — —

  - Bundle git in desktop installers and drop exclusive device-account linking.
  - Redesign sidebar Canvas exploration card as a footer-matched ring row
  - show referral earnings and credit balance in Settings

[Download 0.2.1](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.1)

### 0.2.0 — 7/7/2026

  - Fix desktop settings UX and restore agent model controls.
  - clarify Microsoft OAuth exchange failures
  - add Microsoft sign-in on web and desktop
  - add repo-local git config helpers
  - dedupe well-known worker handler and tighten tests
  - serve Entra domain verification from static assets

[Download 0.2.0](https://github.com/NextStep-AI-inc/NextStep-Agent-Releases/releases/tag/v0.2.0)

---

*This page is generated from tagged releases in the private `NextStep-Agent` repo.
Last updated for `v0.2.48`.*
