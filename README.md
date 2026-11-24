# VoxTranscript - Offline AI

**Offline AI speech-to-text and voice keyboard. Transcribe audio & video without usage limits.**

VoxTranscript is a fast, on-device Android application designed to convert voice, audio, and video files into accurate text and subtitles using local Whisper AI models—and let you dictate directly into any app without an internet connection. Built for low resource consumption and high efficiency, it requires no login, no cloud uploads, and has no transcription paywalls. Your audio stays strictly on your device.

## Key Features

### Offline Voice Keyboard & Floating Dictation
*   **Voice Keyboard (VoxTranscript Voice):** Dictate offline directly into WhatsApp, Notes, Search, or any other app on your phone.
*   **Floating Voice Bubble:** Quick access to offline voice-to-text from anywhere on your screen.
*   **Smart Text Insertion:** Automatically copies dictated text to your clipboard, with an optional Auto-Insert mode to paste directly into active text fields.

### Powered by On-Device Whisper AI
Choose the offline AI engine that best fits your device's hardware and accuracy needs:
*   **Tiny Engine:** Fastest and lightweight—ideal for quick voice notes and everyday dictation.
*   **Base Engine:** Recommended balance of speed and accuracy for clear lectures and interviews.
*   **Small Engine:** High accuracy for detailed audio and varied speaking styles.
*   **Medium Engine:** Maximum precision—best for complex audio, multiple accents, and noisy environments.

### Subtitle Controls, Editing & Export
*   **Subtitle Timing & Duration Control:** Customize subtitle length and pause timing, optimized for Reels, Shorts, and long-form videos.
*   **Multiple Output Formats:** Export transcripts in TXT, PDF, SRT, and VTT formats.
*   **Edit & Convert Anytime:** Fix any transcript line easily and switch between export formats without re-transcribing the audio.
*   **Auto-Translate:** Automatically translate foreign language audio into English text offline.

### Background Processing & Smart Playback
*   **High-Speed Background Queue:** Add multiple audio or video files to process sequentially using a full-power foreground service, with live progress and cancel controls in your notification bar.
*   **Smart Playback:** In-app media player with time-synced text highlighting for effortless review.
*   **Seamless Integration:** Share audio/video files directly from WhatsApp, Recorder, or any file manager using the "Open with VoxTranscript" option.
*   **Zero Friction:** Free and unlimited transcription with no account sign-up and no cloud paywalls.

## Architecture & Tech Stack

*   **Language:** Java, Kotlin, and C++ (JNI for native ML inference)
*   **AI Engine:** Whisper AI (Locally optimized for mobile inference)
*   **Memory Management:** Strictly optimized for minimal RAM usage with robust edge-case handling (such as silence detection) to prevent Out-Of-Memory (OOM) errors on lower-end devices.
*   **UI/UX:** Built with Material 3 design guidelines featuring a compact, information-dense layout tailored for productivity.

## Target Audience
Ideal for content creators generating Reels/Shorts and video subtitles, students recording lectures, journalists conducting interviews, and professionals taking meeting notes offline.

## Download
Available now on the Google Play Store: [VoxTranscript - Offline AI](https://play.google.com/store/apps/details?id=com.codebysonu.voxtranscript)

## Source Code & Support
VoxTranscript is currently a closed-source application. This repository serves as the official hub for documentation, feature updates, bug reports, and feature requests. Feel free to open an issue if you encounter any bugs or have suggestions.

---
*Built for speed, efficiency, and unlimited offline productivity.*
