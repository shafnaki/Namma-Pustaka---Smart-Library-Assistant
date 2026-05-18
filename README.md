# Namma Pustaka - Smart Library Assistant 🌸

**Namma Pustaka** is a modern, Android-based library management application designed to digitize and streamline library operations in educational settings. It replaces traditional manual registers with a smart digital interface featuring QR code integration, AI-powered book discovery, and gamified reading tracking.

## 🚀 Key Features

*   **Smart Cataloging:** Browse books by categories like Story, Science, History, and more with real-time availability status.
*   **QR Code Scanner:** Integrated scanner (using Google ML Kit) for instantaneous book borrowing and returns.
*   **AI Assistant:** Automatically fetches book details from online sources if the book is not found in the local database.
*   **Lending Management:** Comprehensive tracking of borrowing history, return dates, and automated fine calculation.
*   **Leadership Board:** Encourages reading habits among students by ranking them based on pages read and books completed.
*   **Admin Dashboard:** Centralized view for librarians to monitor library stats, manage inventory, and collect fines via UPI.
*   **Multi-Role Access:** Dedicated interfaces for Students and Teachers/Administrators.
*   **UI/UX:** Modern Jetpack Compose UI with support for Dark Mode and beginner-friendly interactions.

## 🛠 Tech Stack

*   **Language:** Kotlin
*   **UI Framework:** Jetpack Compose
*   **Database:** Room (SQLite) for local persistence
*   **Cloud:** Firebase Firestore (for cross-device sync) & Analytics
*   **AI:** Google Generative AI (Gemini) integration for book assistance
*   **Scanning:** Google ML Kit Barcode Scanning & CameraX
*   **Navigation:** Jetpack Compose Navigation
*   **Image Loading:** Coil



## 📦 Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/shafnaki/Namma-Pustaka---Smart-Library-Assistant.git
    ```
2.  Open the project in **Android Studio (Ladybug or newer)**.
3.  Add your `google-services.json` file to the `app/` directory (from Firebase Console).
4.  Build and run the application on an Android device (API 26+).

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---
Developed with ❤️ by [Shafna K I](https://github.com/shafnaki)
