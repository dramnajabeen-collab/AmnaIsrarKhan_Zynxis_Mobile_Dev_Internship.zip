<div align="center">

# 📱 Zynxis Welcome App
### Week 1 — Environment Setup & Hello World
**Zynxis Mobile App Development Internship**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

</div>

---

## 📋 Overview

The **Zynxis Welcome App** is the first deliverable of the Zynxis Mobile Development Internship. It introduces the Zynxis brand through a clean, dark-themed welcome screen — built entirely with **Flutter** and tested on Android.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🖼️ Logo Display | Zynxis logo rendered at the top of the screen |
| 📝 Company Bio | A short description introducing Zynxis |
| 📞 Contact Us | A button that opens a dialog with email & phone contact info |
| 🎨 Custom Theme | Dark charcoal/slate color scheme throughout |
| 🛡️ Graceful Fallback | Falls back to a placeholder icon if the logo asset fails to load |

---

## 🛠️ Tech Stack

| Layer | Tool |
|---|---|
| Framework | Flutter (Dart) |
| IDE | Android Studio |
| Platform | Android |
| Test Device | Android Emulator — Medium Phone (Android 17, "CinnamonBun") |

---

## 📂 Project Structure

```
week1_setup_welcomeapp/
├── android/                 # Native Android project files
├── assets/
│   └── images/
│       └── zynxis_logo.png  # App logo asset
├── lib/
│   └── main.dart            # Main application code (UI + logic)
├── test/                    # Default Flutter test folder
├── pubspec.yaml             # Dependencies & asset declarations
└── README.md                # Project documentation
```

---

## 🚀 How to Run

**1. Install prerequisites**
- [Flutter SDK](https://docs.flutter.dev/get-started/install) added to your system PATH
- Android Studio with the Flutter & Dart plugins installed

**2. Get dependencies**
```bash
flutter pub get
```

**3. Connect a device**
Plug in a physical Android phone with USB debugging enabled, *or* launch an Android emulator from Android Studio's Device Manager.

**4. Run the app**
```bash
flutter run
```
Or simply click the green **▶ Run** button in Android Studio.

---

## 🎨 Color Palette

| Color | Hex | Usage |
|---|---|---|
| ⬛ Background | `#1E1E24` | Screen background |
| 🌑 Card / Primary | `#2C2F38` | Dialog & surface backgrounds |
| 🔵 Accent | `#4A90E2` | Buttons & highlights |

---

## 📦 Deliverables

- ✅ App screenshots (Welcome screen + Contact Us dialog)
- ✅ Full source code
- ✅ This README

---

<div align="center">

**Built with 💙 for the Zynxis Internship Program**

</div>
