# STM32 Development Board Based on STM32F103C8T6

Welcome to the open-source STM32 development board project! This board is designed to simplify embedded development with the STM32F103C8T6 microcontroller. It offers flexible power and communication options while integrating useful peripherals to streamline your projects.

Features

	•	Microcontroller: STM32F103C8T6
	•	Voltage regulation: Buck converter stepping 5V to 3.3V
	•	Built-in TTL: Dual USB-C ports for programming (bootloader via Arduino) and TTL communication
	•	EEPROM: 64KB with 24C64 chip
	•	MicroSD card slot: For expanded storage
	•	ST-Link debugger support: 4 dedicated pins to connect an ST-Link debugger for debugging and flashing
	•	Open-source: All design files, including schematics and board layout, are available

Getting Started

	1.	Programming via USB: Use one of the USB-C ports for programming with the bootloader (compatible with Arduino IDE).
	2.	TTL Communication: Use the second USB-C port for TTL-based communication with external devices.
	3.	Debugging: Connect an ST-Link debugger via the 4 dedicated pins to flash or debug your applications.
	4.	External Storage: Leverage the microSD card slot for applications requiring additional storage.
	5.	EEPROM: Utilize the 64KB EEPROM for non-volatile data storage.

Requirements

	•	STM32F103C8T6: To run your embedded applications.
	•	ST-Link: For debugging and programming.
	•	Arduino IDE: To program the board using the bootloader.

How to Contribute

This is an open-source project, and contributions are welcome! Feel free to fork the repository, report issues, or submit pull requests.
