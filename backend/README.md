# Spotify Backend

Spotify Backend is a Ktor service from the bootcamp Spotify project. It serves static music feed and playlist JSON data for the Android Spotify app.

## Features

- Root health endpoint
- Feed endpoint
- Playlist list endpoint
- Playlist detail endpoint by album id
- Static song resource route

## Tech Stack

- Kotlin
- Ktor
- Kotlin serialization
- Gradle

## API Endpoints

- `GET /`
- `GET /feed`
- `GET /playlists`
- `GET /playlist/{id}`
- `GET /songs/{fileName}`

## Run Locally

```bash
./gradlew run
```

The server runs on `http://localhost:8080`.

## Test

```bash
./gradlew test
```
