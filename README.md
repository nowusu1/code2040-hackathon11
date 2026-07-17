# 🧠 NeuroSight Assistive Runtime

Privacy-first assistive communication platform that enables eye-controlled interaction using on-device computer vision.

Built during the Code2040 Hackathon to improve accessibility for users with limited motor mobility while preserving privacy through entirely local inference.

---

## Demo

(Add GIF or screenshots here)

---

## The Problem

Traditional eye-tracking systems often require expensive hardware or cloud-based processing.

NeuroSight explores a lightweight, browser-based alternative capable of running entirely on consumer devices while maintaining user privacy.

---

## Features

- 👁️ Real-time eye gaze tracking
- 🧠 On-device MediaPipe inference
- 🎯 Personalized calibration workflow
- ♿ Elder-friendly onboarding
- 🔊 Text-to-Speech integration
- 📱 Works on laptops and tablets
- 🔒 No video uploaded to servers

---

## Tech Stack

- React
- TypeScript
- Vite
- MediaPipe Face Landmarker
- ONNX Runtime
- Cloudflare Workers
- WebRTC

---

## Architecture

Camera
↓
MediaPipe Face Landmarker
↓
Iris Landmark Extraction
↓
Calibration Pipeline
↓
Gaze Classification
↓
UI Interaction
↓
Text-to-Speech

---

## My Contributions

During the Code2040 Hackathon I contributed to:

- Developing the gaze tracking pipeline using MediaPipe Face Landmarker
- Improving iris normalization for more reliable gaze estimation
- Building the calibration workflow and onboarding experience
- Integrating accessibility-focused interaction patterns
- Evaluating gaze accuracy across different devices

---

## Team

This project was developed during the Code2040 Hackathon by a two-person team.

---

## Running Locally

```bash
npm install
npm run dev
```

---

## Future Improvements

- Blink detection
- Vertical gaze estimation
- Multi-user calibration
- Mobile optimization
- Predictive cursor movement

---

## License

MIT
