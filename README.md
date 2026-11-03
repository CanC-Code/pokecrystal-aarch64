# GBCRunner

A native Android Game Boy Color runtime with mod support and an AI agent.

## Status

Early development. The first milestone is a CI-built, installable APK.

## Layout

- `android/` — Android application (Kotlin, Gradle)
- `native/` — Emulator core, JNI bridge, AI hooks (added in later commits)
- `ci/` — Build scripts
- `.github/workflows/` — Continuous integration

## Legal

GBCRunner does not ship any copyrighted game content. Users must supply their own ROM files.
