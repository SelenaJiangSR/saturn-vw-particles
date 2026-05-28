# ✦ VW × Saturn · Gesture Studio

A 3D interactive particle system built with Three.js, controlled entirely by hand gestures via webcam. Inspired by Volkswagen's visual identity — a golden Saturn orbited by 50,000 particles, responding to your movements in real time.

**[▶ Try it live](https://SelenaJiangSR.github.io/saturn-vw-particles/)**

<video src="saturn-demo.mp4" controls width="100%"></video>

---

## What it does

Wave your hand in front of the camera to control the scene:

| Gesture | Effect |
|---------|--------|
| ✋ Open palm | Explode particles outward |
| ✊ Fist | Collapse particles inward |
| ☝️ Point up | Rotate scene upward |
| 👇 Point down | Rotate scene downward |
| 🤏 Pinch | Zoom in |
| 🖐 Spread fingers | Zoom out |

---

## Tech stack

| Tool | Purpose |
|------|---------|
| [Three.js](https://threejs.org/) | 3D rendering — Saturn, rings, particle system |
| [MediaPipe Hands](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker) | Real-time hand gesture recognition |
| HTML5 Canvas | Webcam overlay and UI |

Everything runs in a **single HTML file** — no install, no server needed.

---

## Run locally

```bash
# Just open the file
open saturn-vw-particles.html

# Or serve locally for camera access
python3 -m http.server 8000
# then open http://localhost:8000/saturn-vw-particles.html
```

---

## Project background

An experiment in gesture-based human-computer interaction — exploring how physical movement can replace traditional input devices to control generative 3D visuals in the browser.

---

*Made by [Selena J.](https://github.com/SelenaJiangSR)*
