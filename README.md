# Sivinx Stream

Voice typing for Windows. Speak into documents, messages, emails, and other editable text fields using a keyboard shortcut or the floating recording widget.

[Download for Windows](https://github.com/Ra-Studios/Sivinx-Stream/releases/latest/download/Sivinx.Stream.Setup.exe) · [Website & demonstration](https://ra-studios.github.io/Sivinx-Stream/) · [All releases](https://github.com/Ra-Studios/Sivinx-Stream/releases)

## Features

- **Push-to-talk:** Hold `Ctrl + Alt`, speak, and release to finish and insert your transcription.
- **Mouse recording:** Start from the floating microphone, then choose **Finish & Paste** or **Cancel**.
- **Offline transcription:** Process speech on your computer with the included Whisper.cpp English model.
- **Cloud processing:** Configure supported transcription, live typing, and formatting providers using your own API keys.
- **Transcript preview:** View recognized text in the widget as your selected model returns it. Preview timing depends on the provider and model.
- **Personal vocabulary:** Add preferred spellings for names, products, and specialist terms.
- **Writing preferences:** Choose writing modes and application-specific preferences. Some modes require a formatting provider.
- **Optional history:** Enable searchable text history with configurable retention.
- **Desktop controls:** Choose your microphone, customize your shortcut, adjust recording sounds, and access shortcuts from the system tray.
- **Remembered placement:** Keep the recording widget docked where you prefer.

## Requirements

- Windows 10 or Windows 11, 64-bit.
- A working microphone and Windows microphone permission.
- Internet access and your own provider API key for cloud features.

The included offline speech model supports **English**. Other languages, including Urdu, depend on the selected cloud provider and model.

## Install

1. Download [Sivinx.Stream.Setup.exe](https://github.com/Ra-Studios/Sivinx-Stream/releases/latest/download/Sivinx.Stream.Setup.exe).
2. Run the installer and follow the setup wizard.
3. Open Settings from the recording widget or system tray.
4. Choose your microphone and processing preferences.
5. For cloud features, enter and save your own provider API keys.

For fully offline dictation, select local transcription and disable live cloud processing and cloud formatting.

## Start speaking

### Using your keyboard

1. Click inside the text field where you want to write.
2. Hold `Ctrl + Alt`, or your configured shortcut.
3. Speak, then release the keys.
4. Wait for processing to finish and review the inserted text.

### Using your mouse

1. Click inside your destination text field.
2. Hover over the floating widget and click the microphone.
3. Speak, then click the check mark to **Finish & Paste**.
4. To discard the recording, click the cross to **Cancel**.

If automatic insertion does not work in a particular application, click inside the destination field and press `Ctrl + V`. You can also recover the latest result from Home.

## Processing and privacy

- **Local transcription:** Speech recognition runs on your computer.
- **Cloud transcription or live typing:** Audio is sent to your selected provider.
- **Local transcription with cloud formatting:** Speech is recognized locally, then the transcript is sent to your selected formatting provider.
- **API keys:** Saved credentials are stored in Windows Credential Manager on your computer. Your saved keys are not included in the distributed installer.
- **History:** Saved text history is optional and protected using Windows account encryption.

Cloud providers have their own privacy policies, model availability, limits, and possible usage charges. Review important names, numbers, and wording before sending a transcription.

The application's About page includes its Privacy Policy, Terms & Conditions, and FAQ.

## Updates

Users normally download and run only **Sivinx.Stream.Setup.exe**.

The accompanying `.sig` and `update.json` files support verification and in-app updates; users do not need to open them.

Version **0.1.1** configures signed updates for future releases. When a newer release is available, the application checks on startup and can offer **Update Now** or **Later**. An internet connection is required.

Users upgrading from **0.1.0** should download and install **0.1.1** manually once.

## Help

Open **How It Works** in Settings for recording instructions, processing explanations, and recovery guidance.

For microphone problems, check the selected input device and Windows microphone permissions. For cloud connection problems, review the provider, model, and saved credentials in Advanced settings.

## About this repository

This repository hosts the product website on GitHub Pages and distributes the Windows installer through GitHub Releases.

| File | Purpose |
|---|---|
| `index.html` | Website content, styles, and interactions |
| `logo.png` | Product logo |
| `video_compressed.mp4` | Application demonstration video |

The website is a static page with no build step. Preview it by opening `index.html` in a browser or serving the folder with a local static web server.

The website can be viewed on phones, tablets, and computers. The desktop application runs on Windows.

## More information

- [Website and download page](https://ra-studios.github.io/Sivinx-Stream/)
- [Existing releases reference](https://github.com/ra-Studios/sivinx-stream/releases)

Created by **RaStudios**.
