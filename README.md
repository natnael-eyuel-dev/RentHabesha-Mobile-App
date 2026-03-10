# RentHabesha Traditional Clothing Renting Mobile App

RentHabesha is a cross-platform mobile application designed to simplify the rental process for traditional Ethiopian clothing. The platform allows clothing owners and boutiques to list outfits for rent, while renters can browse, search, and book clothing for special occasions. Alongside its practical rental features, the project also promotes Ethiopian cultural heritage through a modern digital solution.

## Project Overview

This version of RentHabesha represents the broader mobile app project built with **Flutter** and **Dart**, making it distinct from the earlier Android-focused implementation. It combines a shared mobile codebase with backend support to deliver a more complete application experience across platforms.

## Team Information

- **Section:** 2
- **Group Members:**
  - **Feven Muluken** - `UGR/8442/15`
  - **Mekdelawit Gebre** - `UGR/1386/15`
  - **Natnael Eyuel** - `UGR/4424/15`
  - **Sifen Biyadgelgn** - `UGR/4937/15`
  - **Yeabsera Tilahun** - `UGR/1418/12`

## Contents

- **`lib/`**: Main Flutter application source code written in Dart.
- **`assets/`**: Images, icons, and other supporting app resources.
- **`android/`**, **`ios/`**, **`web/`**, **`linux/`**, **`macos/`**, **`windows/`**: Platform-specific files generated and maintained by Flutter.
- **`rent-habesha-backend/`**: Backend project directory for server-side logic and API support.
- **`test/`**: Test files for application validation.
- **`pubspec.yaml`**: Flutter dependencies and project metadata.
- **`analysis_options.yaml`**: Dart and Flutter linting configuration.
- **`README.md`**: Project overview and documentation.

## Key Features

- **Clothing Listings (CRUD)**
  - Create listings with photos, outfit type, size, price, and location.
  - Browse and filter available traditional clothing items.
  - Update listing information when details change.
  - Delete unavailable listings.

- **User Profiles (CRUD)**
  - Create profiles for renters, outfit owners, and boutiques.
  - View and manage user information.
  - Update contact details and preferences.
  - Delete profiles when no longer needed.

- **Admin Dashboard (CRUD)**
  - Manage users, listings, and app activity.
  - Update platform records and settings.
  - Remove listings or accounts that violate platform rules.

## Technology Stack

- **Mobile App:** Flutter
- **Programming Language:** Dart
- **Backend:** JavaScript with Express
- **Platforms:** Android, iOS, Web, Linux, macOS, Windows

## Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/natnaeleyuel/RentHabesha-Mobile-App-Flutter.git
   ```
2. Open the Flutter project in **VS Code** or **Android Studio** with Flutter support installed.
3. Install Flutter dependencies:
   ```sh
   flutter pub get
   ```
4. Run the app:
   ```sh
   flutter run
   ```
5. Configure and run the backend inside `rent-habesha-backend/` if server-side functionality is required.

---

*Created collaboratively by the RentHabesha team, including [natnaeleyuel](https://github.com/natnaeleyuel)*
