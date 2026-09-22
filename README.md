# A Client/Server Example - Flutter / NestJS (2026)

This repository refers to the course **“A Client/Server Example - Flutter / NestJS (2026)”**, published at:

**https://stahe.github.io/flutter-nestjs-sept-2026/**

## Overview

This document adapts the educational application **RdvMedecins** (doctor’s appointment scheduling)—which has already been covered in courses on Angular, React, and Vue.js—to current technologies. It presents a mobile version here: a **Flutter** (Dart) client that relies on a **NestJS** (TypeScript) server exposing a JSON API protected by JWT authentication (ADMIN / USER roles).

This document is intended for readers who are already familiar with at least one web framework (Angular, React, or Vue.js) and are learning about Flutter by comparison: each Flutter concept is linked to its equivalent in those frameworks.

The course covers:

- setting up the development environment (VSCode, Flutter SDK, Android Studio, Android SDK, preparing an Android phone and an emulator, `flutter doctor`);
- installing and running the app’s NestJS server (MySQL database, configuration, testing with a browser and with Postman);
- an introduction to Flutter (widgets, `StatelessWidget`/`StatefulWidget`, state management with `provider`, the Dart language);
- a detailed, file-by-file walkthrough of the Flutter client for the RdvMedecins app;
- porting the same source code to three target families: mobile (Android/iOS), desktop (Windows/macOS/Linux), and web, addressing mobile-specific challenges (server address, unencrypted HTTP traffic, narrow screens);
- a conclusion on what was built and avenues for further development.

## Authors

- **Lead Author:** IA Claude (Anthropic)
- **Reviewer:** Serge Tahé

