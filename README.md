# Mini Spotify

Mini Spotify is a bootcamp music app project with an Android Kotlin frontend and a Ktor backend service.

## Project Structure

```text
MiniSpotify/
  android/   Android music browsing app
  backend/   Ktor API serving feed, playlist, and song data
```

## Features

- Android Home and Favorite tabs
- Album feed loaded from backend API
- Playlist detail screen
- Favorite albums stored locally with Room
- Backend endpoints for feed and playlists
- Static song resource serving

## Tech Stack

- Kotlin
- Android
- Jetpack Compose
- Navigation Component
- Retrofit
- Room
- Hilt
- Ktor
- Gradle

## Run Backend

```bash
cd backend
./gradlew run
```

The backend runs on `http://localhost:8080`.

## Build Android App

Make sure Android SDK is installed and `android/local.properties` points to your local SDK path.

```bash
cd android
./gradlew assembleDebug
```

The Android emulator uses `http://10.0.2.2:8080` to reach the backend running on your computer.







