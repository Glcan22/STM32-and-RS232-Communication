#This project demonstrates the communication between an STM32F103C8 microcontroller and a computer using RS-232 protocol.
The primary goal of this project is to send a "Hello World" message from the STM32 to the terminal at regular intervals, while enabling communication via the Virtual Terminal.

Using the keyboard on the computer, the user can send input values (either 1 or 0) to the STM32. If the message 1 is received, an LED connected to the STM32 is turned on. Conversely, if the message 0 is received, the LED is turned off. This communication is achieved using UART, and the RS-232 protocol is used for its full-duplex capability, allowing simultaneous sending and receiving of messages between the two devices.
