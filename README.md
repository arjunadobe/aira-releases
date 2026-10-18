# Aira Releases

Public download host for Aira builds.

This repository holds **release binaries only** — no source. Each release tag
carries the installers for that version plus `latest.json`, the manifest read by
the update endpoint at `https://updates.airadev.com`.

## Downloads

Grab the latest build from the [Releases page](https://github.com/arjunadobe/aira-releases/releases/latest).

| Asset | Purpose |
| --- | --- |
| `Aira-<version>-darwin-arm64.dmg` | macOS installer (Apple Silicon) |
| `Aira-<version>-darwin-arm64.zip` | used by in-app automatic updates |
| `Aira-<version>-win32-x64.exe` | Windows installer (per user, no admin rights) |
| `Aira-reh-<version>-linux-*.tar.gz` | remote extension host, downloaded on demand |
| `*.sha256` | checksums |

macOS builds are signed with a Developer ID and notarized by Apple. Windows builds
are not code-signed yet: Windows may show "Windows protected your PC" the first
time; choose *More info* → *Run anyway*.
