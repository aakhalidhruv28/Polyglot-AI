# 🌐 Polyglot AI - Language Translation Tool

A fast, responsive, and mobile-first language translation web application powered by the **Google Gemini API**.

**Polyglot AI** allows users to seamlessly translate text between **30+ global and regional Indian languages**. It features an intuitive, clean interface with built-in **Text-to-Speech (TTS)** capabilities and quick **copy-to-clipboard** functionality.

---

## ✨ Features

### 🧠 AI-Powered Translation

Utilizes the advanced **Google Gemini** model for highly accurate, context-aware translations.

### 🌍 Extensive Language Support

Supports major global languages such as:

* English
* Spanish
* French
* German
* Italian
* Portuguese
* Chinese
* Japanese
* Korean

And a comprehensive suite of Indian regional languages including:

* Hindi
* Bengali
* Marathi
* Tamil
* Telugu
* Gujarati
* Kannada
* Malayalam
* Punjabi
* Odia
* Assamese
* Urdu
* Sanskrit

### 🔍 Auto-Detect Language

Automatically identifies the source language so you don't have to select it manually.

### 📱 Mobile-First Design

Fully responsive user interface built with **Tailwind CSS**, ensuring a seamless experience across:

* Desktop
* Tablet
* Mobile Devices

### 🗣️ Text-to-Speech (TTS)

Listen to translated text using the browser's native **SpeechSynthesis API**.

### 📋 One-Click Copy

Copy translated text instantly with a secure, fallback-ready clipboard implementation.

### 🔔 Toast Notifications

Clean and non-intrusive success/error messages without using browser `alert()` dialogs.

---

## 🛠️ Tech Stack

| Category     | Technology                         |
| ------------ | ---------------------------------- |
| Frontend     | HTML5, CSS3, Vanilla JavaScript    |
| Styling      | Tailwind CSS (CDN)                 |
| Icons        | Lucide Icons (CDN)                 |
| AI Model     | Google Gemini (`gemini-2.5-flash`) |
| APIs         | Google Gemini API                  |
| Browser APIs | Web Speech API, Clipboard API      |

---

## 🚀 Setup & Installation

This project is built as a **self-contained single-file application**.

✅ No npm installation required
✅ No build tools required
✅ No dependencies to install

### Step 1: Get a Gemini API Key

To enable translations, you'll need a free Google Gemini API key.

1. Visit **Google AI Studio**
2. Sign in with your Google account
3. Click **Get API Key**
4. Create a new API key
5. Copy the generated key

---

### Step 2: Configure the Application

1. Download or clone this repository.

```bash
git clone https://github.com/aakhalidhruv28/Polyglot-AI.git
```

2. Open `index.html` in your preferred code editor.

3. Locate the following line inside the `<script>` section:

```javascript
const apiKey = ""; // Enter Your API Key
```

4. Replace it with your Gemini API key:

```javascript
const apiKey = "AIzaSyYourActualAPIKeyGoesHere...";
```

5. Save the file.

---

### Step 3: Run the Application

Simply open the file in your browser:

```text
index.html
```

Supported browsers:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

You're ready to start translating! 🎉

---

## 💡 How to Use

### 1. Select Source Language

Choose the language you are typing in or leave it as **Detect Language**.

### 2. Enter Text

Type or paste the text you want translated into the left input box.

### 3. Select Target Language

Choose the desired translation language from the target language dropdown.

### 4. Translate

Click the **Translate** button.

### 5. Interact With Results

After translation:

* 🔊 Click the speaker icon to hear the pronunciation
* 📋 Click the copy icon to copy the translated text

---

## 📸 Application Highlights

✅ AI-Powered Translation
✅ 30+ Supported Languages
✅ Automatic Language Detection
✅ Mobile Responsive Design
✅ Text-to-Speech Support
✅ Copy to Clipboard
✅ Toast Notifications
✅ Fast & Lightweight

---

## ⚠️ Important Note

The **Text-to-Speech (TTS)** feature relies on the voices installed on your local operating system and browser.

Some regional languages may not be spoken correctly or may be unavailable if the corresponding voice pack is not installed on your device.

---

## 👨‍💻 Developer Information

### Dhruv Patel

Passionate developer focused on building intuitive, user-friendly, and performant web applications using modern technologies.

Feel free to explore my work and connect professionally.

🌐 **Portfolio:** [View Now!](https://developer.uxtech.in) <br>
💼 **Linkedin:** [Follow Me!](https://www.linkedin.com/in/drpatel-ai)

---

## ❤️ Support

If you find this project useful:

⭐ Star the repository

🍴 Fork the project

📢 Share it with others

---

## 📄 License

This project is open-source and available under the **MIT License**.

---
