# 24V DC Temperature Control PCB

A compact and reliable **24V DC Temperature Control PCB** designed for DIY temperature control. board uses the **LM358 Dual Operational Amplifier** as the main controller to compare the temperature sensor signal with a reference voltage and automatically switch the output when the preset temperature is reached.

---

## Preview

### PCB


<img width="1410" height="917" alt="image" src="https://github.com/user-attachments/assets/e0e27066-15ac-4a39-a594-097722d9d624" />


### Schematic


<img width="967" height="822" alt="image" src="https://github.com/user-attachments/assets/eac491a9-4971-4a1a-a41b-d5cfbcec5baf" />


---

## Features

-  24V DC supply
-  Supports analog temperature sensors
-  LM358-based 
-  Adjustable temperature
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

##Pinout

| Terminal | Description |
|----------|-------------|
| +24V | Power Input |
| GND | Ground |
| Sensor | Temperature Sensor Input |
| OUT | Output |

---







##  Safety

- Use only a regulated **24V DC** power supply.
- Double-check wiring before powering the board.
- Observe correct polarity.
- Do not exceed the output current rating.
- Keep the PCB away from moisture and conductive debris.

---


## Bill of Materials (BOM)

| Qty | Comment | Designator | Footprint | Value | Manufacturer Part | Manufacturer | Supplier Part | Supplier | Category |
|:---:|---------|------------|-----------|-------|-------------------|--------------|---------------|----------|----------|
| 1 | 100nF | C1 | CAP-TH_L5.1-W3.2-P2.5 | 100nF | SR205C104KAR | Kyocera AVX | C1620866 | LCSC | Multilayer Ceramic Capacitor |
| 1 | 470uF | C3 | CAP-TH_BD10.0-P5.00 | 470uF | 35YXJ470M10X16 | Rubycon | C88732 | LCSC | Aluminum Electrolytic Capacitor |
| 1 | 1N4742APF-M | D1 | DO-41_BD2.8-L42.8-P8.00 | — | 1N4742APF-M | STMicroelectronics | C7497920 | LCSC | Zener Diode |
| 1 | TZ-L2-05YYBR2TDJ30-00 | LED1 | LED-TH_BD5.8-P2.54-L-F | — | TZ-L2-05YYBR2TDJ30-00 | TUOZHAN | C779438 | LCSC | LED Indicator |
| 3 | WJ126V-5.0-2P | P1, P2, P3 | CONN-TH_WJ126V-5.0 | — | WJ126V-5.0-2P | KANGNEX | C8404 | LCSC | Screw Terminal Connector |
| 1 | STP80NF70 | Q1 | TO-220AB-3_L10.4-W4.6 | — | STP80NF70 | STMicroelectronics | C361041 | LCSC | N-Channel MOSFET |
| 3 | 100kΩ | R1, R6, R7 | RES-TH_BD2.7-L6.2-P10.0 | 100kΩ | MF1/4W-100K±1%-OT26 | VO | C2843019 | LCSC | Through-Hole Resistor |
| 3 | 47kΩ | R2, R10, R11 | RES-TH_BD2.7-L6.2-P10.0 | 47kΩ | MF1/4W-47K±1%-ST52 | VO | C2857423 | LCSC | Through-Hole Resistor |
| 1 | 1kΩ | R3 | RES-TH_BD2.3-L6.5-P10.0 | 1kΩ | MF1/4W-1KΩ±1%T52 | 华星机电 | C713997 | LCSC | Through-Hole Resistor |
| 2 | 2.2kΩ | R4, R9 | RES-TH_BD2.3-L6.5-P10.0 | 2.2kΩ | MF1/4W-2.2KΩ±1%T52 | 华星机电 | C714002 | LCSC | Through-Hole Resistor |
| 1 | 10kΩ | R5 | RES-ADJ-TH_RK1631110 | 10kΩ | RK1631110U10 | ALPS ALPINE | C370978 | LCSC | Potentiometer |
| 1 | 10kΩ | R8 | RES-ADJ-SMD_RM065-V | 10kΩ | RM065-103(10K) | BOCHEN | C5205021 | LCSC | Potentiometer |
| 1 | 39Ω | R12 | RES-TH_BD5.0-L15.5-P15 | 39Ω | KNP2W-39Ω±5%T | 华星机电 | C714517 | LCSC | Through-Hole Resistor |
| 1 | LM358P | U1 | DIP-8_L9.4-W6.4-P2.54 | — | LM358P | HXY MOSFET | C20616360 | LCSC | Operational Amplifier |
| 1 | 1N5230BPF | U2 | DO-35_BD1.9-L3.9-P7.90 | — | 1N5230BPF | STMicroelectronics | C7497634 | LCSC | Zener Diode |

## License

This project is licensed under the **MIT License**.

---

## Author

**Sugam Pathak**

If you found this project useful, consider giving it a ⭐ on GitHub!
MADE FOR HACKCLUB
