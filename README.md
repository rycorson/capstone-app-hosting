# D424 Capstone Project: Your Way Vacation Solutions - App Hosting

## Title and Purpose
**Application Title:** Your Way Vacation Solutions (Hosted Release)

**Purpose:** This repository is dedicated to hosting the compiled, installable `.apk` release of the *Your Way Vacation Solutions* Android application for the D424 Software Engineering Capstone. This mobile application is a comprehensive vacation planning tool designed to help users manage travel itineraries, schedule excursions, generate data reports, and set system notifications. 

## Installation Instructions
To evaluate or use the application, you must install the provided APK file onto an Android device or an Android Studio Emulator (Pixel 8 Pro running API 36 is recommended).

1. **Download the APK:** Locate the `.apk` file (e.g., `YourWayVacation.apk`) in the root directory of this repository and download it directly to your device or host machine.
2. **Install on Device/Emulator:** * If using a physical Android device, open your file manager, tap the downloaded APK, and select **Install**. *(Note: You may be prompted to allow installations from "Unknown Sources" in your device's security settings. Please allow this to proceed.)*
    * If using an Android Studio Emulator, simply drag and drop the downloaded `.apk` file from your computer's file explorer directly onto the running emulator screen. It will install automatically.
3. **Launch:** Once installed, tap the *Your Way Vacation Solutions* app icon on the home screen or app drawer to launch the application.

## Application Features Overview
* **Vacation & Excursion Management:** Full CRUD (Create, Read, Update, Delete) functionality for travel itineraries, stored securely in a local SQLite database using the Room Persistence Library.
* **Search & Reporting:** Features a dynamic search bar to filter vacations instantly and a reporting tool that generates multi-column, timestamped readouts of saved travel data.
* **Data Validation:** Implements UI-layer safeguards, including Regex sanitization to prevent special characters/empty strings and chronological logic to ensure dates are entered in the correct order.
* **System Alerts:** Allows users to schedule local system notifications to alert them on the start and end dates of their vacations, as well as on the specific days of their excursions.
* **Sharing Capabilities:** Integrates with the device's native messaging and email applications to easily share itinerary details with others.

## Source Code & Documentation
**Note:** This GitHub repository is used strictly for hosting the executable application for distribution.

The complete Java source code, JUnit testing scripts, branch history, and full technical documentation for this project are hosted on GitLab.

* **GitLab Source Code Repository:** https://gitlab.com/wgu-gitlab-environment/student-repos/rcorso6/d424-software-engineering-capstone/-/tree/working_branch?ref_type=heads
