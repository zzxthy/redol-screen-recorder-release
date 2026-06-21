# Redol Screen Recorder Releases and Feedback

This is the public release and issue tracker repository for Redol Screen Recorder.

The application source code is maintained in a private repository. This public repository is used for:

- downloadable builds and release notes
- bug reports
- feature requests
- user-facing support discussions

Chinese version: [README.md](./README.md)

## Download

The current release focuses on the macOS client:

- Latest version: `v1.5.2`
- Release date: 2026-06-21

- Apple Silicon Mac: [Redol-Screen-Recorder-Mac-arm64.dmg](https://github.com/zzxthy/redol-screen-recorder-release/releases/latest/download/Redol-Screen-Recorder-Mac-arm64.dmg)
- Intel Mac: [Redol-Screen-Recorder-Mac-x64.dmg](https://github.com/zzxthy/redol-screen-recorder-release/releases/latest/download/Redol-Screen-Recorder-Mac-x64.dmg)

The Windows client is planned but not released yet.

## v1.5.2 Updates

- Added the Redol account center with signed-in email, plan, entitlement status, device, last verification time, and local access expiry.
- Added account actions for refreshing status, managing subscription, switching accounts, and signing out.
- Fixed account dialog button clicks in the floating recorder HUD.
- Fixed large dialog clipping in the floating HUD.
- Fixed smooth zoom behavior in native high-speed export so exported videos match the editor preview.
- Kept backend-controlled entitlement checks so the free beta access policy can still be revoked or adjusted centrally.

## Report A Bug

If you run into a problem, please open a new issue and include as much of the following information as possible:

- Redol Screen Recorder version
- macOS version
- what you were trying to do
- what happened instead
- what you expected to happen
- screenshots, recordings, diagnostic files, or logs

The more concrete the reproduction details are, the easier it is to investigate and fix the issue.

## Feature Requests

If you want to improve a recording, editing, or export workflow, please use the feature request template.

Helpful requests usually include:

- your current use case
- what feels slow or awkward in the current workflow
- how you expect the product to behave
- examples or screenshots from similar products

## Links

- Issues: https://github.com/zzxthy/redol-screen-recorder-release/issues
- Releases: https://github.com/zzxthy/redol-screen-recorder-release/releases
