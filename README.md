# Flackle Mobile Client (React Native + TypeScript)

A production-ready cross-platform mobile application built with **React Native**, **Expo (Prebuild)**, and **TypeScript** implementing **Clean Architecture** patterns (Domain, Data, and Presentation layers) alongside typed file-based routing.

---

## Architecture Overview

The system strictly decouples domain logic, infrastructure/APIs, and presentation modules:

```text
src/
├── domain/        # Core business models, repository contracts, and use cases
├── data/          # REST endpoints, Axios data sources, and repository implementations
├── presentation/  # Reusable UI components, screens, hooks, and design system tokens
└── native/        # Turbo Native Modules bridging native platform services
app/               # File-based navigation stack, screens, and deep-link handlers