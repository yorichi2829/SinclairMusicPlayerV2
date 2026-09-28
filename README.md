# Sinclair Music 2.0

Android Studio project using Kotlin + Jetpack Compose + Media3.

V2 additions:
- Persistent favorites with DataStore
- Persistent playlist names
- Sorting by title, artist, album, duration
- Search
- Rich Now Playing sheet
- Shuffle/repeat controls wired to Media3
- Background playback through MediaSessionService
- Album-art-ready local library
- Rescan library action
- Dedicated Home / Library / Favorites / Playlists navigation
- Offline-first architecture

Production roadmap:
1. Persist playlist membership and track ordering.
2. Implement real progress slider and elapsed/remaining time.
3. Add sleep-timer countdown service.
4. Extract embedded ID3 artwork where albumart provider is unavailable.
5. Add lyrics file lookup (.lrc), synchronized scrolling, and manual lyrics editor.
6. Add folder browser and SAF import.
7. Add Android Auto and headset/Bluetooth handling tests.
8. Add instrumentation/unit tests and release signing.
