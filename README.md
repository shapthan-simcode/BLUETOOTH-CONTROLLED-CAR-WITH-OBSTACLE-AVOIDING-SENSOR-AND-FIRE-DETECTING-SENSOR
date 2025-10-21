# 🚗 Bluetooth Controlled Car with Obstacle Avoidance and Fire Detection

A smart Arduino-based robotic car that combines manual Bluetooth control with automatic obstacle avoidance and fire detection. Ideal for embedded systems learners and IoT enthusiasts.

## 🔧 Features

- **Bluetooth Control**: Drive the car using a mobile app via HC-05 module.
- **Obstacle Avoidance**: Ultrasonic sensor detects nearby objects and stops or reroutes.
- **Fire Detection**: Flame sensor identifies fire hazards and triggers alerts.
- **Modular Code**: Clean, well-commented Arduino sketch for easy customization.

## 🧰 Components Required

- Arduino Uno or Nano × 1  
- HC-05 Bluetooth Module × 1  
- HC-SR04 Ultrasonic Sensor × 1  
- Flame Sensor (IR or analog) × 1  
- L298N Motor Driver Module × 1  
- DC Motors with Wheels × 2–4  
- Robot Chassis × 1  
- 9V Battery or Li-ion Pack × 1  
- Battery Connector × 1  
- Jumper Wires × As needed  
- Breadboard (optional) × 1  
- Buzzer or LED (for fire alert) × 1  
- Switch (optional) × 1  
- Mobile App (e.g., MIT App Inventor or Arduino Bluetooth Controller) × 1  

## 🧠 Arduino Code Overview

- **Bluetooth Commands**: 'F' (Forward), 'B' (Backward), 'L' (Left), 'R' (Right), 'S' (Stop)
- **Obstacle Logic**: Stops if object detected within 20 cm
- **Fire Logic**: Stops and alerts if flame intensity crosses threshold

## 📲 Mobile App

Use any Bluetooth terminal app or build a custom interface using MIT App Inventor. Send single-character commands to control the car.

## 📸 Demo & Documentation

- Wiring diagrams and sensor placement sketches
- Code walkthrough with comments
- Real-world use cases and safety applications

## 🛠️ How to Run

1. Upload the Arduino sketch to your board.
2. Connect all components as per wiring diagram.
3. Pair HC-05 with your mobile device.
4. Open the app and send movement commands.
5. Test obstacle and fire detection modules.

## 📂 Folder Structure
