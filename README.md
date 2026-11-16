# DREAM 184 — Android app

A native Android (Kotlin + Jetpack Compose) offline-first daily productivity tracker.

## Features
- Daily 1–10 ratings for study, fitness, wake time, sleep and self-discipline
- Daily score out of 100
- Study hours, MCQs, gym completion, bedtime, wake-up time and reflection
- Saved history and a trend line based on real saved daily scores
- Local persistence using Android SharedPreferences (no account or internet required)

## Build
1. Install Android Studio (recent stable version).
2. Open this `DREAM184` folder in Android Studio.
3. Allow Gradle sync to complete (internet is needed for the first dependency download).
4. Connect your Android phone with USB debugging enabled, or use an emulator.
5. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. Install the generated APK on your phone.

Application ID: `com.dream184.app`

## Data
Daily records are stored locally on the device in the app's private preferences. They are not synced to the cloud. Use the History tab's backup button to re-save the local JSON data in app preferences; for a portable export/import feature, that can be added in a later version. Uninstalling the app or clearing its data may erase records, so keep device backups.
