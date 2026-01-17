# Vision
Below is a clean, professional **README.md** suitable for a public GitHub repository. It explains the purpose, features, setup, and limitations clearly, without overselling or misrepresenting the project.

---

# 👁️ Vision — AI Visual Assistant (Web Prototype)

Vision is a browser-based AI assistant designed to support **accessibility, daily organization, and voice-first interaction**, with a focus on assisting visually impaired users.
It combines voice recognition, text-to-speech, local data storage, and Google Gemini AI to provide an all-in-one personal assistant experience—entirely in the browser.

This project is currently a **front-end prototype** intended for learning, experimentation, and future expansion.

---

## ✨ Features

### 🚨 Emergency Assistance

* One-tap emergency activation
* Custom emergency contact and message
* Audio confirmation and visual alert feedback

> *Note: This is a simulation. No real calls or messages are sent.*

### 🎤 Voice Assistant (AI-Powered)

* Speech-to-text via browser APIs
* AI-generated responses using **Google Gemini**
* Spoken responses with adjustable voice speed
* Context-aware assistance (schedule, health, items, etc.)

### 📅 Schedule Manager

* Add, view, and delete events
* Date, time, and notes support
* Persistent storage using `localStorage`

### ❤️ Health Tracker

* Log health metrics (e.g. blood pressure, medication, heart rate)
* Timestamped entries
* Quick review of recent records

### 💰 Finance Manager

* Track income and expenses
* Categories and notes
* Automatic balance summary

### 📍 Item Locator

* Save item locations (e.g. keys, wallet)
* Search items by name
* Spoken location feedback when an item is found

### ⚙️ Settings

* Emergency contact configuration
* Emergency message customization
* Voice speed control for speech synthesis

---

## 🧠 Technologies Used

* **HTML5 / CSS3 / Vanilla JavaScript**
* **Web Speech API**

  * `SpeechRecognition`
  * `SpeechSynthesis`
* **Google Gemini API**
* **Browser Local Storage**
* Responsive UI with accessibility considerations

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/vision-ai-assistant.git
cd vision-ai-assistant
```

### 2. Add Your Gemini API Key

Open the HTML file and replace:

```js
const GEMINI_API_KEY = 'YOUR_GEMINI_API_KEY_HERE';
```

with your actual API key from Google AI Studio.

### 3. Run the App

Simply open the HTML file in a modern browser:

* Chrome (recommended)
* Edge
* Brave

> ⚠️ Voice recognition requires a Chromium-based browser.

---

## ⚠️ Limitations & Notes

* This project runs **entirely client-side**
* No backend or authentication
* Emergency functionality is **simulated**
* Voice recognition is browser-dependent
* Data is stored locally per browser/device
* Not intended for medical or emergency-critical use

---

## 🔒 Privacy

* No user data is sent anywhere except:

  * Voice prompts sent to Google Gemini (when enabled)
* All personal data is stored locally in the browser

---

## 📌 Project Status

**Prototype / Proof of Concept**

Planned future improvements:

* Backend integration
* Real emergency service hooks
* Camera-based visual assistance
* Offline mode
* User accounts and cloud sync

---

## 📄 License

This project is released under the **MIT License**.
You are free to use, modify, and distribute it with attribution.

---

## 🙌 Acknowledgments

* Google Gemini API
* Web Speech API
* Accessibility-first design principles
