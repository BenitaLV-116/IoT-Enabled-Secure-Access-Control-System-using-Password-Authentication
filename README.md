# IoT-Enabled Secure Access Control System using Password Authentication

This project is a password-based access control system using Arduino Uno, a keypad, and a servo motor. The system ensures secure entry by verifying user-inputted passwords and controlling the servo motor to grant or deny access.

## Why This Project is Useful
- Provides a low-cost, efficient solution for door security.
- Ideal for home automation, office security, or DIY smart locks.
- Uses Arduino Uno, making it easy to modify and integrate with other IoT devices.

## Hardware Requirements
- Arduino Uno
- 4x4 Keypad
- Servo Motor (SG90)
- Jumper Wires
- Power Supply

## Software Requirements
- Arduino IDE
- `Servo.h` Library (for controlling the servo motor)

## Installation & Setup
1. Install the Arduino IDE from [Arduino Official Website](https://www.arduino.cc/en/software).
2. Connect the hardware components as per the wiring diagram.
3. Install the required library:
   ```cpp
   #include <Servo.h>
   ```
4. Upload the provided code to the Arduino board.

## Working Principle
1. The user enters a password using the 4x4 keypad.
2. The Arduino verifies the entered password.
3. If correct, the servo motor rotates to unlock the door.
4. If incorrect, access is denied, and the system remains locked.


For any issues or suggestions, reach out via GitHub Issues or email.


