<p align="center">
  <img src="logo.png" alt="Veo Flow Automation Logo" width="140" style="border-radius: 28px; box-shadow: 0 10px 30px rgba(6, 182, 212, 0.4);" />
</p>

<h1 align="center">✨ Test-to-Image & Veo Flow Automation Chrome Extension</h1>

<p align="center">
  <strong>High-speed autonomous batch prompt generator, Text-to-Image & Video synthesis, and automated high-res downloader for Google Flow & Veo.</strong>
</p>

<p align="center">
  <a href="https://github.com/abidalidevv/Test-to-image-Chrome-extention"><img src="https://img.shields.io/badge/Version-3.5.2-06b6d4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Version 3.5.2" /></a>
  <a href="https://developer.chrome.com/docs/extensions/mv3/intro/"><img src="https://img.shields.io/badge/Manifest-V3-6366f1?style=for-the-badge&logo=webcomponents&logoColor=white" alt="Manifest V3" /></a>
  <a href="https://abidalidev.com"><img src="https://img.shields.io/badge/Author-Abid%20Ali%20Dev-8b5cf6?style=for-the-badge&logo=codeforces&logoColor=white" alt="Author Abid Ali Dev" /></a>
  <a href="https://ko-fi.com/abidalidev"><img src="https://img.shields.io/badge/Support-Ko--fi-ff5e5b?style=for-the-badge&logo=kofi&logoColor=white" alt="Support on Ko-fi" /></a>
  <img src="https://img.shields.io/badge/Platform-Chrome%20%7C%20Edge%20%7C%20Brave-3b82f6?style=for-the-badge" alt="Platform Support" />
</p>

---

## 🌟 Overview

**Test-to-Image & Veo Flow Automation** is an advanced browser extension built for creative professionals, video editors, and digital creators generating media at scale on [Google Flow](https://flow.google.com) and **Google Veo**.

Integrated directly inside your browser's native **Chrome Side Panel**, this extension automates the entire media production pipeline:
- Batch queueing prompts with randomized organic delays
- Multi-modal generation (**Text-to-Image**, **Text-to-Video**, **Image-to-Video**)
- Automatic character tile synchronization & voice attribution
- Hands-free auto-downloading of finished media in **1080p**, **2K**, and **4K** resolutions

---

## ✨ Key Features

- ⚡ **Batch Prompt Generation**: Queue hundreds of prompts sequentially or in parallel without manual copy-pasting.
- 🖼️ **Multi-Modal Generation**:
  - **Text to Image**: High-resolution image synthesis with aspect ratio controls.
  - **Text to Video & Image to Video**: Automatic camera motion, duration selection (8s+), and aspect ratios (16:9 / 9:16).
  - **Component to Video**: Feeding seed elements to synthesize cohesive video scenes.
- 💾 **Automated Media Downloader**:
  - Detects finished outputs automatically.
  - Downloads video files (`.mp4`) and image files (`.png`, `.jpg`) into designated project subfolders.
  - Auto-selects output quality presets: **1080p**, **2K**, and **4K**.
- 🛡️ **Zero-Downtime Resilience**:
  - Embedded offline fallback with **55 live Google Flow DOM selectors**—zero dependence on external config servers.
- 🌐 **Global Multi-Language Support**:
  - Full interface localization in English, Spanish, German, French, Italian, Hindi, Bengali, Arabic, Japanese, and more.
- 🎨 **Modern Cyber-Cyan & Indigo Interface**:
  - Sleek dark theme with live rendering progress meters, action logs, and quick controls.

---

## 📥 Quick Installation Guide

Runs out of the box with zero build dependencies!

### Step 1: Clone the Repository
```bash
git clone https://github.com/abidalidevv/Test-to-image-Chrome-extention.git
```
*(Or click **Code > Download ZIP** and extract the folder).*

### Step 2: Load into Chromium Browser (Chrome / Edge / Brave)
1. Open your browser and navigate to:
   ```text
   chrome://extensions
   ```
2. Enable **Developer mode** using the toggle switch in the top-right corner.
3. Click the **Load unpacked** button in the top-left corner.
4. Select the project folder.
5. The extension icon will now appear in your browser toolbar! 🎉

---

## 🕹️ How to Use

1. **Sign in to Google Flow**:
   Go to [https://flow.google.com](https://flow.google.com) in your browser.
2. **Open the Side Panel**:
   Click the extension icon in your Chrome toolbar to slide open the control panel.
3. **Configure Prompts**:
   - Choose your generation mode: *Text to Image*, *Text to Video*, or *Image to Video*.
   - Paste your prompt list (one per line) or import from CSV.
   - Adjust generation settings (Aspect Ratio, Duration, Resolution).
4. **Start Automation**:
   Click **Run / Start** and watch the extension automate prompt typing, generation monitoring, and auto-downloading.

---

## 🏗️ Technical Architecture

- **Extension Standard**: Chrome Manifest V3
- **APIs**: `chrome.sidePanel`, `chrome.downloads`, `chrome.storage.local`, `chrome.debugger`, `chrome.cookies`
- **Frontend Stack**: Vue 3, PrimeVue UI Components, Tailwind CSS Design Tokens
- **Target Platform**: Google Flow (`*://flow.google.com/*`) & Google Veo

---

## 👨‍💻 Author & Developer

Developed and maintained with ❤️ by **Abid Ali Dev**:

- 🌐 **Website**: [abidalidev.com](https://abidalidev.com)
- 💻 **GitHub**: [@abidalidevv](https://github.com/abidalidevv)
- 💼 **LinkedIn**: [in/abidalidev](https://linkedin.com/in/abidalidev)
- 🐦 **X (Twitter)**: [@abidalidevv](https://x.com/abidalidevv)
- 📸 **Instagram**: [@abidalidevv](https://www.instagram.com/abidalidevv)
- 📘 **Facebook**: [abidalidevv](https://www.facebook.com/abidalidevv)
- ☕ **Support / Ko-fi**: [ko-fi.com/abidalidev](https://ko-fi.com/abidalidev)
- 📍 **Location**: Punjab, Pakistan
- 📧 **Contact**: [abidmmp99@gmail.com](mailto:abidmmp99@gmail.com)

---

## 🤝 Contributing & Support

- Found an issue? Open a ticket on [GitHub Issues](https://github.com/abidalidevv/Test-to-image-Chrome-extention/issues).
- Want to contribute? Pull Requests are warmly welcome!
- Give this project a **⭐ Star** if it helped you automate your creative workflow!

---

## ⚖️ License & Disclaimer

Distributed under the **MIT License**. See `LICENSE` for details.

*Disclaimer: This extension is an independent automation tool developed for research, productivity, and personal workflows. It is not affiliated with, endorsed by, or sponsored by Google LLC or Alphabet Inc.*
