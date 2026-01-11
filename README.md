# Gesture Controlled 3D Particles

An interactive **gesture-controlled 3D particle visualization** built using **Three.js** and **MediaPipe Hands**.  
This project uses real-time webcam input to control particle **scale, color, and shape** based on natural hand gestures.

It demonstrates browser-based computer vision integration with GPU-accelerated graphics and intuitive gesture interaction.

---

## 🔗 Live Demo

👉 **Live Preview:** https://bhavanish-mantri.github.io/3D_particle/

> Best experienced on desktop browsers with webcam support (Chrome recommended).

---

## ✨ Key Features

- 🎥 **Real-time hand tracking** using MediaPipe Hands
- 🌌 **Custom 3D particle system** rendered with Three.js and GLSL shaders
- 🤏 **Pinch gesture** (thumb + index) to dynamically scale particles
- 🎨 Control particle **color** via horizontal hand movement
- ✋ **Finger count detection** to switch particle formations:
  - **1 Finger** → Fireworks
  - **2 Fingers** → Heart
  - **3 Fingers** → Saturn Ring
  - **4 Fingers** → Flower
- ⚡ All particle effects computed on the GPU for smooth performance

---

## 🛠️ Technologies & Tools

- **HTML / CSS / JavaScript**
- **Three.js** – WebGL-based 3D rendering
- **MediaPipe Hands** – Real-time hand landmark detection
- **GLSL** – Vertex and fragment shaders
- **WebRTC** – Browser camera access

---

## 🧠 Concept & Approach

This project uses MediaPipe to detect hand landmarks in each video frame.  
Gesture signals such as pinch distance, finger count, and horizontal hand position are mapped to shader uniforms that control particle system behavior, enabling real-time interaction between user movement and rendered visuals.

---

## 📁 Project Structure
```
index.html
```

> The project is currently contained in a single HTML file for simplicity and portability.

---

## 📌 What This Project Demonstrates

- Browser-based real-time computer vision workflows
- Gesture-driven interaction design
- Shader programming and GPU particle systems
- Integrating MediaPipe with WebGL pipelines
- Mapping physical user motion to visual feedback

---

## ⚠️ Limitations

- Requires a webcam and camera permission
- Gesture detection accuracy varies with lighting conditions
- Performance may vary on low-end hardware

---

## 🚀 Future Enhancements

- Support for two-hand interactions
- Gesture filtering for smoother transitions
- Modular shader files
- Recording / screenshot capabilities
- Mobile browser support

---

## 📄 License

This project is open-source and intended for learning, experimentation, and demonstration purposes.
