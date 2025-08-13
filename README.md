CAN Vehicle Monitoring Simulation - README
------------------------------------------
This project is a C-based embedded systems application that implements multiple hardware interface modules including:
ADC (Analog-to-Digital Conversion)
CAN (Controller Area Network) communication
LCD display interface
I2C communication
Interrupt handling
Node-based system architecture (e.g., MAIN_NODE, FUEL_NODE, INDICATOR_NODE)
It is designed for microcontroller environments and can be adapted for various automotive, industrial, or IoT use cases.

FEATURES
------------------------------------------
Modular design with separate .c and .h files for each peripheral.
CAN bus communication support.
LCD display output for system status.
I2C communication for sensor/device interfacing.
External interrupt support for real-time responsiveness.
Example node programs to demonstrate integration.

Project Structure
------------------------------------------
adc.c / adc.h                # ADC driver implementation
can.c / can.h                # CAN communication functions
lcd.c / lcd.h                # LCD display control
i2c.c / i2c.h                # I2C driver
interrupt.c / interrupt.h    # Interrupt handling
FUEL_NODE.c                  # Node handling fuel data
MAIN_NODE.c                  # Main controller node
INDICATOR_NODE.c             # Indicator control node
defines.h                    # Project-wide definitions
delay.c / delay.h            # Delay utilities
