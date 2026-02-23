# MindVault

MindVault is a personal knowledge management demo with two interfaces:

- A web demo for storing and querying information
- A Kotlin Android app for mobile interaction flow

The project is focused on concept validation, UI behavior, and learning outcomes.

## Overview

MindVault demonstrates a simple retrieval workflow:

1. Store information
2. Ask questions in natural language
3. Receive AI-generated responses from stored context

During development demos, the web interface was exposed with ngrok.

## Key Features

- Data capture and retrieval demo flow
- Simple AI-assisted query interface
- Android client prototype in Kotlin (activity/XML based)
- Clean UI-first approach for rapid iteration

## Screenshots

### Web UI

<img width="1280" height="686" alt="MindVault Web UI" src="https://github.com/user-attachments/assets/28732caf-cebb-4b2d-8750-b5e9a0e4c782" />

### Android UI

<img width="240" height="580" alt="Android Screen 1" src="https://github.com/user-attachments/assets/27c6e2b6-7e4a-4d6c-b7f3-67df46333a6f" />
<img width="240" height="580" alt="Android Screen 2" src="https://github.com/user-attachments/assets/cd8b2eb2-70aa-4c8a-9714-ce578957f591" />
<img width="240" height="580" alt="Android Screen 3" src="https://github.com/user-attachments/assets/663f8e03-4307-4c1a-95ea-b65403a358cf" />

## Android App Scope

The Android module is intentionally lightweight and built to validate client-side UX:

- Kotlin + Android SDK
- Activity-based navigation
- XML layouts
- Basic interaction/testing screens

## Project Scope and Limits

This repository intentionally does not include internal backend/AI workflow details, production deployment setup, or sensitive service configuration.

## Local Run Guidance

### Android

1. Open the repository in Android Studio.
2. Sync Gradle dependencies.
3. Run on emulator/device.

### Web Demo

The original web demo setup is not fully packaged in this repository.

To reproduce a similar flow:

1. Run a local web frontend.
2. Connect your own AI service endpoint.
3. Optionally expose locally using ngrok for testing.

## Security

- No credentials should be committed.
- Keep secrets in local environment/config only.
- Use sanitized or non-personal test data.

## Contributing

Contributions are welcome for:

- UI improvements
- Documentation clarity
- Code organization

Please avoid adding secrets, internal service credentials, or private workflow details.

## Support

- [Android Developers](https://developer.android.com/docs)
- [ngrok Docs](https://ngrok.com/docs)
- GitHub Issues in this repository
