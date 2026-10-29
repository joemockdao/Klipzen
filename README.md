# Klipzen

<p align="center">
  <img src="screenshots/icon.png" alt="Klipzen Logo" width="128" height="128" style="border-radius: 28px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);"/>
</p>

<h3 align="center">Klipzen</h3>

<p align="center">
  <b>A free, native video editor for Mac — trim, style, caption, and export in minutes.</b>
</p>

<p align="center">
  <a href="https://github.com/joemockdao/Klipzen/releases/latest">
    <img src="https://img.shields.io/github/v/release/joemockdao/Klipzen?style=flat-square&color=0066cc&label=Version" alt="Latest Version">
  </a>
  <img src="https://img.shields.io/badge/macOS-14.0%2B-brightgreen?style=flat-square&logo=apple" alt="macOS Support">
  <img src="https://img.shields.io/badge/SwiftUI-Native-orange?style=flat-square&logo=swift" alt="Built with SwiftUI">
  <img src="https://img.shields.io/badge/Apple-Notarized-success?style=flat-square&logo=apple" alt="Apple Notarized">
  <img src="https://img.shields.io/badge/License-Free-blue?style=flat-square" alt="100% Free">
  <a href="https://github.com/joemockdao/Klipzen/releases">
    <img src="https://img.shields.io/github/downloads/joemockdao/Klipzen/total?style=flat-square&color=brightgreen&label=Downloads" alt="Total Downloads">
  </a>
  <a href="https://github.com/joemockdao/Klipzen/stargazers">
    <img src="https://img.shields.io/github/stars/joemockdao/Klipzen?style=flat-square&color=yellow&label=Stars" alt="GitHub Stars">
  </a>
</p>

<p align="center">
  <a href="https://github.com/joemockdao/Klipzen/releases/latest">
    <img src="https://img.shields.io/badge/Download-Latest_Release-0066cc?style=for-the-badge&logo=apple&logoColor=white" alt="Download Klipzen">
  </a>
</p>

---

Klipzen is a fast, native SwiftUI video editor for Mac, made for people who want to cut, style, and share a video in minutes. Import multiple clips, trim and reorder them, add filters, transitions, captions, and music, then export in vertical, square, or widescreen formats ready for social media — all running locally on your Mac.

**New in 1.1:** edit your videos by talking to your own AI agent (Claude Code, Codex, OpenCode, or Antigravity). Ask for “a 30-second reel with subtitles” and watch the edit happen live in Klipzen. [Learn more ↓](#-edit-with-your-ai-agent-mac)

![Klipzen editor](screenshots/editor.png)

> [!NOTE]
> **Free & ad-free:** Klipzen is a personal, independent project. No subscriptions, no watermarks, no ads, no account required.

<p align="center">
  ⭐ If Klipzen is useful to you, <a href="https://github.com/joemockdao/Klipzen/stargazers">starring the repo</a> helps other people find it.
</p>

---

## 🔒 Trust & Security (Apple Notarized)

* **Signed & Notarized**: Every release is signed with a valid Apple **Developer ID** and notarized by Apple's automated notary service, so it opens without security warnings on macOS.
* **On-Device Processing**: Video composition and export run entirely through Apple's native AVFoundation — your clips are never uploaded anywhere. Automatic subtitles, subtitle translation, and voice translation also run on-device via Apple's Speech and Translation frameworks (macOS 26+ for translation on Mac).
* **AI Agents Stay Local**: The AI agent connection is off until you switch it on. It only accepts connections from your own Mac (never from the network) and every request needs a secret key that only you can copy. Keep in mind that your agent may send what it reads from the project (for example a transcript or a preview frame) to its own AI service, under that service's terms.
* **Closed-Source Notice**: This repository hosts precompiled releases only — the source code is private. Independent security audits are always welcome.

---

## 🤖 Edit with Your AI Agent (Mac)

Klipzen can be driven by the AI agent you already use. Describe the video you want, and the agent edits it inside the app while you watch: every change appears live on the timeline, can be undone with ⌘Z, and can be fine-tuned by hand afterwards.

<p align="center">
  <img src="screenshots/agents.png" alt="Klipzen AI Agents panel: three guided steps to turn on the connection, connect your agent, and try a request" width="60%"/>
</p>

**What you can ask for**
* *“Make a 30-second vertical reel from this project with animated subtitles.”*
* *“Remove the silences and the filler words, then add background music.”*
* *“Translate the subtitles into Spanish and dub the voice.”*
* *“Add my logo in the corner and export for Instagram.”*
* *“Review the project and tell me what to improve before exporting.”*

**Set up in three steps**
1. In the project list, click the ✨ button and switch on **Allow control from AI agents**.
2. Pick your agent, click **Copy command**, and paste it once in Terminal (for Codex, **Copy configuration** and paste it into its config file). The panel shows a green check when the agent connects.
3. Open your agent and ask for an edit. Keep Klipzen open while it works.

**Supported agents:** [Claude Code](https://claude.com/product/claude-code), [Codex](https://github.com/openai/codex), [OpenCode](https://opencode.ai), and [Antigravity](https://antigravity.google). The agent itself (and any account or subscription it requires) is not part of Klipzen.

---

## 🚀 Key Features

### 🎬 Timeline Editing
Import multiple video clips from Photos, Files, or your library, arrange them on a multi-track timeline, and trim, split, reorder, or multi-select clips for batch actions (delete, mute, speed change). Full undo/redo history and autosave — pick up right where you left off.

### 🎨 Color Filters & Grading
Apply one of 11 built-in cinematic presets (Cinematic, Vintage, Atmospheric, B&W, Faded, Cold, Warm, Drama, Chrome, Sunset, Matte), or fine-tune brightness, contrast, saturation, and more with manual color grading sliders.

### ✂️ Transitions
Add Fade, Cross Dissolve, Slide, Wipe, or Zoom transitions between clips, with adjustable duration — live preview included.

### 🔤 Titles & Animated Captions
Drop in quick-start title, lower-third, subtitle, and badge presets, or fully customize text style and animation. Generate word-by-word animated captions (karaoke, pop, spotlight styles) automatically from speech.

### 🗣️ Auto Subtitles, Translation & Voice Dubbing
On-device speech recognition generates subtitles automatically from your video's audio. Translate subtitles into another language, or go further with **Voice Translation**: recognize the spoken audio, translate it, and generate a dubbed voiceover with natural-sounding voices — all without leaving the app.

### 🖼️ Photos to Video
Turn still photos into video clips with a smooth Ken Burns pan-and-zoom effect and crossfade transitions.

### 🫥 Face & Plate Blurring
Automatically track and blur faces or license plates across a clip to protect privacy before sharing.

### 🔊 Audio Tools
Import background music, record a voiceover, generate text-to-speech narration, fine-tune fade in/out, and duck music automatically under dialogue. Waveform preview included.

### 📐 Canvas & Aspect Ratio
Choose your canvas aspect ratio and background, then override it per export with one-tap presets for **TikTok/Reels (9:16)**, **Instagram (1:1)**, or **YouTube (16:9)** — without touching your original project.

### 🖥️ Built for the Mac
Full menu bar commands with keyboard shortcuts, and drag & drop: drop videos or audio from Finder onto the editor, or onto the project list to start a new project.

### 📤 Flexible Export
Export at Maximum Quality (HEVC/MOV), High Quality (1080p/MP4), or Standard Quality (720p/MP4), and save straight to your Mac or Photos library.

---

## 📸 Screenshots

<p align="center">
  <img src="screenshots/export.png" alt="Klipzen export options" width="80%"/>
</p>
<p align="center">
  <img src="screenshots/toolbar.png" alt="Klipzen editing toolbar: import, voiceover, text to speech, split, canvas, text, subtitles, captions" width="80%"/>
</p>

---

## 🛠️ Requirements & Installation

### Requirements
* **macOS 14.0** or later (macOS Sonoma and newer)
* **macOS 26.0** or later is required for the automatic subtitle translation and voice translation features specifically — everything else in the app works from macOS 14.0 up.
* **AI agent editing** requires one of the supported agents installed on the same Mac (see [Edit with Your AI Agent](#-edit-with-your-ai-agent-mac)). It is optional: the app works fully without it.
* Klipzen will ask for **Photos** access to import and save videos, and for **Microphone** / **Speech Recognition** access only if you record a voiceover or generate automatic subtitles.

### Installation
1. Download the latest `.dmg` from the [Latest Releases](https://github.com/joemockdao/Klipzen/releases/latest) page.
2. Open the DMG file and drag **Klipzen** into your **Applications** folder.
3. Launch the app and grant permissions when prompted.

---

## 🌍 Languages

Klipzen automatically follows your macOS system language:
* 🇮🇹 Italian
* 🇬🇧 English

---

## 📬 Feedback & Support

Found a bug or have a feature idea? Your feedback shapes Klipzen.
* **Open an issue**: [github.com/joemockdao/Klipzen/issues](https://github.com/joemockdao/Klipzen/issues)
* **Start a discussion**: [github.com/joemockdao/Klipzen/discussions](https://github.com/joemockdao/Klipzen/discussions)

### Other Apps by the Developer
* 🧹 [CleanMacJoe](https://github.com/joemockdao/CleanMacJoe) — Free macOS disk cleaner, duplicate finder, and app uninstaller.
* 🛌 [SleepRec](https://apps.apple.com/it/app/sleeprec/id1528754113) — Advanced sleep analysis and rest tracker.
* 📝 [JoeNote](https://apps.apple.com/it/app/joenote/id6738133424) — Sleek notes and reminders organizer.
* 🔗 [Linktree](https://linktr.ee/joemockdevmobile) — All my projects in one place.

---

## 📄 License

Free to use. This repository hosts precompiled releases only. Source code is not public.
