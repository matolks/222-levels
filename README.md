# 222 Levels

222 Levels is an in-progress Flutter mobile game built with Firebase. The game is designed around a 222-level progression system divided into multiple gameplay sections, where each section introduces different mechanics, difficulty models, and progression rules.

The project focuses on scalable mobile architecture, competitive progression design, authentication systems, cloud-backed state management, and ad-supported monetization.

---

## Tech Stack

- **Framework:** Flutter
- **Language:** Dart
- **Backend:** Firebase / Cloud Firestore
- **Authentication:** Firebase Authentication
- **OAuth Providers:** Google, Apple, X
- **Monetization:** Google Mobile Ads SDK (AdMob)
- **Local Storage:** Hive
- **Platform Targets:** iOS / Android

---

## Features

### Authentication

- Firebase Authentication integration
- Google Sign-In support
- Apple Sign-In support
- X authentication support
- Persistent account-based progression tracking

### Backend Infrastructure

- Firebase-powered backend architecture
- NoSQL cloud database integration
- Remote player data synchronization
- Scalable client-server communication design

### Local Storage

- Hive local database integration
- Cached gameplay state management
- Persistent progress storage
- Offline-friendly state tracking

### Monetization

- AdMob interstitial advertisement integration
- Failure-state advertisement triggering
- Ad-supported progression model
- Mobile-focused monetization architecture

---

## Gameplay Structure

The game is planned around 222 total levels divided across 25+ sections, with each section containing approximately 5–10 levels.

Each section introduces a different gameplay system or challenge type. Players must complete the active section before progressing further into the game.

Progression rules vary between sections and may include:

- Limited-life challenge systems
- Full section resets on failure
- Increasing difficulty escalation
- Locked progression checkpoints
- Re-clearing previous sections after moving backward

The progression model is intentionally designed to create long-term difficulty scaling and competitive pressure throughout the game experience.

---

## Competitive Gameplay Design

222 Levels is designed around competitive completion incentives, where players attempt to finish the full game progression before others.

Failure states are intentionally designed to carry consequences. Interstitial advertisements, progression resets, and limited-life systems are integrated directly into the gameplay loop to increase tension and discourage careless progression.

Rather than functioning as detached monetization, advertisements are incorporated as part of the overall challenge structure and risk-reward progression model.

---

## Project Goals

- Build a scalable full-stack mobile game architecture
- Design modular gameplay sections with distinct mechanics
- Integrate authentication and persistent cloud progression
- Develop a competitive progression system with long-term retention
- Implement monetization systems directly into gameplay flow
- Support large-scale concurrent mobile users through Firebase infrastructure

---

## Current Status

The project is currently in active development. Core systems including authentication, backend integration, local storage, gameplay progression logic, and monetization infrastructure are actively being implemented and refined.
