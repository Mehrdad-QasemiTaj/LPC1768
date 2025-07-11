# 🛠 LPC1768 Development Board

This repository contains resources and documentation for a custom-designed development board based on the NXP LPC1768 ARM Cortex-M3 microcontroller.

## 💡 Features

**Full I/O Access**🕹
All GPIO pins are brought out to easily accessible headers for prototyping and testing.

**USB to Serial (CH340G)** 🔌: 
An onboard CH340G USB-to-Serial converter enables direct programming and communication with the LPC1768 via UART.

**JTAG Interface**🔌: 
Includes a standard IDC socket for JTAG debugging and flashing.

**Crystals**⏱: 
12 MHz main crystal for system clock.
32.768 kHz crystal for the RTC (Real-Time Clock).
Battery Backup for RTC
A coin-cell battery holder allows RTC operation during power-off.

**External EEPROM (AT24C32)** 💾: Onboard I2C EEPROM for additional non-volatile data storage

**User Interface**🔧: User push button.User LED for general-purpose signaling and debugging.

![LPC1768](Images/LPC1768-3.png)

## License

This project is released under the [MIT License](LICENSE).

## Author

Developed by [Mehrdad Qasemi Taj](https://github.com/Mehrdad-QasemiTaj)

---