# tape-releases

Public artifact repository for [Tape](https://github.com/ailtonvivaz/tape) — a local-first macOS transcription app.

This repo holds:

- `appcast.xml` — Sparkle update feed consumed by the Tape app
- GitHub Releases — signed, notarized DMGs

The Tape source repository remains private until 1.0.

## Verifying downloads

DMGs are:

- Signed with Apple Developer ID and notarized by Apple
- Signed with EdDSA and verified by Sparkle on update install

The Sparkle public key is embedded in the Tape app's `Info.plist` under `SUPublicEDKey`.

## Reporting issues

Until the source repo is public, send feedback to the email listed on the Tape app's About window.
