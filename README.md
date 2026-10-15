# 🌙 Dark Speech & Translation Assistant

An interactive, distraction-free web application designed for capturing spoken notes, lectures, and research thoughts in a pitch-black display mode. Developed specifically for mobile execution, this tool eliminates visual screen glare, saves phone battery, and automatically converts speech into clean, shareable text without relying on external API credits.

---

## 🌟 Key Features

* **Dark Screen Mode**: Blanks out the display with a pitch-black overlay to prevent visual fatigue and save battery power during long study sessions.
* **One-Thumb Floating Stop Button**: Features a large, comfortable, raised stop control positioned specifically for natural one-handed holding on mobile devices.
* **Free In-Browser Speech Recognition**: Uses native browser speech processing (`webkitSpeechRecognition`) to transcribe spoken thoughts in real-time with zero API costs or balance limits.
* **Multilingual Speech Support**: Seamlessly captures voice notes in English, Hindi, or mixed conversational phrases.
* **Instant Native Sharing**: Includes a one-tap Android share button to send transcripts directly to WhatsApp, Google Drive, Gmail, or notes apps.
* **Local Text Export**: Allows one-click downloading of captured transcripts directly to your phone's `Downloads` folder as `.txt` files.

---

## 📱 Mobile-First Design & Architecture

This application is optimized for smooth operation on mobile web browsers (Google Chrome / Samsung Internet) on devices like the **Samsung Galaxy S20 FE**. By hosting the single HTML file over secure HTTPS via **GitHub Pages**, the tool runs with full microphone access without complex software installation.

---

## 🚀 How To Use

1. **Launch the Web App**: Open your live GitHub Pages link on your mobile phone browser.
2. **Start Dark Session**: Tap **Start Dark Recording** and grant microphone access when prompted.
3. **Speak Naturally**: Focus on your lecture or research thoughts while the screen remains pitch black to preserve focus and battery.
4. **Stop Recording**: Tap the raised **⏹ STOP RECORDING** button with your thumb.
5. **Review & Export**: View your transcribed text on screen, then tap **📲 Share Transcript** or **💾 Save Notes as Text File**.

---

## 🛠️ Technology Stack

* **HTML5 / Modern CSS3**: Responsive flexbox layout with blur filters and animated dark overlay indicators.
* **JavaScript (Web Speech API)**: Handles real-time speech-to-text recognition directly in the client browser.
* **Web Share & Blob API**: Triggers native mobile share drawers and local text file generation.
* **GitHub Pages**: Fast, secure HTTPS web hosting.

---

*Created to enhance productivity, research workflows, and skill adoption for faculty, researchers, and students.*
