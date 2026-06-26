# Arduino-UNO-Q-INDUS
Person Detection with LED Matrix Display
A complete person detection application for Arduino Uno Q that displays real-time person count on both the LED matrix and web UI.

📋 Overview
This application uses the Arduino Uno Q's dual-processor architecture to:

Python (MPU): Run video object detection using the VideoObjectDetection brick

C++ (MCU): Control the LED matrix and built-in LED in real-time

Web UI: Display person count and detection results

✨ Features
✅ Real-time person detection using computer vision

✅ LED matrix display showing:

👤 Person icon when detected

🔢 Person count (0-99)

✅ Web UI with:

Big person count display

Recent detections list

Confidence threshold slider

Reset button

✅ Built-in LED blinks on detection

✅ Bidirectional communication between Python and C++ via Bridge
