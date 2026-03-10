# Automated-Darkness-Lamps
Automated Darkness Lamp is a simple electronics project that automatically turns a lamp ON in darkness and OFF in daylight using a light dependent resistor (LDR) sensor circuit.

## **WORKING PRINCIPLE:**
The system uses an LDR and fixed resistor voltage divider to sense ambient light intensity. The Arduino reads the voltage across the fixed resistor and compares it with a predefined threshold value. In bright light, the LDR resistance decreases, causing a higher voltage reading and the relay keeps the lamp OFF. In darkness, the LDR resistance increases, resulting in a lower voltage reading; once it falls below the threshold, the relay activates and turns the lamp ON automatically.

## **MATERIAL USED:**
- Arduino UNO
- LDR
- Relay Module
- Resistors and Power Supply
- Light Bulb
- Breadboard and basic electronic components

## **KEY LEARNING OUTCOMES:**

- Understanding sensor-based automatic control systems
- Practical implementation of voltage divider circuits
- Using transistors as electronic switches
- Basic hardware prototyping and circuit debugging
- Concepts of energy-efficient automated systems
