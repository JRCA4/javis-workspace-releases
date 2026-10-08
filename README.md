# Javi’s Workspace — releases

Installers and update files for **Javi’s Workspace**, a local-first desktop command center for AI
coding CLIs (Claude Code and Codex). The source code lives in a private repository; this one holds
only what the app downloads.

## Install

Open the [latest release](../../releases/latest) and download:

- **Windows 11:** `javis-workspace_<version>_x64-setup.exe` (per-user install, no admin rights).
  The installer isn't code-signed yet, so SmartScreen warns: choose **More info → Run anyway**.
- **macOS (Apple silicon):** `javis-workspace_<version>_aarch64.dmg`. The app isn't notarized yet:
  the first time, right-click it and choose **Open**.

## Updates

The app checks this repository's latest release for a newer version (Settings → Updates; it
sends no project data) and installs one only when you click **Install**. Every update is signed,
and the app refuses a file whose signature doesn't match.
