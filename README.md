# eyes-front-monitor
A lightweight, privacy-first browser tool that uses your webcam to monitor attention and alert you when you look away.
# 👀 Eyes Front — Webcam Attention Monitor

A lightweight, browser-based utility that monitors your webcam feed to track focus. If you look away from the screen for too long, it triggers a warning tone or a customizable video alarm to help you maintain attention.

---

## ⚡ Features

- **Real-Time Tracking:** Uses lightweight computer vision in the browser to detect your gaze direction.
- **Customizable Alarms:** Upload your own alert sound/video or rely on the built-in backup buzzer.
- **Privacy First:** All video processing happens locally in your browser. No data is sent to any server.
- **Hybrid Loops:** Uses `requestAnimationFrame` with a background timer fallback to keep monitoring active even if the tab loses focus.

---

## 🚀 Quick Start / How to Use

Since this project is completely self-contained in a single HTML file, getting started is instant:

1. **Download or clone** the repository.
2. Open `eyes-front-default-video.html` in any modern web browser (Chrome, Edge, Firefox).
3. Click **Enable Camera** to grant webcam permissions.
4. (Optional) Click **Pick Alert Video** to choose a custom alarm file.
5. Calibrate, set your threshold, and click **Test Alert** to start.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (Custom variables, responsive grid design)
- **Fonts:** Sora, Inter, and JetBrains Mono via Google Fonts
- **Logic:** Vanilla JavaScript with responsive canvas rendering
