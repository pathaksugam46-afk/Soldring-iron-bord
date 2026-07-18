# 24V DC Temperature Control PCB

A compact and reliable **24V DC Temperature Control PCB** designed for industrial and DIY temperature control applications. The board uses the **LM358 Dual Operational Amplifier** as the main controller to compare the temperature sensor signal with a reference voltage and automatically switch the output when the preset temperature is reached.

---

## Preview

### PCB


<img width="1410" height="917" alt="image" src="https://github.com/user-attachments/assets/e0e27066-15ac-4a39-a594-097722d9d624" />


### Schematic


<img width="967" height="822" alt="image" src="https://github.com/user-attachments/assets/eac491a9-4971-4a1a-a41b-d5cfbcec5baf" />


---

## Features

-  24V DC power supply
-  Supports analog temperature sensors
-  LM358-based comparator circuit
-  Adjustable temperature set point
---

## Specifications

| Parameter | Value |
|-----------|-------|
| Supply Voltage | 24V DC |
| Controller | LM358 |
| Sensor Type | Analog Temperature Sensor |
| Output | Relay / MOSFET / Transistor (Depending on Version) |
| PCB Type | Through-hole / Mixed Components |

---

##  Supported Sensors

This PCB can work with:

- LM35
- NTC Thermistor
- PTC Thermistor
- Other analog temperature sensors

> **Note:** The sensor must provide an analog voltage proportional to temperature.

---

## How It Works

1. Apply **24V DC** to the power input.
2. Connect a compatible temperature sensor.
3. Adjust the potentiometer to set the desired switching temperature.
4. The LM358 compares:
   - Sensor voltage
   - Reference voltage
5. When the threshold is reached, the output changes state.
6. The output can drive:
   - Cooling Fan
   - Heater
   - Relay
   - Alarm
   - Other external circuits

---

## 🔌 Pinout

| Terminal | Description |
|----------|-------------|
| +24V | Power Input |
| GND | Ground |
| Sensor | Temperature Sensor Input |
| OUT | Output |

---


---

## Components Used

- LM358
- Potentiometer
- Resistors
- Capacitors
- Diodes
- Terminal Blocks
- Temperature Sensor Connector
- MOSFET Driver Components

---

## Applications

- Temperature Monitoring
- Cooling Fan Controller
- Heater Controller
- Battery Temperature Protection
- Greenhouse Automation
- Industrial Temperature Control
- Laboratory Equipment
- DIY Electronics Project



##  Safety

- Use only a regulated **24V DC** power supply.
- Double-check wiring before powering the board.
- Observe correct polarity.
- Do not exceed the output current rating.
- Keep the PCB away from moisture and conductive debris.

---



## License

This project is licensed under the **MIT License**.

---

## Author

**Sugam Pathak**

If you found this project useful, consider giving it a ⭐ on GitHub!
