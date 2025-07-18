# Stair-Light-System
# 🚶‍♂️ Stair Lighting System using Arduino UNO  This project is a smart stair lighting system designed using Arduino UNO. It detects a person approaching the stairs using IR sensors and lights up the stair LEDs one by one to enhance visibility, aesthetics, and energy efficiency.
---

## 🔧 Features

- Motion detection using IR Sensors
- Automatic LED activation in stair-wise sequence
- Energy-efficient lighting solution
- Beginner-friendly Arduino circuit
- Neat and clean wiring layout
- Real-time demonstration with simulation support

---

## 🧠 Components Used

- Arduino UNO
- IR Sensors (x2)
- LED Lights (x10 or as required)
- Jumper wires
- Breadboard
- Resistors

---

## 📷 Project Preview

>Check Project Demo on LinkedIn account 
www.linkedin.com/in/raazia-mehmood-22199532

---

## 🖥️ Code

The code is available in the `stair_lighting.ino` file. It is well-commented for easy understanding and modification.

📝 How It Works
IR sensor detects motion at the bottom of the stairs.

The microcontroller (Arduino UNO) triggers LEDs in sequence.

Lights stay ON for a few seconds and then turn OFF automatically.

Reverse triggering can be set for descending movement.

```cpp
// Example Code Snippet
if (digitalRead(sensor1) == HIGH) {
    for (int i = 0; i < numLEDs; i++) {
        digitalWrite(ledPins[i], HIGH);
        delay(200);
    }
}
🙋‍♀️ Created By
Raazia Mehmood
Student at National University of Computer & Emerging Sciences (FAST-NUCES)
Passionate about embedded systems, ethical hacking, and automation.
