diff --git a/README.md b/README.md
index 0bd485024eb127704feb31895d7b8f35f3e9d593..b61e94ca1dcd1f94562e9fe158ac0274873e80a8 100644
--- a/README.md
+++ b/README.md
@@ -1 +1,41 @@
-# 111
+# Flutter Card App
+
+This project showcases a simple Flutter application for displaying playing card data.
+
+## Prerequisites
+
+- **Flutter SDK**: Version 3.10 or later is recommended. Install Flutter from the [official site](https://docs.flutter.dev) and run `flutter doctor` to verify your environment.
+- **Device or Emulator**: Connect a physical device or launch an emulator from Android Studio or Xcode.
+
+To run the project on a connected device or emulator:
+
+```bash
+flutter run
+```
+
+To build release binaries:
+
+```bash
+flutter build apk   # Android
+flutter build ios   # iOS (requires macOS)
+```
+
+Run unit tests (if any) with:
+
+```bash
+flutter test
+```
+
+## Folder Structure
+
+```
+lib/
+├── models/      # Data models
+├── providers/   # State management classes
+├── screens/     # App screens
+└── widgets/     # Reusable widgets
+```
+
+## Card Images
+
+Placeholder card images can be placed in `assets/cards/`. You may create your own or use royalty-free resources such as Unsplash. Ensure that any images you include comply with their respective licenses; the included samples are under a CC0 license.
