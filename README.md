# Gesture Controlled 3D Particles

An interactive **gesture-controlled 3D particle visualization** built using **Three.js** and **MediaPipe Hands**.  
The project uses real-time hand tracking via a webcam to control particle **scale, color, and shape** through intuitive gestures.

This project focuses on **human–computer interaction**, **GPU-based rendering**, and **real-time input processing** in the browser.

---

## 🔗 Live Preview
> Run locally using a server (camera access required)

---

## ✨ Features

- 🎥 **Real-time hand tracking** using MediaPipe Hands
- 🌌 **GPU-accelerated particle system** using custom GLSL shaders
- 🤏 **Pinch gesture (thumb + index)** to scale particles
- 🎨 **Hand X-axis movement** to dynamically change particle color
- ✋ **Finger count detection** to switch particle shapes:
  - 1 Finger → Fireworks
  - 2 Fingers → Heart
  - 3 Fingers → Saturn Ring
  - 4 Fingers → Flower
- 🧠 Smooth integration of computer vision + WebGL

---

## 🛠️ Technologies Used

- **HTML5 / CSS3 / JavaScript**
- **Three.js** – 3D rendering & shaders
- **MediaPipe Hands** – Hand landmark detection
- **GLSL** – Custom vertex & fragment shaders
- **WebRTC** – Camera input via browser

---

## 📁 Project Structure
```
index.html
```
> Shaders are embedded directly in the HTML to ensure compatibility and avoid async loading issues.

---

