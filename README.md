# AirMatch

Airport Traveler Matching Platform — connect travelers at the same airport heading to similar destinations so they can share transportation.

## Repositories

This project is split into separate repositories:

| Repo | Description | Link |
|------|-------------|------|
| **Flutter app** | Mobile client (iOS & Android) | [github.com/jaydeepdodiya/airmatch-flutter](https://github.com/jaydeepdodiya/airmatch-flutter) |
| **Backend API** | Node.js REST API | [github.com/jaydeepdodiya/airmatch-backend](https://github.com/jaydeepdodiya/airmatch-backend) |

## Local development

Clone both repos side by side (or keep this folder layout):

```
development/
├── airmatch/              ← this repo (docs only)
├── airmatch-flutter/      ← git clone ...
└── airmatch-backend/      ← git clone ...
```

Or work from this monorepo-style folder — `flutter/` and `backend/` are separate git repos and are not tracked here.

## Documentation

- [Product Requirements (PRD)](docs/PRD.md)

## Git workflow (all repos)

| Branch | Purpose |
|--------|---------|
| `main` | Stable releases |
| `development` | Daily development — **default working branch** |

Work on `development`, merge to `main` via Pull Request when a feature is complete.

## Tech stack

| Layer | Stack |
|-------|-------|
| Mobile | Flutter, BLoC, Clean Architecture, Dio, GetIt, Firebase Auth, Google Sign-In |
| Backend | Node.js, Express, Firebase Admin |
| Auth | Firebase Authentication + Google Sign-In |
| Push (planned) | Firebase Cloud Messaging |
