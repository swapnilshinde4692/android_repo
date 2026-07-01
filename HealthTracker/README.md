# HealthTracker

A comprehensive Android application for tracking and managing your health metrics.

## Features

- Track daily health activities
- Monitor health metrics (steps, calories, heart rate, etc.)
- View health analytics and statistics
- Set and track fitness goals
- Local data storage with Room database

## Project Structure

```
HealthTracker/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── kotlin/com/healthtracker/
│   │       │   ├── MainActivity.kt
│   │       │   └── ui/theme/
│   │       │       ├── Theme.kt
│   │       │       └── Type.kt
│   │       └── AndroidManifest.xml
│   └── build.gradle
├── settings.gradle
├── build.gradle
└── gradle.properties
```

## Requirements

- Android SDK 34
- Minimum SDK: 24
- Target SDK: 34
- Kotlin 1.9.0+
- Java 11

## Build & Run

### Prerequisites
- Android Studio (latest version)
- Android SDK tools
- Gradle 8.0+

### Steps
1. Clone the repository
2. Open project in Android Studio
3. Build the project: `./gradlew build`
4. Run on emulator or device: `./gradlew installDebug`

## Dependencies

### Core Android
- androidx.core:core-ktx
- androidx.appcompat:appcompat
- com.google.android.material:material

### Jetpack Compose
- androidx.compose.ui:ui
- androidx.compose.material3:material3
- androidx.activity:activity-compose
- androidx.lifecycle:lifecycle-runtime-ktx

### Data Storage
- androidx.room:room-runtime
- androidx.room:room-ktx

### Testing
- junit:junit
- androidx.test.ext:junit
- androidx.test.espresso:espresso-core

## License

MIT License

## Author

HealthTracker Team
