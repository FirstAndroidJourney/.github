# First Android Journey

> Learn Android & Flutter concepts through bite-sized, production-style labs.

<p align="center">
  <img src="https://img.shields.io/badge/Android%20Labs-9-green?style=flat-square" alt="Android labs">
  <img src="https://img.shields.io/badge/Flutter%20Projects-1-02569B?style=flat-square" alt="Flutter labs">
  <img src="https://img.shields.io/badge/Tech-Auth%20·%20Maps%20·%20Payments%20·%20UI-orange?style=flat-square" alt="Tech focus">
</p>

Hands-on Android and Flutter labs for students who learn by building. Every repository in this organization is a self-contained mini project, complete with source, assets, and lab notes, so you can explore a specific topic without wading through unrelated boilerplate.

---

## 🔍 Why these labs exist
- Reinforce lectures with working code that you can run, break, and fix.
- Compare Java, Kotlin, and Flutter approaches to the same mobile concepts.
- Share reproducible snippets with classmates or contributors via GitHub Discussions and Issues.

---

## 📚 Project Capsules

### ✅ Android-Task-List-App
A classic to-do list that walks through RecyclerView adapters, SQLite-style helpers, and lifecycle-aware UI updates. It is intentionally small, so you can focus on CRUD operations, custom adapters (`CongViecAdapter`), and persistence wiring without extra libraries.

### 🌐 Android-Database
Shows how to talk to a backend using Retrofit. The `ApiService` interface demonstrates posting JSON login credentials, while the surrounding activities cover request/response DTOs, field validation, and handling asynchronous network callbacks in a Kotlin-DSL Gradle setup.

### 🔐 Android-Firebase-Auth
Email/password authentication powered by FirebaseAuth. You practice sign-up, sign-in, sign-out, verification flows, success animations, and error handling with `Task<AuthResult>` listeners. The UI layer includes entrance animations (`card_enter`) and vector drawables for feedback.

### 🧭 Android-Fragment_Bottom_Navigation
Demonstrates Jetpack Navigation, ViewBinding, and shared `ViewModel`s inside a bottom navigation shell. It wires fragments to toolbar actions, keeps the back stack predictable, and illustrates how to integrate `AppBarConfiguration` plus `NavigationUI` helpers.

### 🗺️ Android-Google-Map
An osmdroid-based mapping lab that also taps into Google Play Services for location. You learn how to request runtime permissions, initialize tile sources, switch map styles, drop markers programmatically, and tie UI buttons to `FusedLocationProviderClient` updates.

### 📸 Android-Permission-Dialog
Focuses on the UX around dangerous permissions—in this case, the camera. It shows how to check `ContextCompat` status, request with `ActivityCompat`, surface rationale messages, and deep-link the user into system settings when authorization is permanently denied.

### ☰ Android-Option-Menu
A trio of menu-centric exercises. Each activity explores a different menu primitive (options menu, context menu, action mode) and how to respond to selection events. It is perfect for practicing XML menu inflation, dynamic state toggles, and theming menu items.

### 💳 Android-ZaloPay-Payment-Gateway
A merchant-style checkout sandbox that integrates the ZaloPay SDK. It includes helper classes for HMAC signing (`Helper/HMacUtil`), request constants (`AppInfo`), and callback handling so you can walk through an end-to-end payment attempt using sandbox credentials.

### 🔔 Android-Notification
Modern notification practices for API 33+: create channels, request the `POST_NOTIFICATIONS` permission via `ActivityResultLauncher`, and send richly styled notifications with large icons, inline actions, and pending intents to reopen the app.

### 🛍️ Flutter-CellphoneZ
A Flutter 3 commerce showcase that combines Provider for state management, Supabase for auth/storage, dependency injection helpers, theming, and a multi-step checkout with VNPAY Edge Functions. It is ideal if you want to compare native Android patterns with a cross-platform stack.

### 🐎 Umamuse_Rep11
A playful horse-racing mini game. You experiment with a custom game loop driven by `SeekBar`s, persisted preferences (`UserPreferences`), and repository-style abstractions for race data. It is a fun way to connect UI events, background timers, and stateful screens.

---

## 🚀 Getting started
1. Clone the umbrella repo: `git clone https://github.com/FirstAndroidJourney/FirstAndroidJourney.git`
2. Open any lab folder in Android Studio or VS Code (Flutter) and let Gradle/Flutter download dependencies.
3. Check each lab’s `README.md` or guide files for credentials, API keys, or emulator requirements.

## 🤝 Contribute
- Keep pull requests scoped to one lab, and document emulator/device details in the description.
- Attach screenshots or screen recordings when the change is UI-heavy.
- Missing a topic? Open an Issue or Discussion with your idea—we’re always looking for the next lab to build together.
