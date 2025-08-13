<p align="center">
  <img src="https://github.com/user-attachments/assets/07c3453c-0a80-41fc-bf45-e779af19588a" alt="NoCaptchaAI Logo" width="128">
</p>

<h1 align="center">NoCaptchaAI CAPTCHA Solver</h1>
<h3 align="center">The Official Browser Extension for Chrome, Firefox, Edge, & Brave</h3>

<p align="center">
  <a href="https://chromewebstore.google.com/detail/nocaptcha-ai-auto-captcha/hbnbcapieoandchfgacedlkjpdbbejgb"><img src="https://img.shields.io/badge/Chrome_Web_Store-_-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Chrome Web Store"></a>
  &nbsp;
  <a href="https://addons.mozilla.org/en-US/firefox/addon/nocaptcha-ai-captcha-solver/"><img src="https://img.shields.io/badge/Firefox_Add--ons-_-%23FF7139?style=for-the-badge&logo=firefox-browser&logoColor=white" alt="Firefox Add-ons"></a>
  &nbsp;
  <a href="https://github.com/noCaptchaAi/NoCaptcha-Ai-Browser-Extension/releases"><img src="https://img.shields.io/badge/Download_for_Edge-%230078D7?style=for-the-badge&logo=microsoft-edge&logoColor=white" alt="Edge Add-ons"></a>
</p>

<p align="center">
  <a href="https://github.com/noCaptchaAi/NoCaptcha-Ai-Browser-Extension/releases">
    <img src="https://img.shields.io/github/v/release/noCaptchaAi/NoCaptcha-Ai-Browser-Extension?style=for-the-badge&label=Latest%20Release&color=brightgreen" alt="Latest Release">
  </a>
  &nbsp;
  <a href="https://github.com/noCaptchaAi/NoCaptcha-Ai-Browser-Extension/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/noCaptchaAi/NoCaptcha-Ai-Browser-Extension?style=for-the-badge&color=blue" alt="License">
  </a>
</p>

The official browser extension for **NoCaptchaAI**, bringing fast and reliable CAPTCHA solving directly to your browser. Once installed and configured, it automatically enhances your browsing experience by handling CAPTCHA challenges for you.

---

### 📋 Table of Contents

*   [Screenshot Gallery](#-screenshot-gallery)
*   [Key Features](#-key-features)
*   [Installation](#-installation)
*   [Configuration](#️-configuration)
*   [Resources & Community](#-resources--community)
*   [Changelog](#-changelog)

---

## 🖼️ Screenshot Gallery

| Main Interface & Settings | Proxy & User-Agent Configuration |
| :----------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://github.com/user-attachments/assets/90ac7683-5450-4b0f-8cb3-171f28f35b18" alt="Main UI" width="350">                 | <img src="https://github.com/user-attachments/assets/042ab090-881a-46ae-94ac-2d4162286340" alt="Proxy Settings" width="350">          |
| <img src="https://github.com/user-attachments/assets/6476ddba-2953-4b5f-9c08-0a269ff7190a" alt="Compact View 1" width="350">             | <img src="https://github.com/user-attachments/assets/782bd8c1-a79c-4df7-affd-e741e1e0dbbb" alt="Compact View 2" width="350">              |

## ✨ Key Features

*   **Automated CAPTCHA Solving**: Handles various CAPTCHA types quickly and efficiently.
*   **Proxy Support**: Configure custom proxies to route your requests.
*   **Custom User-Agent**: Set a custom user-agent string for your requests.
*   **Intuitive UI/UX**: A clean and easy-to-use interface.
*   **Resilient Service**: Includes backup API endpoints to ensure service accessibility in all regions.
*   **Easy Configuration**: Simple JSON-based setup for your API key.

## 🚀 Installation

For the easiest installation, use the official store links at the top of this page. For manual installation (e.g., for development):

1.  Download the latest release from the **[Releases Page](https://github.com/noCaptchaAi/NoCaptcha-Ai-Browser-Extension/releases)**.

---

### **For Chrome / Edge / Brave**

1.  Download the **`.zip`** file from the releases page.
2.  Extract the contents of the `.zip` file into a dedicated folder.
3.  Navigate to `chrome://extensions` (for Chrome) or `edge://extensions` (for Edge).
4.  Enable **"Developer mode"** using the toggle switch, usually in the top-right corner.
5.  Click the **"Load unpacked"** button and select the folder where you extracted the extension.

### **For Firefox**

1.  Download the **`.xpi`** file from the releases page.
2.  Navigate to `about:addons` in Firefox.
3.  Click the gear icon (⚙️) on the right, then select **"Install Add-on From File..."**.
4.  Select the downloaded `.xpi` file to install the extension.

## ⚙️ Configuration

To use the extension, you must add your personal API key.

1.  Get your API key from the **[NoCaptchaAI Dashboard](https://dash.nocaptchaai.com/?ref=github)**.
    <img src="https://github.com/user-attachments/assets/e783f7c6-e9de-4439-a062-2ca9c164b90d" alt="API Key on Dashboard" width="450">

2.  In the extension folder you downloaded, find and open the `defaultConfig.json` file.
    <img src="https://github.com/user-attachments/assets/356f45c7-8240-456f-a366-302a34071da0" alt="defaultConfig.json file" width="450">

3.  Paste your API key into the `apiKey` field and save the file.

Success! If you installed via "Load unpacked" (Chrome/Edge), reload the extension from the `chrome://extensions` page for the changes to take effect.

## 🔗 Resources & Community

*   🌐 **Website**: Visit our official site at [NoCaptchaAI.com](https://www.nocaptchaai.com)
*   📊 **Dashboard**: Manage your account and view stats at the [NoCaptchaAI Dashboard](https://dash.nocaptchaai.com)
*   🛠️ **Developer API Docs**: Explore our powerful [API for automation](https://docs.nocaptchaai.com).
*   💬 **Community**: Join us on [Telegram](https://t.me/your_telegram_link) or [Discord](https://discord.gg/your_discord_link).

---

## 📝 Changelog

### **v1.4.0**
*   **Feature**: Added full support for custom Proxies.
*   **Feature**: Added support for custom User-Agents.
*   **Improvement**: General UI and performance enhancements.

### **v1.3.0**
*   **Major Rewrite**: Complete overhaul of the extension's codebase.
*   **Improvement**: Updated and modernized UI & UX.
*   **Feature**: Added backup API endpoints for users in Algeria and Russia to ensure service continuity.
