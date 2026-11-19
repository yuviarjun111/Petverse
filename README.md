# PETVERSE v1.0 – Playable starter build

This package contains a playable offline-first PETVERSE game experience and an Android Studio WebView wrapper project.

## Play immediately
Open `index.html` in a modern browser on your phone or computer. Progress is saved in browser local storage.

## Build an Android APK
1. Install Android Studio (current stable) and Android SDK Platform 35.
2. Open this `PETVERSE` folder in Android Studio.
3. Allow Gradle sync to finish.
4. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Find the APK under `app/build/outputs/apk/debug/app-debug.apk`.
6. Transfer it to your Android phone and install it. You may need to allow installation from that file manager.

## Included playable features
- Pet home dashboard and companion selection
- Feed, play, pet and train interactions
- 10 adoptable animals with rarity and coin costs
- Daily habit checklist and custom habits
- Habit XP, coins, happiness and loyalty rewards
- Pet level progression
- Daily mission reward
- Local persistence using browser storage

## Scope note
This is a functional first playable release, not the entire large-scale game specification. Advanced 3D worlds, unique species-specific animation rigs, Room database migration, sound, notifications and full QA are not included yet. The Android wrapper stores progress in the WebView's local storage on the device.
