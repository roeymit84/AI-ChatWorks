# AI ChatWorks - Version 1.0.0

Pioneering prompt management and bi-directional text control for ChatGPT, Claude, and Gemini. Your ultimate AI workflow companion.

AI ChatWorks is a comprehensive browser extension designed to enhance AI chatbot workflows for users of all languages. With specialized RTL support, intelligent prompt management, and productivity optimization tools, it transforms how you interact with leading AI platforms.

---

### Core Problem Solved

Modern AI chat interfaces are built primarily for Left-to-Right (LTR) languages. This creates a frustrating experience for users working with Right-to-Left (RTL) languages like Hebrew and Arabic. Text inputs and AI-generated outputs often remain misaligned, hindering readability and workflow.

AI ChatWorks solves this problem completely while adding a suite of powerful productivity features for all users.

---

### Key Features

#### 1. Intelligent Text Direction
* **Automatic RTL/LTR Detection:** Instantly detects and applies the correct text alignment for both your inputs and the AI's responses.
* **Enhanced Canvas Support:** Full bi-directional text support for complex "Canvas" editors and artifacts in ChatGPT and Claude.
* **Dynamic Content Awareness:** Real-time formatting ensures that even streaming AI responses are perfectly aligned as they appear.

#### 2. The Ultimate Prompt Library
* **Unlimited Local Storage:** Your entire prompt library is stored locally using your browser's high-capacity storage, removing restrictive cloud limits.
* **Full-Featured Management:** A beautiful, full-screen interface to create, edit, search, and organize your prompts.
* **Folder Organization:** Group your prompts into custom, color-coded folders for easy access.
* **Favorites & Recents:** Quickly access your most-used and favorite prompts.
* **Customizable Layouts:** Choose between compact, comfortable, or list views.
* **Usage Analytics:** See at a glance which prompts are your most effective with built-in usage statistics.
* **Backup & Restore:** Easily import and export your entire library, ensuring your prompts are always safe and portable.

#### 3. Seamless & Polished UI
* **Modern Design:** A clean, intuitive interface with smooth animations that feels premium and easy to use.
* **Dedicated Settings Panel:** A standalone, tabbed window to manage appearance, data, and advanced settings without cluttering your chat view.
* **Quick Access Panel:** A collapsible side panel gives you instant control over text alignment and access to your prompt library.

---

### Supported Platforms
* ChatGPT (chat.openai.com & chatgpt.com)
* Claude (claude.ai)
* Google Gemini (gemini.google.com)

---

### Installation

**1. Official Version (Recommended)**
* Install the extension directly from the [Chrome Web Store](link-to-your-store-page).

**2. From Source (for Developers)**
* Clone this repository: `git clone https://github.com/roeymit84/AI-ChatWorks.git`
* Open Chrome and navigate to `chrome://extensions/`.
* Enable "Developer mode" in the top right corner.
* Click "Load unpacked" and select the cloned repository folder.

---

### Getting Started

1.  After installation, navigate to a supported platform like ChatGPT.
2.  The AI ChatWorks side panel will appear on the right. Click the power icon to enable the extension for the site. The page will reload.
3.  Type in the chat input box. The extension will automatically detect and align your text (e.g., for Hebrew or Arabic).
4.  Open the **Prompt Library** from the side panel to manage and use your saved prompts.
5.  Click the **Settings** icon in the side panel to customize themes, language, and other features.

---

### Feedback and Contribution

This project thrives on community feedback! If you encounter a bug, have a feature request, or would like to contribute, please feel free to:
* Contact the developer directly at [roey.tech.ai@gmail.com](mailto:roey.tech.ai@gmail.com).

---

### Technical Architecture

* **Manifest V3:** Built on the modern and secure browser extension platform.
* **Service Worker (`background.js`):** Manages extension state, icon updates, and cross-tab communication.
* **Local-First Storage:** Settings are stored in `chrome.storage.sync`, while the high-capacity prompt library resides in `chrome.storage.local` for performance and privacy.
* **Modular Design:** The codebase is cleanly separated into single-responsibility modules for state, UI, RTL logic, and data management, ensuring the extension is stable and easy to maintain.

---

### Changelog

**Version 1.0.0 (October 07, 2025)**
* Official public release!
* NEW: Standardized versioning and prepared all package files for the Chrome Web Store.
* FIX: Completed all Hebrew translations for a fully localized experience.
* FIX: Corrected an issue where the Prompt Library modal would incorrectly flip its entire layout for RTL languages. The UI layout now remains consistent (LTR) while text content correctly aligns.
* IMPROVEMENT: Completely rewrote and updated the README documentation to reflect the latest feature set and architecture.
