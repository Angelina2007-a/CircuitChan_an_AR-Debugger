<div align="center">

# 🔬 Circuit-Chan Vision
### AI-Powered AR Circuit Debugger

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript)
![Vite](https://img.shields.io/badge/Vite-6-646CFF?logo=vite)
![Gemini AI](https://img.shields.io/badge/Google-Gemini_AI-4285F4?logo=google)
![AR](https://img.shields.io/badge/AR-Augmented%20Reality-purple)
![License](https://img.shields.io/badge/License-MIT-green)

**An AI-powered Augmented Reality assistant that detects, analyzes, and debugs electronic circuits using computer vision and Gemini AI.**

</div>

---

# 📖 Overview

Circuit-Chan Vision is an intelligent AR-based electronics debugging assistant designed for students, hobbyists, and engineers.

Using a device camera, the application analyzes breadboards and PCBs, recognizes electronic components, identifies wiring mistakes, and provides AI-generated debugging suggestions in real time.

Instead of manually tracing circuits, users receive instant visual feedback and detailed explanations, making circuit debugging faster and easier.

---

# ✨ Features

## 📷 AR Circuit Analysis

- Analyze breadboards using your camera
- Detect electronic components automatically
- Supports both breadboards and PCBs

---

## 🤖 AI-Powered Debugging

Gemini AI analyzes the captured image and provides:

- Wiring fault detection
- Incorrect pin placement
- Component identification
- Possible causes of failure
- Step-by-step debugging suggestions

---

## 🔍 Component Recognition

Recognizes common electronic components including:

- Resistors
- Capacitors
- LEDs
- ICs
- Logic Gates
- Jump Wires

---

## ⚡ Logic State Recognition

Understands digital logic circuits and identifies configurations such as:

- AND Gate
- OR Gate
- NAND Gate
- NOR Gate
- NOT Gate
- XOR Gate

---

## 🛠 Fault Detection

Detects common mistakes including:

- Loose connections
- Missing wires
- Wrong polarity
- Short circuits
- Incorrect IC orientation
- Wrong resistor placement

---

## 📚 AI Learning Assistant

Provides educational explanations for:

- Component functions
- Pin configurations
- Circuit operation
- Internal working principles
- Troubleshooting techniques

---

# 🏗️ System Architecture

```text
               Camera
                  │
                  ▼
      Image Capture & Processing
                  │
                  ▼
         Gemini Vision Analysis
                  │
      ┌───────────┴───────────┐
      │                       │
      ▼                       ▼
Component Detection      Fault Detection
      │                       │
      └───────────┬───────────┘
                  ▼
          AI Debugging Report
                  │
                  ▼
          User Interface (React)
```

---

# 🛠 Tech Stack

## Frontend

- React 19
- TypeScript
- Vite

## AI

- Google Gemini API
- Gemini Vision

## UI

- Lucide React Icons

## Development

- Node.js
- npm

---

# 📂 Project Structure

```
CircuitChain_AR_Debugger/

│── components/
│     └── CircuitCanvas.tsx

│── services/
│     └── geminiService.ts

│── my_circuit_dataset/
│     └── circuit_tuning.jsonl

│── App.tsx
│── index.tsx
│── package.json
│── vite.config.ts
│── README.md
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/CircuitChain_AR_Debugger.git

cd CircuitChain_AR_Debugger
```

---

## Install Dependencies

```bash
npm install
```

---

## Configure API Key

Create a `.env.local` file.

```env
GEMINI_API_KEY=YOUR_API_KEY
```

---

## Start Development Server

```bash
npm run dev
```

Visit

```
http://localhost:5173
```

---

# 📸 How It Works

1. Open the application.
2. Allow camera access.
3. Point the camera at your breadboard or PCB.
4. Capture the circuit image.
5. Gemini AI analyzes the circuit.
6. View detected components and debugging suggestions.

---

# 📷 Screenshots

Add your screenshots here.

```
screenshots/

home.png

camera-view.png

analysis.png

debug-report.png
```

---

# 🎥 Demo

Add your demo video link here.

Example:

```
https://youtu.be/your-demo
```

---

# 🎯 Use Cases

- Electronics Labs
- Engineering Education
- DIY Projects
- PCB Inspection
- Breadboard Debugging
- Robotics Projects
- Embedded Systems Learning

---

# 🚀 Future Improvements

- Live AR overlay on detected components
- 3D component recognition
- PCB trace analysis
- Oscilloscope integration
- Multimeter data support
- Voice-guided debugging assistant
- Offline AI model support
- Multi-language assistance

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 👨‍💻 Author

**Angelina Raj**

AI & Machine Learning Student

GitHub: https://github.com/Angelina2007-a

LinkedIn: https://www.linkedin.com/in/angelina-raj-7a601633b/

---

# ⭐ Support

If you found this project useful,

⭐ Star the repository

🍴 Fork the project

📢 Share it with others

---

<div align="center">

### ⚡ Making Electronics Debugging Smarter with AI & Augmented Reality

Made with ❤️ using React, TypeScript, Vite, and Google Gemini AI.

</div>
