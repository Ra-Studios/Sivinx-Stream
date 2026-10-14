# Sivinx Stream

**[Visit the website](https://ra-studios.github.io/Sivinx-Stream/)** · **[Download for Windows (v0.1.0)](https://github.com/Ra-Studios/Sivinx-Stream/releases/download/v0.1.0/Sivinx.Stream.Setup.exe)**

Sivinx Stream is a desktop voice transcription application for Windows. Hold a hotkey, speak, and release the keys to insert the transcription into the text field you are using.

The website includes a video demonstration, setup guide, frequently asked questions, and privacy information. You can browse it on a phone, tablet, or computer; the application itself runs on Windows.

## Features

- **Push-to-talk:** Hold `Ctrl + Alt` to record and release to transcribe into your active text field.
- **Cloud transcription:** Choose Deepgram or Google Gemini in Settings. Cloud engines require an internet connection and your own provider API key.
- **Offline mode:** Use local Whisper.cpp models to transcribe without sending audio to a cloud provider.
- **Customizable hotkey:** Choose a key combination that suits your workflow in Settings.
- **Desktop integration:** Access Settings from the application's system tray icon.

## Install on Windows

1. Download [Sivinx Stream Setup.exe](https://github.com/Ra-Studios/Sivinx-Stream/releases/download/v0.1.0/Sivinx.Stream.Setup.exe).
2. Run the installer and follow the setup wizard.
3. Open Sivinx Stream and configure your microphone and transcription engine in Settings.
4. For a cloud engine, enter your own provider API key. For offline transcription, complete the local model setup in the application.

The current application supports **Windows 10 and Windows 11**. See the [website](https://ra-studios.github.io/Sivinx-Stream/) for the full user guide.

## Use Sivinx Stream

1. Click inside a text field, such as a document, chat, email draft, or browser search box.
2. Press and hold `Ctrl + Alt` (or your configured hotkey).
3. Speak while holding the keys.
4. Release the keys to transcribe and insert your words at the cursor.

To switch engines or change the hotkey, open Settings from the system tray icon.

## Website files

This repository hosts the product website on GitHub Pages and distributes the Windows installer through GitHub Releases.

| File | Purpose |
| --- | --- |
| `index.html` | Website content, responsive styles, and interactive demonstrations |
| `logo.png` | Product logo |
| `video_compressed.mp4` | Application demonstration video |

The website is a static page with no build step. To preview changes locally, open `index.html` in a browser or serve the repository with a local static web server. Keep the existing release URLs, section anchors, and asset paths intact when editing the page.

## More information

- [Website and download page](https://ra-studios.github.io/Sivinx-Stream/)
- [Existing releases reference](https://github.com/RaStudios/sivinx-stream/releases)

Created by **RaStudios**.
