# Dockyard Releases

This repo hosts signed, notarized release downloads for Dockyard, a macOS app for visually
orchestrating and monitoring local Docker Compose projects — it contains no source code.
Dockyard's source lives in a private repository; this repo exists purely so real users (and the
in-app Sparkle auto-updater) can download release assets and the update feed without
authentication.

- **Downloads**: see [Releases](https://github.com/rschalch/dockyard-releases/releases) for the
  latest signed, notarized `.dmg`.
- **Update feed**: `appcast.xml` in this repo is what Dockyard's Sparkle integration polls for
  new versions.

Every asset here is built, signed with a Developer ID certificate, and notarized by Apple before
being uploaded — nothing here is unsigned or unverified.
