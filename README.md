# Voice-Controlled Wheelchair using Raspberry Pi

This project demonstrates a **voice-controlled wheelchair system** using a **Raspberry Pi**. The system allows physically challenged individuals to navigate their wheelchair using simple voice commands, enhancing mobility and independence.

---

## 🔧 Features

- 🎙️ Voice command recognition for directions (e.g., "forward", "backward", "left", "right", "stop")
- 📦 Built on Raspberry Pi for low-cost, compact control
- 🎧 Integration with a microphone for real-time voice input
- 🛞 Motor control via GPIO pins
- 💡 LED/Visual feedback for debugging and status

---

## 🧰 Tech Stack

- **Hardware**: Raspberry Pi 3/4, Motor Driver (L298N), DC motors, Microphone
- **Software**: Python, SpeechRecognition, PyAudio, RPi.GPIO

---

## 🚀 Getting Started

### Prerequisites

- Raspberry Pi with Raspbian OS
- Microphone connected to USB port or Pi jack
- Install required libraries:
  
```bash
pip install SpeechRecognition
pip install pyaudio
