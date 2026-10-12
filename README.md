# Cloud Anchor updates

This is the public update feed for **Cloud Anchor**, a macOS app and `anchor` command-line tool for managing cloud credentials.

- **`appcast.xml`** is the [Sparkle](https://sparkle-project.org) feed that Cloud Anchor checks for new versions. It's served at <https://dbagan.github.io/cloud-anchor-updates/appcast.xml>.
- **Releases** hold the notarized, Developer ID–signed `CloudAnchor-X.Y.Z.zip` for each version. Every update is also signed with Cloud Anchor's EdDSA update key, and the app refuses one that doesn't verify.

The source code lives in a private repository. This repository is written by the release process; please don't open pull requests here.

## Installing

```sh
brew install --cask dbagan/tap/cloudanchor
```

Once installed, Cloud Anchor updates itself (**Cloud Anchor ▸ Check for Updates…**). Homebrew leaves it alone because the cask is marked `auto_updates`.
