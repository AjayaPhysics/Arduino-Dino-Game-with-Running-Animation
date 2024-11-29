# Arduino-Dino-Game-with-Running-Animation
This project is a simple Dino Game implemented using Arduino, a 16x2 I2C LCD, push buttons, and a buzzer. The Dino and the obstacle both feature animated running effects for a visually dynamic experience.
Hardware Requirements
Arduino Uno/Nano/Mega
16x2 I2C LCD Display
Push Buttons (2 buttons: Jump and Reset)
Buzzer
Resistors (Pull-down resistors for buttons)
Jumper Wires
Connections
16x2 I2C LCD
LCD Pin	Arduino Pin
VCC	5V
GND	GND
SDA	A4
SCL	A5
Push Buttons
Button	Arduino Pin	Other Connection
Jump Button	D2	GND (with pull-down resistor)
Reset Button	D3	GND (with pull-down resistor)
Buzzer
Buzzer Pin	Arduino Pin
Positive (+)	D4
Negative (-)	GND
# Dino Game on Arduino with 16x2 LCD and Animation

This project implements a simple Dino Game using Arduino, an I2C 16x2 LCD, push buttons, and a buzzer. Both the Dino and the obstacle feature animated running effects for a dynamic visual experience.

## Features
- Animated Dino and Obstacle
- Jump functionality
- Score counter
- Reset option

## Hardware Requirements
- Arduino Uno/Nano/Mega
- 16x2 I2C LCD Display
- Push Buttons (Jump and Reset)
- Buzzer
- Breadboard and Wires

## Connections
### LCD
| LCD Pin | Arduino Pin |
|---------|-------------|
| VCC     | 5V          |
| GND     | GND         |
| SDA     | A4          |
| SCL     | A5          |

### Push Buttons
| Button        | Arduino Pin | Other Connection          |
|---------------|-------------|---------------------------|
| Jump Button   | D2          | GND (with pull-down resistor) |
| Reset Button  | D3          | GND (with pull-down resistor) |

### Buzzer
| Buzzer Pin  | Arduino Pin |
|-------------|-------------|
| Positive (+)| D4          |
| Negative (-)| GND         |

## How to Play
1. Press the **Reset Button** to start the game.
2. Use the **Jump Button** to avoid obstacles.
3. Score increases each time the Dino successfully avoids an obstacle.
4. If the Dino collides with an obstacle, the game ends with a "Game Over" message.

## License
This project is licensed under the MIT License.
