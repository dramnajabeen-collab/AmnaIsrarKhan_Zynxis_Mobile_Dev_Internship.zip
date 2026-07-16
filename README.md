# Week 1 — Environment Setup & "Zynxis Welcome App"

## Overview
This is the Week 1 deliverable for the Zynxis Mobile App Development Internship.
It is a Flutter application called Zynxis Welcome App, built and tested on a physical/emulated Android device using Android Studio.

## Features
- Zynxis company logo displayed at the top of the screen
- A short company bio describing Zynxis
- A "Contact Us" button that opens a dialog showing the company's email and phone number
- Custom dark charcoal/slate theme applied across the app

## Tech Stack
- Framework: Flutter (Dart)
- IDE: Android Studio
- Platform: Android
- Testing device: Android Emulator (Medium Phone, Android 17 "CinnamonBun")

## Project Structure
```
week1_setup_welcomeapp/
├── android/              # Native Android project files
├── assets/
│   └── images/
│       └── zynxis_logo.png
├── lib/
│   └── main.dart         # Main application code (UI, logic)
├── test/                 # Default Flutter test folder
├── pubspec.yaml          # Project dependencies & asset declarations
└── README.md             # This file
```

## How to Run
1. Make sure the [Flutter SDK](https://docs.flutter.dev/get-started/install) is installed and added to your PATH.
2. Open this project folder in **Android Studio** (with the Flutter/Dart plugins installed).
3. Connect a physical Android device (with USB debugging enabled) or start an Android emulator.
4. Run the following commands from the project root, or simply click the **Run ▶** button in Android Studio:
   ```
   flutter pub get
   flutter run
   ```
5. The app will launch showing the Zynxis welcome screen. Tap "Contact Us" to view contact details.

## Deliverables Included
- Screenshots of the app running on a device (Welcome screen + Contact Us dialog)
- This README
- Full source code

## Notes
- The app uses `Image.asset` with an `errorBuilder` fallback, so if the logo asset is ever missing or fails to load, a placeholder icon is shown instead of crashing the app.
- Theme colors: background `#1E1E24`, card/primary `#2C2F38`, accent button `#4A90E2`.
