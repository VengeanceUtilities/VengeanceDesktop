<div align="center">

<p align="center">
  <img src="https://github.com/VengeanceUtilities.png" alt="Vengeance Desktop Logo" width="120" style="border-radius: 50%;">
</p>

# ⚡ Vengeance Desktop

**Hybrid Music Streaming, Realtime DSP Engine & Liquid Glass UI for Windows**

[![Version](https://img.shields.io/badge/VERSION-1.0.0-purple?style=for-the-badge)](https://github.com/VengeanceUtilities/VengeanceDesktop/releases/latest)
[![Platform](https://img.shields.io/badge/PLATFORM-WINDOWS%20x64-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/VengeanceUtilities/VengeanceDesktop/releases)
[![Website](https://img.shields.io/badge/WEBSITE-vengeanceutilities.de-blue?style=for-the-badge)](https://vengeanceutilities.de)
[![Instagram](https://img.shields.io/badge/INSTAGRAM-@upperechelon.dev-E4405F?style=for-the-badge&logo=instagram)](https://instagram.com/UpperEchelon.dev)
[![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red?style=for-the-badge)](LICENSE)

<br/>

<a href="https://github.com/VengeanceUtilities/VengeanceDesktop/releases/latest">
  <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge&logo=windows&logoColor=white" height="42" alt="Download Vengeance Desktop" />
</a>

</div>

---

## Overview

**Vengeance Desktop** brings **YouTube Music**, **SoundCloud**, **Spotify playlists**, and your **local audio library** together in a single, ad-free desktop client. Built with Electron and a custom Web-Audio DSP pipeline, version **1.0.0** features a GPU-composited Liquid Glass UI with an animated moonlit sky backdrop, live BPM & musical key detection, a click-through Gaming HUD overlay, and built-in offline downloads with waveform trimming.

---

## Screenshots

<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/33a1c3b1-25d5-4291-b93c-3107a101667f" width="100%" alt="Vengeance Desktop - Liked Songs & Liquid Glass UI" />
      <br />
      <sub><b>Liked Songs & Liquid Glass UI</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/0be42c8a-1d0c-4237-8c12-0b6dabeb7119" width="100%" alt="Vengeance Desktop - Lyrics & Cover Stage" />
      <br />
      <sub><b>Lyrics & Cover Stage</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/024652cc-ec97-46e9-879b-4b05887b2514" width="100%" alt="Vengeance Desktop - Synced Lyrics View" />
      <br />
      <sub><b>Synced Lyrics & TV Karaoke</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/e957dab8-c9f4-4205-a5a3-52238e3f09b9" width="100%" alt="Vengeance Desktop - Click-Through Gaming HUD" />
      <br />
      <sub><b>Click-Through Gaming HUD</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/148c1b9e-8d80-4201-9d4d-61cad0d7f9d0" width="100%" alt="Vengeance Desktop - Multi-Platform Playlist Import" />
      <br />
      <sub><b>Multi-Platform Playlist Import</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/ca221eb7-4bea-4ac4-b2d9-9cf26b6a259b" width="100%" alt="Vengeance Desktop - Settings & Integrations" />
      <br />
      <sub><b>Settings & Integrations</b></sub>
    </td>
  </tr>
</table>

---

## What's Inside v1.0.0

### Hybrid Streaming & Library Sync
- **Multi-Platform Playback:** Stream seamlessly from YouTube Music, YouTube, SoundCloud, and local audio files (`MP3`, `FLAC`, `WAV`, `OPUS`, `M4A`, `OGG`) in one unified app.
- **Playlist Import & Sync:** Import playlists from Spotify, YouTube / YouTube Music, SoundCloud, Apple Music, Deezer, Yandex Music, VK, and TikTok with background sync support.
- **Offline Cache & Downloads:** Built-in `yt-dlp` and `FFmpeg` export pipeline (`MP3`, `FLAC`, `M4A`, `OPUS`, `WAV`) with automatic cover art embedding, visual waveform trimmer, and optional audio FX bake-in.

### Realtime DSP & Audio Tools
- **Sub-Bass Harmonic Exciter:** Dedicated low-end harmonic generator with tunable frequency targets (`58 Hz Deep`, `70 Hz Crusher`, `88 Hz Punch`) and built-in soft limiter.
- **Mid/Side Stereo Widener & 10-Band EQ:** Real-time stereo stage control (`0%` Mono to `200%` Wide) alongside a 10-band equalizer and custom presets.
- **Live BPM & Key Analyzer:** Real-time FFT spectral flux and chroma analysis displaying live BPM and musical key directly in the player and HUD.
- **In-App Audio Output Switcher:** Switch output devices (speakers, headsets, virtual mixers, or Vengeance Audio Bridge) directly from the playbar without touching Windows settings.

### Liquid Glass UI & Gaming HUD
- **Click-Through Gaming HUD (`Ctrl+Shift+H`):** Focus-free floating overlay for borderless games with persistent saved position across restarts, hover playback controls, live progress bar, and BPM/Key badges.
- **Moonlit Sky & Specular Glass:** GPU-composited volumetric clouds, twinkling stars, 3D specular hover cards, animated MP4/WebM video covers, and full Light/Dark + dynamic accent theming.
- **Synced Lyrics & TV Karaoke:** Word-by-word and line-synced lyrics (LRCLIB, Genius, Musixmatch, KuGou, NetEase) with fullscreen karaoke mode.
- **Discord Rich Presence & Customization:** Native Discord RPC with album art and timestamps, built-in Monaco CSS editor, plugin support, and live performance diagnostics (`Ctrl+Shift+D`).

---

## Installation

1. Open the [Latest Release](https://github.com/VengeanceUtilities/VengeanceDesktop/releases/latest) page.
2. Download the latest Windows installer (`Vengeance-Desktop-Setup-1.0.0.exe`) or portable archive.
3. Run the installer and launch **Vengeance Desktop**.
4. *(Optional)* On first launch, let the built-in setup fetch `yt-dlp` and `FFmpeg` for downloads and audio conversion.

---

## Tech Stack

- **Core:** Electron, Node.js, HTML5 / CSS3 / Vanilla JavaScript
- **Audio & DSP:** Web Audio API (Custom Sub-Bass Exciter, Mid/Side Matrix, Soft Limiter, FFT Analyzer)
- **Media Pipeline:** `yt-dlp`, `FFmpeg`, Local HTTP Streaming & Audio Proxy Server
- **Integrations:** Discord RPC, Spotify Web Session Sync, Monaco Editor

---

## License

**All Rights Reserved** — Copyright (c) 2026 VengeanceUtilities (UpperEchelon). See the `LICENSE` file for details.

> Actively maintained and updated regularly. Found a bug or have a feature idea? Reach out on Discord or Instagram:
>
> [![Discord](https://img.shields.io/badge/Discord-Join%20Server-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/GCU3SU5fKH)
