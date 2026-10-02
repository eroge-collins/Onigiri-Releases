# What's New

## 1.0.7

- Improved the Marketplace download flow so downloaded skins open directly in the normal import/edit workflow.
- Added marketplace image proxying and local image caching for more reliable previews.
- Improved skin browser pagination, virtualization, and custom-skin handling.
- Added an in-app console/debug section for troubleshooting.

## 1.0.6

- App updates no longer delete LTK Patcher binaries from `%APPDATA%/Onigiri/tools`.
- App updates no longer delete imported mod cache or overlay profiles.
- LTK Patcher files and their version marker now survive normal app upgrades.
- Refreshed RuneForge marketplace cache with the current archive index.
- RuneForge entries without an archived `.fantome` now clearly link to RuneForge instead of being mislabeled as Open Source.
- 2,952 of 3,099 current RuneForge entries have an archived downloadable file; the remaining 147 are source-only entries in the website catalog.

## 1.0.5

- Fixed restore from maximized mode always returning to a compact 1280x720 window.
- Prevented maximized bounds from being persisted as the normal window size.
- Removed the remaining Discord Rich Presence/activity ambiguity around the Onigiri game name.
- The Windows updater now shows the normal Onigiri installer UI while installing updates.
- Polished the LTK-required action buttons to use the standard Onigiri button styling.

## 1.0.4

- Fixed Marketplace custom skins being classified as `Custom` when their champion uses a display name such as `Lee Sin`.
- Fixed Apply resolving imported marketplace files by a reconstructed filename instead of their actual local file path.
- Fixed the Hematite repair tool integration by replacing the broken upstream v0.7.0 release asset with a clean build from the tagged source.- Added SHA-256 verification for the bundled Hematite mirror and clearer Fix error output.
- Increased the Hematite Fix timeout to 180 seconds for larger mods.

## 1.0.3

- Fixed restore from maximized mode always returning to a compact 1280x720 window.
- Prevented maximized bounds from being persisted as the normal window size.
- Removed the remaining Discord Rich Presence/activity ambiguity around the Onigiri game name.
- The Windows updater now shows the normal Onigiri installer UI while installing updates.
- Polished the LTK-required action buttons to use the standard Onigiri button styling.

## 1.0.2

- Fixed Discord Rich Presence conflicting with the unrelated game named Onigiri.
- Restored the compact window size to 1280×720 when leaving maximized mode.
- Moved Onigiri user data to `%APPDATA%/Onigiri` with organized storage, runtime, tools, and browser directories.
- Separated Chromium/Electron session data from Onigiri's application data.

## 1.0.1

- Public GitHub release channel for automatic updates.
- Improved marketplace installation synchronization.
- Improved update and web integration reliability.