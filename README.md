# 📱 Flutter Course Projects

[![Flutter](https://img.shields.io/badge/Flutter-3.47.1-blue.svg?logo=flutter)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.13.1-0175C2.svg?logo=dart)](https://dart.dev)
[![Projects](https://img.shields.io/badge/Projects-7%20Standalone%20Apps-brightgreen.svg)]()

This repository contains **7 standalone Flutter applications** built as part of the Udemy Flutter & Dart Course. Each folder represents an independent, fully runnable Flutter project with its own `pubspec.yaml`, `lib/main.dart`, and platform runners.

---

## 📂 The 7 Projects Overview

| # | Project Folder | Topic & Description | How to Run |
|:---:|---|---|---|
| **01** | [`01_hello_world_app/`](01_hello_world_app/) | **Building Your First App: "Hello World"**<br>Scaffold, AppBar, Container (color red), Center, and styled Text. | `cd 01_hello_world_app && flutter run` |
| **02** | [`02_random_color_app/`](02_random_color_app/) | **Stateful Widget & Random Color Generator**<br>StatefulWidget lifecycle, dynamic RGB calculation (`Random().nextInt(256)`), luminance contrast formula for text/FAB, `setState()`. | `cd 02_random_color_app && flutter run` |
| **03** | [`03_navigation_auth_app/`](03_navigation_auth_app/) | **Navigation, Auth Flow & Named Routes**<br>3s Splash delay (`Future.delayed`), pushReplacement, Login with validation, Registration with automatic back button, Dashboard receiving username argument, centralized named routes (`onGenerateRoute`). | `cd 03_navigation_auth_app && flutter run` |
| **04** | [`04_sqlite_notes_app/`](04_sqlite_notes_app/) | **SQLite Notes App (Local Database MVC)**<br>Local SQLite storage: Note Model, Singleton `DatabaseHelper`, Controller, `FutureBuilder` NotesListScreen, Add/Edit Note Form. | `cd 04_sqlite_notes_app && flutter run` |
| **05** | [`05_quotes_app/`](05_quotes_app/) | **Quotes App (GetX + REST API + JSON Parsing)**<br>HTTP package integration, QuickType model parsing `q` (quote) and `a` (author), reactive `QuotesController` with `quotes.obs`, `Obx` reactive UI, refresh FAB. | `cd 05_quotes_app && flutter run` |
| **06** | [`06_todo_api_crud/`](06_todo_api_crud/) | **Todo CRUD App (REST API without GetX)**<br>Pure `StatefulWidget` & `setState()`, HTTP CRUD operations (GET, POST, PUT, DELETE), `Expanded` row with text field + add button, `CheckboxListTile` with leading checkbox, trailing delete. | `cd 06_todo_api_crud && flutter run` |
| **07** | [`07_firestore_user_management/`](07_firestore_user_management/) | **Cloud Firestore User Management CRUD**<br>Cloud Firestore real-time data storage, `StreamBuilder` listening to collection snapshots, dual-mode Form (Insert vs Update by `selectedId`), document deletion. | `cd 07_firestore_user_management && flutter run` |

---

## 🚀 How to Run Any Project

1. Open terminal and navigate to the project folder you want to run:
   ```bash
   cd 01_hello_world_app
   # or
   cd 04_sqlite_notes_app
   # or
   cd 07_firestore_user_management
   ```

2. Fetch dependencies:
   ```bash
   flutter pub get
   ```

3. Run the application:
   ```bash
   flutter run -d chrome
   # or for connected device / emulator:
   flutter run
   ```
