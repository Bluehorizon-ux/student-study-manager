# Student Study Manager (Android starter project)

## Included
- Compose-based Android app UI
- Subject-wise PDF library
- PDF import through Android document picker and WhatsApp Share intent
- PDF status: Unread / In Progress / Completed
- Daily task list with completion checkboxes
- 20-question daily reasoning/aptitude challenge
- Local persistence for PDF references and tasks using SharedPreferences

## Build
1. Open this folder in Android Studio (Hedgehog or newer).
2. Allow Gradle sync and install the Android SDK Platform 35 if prompted.
3. Connect your Android phone with USB debugging enabled, or use an emulator.
4. Press Run.

## Important notes
- This is a first working starter build, not a polished Play Store release.
- PDF import uses Android's document picker. To import from WhatsApp, open a PDF in WhatsApp, tap Share, then choose Study Manager. Android may ask you to grant access.
- PDF references and tasks are stored locally. Keep the original source PDF available to Android if the provider revokes access.
- The current MCQ set is a fixed starter set of 20 sample questions. A robust daily rotating question bank, analytics history, revision notifications, and custom subject creation are planned next.
- The app launches an installed PDF viewer to open documents.
