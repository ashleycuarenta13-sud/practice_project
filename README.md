# Cacao Grade AI

## Summary
A web-based system for grading cacao beans using AI. This first checkpoint
contains the Flutter Web starter project with a Home screen and a Login
placeholder screen.

## Current stack
- Flutter Web / Dart (implemented)
- REST API (planned)
- PostgreSQL (planned)

## Project structure
lib/
- main.dart - application entry point
- app.dart - MaterialApp setup, title, and routes
- screens/ - Home and Login screens
- widgets/ - reusable UI components (AppButton, AppTextField)
- services/ - future API clients
- models/ - future data models
- routes/ - future routing helpers
- constants/ - app-wide constants (no secret credentials)

## Run locally
flutter pub get
flutter run -d chrome

## First checkpoint
Date: October 16, 2026 | Commit: 02366c7