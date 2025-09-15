# Vivaan (Unnal Mudiyum) — Android App

This repository contains the Vivaan Android app (minimal / text-first).
Push to `main` — GitHub Actions will build an APK artifact automatically.

How to build locally:
- Install Android Studio + JDK 17
- Open project, Build > Build APK(s)

OR to ensure Actions runs:
- Generate Gradle wrapper locally: `./gradlew wrapper` (or `gradle wrapper`) and commit `gradlew` and `gradle/wrapper/`.

APK artifact will appear under: Actions → Build Vivaan APK → Artifacts → `Vivaan.apk`
