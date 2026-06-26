# Arduino-UNO-Q-INDUS
👤 Person Detection with LED Matrix Display
Complete person detection application for Arduino Uno Q that displays real-time person count on both the LED matrix and web UI.

📋 Overview
This application leverages the Arduino Uno Q's dual-processor architecture to deliver a seamless person detection experience:

🐍 Python (MPU): Runs video object detection using the VideoObjectDetection brick

⚙️ C++ (MCU): Controls the LED matrix and built-in LED in real-time

🌐 Web UI: Displays person count and detection results

The system processes camera input, detects people, and provides instant visual feedback through multiple interfaces.

✨ Features
Core Functionality
✅ Real-time person detection using computer vision

✅ Dual-processor communication via Bridge protocol

✅ Live video processing with configurable confidence thresholds

LED Matrix Display
👤 Person icon displayed when detection occurs

🔢 Person count (0-99) shown prominently

💡 Built-in LED blinks on each detection

Web Interface
📊 Big person count display for easy visibility

📋 Recent detections list with timestamps

🎚️ Confidence threshold slider for sensitivity adjustment

🔄 Reset button for clearing detection history
