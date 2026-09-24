# Dino-game
A DIY Dino Game built using an Arduino UNO and a 16×2 I2C LCD display.  The player controls the Dino using a push button and must jump over obstacles to survive and increase the score.
## 🎯 Features

- Dino running animation
- Push-button jump control
- Random obstacles
- Collision detection
- Score tracking
- Game restart functionality
- DIY cardboard enclosure

## 🧩 Components Required

- Arduino UNO
- 16×2 I2C LCD Display
- Push Button
- Breadboard
- Jumper Wires
- USB Cable
- White Cardboard for the enclosure

## 🔌 Connections

| Component | Arduino UNO |
|---|---|
| LCD VCC | 5V |
| LCD GND | GND |
| LCD SDA | A4 |
| LCD SCL | A5 |
| Push Button | Digital Pin 2 |

## ⚙️ Working

The Dino is displayed on the 16×2 LCD along with obstacles.

When the player presses the push button, the Dino jumps. The obstacles continuously move toward the Dino. If the Dino hits an obstacle, the game ends.

The score increases as the player successfully avoids obstacles.

## 🏗️ Project Enclosure

The project is placed inside a DIY enclosure made using white cardboard.

## 📸 Project Images

Add project photos here.

## 💻 Programming

The project is programmed using the Arduino IDE.

**Board:** Arduino UNO

**Display:** 16×2 I2C LCD

**LCD Address:** `0x27`

## 🚀 Future Improvements

- Add a buzzer
- Add multiple difficulty levels
- Add a high-score system
- Add more obstacle types
