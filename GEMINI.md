# Project: ListNest

## Project Overview
This is a Flutter application named "ListNest", designed for managing lists. It features dynamic theming, including an AMOLED dark mode, and persists user data using `shared_preferences`. The application allows users to create, archive, pin, and delete lists. It utilizes `dynamic_color` for enhanced theming capabilities and provides a user-friendly interface for list organization.

## Building and Running
This project is a standard Flutter application. To build and run it, you can use the following commands in your terminal:

*   **Install dependencies:**
    ```bash
    flutter pub get
    ```
*   **Run the application:**
    ```bash
    flutter run
    ```
*   **Build for Android:**
    ```bash
    flutter build apk
    ```
*   **Build for iOS:**
    ```bash
    flutter build ipa
    ```
*   **Run tests:**
    ```bash
    flutter test
    ```
*   **Analyze code for linting issues:**
    ```bash
    flutter analyze
    ```

## Development Conventions
*   **Linting:** The project uses `package:flutter_lints/flutter.yaml` for code analysis, encouraging good coding practices and consistency.
*   **Theming:** Implements dynamic theming with `dynamic_color` and supports light, dark, and AMOLED dark modes.
*   **UI Framework:** Leverages Material Design 3 for its user interface components.
*   **Font:** Uses the "Rubik" font family for text.
*   **State Management:** Local state management is handled within `StatefulWidget`s, and `shared_preferences` is used for persisting user settings and list data.