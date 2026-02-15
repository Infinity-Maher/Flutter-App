# GDG Services App

A cross-platform Flutter application for browsing and discovering service providers, with built-in voice search powered by speech-to-text.

## Features

- **Authentication** — Login & registration screens
- **Home & Browse** — Explore available services and categories
- **Service Providers** — View provider profiles with ratings and experience
- **Voice Search** — Search using speech-to-text (Arabic language supported)
- **Responsive UI** — Adaptive layout via `flutter_screenutil`
- **Splash Screen** — Animated splash with video/GIF

## Tech Stack

| Layer | Library |
|---|---|
| Navigation | `go_router` |
| Networking | `dio` + `pretty_dio_logger` |
| UI | `flutter_screenutil`, `flutter_svg`, `google_fonts`, `carousel_slider` |
| Media | `video_player` |
| Voice | `speech_to_text`, `record` |
| Storage | `sqflite`, `path_provider` |
| Permissions | `permission_handler` |

## Project Structure

```
lib/
├── main.dart
├── core/
│   ├── apis/          # Dio HTTP helper
│   ├── common_widgets/
│   ├── routes/        # GoRouter configuration
│   └── theme/
└── feture/
    ├── auth/          # Login & Register
    ├── main/          # Home screen
    ├── search/        # Category browsing & voice search
    ├── sevice_view/   # Service provider listings
    └── splash/        # Splash screen
```

## Getting Started

### Prerequisites

- Flutter SDK `>=3.10.3`
- Dart `>=3.10.3`

### Install & Run

```bash
# Clone the repo
git clone https://github.com/Infinity-Maher/Flutter-App.git
cd app

# Install dependencies
flutter pub get

# Run the app
flutter run
```

## License

This project is for educational / GDG community use.
