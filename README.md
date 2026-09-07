# 24V DC Temperature Control PCB

This is my first PCB design project. I made this board as a simple temperature controller for a 24V DC soldering iron. The circuit is based on the **LM358 operational amplifier**, which compares the temperature sensor voltage with a reference voltage and switches the output when the set temperature is reached.

I designed both the schematic and PCB in EasyEDA as a way to learn PCB design and analog circuits.

---

## Preview

### PCB

<img width="1410" height="917" alt="PCB" src="https://github.com/user-attachments/assets/e0e27066-15ac-4a39-a594-097722d9d624" />

### Schematic

<img width="967" height="822" alt="Schematic" src="https://github.com/user-attachments/assets/eac491a9-4971-4a1a-a41b-d5cfbcec5baf" />

---

## Features

- Works with a 24V DC power supply
- LM358-based temperature control circuit
- Adjustable temperature using a potentiometer
- Easy to assemble and modify

---



## Supported Sensors

The board can work with:

- LM35
- NTC Thermistor
- PTC Thermistor


---

## How it works

 Connect a regulated 24V 
 Connect a compatible temperature sensor.
 Adjust the potentiometer to set temperature.



## Pinout

 +24V = Power Input 
 GND = Ground 
 Sensor = Temperature Sensor Input 
 OUT = Output 



## Bill of Materials (BOM)

| Qty | Component | Value |
|:---:|-----------|-------|
| 1 | LM358P | Dual Operational Amplifier |
| 1 | STP80NF70 | N-Channel MOSFET |
| 1 | 100nF Capacitor | C1 |
| 1 | 470uF Capacitor | C3 |
| 1 | LED | Power Indicator |
| 3 | Screw Terminal | 2-Pin |
| 3 | 100kΩ Resistor | R1, R6, R7 |
| 3 | 47kΩ Resistor | R2, R10, R11 |
| 1 | 1kΩ Resistor | R3 |
| 2 | 2.2kΩ Resistor | R4, R9 |
| 1 | 39Ω Resistor | R12 |
| 2 | 10kΩ Potentiometer | Temperature Adjustment |
| 2 | Zener Diodes | Protection |

> The complete BOM is available in the project files.

---

## What I Learned

This was my first PCB design, so I learned a lot while building it. I learned how to read datasheets, create schematics, route a PCB, fix ERC/DRC errors, and check the final design in 3D before finishing the board.

There were a few mistakes during the design process, but fixing them helped me understand PCB design much better.

---

## License

This project is licensed under the MIT License.

---

## Author

**Sugam Pathak**

Made for **Hack Club**
