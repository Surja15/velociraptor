## velociraptor

Hosted on: https://surja15.github.io/velociraptor/
## 🚀 Speed Reader (RSVP-based)

A minimal, distraction-free **speed-reading web app** built using **Rapid Serial Visual Presentation (RSVP)**.  
It displays text one word at a time at a fixed focal point, helping readers reduce eye movement and improve reading efficiency.

Designed to be **fast, lightweight, and fully client-side**.

---

### ✨ Features
- 🧠 RSVP reading mode (one word at a time)
- 🎯 Fixed pivot letter highlighting for visual focus
- ⏱️ Custom Words-Per-Minute (WPM) control
- 📄 Large, scrollable text input
- ⏯️ Start / Pause / Resume controls
- 🌙 Dark UI optimized for long reading sessions
- 📱 Responsive design (desktop & mobile)

---

### 🛠️ Technical Details
- Frontend: HTML, CSS, JavaScript
- Rendering: Single-word stream with fixed alignment
- Timing Engine: WPM-based interval scheduler
- Pivot Logic: Dynamic character index calculation per word
- Layout: CSS transforms + absolute positioning
- Dependencies: None
- Data: Fully local (no tracking, no storage, no network calls)

---

### 📐 How It Works
Text is tokenized into words and streamed sequentially at a user-defined rate.  
Each word is aligned around a calculated pivot character to keep the reader’s gaze fixed, minimizing saccadic eye movement.

---

