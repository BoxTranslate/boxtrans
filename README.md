# 🏆 BoxTrans: AI-Powered Real-Time Screen Translator

<p align="center">
  <a href="https://github.com/BoxTranslate/boxtrans/stargazers">
    <img src="https://img.shields.io/github/stars/BoxTranslate/boxtrans?style=for-the-badge&color=yellow" alt="GitHub stars">
  </a>
  <a href="https://github.com/BoxTranslate/boxtrans/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-Freeware-blue?style=for-the-badge" alt="License">
  </a>
  <a href="https://github.com/BoxTranslate/boxtrans/releases">
    <img src="https://img.shields.io/github/v/release/BoxTranslate/boxtrans?style=for-the-badge&color=green" alt="Release">
  </a>
</p>

<p align="center">
  <b>If you like BoxTrans, please give us a ⭐ on GitHub to support the project!</b>
</p>

- A powerful, AI-driven real-time screen translation and OCR tool. Seamlessly capture, translate, and listen to any text on your screen with **GPU Acceleration**.

---

## 📺 Preview
<p align="center">
  <img src="Animation.gif" alt="BoxTrans OCR Demo" width="700" style="border-radius: 10px;">
</p>

## 🚀 Key Features

| Feature | Description |
| :--- | :--- |
| **🏎️ Turbo GPU Mode** | **NEW!** NVIDIA CUDA support for **6x faster** OCR processing (~0.2s). |
| **⚡ High-Speed OCR** | Powered by **PaddleOCR** (PP-OCRv4) for millisecond-level text recognition. |
| **🧠 DeepL AI** | Context-aware, natural translations using the world-class DeepL engine. |
| **🔊 AI Voice (gTTS)** | **Integrated FFmpeg suite** for instant, high-quality translation playback. |
| **🛡️ Smart Fallback** | Automatically detects hardware; falls back to CPU if no compatible GPU is found. |
| **🖥️ Overlay HUD** | Transparent, non-intrusive display that stays on top of your games. |
| **🎮 Gamer Friendly** | Works perfectly with story-driven games in Borderless/Windowed mode. |

---

## 🛠️ Requirements & Setup

1. **Administrator Rights:** Always run `boxtrans.exe` as **Administrator**.
2. **GPU Support (Optional):** Requires an NVIDIA GPU (Maxwell architecture or newer) for Turbo mode.
3. **DeepL API Key:** Get your free key from [DeepL Developer Portal](https://www.deepl.com/pro-api).
4. **No External Dependencies:** Version 1.4+ includes built-in **cuDNN**, **FFmpeg** and **CUDA libs**—no separate installation required!

> [!IMPORTANT]
> **Anti-Virus Note:** Due to high-performance Nuitka compilation and screen-grabbing behavior, some AV software may flag the tool. BoxTrans is 100% safe; please whitelist the folder if needed.

---

## 💻 Technical Stack
- **Engine:** Nuitka-compiled high-performance binary.
- **OCR:** PaddleOCR Framework (GPU/CPU Dual-Engine).
- **Audio:** Embedded FFmpeg, FFplay, FFprobe suite.
- **Translation:** DeepL API Integration.
- **GUI:** CustomTkinter Modern UI.

---

## 📦 Installation
1. Download the latest `boxtrans_setup.exe` from [Releases](https://github.com/BoxTranslate/boxtrans/releases).
2. Install the application (all necessary libraries are included in the 1GB package).
3. Run and enjoy the fastest translation experience!

---

## 🛡️ File Integrity (Checksum)
To ensure the security of your download, you can verify the file using the SHA256 hash:  
`sha256:4c6ce86500f8a1c19e6acfd359796088294e661c4686668ef7a51bb9aeb3f4a2`

---

## 📜 License & Privacy
This project is provided as **Freeware**.  
- **Usage:** Free for personal and non-commercial use.
- **Protection:** All intellectual property rights belong to **BoxTranslate**. 
- **Privacy:** BoxTrans works locally for OCR. Only the text you select is sent to DeepL via secure SSL for translation.

---

## 📧 Contact & Support
Developed with Python by **Thewalkry**.  

- **Github Page:** [boxtranslate.github.io](https://boxtranslate.github.io/boxtrans/)
- **Email:** herrmanndolunay@gmail.com
- **Reddit:** [u/Thewalkry](https://www.reddit.com/user/Thewalkry/)

<p align="left">
  <a href="https://buymeacoffee.com/boxtrans">
    <img src="https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Donate-orange?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white" alt="Buy Me A Coffee">
  </a>
</p>

---
<p align="center">© 2024-2025 BoxTrans Project. All rights reserved.</p>
