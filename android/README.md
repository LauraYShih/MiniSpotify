# Spotify Android

Spotify Android is a music browsing app built from the bootcamp Spotify project. It connects to the Spotify backend service, displays album sections, supports playlist detail screens, and stores favorite albums locally.

## Features

- Bottom navigation with Home and Favorite tabs
- Home feed loaded from backend API
- Playlist detail screen
- Favorite album persistence with Room
- Compose UI inside Android fragments
- Dependency injection with Hilt
- Retrofit networking

## Tech Stack

- Kotlin
- Android
- Jetpack Compose
- Navigation Component
- Retrofit
- Room
- Hilt
- Coil

## Backend

Run the companion backend project first:

```bash
cd ../../spotify_backend
./gradlew run
```

The Android emulator uses `http://10.0.2.2:8080` to reach the backend running on your computer.

## Build

Make sure Android SDK is installed and `local.properties` points to your local SDK path.

```bash
./gradlew assembleDebug
```

## Notes

`local.properties` is local machine configuration and should not be committed.
