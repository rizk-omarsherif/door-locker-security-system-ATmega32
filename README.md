# Door Locker Security System

#### The Door Locker Security System is designed to unlock a door using a password. It consists of two ATmega32 Microcontrollers: HMI ECU and Control ECU. The system utilizes various hardware and software components to facilitate password creation, validation, and door unlocking functionalities.

## Features
- Creation and validation of a system password
- Password-protected door unlocking mechanism
- Option to change the system password
- Error handling for incorrect password entries
- Integration with GPIO, LCD, Keypad, DC Motor, EEPROM, I2C, UART, Timer, and Buzzer drivers

## Hardware Components
- ATmega32 Microcontrollers (x2)
- 2x16 LCD
- 4x4 Keypad
- DC Motor
- EEPROM
- Buzzer

## Software Components
- GPIO Driver
- LCD Driver
- Keypad Driver
- DC Motor Driver
- EEPROM Driver
- I2C Driver
- UART Driver
- Timer Driver
- Buzzer Driver

## Implementation
- The project is implemented in C programming language, following a layered architecture model for better organization and maintainability.
- It utilizes the hardware components and software drivers to achieve the desired functionality.

## Usage

- Clone the repository and upload the provided code to an ATmega32 microcontroller.
- Follow hardware setup instructions and connect the required components as specified.
- Power up the system with a suitable power supply.
- Follow on-screen instructions displayed on the LCD to create or enter the system password.
-  Choose from main system options displayed on the LCD.
- Enter the password using the keypad to unlock the door or change the system password.

## Additional Resources
- [LinkedIn Post](https://www.linkedin.com/posts/omar-sherif-rizk_embeddedsystems-avr-project-activity-7081158631039074305-o3t-?utm_source=share&utm_medium=member_desktop) demonstrates the hardware setup and functionality of the Door Locker Security System through a video.

## Contributing
Contributors are welcome to suggest improvements, report issues, and submit pull requests to enhance the functionality and usability of the project.

## License
This project is licensed under the MIT License, allowing for modification, distribution, and commercial use with proper attribution.
