# CampusCare Android

A simple native Android campus helpdesk demonstration built with Java, XML layouts and SQLite.

## Features
- Submit student complaints and generate local references such as CH-0001.
- Track complaints and view status history.
- View complaints saved on the device.
- Demonstration staff login (`staff` / `staff123`).
- Staff dashboard with status updates.

## Project details
- Package / namespace: `com.example.myapplication`
- Minimum SDK: 24
- Java compatibility: 11
- Local database: SQLite (`CampusCare.db`)

## Open in Android Studio
Open the extracted project folder in Android Studio and allow Gradle sync. This bundle contains the source code and Gradle build configuration but intentionally does not include generated IDE files, build outputs, local.properties, SQLite databases, or the Gradle wrapper JAR/scripts. If importing as a standalone project, let Android Studio create/use its Gradle wrapper, or copy the original `gradlew`, `gradlew.bat`, and `gradle/wrapper/` files from your existing Android Studio project.

## Demo login
Username: `staff`
Password: `staff123`

This is a local academic demonstration only, not production authentication.

## Data scope
Complaints are stored locally on the Android device. This demo does not synchronize with the CampusCare website, Neon or Render.
