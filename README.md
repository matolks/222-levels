# 222 Levels

222 Levels is an in-progress Flutter mobile game built around one objective: clear all 222 levels before anyone else.

The game uses Firebase for cloud-backed progress, Hive for local gameplay state, and AdMob interstitials as part of the failure loop. Each section introduces different mechanics, difficulty rules, and penalties, making progression feel competitive rather than passive.

---

## Tech Stack

- **Framework:** Flutter
- **Language:** Dart
- **Backend:** Firebase / Cloud Firestore
- **Authentication:** Firebase Authentication
- **OAuth Providers:** Google, Apple, X
- **Monetization:** Google Mobile Ads SDK / AdMob
- **Local Storage:** Hive
- **Platform Targets:** iOS / Android

---

## Features

- Firebase authentication with Google, Apple, and X sign-in
- Cloud-backed player progress using Firebase / Cloud Firestore
- Local gameplay state storage with Hive
- AdMob interstitial ads integrated into failure states
- Section-based progression across 222 planned levels
- Competitive completion-focused gameplay loop

---

## Gameplay Structure

The game is planned around 222 total levels divided into 25+ sections. Each section contains approximately 5–10 levels and introduces a different game type, mechanic, or penalty model.

Players must complete the active section before progressing. Some sections may use limited lives, section resets, locked checkpoints, or other failure penalties.

Moving backward to a previous section requires the player to complete that section again before returning to later levels.

---

## Monetization Design

Interstitial ads are integrated into failure states as part of the gameplay loop.

Because the game is designed around competitive completion, ads function as both monetization and a progression deterrent. Failure costs time, which matters when players are competing to finish first.

---

## Status

This project is currently in active development. Core systems for authentication, Firebase integration, local storage, progression logic, and ad monetization are being implemented and refined.
