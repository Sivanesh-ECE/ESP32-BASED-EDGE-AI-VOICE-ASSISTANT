ESP32-Based Edge AI Voice Assistant

📌 Overview

VoxEdge AI is an ESP32-powered Edge AI Voice Assistant designed to demonstrate the integration of Embedded Systems, IoT, and Artificial Intelligence. The system captures voice input through an INMP441 I2S microphone, processes commands, and provides audio feedback using a MAX98357A I2S amplifier and speaker. An OLED display provides real-time status updates, while an LED indicates system activity.

This project showcases how low-cost embedded hardware can be used to build intelligent voice-interactive systems.

⸻

🚀 Features

* 🎤 Real-time voice input using INMP441 I2S Microphone
* 🔊 Audio output through MAX98357A I2S Amplifier and Speaker
* 📟 OLED display for status and user feedback
* 💡 LED activity indication
* 📶 Wi-Fi enabled ESP32 platform
* ⚡ Low-cost Edge AI implementation
* 🔧 Modular hardware architecture

⸻

🛠️ Hardware Components

Component	Quantity
ESP32 Dev Board	1
INMP441 I2S Microphone	1
MAX98357A I2S Amplifier	1
2W 4Ω Speaker	1
SSD1306 OLED Display (128x64)	1
5mm LED	1
220Ω Resistor	1
Jumper Wires	As Required

⸻

🔌 Wiring Connections

INMP441 Microphone → ESP32

INMP441	ESP32
VDD	3.3V
GND	GND
WS	GPIO 25
SCK	GPIO 26
SD	GPIO 33
L/R	GND

MAX98357A Amplifier → ESP32

MAX98357A	ESP32
VIN	5V
GND	GND
DIN	GPIO 22
BCLK	GPIO 27
LRC	GPIO 14

OLED Display → ESP32

OLED	ESP32
VCC	3.3V
GND	GND
SDA	GPIO 21
SCL	GPIO 19

Status LED → ESP32

LED	ESP32
Anode (+)	GPIO 18 (via 220Ω resistor)
Cathode (-)	GND

⸻

🏗️ System Architecture

Voice Input (INMP441)
↓
ESP32 Processing Unit
↓
AI Command Processing
↓
OLED Status Display
↓
MAX98357A Audio Amplifier
↓
Speaker Output

⸻

📚 Skills Demonstrated

* Embedded Systems Design
* ESP32 Development
* Edge AI Applications
* I2S Communication Protocol
* IoT System Integration
* Hardware Debugging
* Real-Time Embedded Programming
* Electronics Prototyping

⸻

🎯 Future Enhancements

* Wake Word Detection
* Offline Speech Recognition
* Home Automation Integration
* ChatGPT / LLM Integration
* Multi-language Support
* Custom PCB Design
* Battery-Powered Operation

⸻

👨‍💻 Author

Sivanesh G
B.Tech Electronics and Communication Engineering
VIT Chennai

Passionate about Embedded Systems, IoT, Edge AI, Semiconductor Technology, and Hardware Innovation.

⭐ If you found this project interesting, consider giving this repository a star!
