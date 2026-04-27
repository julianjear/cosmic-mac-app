# cosmic-mac-app

Public release feed for [Cosmic](https://julian.ai/cosmic) — the macOS-native AI second brain.

Each tagged release here ships the signed, notarized `Cosmic-X.Y.Z.dmg`.
[`appcast.xml`](./appcast.xml) is the Sparkle feed; the app reads it from
`raw.githubusercontent.com/julianjear/cosmic-mac-app/main/appcast.xml`
to deliver in-app updates.

Releases are produced by [`scripts/release.sh`](https://github.com/julianjear/cosmic) in the source repo.
