# Spotify

Spotify is a bootcamp music app project with an Android Kotlin frontend and a Ktor backend service.

## Project Structure

```text
Spotify/
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
# Spotify

Spotify is a bootcamp music app project with an Android Kotlin frontend and a Ktor backend service. The backend serves feed and playlist data, and the Android app displays album sections, playlist detail screens, and favorite albums.

## Project Structure

```text
Spotify/
  android/   Android app
  backend/   Ktor backend service
```

## Features

- Android music browsing app
- Home and Favorite tabs
- Playlist detail screen
- Room local favorite storage
- Retrofit backend integration
- Hilt dependency injection
- Ktor backend endpoints for feed and playlists
- Static song resources served by backend

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

Backend runs on `http://localhost:8080`.

## Build Android App

Make sure Android SDK is installed and create `android/local.properties` with your SDK path:

```properties
sdk.dir=/path/to/your/android/sdk
```

Then build:

```bash
cd android
./gradlew assembleDebug
```

The Android emulator uses `http://10.0.2.2:8080` to reach the backend running on your computer.
