# First Arduino Project

Calculates distance via readings from a HC-SR04 sensor, displays it on a 16x2 LCD, and flashes an LED when target is within threshold distance.

## Hardware
- Arduino Uno R3
- HC-SR04 ultrasonic sensor
- 16×2 LCD (HD44780)
- LED and 220Ω resistor
- Breadboard and jumper wires

## Wiring
-----------------------------------------
| Component        | Arduino pin        |
|------------------|--------------------|
| HC-SR04 Trig     | 13                 |
| HC-SR04 Echo     | 12                 |
| LCD RS, E, D4–D7 | 11, 10, 2, 3, 4, 5 |
| LED (via 220Ω)   | 6                  |
-----------------------------------------

## Usage
1. Open `src/ultrasonic_distance_led_alert.ino` in the Arduino IDE.
2. Select **Tools → Board → Arduino Uno** and the correct port.
3. Click **Upload**.
4. Adjust `threshold` in the code to set the alert distance (in cm).
